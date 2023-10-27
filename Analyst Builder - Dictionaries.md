```python
ice_cream_customer = {'Name':'Jimmy John','Flavor Purchased':['Mint Chocolate Chip','Vanilla','Chocolate'],'Age':40}

print(ice_cream_customer)
type(ice_cream_customer)
```

    {'Name': 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 40}
    




    dict




```python
ice_cream_customer.keys()
```




    dict_keys(['Name', 'Flavor Purchased', 'Age'])




```python
ice_cream_customer.values()
```




    dict_values(['Jimmy John', ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 40])




```python
ice_cream_customer.items()
```




    dict_items([('Name', 'Jimmy John'), ('Flavor Purchased', ['Mint Chocolate Chip', 'Vanilla', 'Chocolate']), ('Age', 40)])




```python
ice_cream_customer['Name']
```




    'Jimmy John'




```python
ice_cream_customer['Flavor Purchased']
```




    ['Mint Chocolate Chip', 'Vanilla', 'Chocolate']




```python
ice_cream_customer_2 = {0:'Jimmy John','Flavor Purchased':['Mint Chocolate Chip','Vanilla','Chocolate'],'Age':40}

print(ice_cream_customer_2)

ice_cream_customer_2[0]
```

    {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 40}
    




    'Jimmy John'




```python
ice_cream_customer_2['Amount Spent'] = 20.06
```


```python
print(ice_cream_customer_2)
```

    {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 40}
    


```python
ice_cream_customer_2.update({0:'Jimmy John','Flavor Purchased':['Mint Chocolate Chip','Vanilla','Chocolate'],'Age':25,})
```


```python
print(ice_cream_customer_2)
```

    {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06}
    


```python
ice_cream_customer_2.update({'First/Last': 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06})
```


```python
print(ice_cream_customer_2)
```

    {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06, 'First/Last': 'Jimmy John'}
    


```python
del ice_cream_customer_2['First/Last']
print(ice_cream_customer_2)
```

    {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06}
    


```python
customer_spent = ice_cream_customer_2['Amount Spent']
print(customer_spent)
```

    20.06
    


```python
nested_dict = {1: 'Value',2:'Value_2',3:{0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06}}
print(nested_dict)
```

    {1: 'Value', 2: 'Value_2', 3: {0: 'Jimmy John', 'Flavor Purchased': ['Mint Chocolate Chip', 'Vanilla', 'Chocolate'], 'Age': 25, 'Amount Spent': 20.06}}
    


```python
nested_dict[3][0]
```




    'Jimmy John'




```python
nested_dict[3]['Flavor Purchased'][0]
```




    'Mint Chocolate Chip'




```python

```
