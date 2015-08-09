# aiu

*aiu* is a set of scripts created to make keeping track of your media easier.
It keeps a backlog of things you haven't watched yet and helps you pick something
to watch using dmenu.

## Installation
- Clone the repo somewhere
- Include it in your `$PATH`
- You *should* run `aiu conf` and set up a few things
- That's it!

## How to use
- Start by adding some files to your backlog using `aiu add <file>`
- If you have a whole directory of files you want to add (e.g. a whole season), you can use `aiu add dir` instead, which adds all files in the current directory
- Right now, *aiu* expects files to be named `[group] Title - 01.ext`, files named differently might not work well (or at all)
- Browse your backlog using `aiu open`
- Select something and enjoy! It gets removed from your backlog automatically after you finish watching
- Using *aiu* with something like [Flexget](http://flexget.com/) is highly encouraged - set it up to add things to your backlog automatically
