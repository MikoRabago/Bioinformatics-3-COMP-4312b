# Bioinformatics 3 (COMP 4312b)
A repository containing all the file projects that I have for the Basic Bioinformatics (Bioinformatics 1) (BIO 4312d)

Link to this card: https://trello.com/c/7RWUWJ9g

Section: Bioinformatics
Course: Bioinformatics 3 | Coursera
Final Project: link to your GitHub repository
Duration: 4 weeks
Effort: 6 hours per week

Comparing Genes, Proteins, and Genomes (Bioinformatics III)

About this Course
Once we have sequenced genomes in the previous course, we would like to compare them to determine how species have evolved and what makes them different.

In the first half of the course, we will compare two short biological sequences, such as genes (i.e., short sequences of DNA) or proteins. We will encounter a powerful algorithmic tool called dynamic programming that will help us determine the number of mutations that have separated the two genes/proteins.

In the second half of the course, we will "zoom out" to compare entire genomes, where we see large scale mutations called genome rearrangements, seismic events that have heaved around large blocks of DNA over millions of years of evolution. Looking at the human and mouse genomes, we will ask ourselves: just as earthquakes are much more likely to occur along fault lines, are there locations in our genome that are "fragile" and more susceptible to be broken as part of genome rearrangements? We will see how combinatorial algorithms will help us answer this question.

Finally, you will learn how to apply popular bioinformatics software tools to solve problems in sequence alignment, including BLAST.

Wikipedia (BLAST): BLAST (biotechnology)

SKILLS YOU WILL GAIN
(1) Bioinformatics
(2) Graph Theory
(3) Bioinformatics Algorithms
(4) Python Programming

SYLLABUS
Comparing Genes, Proteins, and Genomes (Bioinformatics III)

Introduction to Sequence Alignment
<p>Welcome to class!</p>
<p>If you joined us in the previous course in this Specialization, then you became an expert at <em>assembling</em> genomes and sequencing antibiotics. The next natural question to ask is how to compare DNA and amino acid sequences. This question will motivate this week's discussion of <strong>sequence alignment</strong>, which is the first of two questions that we will ask in this class (the algorithmic methods used to answer them are shown in parentheses):</p>
<ol><li>How Do We Compare DNA Sequences? (<em>Dynamic Programming</em>)</li><li>Are There Fragile Regions in the Human Genome? (<em>Combinatorial Algorithms</em>)</li></ol>

<p>As in previous courses, each of these two chapters is accompanied by a Bioinformatics Cartoon created by talented artist Randall Christopher and serving as a chapter header in the Specialization's bestselling <a href="BioinformaticsAlgorithms.github.io" target="_blank">print companion</a>. You can find the first chapter's cartoon at the bottom of this message. Why have taxis suddenly become free of charge in Manhattan? Where did Pavel get so much spare change? And how should you get dressed in the morning so that you aren't late to your job as a crime-stopping superhero? Answers to these questions, and many more, in this week's installment of the course.</p>
<p><img src="http://bioinformaticsalgorithms.com/images/cover/alignment_cropped.jpg" width="528"></p>

From Finding a Longest Path to Aligning DNA Strings
<p>Welcome to Week 2 of the class!</p>

<p>Last week, we saw how touring around Manhattan and making change in a Roman shop help us find a longest common subsequence of two DNA or protein strings.</p> <p>This week, we will study how to find a highest scoring alignment of two strings. We will see that regardless of the underlying assumptions that we make regarding how the strings should be aligned, we will be able to phrase our alignment problem as an instance of finding the longest path in a directed acyclic graph.</p>

Advanced Topics in Sequence Alignment
<p>Welcome to Week 3 of the class!</p>

<p>Last week, we saw how a variety of different applications of sequence alignment can all be reduced to finding the longest path in a Manhattan-like graph.</p> <p>This week, we will conclude the current chapter by considering a few advanced topics in sequence alignment. For example, if we need to align long strings, our current algorithm will consume a huge amount of memory. Can we find a more memory-efficient approach? And what should we do when we move from aligning just two strings at a time to aligning many strings?</p>

Genome Rearrangements and Fragility
<p>Welcome to Week 4 of the class!</p>

<p>You now know how to compare two DNA (or protein) strings. &nbsp;But what if we wanted to compare entire genomes? When we "zoom out" to the genome level, we find that substitutions, insertions, and deletions don't tell the whole story of evolution: we need to model more dramatic evolutionary events known as <strong>genome rearrangements</strong>, which wrench apart chromosomes and put them back together in a new order. A natural question to ask is whether there are "fragile regions" hidden in your genome where chromosome breakage has occurred more often over millions of years. This week, we will begin addressing this question by asking how we can compute the number of rearrangements on the evolutionary path connecting two species.</p> <p>You can find this week's Bioinformatics Cartoon from Randall Christopher at the bottom of this E-mail. What do earthquakes and a stack of pancakes have to do with species evolution? Keep learning to find out!</p> <p><img width="528" src="http://bioinformaticsalgorithms.com/images/cover/rearrangements_cropped.jpg"></p>
