---
layout: post
title: Spikeball
---

## Ugh
Jon's leaving. He's leaving Grand Rapids with his fiancée back to the West Coast to be closer to family, other friends, and other opportunities. The scoundrel.

{% for photo in site.static_files %}
{% if photo.path contains 'jon-bday-2026-blues-2.jpg' %}
<img src="{{ photo.path | relative_url }}"/>
<p class="image-description">The scoundrel in question</p>
{% endif %}
{% endfor %}

Jon's been my buddy since 2022. For his birthday this year, he wanted to do a beach Spikeball day with our Spikeball friends. If you don't know what Spikeball is...boy oh boy you're about to find out through about 30 photographs.

## About 30 photographs
{% for photo in site.static_files %}
{% if photo.path contains 'jon-bday-2026-blues-2.jpg' %}
{% elsif photo.path contains 'jon-bday-2026-browns-9.jpg' %}
{% elsif photo.path contains 'jon-bday-2026' %}
<img src="{{ photo.path | relative_url }}" />
{% endif %}
{% endfor %}

## What's that now? The pictures don't help you understand Spikeball?
I guess these don't really explain it that well. In short, the sport has been a great reason for us to get together. Something to talk about, to bond around. They should've called it Bond Around Net. Hopefully that helps clear things up.

## Ugh
Jon's leaving. It feels impossible to say goodbye to someone you know you'll be close to for the rest of your life. You know it's not goodbye, but it's something _like_ goodbye. It's something like "This isn't going to be the same anymore."

This will be one of our last game days all together, at least with this crew. In this era of our lives.

I know that things change, but change kind of sucks sometimes. Having a day like this, where we can revel in our victories and losses, makes it suck less. I'm glad to have these moments together.

{% for photo in site.static_files %}
{% if photo.path contains 'jon-bday-2026-browns-9.jpg' %}
<img src="{{ photo.path | relative_url }}" />
{% endif %}
{% endfor %}
