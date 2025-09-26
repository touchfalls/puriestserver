# puriest server

## This is an optimized version of the server on the Purpur nucleus, but minecraft remains the same functional and without removing AI in monsters and residents
### The repository uses the purpur nucleus version 1.21.8, version of [Build 2497](https://api.purpurmc.org/v2/purpur/1.21.8/2497/download).
### All optimization lines are signed, I did optimization as I would do it on my server so I advise you to look at the changed files and draw a conclusion for yourself
### [The repository is based on optimization from Youhavetroble](https://github.com/YouHaveTrouble/minecraft-optimization)

# What's lagging? - measuring performance

## mspt

Paper offers a ``/mspt`` command that will tell you how much time the server took to calculate recent ticks. If the first and second value you see are lower than 50, then congratulations! Your server is not lagging! If the third value is over 50 then it means there was at least 1 tick that took longer. That's completely normal and happens from time to time, so don't panic.
# Spark
[Spark](https://spark.lucko.me/) is a plugin that allows you to profile your server's CPU and memory usage. You can read on how to use it on its [wiki](https://spark.lucko.me/docs). There's also a guide on how to find the cause of lag spikes here.
