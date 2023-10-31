# Writing_user_interaction_python_pipelines

## Prerequisites
**a. for searching and retrieving from any of the NCBI databases from the edirect package**
```
esearch
efetch
```
**b. for clustering sequences etc**
```
clustalo
```
**c. for doing BLAST analyses etc**
```
makeblastdb
blastn
blastx
blastp
```
**d. EMBOSS**
```
plotcon
```

1.to identify a family of protein sequences from a user-defined subset of the taxonomic tree (e.g. glucose-6-
phosphatase proteins from Aves (birds), or ABC transporters in mammals, or kinases in rodents, or adenyl
cyclases in vertebrates etc.) that could then be processed using.

2.to determine, and plot, the level of protein sequence conservation across the species within that
taxonomic group

3.to scan the protein sequence(s) of interest with motifs from the PROSITE database, to determine
whether any known motifs (domains) are associated with this subset of sequences

4.to do any other appropriate EMBOSS (or other) analysis that you think might add relevant biological
information to the outputs
