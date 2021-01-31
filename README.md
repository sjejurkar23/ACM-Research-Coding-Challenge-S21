# ACM Research Coding Challenge (Spring 2021)

## No Collaboration Policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed to use Internet documentation. If you _do_ use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Submission Procedure

Please follow the below instructions on how to submit your answers.

1. Create a **public** fork of this repo and name it `ACM-Research-Coding-Challenge-S21`. To fork this repo, click the button on the top right and click the "Fork" button.
2. Clone the fork of the repo to your computer using `git clone [the URL of your clone]`. You may need to install Git for this (Google it).
3. Complete the Challenge based on the instructions below.
4. Submit your solution by filling out this [form](https://acmutd.typeform.com/to/uqAJNXUe).

## Question One

Genome analysis is the identification of genomic features such as gene expression or DNA sequences in an individual's genetic makeup. A genbank file (.gb) format contains information about an individual's DNA sequence. The following dataset in `Genome.gb` contains a complete genome sequence of Tomato Curly Stunt Virus. 

**With this file, create a circular genome map and output it as a JPG/PNG/JPEG format.** We're not looking for any complex maps, just be sure to highlight the features and their labels.

**You may use any programming language you feel most comfortable. We recommend Python because it is the easiest to implement. You're allowed to use any library you want to implement this**, just document which ones you used in this README file. Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file. However, we highly recommend giving the challenge a try, you just might learn something new!

Solution:

This was my first time dealing with genetic maps so I had to look up what they were and get information on how they are made. I initially came across an article https://academic.oup.com/bib/article/20/4/1576/4037458 which talked about what genome maps are and what technologies are capable of creating such a map with data from a genbank file. This specific article talked about a Java package called CGView, which is what I used to create my map. I read the overview page which mentioned that CGView has a server onto which you can upload a genbank, XML, or tab-delimited file and whose program will then create a circular, zoomable genome map. I downloaded the genbank file from the github cloned repository and uploaded it to their server, which in return gave me a simple circular genome map for the Tomato Curly Stunt Virus, which I then saved as a PNG file. (This is the link to the map generated: http://cgview.ca/maps/dd2f25305ab678ffb81d15e6436ab8c8a78241ab-1).

CGView Overview: https://paulstothard.github.io/cgview/index.html
CGView API: https://paulstothard.github.io/cgview/api_overview.html
CGView Server: http://cgview.ca/ (link I used to upload the genbank file and generate the map)


After looking into what other servers can perform a similar genetic mapping, I came across this link, https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6728899/ which provides all the possible servers capable of accepting a file with the genetic marker and turn them into a circular genome map. 

