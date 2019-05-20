# TweetWorld

Display in real time maps of Tweets around the world based on topics

See https://medium.com/@tomsoft/infography-iphone-vs-android-shows-north-vs-south-split-and-in-real-time-91e69c16b296

![Sample](/pics/sample.png)

There are numerous parameters that can be added in the URL

* __word__ : The list of words totrack, as an array. Example,   words=["apple","orange","cheese"]
* __source__: what field of the twitter json to be checked. By default, it's the "source" field (text of the tweet) but could be also the language (see samples below)
* __ray__: The number of rays emitted when a new point is created
* __size__: The size of the ray
* __effect__: The effect type, line (default), point

Example of url parameter:
`?words=["apple","pie"]&ray=5&source="lang"`
![Other Sample](/pics/other_sample.png)

