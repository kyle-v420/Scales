void setup() {
  size(1000, 1000);
  background(50, 255, 55);
}

void draw() {
  boolean demoman = true; 
  for(int b = -40 ; b <= 2000 ; b += 25)
  {
    for(int a = -20; a<= 1250; a+= 10)
    {
      if(demoman == true)
      e(a+5,b);
      else
        e(a,b);
    }
    if (demoman == true)
      demoman = false;
    else
    demoman = true;
      
  }
}

void e(int x, int y) {
  fill(155, 25, 255);
  ellipse(x, y, 20, 100);
  fill(255, 169, 0);
  ellipse(x, y-20, 100, 20);
}
