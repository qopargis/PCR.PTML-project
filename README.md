# PCR.PTML-project

# PCR.PTML Model and Experimental Data for aDNA Microbiome Sequences

# Authors 
José L.R. Rama 1, José Manuel Ageitos 1, Lucía Feijoo-Siota 1, Estefania Ascencio-Medina 2,3,4,5, 
Amirreza Daghighi 2,3 Gerardo Casañola Martin 2, Bakhtiyor Rasulev 2, Cristian R. Munteanu 4,
Humberto González-Díaz 5,6,78, *and Tomas G. Villa 1, *

# Affiliations 
1Department of Microbiology and Parasitology, Faculty of Pharmacy, 
University of Santiago de Compostela, 15782, Santiago de Compostela, Spain.
2 Department of Coatings and Polymeric Materials, North Dakota State University, 
58102, Fargo, North Dakota, United States.
3 Biomedical Engineering Program, North Dakota State University, Fargo, ND 58105, USA.
4 RNASA-IMEDIR, Department of Information and Communication Technologies,
Computer Science Faculty, University of Coruña (UDC), 15071, A Coruña, Spain.
5 IKERDATA S.L., ZITEK, University of the Basque Country (UPV-EHU), 
Rectorate Building, 48940 Leioa, Spain.
6 BIOFISIKA Institute, Spanish National Research Council (CSIC) - 
University of the Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain. 
7 Department of Organic and Inorganic Chemistry and Basque Center for Biophysics;
University of Basque Country (UPV/EHU), 48940, Leioa, Basque Country, Spain.
8 IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Biscay, Spain.

* Corresponding authors.
  
# Abstract. 

The characterization of DNA sequence variants (variant calling) from ancient samples (aDNA) is a topic of major interest in modern science. However, there are important theoretical and experimental problems to be overcome like the low number of reliable samples, the possibility of contamination, etc. On the other hand, the main concern during the extraction ancient of DNA (aDNA) is to prevent contamination with modern materials. Consequently, it is crucial to be able to differentiate modern from ancient sequences in aDNA variant calling. In this context, computational techniques may play an important role. Most methods reported use alignment-dependent algorithms relying on limited samples. More recently Artificial Intelligence / Machine Learning (AI/ML) methods have been proposed as an alternative. However, almost all of them focus on the analysis of Mammoth, Neanderthal, or other Demographic aDNA problems and omit the study of aDNA paleo-microobiomes.  In this work, we report by the first time the PCR.PTML methodology based on the combination of experimental Polymerase Chain Reaction (PCR) metagenomic analysis of aDNA sequences with the Perturbation Theory (PT) and Machine Learning (ML) predictive modeling. Firstly, we reported the extraction and PCR analysis of a new set of putative microbiome 16S aDNA sequences from Miocene fossil amber. Next, we developed a variant calling PTML model able to discriminate 16S aDNA sequences of Miocene bacteria from modern bacteria sequences with more that 80% of specificity and sensitivity in training and validation series. We used both Linear Discriminant Analysis (LDA) and Artificial Neural Networks (ANN) algorithms for variant calling exploration of 100000 combinations of query and reference sequences to seek the model. In addition, we report a complimentary but preliminary study of ancient RNA (aRNA) sequences as well. PCR.PTML method may facilitate the experimental analysis and variant calling annotation of aDNA and possibly aRNA sequences of ancient microbiomes without relying upon sequence alignment.

# Keywords
Ancient DNA Sequences, Perturbation Theory, Machine Learning, Complex Networks, Shannon’s Information Theory

# Authors Contributions

José L.R. Rama, José Manuel Ageitos, Lucía Feijoo-Siota, and Tomas G. Villa
DNA isolation, sequencing, alingment, and annotation, Paper Writing, Artworks

Estefania Ascencio-Medina, Amirreza Daghighi, Gerardo Casañola Martin, Bakhtiyor Rasulev, Cristian R. Munteanu, 
Phyton scripting, Machine Learning, Data analysis, Paper Writing, Artworks

Sonia Arrasate, Humberto González-Díaz, Tomas G. Villa, Bakhtiyor Rasulev,
Paper design, Funding attraction, Paper Writing, Suppervision

# Funding
Acknowledgments
H.G-D. acknowledges financial support from grants MINECO (CTQ2016-74881-P), 2017 – 2019, and MICIIN (PID2019-104148GB-I00), 2020 – 2022, of Spain government and grant (IT1045-16), 2016 – 2021, and IT1558-22, 2022 – 2025, of Basque Government. This project was funded by grants INCITE07PXI203141ES (Conselleria de Industria, Xunta de Galicia, Spain) and BFU2009-07745 (MINECO, Spain).
