#Python Implementation of Apriori Algorithm 
==========================================

The code attempts to implement the following paper:

> *Agrawal, Rakesh, and Ramakrishnan Srikant. "Fast algorithms for mining association rules." Proc. 20th int. conf. very large data bases, VLDB. Vol. 1215. 1994.*

Interactive Streamlit App
-------------
To view a live interactive app, and play with the input values, please click [here](https://share.streamlit.io/asaini/apriori/python3). This app was built using [Streamlit](https://www.streamlit.io) 😎, the source code for the app can be found [here](https://github.com/asaini/Apriori/blob/python3/streamlit_app.py)


CLI Usage
-----
To run the program with dataset provided and default values for *minSupport* = 0.03 and *minConfidence* = 0.2

    python apriori.py -f INTEGRATED-DATASET.csv

To run program with dataset  

    python apriori.py -f INTEGRATED-DATASET.csv -s 0.17 -c 0.68

Best results are obtained for the following values of support and confidence:  

Support     : Between 0.1 and 0.2  

Confidence  : Between 0.5 and 0.7 


List of files
-------------
1. apriori.py
2. INTEGRATED-DATASET.csv
3. README(this file)

