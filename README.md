1. **What will be the output of the following code?**

    ```java
    int a = 5, b = 10, c = 15;
    int result = a + b * c / a;
    System.out.println(result);
    ```
    - A) 15
    - B) 20
    - C) 25
    - D) 30


2. **What will be the output of the following code?**

    ```java
    int x = 5;
    while (x > 0) {
        System.out.print(x + " ");
        x--;
    }
    ```
    - A) 5 4 3 2 1
    - B) 5 4 3 2 1 0
    - C) 4 3 2 1
    - D) 4 3 2 1 0



3. **What does the following method do?**

    ```java
    public static void mystery(int n) {
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
    ```
    - A) Prints a square of stars
    - B) Prints a right-angled triangle of stars
    - C) Prints an inverted triangle of stars
    - D) Prints a pyramid of stars



4. **What will be the output of the following code?**

    ```java
    int[] arr = {1, 2, 3, 4, 5};
    for (int i = 0; i < arr.length; i++) {
        arr[i] *= 2;
    }
    System.out.println(arr[3]);
    ```
    - A) 4
    - B) 6
    - C) 8
    - D) 10



5. **What will be the value of `sum` after the following loop executes?**

    ```java
    int sum = 0;
    for (int i = 1; i <= 5; i++) {
        sum += i;
    }
    ```
    - A) 10
    - B) 15
    - C) 20
    - D) 25



6. **What will be the output of the following code?**

    ```java
    String str = "Hello";
    for (int i = 0; i < str.length(); i++) {
        System.out.print(str.charAt(i) + " ");
    }
    ```
    - A) H e l l o
    - B) Hello
    - C) H e l l o 
    - D) H,e,l,l,o


7. **Which of the following statements correctly creates an ArrayList of Strings?**

    - A) `ArrayList<String> list = new ArrayList<>();`
    - B) `ArrayList<String> list = new ArrayList<String>();`
    - C) `ArrayList list = new ArrayList<String>();`
    - D) All of the above


8. **What will be the output of the following code?**

    ```java
    int[] arr = {2, 4, 6, 8, 10};
    int sum = 0;
    for (int i = 0; i < arr.length; i += 2) {
        sum += arr[i];
    }
    System.out.println(sum);
    ```
    - A) 10
    - B) 12
    - C) 14
    - D) 16


9. **What is the output of the following code segment?**

    ```java
    int x = 3;
    switch (x) {
        case 1:
            System.out.print("One ");
            break;
        case 2:
            System.out.print("Two ");
            break;
        case 3:
            System.out.print("Three ");
            break;
        default:
            System.out.print("Other ");
    }
    ```
    - A) One
    - B) Two
    - C) Three
    - D) Other


10. **What will be the output of the following code?**

    ```java
    String str1 = "AP";
    String str2 = "CS";
    String str3 = str1 + str2;
    System.out.println(str3);
    ```
    - A) AP
    - B) CS
    - C) APCS
    - D) AP CS


11. **What will be the output of the following code?**

    ```java
    int a = 5;
    if (a < 10) {
        if (a < 5) {
            System.out.println("Less than 5");
        } else {
            System.out.println("Greater than or equal to 5");
        }
    } else {
        System.out.println("10 or more");
    }
    ```
    - A) Less than 5
    - B) Greater than or equal to 5
    - C) 10 or more
    - D) None of the above


12. **What will be the output of the following code?**

    ```java
    String[] arr = {"A", "B", "C", "D"};
    for (int i = arr.length - 1; i >= 0; i--) {
        System.out.print(arr[i] + " ");
    }
    ```
    - A) A B C D
    - B) D C B A
    - C) D B A C
    - D) C B A D


13. **What is the result of the following code?**

    ```java
    boolean flag = true;
    if (!flag) {
        System.out.println("False");
    } else {
        System.out.println("True");
    }
    ```
    - A) False
    - B) True
    - C) Error
    - D) None of the above


14. **What will be the output of the following code?**

    ```java
    for (int i = 1; i <= 5; i++) {
        for (int j = 1; j <= i; j++) {
            System.out.print(j + " ");
        }
        System.out.println();
    }
    ```
    - A) 1 2 3 4 5
    - B) 1 2 3 4 5 1 2 3 4 5
    - C) 1
          1 2
          1 2 3
          1 2 3 4
          1 2 3 4 5
    - D) 1
          2
          3
          4
          5


15. **Which of the following is the correct way to declare a two-dimensional array in Java?**

    - A) `int[][] arr = new int[3][3];`
    - B) `int arr = new int[3][3];`
    - C) `int arr[][] = new int[3][3];`
    - D) Both A and C


16. **What will be the output of the following code?**

    ```java
    int[] arr = {1, 2, 3, 4, 5};
    int product = 1;
    for (int i = 0; i < arr.length; i++) {
        product *= arr[i];
    }
    System.out.println(product);
    ```
    - A) 15
    - B) 120
    - C) 60
    - D) 10


17. **What is the result of the following code segment?**

    ```java
    int[] arr = {5, 10, 15, 20};
    System.out.println(arr[1] + arr[3]);
    ```
    - A) 25
    - B) 30
    - C) 35
    - D) 40


18. **What will be the output of the following code?**

    ```java
    String str = "Hello World";
    System.out.println(str.substring(0, 5));
    ```
    - A) Hello World
    - B) Hello
    - C) World
    - D) ello


19. **What is the output of the following code?**

    ```java
    int x = 0;
    do {
        x++;
    } while (x < 5);
    System.out.println(x);
    ```
    - A) 4
    - B) 5
    - C) 6
    - D) 1

20. **Which of the following correctly checks if `num` is a multiple of both 3 and 5

?**

    ```java
    int num = 15;
    ```
    - A) `if (num % 3 == 0 || num % 5 == 0)`
    - B) `if (num % 3 == 0 && num % 5 == 0)`
    - C) `if (num % 3 == 1 && num % 5 == 1)`
    - D) `if (num % 3 == 1 || num % 5 == 1)`


21. **What will be the output of the following code?**

    ```java
    int[][] arr = {
        {1, 2, 3},
        {4, 5, 6},
        {7, 8, 9}
    };
    System.out.println(arr[1][2]);
    ```
    - A) 5
    - B) 6
    - C) 7
    - D) 8


22. **What will be the output of the following code?**

    ```java
    for (int i = 0; i < 10; i++) {
        if (i % 2 == 0) {
            continue;
        }
        System.out.print(i + " ");
    }
    ```
    - A) 0 2 4 6 8
    - B) 1 3 5 7 9
    - C) 2 4 6 8 10
    - D) 0 1 2 3 4 5 6 7 8 9


23. **What will be the output of the following code?**

    ```java
    String str = "AP Computer Science";
    System.out.println(str.indexOf('C'));
    ```
    - A) 0
    - B) 1
    - C) 3
    - D) 12


24. **What does the following method return?**

    ```java
    public static boolean isEven(int num) {
        return num % 2 == 0;
    }
    ```
    - A) True if the number is even
    - B) True if the number is odd
    - C) False if the number is even
    - D) None of the above


25. **What will be the output of the following code?**

    ```java
    for (int i = 5; i > 0; i--) {
        System.out.print(i + " ");
    }
    ```
    - A) 5 4 3 2 1
    - B) 4 3 2 1
    - C) 5 4 3 2 1 0
    - D) 4 3 2 1 0


26. **What is the output of the following code segment?**

    ```java
    int x = 1;
    int y = 2;
    if (x < y) {
        System.out.println("x is less than y");
    } else {
        System.out.println("x is greater than or equal to y");
    }
    ```
    - A) x is less than y
    - B) x is greater than or equal to y
    - C) x is less than or equal to y
    - D) x is greater than y


27. **What will be the output of the following code?**

    ```java
    int[] arr = {10, 20, 30, 40, 50};
    for (int i = arr.length - 1; i >= 0; i--) {
        System.out.print(arr[i] + " ");
    }
    ```
    - A) 10 20 30 40 50
    - B) 50 40 30 20 10
    - C) 50 40 30 20
    - D) 40 30 20 10


28. **What will be the output of the following code?**

    ```java
    int a = 5;
    int b = 10;
    int temp = a;
    a = b;
    b = temp;
    System.out.println("a: " + a + ", b: " + b);
    ```
    - A) a: 5, b: 10
    - B) a: 10, b: 5
    - C) a: 10, b: 10
    - D) a: 5, b: 5


29. **What will be the output of the following code?**

    ```java
    int sum = 0;
    for (int i = 1; i <= 5; i++) {
        if (i % 2 == 0) {
            continue;
        }
        sum += i;
    }
    System.out.println(sum);
    ```
    - A) 9
    - B) 10
    - C) 8
    - D) 15


30. **What is the output of the following code?**

    ```java
    int x = 10;
    while (x > 0) {
        System.out.print(x + " ");
        x -= 2;
    }
    ```
    - A) 10 8 6 4 2
    - B) 10 9 8 7 6 5 4 3 2 1
    - C) 10 8 6 4
    - D) 10 9 7 6 5 3 2 1


31. **What will be the output of the following code?**

    ```java
    int a = 10, b = 20, c = 30;
    System.out.println(a < b && b < c);
    ```
    - A) True
    - B) False
    - C) Error
    - D) None of the above


32. **What will be the output of the following code?**

    ```java
    String str = "abc";
    str += "def";
    System.out.println(str);
    ```
    - A) abc
    - B) def
    - C) abcdef
    - D) ab


33. **What will be the output of the following code?**

    ```java
    int[] arr = {1, 2, 3, 4, 5};
    System.out.println(arr[2]);
    ```
    - A) 1
    - B) 2
    - C) 3
    - D) 4


34. **What will be the output of the following code?**

    ```java
    int[] arr = new int[5];
    System.out.println(arr[0]);
    ```
    - A) 0
    - B) 1
    - C) Null
    - D) ArrayIndexOutOfBoundsException


35. **What will be the output of the following code?**

    ```java
    int num = 5;
    for (int i = 1; i <= num; i++) {
        if (i % 2 == 0) {
            System.out.print(i + " ");
        }
    }
    ```
    - A) 1 3 5
    - B) 2 4
    - C) 2 3 4
    - D) 1 2 3 4 5


36. **What will be the output of the following code?**

    ```java
    int a = 10;
    int b = 5;
    int max = (a > b) ? a : b;
    System.out.println(max);
    ```
    - A) 5
    - B) 10
    - C) 15
    - D) Error


37. **What will be the output of the following code?**

    ```java
    String str1 = "Java";
    String str2 = "Programming";
    System.out.println(str1 + " " + str2);
    ```
    - A) JavaProgramming
    - B) Java Programming
    - C) Java+Programming
    - D) Java+ Programming


38. **What will be the output of the following code?**

    ```java
    String str = "12345";
    int num = Integer.parseInt(str);
    System.out.println(num + 10);
    ```
    - A) 1234510
    - B) 12355
    - C) 13345
    - D) Error


39. **What will be the output of the following code?**

    ```java
    int num = 5;
    for (int i = 1; i <= num; i++) {
        System.out.print(i * i + " ");
    }
    ```
    - A) 1 4 9 16 25
    - B) 1 8 27 64 125
    - C) 1 2 3 4 5
    - D) 1 3



40. **What will be the output of the following code?**

    ```java
    String str = "Welcome";
    System.out.println(str.length());
    ```
    - A) 6
    - B) 7
    - C) 8
    - D) 9


41. **What will be the output of the following code?**

    ```java
    int a = 5;
    int b = 10;
    int sum = 0;
    for (int i = a; i <= b; i++) {
        sum += i;
    }
    System.out.println(sum);
    ```
    - A) 35
    - B) 40
    - C) 45
    - D) 50


42. **What will be the output of the following code?**

    ```java
    String str = "abcdef";
    System.out.println(str.substring(2, 5));
    ```
    - A) ab
    - B) cde
    - C) bcde
    - D) cdef


43. **What will be the output of the following code?**

    ```java
    int a = 3;
    int b = 4;
    int c = 5;
    System.out.println(a + b * c);
    ```
    - A) 23
    - B) 35
    - C) 12
    - D) 17


44. **What will be the output of the following code?**

    ```java
    int i = 0;
    while (i < 5) {
        System.out.print(i + " ");
        i++;
    }
    ```
    - A) 0 1 2 3 4
    - B) 1 2 3 4 5
    - C) 0 1 2 3 4 5
    - D) 1 2 3 4


45. **What will be the output of the following code?**

    ```java
    int x = 10;
    for (int i = 0; i < 3; i++) {
        x += i;
    }
    System.out.println(x);
    ```
    - A) 10
    - B) 11
    - C) 12
    - D) 13


46. **What will be the output of the following code?**

    ```java
    int num = 10;
    while (num > 0) {
        System.out.print(num + " ");
        num -= 3;
    }
    ```
    - A) 10 9 8 7 6 5 4 3 2 1
    - B) 10 7 4 1
    - C) 10 8 6 4 2
    - D) 10 6 3


47. **What will be the output of the following code?**

    ```java
    int[] arr = {1, 2, 3, 4, 5};
    int max = arr[0];
    for (int i = 1; i < arr.length; i++) {
        if (arr[i] > max) {
            max = arr[i];
        }
    }
    System.out.println(max);
    ```
    - A) 1
    - B) 3
    - C) 4
    - D) 5


48. **What will be the output of the following code?**

    ```java
    String str = "ABCDE";
    System.out.println(str.charAt(1));
    ```
    - A) A
    - B) B
    - C) C
    - D) D


49. **What will be the output of the following code?**

    ```java
    int[] arr = {1, 2, 3};
    int sum = 0;
    for (int i : arr) {
        sum += i;
    }
    System.out.println(sum);
    ```
    - A) 1
    - B) 2
    - C) 6
    - D) 7


50. **What will be the output of the following code?**

    ```java
    int a = 3;
    int b = 2;
    System.out.println(Math.pow(a, b));
    ```
    - A) 6.0
    - B) 9.0
    - C) 8.0
    - D) 5.0

