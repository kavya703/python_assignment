# python_assignment
fruits=['apple','banana','cherry','watermelon','grapes','mango','orange','kiwi']
vegetables=['potato','tomato','onion','carrot','beetroot','cabbage','brinjal','capsicum']
print('vegetabels',vegetables)
print('fruits',fruits)
apple_price=100
banana_price=40
cherry_price=70
watermelon_price=30
grapes_price=50
mango_price=60  
orange_price=80
kiwi_price=90
item=input('what you want:')
if item in fruits:
    quantity=int(input('how many kg you want:'))
    if item=='apple':
     print('total amount:',100*quantity)
    elif item=='banana':
      print('total amount:',40*quantity)
    elif item=='cherry':
      print('total amount:',70*quantity)
    elif item=='watermelon':
      print('total amount:',30*quantity)
    elif item=='grapes':
      print('total amount:',50*quantity)
    elif item=='mango':
      print('total amount:',60*quantity)
    elif item=='orange':
      print('total amount:',80*quantity)
    elif item=='kiwi':
      print('total amount:',90*quantity)
else:
    if item in vegetables:
       quantity=int(input('how many kg you want:'))
       if item=='potato':
            print('total amount:',20*quantity)
       elif item=='tomato':
            print('total amount:',30*quantity)
       elif item=='onion':
            print('total amount:',40*quantity)
       elif item=='carrot':
            print('total amount:',50*quantity)
       elif item=='beetroot':
            print('total amount:',60*quantity)
       elif item=='cabbage':
            print('total amount:',70*quantity)
       elif item=='brinjal':
            print('total amount:',80*quantity)
       elif item=='capsicum':
            print('total amount:',90*quantity)
       else:
            print(f'sorry {item} is not available')
    else:
       print(f'sorry {item} is not available')
