# redditcontentinator

This is a client side html/js monolithic script that will allow you to navigate Reddit by various sorting options. You can:
 - Sort by SFW/NSFW
 - Load posts in real-time
 - Pause the real-time loading
 - Select from popular subreddits (or all)
 - Input a subreddit manually
 - Reverse the sort order so new posts load in on top of old posts. Default is new posts load under default posts.
 - Sort by hot/new/rising/etc
  
Download by clicking "clone or download" and downloading the zip file, or click here: https://github.com/distortednet/redditcontentinator/archive/master.zip

This requires no server, and can run locally. Browser compatibility not guarenteed.

This script is useful for either finding content, or monitoring a subreddit. For example, you could monitor AskReddit for new threads by selecting AskReddit, selecting new for the sort by field, and then clicking "reverse sort order" so new posts load first. You can also monitor all of reddit, although there are certain scenarios where this seems to crash the browser.


Future features (hopefully):
 - audio notification on new posts with checkbox toggle
 - username/subreddit filter to help dedupe content by users that cross post, or to filter unwanted subreddits from /r/all
 - ability to load content based on if an image or embed exists or not, or post is self post.
 - unload very old posts as you scroll...to hopefully save browser memoriez
