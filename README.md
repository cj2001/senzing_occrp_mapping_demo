# From Raw Data to Resolved Identities: Transforming Your Data for Senzing Entity Resolution
## Step-by-Step Strategies to Prepare Your Data for Accurate, Scalable Identity Matching
### Written by: Dr. Clair J. Sullivan
#### email: clair@clairsullivan.com
#### Last modified: 2025-01-30

## Introduction

This repository contains the code to go with my blog post showing how to map arbitrary data (in this case, the OCCRP Azerbaijani Laundromat data) into a format that can be read by Senzing.  At present, it contains two files:

1. `occrp_17k.csv`: OCCRP transaction data on entities within the Azerbaijani Laundromat
2. `occrp_to_senzing_mapping.ipynb`: Google Colab notebook to load and transform data file into Senzing-readable JSON files

The blog post walks through how to use this notebook to create the JSON files, load them into Senzing, and do some basic EDA.  You can view the blog post [here](https://nbsanity.com/static/0e9908da3f8f9a9deff7f38e1ce655c8/occrp_to_senzing_mapping.html).
