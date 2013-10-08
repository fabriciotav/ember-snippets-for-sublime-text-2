Ember.js snippets for Sublime Text 2
====================================

## Ember.js

- app ⇥
- component ⇥
- controller ⇥
- helper ⇥
- mixin ⇥
- model ⇥
- object ⇥
- route ⇥
- router ⇥
- store ⇥
- view ⇥

## Handlebars helpers

- action ⇥
- each ⇥
- eachelse ⇥
- if ⇥
- ifelse ⇥
- linkto ⇥
- partial ⇥
- unless ⇥
- viewb ⇥

## Handlebars script tag

- hbs ⇥

If you don't want to be annoyed by JavaScript syntax when using type="text/x-handlebars" with Sublime Text 2, just edit the HTML.tmLanguage file, replacing:

  `<string>(?:^\s+)?(&lt;)((?i:script))\b(?![^&gt;]*/&gt;)</string>`

with:

  `<string>(?:^\s+)?(&lt;)((?i:script))\b(?!([^&gt;]*text/x-handlebars[^&gt;]*|[^&gt;]*/>))</string>`

