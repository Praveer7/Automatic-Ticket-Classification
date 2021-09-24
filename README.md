# Automatic-Ticket-Classification
Topic Modelling case study 

In this project, we have created a model that can automatically classify customer complaints based on the products and services that the complaint ticket mentions. This model helps segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

We have done topic modelling on the .json data. Since this data is not labelled, we have applied NMF to analyse patterns and classify tickets into the five clusters based on their products/services. With the help of topic modelling, we mapped each ticket onto its respective department/category. This data is then used to train a few supervised models such as logistic regression, decision tree, random forest, etc. Finally, a best model is selected and tested on some custom text data.
