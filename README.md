# FakeNewsData
Fake news detection dataset

When used, you can reshuffle the data set to better train the model.


**COVID-19.csv**

This data set is composed of two parts A and B. 
Part A is the Checked dataset, which  is available at https://github.com/cyang03/CHECKED. From December 2019 to August 2020, CHECKED has 2,120 pieces of blogs including 344 being “Fake” and 1776 being “Real”. 
Part B is also qualified for obtaining from Tencent fact check platform.Those 718 pieces of data were added to prevent overfitting caused by the extreme shortage of dataset.
A total of 2,838 pieces of data were combined, including 883 pieces of fake news and 1,955 pieces of true news.


**BAAI_biendata2019.csv**

The dataset comes from an Internet fake news detection contest, and it can be available at https://www.biendata.xyz/competition/falsenews/data/. The competition was jointly held by the Beijing Academy of Artificial Intelligence (BAAI) and the Institute of Computing Technology of the Chinese Academy of Sciences in 2019. BAAI has set up the Data Open Research Center with the aim of achieving the sharing of high-quality data and knowledge. 
The dataset for this competition was provided by BAAI and is of high quality. The dataset contains 38,471 items of data, including 19,186 true news and 19,285 fake news. Each piece of data is represented by the following components: id, text, and label. 
