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

  episodes_count: 20
  series_start_year:  2019
  series_end_year:  2020

  trailer: "https://youtube.com/watch?v=INSERT_YOUTUBE_ID_HERE"
  poster: "https://example.com/poster.jpg" # or "poster.png" and place it in assets/images/posters

  external_links:
    imdb: "https://www.imdb.com/title/INSERT_IMDB_ID_HERE"
    rotten_tomatoes: "https://www.rottentomatoes.com/m/INSERT_RT_ID_HERE"
    meta_critic: "https://www.metacritic.com/movie/INSERT_METACRITIC_ID_HERE"
    wikipedia: "https://en.wikipedia.org/wiki/INSERT_WIKI_ID_HERE"

genres:
  - genre1
  - genre2
  - genre3

actors:
  - actor1
  - actor2
  - actor3

directors:
  - director1
  - director2

writers:
  - writer1
  - writer2

cinematographers:
  - cinematographer1
  - cinematographer2

musicdirectors:
  - music_director1
  - music_director2

plottags:
  - plottag1
  - plottag2
  - plottag3
---
