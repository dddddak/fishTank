background(89, 216, 255);

var drawFish = function(centerX, centerY, bodyLength, bodyHeight, bodyColor) {

    noStroke();
    fill(bodyColor);
    // body
    ellipse(centerX, centerY, bodyLength, bodyHeight);
    // tail
    var tailWidth = bodyLength/4;
    var tailHeight = bodyHeight/2;
    triangle(centerX-bodyLength/2, centerY,
            centerX-bodyLength/2-tailWidth, centerY-tailHeight,
            centerX-bodyLength/2-tailWidth, centerY+tailHeight);
    // eye
    fill(33, 33, 33);
    ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);

};

drawFish(random(20, 300), random(20, 300), random(20, 150), random(20, 100), color(random(0, 256), random(0, 256), random(0, 256)));
drawFish(random(20, 300), random(20, 300), random(20, 150), random(20, 100), color(random(0, 256), random(0, 256), random(0, 256)));
drawFish(random(20, 300), random(20, 300), random(20, 150), random(20, 100), color(random(0, 256), random(0, 256), random(0, 256)));

var drawBubbles = function() {
    noStroke();
    var BubbleSize = random(5, 40);
    fill(211, 252, 248);
    ellipse(random(10, 350), random(10, 100), BubbleSize, BubbleSize);
};

drawBubbles();
drawBubbles();
drawBubbles();
drawBubbles();
drawBubbles();

mouseClicked = function() {
    var centerX = mouseX;
    var centerY = mouseY;
    var bodyLength = random(20, 150);
    var bodyHeight = random(20, 100);
    var bodyColor = color(random(0, 256), random(0, 256), random(0, 256));
    noStroke();
    fill(bodyColor);
    // body
    ellipse(centerX, centerY, bodyLength, bodyHeight);
    // tail
    var tailWidth = bodyLength/4;
    var tailHeight = bodyHeight/2;
    triangle(centerX-bodyLength/2, centerY,
            centerX-bodyLength/2-tailWidth, centerY-tailHeight,
            centerX-bodyLength/2-tailWidth, centerY+tailHeight);
    // eye
    fill(33, 33, 33);
    ellipse(centerX+bodyLength/4, centerY, bodyHeight/5, bodyHeight/5);

};




