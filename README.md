# courtney_RNAseq_crabs

## **Differential gene expression in snow crabs (*Chionoecetes opilio*) in response to different pH treatments**

[DOI](Courtney%20Skalley,%20&%20Steven%20Roberts.%20(2023).%20course-fish546-2023/courtney_RNAseq_crabs:%20v1.0-RNAseq_snowcrabs%20(v1.0-RNAseq_snowcrabs).%20Zenodo.%20https://doi.org/10.5281/zenodo.7972051) for github repository May 25, 2023

### Update on June 5, 2023: 
Completed DGE using all 63 samples, updated code to combine forward and reverese sequences in DESeq. Visualized data with:
    -   Heatmap
    -   PCA
    -   Volcano plot
    
### Link to results:
-   Rpubs: <https://rpubs.com/cskalley/snowcrabs_dge>
-   Code: <https://github.com/course-fish546-2023/courtney_RNAseq_crabs/blob/970eec8fea6298725a453ccc06ac890338e26598/code/snowcrabs_dge.Rmd>
-   Output: <https://github.com/course-fish546-2023/courtney_RNAseq_crabs/tree/main/output>

I am working with paired end RNA-Seq data prepared and provided by
Laura Spencer.

### End Point

The ultimate goal of this project is to compare gene expression between
snow crabs exposed to low pH levels.

### **Data**

The data is located here, uploaded by LS on 01/12/2022:

<https://drive.google.com/drive/u/1/folders/1w7tqjcd-Rabh0TsWpw-JLTcJ2QbWIh3H>

Detailed metadeta is located here:

<https://docs.google.com/document/d/1HzMTreqnY2BD-oyjEJRA-JECpFE4CXlEoWKkmiaTYis/edit#>

### Samples used in analysis:

Control: samples #1-4 + 5010_1\_S1_L003_R2_001.fastq.gz +
5010_2\_S2_L003_R1_001.fastq.gz + 5010_3\_S3_L003_R1_001.fastq.gz +
5010_4\_S4_L003_R1_001.fastq.gz

pH 7.8 (long exposure): samples #39-42 +
5010_39_S39_L003_R1_001.fastq.gz + 5010_40_S40_L003_R1_001.fastq.gz +
5010_41_S41_L003_R1_001.fastq.gz + 5010_42_S42_L003_R1_001.fastq.gz

Hash for samples 1-4 (control):

-   2e862ecd7a241b25980b261eb6829463    5010_1\_S1_L003_R1_001.fastq.gz

-   c1d0d493367d748ad825f7c2b4535a7b    5010_1\_S1_L003_R2_001.fastq.gz

-   3ba220b8d4e5e128b96fb22a6fdd8e7c    5010_2\_S2_L003_R1_001.fastq.gz

-   5c9c5e94000ea696399b8903aafa9b78    5010_2\_S2_L003_R2_001.fastq.gz

-   70210dee456eb52ad8362a5603049fb4    5010_3\_S3_L003_R1_001.fastq.gz

-   a0c510142e8152e89b85d9d78dbf0b5d    5010_3\_S3_L003_R2_001.fastq.gz

-   5960706ab3acbd635c367f02c70ccaad    5010_4\_S4_L003_R1_001.fastq.gz

-   b8691b8dcbfac0c3f7a37637fd71bc57    5010_4\_S4_L003_R2_001.fastq.gz

Hash for samples 38-41 (long exposure to pH 7.8):

-   d512765b1b412932a78921012be6858a    5010_39_S39_L003_R1_001.fastq.gz

-   960b7db2a6ab538ddc029bf46b1109a3    5010_39_S39_L003_R2_001.fastq.gz

-   5ffc2addd9c17fc5760b8dfcdf2cd2ac    5010_40_S40_L003_R1_001.fastq.gz

-   acdb644ed1172ea3a7817da274d5513f    5010_40_S40_L003_R2_001.fastq.gz

-   0e1e80179a8bf02acba248e7ea91d626    5010_41_S41_L003_R1_001.fastq.gz

-   5efd0698e48a0d0a4e3fe919aba0070f    5010_41_S41_L003_R2_001.fastq.gz
