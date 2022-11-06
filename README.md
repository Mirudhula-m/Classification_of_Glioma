# Classification of Glioma

Glioma is a common malignancy of the brain. It is the leading cause of death due to inefficient tumor classification methods and poor prognosis. Our idea was that classification of gliomas and normal cells can lead to early diagnosis of the cancer. In addition to this, classification of subtypes of gliomas could lead to better decision-making on which drug protocol to follow to curb the disease better.

We evaluated four different supervised classification models comprising Gaussian Naive Bayes, K-nearest neighbor, Logistic Regression and Support Vector Machines. This was conducted on Gene Expression data from The Cancer Genome Atlas (TCGA). The models were trained to classify between normal and glioma samples and further classify the subtypes of glioma. Five fold cross validation was used to evaluate our models for extracted gene expression data.

Out of these, I was responsible for Gaussian Naive Bayes. As a part of our course project, this was implemented from scratch without the use of any ML packages. The results were validated against results of SVM that was run using the scikit package.

<img width="393" alt="Screen Shot 2022-11-06 at 12 40 50 AM" src="https://user-images.githubusercontent.com/38470217/200154565-8654b6a0-afc7-424a-ae53-52b028d8e2a8.png">

                                    PCA results of data.
                                    
<img width="364" alt="Screen Shot 2022-11-06 at 12 42 06 AM" src="https://user-images.githubusercontent.com/38470217/200154587-281ffc0f-40e0-4f36-9d2c-89522034df3e.png">

                               Final classifier evaluation

We performed a comparative study for the performance of each classifier against the data and found SVM to be performing the best.


# Team Members

Mirudhula Mukundan, Aditi Sarathy, Ketaki Ghatole, Arnav Gupta


## Final Report and Outcomes
<object data="https://github.com/ArnavGuptaa/02620_ML_Project/blob/main/ML_project_report.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/ArnavGuptaa/02620_ML_Project/blob/main/ML_project_report.pdf">
        <p>Please download the PDF to view it: <a href="https://mirudhula-m.github.io/assets/project_reports/glioma.pdf">Download PDF</a>.</p>
    </embed>
</object>
