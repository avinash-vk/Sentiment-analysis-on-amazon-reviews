# Sentiment-analysis-on-amazon-reviews

This project showcases a comparative study between different machine learning models to perform sentiment analysis on the customer reviews of Amazon products in the Electronics category. The primary models we will look into for our analysis are Support Vector Machines, Naive Bayes Classifier, Random Forest Classifier, BERT Model, Stochastic Gradient Descent (SVM Linear) and Linear SVC models.

---

## Dataset Source
Amazon Product Reviews Dataset (2018 Updated Version)<br>
http://jmcauley.ucsd.edu/data/amazon/index_2014.html

## Useful links

- [Demo Video](https://drive.google.com/drive/folders/190hH4boR2IaLi2K0Y8kADxtAe9aHcNAC?usp=sharing)
- [Literature Review](https://drive.google.com/drive/folders/1H_DjSv5xl1DP-o0ejYsmil1nJEVjMWgX?usp=sharing)
- [Project Report - IEEE Format Paper](https://drive.google.com/drive/folders/14ccg7k00QGlAc3ijbAj5JaqiYizgfrwP?usp=sharing)

## Team-34 <br>
- Sanskriti Pattanayak - [@sanskritip](https://github.com/sanskritip)
- Venkatavaradan Raghuraman - [@venkatavaradan-R](https://github.com/Venkatavaradan-R)
- Avinash V K - [@avinash-vk](https://github.com/avinash-vk)
- Akshay C Patil - [@akshaycpatil](https://github.com/akshaycpatil)

---

## Running the project

The original dataset is huge and takes a lot of computational power to process. Here are some samples from the original dataset that can be used to execute the project. Make sure to download/save it to your drive, and change the URLs in the files accordingly.

- [Subset of the original dataset with 50k rows](https://drive.google.com/file/d/1EW-2ZiC2Df8PufsuNMPqIrdx6_zo29D1/view?usp=sharing)

### To run the project
Update the urls in the files and run following steps

- Data cleaning: Run datacleaning.ipynb with its dataset url pointing to the location where your dataset is stored. Modify the "CLEAN_URL" to the output file as well where the clean dataframe would be written into.
- Exploratory data analysis: Run EDA.ipynb with the url pointing to the cleaned version of the dataset from above to view the different visualisations from the dataset.
- Model Building and training: Inside the `models` folder, run the models.ipynb to compare and train different models we build, like Support Vector Machines, Naive Bayes Classifier, Random Forest Classifier, Stochastic Gradient Descent (SVM Linear) etc, and view the accuracies and compare them. To run BERT model, run the `BERT.ipynb` with the url pointing to the cleaned dataset

