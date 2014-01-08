## ThisOnesOnGitHub™ :tada: GitHub Drinkup Metrics :tada:

What's more fun than a [GitHub Drinkup](https://github.com/blog/category/drinkup)? **GitHub Drinkup Metrics**! Data! Hooray!!! :+1::+1::+1:

Drinking :potable_water:, :tea:, :coffee:, :wine_glass:, :cocktail:, :beer:, kombucha or whatever?  Record it!  

### Format
**ThisOnesOnGitHub™** records GitHub Drinkup Metrics via [TOML](https://github.com/mojombo/toml).

*./drinkups/20140107_los_angeles.toml*
```toml
when = "2014-01-07T20:00:00-08:00" # iso8601 with timezone
venue = "Lucky Baldwin's Trappiste Pub & Cafe"
address = "1770 E Colorado Blvd, Pasadena, California, United States"
coordinates = [
  -118.1138755,
  34.1457363
]

[[drinks]]
login = "simeonwillbanks"
name = "Lucky Baldwins Red Belgian Ale"

[[drinks]]
login = "jch"
name = "Gulden Draak"

# not alcoholic? totally cool!
[[drinks]]
login = "simeonwillbanks"
name = "Cappuccino"

# maybe you're a beer geek
[[drinks]]
login = "simeonwillbanks"
name = "Kwak"
style = "Belgian Golden Strong Ale"
abv = 8.1
ibu = 50
srm = 16
```

### BigData
The people want to know... and **ThisOnesOnGitHub™** is here to help. :bar_chart: :bar_chart: :bar_chart: 

 - *Bud Lite* vs. *Coors Light* vs. *Miller Lite* vs. *Natural Lite*, Who Wins?
 - The average distance between an Apple Store and a Drinkup
 - Which GitHub user has attended the most Drinkups?
 - So much more!!! :chart_with_upwards_trend: :chart_with_upwards_trend: :chart_with_upwards_trend: 

### Contributing
![Excellent](http://img.pandawhale.com/72017-bill-and-Ted-excellent-gif-JLyQ.jpeg)

 1. Attend a [GitHub Drinkup](https://github.com/blog/category/drinkup)
 2. Imbibe
 3. [GitHub Flow in the Browser](https://github.com/blog/1557-github-flow-in-the-browser)

### Continuous Integration [![Build Status](https://travis-ci.org/simeonwillbanks/this_ones_on_github.png?branch=master)](https://travis-ci.org/simeonwillbanks/this_ones_on_github) 
For Reals B.  When you fat finger your drink entry, [Travis](https://travis-ci.org/simeonwillbanks/this_ones_on_github) got your back.
