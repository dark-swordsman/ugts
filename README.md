# The Ultimate Guide to Video Production

This GitHub repository is intended to serve as an aggregate for all sorts of data across the internet and to help anyone at any level understand what they need to know for video streaming, recording, production, editing, etc.

## Preface

I've spent a lot of time doing my own little productions with OBS to Twitch or cameras and editing software for YouTube, and each and every time I tried doing it, I always found something that got in my way preventing me from reaching my goal to make a high quality production, whether it be images, overlays, encoding settings, cameras, etc.

My goal with this repo is to take all the information I know and throw it in one place with as many sources as possible, while also letting people check my work, contribute, and to overall provide a very detailed and organized guide for anyone to come and read. 

After getting so fed up trying to help people on [r/OBS](https://www.reddit.com/r/obs/) that don't really know better, this is what I started.

By the way, this whole article will be mostly focused around the idea of gamers that are streaming/recording, and not so much people doing large, live productions or vlogs/documentaries, etc. It's really to drive home a good stream/recording quality and to get extremely nerdy about encoding, the do's and dont's, etc.

***

# Table of Contents

- [The Ultimate Guide to Video Production](#the-ultimate-guide-to-video-production)
  - [Preface](#preface)
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
  - [What is Video Production?](#what-is-video-production)
  - [Recording or Streaming?](#recording-or-streaming)
- [Getting Started with Streaming](#getting-started-with-streaming)
- [Getting Started with Recording](#getting-started-with-recording)

***

# Introduction

## What is Video Production?

[CWM Studios](http://www.cwmstudios.com/98/the-three-phases-of-video-production.html) has a pretty good definition of Video Production: "There are three main processes to putting a video together: pre-production, filming and editing."

However, for all intents and purposes, video production in this article can mean literally anything that has to do with video. Whether it be OBS Studio, video encoding settings, editing software, how to uses these softwares, how Psycho Visual Tuning works, what Node.js and how to use it for overlays, what the heck is a codec?!, what a processors is, what NDI and SSSE3 instructions are, and so on.

This article, at least for the time being, will be mostly focused on OBS Studio, encoding settings, technologies like NDI and new NVENC, how to use basic editing software, why it's important to understand the basics of computer hardware like CPUs (processors), etc. It will also be focused around the idea of producing video in OBS Studio, as well as doing recordings for YouTube and streaming for Twitch/YouTube.

## Recording or Streaming?

There's a good chance if you're reading this article, that you're doing one or the other. Thankfully, the basic understanding required for each of these is fairly similar, however, the workflow will be quite a bit different. 

For Streaming, it's all about getting everything ready beforehand and making things easy so, while you're live, you don't have to do much fiddling and stuff just works. It about getting transitions, overlays, and video feeds smooth and well timed, finding ways to reduce your performance requirements, as well as making sure your audio is on key. You'll be switching scenes a lot and interacting with chat, or if you're not interacting with chat, there's a good chance you have a full production and are casting a torunament or something.

For Recording, there's a lot of room for error, except after you're done capturing, you don't just end, you now have to edit and post-process, so there's a whole 'nother workflow, set of programs, and mindset compared to live production. You'll likely be recording gameplay in something like OBS Studio, or if it's a short film/vilog/etc. you'll have your camera to record. From there, you'll injest all your data into a folder or location for a project, open up your editing software (like Sony Vegas, Premiere, etc.) and get started editing. Once you're satisfied, you can export it with a collection of settings for resoltion, bitrate, codec, etc. and you can upload it/sent it where you need.
