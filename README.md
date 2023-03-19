# BigData

# Overview of Analysis

The purpose of this module is to analyze customer reviews written by Amazon Vine members. This service allows manufacturers and publishers to recieve reviews for their products. I used the video game dataset to create dataframes using Python, SQL, and Pandas to complete the analysis. I then uploaded them to AWS, a cloud database, so that they can be accessed publically.

# Results

![image](https://user-images.githubusercontent.com/109708202/226216245-cc7778be-5144-4e92-b514-a503dafdb110.png)
The image above shows the first line of a dataframe to show the number of reviews for members who paid for the Vine services. As you can see it totals up to 104 total users.

![image](https://user-images.githubusercontent.com/109708202/226216313-575bfb95-bd1d-4574-8b69-220b37ed9bf3.png)
The image above shows the first line of a dataframe to show the number of reviews for members who did not pay for the Vine services. As you can see it totals up to 65275 total users.

![image](https://user-images.githubusercontent.com/109708202/226216344-31a4f4d7-9cd0-45ca-8320-1c90329c9413.png)
The image above shows the number of reviews from those who did not pay for the Vine services. As you can see the total number of 5-star reviews from non paying users was 20439.

 ![image](https://user-images.githubusercontent.com/109708202/226216421-c07407a5-fb70-4d5f-af4b-68618c2010ad.png)
The image above shows the number of reviews from those who paid for the Vine services. As you can see the total number of 5-star reviews from non paying users was 48.

![image](https://user-images.githubusercontent.com/109708202/226216451-5d6ae0aa-a668-46a1-a463-cb066d5db461.png)
The image above shows the percentage of 5-star ratings for those who did not pay for the Vine services.

![image](https://user-images.githubusercontent.com/109708202/226216503-b6e7b0d0-2b6b-4d4d-9271-5a2ef9ca0afe.png)
The image above shows the percentage of 5-star ratings for those who paid for the Vine services.

# Summary
Based on the results of my analysis, there does not look like there is a positibity bias for reviews written by Vine paying members. I found that 31.31% of the reviews written by non paying members were 5-stars and 46.14% of the reviews written by paying members were 5-stars. Though, just looking at percentages, its seems there may be a biased, the vast majority of total members did not pay for the Vine membership, 20439 versus 104 members who did pay for the Vine membership.

One additional analysis that could be helpful would be to conduct a similar analysis to another dataset provided. This new analysis would allow us to see if there is a similar trend across mulitple products or if it was unique to the dataset used in this analysis.
