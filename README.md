# Genomic analysis of Coccomyxa viridis
* Description of analysis associated with Tagirdzhanova et al. 2023

## Abstract
Lichen symbiosis is centered around a relationship between a fungus and a photosynthetic microbe, usually a green alga. In addition to their main photosynthetic partner (the photobiont), lichen symbioses can contain additional algae present in low abundance. The biology of these algae and the way they interact with the rest of lichen symbionts remains largely unknown. Here we present the first genome sequence of a non-photobiont lichen-associated alga. Coccomyxa viridis was unexpectedly found in 12% of publicly available lichen metagenomes. With few exceptions, members of the Coccomyxa viridis clade occur in lichens as non-photobionts, potentially growing in thalli endophytically. The 45.7 Mbp genome of C. viridis was assembled into 18 near chromosome-level contigs, making it one of the most contiguous genomic assemblies for any lichen-associated algae. Comparing the C. viridis genome to its close relatives revealed the presence of traits associated with the lichen lifestyle. The genome of C. viridis provides a new resource for exploring the evolution of the lichen symbiosis, and how symbiotic lifestyles shaped evolution in green algae.


## Structure of the repository
* `analysis_and_temp_files`: all files generated during labwork and bioinformatic analysis and retained either for reusing, or for documentation purposes. Broken into subfolders by steps
* `code`: all scripts associated with the project. Not including RMarkdown files (they are in `notebook`) and Snakemake files (they are in subfolders in `analysis_and_temp_files`)
* `notebook`: documentation of all labwork and data analysis. Folder contains RMarkdown files used to generate reports, and reports themselves in html. Names match the subfolders of `analysis_and_temp_files`
* `results`: figures and tables generated for the publication, including supplementary

