Tweetstream
===========

A shell script to extract tweets from the live tweet stream for data mining.

Tweets can be captured from a set of specific users or by matching a set of keywords.

Run it like this:

    $ tweetstream -c config.yaml

See `sample-conf.yaml` for a config template.

Data is saved in a CSV file (with quoted fields) in the configured location.

Tweetstream captures tweets from the live stream only, it does not capture historic tweets.

There's more detailed info in `sample-conf.yaml`.

Installing
----------

1. Save `tweetstream` in `~/bin` or somewhere in your path.
2. Make it executable

        $ chmod a+x ~/bin/tweetstream

3. Install dependencies

        $ gem install tweetstream

4. Create a configuration file
5. Run it

        $ tweetstream -c my-conf.yaml

You will need a recent verison of Ruby installed.
If you don't have this already, [RVM](https://rvm.io/rvm/install/) is probably the easiest way to go.
