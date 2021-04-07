# DeCiFer data

This repository contains the simulated data as well as the processed data and DeCiFer’s results for the whole-genome multi-sample tumor sequencing datasets for the prostate cancer patients analyzed in the DeCiFer paper at:

[Gryte Satas†, Simone Zaccaria†, Mohammed El-Kebir†,\* and Ben Raphael\*, 2021](https://doi.org/10.1101/2021.02.27.429196)\
† Joint First Authors\
\* Corresponding Authors

This repository is linked to the [DeCiFer's repository](https://github.com/raphael-group/decifer).

## Simulated data

Simulated data will be available soon...

## Cancer data

This repository contains the processed data in the DeCiFer's input format within the folder `input/prostate`.
The two input files required by DeCiFer are provided in two separate folders:
1. Folder `mutations` contains the mutation input file `{PATIENT}.decifer.input.tsv` for every protate cancer patient `{PATIENT}`
2. Folder `purity` contains the purity input file `{PATIENT}.purity.txt` for every protate cancer patient `{PATIENT}`

In addition, this repository contains the DeCiFer's results presented in the related manuscript for all the prostate cancer patients within the folder `results/prostate`. Each TSV file represents the output dataframe in the DeCiFer's output format.

<a name="contacts"></a>
## Contacts

The data in this repository have been generated as part the DeCiFer's study.
As the DeCiFer's repository, this repository is actively mantained by three previous Postdoctoral Research Associates at Princeton University in the research group of [prof. Ben Raphael](http://compbio.cs.brown.edu/):

- [Simone Zaccaria](https://simozacca.github.io/) (most of algorithmic core, likelihood computation, and Python implementation), group leader of the [Computational Cancer Genomics research group](https://www.ucl.ac.uk/cancer/zaccaria-lab) at UCL Cancer Institute, London, UK

- [Gryte Satas](linkedin.com/in/gryte-satas-23a74844) (most of input/output interfact and CF computations for single mutations), Postdoctoral Research Fellow at Memorial Sloan Kettering Cancer Center, NY, USA

- [Mohammed El-Kebir](http://www.el-kebir.net/) (generation of state trees), Assistant Professor in the Computer Science department at the University of Illinois at Urbana-Champaign (UIUC), IL, USA.
