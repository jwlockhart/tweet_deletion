# tweet_deletion
A quick and dirty hack approach to deleting old tweets. It's not perfect, and it's shared with no warranties and probably no maintenence. Use at your own risk. It got the job done for me; maybe it will be helpful to you.

1. [Download your Twitter archive](https://twitter.com/settings/download_your_data), which contains all your tweets.
1. Locate the file(s) with your tweets. Most will be in `data/tweets.js`. Some may be in `data/twitter-circle-tweets.js`.
1. Use the `tweet_sorter` code to select out the tweets you want to delete.
1. Use the `tweet_deleter` code to delete them. If you want to delete all tweets, you can skip the sorting step.

N.B. you'll need `selenium` and a browser driver set up. There are many guides for this online.
