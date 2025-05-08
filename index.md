## Portfolio
Note: Most of these projects include a link to a Jupyter Notebook in Colab. This was done to make it easier to navigate through the notebooks with the use of Colab's Table of Contents functionality. That said, the only projects where the notebooks are designed to run as-is using Colab are the first three projects listed.

---
### Power Analysis and Experiment Analysis
[Streamlit App (Experimentation Toolkit)](https://papale47-experimentation-tools-streamlit-app-akgz6j.streamlit.app/) <br>
This is an app I developed (with the help of Generative AI) that takes the core components of the power analysis notebook linked below and presents it in a more user-friendly and interactive app using Streamlit.  This tool allows you to import a dataset (or create a synthetic one for learning purposes) and conduct a power analysis using that dataset or using manual inputs. This app also allows you to evaluate customer signup volumes over time and conversion timing, which are important considerations when planning an experiment where a customer is the unit of observation and conversion is the key metric.
<br>
<br>
[Streamlit App (click to see a larger picture)](images/Streamlit%20App%202.png)
<img src="images/Streamlit App 2.png?raw=true"/> 

#### Jupyter Notebooks
[Jupyter Notebook (Power Analysis)](https://colab.research.google.com/drive/13ppjrbEVKbhfWTBLmT3SuIYbZvHmXZ_z#scrollTo=BWGEJ3eKhUu-) <br>
[Jupyter Notebook (Experiment Analysis)](https://colab.research.google.com/drive/1zBys67ADftUMQZ5L3d8wVvrHZwMF8GkW#scrollTo=DMhAna-IRQVU) <br><br>
There are two Jupyter notebooks linked above.  The first notebook goes through the steps required to perform a power analysis using a (synthetic) historical dataset and:
1.  Generates a table which provides test sizing options for various levels of statistical significance and power and minimum detectable effect (MDE) sizes, as well as expected timeframes for test duration and metric curing.  <br>
2.  Evaluates conversion rate with respect to tenure to make it easier to determine an appropriate curing timeframe for conversion rate. <br>
3.  Provides a short summary which explains the selected test sizing option and the associated inputs, as well as an Excel file which contains one tab for each metric evaluated (only evaluating one metric in this notebook). <br>

**Note**: While this notebook is still included to make the code accessible, a Streamlit App linked above contains all the functionality within this notebook and makes it available in a more user-friendly and interactive way.
<br><br>

The second notebook focuses on performing an analysis on data from an experiment (using another synthetic dataset) and includes:
1.  Customer and product-level analysis.  <br>
2.  A logistic regression model to perform statistical testing on the key metric of conversion rate, as well as to perform a high-level covariate balance check.
3.  A Generative AI-powered pipeline that first identifies the main themes prevalent in freeform survey responses and then associates each response with one or more themes, as applicable.  This then makes it possible to quantify the extent to which the treatment impacted sentiment at a theme level.
<br>
[Comparison of Themes between Treatment and Control (click to see a larger picture)](images/Freeform%20Response%20Analysis%202.png)
<img src="images/Freeform Response Analysis 2.png?raw=true"/>

---
### ParkZen Forecasting Project
[Jupyter Notebook](https://colab.research.google.com/drive/1NZjIlHnsFhlbO4HVlJOsN3xz-uF6Jscb#scrollTo=MkgKoBgZ1ahZ) <br><br>
This project entailed training and evaluating several forecasting models to predict the future occupancy of parking lots given current occupancy, as well as other independent variables (e.g., day of week). I performed this project to help my friend Manos Chatzopoulos, CEO of ParkZen, better leverage parking data available within his company.
<br>
<br>
[Model Evaluation Visualizations (click to see a larger picture)](images/Forecasting%20Results.png)
<img src="images/Forecasting Results.png?raw=true"/> 


---
### Attrition Modeling Project
[Jupyter Notebook](https://colab.research.google.com/drive/1sHXkTWLu-21rMSyXAApG52ejHnL7aABw?usp=sharing) <br>
[Presentation](https://docs.google.com/presentation/d/1mqQj5MJvuWVrUOKSyWe9eyuS83lkR7fOF5863mZnQGI/edit?usp=sharing) <br><br>
This project utilizes a customer churn dataset I obtained on Kaggle and entails building two binary classifier models to predict churn. The project also includes:
<br>
1.  Exploratory data analysis (which includes dimensionality reduction and clustering techniques) and data transformations  <br>
2.  Hyperparameter tuning using a Genetic Algorithm <br>
3.  An economic framework (illustrated below in the image) which aids in translating model performance into expected business impact, as well as in identifying the optimal classification threshold <br>
4.  A simulated experiment which quantifies the impact of a model-driven treatment 

My initial motivation for creating this notebook was to consolidate existing bodies of work I have pursued (in both academic and professional settings) into one robust, end-to-end modeling pipeline. I was also interested in having a platform (i.e., Google Colab) on which I could use an open source dataset that would allow me to explore and become more proficient in data science techniques that I have not worked with yet. Another motivation for writing this notebook is to serve as a guide for others who are interested in learning more about modeling, experimentation, or translating model performance to business impact. Finally, I do intend to continually supplement and improve upon this notebook over time, so if there are any suggestions or errors which you identify, please let me know!
<br>
<br>
[Economic Framework to Translate Model Performance into Expected Business Impact (click to see a larger picture)](images/Net_Value_5.PNG)
<img src="images/Net_Value_5.PNG?raw=true"/>


---
### Foster Care Matcher Project (UC Berkeley MIDS Capstone)
[Project Page (Berkeley Website)](https://www.ischool.berkeley.edu/projects/2021/foster-care-matcher) <br>
[Project Page (Website Developed by Team)](https://groups.ischool.berkeley.edu/FostercareMatcher/) <br>
[Presentation](https://docs.google.com/presentation/d/1i6v82ls_K5gv1CMo65wCuCMUe5iEGgjahMEikmlWTy4/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1R582ZZjfWUIhLHSJTNy6it1xjZUhsvSm?usp=sharing) <br><br>
This project entailed the development of an interpretable decision support tool intended to be used by foster care placement specialists in order to aid them in making more effective placements between a foster child and a foster parent. This project served as my capstone (UC Berkeley MIDS program), and I worked on it with 3 other team members using foster care placement data for the state of Florida, as well as other related demographic data. Though we all collaborated and worked on multiple parts, my main contribution centered around the development of two XGBoost models.  The first model was a regression model designed to predict the duration of a given foster care placement.  The second model was a classification model which was designed to predict the probability of a good placement outcome.  The results of both models can be found on a webpage which one of my team members put together (link included above). Additionally, it is worth noting that our project was selected as a finalist for the MIDS Val Harian Capstone Award, which is awarded to the team with the top project each semester.
<br>
<br>
<img src="images/FCM Logo.PNG?raw=true"/> 


---
### Predicting Customer Satisfaction Using Call Transcripts and Deep Learning Models
[White Paper](pdf/w266_Final_Project.pdf) <br>
[Presentation](https://docs.google.com/presentation/d/1jyofU1cUSDB_NifqXl3WcC0d5itfWP5yfcuBDXIDkTA/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1bbrwdkc-Omtqgm0po-nkhplJ7ix4iiVz?usp=sharing) <br><br>
I completed this project as part of the UC Berkeley MIDS program, and it entailed developing several deep learning Natural Language Processing (NLP) models and leveraging after-call surveys to predict customer satisfaction given a telephone transcript.  As part of this effort, I explored three different deep learning model architectures: a Convolutional Neural Network (CNN) using 100-dimensional GloVe embeddings, a fine-tuned Bidirectional Encoder Representations from Transformers (BERT) model, as well as a set of hierarchical transformer models: a Transformers over BERT (ToBERT) model and a Recurrence over BERT (RoBERT) model. As can be seen below, the CNN performed the best in terms of achieving the highest precision and recall for the minority class (i.e., dissatisfied) predictions. However, at USAA, I have since used this same pipeline to predict churn given a transcript and the best performing model was the Fine-Tuned BERT model. Though I offer some possible reasons as to why the hierarchical transformers perform so poorly in the white paper linked above, additional work is required to fully understand the reason behind the poorer-than-expected performance for these models.
<br>
<br>
[Precision Recall Curves for All NLP Models Developed (click to see a larger picture)](images/Precision_Recall_Curves.PNG)
<img src="images/Precision_Recall_Curves.PNG?raw=true"/> 


---
### Predicting Airline Delays with PySpark
[Jupyter Notebook](https://colab.research.google.com/drive/1_nijztiOgOJ0UI98Ix1GdhtSRPcjKztC?usp=sharing) <br><br>
This project entailed developing and evaluating several classification models designed to predict whether or not a flight would have an arrival delay of at least 15 minutes. I completed this project as part of the UC Berkeley MIDS program, and I collaborated with two other individuals. Due to the division of labor between this project and another unrelated assignment, my contribution encompassed the development of most parts of this notebook. Of note, this project was developed using Databricks and was written primarily in PySpark. In terms of the modeling, there were three models which were trained and evaluated: a Gradient Boosted Tree model, a Random Forest model, and a Logistic Regression model. The Gradient Boosted Tree model performed the best in terms of the area under the ROC and precision-recall curves as can be seen in the results shown below.
<br>
<br>
[Model Performance Values for All Models Developed (click to see a larger picture)](images/Airline_Project_Results.PNG)
<img src="images/Airline_Project_Results.PNG?raw=true"/> 


---
### Diagnosing COVID Infection Using Chest CT Scans and Deep Learning Models
[White Paper](https://docs.google.com/document/d/1tqgsLxmJMESIS1umfFzvvO6LrEpHSe7dHGsX1zvpBXo/edit?usp=sharing) <br>
[Presentation](https://docs.google.com/presentation/d/141aqIfPYyV5O5JCnim5SX8bKODQJGwlTzBdxHKdwKXY/edit?usp=sharing) <br>
[Jupyter Notebook](https://colab.research.google.com/drive/1mP1w7ZNzAR_yZ2__G1QwVK-CnpKQ8hPO?usp=sharing) <br>
[Python Script to Deploy CNN Model to Edge Device](https://github.com/papale47/papale47.github.io/blob/master/PY_Files/ct_cnn_detector.py)<br><br>
The objective with this project was to utilize cloud resources to develop a deep learning model which could classify respiratory disease given a CT scan and then deploy that model to an edge device for local inference. Specifically, the three possible outcomes were: COVID, Pneumonia, and no disease. I completed this project with 3 other teammates as part of the UC Berkeley MIDS program. My contributions centered primarily around the development of a baseline convolutional neural network, as well as writing the script to reconstruct the model on an Nvidia Jetson NX device, take a picture of a CT scan on using a webcam attached to the NX device, automatically crop and resize the image such that it would be consumable by the model, and then have the model generate a prediction. While the model performed quite well when using the higher fidelity training and evaluation data obtained from Kaggle, it (somewhat unsurprisingly) did not perform as well when generating predictions based on images obtained using a webcam and a picture of a CT scan being displayed on a computer screen.  In any event, a high-level overview of the architecture I employed in the baseline CNN is shown below.
<br>
<br>
[Model Architecture of Baseline CNN Model (click to see a larger picture)](images/Covid_CNN_Image.PNG)
<img src="images/Covid_CNN_Image.PNG?raw=true"/> 


---
### Understanding Drivers Behind Crime in Gotham City Using Regression
[Notebook](https://colab.research.google.com/drive/1M015KXvRmL2zYe8fxPcGjo_BAiaqRXfa?usp=sharing) <br><br>
In this project, I, along with two other individuals in the UC Berkeley MIDS program, developed a series of linear regression models to better understand the drivers of crime using a selection of North Carolina crime data. Though it is my recollection that the dataset is derived from real data, I recall that it may have been altered by the instructors to facilitate certain learning points. I believe this is the reason that project is set in a fictional context (i.e., Gotham City). In any case, my contributions centered primarily around exploratory data analysis and data cleansing. Additionally, though this notebook is liked to Colab (an environment intended to be used with Python), the entirety of the code contained within this notebook is written in R. 
<br>
<br>
<img src="images/Gotham_City.jpg?raw=true"/> 


---
### Business Consulting Project for IFish Fishing Apparel Company (Mississippi State MBA Capstone)
[White Paper](pdf/IFish_Report.pdf) <br>
[Presentation](pdf/IFISH_Final_Presentation.pdf) <br><br>
As part of the capstone for the MBA program I completed at Mississippi State University, I, along with three other classmates, completed a consulting project with a small fishing apparel company called IFish. This project entailed conducting a review of the business, developing an understanding of how customer needs were being met by the existing fishing apparel marketplace, identifying how IFish could best position itself to fill gaps left by the existing marketplace, and providing a concise set of recommendations to the company owner. My contributions centered primarily around designing a focus group to better understand the wants and needs of potential customers, as well how those potential customers assessed the value of IFish's products. I also developed a repository of competitive intelligence around the offerings of competing fishing apparel companies so that it would be possible for our team to identify gaps in the existing marketplace.
<br>
<br>
<img src="images/IFish_Logo.PNG?raw=true"/> 




---
