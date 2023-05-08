Download Link: https://assignmentchef.com/product/solved-solvedunit-2-basics
<br>
Lab 2 â€“ Fundamental Data Types

1) Create a project and execute the program below. Each invocation of the println method outputs the result of an arithmetic expression. The first two println commands are followed by comments that describe the operations that occur in each expression. Modify the program by adding a print statement before each println statement that describes what arithmetic operations occur when evaluating the expression that is printed.

“`javapublic class Expressions{public static void main(String[] args){int a = 3;int b = 4;int c = 5;int d = 17;System.out.println((a + b)/ c);// 3 and 4 are added with sum 7// 7 is divided by 5 with quotient 1System.out.println(a + b / c);// 4 is divided by 5 with quotient 0// 3 is added to 0 with sum 3System.out.println(a++);System.out.println(a–);System.out.println(a + 1);System.out.println(d % c);System.out.println(d / c);System.out.println(d % b);System.out.println(d / b);System.out.println(d + a / d + b);System.out.println((d + a) / (d + b));System.out.println(Math.sqrt(b));System.out.println(Math.pow(a, b));System.out.println(Math.abs(-a));System.out.println(Math.max(a, b));}}“`

2) Suppose you have 5 1/2 gallons of milk and want to store them in milk jars that can hold up to 0.75 gallons each. You want to know ahead of time how many completely filled jars you will have. The following program has been written for that purpose. Create a Netbeans project and examine the output. What is wrong with it? Why? How can you fix it?

“`javapublic class MilkJarCalculator{public static void main(String[] args){double milk = 5.5; // gallonsdouble jarCapacity = 0.75; // gallonsint completelyFilledJars = milk / jarCapacity;System.out.println(completelyFilledJars);}}“`

3.1) What is the output of the following program? Why?

“`javapublic class AverageCalculator{public static void main(String[] args){int age1 = 18;int age2 = 35;int age3 = 50;int age4 = 44;double averageAge = (age1 + age2 + age3 + age4) / 4;System.out.println(averageAge);}}“`

3.2) Fix the program in Lab 2.3.1 so that it yields the correct result.