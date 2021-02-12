---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true

meta:
  title: "movie title"
  tagline: "movie tagline"
  storyline: "story line"

  year: "2001"
  released_on: "2001-01-01"
  running_time: 50 # in minutes
  certificate: "U"

  total_episodes: 20
  total_seasons: 20
  year_end:  2020

  trailer: "https://youtube.com/watch?v=INSERT_YOUTUBE_ID_HERE"
  poster: "https://example.com/poster.jpg" # or "/posters/poster.png" and place it in static/images directory

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

creators:
  - creator1
  - creator2
  - creator3

plottags:
  - plottag1
  - plottag2
  - plottag3
---
