## write a python program to perform addition and division operation using class and if,elif..


#Aim 
```
To write a python program to perform addition and division operation using class and if,elif..

```
#algorithm.
```
1. Start.
2. Define a class Saveetha with methods setvalues, add, and div.
3. Prompt the user for their choice: 1 for addition, 2 for division, 0 for exit, else print "invalid choice".
4. Perform the operation based on the user's choice and handle the ZeroDivisionError for division
```
##program
```
class saveetha:
    def setvalues(self,a,b):
        self.a=a
        self.b=b
    def div(self,a,b):
        if b==0:
        
            print("division is not allowed by 0")
        return int(a/b)
    def add(self,a,b):
        return print(f"Result:  {a+b}")
        
        


a=int(input())
b=eval(input())
choice=int(input())
class1=saveetha()
if choice == 1:
    class1.add(a,b)
    print("Exiting!")

elif choice == 2:
       x=class1.div(a,b)
       print(f"Result:  {x}")
       print("Exiting!")
else:
    print("Exiting!")
   
```

#output
![image](https://github.com/user-attachments/assets/e97db90f-587d-4663-99ea-b72b374218fa)




#result
```
The expected output is Achieved.
```
