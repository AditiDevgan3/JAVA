# JAVA
## Question 1:
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
## Question 2:
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
## Question 3:
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
## Question 4:
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
## Question 5:
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
## Question 6:
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
