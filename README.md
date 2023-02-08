# Thesis
Repository for my master's thesis project: INTEGRATIVE SINGLE CELL ANALYSIS OF SURFACE PROTEINS AND TRANSCRIPTOMES OF BONE MARROW T/NK-CELLS ACROSS HEMATOLOGICAL MALIGNANCIES

## WORK PACKAGES: 

### WP1: Identification of T- and NK-cell clusters and comparison of established marker gene and protein expression between the clusters. 
Q1: Which clusters corresponds to different T/NK cell types based on marker gene(s) established in recent publications? 
Q2: Can we identify similar clustering results based on transcriptomes or surface protein markers when comparing to clusters obtained from joint representation by the neural network? 
Task 1: Clustering analysis based on transcriptomes/surface proteins and based on joint representation (Methods: Scanpy) 
Task 2: Comparisons of the results of clustering analyses (Methods: visualization tools such as seaborn and matplotlib). 
Deliverables: Identification of the usefulness of combining multiple datatypes by joint representation and possibly more detailed characterization of different subtypes of T/NK-cells. 
### WP2: Evaluation of the performance of surface protein analysis (CITE-seq) when comparing to flow cytometry results. 
Q1: Are antibodies used in CITE-seq working as expected? 
Q2: Are there any differences between data sets in antibody staining? 
Task 1: Systematic organization of flow cytometry data obtained from clinics (Methods: data manipulation tools and tools to handle arrays/data frames, such as numpy and pandas). 
Task 2: Visualization of CITE-seq and flow cytometry results for comparisons (Methods: visualization tools, such as seaborn and matplotlib). 
Deliverables: Detection of possible methodological differences, differences between datasets or poor-quality antibodies affecting analysis. 
### WP3: Evaluation of model’s predictions of surface markers when applied to scRNA-only profiles. 
Q1: How well the model predicts selected surface protein markers of T/NK cells when comparing to scRNA-only profiles? 
Task 1: The relationship between selected RNA transcript and the level of its encoded protein will be predicted using the neural networks. (Methods: scikit-learn, tensor flow, keras, pytorch, scvi). 
Task 2: Visualization of the results of joint representation by neural networks and comparisons to the input data. (Methods: Visualization tools, such as seaborn and matplotlib). 
Deliverables: Identification of model’s performance  when predicting surface protein markers from RNA data. This could be usable tool in research where scRNA genomics is mostly used. For example, when using flow cytometry to isolate certain cell population identified by clustering analysis based on transcriptomes, identification of surface protein state in essential. 
### WP4: Biological interpretation of T- and NK-cell clustering analysis (focusing on interesting cases based on visualization).
Q1: How relative proportions of different T- and NK-cell subtypes differ between healthy and malignant states? 
Q2: What differences can be identified between malignancies? 
Q3: What is the biology behind the differences identified in this project? 
Q4: Can we validate the interesting findings made in this project in larger cohort datasets?
Tasks 1:  Identification and visualization of the proportions of different T/NK cell types in healthy and malignant samples. (Methods: statistical and visualization tools, such as numpy, scipy, seaborn and matplotlib. 
Task 2: Literature search. 
Deliverables: Identification of the major differences in T/NK-cell proportions between healthy or malignant state or in different hematological malignancies could reveal new insights to the complex role of T/NK cells in hematological diseases.
