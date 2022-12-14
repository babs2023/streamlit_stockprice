# A Simple Streamlit Tutorial 

This is a simple tutorial to demonstate how to use the **streamlit** python module/library to create a web application that displays the stock price of any listed organization by pulling data from Yahoo finance using the **yfinance** module.

Streamlit turns data scripts into shareable web apps in minutes. All in pure Python. No front‑end experience required.

NOTE: To implement this tutorial you should be using the ANACONDA python distribution.

# Steps

1. Download the streamlit library by following the [installation steps](https://docs.streamlit.io/library/get-started/installation) as desribed on the streamlit website.
2. After this step simply import the module as follows:

```python
import streamlit as st
```
3. Next, copy the code from this link: https://github.com/babs2023/streamlit_stockprice/blob/main/stockprice.py and make any necessay changes. You can change the ticker symbol to that of any organization you which to view their stock price.
4.  To deloy your code as a streamlit web application, go to the anaconda command promopt, change the directory to the directory where your python script is saved and run the follwing command:
```
c:\directory>streamlit run <file.py>
```


