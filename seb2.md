##Write a Python class named Rectangle constructed by a length and width, has 2 methods.


#Aim 
```
To Write a Python class named Rectangle constructed by a length and width, has 2 methods.

  1. setvalues - to set the values of length and breadth

  2. a method which will compute the area of a rectangle.
```
#algorithm.
```
1. Start.
2. Define a Rectangle class with attributes length and width.
3. Define a setvalues method to set the values of length and width.
4. Define a method to compute and return the area of the rectangle (length * width)
```
##program
```

class rectangle:
    def setvalues(self,a,b):
        self.a=0
        self.b=0
    def area(self,a,b):
        return a*b
        
        
a=int(input())        
b=int(input())        
obj=rectangle()

print(obj.area(a,b))
        
            
```

#output
![image](https://github.com/user-attachments/assets/52691cd5-7e15-45b0-8a6d-fac7d17dacbe)
#result
```
The expected output is Achieved.
```
