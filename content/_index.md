---
# Leave the homepage title empty to use the site title
title:
date: 2023-07-12
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ---
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: collection
  #   id: research
  #   content:
  #     title: Working Papers
  #     filters:
  #       folders:
  #         - workingpapers
  #       featured_only: false
  #   design:
  #     columns: '1'
  #     view: Card
  - block: collection
    id: research
    content:
      title: Publications
      filters:
        folders:
          - publication 
        featured_only: false
    design:
      columns: '1'
      view: Card
  - block: collection
    id: research
    content:
      title: Research in progress 
      filters:
        folders:
          - research
        featured_only: false
    design:
      columns: '1'
      view: Card
  - block: collection
    id: teaching
    content:
      title: Teaching Positions 
      filters:
        folders:
          - teaching
        featured_only: false
    design:
      columns: '2'
      view: list
    sort_by: 'Date'
---
