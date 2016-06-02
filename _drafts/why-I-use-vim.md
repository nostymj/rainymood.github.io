---
layout: post
title:  "Why do I use vim?"
date:   2016-05-29 00:00:00 +0200
categories: jekyll update
---

## The loyal Vim user ##

If you boot up Vim without knowing how to quit you're in for a surprise

<script type="text/javascript" src="https://asciinema.org/a/ekyzyuztuisbxb05779ryuxsc.js" id="asciicast-ekyzyuztuisbxb05779ryuxsc" async></script>

Hence the running gag

![image](http://i.imgur.com/8NFIwoC.png)

But how do you actually quit? The way to quit Vim (without saving) is `<Esc>:q!`

## What is Vim? ## 

Before I tell you why I use Vim, let me tell you what Vim actually is. Simply
put, at it's core, Vim is a text editor. Just like notepad, notepad++, and 
Sublime text. If we go up a level of abstraction Vim
is like a language and there's also the Vim philosophy. But those are things for
later I guess. 

_Vim is a text editor._

## Why do I use Vim? ##

Basically it boils down to these reasons:

1. It's kind of hard to _not_ use Vim anymore

2. Vim makes my code writing (text editing) so much more efficient

3. Once you get the hang of it, using Vim is pretty fun

4. Once you *really* get the hang of it, it all just suddenly clicks and it
   makes so much sense

## Reasons not to use Vim ##

Of course, there are a lot of reasons not to use Vim:

1. Vim has a steep learning curve

2. Vim requires a lot of customization/tinkering

3. You will miss Vim bindings on any other text editor

## Modes ##

Before explaining the pros and cons I listed above I first have to tell you
something about so called "modes". What makes Vim special is that it's a "modal"
text editor. Modal in this context simply means that Vim support multiple modes.
The two modes you will most frequently be in are `normal` mode and `insert`
mode. This is what frequently freaks out beginners because you start Vim in
`normal` mode, to enter insert mode you simply press `i`. After pressing `i` you
can type just like your regular text editor. 

I'm a huge fan of the mantra: "Show, don't tell". In the following animation I
fire up Vim with `$ vim`. We enter Vim in normal mode which might be quite
confusing to someone who is new to Vim.
Typing `i` to enter insert mode and we can use Vim like a regular
editor. Press `<Esc>` to exit insert mode and enter normal mode once again. To
exit Vim mash `<Esc>` a couple of time so make sure you're in `normal` mode and
then type `:q!` which means force quit (i.e. quit without saving current file). 

[comment]: # (Showing insert and normal mode)
<script type="text/javascript" src="https://asciinema.org/a/eby9q6k3kouch1vkq7381jspn.js" id="asciicast-eby9q6k3kouch1vkq7381jspn" async></script>

[comment]: # (Moving around in the file with hjkl)
<script type="text/javascript" src="https://asciinema.org/a/aw6naoprbqlmpwm32wwwnvxz6.js" id="asciicast-aw6naoprbqlmpwm32wwwnvxz6" async></script>


<!---
## My main pros and cons in a quick list ##

Reasons not to use Vim:
    * Learning curve
    * Requires quite some customization (could also be a pro) 
    * You will miss Vim bindings on all other editors 

Reasons to use Vim:
    * It makes text editting really really fast. 
    * IT makes text editting fun (or at least, less cumbersome). 
    * You can learn new stuff about Vim every day, learning new things is awesome. 

## Pros ##

### Learning curve ###

### Customization ###

Vim requires some customization but is usable from the get-go. This is what Vim
looks like without any configuration file (~/.vimrc file). A link to my .vimrc
can be found here and if you see any improvements or have some comments or
questions feel free to reach out to me! Thankfully, there is a huge community of
Vimmers out there and there are lots of plugins which will possibly satisfy 99%
of your needs. I have to say that there are some awesome plugin-managers (Vundle
and Pathogen mainly) which require some credit as well making it really (like
**really**) easy to manage your Vim plugins. 

I count the customization as a con but this is not really the case if you enjoy
tinking with stuff (like I do).  I personally used badwolf.colors for a year or
so

image

but now have switched to solarized-dark, which is really nice as well

image



### You will miss Vim bindinsg ###

## Cons ##

### Speed ###

### Fun ###

### Learning new stuff every day ### 




### Learning new stuff every day ###

For this blog post I had this list 

    Reasons to use Vim:
        * It makes text editting really really fast. 
        * IT makes text editting fun (or at least, less cumbersome). 
        * You can learn new stuff about Vim every day, learning new things is awesome. 

and I was wondering if there would be any way to quickly append "##" to each
line instead of simply doing it three times. I found this link ***link*** which
showed me that it could be done like this 

    :'<,'>norm A##



Reasons not to use Vim:

(1) Vim has a ridiculuous learning curve: 

<image>

Although the learning curve is quite bad early on I personally promise you
that it gets better, and it's totally worth it. Programmers and actuaries and
mathematicians are all quite known with the concept of delayed gratification,
right? Instead of eating the cookie now, you wait an hour and you get 2
cookies, sweeet! Vim is kind of like this. 

When you are first learning Vim, it WILL suck. 

You will feel really stupid. How do I move around a file? Oh shit what did I
do? How do I save? How do I exit? I highly recommend you to stick with it, and
more importantly don't go back to the mouse or the arrow keys. Repeat after
me, "arrow keys are evil." 

It will be difficult in the beginning, all I can say is: stick with it and it
WILL become better over time. 

(2) Vim requires a lot of customization

If you love tinkering with configurations this probably won't bother
you. MacVim is quite the package for Macs and I personally use this. I will
upload my personal .vimrc (Vim's config file) here: <link>

This is what Vim looks like from the terminal without any configuration

<image>

This is what it looks like with a nice coloursheme and font 

<image>

(3) You WILL miss Vim bindings on other machines

When you are used to Vim bindings and they are ingrained in your muscle
memory. It becomes really annoying when you have to type on someone else's
machine and suddenly out of habit you mash "kjkjkjkj" (kj is often remapped to
Escape, which puts out of Insert mode and into Normal mode again). Soon you
will be using Vim bindings for Firefox (Vimperator) or Chrome (Vimium) and
it's all downhill from there. 

Obviously there are more reasons not to use Vim, but let me argue that Vim is
really awesome.

Reasons why Vim is awesome: 

Vim makes editting text and source code fun again. 

Why...? 

Here's why: 
    - The mode system is really really cool 
    - Text editting becomes effortless and very efficient
    - You constantly learn new stuff
    - Typing in Vim is like a language, it's made up of words and verbs 


The mode system is really really cool 

Text editting becomes effortless and very efficient

You constantly learn new stuff

I mean, learning new stuff is fun! For example, I was wondering how to remove
brackets in Vim efficiently. I googled "how to remove parentheses Vim" and
found this solution: yi(va(p. What the? What does that even mean? Let me break
it down for you:

yi( means yank (copy) inside parentheses
va( means visually select around parentheses
p paste

<gif of removing brackets> 

Another example. Can't remember where I found but if you hover over a URL in
Vim and then type gx, it will open that link! Check it out:

<gif opening link with gx>

Typing in Vim is like a language, it's made up of words and verbs 



<script type="text/javascript" src="https://asciinema.org/a/b9w4y6mmeb00sknogxi9klfzz.js" id="asciicast-b9w4y6mmeb00sknogxi9klfzz" async></script>


-->


