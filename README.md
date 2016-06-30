# aiu

*aiu* is a shell script created to make keeping track of your media easier.
It keeps a backlog of things you haven't watched yet and helps you pick something
to watch using dmenu.

## Installation

### Manual
- Clone the repo somewhere
- Include it in your `$PATH`
- You *should* run `aiu conf` and set up a few things
- That's it!

### Arch Linux
*aiu* can be installed from *AUR* using the **aiu-git** package.

## How to use
- Start by adding some files to your backlog using `aiu add <file>`
- If you have a whole directory of files you want to add (e.g. a whole season), you can use `aiu add dir` instead, which adds all files in the current directory
- Video files are expected to be named `.* - 01.ext`
- Comic files are expected to be named `.* #01.ext`
- Browse your backlog using `aiu open`
- Select something and enjoy! It gets removed from your backlog automatically after you finish watching/reading
- Using *aiu* with something like [Flexget](http://flexget.com/) is highly encouraged - set it up to add things to your backlog automatically
