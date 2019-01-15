# Primer on the SURF project
Wetlab and programming skills are now indispensible to the modern biologist. As such, to give you a taste of what this project might entail, we have provided two puzzles for you to try out.

These exercises will help gauge your understanding of cloning, troubleshooting, and data analysis in biological sciences. These skills are not taught in a classroom and are gained by practice. Please try your best to complete these exercises and detail your strategy for solving the problem. Please also note anywhere if you have any difficulties solving the problem.

## Plasmid Annotation and WTH?
The following is adapted from a real story that commonly occurs in biology labs.

Your PI is an onerously vague and mysterious person. Before leaving on a 6 month sabbatical to Antartica to photograph penguins and hunt for aliens, they ask you to run some experiments in order to study some vague phenomena of bacterial gene regulation. On your bench is a single PCR tube containing the plasmids of interest and in your email are two wholly unannotated plasmid sequences labeled control.gb and test.gb

By nature of the expedition, your PI will be out of contact for the next 6 months.

**Your task is to deduce what exactly you are being asked to study and complete those experiments before your PI comes back.**

If you are completely clueless about how to solve this problem. Don't worry. *Welcome to grad school!! ;)* Thankfully, your fellow labmates have provided you with some helpful tips for solving this problem.

* Annotate all interesting features/genes in the provided plasmid sequences
  * biobrick parts or derivatives thereof are likely heavily being used
  * bonus points if you can also identify the most likely PDB structures of the proteins being expressed
* Design the primers which will be used to identify your plasmids via colony PCR
* Specify the primers you will use to sequence verify your whole plasmid
  * annotate primers used on the plasmid maps
* Use the annotated plasmid map to figure out what you are studying or testing
* Important details to know in order to perform the experiment:
    1. What resistance gene and origin of replication is the plasmid carrying. Does it even have an origin of replication? What antibiotics will be used?
    2. What reporter proteins are being used or expressed? How will I measure the signal?
    3. What inducible promoters are being used and what inducer chemical do I need to run my experiment?
    4. How will I plot and interpret the data?

### Here are some useful resources
* http://jorgensen.biology.utah.edu/wayned/ape/
* https://blog.addgene.org/plasmid-101-origin-of-replication
* https://blog.addgene.org/plasmids-101-colony-pcr
* https://www.addgene.org/protocols/sequence-analysis/
* https://tmcalculator.neb.com/#!/main
* http://parts.igem.org/Catalog
* http://parts.igem.org/Promoters
* http://parts.igem.org/Ribosome_Binding_Site/about
* https://blog.addgene.org/plasmids-101-terminators-and-polya-signals
* https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch

## Charming the snake charmer. Scientific data analysis with python.
The following is adapted from bebi103 taught by our brillant lab alumni Dr. Justin Bois.

After a night of drunken escapades, caltech graduate students Ravi, Claire, and Michael decided to embark on the age old of question of "do jellyfish sleep?"

More details on this study can be found here:
* http://www.caltech.edu/news/surprising-ancient-behavior-jellyfish-79701

To answer this question, the trio monitored the pulsation of Cassiopea upside-down jellyfish during their night and day phases via timelapse imaging. Provided are the raw data acquired by the researchers.

The task is the following:
1. Download timelapse data.
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/data/cassiopea_pulsation.zip
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/homework/hw8.html
2. Measure the pulsations of the jellyfish via image analysis and obtain time traces of the pulsatile activity
3. Plot the time traces and note on any irregularities
4. Obtain the interpulse times for each jellyfish during night and day phases
5. Plot the distribution of interpulse times for each jellyfish via histogram or ecdf

Finally, based on the provided datasets and plots you have generated, determine if jellyfish really do sleep. What kind of time series random process do the pulses seem to follow?

We will be impressed if you can justify your claim through statistics from frequentist or bayesian methods.

Please submit your responses to this exercise preferrably as a jupyter notebook and make sure we can run it. As a backup, you can export your jupyter notebook as an html5 webpage. Simply include this in your submission file.

### Auxiliary info
If you are feeling inadept at python, you may skip task2 as we do not expect anyone to have background in image analysis. Within the repository, we have already provided the time series data in csv format and you may start your analysis from there.

For those bold enough to accept the challenge or have background in machine learning, we will be impressed if you can write code to do image segmentation with deep neural networks and obtain the time traces. If you choose this path, we recommend using keras and training with convolutional neural networks.

Some helpful machine learning resources
* http://www.yisongyue.com/courses/cs155/2019_winter/
* https://keras.io/
* https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/
* https://machinelearningmastery.com/handwritten-digit-recognition-using-convolutional-neural-networks-python-keras/

### Why are we doing this?
We want to make sure you are not completely inept at understanding and running python scripts provided by your lab mates or are completely clueless at how to plot scientific data. This exercise serves as a useful tutorial before you join the lab.

Although cloning will be a majority of the project, you will have handle raw data from the plate reader and sometimes it is painful to process via excel.

If you lack time, simply focus on the cloning exercise as that will be far more relevant.

### Below are some useful resources
Some tutorials on setting up jupyter notebook and getting started with data analysis in python from bebi103
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/documents.html
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/tutorials/t0a_python_for_scientific_computing.html
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/tutorials/t8b_extracting_info_from_images.html
* http://bebi103.caltech.edu.s3-website-us-east-1.amazonaws.com/2017/tutorials/t8a_time_series.html
* Generating plot using matplotlib will also make your life easier. Bokeh is for fancy people.

## Collaboration
Please adhere to the caltech honor code when completing these exercises. Your responses are to be your own original work. No collaboration is allowed.

## Submission
You may provide your responses and code submissions as a git repository and email us the link. Submit your write ups in the README.md. Include in your submission relevant code, jupyter notebook, the annotated plasmid files, and references.

__*Aim to be brief and concise in the descriptions of what you did and how you solved each problem.*__

Alternatively, you may email us a zip or tar archive of your responses and code.

## Its too hard
Do not worry. We do not everyone to completely get both exercises. If you find them difficult, it just means do not yet have the background for the task at hand. As with everything in life, knowledge and skill is gained over time and with patience. We will be equally impressed just to see you give it your best try. Do not feel bad if you need to leave some sections incomplete.

Best of Luck! :)
