# NGS Data Analysis of Bean Yellow Mosaic Virus (BYMV)

This project contains the workflow, results, and reports from NGS analysis of BYMV (SRA ID: SRX7118692), performed on [Galaxy.eu](https://usegalaxy.eu).

## Tools Used
- FastQC, Trim Galore, MultiQC
- BWA-MEM2, SAMtools
- LoFreq for SNP calling
- Velvet, SPAdes for assembly
- IGV for visualization

## Results Summary
- Initial mapping rate: 26.98%
- Post-duplicate removal: 37.59%
- SNPs identified via LoFreq
- De novo assembly validated with QUAST and BLAST

## Folder Structure
- `results/`: Contains reports and summary files
- `plots/`: Visuals like FastQC plots or IGV screenshots
- `scripts/`: Command lines or workflow steps
- `references/`: Reference genome links or notes

## Acknowledgment
Analysis was performed using the [Galaxy.eu](https://usegalaxy.eu) platform.

