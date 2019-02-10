# aiu

*aiu* is a shell script created to make keeping track of your media easier.
It keeps a backlog of things you haven't watched yet and helps you pick something to watch using dmenu.

## Installation

### Dependencies
This project uses [modernish](https://github.com/modernish/modernish).

### Setting up
*aiu* tries to guess sane defaults—you can view the current settings with `aiu show`.
If you would like to make some changes, create a config file at `$XDG_CONFIG_HOME/aiu/config` and overwrite the desired settings.
You can also issue `aiu write` to write the current settings to the file (in this case, create a config file with the autodetected defaults) and edit it with `aiu edit`.

## How to use
- Start by adding some files to your backlog using `aiu add <file>`
- If you have a whole directory of files you want to add (e.g. a whole season), you can use `aiu dir` instead, which adds all files in the current directory
- Video files are expected to be named `.* - 01 [.*].ext`
- Comic files are expected to be named `.* #01 [.*].ext`
- Partial files with `.part` suffix are supported for adding
- Browse your backlog using `aiu open`
- Select something and enjoy! It gets removed from your backlog automatically after you finish watching/reading>
- Using *aiu* with something like [Flexget](http://flexget.com/) is highly encouraged - set it up to add things to your backlog automatically
