# BioParser

## Developer(s)
- KOGIC
- Alan An B.Sc.

## Current Release
- v.0.1.0 - alpha (**Under Construction**)

## Description
- BioParser is a Python-based parsing pipeline (and scripts) for bioinformatics for KOGIC.

- The script **fileparser.py** houses all the classes which are yet organized in separate manner (will do in future).

- The current formats that **are** supported include:
1. VCF (Varint Call Format) 
2. FASTQ (FAST-All Format with associated Quality score)
3. GTF (Gene Transfer Format)
4. GCT (Gene Count Table)
5. GEO (Gene Expression Omnibus Metadata Table)
6. HGNC (Human Gene NomenClature Metadata Table)

- The current format **does not** support:
7. SAM/BAM (Binarized Sequence Alignment/Map format)

- It also allows for Fetching Public Dataset on SRA.
- It is under **filefetcher.py** currently.
- Currently, I'm baffled if it is correct for a fetcher to be under "BioParser"/

## Future Updates
The features below **will be** supported in the next update.
1. SAM/BAM parser required
2. GFA parser required


   

