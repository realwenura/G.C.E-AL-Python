## Practical 1

### Printing function
	
#### _Input_
```py
print("AL ICT 2023")
print("my name is Wenura")
print("my school is SBC")
print('my country is Sri lanka')
print('Nimal said" he likes ice cream"')
print('"Nimal said" he likes ice cream""')
```

#### _Output_
	AL ICT 2023
	my name is Wenura
	my school is SBC
	my country is Sri lanka
	Nimal said" he likes ice cream"
	"Nimal said" he likes ice cream""
	
## Practical 2

### Join two strings (concatenate)

#### _Input_
```py
print("nimal"+"kaml")
print("nimal","kaml")
#print("nimal"."kaml") #dot will show invalid syntax
#this is a comment
print("nimal\n kaml") 
print("nimal\t kaml")
print("nimal\t\tkaml")
```
#### _Output_
	nimalkaml
	nimal kaml
	nimal
	 kaml
	nimal	 kaml
	nimal		kaml
	
## Practical 3

### Variables

#### _Input_
```python
x=input("Name:")#user input
print("Name is",x)

y=input("Age:")#user input
print("Age is",y)

z=input("School:")#user input
print("School is",z)

p=input("Address:")#user input
print("Address is",p)
```

#### _Output_
	
	Name:Wenura
	Name is Wenura
	Age:18
	Age is 18
	School:SBC
	School is SBC
	Address:119 @ Colombo
	Address is 119 @ Colombo
	
## Practical 4

### Casting int() float()

#### _Input_

```python
#we can input only integers for C and F

A=input("What is you name:") #string,int,float

B=input("what is your age:") #string,int,float

C=int(input("maths marks:")) #can't insert float and string

F=float(input("ICT marks")) #can iinput float or integer

#if we insert integer for float the output result with decimal as #float
#since they ask float and we input int,then int will convert to #float and print

print("I'm",A,"my ICT mark",C,"My maths mark",F)
```

#### _Output_
```
What is you name:Wenura
what is your age:18
maths marks:80
ICT marks80
I'm Wenura my ICt mark 80 My maths mark 80.0
```

## Practical 5

### string arrays

#### _Input_
```py
x="school"
print(x)#school
print(x[0])#s
print(x[1])#c
print(x[2])#h
print(x[3])#o
print(x[4])#o
print(x[5])#l


print(x[-1])#l
print(x[-2])#o
print(x[-3])#o
print(x[-4])#h
print(x[-5])#c
print(x[-6])#s
```

#### _Output_
```
school
s
c
h
o
o
l
l
o
o
h
c
s
```

## Practical 6

#### _Input_

```py
x="school"
print(x[0])#s
print(x[0:1])#s
print(x[0:2])#sc
print(x[0:3])#sch
print(x[0:4])#scho
print(x[0:5])#schoo
print(x[0:6])#school
print(x[0:7],"\n")#school

y="school is SJC"
print(y[0:8])#school i
print(y[0:9])#school is
print(y[0:10])#school is
print(y[0:11])#school is s
print(y[0:12])#school is SJ
print(y[0:13])#school is SJC
print(y[0:20],"\n")#school is SJC


z="school_is_SJC"
print(y[0:13])#school is SJC
print(y[0:13:1])#school is SJC
print(y[0:13:2])#sho_sSC
print(y[0:13:3])#so__C
print(y[0:13:4])#sosC
print(y[0:13:5])#slS
print(y[0:13:6])#s_C
print(y[0:13:7])#si
print(y[0:13:8])#ss
print(y[0:13:9])#s_
print(y[0:13:10])#sS
print(y[0:13:11])#sJ
print(y[0:13:12])#sC
print(y[0:13:13])#s
```
#### _Output_

```
s
s
sc
sch
scho
schoo
school
school 

school i
school is
school is 
school is S
school is SJ
school is SJC
school is SJC 

school is SJC
school is SJC
sho sSC
so  C
sosC
slS
s C
si
ss
s 
sS
sJ
sC
s
```
## Practical 6

#### _Input_
```py
b="colombo"
c=b.replace("o","a")
print(c)#calambo

#multiply the input values
x=input("enter your name")#ICT
print(x*3)#ICTICTICT

#add the value
print(x+x)#ICTICTICT
```
#### _Output_
```
calamba
enter your nameWenura
WenuraWenuraWenura
WenuraWenura
```
## Practical 7

#### _Input_
```py
A=input("What is you name:")
F=int(input("maths marks:"))
C=int(input("ICT marks"))
B=input("What is your best friends name")
E=float(input("Friends maths marks"))
D=float(input("Friends ICT marks"))
tot1=F+C
tot2=E+D

print("My name is",A)
print(A,"ICT marks",C)
print(A,"maths marks",F)
print(A,"best friend is",B)
print(B,"maths marks",E)
print(B,"ICT marks",D)
print(A,"Total=",tot1)
print(B,"Total=",tot2)
```
#### _Output_
```
What is you name:Wenura
maths marks:80
ICT marks80
What is your best friends nameRavindu
Friends maths marks80
Friends ICT marks80
My name is Wenura
Wenura ICT marks 80
Wenura maths marks 80
Wenura best friend is Ravindu
Ravindu maths marks 80.0
Ravindu ICT marks 80.0
Wenura Total= 160
Ravindu Total= 160.0
```
## Practical 8

#### _Input_

```py
#1_initialize inpt data string
x=input("what is your name?")
y=input("where do you live?")

#recall string using varaiable
print("myname is"+x+"I live in"+y)
print("myname is %s I live in %s"%(x,y))
print("myname is %s I live in %s"%(y,x))
```
#### _Output_
```
what is your name?Wenura
where do you live?Wattala
myname isWenuraI live inWattala
myname is Wenura I live in Wattala
myname is Wattala I live in Wenura
```
## Practical 9

#### _Input_

```py
a="Hello, world!"
print(len(a))

#strip() method
a="             Hello, world!            "
print(a.strip())

#lower() method
a="Hello, world!"
print(a.lower())

#upper() method
a="Hello, world!"
print(a.upper())

#split() method
a="Apple,Cake,Banana,Chocolate,ice-cream"
b=a.split(",")
print(b)

A="Apple/Cake/Banana/Chocolate/ice-cream"
c=A.split("/")
print(c)

B="Apple Cake Banana   Chocolate ice-cream"
c=B.split(" ")
print(c)

A="Apple/Cake/Banana/Chocolate/ice-cream"
c=A.split("o")
print(c)

#in
txt="the rain in spain stays mainly in the plain"
x="ain"in txt
print(x)#true
x="123"in txt
print(x)#false

#not in
txt="the rain in spain stays mainly in the plain"
x="ain"not in txt
print(x)#false
x="  "not in txt
print(x)#true
```
#### _Output_
```
13
Hello, world!
hello, world!
HELLO, WORLD!
['Apple', 'Cake', 'Banana', 'Chocolate', 'ice-cream']
['Apple', 'Cake', 'Banana', 'Chocolate', 'ice-cream']
['Apple', 'Cake', 'Banana', '', '', 'Chocolate', 'ice-cream']
['Apple/Cake/Banana/Ch', 'c', 'late/ice-cream']
True
False
False
True
```
## Practical 10

### Arithmetic operators

#### _Input_

```py
x=10
y=3
print("addition=",(x+y))
print("substraction=",(x-y))
print("multiplication=",(x*y))
print("division=",(x/y))#output is a float
print("exponentiation=",(x**y))
print("floor division=",(x//y))
```
#### _Output_
```
addition= 13
substraction= 7
multiplication= 30
division= 3.3333333333333335
exponentiation= 1000
floor division= 3
```
## Practical 11

### Assignment operators

#### _Input_
```py
x=5
print("x=",x)

x=5
x-=3
print("x=",x)

x=5
x+=3
print("x=",x)

x=5
x*=3
print("x=",x)

x=5
x/=3
print("x=",x)

x=5
x%=3
print("x=",x)

x=5
x//=3
print("x=",x)

x=5
x**=3
print("x=",x)

x=5
x&=3
print("x=",x)

x=5
x|=3
print("x=",x)

x=5
x^=3
print("x=",x)

x=5
x>>=3
print("x=",x)

x=5
x<<=3
print("x=",x)
```
#### _Output_
```
x= 5
x= 2
x= 8
x= 15
x= 1.6666666666666667
x= 2
x= 1
x= 125
x= 1
x= 7
x= 6
x= 0
x= 40
```
## Practical 12

### Comparison operators

#### _Input_

```py
x=5
y=3
print(x==y)#false

x=5
y=-5
print(x==y)#false

x=5
y=5 
print(x==y)#true

x=5
y=5.00 #float
print(x==y)#true

x=5
y="5" #string
print(x==y) #false different data types with same value

x=5
y=3
print(x!=y)#true
print(x>y)#true
print(x<y)#false
print(x>=y)#true
print(x<=y)#false
```
#### _Output_
```
False
False
True
True
False
True
True
False
True
False
```
## Practical 13

### Logical operators

#### _Input_
```py
x=5
print(x>3 and x<10)
print(x>3 or x<4)
print(not(x>3 and x<10))
```
#### _Output_
```
True
True
False
```
## Practical 14

### Identity operators

```py
x=["apple","banana"]
y=["orange","grapes"]
z=x
print(x is z)#true
print(x is y)#false
print(x == y)#false

print(x is not z)#false
print(x is       not y)#true
print(x != y)#true
```
#### _Output_
```
True
False
False
False
True
True
```

## Practical 15

### Membership operators

#### _Input_

```py
x=["apple","banana"]
print("banana" in x) #true
print("pineapple" in x) #false

print("pineapple" not   in x)#true
print("apple" not in x) #false

```
#### _Output_
```
True
False
True
False
```

## Practical 16

### Bitwise operators 

#### _Input_
```py
a=60   #60=00111100
b=13   #13=00001100
c=0

#Bitwise AND
c=a&b #12=00001100
print("Bitwise AND value of c is:",c)

#Bitwise OR
c=a|b #61=00111101
print("Bitwise OR value of c is:",c)

#Bitwise XOR
c=a^b #49=00110001
print("Bitwise XOR value of c is:",c)

#Bitwise NOT
c=~a #-51=11000011
print("Bitwise NOT value of c is:",c)

#Left shift
c=a<<2 #240=11110000
print("Left shift  value of c is:",c)

#Right shift
c=a>>2 #15=00001111
print("Right shift  value of c is:",c)

print(~2)
```
#### _Output_
```
Bitwise AND value of c is: 12
Bitwise OR value of c is: 61
Bitwise XOR value of c is: 49
Bitwise NOT value of c is: -61
Left shift  value of c is: 240
Right shift  value of c is: 15
-3
```
## Practical 17

### For loop

#### _Input_
```py
for x in range(1,6):
    print(x)
print("finish")
```
#### _Output_
```
1
2
3
4
5
finish
```
## Practical 18

#### _Input_

```py
for x in range(200,301):
    print(x)
print("finish")
```
#### _Output_
```
200
201
202
203
204
205
206
207
208
209
210
211
212
213
214
215
216
217
218
219
220
221
222
223
224
225
226
227
228
229
230
231
232
233
234
235
236
237
238
239
240
241
242
243
244
245
246
247
248
249
250
251
252
253
254
255
256
257
258
259
260
261
262
263
264
265
266
267
268
269
270
271
272
273
274
275
276
277
278
279
280
281
282
283
284
285
286
287
288
289
290
291
292
293
294
295
296
297
298
299
300
finish
```
## Practical 19

#### _Input_
```py
for x in range (1,11,2):
    print(x)
print("finish")
 ```
#### _Output_
```
1
3
5
7
9
finish
```
## Practical 20

#### _Input_

```py
for x in range (0,37,3):
    print(x)
print("finish")
```

#### _Output_

```
0
3
6
9
12
15
18
21
24
27
30
33
36
finish
```
## Practical 21

#### _Input_

```py
for x in range(100,1,-2):
    print(x)
print("finish")
```

#### _Output_

```
100
98
96
94
92
90
88
86
84
82
80
78
76
74
72
70
68
66
64
62
60
58
56
54
52
50
48
46
44
42
40
38
36
34
32
30
28
26
24
22
20
18
16
14
12
10
8
6
4
2
finish
```
## Practical 22

#### _Input_

```py
for x in range(50,-1,-5):
    print(x)
print("finish")
```

#### _Output_
```
50
45
40
35
30
25
20
15
10
5
0
finish
```

## Practical 23

#### _Input_
```py
for x in range(300,199,-2):
    print(x)
print("finish")
```
#### _Output_
```
300
298
296
294
292
290
288
286
284
282
280
278
276
274
272
270
268
266
264
262
260
258
256
254
252
250
248
246
244
242
240
238
236
234
232
230
228
226
224
222
220
218
216
214
212
210
208
206
204
202
200
finish
```
## Practical 24

#### _Input_
```py
animals=["cat","dog","fish"]
for a in animals :
    print(a)
```

#### _Output_
```
cat
dog
fish
```
## Practical 25

#### _Input_
```py
n1=int(input("input n1"))
n2=int(input("input n2"))
if(n1<n2):
    
    for x in range(n1,n2,1):
         
         if(x%2==0):
             print(x)
else:
    
 print("invalid input")
 ```

#### _Output_

```
input n112
input n223
12
14
16
18
20
22
```
## Practical 26

#### _Input_

```py
n=int(input("enter number of students"))
for x in range(n):
   
    i=input("enter index no-")
    m=input("enter name-")
    a=int(input("subject 1-"))
    b=int(input("subject 2-"))
    c=int(input("subject 2-"))
    t=(a+b+c)
    av=t/3
    print("Name=",m,"","Average=",av,  "Total=",t)
```
#### _Output_
```
enter number of students3
enter index no-1
enter name-Wenura
subject 1-80
subject 2-80
subject 2-80
Name= Wenura  Average= 80.0 Total= 240
enter index no-2
enter name-Wenura2
subject 1-81
subject 2-81
subject 2-81
Name= Wenura2  Average= 81.0 Total= 243
enter index no-3
enter name-Wenura3
subject 1-82
subject 2-83
subject 2-83
Name= Wenura3  Average= 82.66666666666667 Total= 248
```
## Practical 27

### Multiplication 1 to 12

#### _Input_

```py
n=int(input("enter number"))
for i in range(1,13):
    a=n*i
    print(n,"x",i,"=",a)
```

#### _Output_
```
enter number2
2 x 1 = 2
2 x 2 = 4
2 x 3 = 6
2 x 4 = 8
2 x 5 = 10
2 x 6 = 12
2 x 7 = 14
2 x 8 = 16
2 x 9 = 18
2 x 10 = 20
2 x 11 = 22
2 x 12 = 24
```




 







	
