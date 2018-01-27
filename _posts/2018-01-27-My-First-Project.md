---
title: My First Project
---
Tutorials and video guides aside, I wanted to put what I’d learnt to the test in a real life application. I’ll give a little background to what I had in mind and why.

I’ve mentioned before that I work with a lot of raw sequencing data. For those not into science, when I say sequencing data I am referring to DNA sequences. These sequences can be used to work out evolutionary relationships of microorganisms and infer identifications of unknown isolates. I’ve included a couple of links below if case of interest. I also talk about FASTA sequences a lot, so there’s a link on those too.

In a nutshell, I receive a lot of data that requires processing, organising, retrieving and analysing. I’m still no expert in programming but this sounded to me like something Python could help with. Using blue-sky thinking, I came up with a mission statement:

Design a GUI that allows users to sort, batch process sequences, organise the output, retrieve certain output files when required and analyse the output files.

At the time of inception, this was way beyond my capabilities. In fact GUI generation is still beyond my capability, but my plan was to generate the separate scripts and modules before linking them together with a GUI and package the entire thing. Remember, I work in a non-coding environment so requiring users to input commands into a shell or Python interpreter is not an option. And also remember, I’m still writing these retrospectively.

Right of the bat I’d identified several functions I wanted to include. In order of complexity (and thus the order in which I have begun to write code) these are:<br> <br>
•	FASTA analyser (to analyse FASTA sequences)<br>
•	Sequence sorter (to automatically sort raw sequence data by unique elements into folders)<br>
•	Directory rename (to rename multiple folders)<br>
•	Drive organiser (to automatically organise and store processed/output sequence data in a directory)<br>
•	FASTA finder (to retrieve FASTA sequences stored by the previous script, depending on user input)<br>

I’ll be doing a series of blog posts diving in much more detail into each of these modules and plan to put my code on GitHub as I go. I will be modifying the code to make it applicable (hopefully) to the scientific community rather than just my personal use.


In addition I also want to do short posts on useful tips I’m picking up whilst learning Python.

<br>
Resources: <br>
https://blast.ncbi.nlm.nih.gov/Blast.cgi?CMD=Web&PAGE_TYPE=BlastDocs&DOC_TYPE=BlastHelp <br>
https://en.wikipedia.org/wiki/Phylogenetic_tree <br>
https://en.wikipedia.org/wiki/Sanger_sequencing <br>


