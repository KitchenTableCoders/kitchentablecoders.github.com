---
layout: post
category: class
style: text
title: Server-Side Video Editing
class_date: 2013-07-27
upcoming: false
start: 1pm
end: 5pm
location: Brooklyn, NY
registration_url: http://www.eventbrite.com/event/6678436383
fee_list: [["Students", "$60"],
           ["Freelancers", "$120"],
           ["Corporate", "$250"]]
published: true
instructor: Jeff Crouse
---

While there have been some great projects that use browser-based
real-time graphics teqhniques combined with video sharing APIs to
create interactive, video-driven experiences, the results of these
types of projects are usually fleeting. What if you want to allow
users to create a custom, shareable, downloadable video artifact that
draws from the huge world of source audio and video out there on the
web?  In this workshop, we will explore a suite of tools that can be
used to create a server-side video editing platform that can churn out
customized video files based on logic that we provide. I like to call
this process "procedural video editing", and while it's nowhere near
as sophisticated as a tool like FinalCut, it is very powerful
nonetheless.

###Agenda

1. First, we will look at a program called
   [youtube-dl](https://github.com/rg3/youtube-dl) that will allow us
   to gather video content from sites like YouTube, Vimeo, and many
   more.
1. Once we have acquired our source content, we will need to massage
   the format of the videos. To do this, we will use the legendary
   command line video workhorse: [ffmpeg](http://www.ffmpeg.org/)
1. We will use [MLT framework](http://www.mltframework.org/) ("melt")
   to edit the videos together
1. To automate the process, we will use Python (specifically,
   [the Subprocess module](http://docs.python.org/2/library/subprocess.html)). If
   you wish to use another scripting language, that's fine - the
   language itself is not important to the main techniques. However, I
   will be providing some sample code in Python.
1. We will talk generally about how to install on a server so that it
   is accessable on the web

There will be an optional (free) work session on the 28th (the next
day) where participants may come back to the studio to work on their
projects and get help from Jeff.

###Techniques/Sample Code

* Get video info (ffprobe)
* Crossfading (mlt)
* Video overlays (ffmpeg)
* Watermarking (ffmpeg)
* Find video based on keyword (Youtube)
* Find news video (Archive.org)
* Generating video clips from Google Streetview ("<a
  href="http://hyperlapse.tllabs.io/">Hyperlapse</a>")
* Using <a href="http://developer.echonest.com/docs/v4/">EchoNest
  API</a> to edit a video to the beat of a song
* Generate title sequence using <a
  href="http://www.pythonware.com/products/pil/">Python Imaging
  Library</a>
* Incorporating <a
  href="https://github.com/grampajoe/Autodatamosh">datamoshing</a>


###Prerequisites

1. A laptop (preferably Mac or Linux)
1. Some experience with Python or another scripting language
1. Please install ffmpeg, mlt, sox ImageMagick, and Python (Python
   comes standard on a Mac) on your laptop so that we don't waste time
   setting up at the workshop. Depending on your platform, this can be
   a harrowing experience, so if you have trouble, please let me
   know. On a mac, I recommend using
   [Macports](http://www.macports.org/)+. On Linux, any decent package
   manager should have these packages. On Windows, you're on your own.

+ If you are on a Mac and have <a
href="http://www.macports.org/">MacPorts</a> installed, issue the
following commands in the Terminal:

	sudo port install youtube-dl sudo port install ffmpeg +gpl +lame
	+x264 +xvid +universal sudo port install mlt +universal sudo port
	install sox +universal sudo port install ImageMagick +universal
