---
layout: post
title: "I Wish I Were a Donkey"
date: 2014-10-30
tag: donkey
---
That's right. A donkey would be a great thing to be.

Here are some other cool things:

{% for cool_thing in site.data.cool_things %}
*  A {{cool_thing.name}} that says {{cool_thing.sound}}
{% endfor %}
