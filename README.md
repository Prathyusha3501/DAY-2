# DAY-2
fav_pizza=['vegpizza','chickenpizza','periperipizza'] print(fav_pizza) friend_pizza=fav_pizza[:] fav_pizza.append('chillipizza') friend_pizza.append('pepporonipizza') print('my favourite pizzas are') for i in fav_pizza: print(i) print('My friend favourite pizzas are') for i in friend_pizza: print(i)

fruits=['apple','banana','grapes','guava','papaya','melon','lemon','mango','strawberry','cherry'] print("the first three fruits are:",fruits[0:3]) print("the fruits from the middle of the list:",fruits[3:6]) print("the last three fruits are:",fruits[6:9]) for i in range(1,21): print(i)

numbers=list(range(1,1000001)) s=0 for i in numbers: s=s+i print(s) print(min(numbers)) print(max(numbers))

odd=list(range(1,21)) print('the odd numbers are:',odd[0:21:2])

b=[] for i in range(1,11): a=3*i b.append(a) print(b) d=[] for i in range(1,11): c=i**3 d.append(c) print(d)

cubes=[a**3 for a in range(1,11)] print(cubes)
