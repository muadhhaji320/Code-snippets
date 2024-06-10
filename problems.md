
<u>**Run python file:**<u/> write a shell script that runs a python script.<br>
The python file name will be saved in the environment variable $PYFILE
```python
#!/bin/bash
python3 $PYFILE
```

<u>**Greater number:**</u> find greater number between two numbers
```python
# Prompt the user for input
first_number = int(input("Enter the first number: "))
second_number = int(input("Enter the second number: "))

# Compare the numbers and display the appropriate message
if first_number > second_number:
    print(f"{first_number} is greater than {second_number}")
elif first_number < second_number:
    print(f"{first_number} is smaller than {second_number}")
else:
    print("Both numbers are equal")
```
