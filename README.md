# Tarea1
int col;
void setup ()

{
   size (640, 680); 
   frameRate (3000);
}

void draw ()

{
   
  background (col);
  col++;
  if(col>255)
    col=0;
  
  
}
