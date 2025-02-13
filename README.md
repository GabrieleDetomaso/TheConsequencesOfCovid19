# TheConsequencesOfCovid19
Small Data mining project that aims to find meaningful clusters and frequent patterns into a dataset of Spanish families which lived the covid19 pandemic

# Repository structure
There are several python notebooks, the number define the execution order  
Fields:
- **Array_saved** contains the dataset csv files after some elaborations.
- **Clustering_results** contains the clusters csv files for each clustering methods.
- **DataMiningEnv** contains the python virtual environment.
- **Documents** contains some utils documents (the input dataset and the dataset paper that explains all the dataset attributes).
    - Article's name: "Survey data on the consequences of COVID-19 and home confinement on the educational community and families in Spain" by Guillermo Palau-Salvador, Kas Sempere, Nerea Gómez-Fernández, Ana Belda-Marco, Isabel González-Galindo , Miriam Hoyo-Juliá ,Davinia Ros-Bonanad, José-Miguel Carot Sierra.
- **Utils** is like a personal python library where there are some utils methods.


# Pipeline
1. Data cleaning
    - remove useless features
    - remove rows with at least 2 NaN values
2. Clean dataset analysis
3. Dimensionality Reduction
4. Clustering 2D
5. Multidimensional Clustering
6. Analysis of Interesting Association Patterns
7. Conclusion