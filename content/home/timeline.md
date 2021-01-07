---
# An instance of the Blank widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 25

title: Timeline
subtitle:

design:
  columns: "1"
  background:
    image:  
    image_darken: 0
    image_parallax: false
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]


---
{{< chart data="timeline.json" >}}