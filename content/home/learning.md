---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: 'What I'm Learning'
subtitle:
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
  filter_button:
    - name: All
      tag: '*'
    - name: Mathematics
      tag: Mathematics
    - name: Physics
      tag: Physics
    - name: Statistics
      tag: Statistics
    - name: Dynamical Systems
      tag: dynamicalsystems
design:
  # Choose a view for the listings:
  view: showcase
  columns: '1'
---
