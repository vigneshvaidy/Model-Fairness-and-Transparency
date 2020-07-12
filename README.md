#Pre -requisits:

1. To run the google What If Tool please use google colab and run WIT_COMPAS_with_SHAP_project.ipynb file
2. Install other dependencies like IBM 360, Shap, WIT while executing the respective files.

How to run the code:

A). A data pipeline using IBM AIF360

    1. Run AIF360_and_SHAP.ipynb which covers end-to-end implementation of the complete pipeline.
        1.1 The file conatins:
            a) Data preprocessing and Feature Engineering
            b) Disparate Impact analysis
            c) Re-weighing algorithm to mitigate the bias
            d) shap plots to explain the model performance and fairness
    
B). A data pipeline using google WIF.

    1. Run WIT_COMPAS_with_SHAP_project.ipynb which covers end-to-end implementation of the complete pipeline.
        1.1 The file conatins:
            a) Data preprocessing and Feature Engineering 
            b) Shap plots to explain the model performance and fairness
            c) Googl What If tool Interface: The tool can be used to perform following things:
                1. change in predictions after changing the feature values of the data points
                2. Evaluation of Model Fairness and performance
                3. Features - data distribution in the dataset used.

c). data product(Full stack node application) - url - https://model-fariness-project-demo.herokuapp.com

    1. use the code in "website" directory to lauch the website through local host.
    2. The application uses port 3004 to luach via local host
    
d). Please use the branch - https://csil-git1.cs.surrey.sfu.ca/manjum/cmpt-733-programming-for-big-data-2/-/tree/EDA_branch for the work completed for milestone 1 as part of EDA



Group contribution:

    Chidambaram Allada: worked on Feature Engineering, Data analysis,implementation of the data pipeline using IBM 360, presentations and report

    Manju Malateshappa: worked on Feature Engineering, Data analysis,implementation of the data pipeline using What If tool, website development, report preparation and presentations.

    Urvi Chauhan: worked on implementation of the data pipeline using What If tool, shap implementation, report preparation and presentations.

    Vignesh Vaidyanathan: worked on Data analysis, implementation of the data pipeline using IBM 360, shap implementation report and presentations

All team members put up equal efforts for this challenging project and contributed equally towards the success of the project.