# Exploratory Data Analysis in Amazon datasets
---
### Contributors

- Juan F. García-Moreno

---
### Objective

The purpose of this repository is to conduct an Exploratory Data Analysis of product data from Amazon. By leveraging statistical techniques, data visualization, and advanced data analysis methods, we strive to uncover valuable insights and patterns within the dataset.

---
### Project Structure

- amazon_data_files: This directory contains the Amazon datasets.
- notebooks: This directory contains Jupyter notebooks with the exploratory data analysis code.
- images: This directory stores images generated during the EDA.

---
### Data Visualization

Here is the bar plot displaying Top10 most popular manufacturers:
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
The histogram reveals that the majority of products are sold in the price range of approximately `10` to `4000`. However, there's a long tail on the right side, confirming our earlier inference from the skewness value that there are products sold at much higher prices. The Kernel Density Estimate (the smooth line) also shows the right-skewed nature of the distribution.
</p>


