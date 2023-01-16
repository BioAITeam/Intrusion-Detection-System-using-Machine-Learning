# Intrusion Detection System in Wireless Sensor Network using Machine Learning
One of the fields where Artificial Intelligence (AI) must continue to innovate is computer security. The integration of Wireless Sensor Networks (WSN) with the Internet of Things (IoT) creates ecosystems of attractive surfaces for security intrusions, being vulnerable to multiple and simultaneous attacks. This research evaluates the performance of an Intrusion Detection System (IDS) configured with novel Machine Learning (ML) algorithms. This work presents a new balanced dataset (IDSAI) with intrusions generated under real-based attack settings. The experiments show that for the detection of intruders, the best algorithms are XGBoost, Gradient Boosting, Decision Tree, Random Forest, and Extra Trees. Which can generate predictions when trained and predicted with specific intrusions (i.e., ARP spoofing, Brute Force SSH, DDoS MAC Flood, ICMP echo request Flood, IP Fragmentation, SYN Flooding faster, SYN/ACK Flooding, SYN/ACK & RST Flooding, TCP Null, and UDP port scan), both of binary form (intrusion and no-intrusion) with up to 94 % of accuracy, as multiclass form (ten different intrusions and no-intrusion) with up to 92 % of accuracy. In contrast, up to 90 % of accuracy is achieved for prediction on the Bot-IoT dataset using models trained with the IDSAI dataset. 

## Citing

If you use our project for your research or if you find this paper and repository helpful, please consider citing the work.

## Folders

- **DBs** This folder contain the datasets. Please unzip the Data.zip file when you download or clone the repository.
- **Notebooks** In this folder, you will find all algorithms and implementations for the different scenarios. 

## Requirements
This repository requires the following libraries:

- NumPy
- Pandas
- string
- Seaborn
- openpyxl
- scikit-learn
- keras-gpu
- scikit-image
- NLTK
- spaCy
- imbalanced-learn
- Matplotlib
- Yellowbrick
- Time
- OpenCV
- Pydot
- Graphviz
- dtreeviz
- Statsmodels
- XGBoost

This repository was developed in the Python 3 (3.8) programming language.

## Package installation

If you don't use google colab, We highly recommend to use and install Python packages within an Anaconda environment. To create, execute the command below:
```
conda update -n base -c defaults conda
```
```
conda create --name NID python=3.8
```
```
pip install notebook
```
So, activate it:
```
conda activate NID
```
Packages installation
```
pip install ipykernel
```
and display of environment in jupyter
```
python -m ipykernel install --user --name NID --display-name "NID"
```
Now, install the libraries
```
conda install -c conda-forge matplotlib
```
```
conda install -c anaconda seaborn
```
```
conda install -c districtdatalabs yellowbrick
```
```
conda install -c conda-forge imbalanced-learn
```
```
pip install imblearn
```
```
conda install -c anaconda scikit-learn
```
```
pip install scikit-image
```
```
pip install anaconda keras-gpu
```
```
pip install opencv-python
```
```
pip install pandas
```
```
pip install pydot
```
```
conda install -c conda-forge spacy
```
```
conda install openpyxl
```
```
pip install graphviz
```
```
pip install seaborn
```
```
pip install dtreeviz
```
```
pip install statsmodels
```
```
pip install xgboost
```
```
pip install spacy
```

## Execution
After installing all the Requirements, you must clone the repository using.
```
git clone https://github.com/BioAITeam/Intrusion-Detection-System-using-Machine-Learning.git
```
If you will use colab, upload the cloned folder to drive, then open the folder and run the notebook.

If you are going to use your computer, install:
```
conda install jupyter 
```
Enter the cloned folder, then enter the folder and run the notebook.

