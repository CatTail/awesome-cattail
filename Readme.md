# Awesome-CatTail

> **MY PERSONAL** applications and tips.

## OSX Application

[brew](http://brew.sh/)

> The missing package manager for OS X

[dash](https://kapeli.com/)

> Dash is an API Documentation Browser and Code Snippet Manager

[f.lux](https://justgetflux.com/)

> f.lux fixes this: it makes the color of your computer's display adapt to the time of day, warm at night and like sunlight during the day

[iTerm2](https://www.iterm2.com/)

> iTerm2 is a replacement for Terminal and the successor to iTerm. It works on Macs with OS X 10.8 or newer. iTerm2 brings the terminal into the modern age with features you never knew you always wanted.

[macpass](https://github.com/mstarke/MacPass)

> A native OS X KeePass client

[p4merge](https://www.perforce.com/product/components/perforce-visual-merge-and-diff-tools)

> Visual Merge and Diff Tools

[postman](https://www.getpostman.com/)

> Postman helps you develop APIs faster.

[quick look plugins](https://github.com/sindresorhus/quick-look-plugins)

> List of useful Quick Look plugins for developers

[Sequel Pro](http://sequelpro.com/)

> MySQL database management for Mac OS X

[sip](http://theolabrothers.com/)

> Drag and drop a color to and from any native application you are using

[ShiftIt](https://github.com/fikovnik/ShiftIt)

> Managing windows size and position in OSX

[typora](http://typora.io/)

> it combines syntax highlighting for markdown source and the live preview function
>
> --- http://abnerlee.github.io/typora/2015/03/11/why-typora/

## iOS Application

[Evernote](https://evernote.com/)

> Discover what a new kind of note can do for you.

[Minikeepass](https://minikeepass.github.io/)

> Secure password storage on your phone that's compatible with KeePass

[Overcast](https://overcast.fm/)

> A powerful yet simple podcast player for iPhone, iPad, and Apple Watch

[Pocket](https://getpocket.com/)

> Save, discover, and recommend the best stories on the Web

[Reeder](http://reederapp.com/)

> A news reader for Feedbin, Feedly, Feed Wrangler, FeedHQ, NewsBlur, The Old Reader, Inoreader, Minimal Reader, BazQux Reader, Fever, Readability and Instapaper

[Surge](http://surge.run/)

> Surge is a web developer tool and proxy utility for iOS 9

[Microsoft Outlook](https://itunes.apple.com/us/app/microsoft-outlook-email-calendar/id951937596?mt=8)

> email and calendar

## Terminal

[ag](ggreer/the_silver_searcher)

> A code-searching tool similar to ack, but faster. http://geoff.greer.fm/ag/

[autojump](https://github.com/wting/autojump)

> A cd command that learns - easily navigate directories from the command line [http://wiki.github.com/joelthelion/autojump/](http://wiki.github.com/joelthelion/autojump/)

[fpp](https://facebook.github.io/PathPicker/)

> | fpp
> Why Pipe when you can Pick?

[fzf](https://github.com/junegunn/fzf)

> A command-line fuzzy finder

[hr](https://github.com/LuRsT/hr)

> <hr /> for your terminal
> Tired of not finding things in your terminal because there's a lot of logs and garbage? Tired of destroying the Enter key by creating a "void zone" in your terminal so that you can see the error that you're trying to debug?

[jq](https://github.com/stedolan/jq)

> Command-line JSON processor

[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

> A delightful community-driven framework for managing your zsh configuration. Includes 200+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, php, python, etc), over 140 themes to spice up your morning, and an auto-update tool so that makes it easy to keep up with the latest updates from the community. [http://ohmyz.sh/](http://ohmyz.sh/)

[osquery](https://osquery.io/)

> osquery gives you the ability to query and log things like running processes, logged in users, password changes, usb devices, firewall exceptions, listening ports, and more.
> You can perform ad-hoc queries or schedule them.

    osquery> SELECT uid, name FROM listening_ports l, processes p WHERE l.pid=p.pid;

pv

> monitor the progress of data through a pipe

tee

> pipe fitting

xxd

> make a hexdump or do the reverse

## Service

[asciinema](https://asciinema.org/)

> Forget screen recording apps and blurry video. Enjoy a lightweight, purely text-based approach to terminal recording.

[CloudFlare](https://www.cloudflare.com/)

> Provides a content delivery network and distributed domain name server services, sitting between the visitor and the CloudFlare user's hosting provider, acting as a reverse proxy for websites

[DirtyMarkup](https://www.dirtymarkup.com/)

> Paste in your dirty code and hit clean

[httpbin](http://httpbin.org/)

> HTTP Request & Response Service

[Tonic](https://tonicdev.com/)

> Tonic is node prototyping.

[Wayback Machine](https://archive.org/web/)

> Internet Archive

[Web Annotator](http://genius.com/web-annotator)

> Genius lets you add line-by-line annotations to any page on the Internet

## Game

[BombSquad](http://www.froemling.net/apps/bombsquad)

> 8 Player Party Game Madness!

[Don't Strave](http://www.kleientertainment.com/games/dont-starve)

> *Don't Starve* is an uncompromising wilderness survival game full of science and magic.

[The Last Of Us](http://www.thelastofus.playstation.com/index.html)

> *The Last of Us* is genre-defining experience blending survival and action elements to tell a character driven story

[The Witcher 3](http://thewitcher.com/en/witcher3)

> The game is based on the novel series of the same name by Polish author Andrzej Sapkowski. *The Witcher* takes place in a medieval fantasyworld and follows the story of Geralt, one of a few remaining Witchers – traveling monster hunters for hire who have supernatural powers. The game's system of "moral choices" as part of the storyline was noted for its time-delayed consequences and lack of black-and-white morality. - Wikipedia

## Tips

OSX Help menu shortcut

> `Cmd+Shift+/`

iTerm2 cmd-click to open file in vim in terminal

> Preferences -> Profiles -> Advanced
> Under "Semantic History", choose "Run coprocess..". In the text field, put:
> echo vim \1 +\2
