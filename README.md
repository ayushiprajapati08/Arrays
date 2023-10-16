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
1. Start
2. Declare an integer array numbers[5] to store marks
3. Output: "Enter 5 marks:"
4. Start a loop with index i from 0 to 4
   a. Input: Read a mark from the user and store it in numbers[i]
5. Output: "The marks are: "
6. Start another loop with index n from 0 to 4
   a. Output: Print numbers[n] followed by a space
7. End
The program starts and declares an integer array numbers of size 5 to store the marks entered by the user.
The user is prompted to enter 5 marks.
The program enters a loop where it reads each mark from the user and stores it in the corresponding position in the numbers array.
After reading all the marks, the program outputs "The marks are: ".
The program enters another loop to print the marks stored in the numbers array, separated by spaces.
The program ends.



##Code 3
1. Start
2. Declare variables: int i, n
3. Declare double variables: sum = 0, average = 0
4. Output: "Enter the number of integers you want in an array: "
5. Input: Read the value of n (number of integers)
6. Declare an integer array arr[n]
7. Start a loop with index i from 0 to n-1
   a. Output: "Enter arr[i]: "
   b. Input: Read the value and store it in arr[i]
8. Output: "The Elements of the Array are: \n\n"
9. Start a loop with index i from 0 to n-1
   a. Output: "arr[i] = arr[i]"
   b. Add arr[i] to the sum variable: sum += arr[i]
10. Calculate average: average = sum / n
11. Output: "The Sum of the Elements of the Array is: sum"
12. Output: "The Average of the Elements of the Array is: average"
13. Output: "\n\n"
14. End
The program starts and declares necessary variables.
The user is prompted to enter the number of integers they want in the array (variable n).
An array arr of size n is declared to store the integers.
The program then enters a loop to read integers from the user and stores them in the array.
After reading all the integers, the program calculates the sum of the elements and the average.
Finally, the program outputs the elements, sum, and average of the array.


##code 4

