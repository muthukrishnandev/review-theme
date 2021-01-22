---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

meta:
  name: "music director name"
  dob: "1900-01-01"
  gender: "female"
 
  image: "person.png" # place it in assets/images/people

  links:
    imdb: "https://www.imdb.com/name/INSERT_IMDB_ID_HERE"
    rotten_tomatoes: "https://www.rottentomatoes.com/celebrity/INSERT_RT_ID_HERE"
    meta_critic: "https://www.metacritic.com/person/INSERT_METACRITIC_ID_HERE"
    wikipedia: "https://en.wikipedia.org/wiki/INSERT_WIKI_ID_HERE"
---
