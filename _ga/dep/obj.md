---
layout: relation
title: 'obj'
shortdef: 'direct object'
---

The `obj` label is used to mark the relationship between a verb and its direct object.

### Examples

_Bhailigh siad eolas_ 'They collected <b>information</b>'

~~~ sdparse
Bhailigh siad eolas \n Collected they information
obj(Bhailigh, eolas)
~~~

Note that the object of an infinitival phrase occurs before the infinitive form (Verbal Noun), despite Irish being a VSO language.

_<b>eolas</b> a chur ar fáil_  'to make <b>information</b> available'

~~~ sdparse
eolas a chur ar fáil \n information to put at available
obj(chur, eolas)
~~~

Impersonal/autonomous verbs are used to create phrases similar to the English passive. However, unlike English, the object does not become the subject of this verb form, and remains labelled as `obj`.

_An lá a cuireadh <b>é</b>_ 'The day <b>he</b> was buried'

~~~ sdparse
An lá a cuireadh é \n The day [] was_buried he
obj(cuireadh, é)
~~~



