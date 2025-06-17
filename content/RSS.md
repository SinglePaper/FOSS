---
title: "RSS Feeds: Better content delivery"
---
![[Pasted image 20250617230701.png|50]]
RSS (Really Simple Syndication) feeds are a game-changer for staying informed and organized online. RSS lets you subscribe to updates from websites, blogs, news sources, and even social media platforms. Many sites offer RSS feeds, usually marked with an orange icon. By using RSS, you take control of your content consumption, getting updates directly without relying on algorithms. This means you won't miss important content and can reduce your dependence on social media and search engines. With an RSS reader, you can have all your favorite content in one place, making it easy to stay updated on what matters to you. Whether you're into news, tech, or specific hobbies, RSS feeds keep you in the loop efficiently.

RSS feeds look intimidating when you see them, which is why you should use an RSS reader when you are actually using them. I use [Feedly](https://feedly.com/), but feel free to look around on the internet to see if there's one that fits. This specific RSS reader is ironically not open source, but has some nice features and allows for cross-device syncing without having to rely on self-hosting. If you do not need your RSS reader to sync between devices there is a plethora of open source options available online for both phone and desktop.

### What can I link?
And now the exciting part! Below I will list some of the services and platforms I have linked to my feed reader, but RSS feeds can be found all over the place. Usually they are located at www.example.com/feed or www.example.com/rss, but they can more easily be extracted by using some [extensions](https://addons.mozilla.org/en-US/firefox/addon/rss-launchpad-find-feeds-easy/) or RSS reader [functionality](https://feedly.com/i/discover). 

#### YouTube
For YouTube, there are a number of feeds to follow with some filters too! 
- Follow Channels: ```https://www.youtube.com/feeds/videos.xml?channel_id=EXAMPLE```
	- A channel ID looks something like ```UCGaVdbSav8xWuFWTadK6loA``` and can be extracted automatically using the extensions listed above.
	- Don't want to include Shorts in your feed? Only care about livestreams? You easily can filter it! [Here's some information on it](https://blog.amen6.com/blog/2025/01/no-shorts-please-hidden-youtube-rss-feed-urls/#no-shorts). It's fully undocumented, but supported by Google! That's how you know it's good.
- Follow Playlists: ```https://www.youtube.com/feeds/videos.xml?playlist_id=EXAMPLE```
	- The feed gets updated each time a video gets added to a playlist without receiving updates about other uploads from the channel!

#### Dropout.TV
Personally, I am a big Dropout.tv fan, and the website has no built-in RSS support. Luckily, since RSS is so simple, I made my own, and it is available for anyone to use. You can follow any show's RSS feed listed [here](https://singlepaper.github.io/dropout-rss/). There are hourly updates and new shows are added automatically. 
- Note: when you first add a show, the timestamps are incorrect. New episodes that air, are correct, however.

#### Nebula
Another creator-owned platform with great content! Nebula has built-in support for RSS that can be detected by extensions and RSS readers.
- Follow Channels: https://rss.nebula.app/video/channels/jetlag.rss
	- You may replace 'jetlag' here with any channel. The channel IDs are in the URL bar when you navigate to a channel on the website.

#### Comics
- The Oatmeal: http://theoatmeal.com/feed/rss
- xkcd: http://xkcd.com/rss.xml
- Many, many, many more

#### Other
I have now covered my main usecases for RSS, but there are so. many. more. If you read fan fiction, read comics, newsletters, news stories, literally anything that you could even remotely interpret as a feed: it probably has RSS, which means you can control how you receive it. Give it a try!