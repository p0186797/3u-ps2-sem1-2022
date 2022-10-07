# 3u-ps2-sem1-2022

Create a file called **base_three.py** and upload it to this repository. In that file, write a program that takes in one line from the user and 
outputs if the sequence represents a base 3 number.

A base 3 number is made of digts: 0, 1, 2 and should not start with 0.

**Sample Input 1**
```
1212121212121
```

**Sample Ouput 1**
```
yes
```

**Sample Input 2**
```
01212101012
```

**Sample Ouput 2**
```
no
```

**Sample Input 3**
```
1231323132436
```

**Sample Ouput 3**
```
no
```
---

Create a file called **astrology.py** and upload it to this repo.

Write a program that takes in the user's year of birth and outputs their spirt animal. Their spirit animal consists of an element (Metal, Fire, Wood, Water, Earth) and a domestic pet (Rabbit, Dog, Mouse, Cat, Bird).

To figure out your element, **look at the last digit of your birth year**.

- 0 or 1, your element is metal
- 2 or 3, your element is water
- 4 or 5, your element is wood
- 6 or 7, your element is fire
- 8 or 9, your element is earth

To figure out your domestic pet use the below chart.

|rabbit    |dog       |mouse     |cat       |bird      |
|----------|----------|----------|----------|----------|
|2008      |2009      |2010      |2011      |2012      |

This chart repeats every 5 years. For example, someone born in 2008 + 5 = 2013 is also a rabbit.

**Input Specifications**
```
1 line of input representing the year of birth
```

**Output Specifications**
```
1 line of output: element and zodiac animal with a space in between with all lower case
```

**Sample Input 1**
```
1999
```

**Sample Output 1**
```
earth dog
```

**Sample Input 2**
```
2020
```

**Sample Output 2**
```
metal mouse
```
---

Create a file called **password.py** and upload it to this repository. In that file, write a program that takes in one line from the user.

Your program checks if the line meets the following requirements:

1. It is at least 7 digits long.
2. It ends with a number.
3. It starts with a letter (upper or lower).
4. It contains at least one special character: !,@,#,$,%,^,&,*

**Sample Input 1**
```
1234567
```

**Sample Ouput 1**
```
no
```

**Sample Input 2**
```
a123456$
```

**Sample Ouput 2**
```
no
```

**Sample Input 3**
```
a12%34&643
```

**Sample Ouput 3**
```
yes
```
