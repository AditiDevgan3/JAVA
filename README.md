# JAVA
## Question 1:
WAP to Print Hello World!
```java
public class HelloWorld{
    public static void main(String []args){   	       
        		System.out.println("Hello World!");
    }  
}
```
## Question 2:
WAP to find if the given number is even or odd
```java
import java.util.*;  
public class HelloWorld{
    public static void main(String []args){
    	Scanner sc= new Scanner(System.in);
    	int num = sc.nextInt();
    	if(num%2==0){
    		System.out.println("The number is even!");
    	}else {
    		System.out.println("The number is odd!");
    	}
        		
    }  
}
```
## Question 3:
WAP to find if the given number is positive, negative or odd
```java
import java.util.*;  
public class HelloWorld{
    public static void main(String []args){
    	Scanner sc= new Scanner(System.in);
    	int num = sc.nextInt();
    	if(num>0){
    		System.out.println("The number is positive!");
    	}else if(num<0) {
    		System.out.println("The number is negative!");
    	}else {
    		System.out.println("The number is zero!");
    	}
        		
    }  
}
```
## Question 4:
WAP to find if the year is a leap year or not
```java
import java.util.*;  
public class HelloWorld{
    public static void main(String []args){
    	Scanner sc= new Scanner(System.in);
    	int year = sc.nextInt();
    	if(((year % 4 == 0) && (year % 100!= 0)) || (year%400 == 0)) {
    		System.out.println("The year is leap year!");
    	}else {
    		System.out.println("The year is not a leap year!");
    	}
    }
}
```
## Question 5:
WAP to perform arithmetic operations on given numbers
```java
import java.util.*;  
public class HelloWorld{
    public static void main(String []args){
    	Scanner sc= new Scanner(System.in);
    	int num1 = sc.nextInt();
    	int num2 = sc.nextInt();
    	int sum = num1+num2;
    	int sub = num1-num2;
    	int mul = num1*num2;
    	int div = num1/num2;
    	System.out.println("Addition: "+sum);
    	System.out.println("Subtraction: "+sub);
    	System.out.println("Multiply: "+mul);
    	System.out.println("Divide: "+div);
    }
}
```
## Question 6:
WAP to find the largest number
```java
import java.util.*;  
public class HelloWorld{
    public static void main(String []args){
    	Scanner sc= new Scanner(System.in);
    	int num1 = sc.nextInt();
    	int num2 = sc.nextInt();
    	int num3 = sc.nextInt();
    	if(num1>num2 && num1>num3) {
    		System.out.println("Num1 is the largest");
    	}else if(num2>num3){
    		System.out.println("Num2 is the largest");
    	}else {
    		System.out.println("Num3 is the largest");
    	}
    	
    }
}
```
## Question 7:
WAP to print array elements in the array:
```java
public class Arr{

    public static void main(String []args){
        int[] arr = {1,2,3,4,5,6};
        for(int i=0;i<arr.length;i++) {
        	System.out.println(arr[i]);
        }              
    }    
}
```
## Question 8:
WAP to print largest element in the array:
```java
import java.util.Arrays;
public class Arr{

    public static void main(String []args){
        int[] arr = {1,2,3,4,5,6};
        int max = Arrays.stream(arr).max().getAsInt();
        	System.out.println(max);
    } 
}
```
## Question 9:
WAP to print smallest element in the array:
```java
import java.util.Arrays;
public class Arr{

    public static void main(String []args){
        int[] arr = {1,2,3,4,5,6};
        int max = Arrays.stream(arr).min().getAsInt();
        	System.out.println(max);
    } 
}
```
## Question 10:
WAP to print all elements of one array into another array:
```java
public class PrintingElementsOfArray{

    public static void main(String []args){
    	
        int[] arr = {1,2,3,4,5,6};
        int[] arr2 = new int[arr.length];
        for(int i=0;i<arr.length;i++) {
        	arr2[i] = arr[i];
        	System.out.println(arr2[i]);
        }                
    }    
}
```
## Question 11:
WAP to print sum of all the elements of an aarray:
```java
public class Sum{

    public static void main(String []args){   	
        int[] arr = {1,2,3,4,5,6};
        int sum = 0;
        for(int i=0;i<arr.length;i++) {
        	sum = sum + arr[i];
        }
        System.out.println("Sum of elements in array is: "+sum);
    }    
}
```
## Question 12:
WAP to print to perform linear search:
```java
public class LinearSearch{

    public static void main(String []args){   	
        int[] arr = {1,2,3,4,5,6};
        int x = 6;
        for(int i=0;i<arr.length;i++) {
        	if(arr[i] == x) {
        		System.out.println(i);
        	}
        }
    }    
}
```
