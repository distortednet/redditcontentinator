# redditcontentinator

This is a client side html/js monolithic script that will allow you to navigate Reddit by various sorting options. You can:
 - Sort by SFW/NSFW
 - Load posts in real-time
 - Pause the real-time loading
 - Select from popular subreddits (or all)
 - Reverse the sort order so new posts load in on top of old posts. Default is new posts load under default posts.
 - Sort by hot/new/rising/etc
  
Should be as easy as downloading the .html file to your computer and running. This requires no server, and can run locally. Browser compatibility not guarenteed.

This script is useful for either finding content, or monitoring a subreddit. For example, you could monitor AskReddit for new threads by selecting AskReddit, selecting new for the sort by field, and then clicking "reverse sort order" so new posts load first. You can also monitor all of reddit, although there are certain scenarios where this seems to crash the browser.


This script works mostly by url parameters. This is the easiest way to do things. When clicking buttons, you'll be redirected to the url, instead of updating the state of the script in real time.

Eventually, audio notifications on new posts may be added as well as a username or subreddit filter, to prevent scenarios where you may load in content from users or bots that cross posts to multiple subreddits which will help de-dupe content.

Future features:
 - audio notification on new posts with checkbox toggle
 - username/subreddit filter to help dedupe content by users that cross post, or to filter unwanted subreddits from /r/all
 - allow users to select the interval time for live loading content
 - ability to load content based on if an image or embed exists or not, or post is self post.
 - unload very old posts as you scroll...to hopefully save browser memoriez
