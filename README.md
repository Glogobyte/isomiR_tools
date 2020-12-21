# isomiRs-hidden soldiers in the miRNA regulatory army and how to find them 

List of tools updated 01.01.2021

|Tool name | Type |Tool Features| Year|Authors|Journal/URL| Reference<br/>(DOI number)| 
|---|---|--------------------------------|---|---|---|---|
|#miRMaster | Web| ● Quantification of miRNAs and non-coding RNAs<br/>● Discovering of new miRNAs and isomiRs<br/>● Discovering of new miRNAs and isomiRs<br/>● Quantification on known and novel miRNA with miRDeep2<br/>● Preprocessing (adapter trimming, quality filtering, read collapsing)<br/>● Mapping with Bowtie to various ncRNA (rRNAs, snRNAs, snoRNAs, scaRNAs, lincRNAs, piRNAs, tRNAs)<br/>● Exogenous miRNAs mapping with bacteria and viruses<br/>● Used for validation used samples from lung and blood samples from PAX blood RNA pool | 2017 | Tobias Fehlmann et all. | Nucleic Acids Research<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5587802/10.1093/nar/gkx595 | 10.1093/nar/gkx595|
|QuickMIRSeq|Linux|● Quantify miRNAs and isomiRs<br/>● Avoid of multiple mapping issue of reads of identical sequences<br/>● Clustering and grouping of identical and similar sequences<br/>● Trimming adapters, collapsing, joint mapping with Bowtie<br/>● Remapping reads with mismatches to a reference genome to further reduce the number of false hits|2017|Shanrong Zhao et all.|BMC Bioinformatics<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5359966/|10.1186/s12859-017-1601-4|
|iMir|Linux<br/>Mac|● Identification of miRNAs and other sncRNAs, such as piRNAs<br/>● Adapter trimming, quality filtering, differential expression analysis<br/>● Analysis of sncRNAs and novel miRNAs<br/>● Identification of isomirs using miRanalyzer<br/>● Using miRAnalyzer and miRDeep2<br/>● Statistical analysis to remove low expressed sncRNAs<br/>● Differential Expression using Deseq Quantile normalization<br/>● Target Prediction using TargetScan and miRanda|2013|Giorgio Giurato et all.|BMC<br/>Bioinformatics<br/><br/>Open access<br/><br/>https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-362|10.1186/1471-2105-14-362|
|MIR-isomiRExp|Web|● Analyze the expression patterns or miRNA/isomer levels<br/>● miRNA maturation and processing mechanism at isomiRs levels<br/>● Using MirBase DB, mapping with Bowtie<br/>● Differential expression using Deseq<br/>● Analysis at the isomiR levels based/independent on miRNA locus<br/>● Arm-switching analysis|2016|Li Guo et all.|Nature<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4806314/|10.1038/srep23700|
|miRNAgFree|Linux<br/>Windows|● miRNA prediction based on biogenesis features (known 5’ homogeneity) and isomiR duplex forming<br/>● Uses the sRNAbench preprocessing|2017|EL Aparicio et all.|BioRxiv<br/><br/>https://www.biorxiv.org/content/10.1101/193094v1.full|10.1101/193094| 
|isomiRID|Linux<br/>Mac|● Identification of 5’, 3’ and polymorphic isomiRs<br/>● Identification of non-templated 5’ or 3’ end and variations<br/>● It could be applied to every organism (plants + animals)<br/>● Detection of isomiRs with one mismatch<br/>● Mapping in pre-miRNAs with Bowtie|2013|Luiz Felipe Valter de Oliveira et all.|Bioinformatics<br/><br/>https://academic.oup.com/bioinformatics/article/29/20/2521/276800|10.1093/bioinformatics/btt424|
|MIRPIPE|Web|● Rapid and simple browser-based miRNA homology detection and quantification of miRNAs<br/>● Read counts from isomiRs of the same miRNA are combined. <br/>● Using FASTX-tollkit, Cutadapt, BLASTN|2014|Carsten Kuenne et all.|Bioinformatics<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4816158/|10.1093/bioinformatics/btu573|
|CASMIR|Standalone<br/>Linux|● Sequence-oriented isomiR annotation which allows unbiased identification of global isomiRs from small sequencing data<br/>● Alignment against canonical and precursors from miRBase<br/>● Discovering of canonical, 5’, 3’, polymorphic, mixed type, non-templated isomiRs, quantification using miRDeep2<br/>● In-house trimming and size filtering<br/>● BLAST with in house custom isomiR-BLAST alignment tool<br/>● Differential expression performed with a Poisson regression model combined with a quasi-likelihood approach and AUC based on methods of DeLong and Clarke-Pearson|2018|Chung Wah Wu et all.|BMC Genomics<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pubmed/29801434|10.1186/s12864-018-4794-7|
|IsomiR-SEA|Linux<br/>Windows<br/>Mac|● Provide users with a complete and accurate picture of the miRNAs, isomiRs and conserved miRNA:mRNA interaction sites <br/>● Provide accurate miRNA and isomiRs expression levels<br/>● Use a specialized algorithm for alignment<br/>● Evaluates the positions of the encountered mismatches in analyzed tags|2016|Gianvito Urgese et all.|BMC Bioinformatics<br/><br/>https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-0958-0|10.1186/s12859-016-0958-0|
|DeAnnIso|Web|● Detection and Annotation of IsomiRs from sRNA se- quencing data<br/>● Еxtract the differentially expressing isomiRs with isomiRs expression, isomiRs classification  from paired or multiple samples<br/>● Tissue specific isomiR expression<br/>● Using Bowtie and BLAST with miRBase<br/>● Normalization with RPM<br/>● isomiRs’ classification, 5’ isomiRs, 3’ isomiRs, isomiRs with internal modifications, templated and non-templated <br/>● Target analysis and enrichment analysis of isomiRs with miRanda or RNA hybrid|2016|Yuanwei Zhang et all.|Nucleic Acids Research<br/><br/>https://www.ncbi.nlm.nih.gov/pubmed/27179030|10.1093/nar/gkw427|
|IsomiRage|Windows<br/>Mac|● Identification of miRNA variants (canonical miRNAs, templated and non-templated isomiRs)<br/>● Detects and groups all 3’-,5’- and trimmed variants <br/>● Uses reference sequences from miRBase<br/>● Classification of isomiRs according to the type of modification (uridylation, adenylation,etc)<br/>● Mapping performed with Bowtie with no mismatches to reference and custom genome<br/>● Normalization with RPM and read counts that can be used for comparisons of fold changes and other downstream analyses|2014|Muller Heiko et all.|Frontiers in Bioengineering and Biotechnology<br/><br/>https://www.frontiersin.org/articles/10.3389/fbioe.2014.00038/full|10.3389/fbioe.2014.00038|
|QuagmiR|Standalone<br/>Web|● Designed for the detection and annotation of heterogeneous isomiRs<br/>● Provide extensive customization of the process and reference databases according to user’s diverse research needs<br/>● Can be used to analyze both private datasets and the public datasets that are available to authorized researchers through the CGC|2018|Xavier Bofill-De Ros et all.|Bioimformatics<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6499244/|10.1093/bioinformatics/bty843|
|Jasmine|R + Java|● Identification of isomiR populations.<br/>● Propose a comprehensive isomiR nomenclature<br/>● Uses curated miRBase annotation.<br/>● Adapter trimming (trimmomatic, cutadapt)<br/>● Collapsing trimmed reads (fastx_collapser, fastq _to_fasta from FASTX-toolkit), Quality control (FastQC)<br/>● Mapping with Bowtie with at least one mismatch<br/>● Uses miRBase database|2019|Xiangfu Zhong et all.|Bioinformatics<br/><br/>https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btz806/5612093|10.1093/bioinformatics/btz806| 
|CBS-miRSeq|Linux<br/>Docker<br/>VM|● Color-spaced raw reads<br/>● Read length distribution, summary of adapter removal, mapping statistics, and raw expression count matrix of known miRNAs.<br/>● Using Bowtie with reference genome<br/>● Differential expression analysis using Deseq2, EdgeR<br/>● Identifies isomiRs using miRspring<br/>● Predicts novel miRNA candidates using miRDeep2<br/>● Predicts the most consistent miRNA:mRNA unique pairs, using RNAhybrid, miRanda|2019|Rupesh K. Kesharwani et all.|Computers in Biology and Medicine<br/><br/>https://www.sciencedirect.com/science/article/pii/S001048251930188X|10.1016/j.compbiomed.2019.05.019.|
|sRNAtoolbox|Web|●Expression profiling of small RNAs, prediction of novel microRNAs, analysis of isomiRs<br/>● Differential expression using DESeq, edgeR, and NOISeq<br/>● Target prediction onuser-provided input data based on Miranda, PITA and TargetSpy<br/>● Visualization of sRNA expression data in a genome context using jBrowse|2015|Antonio Rueda et all.|Nucleic Acids Research<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4489306/pdf/gkv555.pdf|10.1093/nar/gkv555| 
|sRNAnalyzer|Web|● miRNA profiling strategies for isomiRs<br/>● Detection of potential SNPs in miRNAs<br/>● Uses Cutadapt, Printseq, FastX for preprocessing and Bowtie for mapping; MirBase and MirGen DB<br/>● Use of LPM (local probability mapping) strategy to increase mapping specificity<br/>● Extensive rRNA and tRNA filtering steps to enhance the accuracy of exogenous RNA mapping<br/>● Exogenous RNA mapping process using sRNAnalyzer|2017|Xiaogang Wu et all.|Nucleic Acids Research<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pubmed/29069500|10.1093/nar/gkx999|
|mirPRo|Linux|● Quantify known miRNAs<br/>● Predict novel miRNAs and miRNA family expression quantification<br/>● IsomiRs identification and categorization<br/>● Arm switching detection<br/>● Using Novoalign, HTSeq and pre-miRNAs from miRBase<br/>● Using DESeq to perform differential expression profile analysis for known and novel mature miRNAs|2015|Jieming Shi et all.|Nature<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4592965/|10.1038/srep14617|
|miRge|Standalone|● MirGeneDB miRNAs were used to assemble positive clusters (known miRNAs and  tRNA, snoRNA, rRNA or mRNA were used to assemble negative clusters (known non-miRNAs)<br/>● Identification of isomiRs<br/>● Novel miRNA detection <br/>● Preprocessing with Cutadapt and mapping (Bowtie)<br/>● Using miRbase and miRGen DB<br/>● Detection of A-to-I editing|2015|Alexander S. Baras et all.|Plos one<br/><br/>Open Access<br/><br/>https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0143066|10.1371/journal.pone.0143066|
|miRDis|Web|● Systematic annotation of known miRNAs and other noncoding RNAs based on read mapped regions <br/>● Prediction of novel miRNAs and noncoding RNAs through assigning ambiguous reads to unique genome region with well-predicted RNA structure <br/>● Detection of candidate exogenous miRNAs transported from dietary species<br/>● Using FASTQC, Cutadapt, Bowtie and EdgeR|2017|Hanyuan Zhang et all.|Briefings in Bioinformatics<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pubmed/28073746|10.1093/bib/bbw140|
|miRMOD|Windows|● Identifies and analyzes miRNA 3’ and 5’ modifications (non-templated additions as well as trimming)<br/>● Using Bowtie with reference genome/pre-miRNA<br/>● Provides useful statistics about various types of miRNA modifications along with its frequencies.<br/>● Target alteration analysis|2015|Abhinav Kaushik et all.|PeerJ<br/><br/>Open Access<br/><br/>https://www.ncbi.nlm.nih.gov/pubmed/26623179|10.7717/peerj.1332|
|mirTools 2.0|Web|● Detection of various types of ncRNAs (miRNA, tRNA, snRNA, snoRNA, rRNA and piRNA)<br/>● Identify miRNA-targeted genes<br/>● Performs functional annotation or miRNA targets (GO, KEGG, PPI)<br/>● Detect differentially expressed ncRNAs with RPM and the Bayesian method<br/>● Detect novel miRNAs using miRDeep|2013|Jinyu Wu et all.|RNA Biology<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3849156/|10.4161/rna.25193|
|Chimira|Web|● Sequences are automatically cleaned, trimmed, size selected and mapped directly to miRNA hairpin sequences<br/>● Identifies epi-transcriptomic modifications in the input sequences. <br/>● Alignment with BLAST to miRbase and differential Expression of miRNAs using Deseq2<br/>● Modification profiles of 3’ and 5’ and internal modifications, uridylation, adenylation and internal modifications or variations of the miRNAs.|2015|Dimitrios M. Vitsios et all.|Bioinformatics<br/><br/>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4595902/|10.1093/bioinformatics/btv380
|miRTOP|Standalone<br/>Linux|● Generation of a new file format mirGFF3.<br/>● It is compatible with the commonly used tools output files (sRNAbench, Prost!, isomiR-SEA, OptimiR e.g.).<br/>● Converts mirGFF3 file into several different types such as count matrix, FASTA and VCF formats.<br/>● Open source and community-based project.|2019|Thomas Desvignes et all.|Bioinformatics<br/><br/>Open Access<br/><br/>https://academic.oup.com/bioinformatics/article/36/3/698/5556118|10.1093/bioinformatics/btz675|
|Prost!|Standalone<br/>Linux|● Aligns reads to a user-defined genomic dataset.<br/>● Groups reads based on their potential genomic origins, seed sequence and annotation.<br/>● Reports frequencies of individual sequence variations with respect to reference genome and the most expressed sequence. <br/>● Uses Cutadapt and FASTX-toolkit for preprocessing, BBMap suite for alignment, MirBase for annotation and Deseq2 for differential expression.|2019|Thomas Desvignes et all.|Nature<br/><br/>Open Access<br/><br/>https://www.nature.com/articles/s41598-019-40361-8|10.1038/s41598-019-40361-8|
|OptimiR|Standalone<br/>Linux|● Detect genotyping errors● Suggested the existence of novel miRNAs and highlighted the allelic imbalance expression of polymiRs in heterozygous carriers.● Uses Cutadapt for preprocessing, Bowtie2 for alignment and miRBase for annotation.● Uses a scoring algorithm to identify the most plausible alignments.● Produces a comparison analysis of genotype data provided by the user and the genotype data that could be inferred from the sequenced reads aligned to polymiRs|2019|Florian Thibord et all.|Bioinformatics<br/><br/>Open Access<br/><br/>https://rnajournal.cshlp.org/content/early/2019/02/28/rna.069708.118|10.1261/rna.069708.118
isomiRs: Analyze isomiRs and miRNAs from small RNA-seq|R library|● Uses as input file the count matrix<br/>● Includes various functions for characterization of miRNAs and isomiRs, clustering, differential expression and visualizations.<br/>● Designed to analyze the output of SeqBuster tool or any other tool after converting to the desire format<br/>● user can control the analysis step by step.|2020|Pantano L, Escaramis G|Bioconductor<br/><br/>http://bioconductor.org/packages/release/bioc/html/isomiRs.html|10.18129/B9.bioc.isomiRs

