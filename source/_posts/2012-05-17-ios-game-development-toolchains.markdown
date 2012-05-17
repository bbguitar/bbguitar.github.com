---
layout: post
title: "iOS Game Development ToolChains"
date: 2012-05-17 09:05
comments: true
categories: 
---
In an effort to finally getting round to creating an iOS game I thought I'd 
brain dump my software toolchest.

## Programming

This part is easy, and although I can appreciate lua I'm really going to stick to Objective-C
with a smattering of C++ if needed. Its way too easy to get trawled into multi-language projects
and keeping focused on one language makes things simple.

Whilst I love the idea of TDD, BDD and lots of unit tests, like many people, I've found Testing to
be extremely difficult in iOS. For games its much harder. I may build discrete unit tests for any AI and logic inside classes but only if the mocks are not too brittle.


I tend to use git as my code management tool and I'll probably push up to github as time goes on.

I'm not going to get into code coverage and the like for my first iOS game. 

## IDE

Not much choice here xcode is the _de facto_ and I'll swap between vim and xcode as needed.
I could use eclipse and spend a few hours plugging in all the build stuff but I'd still need 
to swap back into xcode for code signing and the other things that are easy to do like archiving, 
building and analysis.
_Note to apple, could we have editor plugins to xcode so I could use vim or emacs bindings without
lot of hassle?_


## Frameworks

I've looked through half a dozen and keep coming back to the same conclusion: ___Cocos 2D___

There's lots of activity, lots of people using it, lots of apps already using it and there are
a few books out there too. 

## Project management

This is the one most solo developers ignore. I've used several systems over the years but for ease of
setup I prefer to set up a local __trac__ instance and use it as a project dumping ground.

I've played around with plugging agilo into trac and I've also got a project pier instance setup if I need it. However I keep coming back to using trac as a todo list especially as I can integrate git into it
easily.

I like _basecamp_ but I can't justify the monthly cost until I've got two or three profitable apps under my belt and I'd rather not start with it at the moment even on a free plan.

## Media

### Graphics

* ___Blender 3D___ for as much as I need for sprite creation and backgrounds.
* ___Inkscape/Gimp___ for any other pixel level work

Depending on the game design I may also need tools to create bitmap fonts, pack textures,
create layouts and physics object tracing. I may be persuaded to buy some tools for this
if I can avoid the moths coming out of my wallet at the time.

### Music/SFX

This is a no-brainer for me. As a legitimate owner of Reason 6 I'll most likely use that
for background music. I might use some of the Garageband loops to begin with but replace them
afterwards. The initial generation might come from some other tools like mma or a pD setup but
I'll experiment when the time comes.



It's easy to become bewildered by the vast array of tools to solve each problem but experience 
has shown me that its better to focus on just a small set. 

If you have suggestions for other tools that I should include, put them in the discussion below.


