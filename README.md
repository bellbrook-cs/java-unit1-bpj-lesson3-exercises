# Lesson 3 Exercises

1. Write code in which a `String` variable `s` contains `"The number of rabbits is"`. An integer variable `argh` has a value of `129`. Concatenate these variables into a `String` called `report`. Then print `report`. The printout should yield:  

```
The number of rabbits is 129.
```

Note that we want a period to print after the `9`.  

2. What is the output of 

```java
System.out.println( p.toUpperCase( ) );
```

if `p == "Groovy Dude"`?  

3. Write code that will assign the value of `"Computer Science is for nerds"` to the `String` variable `g`. Then have it print this `String` with nothing but `"small"` letters. 
4. What will be the value of `c`?  

```java
String c; 
String m = "The Gettysburg Address"; 
c = m.substring(4);  
```

5. What will be the value `c`?  

```java
String b = "Four score and seven years ago,";  
String c = b.substring(7, 12);  
```

6. What is the value of `count`?  

```java
int count;  
String s = "Surface tension"; 
count = s.length( );  
```

7. Write code that will look at the number of characters in `String m = "Look here!";` and then print 

```
"Look here!" has 10 characters.  
```

Use the `length( )` method to print the `10`... you must also force the two quotes to print. 

8. How would you print the following?  

```
All "good" men should come to the aid of their country. 
```

9. Write code that will produce the following printout using only a single `println( )`.  

```
Hello
Hello again  
```

10. Write code that will produce the following printout.  

```
A backslash looks like this \, …right?  
```

11. What is output by the following?  

```java
String pq = "Eddie Haskel";  
int hm = pq.length( );  
String ed = pq.substring(hm - 4);  
System.out.println(ed);
```

12. Which character is at the 5th index in the String "Herman Munster"?
