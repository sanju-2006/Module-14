# Exp.No:38  
## REAR END of deque using collection built-in function

---

### AIM  
Write a Python program to insert 14, 15 at REAR END of deque using collection built-in function.



---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
import collections
de=collections.deque([])
for i in range(3):
    a=int(input())
    de.append(a)
de.append(14)
de.append(15)
print("The deque after appending at right is :")
print(de)
```

### OUTPUT

<img width="924" height="286" alt="image" src="https://github.com/user-attachments/assets/72c6161c-d5f5-44a7-aae3-71f0d708dc90" />


### RESULT

 Python program to insert 14, 15 at REAR END of deque using collection built-in function is successfully verified
