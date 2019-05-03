Put your assignment here.
/*
 By Ilse Westra
 Programming Tutorial 1 Exercise 6
 03-05-2019
 */
 
int counter = 0;

void setup(){
 size(500, 500);
}

void draw(){
 background(0);
 //Write a program that gives as result the sum of all multiples of 5 below 1000
   for(int i=0; i<1000; i = i + 5){
   counter = counter + 1;
 }
 println(counter);
 noLoop();
}
