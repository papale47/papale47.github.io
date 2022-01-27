## Portfolio

---

### Attrition Modeling Project
[Jupyter Notebook](https://colab.research.google.com/drive/1WpCJY0jThIiQxfWPF62ycwbyh8s5P2vU?usp=sharing) <br><br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes:
<br>
1.  Exploratory data analysis (which includes dimensionality reduction and clustering techniques) and data transformations  <br>
2.  Hyperparameter tuning using Bayesian Optimization and a custom net economic value function as a metric to score model performance <br>
3.  An economic framework (illustrated below in the image) which aids in translating model performance into expected business impact, as well as in identifying the optimal classification threshold <br>
4.  A simulated experiment which quantifies the impact of a model-driven treatment 

My initial motivation for creating this notebook was to create an end-to-end modeling project using open source data that would allow me to consolidate related bodies of work I have pursued (in both academic and professional settings) in one place. I was also interested in having a platform (i.e., Google Colab) on which I could use an open source dataset on which I could explore and become more proficienct in data science techniques that I have not worked with yet. Another motivation for writing this notebook is to serve as a guide for others who are interested in learning more about modeling, experimentation, or translating model performance to business impact. Finally, I do intend to continually supplement and improve upon this notebook over time, so if there are any suggestions or errors which you identify, please let me know!
<br>
<br>
[Economic Framework to Translate Model Performance into Expected Business Impact (click to see a larger picture)](images/Economic_Framework2.png)
<img src="images/Economic_Framework2.png?raw=true"/>


---
### Foster Care Matcher Project (UC Berkeley MIDS Capstone)
[Project Page (Berkeley Website)](https://www.ischool.berkeley.edu/projects/2021/foster-care-matcher) <br>
[Project Page (Website Developed by Team)](https://groups.ischool.berkeley.edu/FostercareMatcher/) <br>
[Presentation](https://docs.google.com/presentation/d/1i6v82ls_K5gv1CMo65wCuCMUe5iEGgjahMEikmlWTy4/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1R582ZZjfWUIhLHSJTNy6it1xjZUhsvSm?usp=sharing) <br><br>
This project entailed the development of an interpretable decision support tool intended to be used by foster care placement specialists in order to aid them in making more effective placements between a foster child and a foster parent. This was my capstone project as part of the UC Berkeley MIDS program, and I worked on this project with 3 other team members using foster care placement data for the state of Florida, as well as related other demographic data. This project also required multiple touchpoints with several professionals within the foster care system in Florida. Though we all collaborated and worked on multiple parts, my main contribution centered around the development of two XGBoost models.  The first model was a regression model designed to predict the duration of a given foster care placement.  The second model was a classification model which was designed to predict the probability of a good placement outcome.  The results of both models can be found on a wepbage one my team members put together which is linked above. Additionally, it is worth noting that our project was selected as a finalist for the MIDS Val Harian Capstone Award, which is awarded to the team with the top project each semester.
<br>
<br>
<img src="images/FCM Logo.PNG?raw=true"/> 


---
### Predicting Customer Satisfaction Using Call Transcripts and Deep Learning Models
[White Paper](pdf/w266_Final_Project.pdf) <br>
[Presentation](https://docs.google.com/presentation/d/1jyofU1cUSDB_NifqXl3WcC0d5itfWP5yfcuBDXIDkTA/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1bbrwdkc-Omtqgm0po-nkhplJ7ix4iiVz?usp=sharing) <br><br>
This project entailed developing several deep learning Natural Language Processing (NLP) models and after-call surveys to predict customer satisfaction given a telephone transcript.  As part of this effort, I explored three different types of model architectures: a Convolutional Neural Network (CNN) using 100-dimensional GloVe embeddings, a fine-Tuned Bidirectional Encoder Representations from Transformers (BERT) model, as well as a set of heirarchical transformer models: a Transformers over BERT (ToBERT) model and a Recurrence over BERT (RoBERT) model. As can be seen below, the CNN peformed the best in terms of achieving the highest precision and recall for the minority class (i.e., dissatisfied) predictions. However, at USAA, I have since used this same pipeline to predict churn given a transcript and the best peforming model was the Fine-Tuned BERT model. Though I offer some possible reasons as to why the heirarchical transformers perform so poorly in the white paper linked above, additional work is required to fully understand the reason behind the poorer-than-expected performance for these models.
<br>
<br>
[Precision Recall Curves for All NLP Models Developed (click to see a larger picture)](images/Precision_Recall_Curves.PNG)
<img src="images/Precision_Recall_Curves.PNG?raw=true"/> 


---
### Predicting Airline Delays with PySpark
[Presentation](https://docs.google.com/presentation/d/10HnP3S5U1qiBSeUcAGHE4QvmwD1jCLBdbmKnRZLdBdk/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1_nijztiOgOJ0UI98Ix1GdhtSRPcjKztC?usp=sharing) <br><br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes
<br>
<br>
[Model Performance Values for All Models Developed (click to see a larger picture)](images/Airline_Project_Results.PNG)
<img src="images/Airline_Project_Results.PNG?raw=true"/> 


---
### Diagnosing COVID Infection Using Chest CT Scans and Deep Learning Models
[White Paper](https://docs.google.com/document/d/1tqgsLxmJMESIS1umfFzvvO6LrEpHSe7dHGsX1zvpBXo/edit?usp=sharing) <br>
[Presentation](https://docs.google.com/presentation/d/1YjssHAXVPUgLLcRoLHWWMD10kihpt5fHwWFfoxR7WHM/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1mP1w7ZNzAR_yZ2__G1QwVK-CnpKQ8hPO?usp=sharing) <br>
[Python Script to Deploy CNN Model to Edge Device](PY_Files/ct_cnn_detector.py)<br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes
<br>
<br>
[Model Architecture of Baseline CNN Model (click to see a larger picture)](images/Covid_CNN_Image.PNG)
<img src="images/Covid_CNN_Image.PNG?raw=true"/> 


---
### Understanding Drivers Behind Crime in Gotham City Using Regression
[Notebook](https://colab.research.google.com/drive/1M015KXvRmL2zYe8fxPcGjo_BAiaqRXfa?usp=sharing) <br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes
<br>
<br>
<img src="images/Gotham_City.jpg?raw=true"/> 


---
### Business Consulting Project for IFish Fishing Apparel Company (Mississippi State MBA Capstone)
[White Paper](pdf/IFish_Report.pdf) <br>
[Presentation](pdf/IFISH_Final_Presentation.pdf) <br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes
<br>
<br>
<img src="images/IFish_Logo.PNG?raw=true"/> 





###

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
