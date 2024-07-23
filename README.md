
# Indian Counterfeit Currency Detection and Denomination Recognition

The manufacturing of counterfeit cash is one of the most significant economic setbacks. In the recent past, as a result of technological breakthroughs in colour printing, new methods of counterfeiting cash have emerged. After demonetization in India, the situation has worsened and numerous counterfeit currencies have entered the market. According to current data, the Reserve Bank of India estimates that counterfeit cash is worth around 2 trillion rupees. This surge of counterfeit cash has been a huge issue, especially for the average citizen, and now even banks and ATMs are dispensing Counterfeit currency. Because of their resemblance to actual banknotes, practically everyone, from produce vendors to businessmen, is hesitant to take currency in the denominations of 500 and 2,000. The only answer to this problem is the widespread use of counterfeit cash detecting devices, which are mostly located in banks but are not always accessible to the common person. By developing this system, we intend to provide a simple and effective method for identifying counterfeit currency, which will be of enormous use to the average person. The application would be readily available to the general public. In addition to determining if a bill is counterfeit or not, our technology is also capable of recognising the scanned cash. Using a variety of CNN models, we have conducted cash recognition and verification. The concept provided by our system is to take images of currency notes with denominations of 10, 100, 200, 50, 500, and 2000 on a mobile device and, after processing, determine if the currency is counterfeit and determine its denomination worth. Banks have various uses for money verification, as they often deal with counterfeit currency. A person using a mobile phone would find our approach highly handy for verifying the legitimacy of his cash note. There would also be a speech announcement on recognising and validating a money note, making currency note recognition an useful function for visually challenged individuals.


## Installation

This project consists of two parts Currency detection and denomination recognition. For Currency detection part, data preprocessing is done in the Currency_detection-DataPreprocessing.ipynb notebook and model training is done in Currency_detection.ipynb notebook. Whereas for the denomination recognition part, both data preprocessing and model training are done in the Denomination_Recognition.ipynb notebook.

To run the notebooks, copy the datasets into your drive or use it as it is. Open the notebook in google colab. While running the notebooks, modify the paths of the dataset.


The link for the dataset is: https://drive.google.com/file/d/12V6aGS_NL__RQJ10dnZw7cAEfxcolkB_/view?usp=sharing