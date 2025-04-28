# Exp.No:20  
## SEB - DICTIONARY


### AIM  
To Write a python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n!

### ALGORITHM

1. Begin the program.  
2. Input an integer a from the user.
3. Initialize an empty dictionary d.
4. Initialize a variable f = 1 to store the running factorial.
5. Loop i from 1 to a - 1 (not including a):
6. Multiply f by i → f = f * i
7. Store this factorial in the dictionary → d[i] = f
8. After the loop ends, print the dictionary with the message: "The obtained dictionary is d = ", d
9. Terminate the program.

---

### PROGRAM

```
a=int(input())
d=dict()
f=1
for i in range(1,a):
    f=f*i
    d[i]=f
print("The obtained dictionary is d = ",d)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/ccff069b-f45d-4228-9b6e-cc741e25a809)


### RESULT
Thus the python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n! has been executed successfully.
