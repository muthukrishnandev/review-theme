---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

meta:
  title: "movie title"
  tagline: "movie tagline"

  storyline: "story line"

  released_on: "2001-01-01"
  running_time: 50 # in minutes
  certificate: "U"

  links:
   imdb: "https://www.imdb.com/title/{ insert imdb_id here }"
   rotten_tomatoes: "https://www.rottentomatoes.com/m/{ insert rt id here }"
   meta_critic: "https://www.metacritic.com/movie/{ insert metacritic id here }"
   wikipedia: "https://en.wikipedia.org/wiki/{ insert wiki id here }"

poster: "images/posters/poster.png" # place it in assets/images/posters
review: "review-name.md" # if no review written, comment this

actors:
  - actor1
  - actor2
  - actor3

directors:
  - director1
  - director2

cinematographers:
  - cinematographer1
  - cinematographer2

musicdirectors:
  - musicdirector1
  - musicdirector2

genres:
  - genre1
  - genre2
  - genre3

plottags:
  - plottag1
  - plottag2
  - plottag3
---
