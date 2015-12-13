# my-work
my work of economic
fill(255, 0, 255);
var mouseX = 50;
var mouseY = 40;
var draw = function() {
    background(255, 255, 255);
    ellipse(mouseX, mouseY, 12, 12); 
    var label = mouseX + ' , '+ mouseY;
    text(label, mouseX+15, mouseY+4);
};
