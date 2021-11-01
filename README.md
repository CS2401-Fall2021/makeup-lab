# Makeup Lab (100 pts, Due Nov 30th)
This lab will be worth 100 points. It will be due at the end of the day (NOT NOON) on Nov 30th. You have 3 options:
1) Have a nice break. Take the average of your other labs
2) Replace one of the labs you didn't do well in by doing a lab on a similar theme 
3) Do a fun lab of your own creation (must have >75% lab average)

## Option 1: Take the average of your other labs
This will average your grade for labs 1-9 (not including project labs) and you submit nothing. However you must specify this in reflection.txt and push the change in order to count for credit. 
### Example Grading
You averaged 83% on labs. You update the reflection.txt to indicate option 1. Then you recieve an 83% on this lab.

## Option 2: Replace up a lab
Since solutions are posted, you will need to code, write tests, and answer reflection questions pertaining to questions realating to topics covered in labs. Choose ONE of the option below. 

### Example Grading
You got a 15% on lab3 and your lab average is 71%. So you make up lab 3 and recive an 85% instead. Your lab 3 grade gets changed to an 85. Now your lab average is 79%, which will be the grade you get on this makeup lab.

### Lab 1: String manipulation
Write a function that takes in a string, extracts the words, and turns the sentance into pig-latin
The rules for pig-latin are as follows
* If the First letter is a consonant, 
    * Move the first consonant (non-vowel) to the end of the word
    * add the suffix "ay" to the end of the word
    * Example: data -> ataday
* Otherwise
  * Add "yay" to the end
  * Example: algorithm -> algorithmyay 


#### Reflection Questions
1) How did you split a string into words?
2) How did you determine if a letter was a vowel or not?
3) What is the big-O runtime of a String with m words? Why?
4) What did you do if the string contains non-alphabetic chars?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 2: 2D arrays
Given a 2-D array, count how many Chars are vowels
#### Reflection Questions
1) How do you handle empty arrays?
2) How do you handle uneven 2D arrays?
3) What is the big-O runtime of a 2D array of m arrays, each of which has a max-length of m? Why?
4) How did you determine if a letter was a vowel or not?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 3: big-O
Write 5 methods with different runtimes (constant, linear, quadratic, exponential, m*n)
#### Reflection Questions
1) Wahat is the runtime of each method?
2) What is n (and/or) m?
3) Using the timer methods given in the original lab 3, run timer for each value of n and record it. 

### Lab 4: Recursion
Generate a list of all the ways to select a given subset of letters. E.g. "bat" should return {"b","a","t","ba","bt","at","bat"}
#### Reflection Questions
1) What is your base case?
2) What is your recursive call?
3) How do you use the answer to your recursive call to obtain your final answer?
4) What is the big-O runtime? Why?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 5: Binary Search
You are given an array, but instead of binary search, you have the elements ordered based off their value modulus 3. Example:
[0,6,9,4,7,2]

Change the binary search algorithm to work for this strangely sorted array

#### Reflection Questions
1) What is your midpoint?
2) How do you determine if you are done?
3) When should you search over the left side?
4) When should you search over the right side?
5) What is the big-O runtime for this algorithm? Why?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 6: Sorting
Given a 2-D array of doubles, sort each array using the in-place sort of your choice. Then sort the arrays based off thier initial value using a different in-place sort.
#### Reflection Questions
1) What sort did you use for each row?
2) What sort did you use for each column ?
3) What is the big-O runtime of a 2D array of m arrays, each of which has a max-length of m? Why?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 7: Linked Lists
Determine if the circular linked list you are on is even or odd length by looping through each item ONCE. 
#### Reflection Questions
1) What edge cases do you need to consider?
2) How do you know when to end?
3) What is the runtime? Why?

#### Tests
Write 5 tests describing your input, what you're testing, and desired output

### Lab 8: BST
Given a Binary Search Tree implement prune that does the following:
* Removes duplicates
* If the height is equal to the number of items-1, creates a new tree by inserting the values in a random order into a BST

### Reflections
1) What edge cases should you consider?
2) How do you detect duplicates?
3) How do you remove a node?
4) How did you randomize the order of the values you inserted into a  new tree?
5) How did you check if you should create your new tree?
6) On average, what is the height of the tree? 

### Tests
Write 5 tests describing your input, what you're testing, and desired output
### Lab 9: Stacks and Queues
Represent the game slapjack, which has the following methods
A card is represented by a String with the number of the card followed by the suit (Hearts, Clubs, Diamonds, Spades)
* addCard(String card) which adds a card to the pile
* shouldSlap() which returns true if any of the following
   1) Double: the last two cards are the same number. E.g 10H and 10C
   2) Sandwhich: there are two cards of the same number with a different card inbetween. E.g. 3D, 2S, 3C
   3) Run: the last 3 cards have the same suit, and are in increasing or decreasing order. E.g 4S,5S,6S

### Reflections
1) What edge cases should you consider?
2) How do you determine if there is a double?
3) How do you determine if there is a sandwhich?
4) How did you determine if there was a run?
5) Did you use a stack or queue? Why?

### Tests
Write 5 tests describing your input, what you're testing, and desired output
## Option 3: Makeup your own lab
> NOTE: You can only take this option if your lab grade average is >75%. 
### Example Grading
Let's say your average is 80%. You choose option 3 and get 100%. 100% is the grade you get for the lab, bringing your lab grade average up to 82%
### Reflections
1) What is your problem? What data Structures/algorithms does it use?
2) What edge cases did you consider?
3) What is the big-O runtime for this algorithm? Why?

### Tests
Write 5 tests describing your input, what you're testing, and desired output
