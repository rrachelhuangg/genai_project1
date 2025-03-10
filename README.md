####
* AUTHOR  : Rachel Huang, Jackson Taylor
* CREATED : 17-2-2025
* EDITED  : 1-3-2025
####

## GenAI for Software Development (Ngram)

* [1 Introduction](#1-introduction)  
* [2 Getting Started](#2-getting-started)  
  * [2.1 Preparations](#21-preparations)  
  * [2.2 Install Packages](#22-install-packages)  
  * [2.3 Run N-gram](#23-run-n-gram)  
* [3 Report](#3-report)  

---

## **1. Introduction**  
This project explores **code completion in Java**, leveraging **N-gram language modeling**. The N-gram model predicts the next token in a sequence by learning the probability distributions of token occurrences in training data. The model selects the most probable token based on learned patterns, making it a fundamental technique in natural language processing and software engineering automation.  

---

## **2. Getting Started**  

This project is implemented in **Python 3.9+** and is compatible with **macOS, Linux, and Windows**. Our extracted data is available via [this](https://drive.google.com/drive/folders/1fAkrV63o_tZjk5eRHHE9x1NFYQeN-ZhA?usp=sharing)  google drive link. 

### **2.1 Preparations**  

```shell
(1) Clone the repository to your workspace:

~ $ git clone https://github.com/rrachelhuangg/code-generation-ngram-model.git

(2) Navigate into the repository:

~ $ cd code-generation-ngram-model
~/code-generation-ngram-model $

(3) Set up a virtual environment and activate it:

For macOS/Linux:

~/code-generation-ngram-model $ python -m venv ./venv/
~/code-generation-ngram-model $ source venv/bin/activate
(venv) ~/code-generation-ngram-model $ 

To deactivate the virtual environment, use the command:

(venv) $ deactivate
```

### **2.2 Install Packages**

Install the required dependencies:

(venv) ~/code-generation-ngram-model $ pip install -r requirements.txt

### **2.3 Run N-gram**

(1) How to run N-gram Demo

The script takes a corpus of Java methods as input and automatically identifies the best-performing model based on a specific N-value. It then evaluates the selected model on the test set extracted according to the assignment specifications. The stored data goes to the option input name argument, otherwise it goes to the default results_model.json

(venv) ~/code-generation-ngram-model $ python model_controller.py [input txt file] [optional: file name]

(2) Example run of N-gram Demo

(venv) ~/code-generation-ngram-model $ python model_controller.py all_tokens.txt


### 3. Report

The assignment report is available in the file Assignment_Report.pdf.





