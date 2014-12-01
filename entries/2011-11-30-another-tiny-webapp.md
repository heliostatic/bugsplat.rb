---
title: Another Tiny Webapp
date: '2011-11-30 11:46:50'
tags: Projects
id: fefc4
topic: Software
description: A little webapp for managing a painkiller schedule.
---

Literally ten minutes after hitting the publish button on my [last post](/concurrency-on-heroku-cedar) I took a little tumble and broke a rather important bone in my back, and now I'm on medical leave from work for awhile.

That doesn't stop me from doing fun things, though, so this morning I cooked up a tiny webapp using [Sinatra][], [DataMapper][], and [Bootstrap][] that will help me keep track of when I take painkillers. It's called [Painkiller Jane][] after the comic book character.

--fold--

<img src="https://github.com/peterkeen/painkillerjane/raw/master/public/screenshot.png">

There's not much interesting going on here to be honest. Basically it's just one database table and an in-app configuration hash that lays out what pills are available, their dosage, and their cooldown period. I can click the buttons when the cooldown is over, but when it's not they tell me what time I can take the next dose.

The only other feature that I might add is a lockout so that it helps me manage which pill to take when because I'm alternating tylenol and advil.

[Sinatra]: http://www.sinatrarb.com/
[DataMapper]: http://datamapper.org/
[Bootstrap]: http://twitter.github.com/bootstrap
[Painkiller Jane]: https://github.com/peterkeen/painkillerjane
