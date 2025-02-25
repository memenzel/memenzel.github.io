+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = false

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "200"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Subtropical Jet Behavior in Idealized Models"
  content = "What are the necessary processes to decouple the subtropical jet from the Hadley Cell?"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#333"  # An HTML color value.
  overlay_img = "featured/ideal.jpg"  # Image path relative to your `static/media/` folder.
#  overlay_
  overlay_filter = 0.65  # Darken the image. Value in range 0-1.

  cta_label = "Read More"
  cta_url = "project/ideal_atmos"

[[item]]
  title = "Subtropical Jet and Hadley Cell Relationship in CMIP5"
  content = "Is the subtropical jet actually coupled to the Hadley Cell?"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "featured/cmip5_crop.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.65  # Darken the image. Value in range 0-1.

  cta_label = "Read More"
  cta_url = "project/cmip5"

[[item]]
  title = "Connections between the Lower Stratosphere and Tropospheric Circulation"
  content = "How does tropical tropospheric circulation impact the lower stratosphere and vice versa?"
  align = "center"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "featured/metrics_crop.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.65  # Darken the image. Value in range 0-1.

  cta_label = "Read More"
  cta_url = "project/utls_connect"

+++
