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

To begin solving this challenge, I did some research into how circular genome maps are made, and the current software that is used to make them. Initially, the most promising sources I found were Circos and the CGview API (created by Paul Stothard). I was drawn to these sources in the beginning because they were written in languages that I was familiar with (java, c++), but Circos seemed overly complicated, and I couldn't find access to the libraries behind CGview. After finding myself at a few dead ends with other approaches from scratch, I decided to try out using python, even though I am not familiar with it at all, and very quickly found some extremely useful libraries, inlcuding BioPython and ReportLab, both of which made both parsing the GenBank file and outputting the map painless. To quickly use these sources, I also used a tutorial from TutorialsPoint which helped me get up to speed with these python libraries.
