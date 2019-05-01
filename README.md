# redditcontentinator

This is a client side html/js monolithic script that will allow you to navigate Reddit by various sorting options. You can:
 - Sort by SFW/NSFW
 - Load posts in real-time
 - Pause the real-time loading
 - Select from popular subreddits (or all)
 - Input a subreddit manually
 - Reverse the sort order so new posts load in on top of old posts. Default is new posts load under default posts.
 - Sort by hot/new/rising/etc
 - search user posts and comments
 - search for post title or body+title
 - audio notifications on new posts
 - filter by OC
 
Download by clicking "clone or download" and downloading the zip file, or click here: https://github.com/distortednet/redditcontentinator/archive/master.zip

This requires no server, and can run locally. Browser compatibility not guarenteed.

This script is useful for either finding content, or monitoring a subreddit. For example, you could monitor AskReddit for new threads by selecting AskReddit, selecting new for the sort by field, and then clicking "reverse sort order" so new posts load first. You can also monitor all of reddit, although there are certain scenarios where this seems to crash the browser.


Future features (hopefully):
 - filter by self
 
 Not possibru features:
 - filter by region - does not appear to be exposed in the api.
 - username/subreddit filter to help dedupe content not possible in the context of project (local storage/session cannot be used on local files)

bugs and misc todo/notes:
- audio notifications suddenly dont work???? wtf??? (seriously, WTF)
