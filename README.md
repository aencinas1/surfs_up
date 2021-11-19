# Surfs Up - An Analysis of Hawaiian Temperatures and Building a Business
In this challenge, W. Avy wants to take our anaysis one step deeper. Using the data available, W. Avy wants the temperture statistics for the months of both June and December, to determine if the surf shop/ice cream shop is sustainable year-round. We will pull the data and organize it by min, max, average, etc. to give W. Avy an all-encompassing view of monthly temperature.

# The Results
From the available data, we were able to pull temperatures for both June and December, and used the .describe() funtion to display the following information:

![](june_describe.png)

![](dec_describe.png)

From these, we can conclude several things:
* We can see that the lowest temperature in December was 56 degrees. This is too cold for both surfing and ice cream, but the minimum does not tell the entire story. The average temperature in December was 71 degrees. This temperature is suitable for surfing and ice cream, and the standard deviation tells us that temperatures in December typically fall between 68-74 degrees. This means that the surf/ice cream shop can expect to have temperatures that are good for business in the month of December.
* It should be no surprise that temperatures in June are good for surfing and ice cream. With an average temperature of nearly 75 degrees, and a standard deviation yielding a temperature range of 72-78 degrees, June would be a very advantageous time to own a surf/ice cream shop. There's always the chance of a chillier day (min was 64) but on average June in warm enough for a shop.
* Looking at the mean, as well as the quartiles, temperatures in June are pretty similar to temperatures in December. We can expect June to be warmer on average, but both months are suitable for a surf/ice cream shop. Since both months can reasonably be assumed to capture teamperatures year round, W. Avy should have no problems keeping the shop operational all year long.

# Summary
W. Avy should be comfortable opening his surf/ice cream shop based off of my results. However, there are several options W. Avy could consider to capture a more complete picture of temperatures as it pertains to his business strategy. 
