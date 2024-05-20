# Alternative Polyadenylation Quantification
This repository contains information for the quantification of Alternative Polyadenylation (APA) in RNA-seq datasets over neurodevelopment time 
This project uses the QAPA and DEXseq methods to identify 3'UTR lengthening or shortening by comparing two timepoints in neuron differentiation (day 30 with day 0). 

Abstract: The role of post-transcriptional regulation in neurodevelopment is quite pervasive, activating gene programs that give rise to specialized cell 
features and functions. In this context, 3’ untranslated regions (3’UTRs) play a significant role in regulating mRNA translation, stability, and subcellular 
localization. This is mediated by factors such as miRNAs, lncRNAs and RNA-binding proteins (RBPs) that bind regions at the 3’UTR. Longer 3’UTRs present 
multiple such regions, leading to complex regulation patterns, while shorter ones are characterized by simpler patterns. The process through which one 
gene can have transcripts with longer or shorter 3’UTRs is known as alternative polyadenylation (APA). This study aims to characterize APA events in an 
RNA-seq dataset of iPSCs differentiating into cortical neurons. 

![image](https://github.com/neurogeek03/Thesis_Alternative_Polyadenylation/assets/148254213/ac313eb3-544a-4d46-a5fa-4fd504399dcb)

Figure description: Certain RNA transcripts can contain only 1 site for cleavage and polyadenylation, which we call single. When there are multiple cleavage and 
polyadenylation sites, we name the one closest to the coding sequence (CDS) Proximal (P), while the sites downstream are called Distal (D). 

# Quantification Process 

#Step 1: Data alignment to the reference transcriptome (hg38) using Salmon https://salmon.readthedocs.io/en/latest/salmon.html 

#Step 2: Quantification of APA using QAPA https://github.com/morrislab/qapa 

#Step 3: Data preprocessing 
  
#Step 4: Identifying lengthening and shortening events 

#Step 5: Visualizing reads using Gviz 

#Step 6: Quantification of APA using DEXseq 

#Step 7: Comparison of QAPA and DEXseq 

#Step 8: Analysis of Proteomic data and comparison with APA events 

-- Contact --

Author: Maria Eleni Fafouti

Email: marlen.fafouti@outlook.com

LinkedIn: linkedin.com/in/maria-eleni-fafouti-72950920b 

Feel free to reach out if you have any questions or need further assistance!
