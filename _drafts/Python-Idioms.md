---
layout: post
title: "Python Idioms"
backgrounds:
    - http://steam4kids.net/wp-content/uploads/2015/05/python_logo.jpg
thumb: https://images.unsplash.com/13/unsplash_523ae1f5502d6_1.JPG
tags: Programming Python
category: Tech
---

## Python Idioms Collection
### What is Python Idioms?
It's a specific structural and syntactic patterns of Python programming Language. It shows the capability of Python and by learning Python Idioms, one will understand alternative and compact ways to achieve solutions.


Lately, I am interested about Python idioms and looking for useful Python idioms. This is my attempt on collecting beautiful and useful Python Idioms. This is the result of weekends net surfing and fun reading. Starts from next section,I will categorize python idioms into 3 levels; Easy, Normal and Advanced.

#### Small but still useful
{%highlight bash%}
# assign muliple variables
a,b = 1,2  
print a,b

# swap values
a,b = b,a  
print a,b

# unpacking
identity= ["Joe","MA7687231","Male"]  
name, id, gender = identity
print name, id, gender

people = [identity,["Mary","G6683241","Female"]]  
for (name, id, gender) in people:
    print name, id, gender

identity, (name, id, gender) = people
print name, id, gender
print identity

# only work in interactive interpreter, "_" saves last print value
>>> 1+2 
>>> _   

#build strings from sub-strings
colors = ['red', 'green', 'blue']
print ''.join(colors)  

# printing combinations of static text and variable
colors = ['red', 'green', 'blue']
print "{3 basic colors are {1}, {2}, and {3}}".format(colors[1], colors[2], colors[3])

# chained compraison
num = 3
if 2 > num > 5:
    print "{0} is between 2 and 5.".format(num)
{%endhighlight%}

#### Little bit longer but effective
{%highlight bash%}
#instead of traditional open and close file, with statement close the file after execution
with open(file,'rb') as f1: 
    for line in f1:
        print line

# in case you want to get index and item of a list
for x,e in enumerate(list):
    print x #list index 
    print e # list item

# get unique items from a list
list = [1,2,2,4,4,5,3,3,5]
uniq_list = list(set(list))
print uniq_list

# get all occurences of value from a list
list = [1,2,2,4,4,5,3,3,5]
one = 1
indexes = [i for i,e in enumerate(list) if e == one]
print indexes

{%endhighlight%}




   
   

































































































































































































































































































































































i
