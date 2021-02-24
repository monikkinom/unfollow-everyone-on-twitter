# Unfollow everyone on twitter from your browser! NO API access required
Unfollow every user you follow and declutter your feed.

#### Warning: This may take a while to run in your browser depending on how many users you follow. Unfollow speed estimate is 30 users / minute. 

Steps:
1. Open the browser console. [How to open DevTools on chrome](https://developers.google.com/web/tools/chrome-devtools/open)
2. Head over to your following page on twitter. It should be of the form, https://twitter.com/username/following
3. Copy the contents of [unfollow.js](https://github.com/monikkinom/unfollow-everyone-on-twitter/blob/main/unfollow.js) into the console and hit enter. 
4. Relax as every one of your follower is unfollowed.

## What does the script do?

A. It simply automates what you would have done if you didn't have the script. For each user in the list, it clicks to unfollow. A modal shows up where the confirm is clicked. And this is repeated till we have no more users and need to scroll. We automatically scroll at that point, and continue the unfollow process till there are no more users.
