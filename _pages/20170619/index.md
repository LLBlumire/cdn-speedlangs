---
permalink: "/20170619/"
title: "2017-06-19"
layout: page
---

# Culture 

The langauge is spoken in a high fantasy world like setting of your design. Speakers must be a non-human fantasy race that is reasonable for your setting!

# General

Make an a priori language, naturalism is not critical as this is high fantasy.

# Phonology 

Your phonology must include at least one sound not pronouncable by humans. You can provide a human approximation (used by humans, if they exist in your setting), but the form of the language spoken by it's native speakers contains the phone [ж] (feel free to choose another silly codepoint), this can be phonetic or phonemic.  
Your phonology must contain either 10 or more phonemically distinct soronants, feel free to make [ж] to cheat it down to 9.

# Grammar

The language must have a noun class system with more than 2 classes, try and make it interesting. These must cause inflectional changes to at least one other gramatical category (of your chosing/design).  
The language must have a fusional component to it's verb or noun inflections, they don't need to be purely fusional, but fusion must happen somewhere.  
The language must (dominantly) have objects before subjects, either OSV, OVS, or VOS. If you want to deviate from this in certain instances that's fine, but dominant speech must be O before S.

# Challenges

The first is mandatory; the rest is optional stuff for if you get bored, but I encourage you to at least do the second one as well.  

 1. Showcase your language. In particular, show how you dealt with each of the constraints given.
 2. Translate 5 random sentences from the syntax test list. You can get these by typing the command =syntaxtest in our discord server. The translations should contain /phonemic/ and [phonetic] transcriptions, a gloss (https://www.eva.mpg.de/lingua/resources/glossing-rules.php) and commentary on interesting structures if there are any.
 3. Divise some anatomical words the race uses to describe their own bodies.
 4. Divise some fictional species or flora or fauna, and come up with interesting names for them (this is a good chance for interesting etymologies).
 5. Make a writing system for your language, have it make sense in the context of your race (stone smashing orks probably aren't writing in elaborate ink cursive any time soon)
 6. Come up with some idioms that are used in the conculture.
 7. If you’re still bored, come up with a challenge to add to this list so other people don’t get bored.

# Submissions

{% for submission in site.static_files %}
{% if submission.path contains "submissions/20170619/" %}
 * [{{submission.basename}}]({{submission.path | prepend:site.baseurl}})
{% endif %}
{% endfor %}
