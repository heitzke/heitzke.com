---
title: Oh-My-ZSH for designers (too)
date: 2012-11-09
tags: bash, z shell, 
---
Designers, don't fear the command line. The shell doesn't have to be a scary & ugly thing to use, it can *actually* be somewhat enjoyable (at times). It's really not that bad, plus it gains you all kinds of street cred (or something). I really only started learning/using it because all the guys at Isotope11 made fun of me until I did. Now I can act pretentious and tell people to learn it too. This all really isn't about learning it any way, it's about making it better to use.

The default shell that ships with Linux and OSX is Bash. It looks a little something like this -
![Alt text](/images/zsh/bash.png)
Admittedly, my Bash profile is super plain and pretty difficult to use. I messed around with editing my .bashrc, adding aliases etc. and still just ended up disappointed. One day after bitching about my frequent git typos, I heard about something called 'Oh-my-zsh' in a response to my rants. Again, some sort of great secret had eluded me. 

### Oh-my-ZSH
So if Bash is the shell that ships on Unix computers, what the hell is Z Shell? Basically it's an extended Bourne shell that borrows features from other shells (bash, ksh, tcsh). 

### Installing 
[Github Instructions](https://github.com/robbyrussell/oh-my-zsh)

I installed via curl:
<pre><code>curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh</code></pre>

Set ZSH as your default shell
<pre><code>chsh -s /bin/zsh</code></pre>

Then you should be seeing something like this guy:
![Alt text](/images/zsh/zsh1.png)
Not super impressive yet, I know. It gets better though with the next step.

Vim ~/.zshrc and scroll down to plugins & theme
![Alt text](/images/zsh/zsh2.png)

This is really the cool part, all of these plugins make life really easy. For example, here is a list of all the git aliases the git plugin adds: 
[Git Plugin Cheatsheet](http://jasonm23.github.com/oh-my-git-aliases.html)

There are also tons of themes that come packaged with this. 
[List of Themes](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)

Personally, I'm using gnzh and it looks like this: 
![Alt text](/images/zsh/zsh3.png)
That's a hell of a lot better than what I was rocking before, right? Shows me current working branch, gemset and also directory path. Also note me using the alias for 'git status' which is 'gst'. I also just loooove having an entire extra line to type on below. 

Luckily, there IS more to it than just pretty colors. 
- When you tab tab you get a list of possible completions that you can navigate with arrows
- ZSH shares command history among sessions
- Spell checking (big win for me)
- Little indicator shows when there are changes that haven't been committed 

There's a lot more to it than this, but that's about the extent of my knowledge. Hell, i'm just a designer. 