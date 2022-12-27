---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: ''
subtitle: ''

count: 3

content:
  # Page type to display. E.g. project.
  page_type: project
  filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0
  buttons:
    - name: All
      tag: '*'
    - name: Chirality
      tag: chirality
    - name: Other
      tag: Demo
design:
  columns: '3'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [10, 0, 5, 0]}
---
