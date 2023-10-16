# Arrays
##Code 1
1. Start
2. Declare variables: int key, i
3. Declare an integer array marks[10] and initialize it with values {5, 10, 15, 20, 25}
4. Output: "Enter the number"
5. Input: Read the value of key
6. Initialize a for loop with index i from 0 to 9
   a. Check if key is equal to marks[i]
   b. If true, output: "Key found at location i" and break the loop
7. After the loop, check if i is equal to 10
   a. If true, output: "Key not found"
8. End


Explanation:

The program starts and declares necessary variables.
The user is prompted to enter a number which is stored in the variable key.
The program then iterates through the marks array to find if the key is present in the array.
If the key is found, the program outputs the index where the key is found and breaks out of the loop.
If the key is not found after the loop has iterated through all elements, it outputs "Key not found".
Please note that there are a couple of issues in the provided code such as the incorrect array size in the loop and the use of a semicolon after the if(i==10) statement. The corrected code should have the array size as 5 (since there are 5 elements in the marks array) and the semicolon should be removed to properly execute the if statement.



##Code 2
