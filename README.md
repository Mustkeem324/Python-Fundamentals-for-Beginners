#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[1]:


#First Program
print("This is sparta!!!")


# In[2]:


#Variables
var1="John"
print(var1)


# In[3]:


var1="Sam"
print(var1)


# In[4]:


var1="Matt"
print(var1)


# In[2]:


#Data-Type
a=10
type(a)


# In[3]:


a=10.5
type(a)


# In[1]:


a="sparta"
type(a)


# In[5]:


a=True
type(a)


# In[7]:


a=3+4j
type(a)


# In[ ]:


#Arithmetic Operators


# In[8]:


a=10
b=20


# In[9]:


print(a+b)


# In[10]:


print(a-b)


# In[11]:


print(a*b)


# In[12]:


print(a/b)


# In[4]:


#Relational Operators


# In[5]:


a=10
b=20


# In[6]:


a>b


# In[7]:


a<b


# In[8]:


a==b


# In[9]:


a!=b


# In[10]:


#Logical Operators


# In[12]:


a=True
b=False


# In[14]:


a&b


# In[15]:


b&a


# In[16]:


b&b


# In[17]:


a&a


# In[18]:


a|b


# In[19]:


b|a


# In[20]:


a|a


# In[21]:


b|b


# In[22]:


#Strings


# In[23]:


my_string="My name is John"


# In[24]:


my_string[0]


# In[5]:


my_string="My name is John"


# In[6]:


my_string[-1]


# In[26]:


my_string[0:4]


# In[28]:


len(my_string)


# In[30]:


my_string.lower()


# In[31]:


my_string.upper()


# In[33]:


my_string.replace('y','a')


# In[7]:


new_string = "hello hello world"


# In[8]:


new_string.count("hello")


# In[13]:


s1 = 'This is sparta!!!'
s1.find('sparta')


# In[12]:


s1.find('b')


# In[15]:


fruit = 'I like apples, mangoes, bananas'

fruit.split(',')


# In[ ]:


#Tuples in Python


# In[18]:


tup1=(1,"a",True,2,"b",False)


# In[17]:


tup1


# In[44]:


tup1[0]


# In[45]:


tup1[-1]


# In[22]:


tup1=(1,"a",True,2,"b",False)
tup1[1:4]


# In[46]:


tup1[1:4]


# In[49]:


tup1[2]="hello"


# In[50]:


tup1[6]=3+4j


# In[52]:


min(tup1)


# In[24]:


tup1=(1,"a",True,2,"b",False)
len(tup1)


# In[2]:


tup1 = (1,"a",True)
tup2 = (4,5,6)


# In[3]:


tup2+tup1


# In[31]:


tup1 = ('sparta',300)
tup2 = (4,5,6)
tup1*3 + tup2


# In[32]:


tup1=(1,2,3,4,5)
min(tup1)


# In[33]:


tup1=(1,2,3,4,5)
max(tup1)


# In[34]:


cmp(tup1,tup2)


# In[53]:


#List in Python


# In[ ]:





# In[56]:


l1=[1,"a",2,"b",3,"c"]


# In[58]:


l1=[1,"a",2,"b",3,"c"]
l1[1]


# In[59]:


l1=[1,"a",2,"b",3,"c"]
l1[2:5]


# In[35]:


l1=[1,"a",2,"b",3,"c"]
l1[0]=100
l1


# In[36]:


l1=[1,"a",2,"b",3,"c"]
l1.append("Sparta")
l1


# In[62]:


l1


# In[37]:


l1=[1,"a",2,"b",3,"c"]
l1.pop()
l1


# In[38]:


l1


# In[41]:


l1=[1,"a",2,"b",3,"c"]
l1.insert(1,"Sparta")
l1


# In[43]:


l1 = ["mango","banana","guava","apple"]
l1.sort()
l1


# In[44]:


l1 = [1,2,3]
l2 = ["a","b","c"]
l1+l2


# In[45]:


l1 = [1,"a",True]
l1*3


# In[ ]:


#Dictionary in Python


# In[68]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40}


# In[1]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40}
fruit.keys()


# In[70]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40}
fruit.values()


# In[74]:


fruit["Apple"]


# In[2]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40}
fruit["Mango"]=50
fruit


# In[3]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40,"Mango":50}
fruit["Apple"]=100
fruit


# In[4]:


fruit1={"Apple":10,"Orange":20}
fruit2={"Banana":30,"Guava":40}

fruit1.update(fruit2)

fruit1


# In[6]:


fruit={"Apple":10,"Orange":20,"Banana":30,"Guava":40}
fruit.pop("Orange")
fruit


# In[78]:


#Set in Python


# In[1]:


s1={1,"a",True,2,"b",False}
s1


# In[7]:


s1={1,"a",True,2,"b",False}
s1.add("Hello")
s1


# In[8]:


s1={1,"a",True,2,"b",False}
s1.update([10,20,30])
s1


# In[9]:


s1={1,"a",True,2,"b",False}
s1.remove("b")
s1


# In[13]:


s1 = {1,2,3,4,5,6}
s2 = {5,6,7,8,9}

s1.intersection(s2)


# In[ ]:



#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[ ]:


#simple for loop


# In[1]:


fruits = ["apple","mango","banana"]


# In[2]:


for i in fruits:
    print(i)


# In[3]:


#nested for loop


# In[4]:


color=["blue","green","yellow"]
item=["book","ball","chair"]


# In[5]:


for i in color:
    for j in item:
        print(i,j)


# In[ ]:



#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[1]:


def hello():
    print("Hello World")


# In[2]:


hello()


# In[3]:


#Function with parameter


# In[4]:


def add10(x):
    return x+10


# In[14]:


add10(10)


# In[15]:


def even_odd(x):
    if x%2==0:
        print(x, " is even")
    else:
        print(x, " is odd")


# In[16]:


even_odd(5)


# In[1]:


#lambda functions


# In[2]:


g = lambda x: x*x*x 
print(g(7)) 


# In[3]:


#lambda functions with filter
li = [5, 7, 22, 97, 54, 62, 77, 23, 73, 61] 
final_list = list(filter(lambda x: (x%2 != 0) , li)) 
print(final_list) 


# In[4]:


#lambda functions with map
li = [5, 7, 22, 97, 54, 62, 77, 23, 73, 61] 
final_list = list(map(lambda x: x*2 , li)) 
print(final_list) 


# In[5]:


from functools import reduce
li = [5, 8, 10, 20, 50, 100] 
sum = reduce((lambda x, y: x + y), li) 
print (sum) 


# In[ ]:



#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[1]:


a=10
b=20


# In[2]:


if b>a:
    print("B is greater than A")


# In[3]:


if a>b:
    print("A is greater than B")


# In[4]:


if a>b:
    print("A is greater than B")
else:
    print("B is greater than A")


# In[5]:


#elif


# In[6]:


a=10
b=20
c=30


# In[8]:


if (a>b) & (a>c):
    print("A is the greatest")
elif (b>a) & (b>c):
    print("B is the greatest")
else:
    print("C is the greatest")


# In[ ]:


#Tuple with if


# In[15]:


tup1=("a","b","c")


# In[16]:


if "a" in tup1:
    print("a is present in tup1")


# In[ ]:


#List with if


# In[17]:


l1=["a","b","c"]


# In[18]:


if l1[0]=="a":
    l1[0]=100


# In[19]:


l1


# In[20]:


#Dictionary with if


# In[21]:


d1={"k1":10,"k2":20,"k3":30}


# In[22]:


if d1["k1"]==10:
    d1["k1"]=d1["k1"]+100


# In[23]:


d1


# In[ ]:



#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[ ]:


#Printing 1-10  using while loop


# In[2]:


i=1
while i<=10:
    print(i)
    i=i+1


# In[ ]:


#Printing 2-table with while loop


# In[3]:


i=1
n=2
while i<=10:
    print(n," * ", i, " = ",n*i)
    i=i+1


# In[ ]:


#While with list


# In[5]:


l1=[1,2,3,4,5]


# In[12]:


i=0
while i<len(l1):
    l1[i]=l1[i]+100
    i=i+1


# In[13]:


l1


# In[ ]:



#!/usr/bin/env python
# coding: utf-8

# In[ ]:


#Proprietary content. ©Great Learning. All Rights Reserved. Unauthorized use or distribution prohibited


# In[ ]:


#check even odd


# In[ ]:


num = int(input("Enter a number: "))
if (num % 2) == 0:
   print(num, " is even")
else:
   print(num, " is odd")


# In[ ]:


#check positive, negative or 0


# In[ ]:


num = float(input("Enter a number: "))
if num > 0:
   print("Positive number")
elif num == 0:
   print("Zero")
else:
   print("Negative number")


# In[ ]:


#Factorial of a number


# In[ ]:


factorial = 1
# check if the number is negative, positive or zero
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)


# In[ ]:


#Reversing a number


# In[ ]:


n=int(input("Enter number: "))
rev=0
while(n>0):
    dig=n%10
    rev=rev*10+dig
    n=n//10
print("Reverse of the number:",rev)


# In[ ]:


#Check if it is a palindrome


# In[ ]:


n=int(input("Enter number:"))
temp=n
rev=0
while(n>0):
    dig=n%10
    rev=rev*10+dig
    n=n//10
if(temp==rev):
    print("The number is a palindrome!")
else:
    print("The number isn't a palindrome!")


# In[ ]:


#fibonacci - 0 1 1 2 3 5 8.......


# In[16]:


n=int(input("Enter number:"))
a = 0
b = 1
if n < 0: 
    print("Incorrect input") 
elif n == 0: 
    print(a)
elif n == 1: 
    print(a) 
else: 
    for i in range(2,n): 
        c = a + b 
        a = b 
        b = c 
    print(b) 


# In[2]:


# 10 is the total number to print
for num in range(6):
    for i in range(num):
        print (num,end=" ") #print number
    # new line after each row to display pattern correctly
    print("\n")


# In[ ]:



