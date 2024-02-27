# acadworkshop2024_lucinda
## set up conda environments and the other dependencies
Make a conda environment called 'acad-euks_1' and then activate it. To do this copy and paste the following information into a file using a text editor (e.g. vim):

```
name: acad-euks_1
channels:
  - conda-forge
  - bioconda
  - defaults
dependencies:
  - python>=3.8,<=3.9
  - Cython>=0.29.24
  - pip
  - pip:
      - pyrle>=0.0.31
      - pyranges>=0.0.112
      - kneed>=0.8.1
      - matplotlib>=3.6.0
  - samtools
  - bowtie2
  - r-base
  - r-ggplot2
  - r-dplyr
  - r-tidyr
  - r-readr
  - fastp
  - vsearch
  - sga
  - seqtk
  - fasta-splitter
  - datamash
  - seqkit
```

The way I did this was by running these commands:
```
vim acad_euks_1.yml
conda env create -f acad_euks_1.yml
conda activate acad_euks_1.yml
```
Next we installed......TO BE CONTINUED

