# Utilizing a dual endogenous reporter system to identify functional regulators of aberrant stem cell and differentiation activity in colorectal cancer
 
## Main
Repository for the custom code (with parameters), MaGeCK commands (with parameters) and MaGeCK-generated statistics, as well as the raw read counts generated as part of the CRISPR genetic knockout screens using the single and dual endogenous reporter systems to reproduce the results.

## Software Requirements 
The standard software requirements for the statistical analyses associated with this study are:
* MaGeCK v.0.5.9.5
* Python v.3.9.1
* R v.4.3.1

## Software Library Requirements
R v.4.3.1
* Seurat v.4.1.1 (and its built-in extension, Mixscape)

Python v.3.9.1
* SciPy v.1.7.0

## Running the code
The Epigenetic_Screen.ipynb in the Reporter System directory provides a walkthrough of the differential guide abundance analyses conducted from the raw read counts and the reproducible statistics and figures directly generated to support the study.

## Repository Structure
<pre>
├── README.md
├── gRNA_motifs.tsv
├── primers.tsv
├── Reporter System                                     
│   └── MaGeCK                       // Directory of MaGeCK-generated results. (L3 + L6: Dual Reporter, L1 + L4: Single GFP Reporter, L2 + L5: Single mKate2 Reporter)
│   └── Epigenetic_Screen.ipynb      // Custom Python code for analyses of CRISPR genetic screen.
├── Validation                                    
│   └── MaGeCK                       // Directory of MaGeCK-generated results for early validation of the endogenous reporter system.
│   └── MaGeCK_stats                       // Directory of MaGeCK-generated results for early validation of the endogenous reporter system.
</pre>

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.

## Citing SomaticSiMu
[Sandor Spisak*, David Chen*, Pornlada Likasitwatanakul*, Paul Doan*, Zhixin Li, Laura Vizkeleti, Viktoria Tisza, Pushpamail De Silva, Marios Giannakis, Brian Wolpin, Jun Qi, Nilay S. Sethi. Utilizing a dual endogenous reporter system to identify functional regulators of aberrant stem cell and differentiation activity in colorectal cancer, bioRxiv.](https://doi.org/10.1101/2023.06.21.545895)



