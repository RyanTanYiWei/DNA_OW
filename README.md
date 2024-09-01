# Discourse Network Analysis - Omgevingswet in the Netherlands

## Abstract
This thesis looks into Duch newspaper articles to study the public discourse surrounding the recently introduced the Environmental and Planning Act, a policy that shifts the spatial planning paradigm in the Netherlands. The study focuses on policy beliefs as a means to describe and explain the implementation challenges involved in this system revision. Results describe the emergent topics of discourse, points of conflicts, evolution of discourse coalitions and context, and also changing behaviours of groups of actors.

## Folder Structure
The repository is structured as follows:
- [raw_data](raw_data): Original set of dutch newspaper articles from the LexisNexis database can be found here.
- [translated_data](translated_data): Processed and translated set of newspaper articles, formatted to be imported into the Discourse Network Analyzer.
- [DNA_files](DNA_files): Folder contains the Discourse Network Analyzer which primarily helped the coding of statements and actor attributes.
- [outputs_analysis](outputs_analysis): Folder contains analysis outputs from the discourse analysis.
- [outputs_diagrams](outputs_diagrams): Folder contains figure/diagrams outputs from the discourse analysis.
- [_dump](Dump): Folder contains data/archived data that is not relevant to the final model and analyses.

## Notebooks
The key notebooks are as follows:
- [DataProcessing_FileChunks.ipynb](DataProcessing_FileChunks.ipynb): Python notebook processes, cleans and translate the raw_data into a useable format for the qualitative coding.
- [Qualitative Content Analysis.Rmd](raw_data): R notebook analyses the qualitative content of the final coded dataset.
- [rDNA.Rmd](raw_data): R notebook constructs and analyses the discourse networks.
