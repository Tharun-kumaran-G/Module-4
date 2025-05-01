# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No: 212223060288
Name: Tharun Kumaran G

def process_grades():
    input_str = input("Enter grades separated by commas: ")
    grades_str = input_str.split(",")
    valid_grades = []

    for grade in grades_str:
        try:
            num = int(grade.strip())
            valid_grades.append(num)
        except ValueError:
            print(f"Invalid input '{grade.strip()}': Not an integer.")

    print("Valid grades:", valid_grades)

process_grades()

```

### OUTPUT

![image](https://github.com/user-attachments/assets/12e0f768-cde8-4d7e-9158-cc01be43be4f)

### RESULT

Thus, the python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers has been executed and verified successfully.
