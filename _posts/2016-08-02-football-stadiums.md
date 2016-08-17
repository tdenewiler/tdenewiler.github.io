## Football Stadiums

I have always been a sports fan in the United States.
Over the years I have been exposed to the other football (soccer) and love the idea of relegation.
I wondered why United States sports leagues do not use this concept, especially in light of all the recent
tanking to procure better draft picks.
This led me to wonder how so many teams could be supported in the English Premier League and I started thinking
about geography.
I wanted to know what it would look like if the stadiums of the EPL were moved to the United States.
So I wrote some Python code to help me figure it out.

![EPL Stadiums in United States](http://76.88.102.31/img/ca_epl_stadiums.png)

All of the stadiums (not just the Premier league) would fit inside California and Nevada.

The plots were generated using [Basemap](http://matplotlib.org/basemap/) and a naive average
position offset approach for moving the stadium locations.
The sizes of the icons are based on the stadium capacity.

In the future I hope to try several other Python mapping packages and more sophisticated ways to
fit stadium locations to other areas.
Finding how far I would have to drive to see top-level sports if my local teams were relegated and
comparing that to other countries where relegation is part of sport is also interesting to me and
could help explain why that type of structure is not used in the major sports leagues of the United
States.
