![College Logo](https://www.gndec.ac.in/logo.png)
#          **PROGRAMMING FOR PROGRAM SOLVING ESC-18105** 
##         **Sarvanshdeep Singh Sahota**
##         **Civil B2** 
##         **1914100**
#          **GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA**
##         **Department of Civil Engineering**

**1. To Store the of marks scored by students**
       
     #include<stdio.h>
     int main()
     {
       int i,n,marks;
       char name[30];
       printf("Enter the number of students:");
       scanf("%d",&n);
       for(i=1;i<=n;i++)
        {
           printf("Enter the name:",name);
           scanf("%s",name);
           printf("Enter marks:",marks);
           scanf("%d",&marks);
        }
        return 0;
     }

    Output:-
    Enter the number of students:4
    Enter the name:Sarvansh
    Enter the marks:6
    Enter the name:Sahil
    Enter the marks:7
    Enter the name:Ritik
    Enter the marks:8
    Enter the name:Manthan
    Enter the marks:9
**2. Program to add 2 numbers:-**

    #include<stdio.h>
    int main()
    {
       int a,b,c;
       printf("Enter the value of a:");
       scanf("%d",&a);
       printf("Enter the value of b:");
       scanf("%d",&b);
       printf("The sum of a and b is %d",c=a+b);
       return 0;
    }

    Output:-
     Enter the value of a:33
     Enter the value of b:56
     The sum of a and b is 89
**3. Program to print any table:-**

    #include<stdio.h>
    int main()
    {
       int x, y, z;
       printf("Enter the table you want to print:");
       scanf("%d",&x);
       for(y=1;y<=10;y++)
         {
           printf("\n%d x %d =%d\n",x,y,z=x*y);
         }
       return 0;
    }

    Output:-
     Enter the table you want to print:89
     89 x 1=89
     89 x 2=178
     89 x 3=267
     89 x 4=356
     89 x 5=445
     89 x 6=534
     89 x 7=623
     89 x 8=712
     89 x 9=801
     89 x 10=890
**4. Program to print hello world**

    #include<stdio.h>
    int main()
    {
       puts("_____________");
       puts("|Hello World"|);
       puts("_____________");
    }

    Output:-
    _____________
    |Hello World|
    _____________
**5. To print PPS Using puts:-**

    #include<stdio.h>
    int main()
    {
       puts("PPPPP    PPPPP      SSSS  ");
       puts("P    P   P    P    S      ");
       puts("P     P  P     P  S       ");
       puts("P    P   P    P    S      ");
       puts("PPPPP    PPPPP      SSS   ");
       puts("P        P             S  ");
       puts("P        P              S ");
       puts("P        P             S  ");
       puts("P        P         SSSS   ");
    } 
    Output:-
    PPPPP    PPPPP     SSSS
    P    P   P    P   S
    P     p  P     P S
    P    p   P    P   S
    PPPPP    PPPPP     SSS
    P        P            S
    P        P             S
    P        P            S
    P        P        SSSS
**6. Program to print a calcuator:-**

    #include<stdio.h>
    int main()
    {
        puts("\n\
             _______________\n\
            | 1 | 2 | 3 |   |\n\
            |___|___|___|   |\n\
            | 4 | 5 | 6 | + |\n\
            |___|___|___|___|\n\
            | 7 | 8 | 9 | - |\n\
            |___|___|___|___|\n\
            |     0     | * |\n\
            |___________|___|\n");
    }
    Output:-
     _______________
    | 1 | 2 | 3 |   |
    |___|___|___|   |
    | 4 | 5 | 6 | + |
    |___|___|___|___|
    | 7 | 8 | 9 | - |
    |___|___|___|___|
    |     0     | * |
    |___________|___|
**7. To print a face using puts:-**

    #include<stdio.h>
    int main()
    {
        puts("         OOOOOOOO        ");
        puts("        O ^   ^  O       ");
        puts("       O  -   -   O      ");
        puts("      O            O     ");
        puts("     O      ^       O    ");
        puts("      O            O     ");
        puts("       O  -----   O      ");
        puts("        O        O       ");
        puts("         OOOOOOOO        ");
    }
    Output:-
         OOOOOOOO     
        O ^   ^  O
       O  -   -   O
      O            O
     O      ^       O
      O            O
       O  -----   O
        O        O 
         OOOOOOOO
         
**8. To Identify prime numbers:-**

    #include<stdio.h>
    int main()
    {
        int i, n, count=0;
        printf("Enter the Number:");
        scanf("%d",&n);
        for(i=1;i<=n;i++)
        {
           if(n%i==0)
            {
               count ++;
            }
        }
        if(count==2)
           printf("Its a Prime Number");
        else
           printf("Its not a prime Number");
    }
    Output:-
    Enter the number:23
    Its a Prime Number
**9. Program of Multiplication of 2x2 Matrix**
  
    #include<stdio.h>
    int main()
    {
       float a,b,c,d,e,f,g,h,i,j,k,l;

       printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
       Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

       printf("Enter The Valve of a: ");
       scanf("%f",&a);
       printf("Enter The Valve of b: ");
       scanf("%f",&b);
       printf("Enter The Valve of c: ");
       scanf("%f",&c);
       printf("Enter The Valve of d: ");
       scanf("%f",&d);
       printf("Enter The Valve of e: ");
       scanf("%f",&e);
       printf("Enter The Valve of f: ");
       scanf("%f",&f);
       printf("Enter The Valve of g: ");
       scanf("%f",&g);
       printf("Enter The Valve of h: ");
       scanf("%f",&h); 

       i=(a*e)+(b*g);
       j=(a*f)+(b*h);
       k=(c*e)+(d*g);
       l=(c*f)+(d*h);

       printf("\nMultiplication of A,B is: | %.2f     %.2f |\n                          | %.2f     %.2f |",i,j,k,l);

       return 0;
    }

    Output:-
    Sample of Ist matrix: | a=1      b=2 |
                          | c=3      d=4 |

    Sample of 2nd matrix: | e=5      f=6 |
                          | f=7      h=8 |

    Enter The Valve of a: 5 
    Enter The Valve of b: 6
    Enter The Valve of c: 7
    Enter The Valve of d: 3
    Enter The Valve of e: 2
    Enter The Valve of f: 3
    Enter The Valve of g: 3
    Enter The Valve of h: 5

    Multiplication of A,B is: | 28.00     45.00 |
                              | 23.00     36.00 |
**10. Program to multily 2 numbers using Function:-**

    #include<stdio.h>
    float guna(float a, float b);
    int main()
    {
        float a, b, multi;
        printf("Enter the 1st Value:");
        scanf("%f",&a);
        printf("Enter the 2nd Value:");
        scanf("%f",&b);
        multi=guna(a,b);
        printf("Multiplication of a and b is%.3f", multi);
        return 0;
    }
    float guna(float a, float b)
       {
          return a*b;
       }

    Output:-
    Enter the 1st Value:5
    Enter the 2nd Value:4
    Multiplication of a and b is 20.000

**11. Program to find Area of the Circle:-**
    
    #include<stdio.h>
    int main()
    {
        float r, A;
        float pi = 22/7;
        printf("Enter the Radius of Circle:");
        scanf("%f",&r);
        A = pi*r*r;
        printf("Area of Circle is %.3f",A);
        return 0;
    }
    Output:-
    Enter the Radius of Circle:4
    Area of Circle is 48.000

**12. Program to Find Average of Three numbers:-**

    #include<stdio.h>
    int main()
    {
        float a, b, c, d;
        printf("Enter the value of a:");
        scanf("%f",&a);
        printf("Enter the value of b:");
        scanf("%f",&b);
        printf("Enter the value of c:");
        scanf("%f",&c);
        printf("The average of a, b and c is %.2f",d=(a+b+c)/3);
        return 0;
    }
    Output:-
    Enter the value of a:6
    Enter the value of b:9    
    Enter the value of c:19
    The average of a, b and c is 11.33

**13. Program which can find the maximum among 2 numbers:-**

    #include<stdio.h>
    int main()
    {
        float a, b;
        printf("Enter the 1st number:",a);
        scanf("%f",&a);
        printf("Enter the 2nd number:",b);
        scanf("%f",&b);
        if(a>b)
        {
            printf("%.2f is greater than %.2f",a, b);
        }
        else
        {
            printf("%.2f is greater than %.2f",b, a);
        }
        return 0;
    }
    Output:-
    Enter the 1st number:45.32
    Enter the 2nd number:45.48
    45.48 is greater than 45.32

**14. Program which can find the maximum among 3 numbers:-** 

    #include<stdio.h>
    int main()
    {
        float a, b, c;
        printf("Enter the 1st number:",a);
        scanf("%f",&a);
        printf("Enter the 2nd number:",b);
        scanf("%f",&b);
        printf("Enter the 3rd number:",c);
        scanf("%f",&c);
        if(a>b&&a>c)
        {
            printf("%.2f is greater among these three",a);
        }
        else if(b>c)
        {
            printf("%.2f is greater among these three",b);
        }
        else
        {
            printf("%.2f is greater among these three",c);
        }
        return 0;
    } 
    Output:-
    Enter the 1st number:26.56
    Enter the 2nd number:26.45
    Enter the 3rd number:26.89
    26.89 is greater among these three

**15. Program to solve fizz buzz program:-**

    #include<stdio.h>
    int main()
    {
        int n;
        printf("Enter the integer:",n);
        scanf("%d",&n);
        if(n%3==0 && n%5==0)
        {
            printf("Its FizzBuzz");
        }
        else if(n%3==0)
        {
            printf("Its Fizz");
        }
        else if(n%5==0)
        {
            printf("Its Buzz");
        }
        else
        {
            printf("%d",n);
        }
        return 0;
    }
    Output:- 
    Enter the integer:45
    Its FizzBuzz

**16. Program of addition of 2x2 matrix:-**

    #include<stdio.h>
    int main()

    {
         float a,b,c,d,e,f,g,h,i,j,k,l;

         printf("\nSample of Ist matrix: | a=1      b=2 |\n                      | c=3      d=4 |\n\n\
         Sample of 2nd matrix: | e=5      f=6 |\n                      | f=7      h=8 |\n\n");

         printf("Enter The Valve of a: ");
         scanf("%f",&a);
         printf("Enter The Valve of b: ");
         scanf("%f",&b);
         printf("Enter The Valve of c: ");
         scanf("%f",&c);
         printf("Enter The Valve of d: ");
         scanf("%f",&d);
         printf("Enter The Valve of e: ");
         scanf("%f",&e);
         printf("Enter The Valve of f: ");
         scanf("%f",&f);
         printf("Enter The Valve of g: ");
         scanf("%f",&g);
         printf("Enter The Valve of h: ");
         scanf("%f",&h);

         i = a+e;
         j = b+f;
         k = c+g;
         l = d+h;
         printf("Sum of Matrix(A+B) is | %.2f     %.2f |\n                       | %.2f     %.2f |",i,j,k,l);
         return 0;
    }
    Output:-
    Sample of Ist matrix: | a=1      b=2 |
                          | c=3      d=4 |

    Sample of 2nd matrix: | e=5      f=6 |
                          | f=7      h=8 |

    Enter The Valve of a: 4 
    Enter The Valve of b: 2
    Enter The Valve of c: 8
    Enter The Valve of d: 3
    Enter The Valve of e: 3
    Enter The Valve of f: 6
    Enter The Valve of g: 3
    Enter The Valve of h: 7
    
    Sum of Matrix(A+B) is |7.00      8.00|
                          |11.00     10.00|

**17. Program of Fizz buzz in loop:-**

    #include<stdio.h>
    int main()
    {
        int n,i;
        printf("Enter The Integer:");
        scanf("%d",&n);
        for(i=1;i<=n;i++)
        {
           if(i%3==0 && i%5==0)
           printf("Its FizzBuzz\n");
           else if(i%3==0)
           printf("Its Fizz\n");
           else if(i%5==0)
           printf("ITs Buzz\n");
           else
           printf("%d\n",i);
        }
        return 0;
    }
    Output:-
    Enter The Integer:20
    1
    2
    Its Fizz
    4
    Its Buzz
    Its Fizz
    7 
    8
    Its Fizz 
    Its Buzz
    11
    Its Fizz
    13
    14
    Its FizzBuzz
    16
    17
    Its Fizz
    19
    Its Buzz

**18. Program of while loop:-**

    #include<stdio.h>
    int main()
    {   
       int x=1;
       while(x<=10)
       {
           printf("%d\n",x);
           x++;  
       }
       return 0;
    }
    Output:-
    1
    2 
    3
    4
    5
    6
    7 
    8
    9
    10

**19. Program to Multiply two Floating Point Numbers:-**

    #include<stdio.h>
    int main()
    {
        float a, b, c;
        printf("Enter the first value:",a);
        scanf("%f",&a);
        printf("Enter the second value:",b);
        scanf("%f",&b);
        c=a*b;
        printf("The Multiplication of two Floating Point Numbers is %.2f",c);
        return 0;
    }
    Output:-
    Enter the first value:2.5
    Enter the second value:1.6
    The Multiplication of two Floating Point Numbers is 4.00

**20. Program to Check Whether a Number is Even or Odd using if else statement:-**

    #include<stdio.h>
    int main()
    {
        int a;
        printf("Enter any number:");
        scanf("%d",&a);
        if(a%2==0)
        {
            printf("%d is an even number",a);
        }
        else
        {
            printf("%d is an odd number",a);
        }
    }
    Output:-
    Enter any number:100
    100 is an even number
    
**21. Program to take 5 values from the user and store them in an array and Print the elements stored in the array:-**

    #include<stdio.h>
    int main()
    {
        int x,array[5];
        printf("\n");
        for(x=1;x<=5;x++)
        {
           printf("Enter [%d] element: ", x);
           scanf("%d", &array[x]); 
        }
        for(x=1;x<=5;x++)
        {
           printf("\nElement [%d] = %d", x, array[x]); 
        }
    return 0;
    }
    Output:-

    Enter [1] element: 4
    Enter [2] element: 5
    Enter [3] element: 6
    Enter [4] element: 9
    Enter [5] element: 2

    Element [1] = 4
    Element [2] = 5
    Element [3] = 6
    Element [4] = 9
    Element [5] = 2
    
**22. Program to print Fibbonacci Series:-**

    #include<stdio.h>
    int fibbo(int f);
    int main()                                                                      
    {
       int x,i,f=0;
       printf("\nEnter fibbonacci Number: ");
       scanf("%d", &x);
       for(i=1; i<=x; i++)
       { 
           printf("%d\n", fibbo(f));
           f++;
       }
    return 0;
    }

    int fibbo(int f)
    {
       if(f==1 || f==0)
       return f;
       else
       return ( fibbo(f-1) + fibbo(f-2) );
    }
    Output:-
    Enter fibbonacci Number: 10
    0
    1
    1 
    2    
    3    
    5    
    8
    13
    21
    34
**23. Program swap two numbers using call by value:-**

    #include <stdio.h>
    int main()
    {
        int x, y, t;
        printf("\n\nEnter two integers: ");
        scanf("%d %d", &x, &y);
        printf("\n\nBefore Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
        t = x;
        x = y;
        y = t;
        printf("\n\nAfter Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
        return 0;
    }
    Output:-
    Enter two integers: 1  56

    Before Swapping:
    First integer = 1
    Second integer = 56

    After Swapping:
    First integer = 56
    Second integer = 1
    
**24. Program swap two numbers using call by reference:-**

    #include <stdio.h>
    void swap(int*, int*);
    int main()
    {
        int x, y;
        printf("\nEnter the two integers: ");
        scanf("%d %d", &x, &y);
        printf("\nBefore Swapping\nx = %d\ny = %d", x, y);
        swap(&x, &y);
        printf("\nAfter Swapping\nx = %d\ny = %d", x, y);
        return 0;
    }
    void swap(int *a, int *b)
    {
        int temp;
        temp = *b;
        *b = *a;
        *a = temp;  
    }
    Output of the program
    Enter the two integers: 45 98
    Before Swapping
    x = 45
    y = 98
    After Swapping
    x = 98
    y = 45

**25. Program to implement Linear search for One Dimensional array:-**

    #include<stdio.h>
    int main()
    {
       int array[12]={1,5,9,7,3,82,46,23,23,5,10,3};
       int size=12,flag=0,item,a;
       printf("\nEnter the Value: ");
       scanf("%d", &a);
       for(int i=0;i<size;i++)
       {
          if(a==array[i])
          {
                flag=a;
                break;
          }
       }
      
       if(flag==a)
       printf("\nSearch is Sucessfull \n%d Element is present in the array\n",a);
       else
       printf("\nSearch is Unsucessfull \n%d Element is not present in the array\n",a);
       return 0;
    }
    Output of the program
    First Case
    Enter the Value to be searched: 5
    Search is Sucessfull 5 Element is present in the array
    Second Case
    Enter the Value to be searched: 2
    Search is Unsucessfull 2 Element is not present in the array
    
**26. Program to print Even numbers using while loop:-**

    #include<stdio.h>
    int main()
    {
       int x=1,N;
       printf("\n\nEntere the Integer: ");
       scanf("%d", &N);
       while(x<=N)
      {
         if(x%2==0)
         printf("\n%d", x);
         else
         printf("");
         x++;
      }
    return 0;
    }
    Output:-
    Entere the Integer: 10
    2
    4
    6
    8  
    10

**27.  Program to print Odd numbers using do while loop:-**

    #include<stdio.h>
    int main()
    {
       int x=1,N;
       printf("\n\nEntere the Integer: ");
       scanf("%d", &N);
       do
       {
           if(x%2!=0)
           printf("\n%d", x);
           else
           printf("");
           x++;
       }
       while(x<=N);
    return 0;
    }
    Output:-
    Enter the Integer: 13
    1
    3
    5
    7
    9
    11
    13

**28. Program of a Simple Calculator:-**

    #include<stdio.h>
    int main()
    {
       char operator;
       float x,y;
       printf("\n\nEnter an operator (+, -, *, /): ");
       scanf("%c", &operator);
       printf("Enter two operands: ");
       scanf("%f %f", &x, &y);
       switch(operator)
       {
            case '+':
            printf("\n%.2f + %.2f = %.2f", x, y, x+y);
            break;
            case '-':
            printf("\n%.2f - %.2f = %.2f", x, y, x-y);
            break;
            case '*':
            printf("\n%.2f * %.2f = %.2f", x, y, x*y);
            break;
            case '/':
            printf("\n%.2f / %.2f = %.2f", x, y, x/y);
            break;
            default:
            printf("\nError! operator is not correct");
       }
    return 0;
    }
    Output:-
    Enter an operator (+, -, *, /): *
    Enter two operands: 146  21
    146.00 * 21.00 = 3066.00

**29. Program to implement Bubble Sort:-**

    #include <stdio.h>
    int main()
    {
       int array[100], n, c, d, swap;
       printf("Enter number of elements: ");
       scanf("%d", &n);
       printf("Enter %d integers\n", n);
       for (c=0; c<n; c++)
       scanf("%d", &array[c]);
       for (c=0; c<n-1; c++)
       {
          for (d=0 ; d<n-c-1; d++)
          {
             if (array[d] > array[d+1])
             {
                swap       = array[d];
                array[d]   = array[d+1];
                array[d+1] = swap;
             }
          }
       }
       printf("Sorted list in ascending order:\n");
       for (c=0; c<n; c++)
       printf("%d\n", array[c]);
    return 0;
    }
    Output:-
    Enter number of elements: 6
    Enter 6 integers
    1     
    2      
    3       
    8       
    9     
    1   
    Sorted list in ascending order:
    1
    1 
    2
    3 
    8    
    9

**30. Program to find Factorial:-**

    #include<stdio.h>
    long factorial(int);
    int main()
    { 
       int x;
       long fact = 1;
       printf("\nEnter a number to calculate it's factorial: ");
       scanf("%d", &x);
       printf("%d! = %ld\n", x, factorial(x));
       return 0;  
       long factorial(int x)
       {
          int c;
          long ans=1;
          for (c=x; c>1; c--)
          { 
             ans *= c;
          }
             return ans;
    }
    Output:-
    Enter a number to calculate it's factorial: 6
    6! = 720
    Enter a number to calculate it's factorial: 12
    12! = 479001600
    
**31. Program to Store Information of a Student using Structure:-**

    #include<stdio.h>
    struct student
    {
       char name[50];
       long int ph,marks;
    };
    int main()
    {
       int i,N;
       printf("\nEnter the information of student: \n");
       struct student s;
       printf("Enter Name: ");
       scanf("%s", &s.name);
       printf("Enter Phone Number: ");
       scanf("%ld", &s.ph);
       printf("Enter Marks: ");
       scanf("%d", &s.marks);
       printf("\nEntered Information is: \n");
       printf("Name: %s\n", s.name);
       printf("Age: %ld\n", s.ph);
       printf("Marks: %d\n", s.marks);
       return 0;
    }
    Output:-
    Enter the information of student: 
    Enter Name: Sarvanshdeep Singh Sahota
    Enter Phone Number: 9877703007
    Enter Marks: 60

    Entered Information is: 
    Name: Sarvanshdeep Singh Sahota
    Age: 18
    Marks: 60
