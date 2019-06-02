# Module 1 Final Project

Real estate makes up an enormous portion of the economy of the United States. It should be no surprise that a house is often the most important purchase a person or family may ever make. With so much weight attached to the selling of a house, it is important that a home owner try their best to sell their house for as much as the market will bear and for home buyers to purchase a house for as little as possible. To achieve both ends simultaneously, statistical models can be very useful.

This project will utilize a year's worth of housing data from the Seattle metro area to construct a model to accurately predict the sale price of a home based on the variables present in the dataset. 

- This project utilizes the dataset called [kc_house_data.csv](kc_house_data.csv)
- You can view the whole process in [student2.ipynb](student2.ipynb)

The questions we will answer in the midst of this project are:

- How can we reduce the number of variables in our model to something manageable?
- How might we handle geographical variables?
- Do we have any linear relationships?

If you are curious about my own journey through this process, feel free to read my [blog](https://profparker.blogspot.com/).

This project resulted in the creation of a model that can predict the sale price of a house with an error of around 126,700 USD. The equation for this model is as follows:

$$p = (1296579.6 \times f_L) + (60401.32 \times f_V) + (110.79 \times f_B) + (59144.57 \times f_G) + (111362.3 \times log_e(f_S)) - 62564620.4$$

$p =$ House price (in USD)

$f_L =$ latitude

$f_V =$ times property has been viewed

$f_B =$ square footage of basement

$f_G =$ grade given to the housing unit, based on King County grading system

$f_S =$ square footage of living space
