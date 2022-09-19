# Module-11-Time-Series-Forecasting

For this challenge, we were asked to act as a growth analyst for MercadoLibre. We will analyze the company's financial and user data. We will seek if the ability to predict search traffic can translate into the ability to successfully trade the stock. In this repository we will produce a jupyter notebook that contains our data preparation, analysis, and visualizations for all the time series data that the company needs to understand. Including visual depictions of seasonality, an evaluation of how the company's stock price correlates to its google seach traffic, and plot a forecast for the company's future revenue.


# Technologies, libraries and dependencies

!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

import pandas as pd
from pathlib import Path
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
import numpy as np

# Results and graphs

![image](https://user-images.githubusercontent.com/108433370/191041875-32e96bf4-2ee3-402c-bc34-3d201df9a7f5.png)

![image](https://user-images.githubusercontent.com/108433370/191042642-c311233b-7aeb-45a5-a2a1-cc0775fcee37.png)

![image](https://user-images.githubusercontent.com/108433370/191043013-9a450c1b-1a0a-4c6a-9cf7-b316cf20e8ce.png)

![image](https://user-images.githubusercontent.com/108433370/191043418-64c6dac5-f26e-4717-bd4c-79de3b298cdb.png)

![image](https://user-images.githubusercontent.com/108433370/191045272-1b7400a1-1b6e-43d8-a5c6-00dd7ee783d5.png)

![image](https://user-images.githubusercontent.com/108433370/191045521-1a88235c-198a-467c-8894-dfabc72317df.png)

![image](https://user-images.githubusercontent.com/108433370/191046178-888ebf7c-dc03-4d14-a984-02aa8e7783b5.png)

![image](https://user-images.githubusercontent.com/108433370/191048813-f87d9234-86f0-482c-8507-55d30da88622.png)

![image](https://user-images.githubusercontent.com/108433370/191049135-ea935242-87e8-4f9f-8563-2a86f7f1091c.png)

![image](https://user-images.githubusercontent.com/108433370/191049260-e2c264bc-2f73-4690-84c9-40df0c04797f.png)

![image](https://user-images.githubusercontent.com/108433370/191050084-567571fe-f7f9-4d03-bfbb-c1349ec6db91.png)

![image](https://user-images.githubusercontent.com/108433370/191050352-e8e8b6ed-4d59-43df-88cb-6d0242065075.png)

![image](https://user-images.githubusercontent.com/108433370/191050816-cb8fcd8b-536e-44de-94db-bbd7eded664d.png)








