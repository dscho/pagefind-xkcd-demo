---
date: 2016-05-04
title: "Full-Width Justification"
num: 1676
alt: >-
  Gonna start bugging the Unicode consortium to add snake segment characters that can be combined into an arbitrary-length non-breaking snake.
img: https://imgs.xkcd.com/comics/full_width_justification.png
---
Strategies for full-width justification

[Below the caption is a column with six boxes, each showing a different "strategy" for justification which is annotated beside it. Here the annotation is written at the top and the text below. The top and bottom of the text is cut of in the middle, but as it can be "read" this is written anyway. Only for hyphenation does an extra word appear at the end. In the last with snakes, a snake is drawn to cover the entire space from the end of between to the right border.]

<dl><!-- Note: the CSS is set important and directly on the <dd> to avoid being upset by any current or future stylesheet. If the text is rendered "plain" it still should look about right -->

<dt>Giving up</dt>

<dd style="text-align:justify!important;text-justify:inter-word!important;width:10.5em">their famous paper

<span style="white-space:nowrap">on the relationship</span>

between

deindustrialization

and the growth of</dd>

<dt>Letter spacing</dt>

<dd style="text-align:justify!important;text-justify:inter-word!important;width:10.5em">their famous paper

<span style="white-space:nowrap">on the relationship</span>

<span style="white-space:nowrap">b e t w e e n</span>

deindustrialization

and the growth of</dd>

<dt>Hyphenation</dt>

<dd style="text-align:justify!important;text-justify:inter-word!important;width:10.5em">their famous paper

<span style="white-space:nowrap">on the relationship</span>

<span style="white-space:nowrap">between deindus-</span>

trialization and the growth of ecological</dd>

<dt>Stretching</dt>

<dd style="text-align:justify!important;text-justify:inter-word!important;width:10.5em">their famous paper

<span style="white-space:nowrap">on the relationship</span>

<span style="transform:scaleX(2.4) translateX(28%);;display:inline-block">between</span>

deindustrialization

and the growth of</dd>

<dt>Filler</dt>

<dd style="text-align:justify!important;text-justify:inter-word!important;width:10.5em">their famous paper

<span style="white-space:nowrap">on the relationship</span>

between crap like

deindustrialization

and the growth of</dd>

<dt>Snakes</dt>

<dd>their famous paper<br>

on the relationship<br>

between 🐍 [a snake filling the gap]<br>

deindustrialization<br>

and the growth of</dd>

</dl>