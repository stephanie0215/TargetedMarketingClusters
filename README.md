<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<h1 align="center">Optimizing Targeted Marketing with Customer Segmentation</h1>
<div align = "center" style="text-align: left;" >
  <a href="https://github.com/stephanie0215/TargetedMarketingClusters/blob/main/Customer%20Segmentation.Rmd">
      <img src="https://www.tidio.com/wp-content/uploads/Customer-segmentation-min.png" alt="Customer Segmentation" width="400" height="200">
  </a>

<ul>
  <li>Customer segmentation is essential for retailers aiming to improve marketing effectiveness by tailoring strategies to distinct customer groups. By identifying key segments, retailers can enhance the return on marketing efforts and develop more targeted campaigns.</li>
  <li>This project applies clustering algorithms, specifically k-means, to perform customer segmentation. To determine which attributes are most relevant for clustering, a Random Forest model is used to identify key variables, allowing for the exclusion of less relevant attributes and improving the focus of the analysis.</li>
</ul>
<a href="https://github.com/stephanie0215/TargetedMarketingClusters/blob/main/Targeted_Marketing_Segmentation_Overview.pdf"><strong>Project Overview »</strong></a>

</div>

Built With

[![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)




<!-- TABLE OF CONTENTS -->
#### **TABLE OF CONTENTS**
<details>
  <summary>Click to expand</summary>
  <ol>
    <li>
      <a href="#dataset-used">Dataset used</a>
      <ul>
        <li><a href="#data-source">Data Source</a></li>
      </ul>
    </li>
    <li>
      <a href="#installation-guide">Installation Guide</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation-steps"> Installation Steps</a></li>
      </ul>
    </li>
    <li><a href="#result">Result</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Dataset used: Customer Campaign Responses

This dataset contains information about customer interactions with marketing campaigns conducted by a retail company. Each record represents a unique customer and includes various attributes related to their demographic characteristics, purchasing behavior, and responses to marketing offers. 
The key features of the dataset are as follows:
### Campaign Response Variables:
- **AcceptedCmp1 to AcceptedCmp5**: Binary indicators (1/0) indicating whether the customer accepted offers in the first five campaigns.
- **Response**: A binary target variable (1/0) that indicates whether the customer accepted the offer in the most recent campaign.

### Customer Demographics:
- **DtCustomer**: The date when the customer enrolled with the company.
- **Education**: The customer's level of education.
- **Marital**: The marital status of the customer.
- **Kidhome**: The number of small children in the customer's household.
- **Teenhome**: The number of teenagers in the customer's household.
- **Income**: The yearly household income of the customer.

### Customer Behavior:
- **Complain**: A binary variable indicating whether the customer has lodged a complaint in the last two years.
- **Recency**: The number of days since the customer's last purchase.

### Purchasing Behavior:
- **MntFishProducts, MntMeatProducts, MntFruits, MntSweetProducts, MntWines, MntGoldProds**: These variables represent the total amount spent on various product categories over the last two years.
- **NumDealsPurchases, NumCatalogPurchases, NumStorePurchases, NumWebPurchases**: Counts of purchases made under different conditions, such as using discounts or through specific sales channels.
- **NumWebVisitsMonth**: The number of visits the customer made to the company's website in the last month.


### Data Source
For more information, please visit the [Kaggle dataset page](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign/data).


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Installation Guide

To run this project, ensure you have the following software installed:

### Prerequisites

- **R**: Version 4.2.1 or higher
- **RStudio**: Recommended for an integrated development environment (IDE).

### Installation Steps

1. **Install R**:
   - Download R from the [CRAN website](https://cran.r-project.org/).
   - Follow the installation instructions specific to your operating system (macOS, Windows, Linux).

2. **Install RStudio** (optional but recommended):
   - Download RStudio from the [RStudio website](https://www.rstudio.com/products/rstudio/download/).
   - Follow the installation instructions.

3. **Install Required Packages**:
   - Open R or RStudio and run the following commands to install the necessary packages with their specified versions:

   ```R
   install.packages(c("factoextra" = "1.0.7", 
                      "cluster" = "2.1.4", 
                      "e1071" = "1.7-13", 
                      "rsample" = "1.1.1", 
                      "ranger" = "0.15.1", 
                      "caret" = "6.0-93", 
                      "lattice" = "0.20-45", 
                      "class" = "7.3-20", 
                      "randomForest" = "4.7-1.1", 
                      "vcd" = "1.4-11", 
                      "corrplot" = "0.92", 
                      "reshape" = "0.8.9", 
                      "GGally" = "2.1.2", 
                      "plyr" = "1.8.8", 
                      "forcats" = "0.5.2", 
                      "stringr" = "1.5.0", 
                      "dplyr" = "1.1.2", 
                      "purrr" = "1.0.1", 
                      "readr" = "2.1.3", 
                      "tidyr" = "1.3.0", 
                      "tibble" = "3.2.1", 
                      "ggplot2" = "3.4.2", 
                      "tidyverse" = "1.3.2"))


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Result-->
## Result

To view the results of this project, please visit the following link:
- [Project Overview PDF](https://github.com/stephanie0215/TargetedMarketingClusters/blob/main/Targeted_Marketing_Segmentation_Overview.pdf)
- [Download HTML File] (https://github.com/stephanie0215/TargetedMarketingClusters/blob/main/Customer-Segmentation.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Yung-Hui (Stephanie Pan)- [@linkedin](https://www.linkedin.com/in/stephanieyhpan) - stephanie22335@gmail.com

Project Link: [https://github.com/stephanie0215/TargetedMarketingClusters](https://github.com/stephanie0215/TargetedMarketingClusters)

<p align="right">(<a href="#readme-top">back to top</a>)</p>




