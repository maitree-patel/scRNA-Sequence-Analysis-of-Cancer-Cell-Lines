# scRNA-Sequence-Analysis-of-Cancer-Cell-Lines
*Note: project in progress*
## Main Objective
Exploring scRNA-Seq data to analyze the use of existing FDA-approved antibody therapies on other cancers.

## Key Scientific Question
Using available scRNA-seq data from cancer cell lines, how would you explore the use of the following FDA-approved antibody therapies in additional cancers?

Trastuzumab: Targets HER2 and is used in the treatment of HER2-positive breast and gastric cancers.

Bevacizumab: Targets VEGF and is used for a variety of cancers, including colorectal, lung, glioblastoma, breast, liver, and kidney cancer.

## Breaking Down the Question at Hand
**What are cancer-cell lines?**   
Cancer cell lines are tumour cells that continuous grow and divide that are used as models to study cancers. They are maintained under controlled laboratory conditions (*in vitro* to test therapies against cancers. Under appropriate conditions they reflect the genetic makeup of the source cancer. 

**Why are cancer cell lines used to study cancers?**   
Characterizing their genetic properties can help us study diseases by testing compounds (potentials drugs) across them. 

**What is scRNA-Seq?**   
scRNA-Seq is used to study the transcriptomes of individual cells in tissues, i.e. gene expression profiles within each cells. It reveals heterogeinity in contrast to bulk RNA-Seq which combines gene expression values from the cells in a tissue.

**How is scRNA-Seq useful is studying cancer cell lines (what does it reveal)?**   
The heterogeinity of cancer cell lines are captured by scRNA-Seq allowing us to study response to drug therapies.

**What is HER2 and how is it targetted by Trastuzumab?**   
Human epidermal growth factor 2 (HER2) are proteins that makes cells grow. Breast cancer cells are known to have HER2 as surface proteins. Trastuzumab binds to receptor to decrease the expression of HER2. The drug has been FDA approved for breast and gastric cancer. 

**What is VEGF and how is it targetted by Bevacizumab?**
The vascular endothelial growth factor (VEGF) is a protein that stimulates the production of blood vessels. It is produced in cells like platelets, macrophages and also tumour cells and has a function in the vascular system, for example in bone maroow formation, would healing, etc. In tumours, VEGF promotes angiogenesis which is the formation of new blood vessels from existing ones. It is upregulated in hypoxia conditions or by oncogene expression. The development of new vasculature in and around the tumour through angiogenesis promotes tumour grwoth through supply of nutrients and oxygen.

Bevacizumab (an anti-angiogenic treatment) bind to VEGF cell surface receptors limiting blod vessel growth and therefore blood supply to the tumours.

## Kinker et al., 2019

### Important Terminology
**Gene Expression Programs (GEP)**
A set of genes that work together in response to external cues to perform certain functions. This is achieved through transcriptional co-regulation.

**t-distributed Stochastic Neighbor Embedding (t-SNE)**
A non-linear dimensionality reduction method used for linearly non-separable data (that PCA cannot separate out). It is mainly used to understand highly dimensional data by projecting it onto 2-D or 3-D space.

### Questions
**What were the main objectives of the paper?**

**Why?**

**How did the authors handle the potential caveat of co-culturing cell lines before profiling by scRNA-seq? Why do you think that caveat was or was not adequately addressed?**

**The authors identified discrete subpopulations of cells within a subset of individual cell lines (Fig. 2A-B). What might be the reason why some cell lines have these discrete subpopulations while others do not?**

**What are Recurrent Heterogeneous Programs (RHPs) and how were they defined?**

**How do the identified RHPs relate to in vivo programs of heterogeneity in tumors, and what evidence supports this relationship?**

**Where can you download the scRNA-seq data as shown in Figure 1B?**


## References
1. Mirabelli, P., Coppola, L. and Salvatore, M. (2019) ‘Cancer cell lines are useful model systems for Medical Research’, Cancers, 11(8), p. 1098. doi:10.3390/cancers11081098.
2. Gambardella, G. et al. (2022) ‘A single-cell analysis of breast cancer cell lines to study tumour heterogeneity and Drug Response’, Nature Communications, 13(1). doi:10.1038/s41467-022-29358-6.
3. Masood, R., Cai, J., Zheng, T., Smith, D. L., Hinton, D. R., & Gill, P. S. (2001). Vascular endothelial growth factor (VEGF) is an autocrine growth factor for VEGF receptor–positive human tumors. Blood, 98(6), 1904–1913. https://doi.org/10.1182/blood.v98.6.1904
4. Bevacizumab. (2021). Reactions Weekly, 1853(1), 90. https://doi.org/10.1007/s40278-021-94956-3
5. 


