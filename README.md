# assignments-2-24.02.2022
Write a program number of elements 
num=int(input("Enter number of elements: "))
for i in range(1,num+1):
    listElements=int(input("Enter telement %d: "%i))
    numbers.append(listElements)
evenList=[]
oddList=[]
for j in numbers:
    if j%2==0:
        evenList.append(j)
    else:
        oddList.append(j)
print("Even number list: ",evenList)
print("Odd number list: ",oddList)
OUTPUT:
Enter number of elwmwnts:7
Enter element 1:25
Enter element 2:46
Enter element 3:67
Enter element 4:78
Enter element 5:89
Enter element 6:90
Enter element 7:87
Even number list:[46,78,90]
Odd number list:[25,67,89,87]
