# Python Fundamental Block

Note: Some basics concepts/syntax that i may forget

###### Help options

* dir(Variable): to find available methods
* help(data-type)/(data-type.method): for more details
* type(variable): to check datatype

###### List

* list enumeration

    provides index with item in list

```python
for index,item in enumerate(list):
	print(index,item)
# To set start index as 
for index,item in enumerate(list,start=1):
	print(index,item)
```

* list to string or vice-versa

```python
list=['ved','ant']
str='-'.join(list)
print(str) #ved-ant
# vice-versa
new_list=str.split('-')
```

###### Dictionary

enumeration like list

```python
for key,value in dict.items():
	print(key,value)
```
