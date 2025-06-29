---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 70

title: "Thoughts & Pieces"
subtitle: "Some cool things I've been thinking about"
active: true

content:
  # Filter on criteria
  filters:
    folders:
      - learning
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: asc
  filter_default: 0
  filter_button:
    - name: All
      tag: '*'
    - name: Dynamical Systems
      tag: Dynamical Systems
    - name: Data Science
      tag: Data Science

design:
  # Choose a view for the listings:
  view: compact
  columns: '1'
---
