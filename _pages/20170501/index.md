---
permalink: "/20170501/"
title: "2017-05-01"
layout: page
---

# Culture 

The language is spoken in a futuristic society among the passengers of a generation ship (https://en.wikipedia.org/wiki/Generation_ship) or the first generation to set foot on the destination planet.

# General

Make an a priori naturalistic language (the setting is too far into the future for there to be any similarity to current human languages).

# Phonology 

The language must employ lexical or grammatical tone in some way. Pitch accents are allowed.  
The language must have at least four major places of articulation, and no major PoAs further back than velar. A major PoA is here defined as contrasting at least three manners of articulation.

# Grammar

The language must deviate in some way from plain accusative alignment.  
The language must not make use of Particle Comparatives (http://wals.info/chapter/121).  
The langauge must make use of non-concatenative morphology, and must have some irregularities.

# Challenges

The first is mandatory; the rest is optional stuff for if you get bored, but I encourage you to at least do the second one as well.  

 1. Showcase your language. In particular, show how you dealt with each of the constraints given.
 2. Translate 5 random sentences from the syntax test list. You can get these by typing the command =syntaxtest in our discord server. The translations should contain /phonemic/ and [phonetic] transcriptions, a gloss (https://www.eva.mpg.de/lingua/resources/glossing-rules.php) and commentary on interesting structures if there are any.
 3. Devise a kinship system for the language.
 4. Devise a system for measuring time, both on the short scales (hours…) and the large scales (centuries…) 
 5. Design a writing system for your language. Assuming your setting is purely sci-fi, justify why they aren’t using the latin (or some other modern day earth) script.
 6. If you’re still bored, come up with a challenge to add to this list so other people don’t get bored.

# Submissions

{% for submission in site.static_files %}
{% if submission.path contains "submissions/20170501/" %}
 * [{{submission.basename}}]({{submission.path | prepend:site.baseurl}})
{% endif %}
{% endfor %}
