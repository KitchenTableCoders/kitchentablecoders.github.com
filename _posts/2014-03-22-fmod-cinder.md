---
layout: post
category: class
style: text
title: 3D Audio with Cinder and FMODEx
class_date: 2014-03-22 
upcoming: true
start: 2pm
end: 5pm
location: Brooklyn, NY
registration_url: http://3d-audio-cinder.eventbrite.com
fee_list: [["Students", "$60"],
           ["Freelancers", "$120"],
           ["Everyone Else", "$250"]]
published: true
instructor: Jeff Crouse
---


[FMODEx](http://www.fmod.org/) is a low level, high performance c++ audio API [used in many game engines](http://en.wikipedia.org/wiki/FMOD#Games_using_FMOD). It makes it possible to add full 3D audio to your c++ application and supports even the most exotic audio hardware and speaker configurations. It's especially great for installations because you can play dozens of sounds simultaneously and position them in space to create a rich, immersive experience.

[Cinder](http://libcinder.org/) (a library for professional-quality creative coding in C++) ships with support for FMODEx, but the API can be difficult to understand at first. In this workshop, we will look at this API and learn how to create a 3D audio application using Cinder.  We will cover:

- Setting up your Cinder application
- Initializing your audio system (stereo, 5.1, 7.1, global reverb)
- Loading audio files (in memory and streaming from disk)
- Playing sounds (looping and non)
- Adjusting sound properties (volume, position, balance)
- Adding built-in DSP effects (flange, pitch shift, echo)
- Moving sounds in 3D space 
- *possibly* demo of "raw mode", which allows you to manually address individual speakers

Participants should have some experience with Cinder (beginner to intermediate is fine) and should bring a laptop with Cinder installed and functioning (example apps should build and run), as well as some sample sound effects (loops, soundtrack, effects).