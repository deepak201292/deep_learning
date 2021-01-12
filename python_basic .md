```python
1+1

```




    2




```python
1/2
```




    0.5




```python
2*4
```




    8




```python
2**4
```




    16




```python
x=2
y=5
z=x+y
print(z)

```

    7
    


```python
'single quotes'
```




    'single quotes'




```python
"hi"
```




    'hi'




```python
"indian's"
```




    "indian's"




```python
x="python"
print(x)
```

    python
    


```python
num=12
name= 'sam'
print('my number is:{one},and my name is:{two}'.format(one=num,two=name))

```

    my number is:12,and my name is:sam
    


```python
num=12
name= 'sam'
print('my number is :{},and my name is:{}'.format(num,name))

```

    my number is :12,and my name is:sam
    


```python
my_list=['a','b','c']
my_list.append('e')
my_list
```




    ['a', 'b', 'c', 'e']




```python
my_list[0]

```




    'a'




```python
my_list[-1]

```




    'e'




```python
my_list[:2]
```




    ['a', 'b']




```python
print(True,False)

```

    True False
    


```python
type(False)
```




    bool




```python
True and False
```




    False




```python
my_str="python123"
```


```python
my_str.islower()
```




    True




```python
my_str.isalnum()

```




    True



 True and False


```python
type([])
```




    list




```python
student_name_mark=['rohan','ram',95,96]
```


```python
len(student_name_mark)
```




    4




```python
student_name_mark.append('mohit')
```


```python
student_name_mark
```




    ['rohan', 'ram', 95, 96, 'mohit']




```python
student_name_mark[1:4]
```




    ['ram', 95, 96]




```python
lt=[2,3,6,5,8,9]
```


```python
sum(lt)
```




    33




```python
1>2
```




    False




```python
5>3
```




    True




```python
2<=8
```




    True




```python
if 1<6:
    print('6 is larger')
```

    6 is larger
    


```python
if 2<6:
    print("right")
else :
    print('wrong')
```

    right
    


```python
if 2>6:
    print("right")
else :
    print('wrong')
```

    wrong
    


```python
if 1==2:
    print('first')
elif 3==3:
    print('middle')
else:
    print('last')
```

    middle
    


```python
if 1==1:
    print('first')
elif 3==3:
    print('middle')
else:
    print('last')
```

    first
    


```python
if 1==2:
    print('first')
elif 3==4:
    print('middle')
else:
    print('last')
```

    last
    


```python
seq=[1,2,3,4,5]
```


```python
for item in seq:
    print(item)
```

    1
    2
    3
    4
    5
    


```python
2+3
```




    5




```python
range(5)
```




    range(0, 5)




```python
for i in range(5):
    print(i)
```

    0
    1
    2
    3
    4
    


```python
list(range(5))
```




    [0, 1, 2, 3, 4]




```python
x=[1,2,3,4]
```


```python
out=[]
for item in x:
    out.append(item**2)
print(out)    
    
```

    [1, 4, 9, 16]
    


```python
[item**2 for item in x]
```




    [1, 4, 9, 16]




```python
def times2(var):
    return var*2
```


```python
times2(2)
```




    4




```python
st="hello my name is"
```


```python
st.lower()
```




    'hello my name is'




```python
st.upper()
```




    'HELLO MY NAME IS'




```python
st.split()
```




    ['hello', 'my', 'name', 'is']


