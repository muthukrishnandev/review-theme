---
title: "{{ replace .Name "-" " " | title }}"
subtitle: "review subtitle"
date: {{ .Date }}
draft: true

meta_name: "movie1.md" # must be name of movie or post 
meta_type: "movies" # or "tvshows"

consensus: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
score: 80
custom_scores:
   - 50
   - 60
   
reviewtags:
    - reviewtag1
    - reviewtag2
    - reviewtag3
---

# Review Title




# Consensus

