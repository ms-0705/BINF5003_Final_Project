BINF5003 Final Project: Tumour-Associated Gene Expression in Lung Adenocarcinoma, Accounting for Smoking Status

DATASET: GSE10072

1. Our interest: We want to look at how gene expression differs between lung tumours and normal lung tissue, especially since smoking is the main cause of lung cancer.

2. The dataset: GEO series GSE10072 (Affymetrix HG-U133A microarray). https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE10072

3. The paper: Landi MT, Dracheva T, Rotunno M, Figueroa JD, Liu H, Dasgupta A, Mann FE, Fukuoka J, Hames M, Bergen AW, Murphy SE, Yang P, Pesatori AC, Consonni D, Bertazzi PA, Wacholder S, Shih JH, Caporaso NE, Jen J. Gene expression signature of cigarette smoking and its role in lung adenocarcinoma development and survival. PLoS One. 2008 Feb 20;3(2):e1651. doi: 10.1371/journal.pone.0001651. PMID: 18297132; PMCID: PMC2249927.

4. What is inside: 107 expression profiles: 58 lung adenocarcinoma samples and 49 non-tumour lung tissue samples, from current, former and never smokers. The sample table includes tissue type and smoking status. It loads directly into R with getGEO("GSE10072").

5. Draft question: Which genes are differentially expressed between lung adenocarcinoma and non-tumour lung tissue and does this relationship vary according to smoking status?
