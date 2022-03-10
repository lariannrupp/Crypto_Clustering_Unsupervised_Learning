# Crypto Clustering - An Application of Unsupervised Machine Learning
---
---
## Introduction

This is a demonstration of Crypto Clustering as an application of unsupervised machine learning. It is presented as a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. 

The program is trained to find underlying patterns in cryptocurrency price changes during different time perdiods. It then clusters the cryptocurrencies which perform similarily over different time periods. 

A Principal Component Analysis is performed on the data, and it is cross examined against the original set through composite visualizations.

![Screenshot 2022-03-09 224622](https://user-images.githubusercontent.com/95719899/157597584-823a0740-4513-4675-a040-a19fae81ce3f.jpg)


## Technologies

**A Python 3.9.7 (ipykernal) in JupyterLab** was used to write this notebook.


Additional Python libraries are imported into the start of the app: 


![Screenshot 2022-03-09 224020](https://user-images.githubusercontent.com/95719899/157596978-ce48d230-4397-4cf2-84f5-1318a660e56e.jpg)




---

## Installation Guide

To use the app, from the Github repository, download:
- **crypto_investments.ipynb** Jupyter file 
- **Resources** folder that contains the CSV file of price change data of cryptocurrencies in different periods.

Use either Terminal or GitBash to run the app in a conda dev environment. 
To enter a conda dev environment, type
'conda activate dev'

You may need to install hvplot or sklearn in Terminal or GitBash.
Install hvplot by using the conda install command as follows:
> pip install hvplot.pandas

Install sklearn by using the conda install command as follows:
> pip install sklearn.pandas

Confirm the installation of hvplot by running the following commands:
> conda list hvplot
> conda list sklearn

To run the app, navigate to the root directory, which contains **etf_analyzer** and the **etf.db** file and then type
'jupyter lab'



---

## Usage

The steps for this exercise are broken out into the following sections:

* Import the Data (provided in the starter code)
* Prepare the Data (provided in the starter code)
* Find the Best Value for `k` Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for `k` Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results



---

## Contributors

This exercise was based on a challenge problem from UC Berekely Fintech Bootcamp Module 10, accessed on 2022.03.09. 

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero






