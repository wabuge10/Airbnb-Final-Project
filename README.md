# Airbnb Price Prediction in Los Angeles
Airbnb is a home-sharing platform that allows home-owners and renters ('hosts') to put their properties ('listings') online, so that guests can pay to stay in them. Hosts are expected to set their own prices for their listings. Although Airbnb and other sites provide some general guidance, there are currently no free services which help hosts price their properties. Paid third party pricing software is available, but generally you are required to put in your own expected average price ('base price'), and the algorithm will vary the daily price around that base price on each day depending on day of the week, seasonality, how far away the date is, and other factors.

Airbnb pricing is important to get right, particularly in big cities like Los Angeles where there is lots of competition and even small differences in prices can make the difference between optimum occupancy and high earnings, or being priced out of the market. It is also a difficult thing to do correctly, in order to balance the price with occupancy (which varies inversely with price) in order to maximise revenue.

This project aims to use machine learning and deep learning to predict the base price for properties in London, and also to explore Airbnb listing data, in order to help Airbnb hosts maximise their earnings.

Additional context: I previously worked for a year and a half at an Airbnb property management company, as head of the team responsible for pricing, revenue and analysis. Decisions made during the course of this project are therefore informed by domain expertise in this industry.

The Dataset
The dataset used for this project comes from insideairbnb.com

Limitations
The biggest problem is that the data is quite messy and which is a huge disadvantage in that it only includes the advertised price(which is sometimes called the 'sticker' price).The sticker price is the overall nightly price that is advertised to potential guests, rather than the actual average amount paid per night by previous guests. The advertised prices can be set to any arbitrary amount by the host, and hosts that are less experienced with Airbnb will often set these to very low. A more accurate version could be built using data on the actual average nightly rates paid e.g from sites like AirDNA that sell higher quality Airbnb data.
