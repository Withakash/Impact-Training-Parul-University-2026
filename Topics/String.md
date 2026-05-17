# Java String Interview MCQs (50 Questions)

# Topics Covered

* String
* StringBuilder
* StringBuffer
* SCP
* Heap Memory
* equals()
* hashCode()
* toString()
* compareTo()
* Immutability
* Thread Safety
* Synchronization
* String Methods
* Interning
* DSA String Logic

---

# 1. What is true about Java String?

```java
String s = "hello";
```

A. Mutable
B. Immutable
C. Thread unsafe
D. Dynamic array

---

# 2. Where are string literals stored?

```java
String s = "java";
```

A. Stack
B. Queue
C. SCP
D. CPU Cache

---

# 3. Output?

```java
String a = "java";
String b = "java";

System.out.println(a == b);
```

A. true
B. false
C. Error
D. Runtime Exception

---

# 4. Output?

```java
String a = new String("java");
String b = new String("java");

System.out.println(a == b);
```

A. true
B. false
C. java
D. Exception

---

# 5. Which method compares content?

A. ==
B. compare
C. equals()
D. hashCode()

---

# 6. Which class is mutable?

A. String
B. Integer
C. StringBuilder
D. Character

---

# 7. Which class is thread-safe?

A. StringBuilder
B. StringBuffer
C. ArrayList
D. HashMap

---

# 8. Which is fastest for modification?

A. String
B. StringBuffer
C. StringBuilder
D. Scanner

---

# 9. What does SCP stand for?

A. String Copy Pool
B. Secure Character Pool
C. String Constant Pool
D. Shared Class Pointer

---

# 10. Output?

```java
String s = "Java";
s.concat(" DSA");
System.out.println(s);
```

A. Java DSA
B. Java
C. DSA
D. Error

---

# 11. Correct pseudocode for reversing a string?

```text
START
Take string s
Loop from end to start
Print each character
END
```

A. Palindrome
B. Reverse Logic
C. Sorting
D. Hashing

---

# 12. Output?

```java
StringBuilder sb = new StringBuilder("abc");
sb.append("d");
System.out.println(sb);
```

A. abc
B. abcd
C. dabc
D. Error

---

# 13. Which operator checks reference?

A. equals()
B. compareTo()
C. ==
D. hashCode()

---

# 14. Output?

```java
String s = "hello";
System.out.println(s.charAt(1));
```

A. h
B. e
C. l
D. o

---

# 15. Time complexity of traversing string?

```text
FOR each character in string
```

A. O(1)
B. O(log n)
C. O(n)
D. O(n²)

---

# 16. Which method converts string into char array?

A. toArray()
B. toCharArray()
C. charArray()
D. convert()

---

# 17. Output?

```java
String s = "programming";
System.out.println(s.substring(0,4));
```

A. prog
B. gram
C. progra
D. rogr

---

# 18. Which method removes spaces?

A. strip()
B. trim()
C. remove()
D. clean()

---

# 19. Which class internally uses synchronized methods?

A. String
B. StringBuilder
C. StringBuffer
D. Scanner

---

# 20. Output?

```java
String s = "java";
System.out.println(s.length());
```

A. 3
B. 4
C. 5
D. Error

---

# 21. Which method finds first occurrence?

A. contains()
B. indexOf()
C. search()
D. find()

---

# 22. Output?

```java
String s = "apple";
System.out.println(s.indexOf('p'));
```

A. 0
B. 1
C. 2
D. 3

---

# 23. Which method replaces characters?

A. swap()
B. replace()
C. update()
D. insert()

---

# 24. Output?

```java
String s = "abc";
System.out.println(s.toUpperCase());
```

A. abc
B. ABC
C. Abc
D. Error

---

# 25. Which structure is best for frequency counting?

Pseudo code:

```text
Create array freq[26]
Traverse string
Increase count
```

A. Queue
B. Stack
C. Frequency Array
D. Tree

---

# 26. Output?

```java
StringBuilder sb = new StringBuilder("java");
System.out.println(sb.reverse());
```

A. java
B. avaj
C. JAVA
D. Error

---

# 27. Which method checks substring existence?

A. search()
B. contains()
C. equals()
D. starts()

---

# 28. Output?

```java
String s = "hello world";
System.out.println(s.contains("world"));
```

A. false
B. true
C. Error
D. Null

---

# 29. Which is immutable?

A. ArrayList
B. StringBuilder
C. String
D. StringBuffer

---

# 30. Output?

```java
String s1 = "abc";
String s2 = "ABC";

System.out.println(s1.equalsIgnoreCase(s2));
```

A. true
B. false
C. Error
D. abc

---

# 31. Which method converts object into readable string?

A. print()
B. hashCode()
C. toString()
D. valueOf()

---

# 32. Output?

```java
String s = "java";
System.out.println(s.compareTo("java"));
```

A. 0
B. 1
C. -1
D. Error

---

# 33. compareTo() is used for?

A. Reference comparison
B. Lexicographical comparison
C. Memory allocation
D. Threading

---

# 34. Output?

```java
String s = "java,dsa,web";
String[] arr = s.split(",");

System.out.println(arr.length);
```

A. 1
B. 2
C. 3
D. 4

---

# 35. Which concept helps memory optimization?

A. Recursion
B. SCP
C. JVM Stack
D. Garbage Variable

---

# 36. Pseudocode for palindrome?

```text
Take left = 0
Take right = length-1
Compare characters
Move inward
```

A. Searching
B. Sorting
C. Two Pointer
D. Hashing

---

# 37. Output?

```java
String s = "  java  ";
System.out.println(s.trim());
```

A. "  java  "
B. java
C. "java "
D. Error

---

# 38. Which method returns hash value?

A. value()
B. hashCode()
C. equals()
D. compare()

---

# 39. Which collection heavily uses hashCode()?

A. LinkedList
B. Queue
C. HashMap
D. Stack

---

# 40. Output?

```java
String s = "java";
System.out.println(s.startsWith("ja"));
```

A. true
B. false
C. Error
D. Null

---

# 41. Which method checks ending characters?

A. endsWith()
B. finish()
C. stopWith()
D. close()

---

# 42. Output?

```java
String s = "java";
System.out.println(s.endsWith("va"));
```

A. true
B. false
C. Error
D. java

---

# 43. Which method converts primitive into string?

A. String.convert()
B. String.parse()
C. String.valueOf()
D. String.make()

---

# 44. Output?

```java
int x = 10;
String s = String.valueOf(x);
System.out.println(s);
```

A. 10
B. x
C. Error
D. null

---

# 45. Which method moves string to SCP?

A. move()
B. store()
C. intern()
D. save()

---

# 46. Output?

```java
String s1 = new String("java");
String s2 = s1.intern();
String s3 = "java";

System.out.println(s2 == s3);
```

A. false
B. true
C. Error
D. Null

---

# 47. Best complexity for appending using StringBuilder?

A. O(n²)
B. O(log n)
C. O(1)
D. O(n)

---

# 48. Which algorithm is famous for pattern matching?

A. Bubble Sort
B. KMP
C. DFS
D. Prim

---

# 49. Which pattern is used in longest substring problems?

Pseudo code:

```text
Expand window
Shrink window
Track answer
```

A. Greedy
B. Sliding Window
C. Recursion
D. Divide and Conquer

---

# 50. Which statement is correct?

A. StringBuilder is immutable
B. StringBuffer is not synchronized
C. String is mutable
D. StringBuffer is thread-safe

---

# ANSWERS

| Q No | Answer |
| ---- | ------ |
| 1    | B      |
| 2    | C      |
| 3    | A      |
| 4    | B      |
| 5    | C      |
| 6    | C      |
| 7    | B      |
| 8    | C      |
| 9    | C      |
| 10   | B      |
| 11   | B      |
| 12   | B      |
| 13   | C      |
| 14   | B      |
| 15   | C      |
| 16   | B      |
| 17   | A      |
| 18   | B      |
| 19   | C      |
| 20   | B      |
| 21   | B      |
| 22   | B      |
| 23   | B      |
| 24   | B      |
| 25   | C      |
| 26   | B      |
| 27   | B      |
| 28   | B      |
| 29   | C      |
| 30   | A      |
| 31   | C      |
| 32   | A      |
| 33   | B      |
| 34   | C      |
| 35   | B      |
| 36   | C      |
| 37   | B      |
| 38   | B      |
| 39   | C      |
| 40   | A      |
| 41   | A      |
| 42   | A      |
| 43   | C      |
| 44   | A      |
| 45   | C      |
| 46   | B      |
| 47   | C      |
| 48   | B      |
| 49   | B      |
| 50   | D      |

---

# Important Interview Revision Notes ⭐⭐⭐

## Most Important Topics

* SCP
* Heap vs SCP
* equals() vs ==
* hashCode()
* toString()
* StringBuilder vs StringBuffer
* Synchronization
* Immutability
* compareTo()
* Sliding Window
* KMP Algorithm

---

# Golden Rules ⭐⭐⭐

## Rule 1

```java
==
```

checks reference.

```java
equals()
```

checks content.

---

## Rule 2

String is immutable.

---

## Rule 3

StringBuilder is fastest.

---

## Rule 4

StringBuffer is thread-safe.

---

## Rule 5

If overriding:

```java
equals()
```

also override:

```java
hashCode()
```

---

# Recommended Practice Questions

1. Reverse String
2. Palindrome String
3. Valid Anagram
4. Longest Substring Without Repeating Characters
5. Group Anagrams
6. String Compression
7. Longest Palindromic Substring
8. Minimum Window Substring
9. KMP Pattern Matching
10. Rabin Karp
