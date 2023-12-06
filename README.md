# codingQuiz8
Staircase:
* Time Complexity: O(n) because it has a for loop with n iterations, and the operations within it are constant
* Space Complexity: O(1) because the only variable it stores is the iterator variable in the for loop

Alternating Characters: 
* Recursive Definition: 
	- Base case: 
		if the string is one character or less, there cannot be matching adjacent characters so the number of deletions is returned
	- Recursive case: 
		if the first two characters are adjacent then the count of deletions is increased. 
		Returns the recursive call on the string excluding the first character
* Time Complexity: O(n) because it reduces the size of the string by 1 each recursive call
* Space Complexity: O(n) because no variables are stored in the function, but the result of each recursive call has to be stored in the stack
