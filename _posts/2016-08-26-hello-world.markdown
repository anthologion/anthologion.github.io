---
layout: post
title:  "Hello Flask!"
date:   2016-08-26
categories: news
---
Several accomplishments to report. While my efforts up to this point had
focused on trying to decide on how to design a markup for liturgics, and my
last post proposed a syntax, I have recently discovered a tool previously
unknown to me: template engines!

A friend of mine tipped my off to Jinja a while back as a possible tool, but I
hadn't looked at it in depth. This past week I looked thorugh its docs and I
think it has all the power I need, and a syntax very similar to what I had
proposed in my previous blog post. It just turns out this is a more generic
problem than I had realized and someone else has already implemented solutions.

## Libraries and Frameworks and Engines Oh My

Web Server: Not decided. Apache or nginx. Using Flask's development server in
the interim.

Web Framework: Flask

Template enginer: Jinja2

## Prototype

A prototype has been pulled together. Code can be viewed on
[github](https://github.com/anthologion), the 
[anthologion.faith](https://github.com/anthologion/anthologion.faith)
project has the driver code.

I have purchased the domains `anthologion.faith` and `anthologion.org` for this
project. The development server is available sometimes at 
[http://www.anthologion.faith/]

## Up next

Right now the prototype is a bunch of haphazard text blatted to the screen
just to get a feel for how the tools work. The next thing I want to learn is
how to process query strings in Flask.

I'm a big advocate of useing https everywhere, so I also want to look into
[Let's Encrypt](https://letsencrypt.org/).

