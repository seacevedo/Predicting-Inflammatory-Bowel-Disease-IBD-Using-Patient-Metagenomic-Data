# Predicting-Inflammatory-Bowel-Disease-IBD-Using-Patient-Metagenomic-Data
Using microbial diversity metrics, we build a classifier to predict whether or not a patient has IBD. To do this, we considered the species diversity in the gut of several patients.

Species diversity is the number of species that are represented in a community. In the case of the microbiome, it the number of different microbes that we find in individual(s). By understanding the taxonomic composition of metagenomes, we can analyze the diversity of different environments; in this case we can compare the gut microbiota of patients with and without IBD. Species diversity can be described by two measures:

- Alpha diversity: Measures the varaibility of species within a sample. Indeces that estimate alpha diversity consider the following:
    - richness: number of different species present in an environment
    - abundance: number of individuals of each species present in an environment. Abundance considers the evenness of a distribution of individuals among species in an environment.
- Beta diversity: Accounts for the differences in microbial composition between environments.

In the figure below, we can see a visualization of these two concepts. An environment is represented by a circle, which contains a unique combination of species, each with its alpha diversity, represented by the number of unique species in that environment. The beta diversity describes the number of species that differ between each environment.

![alt text](https://github.com/seacevedo/Predicting-Inflammatory-Bowel-Disease-IBD-Using-Patient-Metagenomic-Data/blob/main/ibd_ml/diversity.gif)

In this analysis, we will employ commonly used metrics to estimate species diversity as features for our machine learning algorithms. A more detailed discussion is provided in a jupyter notebook.
