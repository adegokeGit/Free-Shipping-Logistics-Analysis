# Targeted Minimum Order Values Could Lift Gross Margin by 1.2 Points, Without Ending Free Shipping Offer

**Free Shipping Logistics Analysis**

#### Objective

The objective I aimed to achieve was to identify which states carry disproportionately high logistics costs under an eCommerce brand’s free shipping offer, compared with other state.

#### Results

**Cost of delivery (% of sales) per State**

- Highest: 23.31%
- Average: 16.76%
- Lowest: 11.86%

**Gross margin (%) per State**

- Highest: 64.52%
- Average: 60.36%
- Lowest: 53.22%

### Key Finding

Fulfillment costs follow a clear geographic pattern. High-volume states such as Lagos operate efficiently, with delivery costs below the 16% national average. Cross River, Ebonyi and Katsina exceed 20%, and Northwest and Southeast states generally sit above the 16% national average.

#### Conclusion

I recommend introducing **regional minimum order values** only in the low-efficiency zones that need them, rather than applying a blanket policy nationwide. Bringing these states to or below the 16% national average could lift the total average net margin by a projected **1.2 percentage points**.

#### Technical Review

- **Data preparation:** The dataset was 150 records of sales transactions of an Ecommerce brand over a given period of time, it was a clean dataset, so preparation was limited to dropping unneeded columns.
- **Feature engineering:** I created three features: gross profit, net profit and cost of delivery percentage.
- **Aggregation and analysis:** I aggregated transaction-level data to the state level, then calculated each state’s average cost of delivery (%) and net margin (%).
- **Visualization:** I built an interactive Power BI map for stakeholders. Red marks states with above-average delivery costs, green marks states operating efficiently, and gray marks states with no sales or shipments.

<img width="1047" height="631" alt="Free-Shipping-Logistics-Analysis-Map-PowerBI" src="https://github.com/user-attachments/assets/6f0c4379-7ccd-4b19-8934-1ce963b2f593" />

Image above shows a snapshot of the interactive Power BI map

You can access the LIVE interactive map here:
https://adegokegit.github.io/Free-Shipping-Logistics-Analysis/

#### Assumptions

The projected 1.2 point margin gain assumes each percentage point of delivery cost removed adds one point to net margin, with prices and all other costs held constant.

### Tech Stack

- Python(Pandas)
- PowerBI
