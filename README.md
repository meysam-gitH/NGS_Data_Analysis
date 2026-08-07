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
```
NGS_Data_Analysis/
  results/            analysis report and MultiQC summaries
    NGS Data Analysis of BYMV_report.pdf   full write-up of the analysis
    MultiQC_BYMV.html.zip                  MultiQC report, BYMV sample
    MultiQC_RF.html.zip                    MultiQC report, RF sample
  Galaxy histories/   exported Galaxy workflow histories (see the note inside)
```

Unzip either MultiQC archive and open the enclosed `.html` file in a browser
to view the interactive quality-control report.

## Acknowledgment
Analysis was performed using the [Galaxy.eu](https://usegalaxy.eu) platform.

