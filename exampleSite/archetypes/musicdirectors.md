---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

image: "person.png" # place it in assets/images/people

meta:
  name: "music director name"
  dob: "1900-01-01"
  gender: "male"

  links:
   imdb: "https://www.imdb.com/name/{ insert imdb_id here }"
   rotten_tomatoes: "https://www.rottentomatoes.com/celebrity/{ insert rt id here }"
   meta_critic: "https://www.metacritic.com/person/{ insert metacritic id here }"
   wikipedia: "https://en.wikipedia.org/wiki/{ insert wiki id here }"
---
