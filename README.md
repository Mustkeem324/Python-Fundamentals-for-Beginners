# Python-Fundamentals-for-Beginners

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

