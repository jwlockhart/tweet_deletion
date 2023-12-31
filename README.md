# tweet_deletion
A quick and dirty hack approach to deleting old tweets. It's not perfect, and it's shared with no warranties and probably no maintenence. Use at your own risk. It got the job done for me; maybe it will be helpful to you.

1. [Download your Twitter archive](https://twitter.com/settings/download_your_data), which contains all your tweets.
1. Locate the file(s) with your tweets. Most will be in `data/tweets.js`. Some may be in `data/twitter-circle-tweets.js`.
1. Use the `tweet_sorter` code to select out the tweets you want to delete. You can skip this step if you want to delete everything. Note that there are settings to adjust what gets sorted into the keep and delete buckets. 
1. Use the `tweet_deleter` code to delete them. Note that there are a few settings to adjust, and you need to log into your twitter in the middle of the script.

Notes:
1. This code won't work for everyone, but if you have basic python experience, this should work for you.
1. The deletion script is slow. It takes 4-8 seconds per tweet. The good thing about automation is you can just walk away from it. One could optimize it to go faster, but it's a one-time cost and I need to get back to real work.
1. You are likely to hit your tweets per day limit when you run this. If so, note where you left off and pick up there tomorrow.