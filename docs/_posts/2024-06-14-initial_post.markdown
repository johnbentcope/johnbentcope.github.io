---
layout: post
title:  "Initial Post"
date:   2024-06-14 17:35:43 -0400
categories: 
---

# Hello, World!

This is my initial posting. I hope to document technical development and creative exploration.

### augh

{% include p5js-widget.html width=200 height=200 %}
 function setup() {
  createCanvas(200, 200);

// state
  let circleY = 0;
}

function draw() {
  // clear out old frames
  background(32);

  // draw current frame based on state
  circle(100, circleY, 50);

  // modify state
  circleY = circleY + 1;
}

</script>

### augh