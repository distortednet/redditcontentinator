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
 - filter by OC
 
 ----
 
Download by clicking "clone or download" and downloading the zip file, or click here: https://github.com/distortednet/redditcontentinator/archive/master.zip

This requires no server, and can run locally. Browser compatibility not guarenteed. This script is useful for either finding content, or monitoring a subreddit. For example, you could monitor AskReddit for new threads by selecting AskReddit, selecting new for the sort by field, and then clicking "ascending/descending sort order" so new posts load first.

----


Future features (hopefully):
 - update title bar with new posts
 
----

 Not possibru/no reason to add features:
 - filter by self - just does not seem worth adding.
 - filter by region - does not appear to be exposed in the api.
 - username/subreddit filter to help dedupe content not possible in the context of project (local storage/session cannot be used on local files)
 - audio notifications are inconsistent with local html files.
 
----

bugs and misc todo/notes:
- audio notifs now work somewhat, but can vary based on browser. Chromium on windows for example does not play audio at first but then plays after some time. chromium and linux based browsers may yield different or no result
