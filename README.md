# My Useful Scripts

By far the simplest time-saving tools I’ve found since working more in the OSX terminal are aliases and functions. they are simply shorthand commands that you can define to reference longer commands you find yourself commonly using. I shared git and general scripts that I use in my daily routine.

This repository idea came from deleting derived data folder each time xCode fails, so I consider making it public to make it simple for everyone just by typing ```cleandd``` in the terminal.

## Installation

### Using Git

* First you should clone the repository wherever you want. make sure where do you cloning it because you need it later.

```bash
git clone https://github.com/Salarsoleimani/Usefulscripts.git
```
* After cloning, you should edit your terminal profile ([check out this article if you want to know more](http://hacktux.com/bash/bashrc/bash_profile))
* Your .bash_profile is located at the root of your User folder.
```bash
open .bash_profile
```
* If you didn't have bash_profile, create one:
```bash
touch .bash_profile
```
* add these two line of code there
```bash
source "[Directory_Of_Cloned_Repository]/Components/UsefulScripts/.general-shortcuts.sh"  # General aliases and functions defined by salarSoleimani
source "[Directory_Of_Cloned_Repository]/UsefulScripts/.xcode-shortcuts.sh" # General aliases and functions defined by salarSoleimani
```
* Don't forget to change [Directory_Of_Cloned_Repository]

###  To update, `cd` into your local `Usefulscripts` repository and then:

```bash
git pull
```

### Add custom commands without creating a new fork
* Don't forget if you edited the files by ```git pull``` you can't pull. * 
* open the file:
```bash
open .xcode-shortcuts.sh
```
or
```bash
open .general-shortcuts.sh
```
* add your custom script.

## Feedback

Suggestions/improvements [welcome](https://github.com/Salarsoleimani/Usefulscripts/issues)!

## Author

| ["Follow @salarsoleimani Twitter"](http://twitter.com/salarsoleimani) |

## Thanks to…

* [Ash’s dotfiles](https://github.com/ashleynolan/dotfiles)
* anyone who [contributed a patch](https://github.com/salarsoleimani/Usefulscripts/contributors) or [made a helpful suggestion](https://github.com/salarsoleimani/Usefulscripts/issues)
