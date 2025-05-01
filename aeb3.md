## Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.
##Aim
```
To Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.
```
#algorithm.
```
1. Start.
2. Input two numbers: a and b.
3. Check if b is 0, if true, assign "You can't divide with 0" to result.
4. Otherwise, perform the division and assign the result to result
```
##program
```
a=int(input())
b=int(input())
try:
    result=a/b
    print(result)
except ZeroDivisionError:
                print("You can't divide with 0") 
```

#output
![image](https://github.com/user-attachments/assets/ec79d548-c962-4f3b-aed7-72d3bd659ab0)




#result
```
The expected output is Achieved.
```
