# Welcome to the Woofer Music Player Project

A flexible, efficient and universal music player for GNU+Linux that gives you
the tools to automate the playback of your music collection.

## About

Project Woofer is a free and open-source software project that consists of
multiple repositories, that together create a flexible and efficient music
player, aimed to give you the tools to automate the playback of your music
collection.  Using a configurable algorithm in combination with gathering
statistics, the software can, over time, choose songs for you without any manual
input.  The software is built to run on a variety of environments and to respect
the freedom of the end-user.  Because it is so fundamentally different compared
to other music players, it certainly isn't be suitable for everyone.

## Key-features

* Highly-configurable song choosing algorithm
* Swappable front-ends with the same core functionality
* Respects end-user freedom
* Easily modify user configuration files and share them across devices
* Efficient and fast: runs well on low-end devices

## Why should I use it?

The way this software works is a bit different from the traditional music
players.  For a start, you cannot really create playlists in this program.
Neither can you play in an ordered list; the application is in a permanent
shuffle mode.  The original idea is that you create a list with all songs you
have locally and that you want the software to know about.  Initially, random
songs are chosen and based on your behavior of skipping songs you don't like and
letting songs you like play until the end, the software is going to adapt to
your preference by using collected statistics.  At some point, the statistics
are useful enough that the built-in algorithm chooses songs for you without any
manual input.  You can help the algorithm with this by setting song ratings
on-the-go to further finetune your music style.

In the software's settings, you can tweak how the algorithm choose your songs.
You can, for example, require songs to have a score above 75 and a rating above
8 when you need some good productivity music.  No need to create a new playlist
and add songs; just configure how you want it and press play.

## Why shouldn't I use it?

If you like the simplicity of creating a playlist, dumping songs into it and
playing it from top to bottom, then this software is probably not for you.
Likewise, if you depend a lot on online streaming services and their algorithms
to suggest and play music for you, then this software is also not for you.

However, if you have a local collection full of awesome music but also some
*meh* songs and want some software to choose something to play during the
inspiration-lacking times, this software has the solution for you!

And for the people that don't care what their music player does but want
something that just works on any platform, give it a try!

## Where to find what

The software itself consists of two parts: the application back-end (built as a
software library) and a front-end.  The back-end is what does most of the work
of the application and the front-end supplies an interface with which the user
interacts with the application.  Different front-ends focus on different aspects
and the choice of what front-end to use is up to you, though the official GTK3
one is recommended.

## Getting started

Depending a little on what front-end you want to use, the best option is to
install the software from your distributions software manager.  If it is not
available or you want to customize the setup, you can compile it yourself.

Generally, follow the instructions of the front-end project you want to use on
how to set it up, or start by compiling the application back-end (the libwoofer
repository) first.

## Development status

The application back-end is in the alpha phase of the software release cycle,
meaning it is not stable enough and can still contain critical bugs.  However,
it can be used for testing purposes, both functional testing and testing of the
user experience.  The latter one may involve using it as a daily-driver, but
with the knowledge that some serious issues may occur.

## Design principles

The software is designed with these principles in mind:
* User freedom: The user should have the freedom to use the software however
  they like.
* Flexibility: The software should run in and adapt to a variety of environments
  and should be straight-forward to set up.
* Efficient and fast: The software should be able to run on minimal resources
  and feel fast for the end-user.

## Copyright

All source code of Project Woofer is "free software" and distribute in the hope
that it will be useful.  It is, except when stated differently, released under
the terms and conditions of the GNU General Public License version 3 or later,
as published by the Free Software Foundation.

All documentation of Project Woofer is "free documentation" and, except when
stated differently, released under the terms and conditions of the GNU Free
Documentation License version 1.3 or later, as published by the Free Software
Foundation.

