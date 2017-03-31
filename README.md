# Tweeter Analysis-PANDAS
[![screenshot_1490978130.png](https://s19.postimg.org/3z75lt9gz/screenshot_1490978130.png)](https://postimg.org/image/em0yr8hm7/)
[![screenshot_1490978440.png](https://s19.postimg.org/ldrdu36lv/screenshot_1490978440.png)](https://postimg.org/image/bggd10yzz/)
NO Twitter API, Reading Twitter Analytics data.csv file and Python

## Top 5 Retweets and its count:
[![screenshot_1490977562.png](https://s19.postimg.org/8rcdjier7/screenshot_1490977562.png)](https://postimg.org/image/slyf5mtyn/)

## Top 5 liked Tweets and its count:
[![screenshot_1490977620.png](https://s19.postimg.org/4jhlardbn/screenshot_1490977620.png)](https://postimg.org/image/pgdtffbcf/)

## Top 5 tweets with most impressions:
[![screenshot_1490977691.png](https://s19.postimg.org/5zt3swg8j/screenshot_1490977691.png)](https://postimg.org/image/c0qspz2un/)
-----
## All Hashtags
```
# The 10 most popular tags and counts
tweet_string = ' '.join(str(e) for e in tweets)
#tweet_string
all_hasttags=[i  for i in tweet_string.split() if i.startswith("#") ]
all_hasttags[:3]
```
[![screenshot_1490977879.png](https://s19.postimg.org/ys4gq4d9v/screenshot_1490977879.png)](https://postimg.org/image/ekr0xtfsf/)

## Top 10 hashtags:
[![screenshot_1490931809.png](https://s19.postimg.org/uwrvw2fcj/screenshot_1490931809.png)](https://postimg.org/image/ygdtlvi27/)
## Top 10 mentions:
[![screenshot_1490931831.png](https://s19.postimg.org/407wnqwj7/screenshot_1490931831.png)](https://postimg.org/image/jygmdvqr3/)
-----

## Tweets per day:
[![screenshot_1490977754.png](https://s19.postimg.org/k7ndvaib7/screenshot_1490977754.png)](https://postimg.org/image/3wn9yz5tb/)

## Matplot bar chart:
[![screenshot_1490977449.png](https://s19.postimg.org/h8bvufjg3/screenshot_1490977449.png)](https://postimg.org/image/8q2fq3cxb/)
