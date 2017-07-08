---
permalink: "/20170703/"
title: "2017-07-03"
layout: page
---

# General

In the year of the Lord 1952 a traveller noticed that the elders of a village in which he stayed for the night spoke a language entirely different from the majority language of the area. You are the linguist tasked with documenting it before it is lost with no trace. Within one week, create and document a naturalistic language unrelated to any Indo-European language. Optionally, make it a posteriori.

# Phonology 

Your language must contain exactly four vowel phonemes. This count includes the use of length, phonations and similar effects, but not tone.  
Your consonant inventory’s size must be either 14 or below, or 34 or above; anywhere between 15-33 is not allowed.


# Grammar

Your language must make use of sound symbolism (https://en.wikipedia.org/wiki/Sound_symbolism) either grammatically or lexically.  
Your language must make use of productive reduplication (full, partial or both).  
Your language must have significant allomorphy.  
-Your language’s verbs must be a closed class. You must be able to list them all.


# Challenges

 1. Showcase your language. In particular, show how you dealt with each of the constraints given.
 2. Translate 5 random sentences from the syntax test list. You can get these by typing the command =syntaxtest in our discord server. The translations should contain /phonemic/ and [phonetic] transcriptions, a gloss (https://www.eva.mpg.de/lingua/resources/glossing-rules.php) and commentary on interesting structures if there are any. 
 3. Design an orthography appropriate to the language’s setting. Consider whether it might have already be a written language, or whether you (the linguist) are the one creating the writing system.
 4. Show how your language has been influenced by nearby (real) languages.
 5. Describe how your language names colors. Especially pay attention to Basic Color Terms.(edited)


# Submissions

{% for submission in site.static_files %}
{% if submission.path contains "submissions/20170703/" %}
 * [{{submission.basename}}]({{submission.path | prepend:site.baseurl}})
{% endif %}
{% endfor %}
