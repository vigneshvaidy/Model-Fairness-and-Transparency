# MODEL FAIRNESS AND TRANSPARENCY
The idea of this project is to detect any bias in the data that could inturn lead the Machine Learning model to become bias towards a particular attribute that could have real world implications.


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
