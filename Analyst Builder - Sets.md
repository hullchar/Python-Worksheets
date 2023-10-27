```python
first_set = {1,2,3}

print(first_set)
```

    {1, 2, 3}
    


```python
second_set = {1,2,'Hey!'}

print(second_set)
```

    {1, 2, 'Hey!'}
    


```python
third_set = {1,2,3,2,1,2,3,2,1}

print(third_set)
```

    {1, 2, 3}
    


```python
fourth_set = {(1,2,3),1,2,3}

print(fourth_set)
```

    {1, 2, 3, (1, 2, 3)}
    


```python
fifth_set = {7,7,1,1,3,3,'Carrot','Carrot'}

print(fifth_set)
```

    {1, 3, 'Carrot', 7}
    


```python
fifth_set.update([3,2,1])

print(fifth_set)
```

    {1, 2, 3, 7, 'Carrot'}
    


```python
fifth_set.discard(2)

print(fifth_set)
```

    {1, 3, 7, 'Carrot'}
    


```python
fifth_set.remove(1)

print(fifth_set)
```

    {3, 7, 'Carrot'}
    


```python
set_1 = {1,2,3,4,5}
set_2 = {4,5,6,7,8}

print(set_1 | set_2)
```

    {1, 2, 3, 4, 5, 6, 7, 8}
    


```python
print(set_1 & set_2)
```

    {4, 5}
    


```python
print(set_1 - set_2)
```

    {1, 2, 3}
    


```python
print(set_2 - set_1)
```

    {8, 6, 7}
    


```python
print(set_1 ^ set_2)
```

    {1, 2, 3, 6, 7, 8}
    


```python

```
