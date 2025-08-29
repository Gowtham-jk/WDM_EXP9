### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 29-08-2025
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1703" height="946" alt="Screenshot 2025-08-29 104951" src="https://github.com/user-attachments/assets/9c9aac01-d13f-4dd5-a5f1-12abede88dd3" />

<img width="1702" height="947" alt="Screenshot 2025-08-29 105009" src="https://github.com/user-attachments/assets/8503c460-477f-4917-8029-1be6287f0da2" />

<img width="1700" height="949" alt="Screenshot 2025-08-29 105034" src="https://github.com/user-attachments/assets/1af1745a-6697-4139-81f5-f13ab67f0003" />

<img width="1694" height="924" alt="Screenshot 2025-08-29 105052" src="https://github.com/user-attachments/assets/2bc863a7-af06-4394-834b-cf7b2b84a88f" />


### Result:
Thus the experiment to implement preprocessing technique on Twitter Data using Rapidminer is done successfully.
