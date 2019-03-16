# Phonetics_Class2019
<br> Various Methods and Examples of python 

<br>**Variables**

<br>type|feature|example
---|:---:|---
string|immutable<br>iterable|`'a','123','\n'`
list|mutable<br>iterable|`[1,2,3]. ['apple']`
tuple|immutable<br>iterable|`(1,2,3), (3,), ('a',)`
dictionary|mutable<br>iterable|`{'a':1,'b':2}`
range|immutable<br>iterable|`range(10)`
set|mutable<br>iterable|`{1,2,3}`

<br>**Strings**

|name|meaning|syntax|
|---:|---:|---|
|len|counts the number of elements in container|len(`string`)|
|upper|a string which all characters have been uppercased|upper(`string`)|
|lower|a string which all characters have been lowercased|lower(`string`)|
|find|finds the first occurrence of the specified value|`string`.find(value)|
|rindex|finds the last occurrence of the specified value|`string`.rindex(value, start, end)|
|strip|removes any leading or trailing characters of string|`string`.strip(characters)|
|split|splits a string into a list|`string`.split(separator, max)|
|replace|replaces a specified phrase with another specified phrase|`string`.replace(oldvalue, newvalue, count)|
|join| takes all items in an iterable and joins them into one string|`string`.join(iterable)|

<br>**Syntax**

|operator|meaning|example|
|---:|---:|---|
|`for loop`| allows code to be executed repeatedly| for _ in range(10):|
|`range(start,end)`| generate numbers in order|range(1,10)|
|`len(obj)`|used to determine the size of a container|len('abc')|
|`enumerate(iter)`|adds a counter to an iterable|enumerate({1,2,3})|
|`zip(iter)`|used to slice multiple iterable|zip(['a','b'],[1,2])|
