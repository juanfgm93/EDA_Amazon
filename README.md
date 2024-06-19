# Exploratory Data Analysis in Amazon datasets
---
### Contributors

- Juan F. García-Moreno

---
### Objective

The purpose of this repository is to conduct an Exploratory Data Analysis of product data from Amazon. By leveraging statistical techniques, data visualization, and advanced data analytics methods, we strive to uncover valuable insights and patterns within the dataset.

---
### Project Structure
#### 1. Extract data
. Uses of Amazon API
- amazon_data_files: This directory contains the Amazon datasets.
#### 2. Data transformation and EDA
- notebooks: This directory contains Jupyter notebooks with the exploratory data analysis code.
- images: This directory stores images generated during the EDA.

---
### Data Visualization

After carefully performing data wrangling, we proceeded to visualize product data through diverse types of plots to understand trends and patters. Here is a bar plot displaying the Top10 most popular manufacturers:
<div style="text-align: center;">
  <img src="images/top10_manufacturers.png" alt="Top 10 Manufacturers" width="500"/>
</div>

<p style="margin-top: 20px;">
The plot shows the number of items among the top manufacturers. According to the above visualization, Puma is the most popular brand.
</p>

In the next image, the most popular categories in the Top10 manufacturers are shown.
<div style="text-align: center;">
  <img src="images/categories_popularity.png" alt="Top 10 Manufacturers" width="500"/>
</div>

<p style="margin-top: 20px;">
The plot shows the number of items among categories. The most popular category in Top10 manufacturers is men's clothing.
</p>

Next, we analyzed the main subcategories in Amazon within the top10 manufacturers considering the top5 categories.
<div style="text-align: center;">
  <img src="images/top10_subcategories.png" alt="Top 10 Manufacturers" width="500"/>
</div>

<p style="margin-top: 20px;">
The plot shows the number of items among subcategories. The most popular subcategory is Sports Shoes, followed by Shirts and T-shirts & Polos.
</p>

In the following graph, price distribution is displayed across the Top10 manufacturers, and considering Top5 categories and Top10 subcategories.
<div style="text-align: center;">
  <img src="images/price_distribution.png" alt="Top 10 Manufacturers" width="500"/>
</div>

<p style="margin-top: 20px;">
The histogram reveals that the majority of products are sold in the price range of approximately `10` to `4000`. However, there's a long tail on the right side, indicating that there are products sold at much higher prices. The Kernel Density Estimate (the smooth line) also shows the right-skewed nature of the data distribution.
</p>

Then, we analyzed the presence of outliers regarding product prices.
<div style="text-align: center;">
  <img src="images/outliers.png" alt="Top 10 Manufacturers" width="500"/>
</div>

<p style="margin-top: 20px;">
The pie chart shows that around 3.5% of product data within the Top10 manufacturers are outliers.
</p>

Finally, a violin plot was created to understand how price is distributed across the top10 manufacturers.
<div style="text-align: center;">
  <img src="images/price_distribution_across_manufacturers.png" alt="Top 10 Manufacturers" width="900"/>
</div>

---
### Conclusions:
1) The most popular brand is Puma.
2) The most popular category in Top10 manufacturers is 'men's clothing'.
3) The most popular subcategory is 'Sports Shoes' followed by 'Shirts and T-shirt's & 'Polos'.
4) The products with price less than ₹4000 are more popular.
5) Around 3.5% of product data within the Top10 manufacturers are outliers.
6) Puma, Red, Adidas and Levi's display a wide range of prices. Puma and Levi's have a thicker section around the median, suggesting that most products in these brands fall within this price range.
7) Campus, US and Amazon have a more condensed price distribution, displaying a majority of products priced in the lower to mid-range.
8) Van, Clovia and Pepe have a bimodal distribution, indicating two major groups of product prices.





