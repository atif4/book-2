# firstproject
this is my first repository

num = input("enter an odd lenght number: ")
lenght = len(num)
for i in range(lenght):
    for j in range(lenght):
        if i == j or i+j == lenght-1:
            print(num[j],end =" ")
        else:
            print(" ",end=" ")
    print()
