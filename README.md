# NGS Data Analysis of Bean Yellow Mosaic Virus (BYMV)

This project contains the analysis workflow and summary results for BYMV data (SRA: SRX7118692), processed on [Galaxy.eu](https://usegalaxy.eu). The goal was to perform quality control, reference alignment, SNP calling, and de novo assembly.

## Tools Used
- FastQC, Trim Galore, MultiQC
- BWA-MEM2, SAMtools
- LoFreq for variant calling
- Velvet, SPAdes for assembly

## Project Structure
See the `results/`, `scripts/`, and `plots/` folders for output summaries and visuals.

## Data Source
- [NCBI SRA: SRX7118692](https://www.ncbi.nlm.nih.gov/sra/SRX7118692)
