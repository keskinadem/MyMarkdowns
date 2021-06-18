---
modified: 2021-06-18T18:08:16+03:00
---

# Python

## Important features
| Features | Benefit |
| ------ | ----------- |
| no compiling or linking   | rapid development cycle |
| no type declarations   | simpler, shorter, more flexible |
| automatic memory management   | garbage collection |
| high-level data types and 
operations   | fast development |
| object-oriented programming   | code structuring and reuse, C++ |
| embedding and extending in C   | mixed language systems |
| classes, modules, exceptions   | "programming-in-the-large" support |
| dynamic loading of C modules   | simplified extensions, smaller binaries |
| dynamic reloading of C modules   | programs can be modified without stopping |
  

 Many languages require you to compile (translate) your 
program into a form that the machine understands.  
Python is instead directly interpreted into machine instructions.

## Math commands

>  Some built-in commands to perform scientific calculations:

>>  To use many of these commands, you must write the following at the top 
of your Python program:  
**from math import***

| Command Name | Description |
| ------ | ----------- |
| abs(value)   | absolute value |
| ceil(value) | rounds up |
| cos(value)   | cosine, in radians |
| floor(value)   | rounds down |
| log(value) | logarithm, base e |
| max(value1, value2)   | larger of two values |
| min(value1, value2)   | smaller of two values |
| round(value) | nearest whole number |
| sqrt(value)   | square root |

## print:
Produces text output on the console.  
  
### Example:

``` js
print ("Hello, world!”)
age = 25
print ("You have", 65 - age, "years until retirement”)
```

## input:
 Reads a number from user input.  
 
 ``` js
age = input("How old are you? ")
print ("Your age is", age)
print ("You have", 65 – int(age), "years until retirement”)
``` 

#### output:
```
How old are you? 25
Your age is 25
You have 40 years until retirement
```

## range:
> The range functions specifies a range of integers
>> range(start, stop)  -The integers between start(inclusive) and stop(exclusive)  
>> It can also accept a third value specifying the change between values.
>> range(start, stop, step) - the integers between start (inclusive) and stop (exclusive) by step

### Example:

 ``` js
for x in range(5, 0, -1):
    print (x)
print ("Blastoff!”)
``` 

**Pay attention to the "indent" used in for loop!!!!**

## for loop:
> The range functions specifies a range of integers
>> Syntax:  
>> for *variableName* in *groupOfValues:*
>>> We indent the statements to be repeated with tabs or spaces.  
>>> *variableName* gives a name to each value, so you can refer to it in the statements.  
>>> *groupOfValues* can be a range of integers, specified with *range* function.

#### Example:

 ``` js
for x in range(1, 6):
    print (x, "squared is", x * x)
``` 

#### output:
```
1 squared is 1
2 squared is 4
3 squared is 9
4 squared is 16
5 squared is 25
```
