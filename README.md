# Conversion_Rate_Optimization

## Problem Statement
Given data related to the characteristics and browsing behavior of customers at an E-commerce site, come up with recommendations for the product and the marketing teams to improve conversion rate. In particular, we should identify the characteristics of power users to help the marketing team to reach them using different marketing channels. In addition, worse-performing segments are opportunities for product improvement.

## Description 
Build a model to predict the binary outcome(converted or not). Based on the model result, come up with recommendations to improve conversion rate.
- merged_dat.csv: The dataset contains information about users who hit an ecommerce site. We know some of their characteristics, such as their country, marketing channel, etc. We also know whether they converted or not. 
- EDA.ipynb: Exploratory data analysis to understand the data distribution
- Improve_Conversion_Rate.ipynb: Supervised models to predict conversion and extract insights 

## Conclusions 
- Returning customers are much better than new users and young users have a higher retention rate than old users. Also, most young users come from search engine. Targeted emails with offers to bring them back to the site could be a good idea to try.

- Taken users in China as a reference level, users in Germany, UK, and US have much higher conversion rate. This could be an indicator of bad translation or bad UI design with the Chinese version of the site. Given how many users are based in China, fixing this should be a top priority.

- Other than China, users in Germany, UK, and US have similar conversion rate, with Germany being the best. However, the site has the least amount of users from Germany compared to other countries. Attaracting more users from Germany could another goal for the marketing team.

- The site works well for people under 30. From ~30 y/o conversion clearly starts dropping. Oone possible cause if that the UI design is not friendly to old users. To solve this problem, a good actionable metric to work on is conversion rate for people >=30 yr old.

