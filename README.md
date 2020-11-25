# 311AlleghenyCallsAnalysisAndPrediction

**nbviewer link**: [https://nbviewer.jupyter.org/github/noopurm912/311AlleghenyCallAnalysisAndPrediction/blob/main/311CallsAnalysisAlleghenyProject.ipynb](https://nbviewer.jupyter.org/github/noopurm912/311AlleghenyCallAnalysisAndPrediction/blob/main/311CallsAnalysisAlleghenyProject.ipynb)

**311 Allegheny Call Analysis, visualization, and Prediction**

**Background**

**Data used**: 311 Data - Allegheny County / City of Pittsburgh / Western PA Regional Data Center

**Data Source**: [https://catalog.data.gov/dataset/311-data-in-development](https://catalog.data.gov/dataset/311-data-in-development)

The dataset includes the 311 calls detail for Allegheny County, PA from 2015 to 2020. 311 is a nonemergency phone number, people can call to find information about services and to raise complaints as
well like graffiti, road damage, etc. The data is also useful to provide wealth of insight of how cities are
run and their functional improvement for future.

Motivation: In my quest of finding the dataset, which could function well with the algorithm and mining
method learned in the course. I stumbled upon this dataset which will provide a great supervised
learning solution using powerful classification algorithms such as Random Forest Algorithm and Time
series analysis with ARIMA model.

**Tasks**:

**1: Data Analysis and Visualization**

**2: Time Series Analysis**: To predict the number of 311 Request raised on each date based on the data
available using ARIMA model

**3: Random Forest Classifier**: Predict the values of column NEIGHBORHOOD based on the information
contained in the other columns using Random Forest Classifier Algorithm.

This data analysis is based on the hypothesis that it could be used by the county to optimally allocate
their resource in cost efficient way. The Call volume and requests have been analyzed based on their
origin, day of the week, day, day of the month, month of the year and further the ARIMA model is used to
predict when can we expect higher/lower volume of request. Furthermore, Random Forest algorithm is
used to predict the neighborhood using the coordinates of the area for which request is raised. With the
help of prediction, County can decide on which neighborhood needs more attention based on their
issues.

