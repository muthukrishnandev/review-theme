---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}

meta:
  name: "actor name"
  dob: "1900-01-01"
  gender: "male"

  image: "https://example.com/person.jpg" # or "person.png" and place it in assets/images/people

  external_links:
    imdb: "https://www.imdb.com/name/INSERT_IMDB_ID_HERE"
    wikipedia: "https://en.wikipedia.org/wiki/INSERT_WIKI_ID_HERE"
---
