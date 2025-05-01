# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.No: 212223060288
#Name: Tharun Kumaran G

import sys
def print_custom_dict_size():
    person = {
        "Name": "Sai",
        "Age": 19,
        "Student": True
    }

    size = sys.getsizeof(person)
    print("Dictionary:", person)
    print("Size of the dictionary (in bytes):", size)

print_custom_dict_size()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/50b8a290-fd6f-4772-97a5-bf06318207e1)

### RESULT

Thus, the python program to print the size of a dictionary using `getsizeof()` from the `sys` module has been executed and verified successfully.
