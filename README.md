# java
java cheatsheet

https://www.techinterviewhandbook.org/grind75?weeks=8

HashMap-we can store key, values

Map<Integer,Integer>map=new Hashmap<>(); //Integer/Double/String/Character/Boolean

map.put(element),map.get(element),map.containsKey(element),map.keySet(),map.values(),map.size(),map.remove()

Reference:https://www.w3schools.com/java/java_arrays.asp

example Problem:https://leetcode.com/problems/two-sum/submissions/1153761162/


Array:https://www.geeksforgeeks.org/arrays-in-java/

Initialization: int arr[]=new int[5]; int arr[]=new int[]{1,2};

return new int[]{0,1};

arr. length,

 similar to int we can declare byte, short, boolean, long, float, double, char
 
An array of Objects in Java:

An array of objects is created like an array of primitive-type data items in the following way.

Student[] arr = new Student[5]; //student is a user-defined class

// initialize the first elements of the array

        arr[0] = new Student(1, "a man");
 
        // initialize the second elements of the array
        
        arr[1] = new Student(2, "Vaibhav");


Arrays class in Java:https://www.geeksforgeeks.org/array-class-in-java/

import java. util.Arrays; 

Arrays.asList(arr)),Arrays.binarySearch(intArr, intKey)),Arrays.sort(intArr),Arrays.binarySearch(intArr, 1, 3, intKey)); 

Arrays.toString(intArr)); Arrays.sort(intArr);Arrays.sort(arr, new Sortbyroll()){using comparator}




String:https://www.w3schools.com/java/java_ref_string.asp
str.length();str.toUpperCase();str.toLowerCase();str.indexOf("s");str.toCharArray();

https://docs.oracle.com/javase/8/docs/api/java/lang/Character.html

https://docs.oracle.com/javase/8/docs/api/java/lang/StringBuilder.html

Example for StringBuilder
StringBuilder sb=new StringBuilder();
        for(char c:s.toCharArray()){
            if(Character.isLetterOrDigit(c))
               sb.append(Character.toLowerCase(c));

        }
        if(sb.toString().equals(sb.reverse().toString())){
            return true;
        }
        return false;


 converting string to array, array to string
 
        char[] a=s.toCharArray();
        char[] b=t.toCharArray();
        Arrays.sort(a);
        Arrays.sort(b);
        String s1=new String(a);
        String s2=new String(b);







  










