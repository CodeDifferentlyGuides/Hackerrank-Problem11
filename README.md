# Java Inheritance I

Using inheritance, one class can acquire the properties of others. Consider the following Animal class:

class Animal{ <br>
    void walk(){ <br>
        System.out.println("I am walking"); <br>
    } <br>
} <br>
This class has only one method, walk. Next, we want to create a Bird class that also has a fly method. We do this using extends keyword:

class Bird extends Animal { <br>
    void fly() { <br>
        System.out.println("I am flying"); <br>
    } <br>
} <br><br>
Finally, we can create a Bird object that can both fly and walk.

public class Solution{ <br>
   public static void main(String[] args){ <br>

      Bird bird = new Bird(); 
      bird.walk(); 
      bird.fly(); 
   } <br>
} <br>
The above code will print:

I am walking <br>
I am flying <br><br>
This means that a Bird object has all the properties that an Animal object has, as well as some additional unique properties. <br>

The code above is provided for you in your editor. You must add a sing method to the Bird class, then modify the main method accordingly so that the code prints the following lines:

I am walking <br>
I am flying <br>
I am singing <br><br>

Hackerrank Link: https://www.hackerrank.com/challenges/java-inheritance-1/problem
