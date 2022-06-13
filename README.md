# TPM

## Introduction
The Digital Revolution has profoundly changed the tourism segmentation research field. It is now easier to grasp tourists' behaviors thanks to their digital traces left on social networks. The studies that have centered their method around tourists' digital traces focus on applying existing clustering algorithms to the tourism context. In this paper, we propose a measure to determine tourism segmentation — also known as tourism profiling — by establishing a new clustering algorithm focusing on stays conducted by tourists. This measure is based on both the context and the content of the trips. The approach is simulated and evaluated experimentally on a real dataset at various periods and on diverse nationalities, in the French capital Paris.

## Installation
In order to install the different necessary libraries, it is necessary to perform the following command: 
pip install -r requirements.txt

## Data
The data used in the Results section of our paper are not included in this repository due to their size. However, a sample of each dataset used is proposed in the `data_sample` folder.

## Run
The project is divided into several folders and files : the `data_sample` folder folder is where datasets are stored, while the `res` folder is where results are stored. The `TPM` algorithm has been applied to data coming from two *French* regions : *Hauts-de-France* and *Ile-de-France*.

The `requirements.txt` file contains the libraries needed to run the project with their respective version.

The `README.md` is a descriptive file explaining how to use this repository (which you are currently reading !)

The `TPM.py` file is the algorithm ; however, the only script that you should be using is the main.py. The project has some parameters set by default that you can change at your will ! For instance, the `breakdown_year` parameter (set by default at True) retains only digital traces made during a given year.


## Data visualization, Knownledge discovery & Data interpretation


## References & Contacts


