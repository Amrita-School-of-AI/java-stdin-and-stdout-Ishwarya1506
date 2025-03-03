[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17932145&assignment_repo_type=AssignmentRepo)
# Java Stdin and Stdout Challenge

One popular way to read input from stdin is by using the Scanner class and specifying the Input Stream as System.in. For example:

```java
    Scanner scanner = new Scanner(System.in);
    String myString = scanner.next();
    int myInt = scanner.nextInt();
    scanner.close();
    
    System.out.println("myString is: " + myString);
    System.out.println("myInt is: " + myInt);
```

The code above creates a `Scanner` object named and uses it to read a `String` and an `int`. It then closes the `Scanner` object because there is no more input to read, and prints to stdout using `System.out.println(String)`. So, if our input is:

```shell
    Hi 5
```

Our code will print:

```shell
myString is: Hi
myInt is: 5
```

Alternatively, you can use the BufferedReader class.

### Task:
In this challenge, you must read 3 integers from stdin and then print them to stdout. Each integer must be printed on a new line. To make the problem a little easier, a portion of the code is provided for you.

#### Input Format

There are lines of input, and each line contains a single integer.

#### Sample Input

```
42
100
125
```

#### Sample Output 

import java.util.Scanner

```
42
100
125
```
