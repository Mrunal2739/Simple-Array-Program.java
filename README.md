# Simple-Array-Program.java

public class SimpleArray {

public static void main(String[] args) {

SimpleArray sa = new SimpleArray();

sa.arrayOperations();

}

void arrayOperations() {

int[] array ;

array = new int[10];

array[0] = 10;

array[1] = 20;

array[2] = 30;

array[3] = 40;

array[4] = 50;

array[5] = 60;

array[6] = 70;

array[7] = 80;

array[8] = 90;

array[9] = 100;

System.out.println(array.length);

//array[10] = 110;

/*
* System.out.println(array[0]); System.out.println(array[1]);
* 
* System.out.println(array[2]); System.out.println(array[3]);
* 
* System.out.println(array[4]); System.out.println(array[5]);
* 
* System.out.println(array[6]); System.out.println(array[7]);
* 
* System.out.println(array[8]); System.out.println(array[9]);
* 
*|

//System.out.println(array[10]);

int no = array.length;

  for(int i=0; i < no ; i++) {
   
  System.out.println( array[i] ); 
  }
  
  


}

}
