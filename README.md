# Data Type & Function Challenges
##  Overview:
This repo includes four distinct challenges to practice working with data types, functions, and C# programming concepts. Each challenge emphasizes key aspects like string manipulation, random number generation, and using ref parameters for direct updates.

## Challenges:
### Challenge 1: String and Number Processor
Objective: Process a mix of string and number inputs.
Description: Create a function that concatenates all string inputs into a single sentence and sums up all numeric inputs.
Test Case:
StringNumberProcessor("Hello", 100, 200, "World");  
Expected Outcome:
"Hello World; 300" 

### Challenge 2: Guessing Game
Objective: Implement a number guessing game.
Description: The function generates a random number and prompts the user to guess it. Feedback is provided ("Too High" or "Too Low") until the correct guess is made.
Execution: Uncomment GuessingGame() in Main() to test.
Expected Outcome: The game continues with user input until the correct number is guessed.

### Challenge 3: Simple Word Reversal
Objective: Reverse each word in a given sentence.
Description: The function takes a string input and reverses each word while preserving spaces and punctuation attached to the word.
Test Case:
ReverseWords("This is the original sentence!");  
Expected Outcome:
"sihT si eht lanigiro !ecnetnes"  
### Challenge 4: User Profile Updater
Objective: Update user profile details using the ref parameter modifier.
Description: Create a function to update a user’s Name, Age, and Email. The function will use ref parameters to directly modify the values. Validation should ensure data integrity.
Test Case:
string name = "John";  
int age = 25;  
string email = "john@example.com";  
UpdateUserProfile(ref name, ref age, ref email);  
Expected Outcome:
Updated Name: Jane  
Updated Age: 30  
Updated Email: jane@example.com  

## Key Learnings:
- Manipulating strings and numbers effectively.
- Working with random numbers and user input for interactive programs.
- Using ref parameters for in-place data updates.
- Implementing clean and modular functions in C#.
