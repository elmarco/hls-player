# http live streaming player #

A simple HTTP Live Streaming player written in Python, using GStreamer.

Installation:

> sudo python setup.py install

Play the sample clip from Apple:

> hls-player http://devimages.apple.com/iphone/samples/bipbop/bipbopall.m3u8

or RTVE:

> hls-player http://iphonelive.rtve.es/stream1.m3u8 -r http://m.rtve.es/live/