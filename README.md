# Writing_user_interaction_python_pipelines

## Prerequisites
```
esearch
```

1. the user of your code will specify the protein family, and the taxonomic group, and then your code will need
to obtain the relevant protein sequence data, and perform all subsequent analyses and outputs in the user's
space on the MSc server.
Do NOT set it up so it will only work in your workspace! As all files/databases/outputs will be made in the
users homespace on the MSc server, the user's allowable starting sequence set probably shouldn't have
more than 1,000 sequences (note, this is just a guideline, not a hard limit!)
How useful the programme will be might depend a bit on how many species are represented in the dataset
chosen by the user (i.e. are the sequences all from one species, or are there many different species?), so it
would probably make sense to tell the user, and give them the option to continue or not continue with the
current dataset?
There are almost certainly other checks that could/should be done at this stage before continuing to the
main processing stages...
2. to determine, and plot, the level of conservation between the protein sequences. Here we are wanting to
establish the degree of similarity within the sequence set chosen. The output should go to screen and be
saved as a file output.
Think carefully about how many sequences you might want to use for the conservation analysis. We used
a programme that does this sort of thing in the lectures, but this time, should you limit the number of
sequences used for the conservation analysis and plotting to some number? If so, working out which ones
to keep could be done in several different ways, some a lot easier than others: the method of selection
choice is up to you, should you go down this route.
3. to scan protein sequence(s) of interest with motifs from the PROSITE database, to determine whether any
known motifs (domains) are associated with this subset of sequences: were there any, and if so, what
were their names?
4. a "wildcard" option for you: to do any other appropriate EMBOSS (or other) analysis that you think might add
relevant biological information to the outputs
I am leaving it up to you to chose what might constitute "relevant biolgical information" that your programme
will provide to the user: you are training to be a bioinformatician, so you should be able to decide, and justify
your choice!
5. maintain and provide for assessment a full git log history of your code writing/commit activities for this
Assignment
