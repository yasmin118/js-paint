# js-paint

function setup() {
  createCanvas(600, 600);
  background('pink');
}

function draw() {
  stroke('rgb(248,99,125)');
  fill('rgb(246,162,177)');
  if(mouseIsPressed) {
  rect(mouseX, mouseY, 20, 30); 
  }
}
