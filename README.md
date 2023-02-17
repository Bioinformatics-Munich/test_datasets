# test-datasets: `igfinder`
Test data to be used for automated testing with the Bioinformatics-Munich pipelines

This branch contains test data for the [Bioinformatics-Munich/igfinder](https://github.com/Bioinformatics-Munich/igfinder) pipeline.

## Content of this repository

`design.csv`: Experiment design file for minimal test dataset  
`design_full.csv`: Experiment design file for full test dataset  
`testdata/` : Sub-sampled FastQ files sub-sampled

## Full test dataset origin

The data was obtained from the [publication describing igfinder](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0165473). To produce the test dataset, the original full dataset was processed using the [igfinder workflow](https://github.com/Bioinformatics-Munich/igfinder). The fasta sequences of the identified Ig chains were then used as reference genome to align the full fastq files and detect the reads that map into the chains. The mapping alignments were then back converted to the fastq files provided for the small test set.

### Expression data of mouse-rat synkaryon

[Pubmed](https://pubmed.ncbi.nlm.nih.gov/27788226/), [DDBJ](https://ddbj.nig.ac.jp/resource/sra-submission/DRA004264)

#### Sample information

| SRA ID    | SAMPLE NAME    |
|-----------|----------------|
| DRX045876 | Brg1-hybridoma |
| DRX045877 | Chd2-hybridoma |

