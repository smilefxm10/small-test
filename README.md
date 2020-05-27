The whole data contains confirmed and fatalies, we need to predict both of them, so I divided the whole data into two part which are confirmed and fatalies.
Then in this data, there are 187 countries and after almost all countries shut down their border, so I assumed the virus could only be broadcast in their own country, so I used the same function to predict for every country individually.
Thirdly, I deleted the data which is zero before the first confirmed or fatalies emerge.
I used Holt winter predict function to predict the data and the seasonal order for confirmed is 10, for fatalies is 4 and these two numbers are calculated by experience.
I used to try Arima model to model the data, but for some countries it worked while some countries do not and I don't know why this happen.

I didn't know how to use he Weighted Pinball Loss score but I compare predictions to actual data and I found it is acceptable. Also I plot graphs to see the fit lines and the result seems well for me.
