## Write Python program to print reverse Pyramid of numbers.Get the number of rows as input.
#Aim 
```
To Write Python program to print reverse Pyramid of numbers.Get the number of rows as input.
```
#algorithm.
```
1. Start.
2. Input the number of rows `n`.
3. Loop from i = n to 1, print i times the number `i`.
4. End
```
##program
```
a=int(input())

for i in range(1,a):
    for j in range(1,i+1):
        print(i-j+1,end=" ")
    print()    
```

#output
![image](https://github.com/user-attachments/assets/d7005eed-f3c7-47bf-ae69-0d8dd380a226)


#result
```
The expected output is Achieved.
```
