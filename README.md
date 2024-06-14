# johnbentcope.github.io


{% include p5js-widget.html width=200 height=200 %} function setup() { createCanvas(200, 200);

// state let circleY = 0; }

function draw() { // clear out old frames background(32);

// draw current frame based on state circle(100, circleY, 50);

// modify state circleY = circleY + 1; } </script>