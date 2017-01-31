# Programacion_Orientada_a_Objetos
Claudia Andrea Pérez Juarez

void setup() {
  size(500, 400);
  background(10, 80, 100);
}

void draw() {
  stroke(255, 255, 255);
  fill(random(0,255),random(0,255),random(0,255));
  ellipse(mouseX, mouseY, 100, 100);

  fill(255,0,0);
  rect(mouseX, mouseY, 30, 30);

  
}
