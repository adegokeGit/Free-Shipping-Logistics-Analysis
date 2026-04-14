# Identifying-Logistics-Leakage-by-Region
Business Problem: The supplement eCommerce brand offers free shipping, but shipping supplements can be expensive. Some states might be "profit-killers."

I needed to identify where the brand was losing money on its 'Free Shipping' offer.

I loaded up the dataset into Jupyter Notebook, preprocessed the data and carried out Regional Margin Analysis using the pandas library in Python

The Regional Margin Analysis revealed a clear spatial pattern in fulfillment costs. While high-volume states like Lagos maintained efficient logistics (Leakage < 15%), smaller markets in the Northwest and Southeast of the country showed Logistics Leakage spikes above 20%.

Based on the analysis, I recommended implementing regional minimum order values to restore profitability in these "low-efficiency" zones

I also utilized Tableau to visualize the regional profitability for the brand by mapping the Logistics Leakage. 

https://public.tableau.com/views/IdentifyingLogisticsLeakagebyStateforaneCommerceBrandinNigeria/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
