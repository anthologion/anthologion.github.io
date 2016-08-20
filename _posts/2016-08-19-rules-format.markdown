---
layout: post
title:  "Rules File Format Idea"
date:   2016-08-19
categories: specification
---
Idea for how to format liturigcal services/rules.

{% highlight markdown %}
---
name: theusual
language: en-us
translation: holy-myrrhbearers
priest: yes
deacon: no
reader: yes
default-speaker: reader
---
## The Usual Begining
{$ eoc.common.throughtheprayers spkr:reader $} Amen.
{$ eoc.common.glorryto $}
{$ eoc.common.heavenlyking $}
{$ eoc.common.holygod rep:3 $}
{$ eoc.common.glory $}
{$ eoc.common.allholytrinity $}
{$ eoc.common.lhm lang:gr-k rep:3 $}
{$ eoc.common.glory $}
{$ eoc.common.ourfather $} Amen.
{$ if(priest) $}
  {$ eoc.common.forthine spkr: priest$}
{$ else $}
  {$ eoc.common.throughtheprayers $}
{$ endif $}
{$ eoc.common.lhm rep:12 $}
{$ eoc.common.glory $}
{$ eoc.common.comeletus $}
{% endhighlight %}

