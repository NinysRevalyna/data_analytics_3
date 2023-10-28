# DATA ANALYTICS #3

# Business Understanding

The diamond industry is a highly competitive, market-driven industry. Diamond manufacturers and jewelry retailers need to have a deep understanding of diamond characteristics and market trends to make informed decisions regarding production, inventory, pricing, and marketing. Consumers seek diamond jewelry that aligns with their preferences. Therefore, data analysis on the diamond dataset can provide valuable insights to understand the market and optimize business operations.

# Business Benefits
- Operational efficiency improvement: Data analysis can help diamond manufacturers optimize production and inventory management, reduce wastage, and enhance operational efficiency.
- Sales enhancement: By understanding customer preferences, both manufacturers and retailers can offer products that better align with market demand.
- Increased customer satisfaction: Providing more relevant recommendations to consumers can improve customer satisfaction.
- Stronger competition: With a better understanding of the market and pricing, diamond businesses can compete more effectively in a competitive global marketplace.

# Expected Outcomes
- Enhanced understanding of the diamond market.
- Improved operational efficiency in diamond production and inventory management.
- Increased sales of diamond jewelry.
- Higher customer satisfaction.

# Data Understanding
- Dataset Overview :

  The diamond dataset is a collection of data related to various attributes of diamonds, including carat weight, cut quality, color, clarity, depth percentage, table percentage, price, and more. Understanding this dataset is crucial for conducting meaningful analyses and drawing insights about the characteristics and pricing of diamonds.

- Data Sources :

  Load the dataset in the seaborn library

- Data Size and Structure :

  The dataset consists of 29708 rows and 10 columns. Each row represents an individual diamond. The columns include both numerical and categorical data, such as carat, cut, color, clarity, price, etc.

- Data Attributes :
  - Carat: A numerical value representing the weight of the diamond in carats.
  - Cut: A categorical attribute describing the quality of the diamond's cut (e.g., Fair, Good,   - Very Good, Premium, Ideal).
  - Color: A categorical attribute describing the color of the diamond (ranging from J, the lowest color grade, to D, the highest).
  - Clarity: A categorical attribute describing the clarity of the diamond (e.g., I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF).
  - Depth: A numerical attribute representing the depth percentage of the diamond.
  - Table: A numerical attribute representing the table percentage of the diamond.
  - Price: The price of the diamond in a given currency.
  - x (Length): Measures the length of the diamond in millimeters. This is the measurement of the diagonal length from one end of the diamond to the other.
  - y (Width): Measures the width of the diamond in millimeters. This is a measurement of the diagonal width from side to side.
  - z (Depth): Measures the depth of the diamond in millimeters. This is the vertical distance from the top of the diamond to the bottom.

# Data Preparation
- Python Version : 3.11.4
- Packages : Pandas, Matplotlib, Seaborn

# Data Cleansing

There are 3 columns that have NaN values and solve them using the mean to fill in the NaN values in columns x, y, and z.

# Exploratory Data Analysis (EDA)

### Price Based on Carat Range
![image](https://github.com/NinysRevalyna/data_analytics_3/assets/72516143/deefd9ae-7e82-47a9-8fe0-c47ae20e628e)

Based on the histogram above depicts the distribution of diamond prices across various carat categories, allowing us to see the price spread and how frequently diamonds with specific carats appear in the diamond dataset. Taller bars indicate more popular carat categories. A total of 43.74% of the diamonds in the dataset have carats between 1.00 and 1.50. This indicates that diamonds with carats in this range are very common or popular in the diamond market. It reflects a higher consumer demand for diamonds within this carat range.

###  Diamond Clarity Levels
![image](https://github.com/NinysRevalyna/data_analytics_3/assets/72516143/1bf9cfca-4efa-4f43-854c-a8a622d0ada6)

Based on the data above, the SI1 clarity level of 26.32% is a common choice. Most of the diamonds in the diamond dataset have defects that tend to be small or moderate. Despite some flaws, diamonds at this grade are still of good quality and are often a popular choice due to their more affordable price. Meanwhile, the IF clarity level of 1.63% shows that the diamond in the category is practically free from internal defects, and I1 of 1.62% is the lowest in terms of quality with very obvious defects.

### Diamond Color
![image](https://github.com/NinysRevalyna/data_analytics_3/assets/72516143/3f5878da-592c-4b98-82a3-6035a0cc27e7)

Based on the data above, the color of diamonds in category G is 20.38% one of the common colors. G color diamonds are barely visible and have almost no color. Meanwhile, 6.69% of diamonds in the J category may have a more visible color. J color diamonds may be a more affordable option but have little visible color. Diamonds with colors that are as close to colorless as G tend to command higher prices due to their high color quality. On the other hand, diamonds with more visible colors like J may be a more affordable option.

### Average Diamond Prices Based on Cut Type
![image](https://github.com/NinysRevalyna/data_analytics_3/assets/72516143/3c21c4dc-5e27-4051-a2a8-13957c15a029)

Based on the data above, the Premium cut type of 0.0037% is the cut type with the highest average price among all cut types. This may be due to the excellent cut quality, which produces diamonds with exceptional sparkle and appearance. The lowest cut type, namely Good at 0.0031%, has the most affordable average price among all cut types. Good cut diamonds may have some drawbacks in cut quality compared to other cuts, but are often a more economical choice.

### Diamond Depth
![image](https://github.com/NinysRevalyna/data_analytics_3/assets/72516143/afe97dd0-0f1e-4d24-b3a9-a00438223ff4)

Based on the data above, the depth level ranges from 60 to 65 indicating that most diamonds have a depth level in this range. The highest peak is around 62 which is 42.22%, which indicates that the depth level of 62 is the most common.


