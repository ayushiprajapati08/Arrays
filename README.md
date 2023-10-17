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


##Code 4
1. Start
2. Declare variables: int i, n
3. Declare a float array arr[100] to store elements
4. Output: "Enter total number of elements(1 to 100): "
5. Input: Read the value of n (number of elements)
6. Use a loop to read n numbers from the user and store them in the array arr
   a. Output: "Enter Number i + 1: "
   b. Input: Read a number and store it in arr[i]
7. Initialize arr[0] as the largest element
8. Use a loop to iterate from index 1 to n-1
   a. Check if arr[0] is less than arr[i]
   b. If true, update arr[0] with arr[i]
9. Output: "Largest element = arr[0]"
10. End
The program starts and declares necessary variables.
The user is prompted to enter the total number of elements they want to input (variable n).
An array arr of size 100 is declared to store the elements.
The program then enters a loop to read n numbers from the user and stores them in the array arr.
The program initializes arr[0] as the largest element.
The program then iterates through the elements from index 1 to n-1 and checks if any element is larger than the current largest element (arr[0]). If it finds a larger element, it updates arr[0] with that element.
Finally, the program outputs the largest element found in the array.



##Code 5
1. Start
2. Declare variables: int input[100] (array to store elements), count (to store number of elements), i, min
3. Output: "Enter Number of Elements in Array"
4. Input: Read the value of count
5. Output: "Enter count numbers"
6. Use a loop to read count numbers from the user and store them in the array input
   a. Input: Read a number and store it in input[i]
7. Set min as the first element of the array: min = input[0]
8. Use a loop to iterate through the array from index 1 to count-1
   a. Check if input[i] is less than min
   b. If true, update min with input[i]
9. Output: "Minimum Element\n" followed by the value of min
10. End
The program starts and declares necessary variables.
The user is prompted to enter the number of elements they want in the array (variable count).
The program then enters a loop to read count numbers from the user and stores them in the array input.
The program initializes min with the first element of the array (input[0]).
The program then iterates through the array from index 1 to count-1 and checks if any element is smaller than the current minimum element (min). If it finds a smaller element, it updates min with that element.
Finally, the program outputs the minimum element found in the array.


##Code 6
1. Start
2. Declare variables: int m, n (to store the dimensions of the 2D array)
3. Input: Read the number of rows (m) from the user
4. Input: Read the number of columns (n) from the user
5. Declare a 2D array s[m][n] to store the elements
6. Declare variables: int i, j (loop counters)
7. Output: "Array Input:"
8. Use nested loops to read elements into the 2D array:
   a. Outer loop from i = 0 to m - 1
      i. Inner loop from j = 0 to n - 1
         - Input: Read s[i][j] from the user
9. Output: "Array Elements:"
10. Use nested loops to print the elements of the 2D array:
    a. Outer loop from i = 0 to m - 1
       i. Inner loop from j = 0 to n - 1
          - Output: Print s[i][j]
       ii. Output: Print a new line to move to the next row
11. End
The program starts and declares necessary variables.
The user is prompted to enter the number of rows (m) and columns (n) for the 2D array.
A 2D array s[m][n] is declared to store the elements.
The program then enters nested loops to read elements into the 2D array.
After reading all the elements, the program enters another set of nested loops to print the elements of the 2D array row by row.
Finally, the program ends after printing the entire 2D array.


