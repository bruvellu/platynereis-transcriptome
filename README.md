# :worm: *Platynereis dumerilii* full-length transcriptome of developmental stages

To generate a high-quality full-length transcriptome for the annelid *Platynereis dumerilii*, we collected samples from representative developmental stages, from unfertilized eggs to 5 days post-fertilization. Each sample consisted of a bulk mix from 1 to 5 batches of embryos fertilized by different parents. We incubated all batches at 18 degrees Celsius until the desired time point, then collected the embryos into a clean tube and snap-froze them in liquid nitrogen with as little seawater as possible. The samples were stored at -80 degrees Celsius until RNA extraction. We extracted total RNA from the samples using a Trizol protocol. After measuring the RNA concentration with NanoDrop, we created a bulk RNA mix by combining 1 µL from each sample into a new tube. We gave the sample to the Sequencing and Genotyping facility of the Max Planck Institute of Molecular Cell Biology and Genetics, who ran aliquots of this bulk mix through a Bioanalyzer and gel electrophoresis. They found no evidence of RNA degradation. From this sample, they prepared PacBio Iso-Seq libraries using the Express Template Prep Kit 2.0 and sequenced full-length transcripts on a SMRT 8M Cell for 30 hours using a PacBio Sequel II System. They processed the raw movie subreads with SMRT Analysis software, following the Iso-Seq v3 workflow to generate representative circular consensus sequences, demultiplex and remove primers, trim poly(A) tails, and remove concatemers. After transcript clustering and merging, the resulting dataset contained 176,122 polished high-quality isoforms. Using Cogent, we removed redundant isoforms and obtained a dataset with 117,524 transcripts. From this, we generated a dataset containing only the longest isoform for each gene, with 70,003 sequences in total. We calculated descriptive metrics using Transrate. To estimate their completeness, we used BUSCO for metazoa and obtained a score of 85%. Finally, we annotated the longest-isoform dataset using EnTAP. About 85% of the transcripts have a coding sequence. We obtained annotations for 67% of the sequences, while 33% have remained unannotated.

## Datasets

- [`0-Pdum_workflow.zip`](https://zenodo.org/records/14250773/files/0-Pdum_workflow.zip?download=1) [3.40 GB]: Folder with entire pipeline with notebook entries and analyses.
- [`1-Pdum_hq_isoforms.zip`](https://zenodo.org/records/14250773/files/1-Pdum_hq_isoforms.zip?download=1) [180.30 MB]: Fasta with 176,122 polished high-quality isoforms.
- [`2-Pdum_co_isoforms.zip`](https://zenodo.org/records/14250773/files/2-Pdum_co_isoforms.zip?download=1) [70.68 MB]: Fasta with 117,524 non-redundant polished high-quality isoforms.
- [`3-Pdum_co_longest.ip`](https://zenodo.org/records/14250773/files/3-Pdum_co_longest.zip?download=1) [54.85 MB]: Fasta with the 70,003 longest non-redundant polished high-quality isoforms.
- [`4-Pdum_co_longest_annotations.tsv`](https://zenodo.org/records/14250773/files/4-Pdum_co_longest_annotations.zip?download=1) [34.37 MB]: annotations for longest-isoform dataset.

## Citation

Vellutini, B. C., Handberg-Thorsager, M. & Tomancak, P. *Platynereis dumerilii* full-length transcriptome of developmental stages. https://doi.org/10.5281/zenodo.14250773 (2024).
  

