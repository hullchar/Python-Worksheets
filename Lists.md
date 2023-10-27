```python
name = 'Marisol'
number = len(name)*9
print('Hello ' + name + '. Your lucky number is ' + str(number))

name = 'Ardashir'
number = len(name)*9
print('Hello ' + name + '. Your lucky number is ' + str(number))
```

    Hello Marisol. Your lucky number is 63
    Hello Ardashir. Your lucky number is 72
    


```python
def lucky_number(name):
    number = len(name)*9
    print('Hello ' + name + '. Your lucky number is ' + str(number))
    
lucky_number('Marisol')
lucky_number('Ardashir')
lucky_number('Charlotte')
```

    Hello Marisol. Your lucky number is 63
    Hello Ardashir. Your lucky number is 72
    Hello Charlotte. Your lucky number is 81
    


```python
fruits = ['apple', 'banana', 'cherry']
numbers = [1, 2, 3, 4, 5]
mixed = [1, 'apple', True, 3.14]
cat_list = [1, 'Cat',['Meow',50,'fur'], 10.75, True]

print(fruits)
print(cat_list)

cat_list.append('Kitten')
print(cat_list)

cat_list[0] = 10
print(cat_list)

cat_list[2]

cat_list[2][0]
cat_list[2][0][0]
```

    ['apple', 'banana', 'cherry']
    [1, 'Cat', ['Meow', 50, 'fur'], 10.75, True]
    [1, 'Cat', ['Meow', 50, 'fur'], 10.75, True, 'Kitten']
    [10, 'Cat', ['Meow', 50, 'fur'], 10.75, True, 'Kitten']
    




    'M'




```python
list_1 = [1, 'Great']
list_2 = [2, 'Wonderful']

list_3 = list_1 + list_2
print(list_3)
```

    [1, 'Great', 2, 'Wonderful']
    


```python

```
