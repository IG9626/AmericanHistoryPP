State[] States = new State[4];
PImage img;  // Declare a variable of type PImage
//Period(int x, int y, int w, int h, int xx, int yy, int ww, int hh)
void setup() {
  size(1200, 675);
  tint(255,70);
  img = loadImage("americanMapPeriod1.jpg");
  //number buttons-done
  States[0] = new State(150, 360, 25, 25, 300, 100, 600, 525, "Period 3","la");
  States[1] = new State (1050, 230, 25, 25, 300, 100, 600, 525, "Settlement", "la");
  States[2] = new State(650, 360, 25, 25, 300, 100, 600, 525, "Native Americans", "la");
  States[3] = new State (940, 470, 25, 25, 300, 100, 600, 525, "Settlement", "la");
  //operation buttons-not finished-how to do clear?
}
void draw() {
  background(255);
  image(img,0,0,1200,675);
  for (int i=0; i<States.length; i++) {
    States[i].display();
    States[i].hover();
    States[i].mousePressed();
  }
}
