# java-tutorial

```
Java Class

//example-1
class niranjan {
   public static void main(String args[]){ // Method Header
       System.out.println("Hello World"); // Methos Body
   }
}

//example-2
class hello {
   public static void main(String args[]){
	   double x; //Just like Float Value
	   x = 25;
	   System.out.println("The x Value is:" + x);
   }
}

//Example-3 # Scanner to take import from user
import java.util.Scanner;  // Import Scanner Package , similar to import modules in Python

class hello {
   public static void main(String args[]){
	   Scanner myVar = new Scanner(System.in); //Defined Scannaner myvar and asking for user input
	   System.out.print(myVar.nextLine()); // Its will wait for user input, once received output, it will print on console.
   }
}
==================================
If Conditions
class hello {
   public static void main(String args[]){
	  
	   int apple, orange;
	   
	   apple = 10;
	   orange = 10;
	   
	   if (apple == orange) {
		   
		  System.out.println( "Provided Value is: " + apple);
		  
	   }else if ( apple != orange){
		   
		   System.out.println( "hey i am in else if");
	   }else{
		   System.out.println( "Hey I am in else");
		   
	   }
		   
	}
}
=========================
Switch case

class hello {
   public static void main(String args[]){
	  
	   int age;
	   age = 61;
	   
	switch (age) {
	  
	case 18:
		System.out.println("You can Vote Now");
		break;
		
	case 25:
		System.out.println("You can marry now");
		break;
	case 60:
		System.out.println("You can Retire Now");
	    break;
	    
	default:
		System.out.println("You have to wait");
		
	}   
			   
  }
		   
}
===================================
## While Loop
class hello {
   public static void main(String args[]){
	   int age;
	   age = 0;
	   
  while ( age < 9 ) {
	  age++; 
	   System.out.println( age + " Hello" );
      }
		
  }   
			   
}
==================================
Arrays in Java.
import java.util.ArrayList;

class hello {
   public static void main(String args[]){
	   
	   String Student[] = { "Rama", "Sita", "Laxmana", "Hanuma" };
	   System.out.println(Student[0]);
	   
	   /*
	   int apple[] = { 5, 10, 15, 20, 25, 30 };
	   System.out.println(apple[2]);
	   */
	  
	   /*
	   ArrayList<String> cars = new ArrayList<String>();
	    cars.add("Volvo");
	    cars.add("BMW");
	    cars.add("Ford");
	    cars.add("Mazda");
	    System.out.println(cars.get(0));
		*/
  }   
```
