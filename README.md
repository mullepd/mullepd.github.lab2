# Parker Mullen
**Lab 2**
**GEOG 458**
**4/15/2022**

*GEOG 458 Lab 2 - collecting and mapping geotagged tweets using Tweepy and GQIS.*

## Overview of the Lab
The purpose of this lab was to gain experience interacting with the Twitter API
as well as mining social media data, then doing some very basic analysis of the
data in the form of word clouds and maps.

To interact with the Twitter API, we used Tweepy in a python script to pull and
store geotagged tweets in realtime. We then took the CSV's and mapped them
using QGIS in order to understand the spatial distribution of tweets in the
continental United States. *Note: I used the continental US because I was not
getting very good data from other geographical areas of interest.* In tandem
with the spatial distribution of tweets, we used Word Art to analyze the most
common words that were tweeted within this geographical region.

I decided to compare geotagged tweets within the US between Frriday and Saturday. I thought it would be interesting to see the geographical distribution of tweets as well as the text breakdown of the tweets from the end of the work week to the start of the weekend. I predicted that the density of geotagged tweets on Saturday would be higher than that on Friday simply because many people have Saturday off. However, this was not the case. There was no real difference in density from Friday to Saturday, and only minor changes in the word breakdown of the tweets.

## Analyzing the maps
The first day I collected geotagged tweets was on Friday. Most of the tweets collected on Friday were distributed around Seattle, San Francisco, Los Angeles, and then a high density up and down the entire eastern seaboard. Denver and Salt Lake City were the only cluster of geotagged tweets throughout much of the midwest.

On Saturday, there were fewer tweets located in California and more tweets along the northwest coast of Washington (north of Seattle). The eastern seaboard was still just as dense with tweets; Salt Lake City and Denver were still the only real cluster of geotagged tweets in the midwest.

## Analyzing the word clouds
Excluding "Co", "L$\hat a$" and "Dy" (I do not know if these were errors that occured during the pulling of the twitter data, or if they were actually used), many tweets included the words job and work perhaps alluding to people discussing either their jobs or the work/jobs of more prominent people. Love and time were both tweeted plenty, and one can even see Elonmusk in the word art. I am surprised that Elon was not higher on the list especially with his bid to buy out Twitter completely.

On Saturday, Co, "L$\hat a$" nad "Dy" made another appearance weird enough. Work has disappeared however, job still shows up rather frequently. Love and time still show up frequently. There seems to be an increase in vulgar words as compared to friday, happy, kid and photo also appear more on the weekend. Elonmusk unsurprisingly shows up again. Baseball showed up on Saturday, kinda neat since opening day was the 7th of April and the Mariners had their first home game on Friday. Perhaps the boost to baseball came from Seattle and the excitement surrounding the Mariners having a team that could reach the playoffs for the first time in two decades!
