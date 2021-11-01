# Makeup Lab (100 pts, Due Nov 30th)
This lab will be worth 100 points. It will be due at the end of the day (NOT NOON) on Nov 30th. You have 3 options:
1) Have a nice break. Take the average of your other labs
2) Makeup one of the labs you didn't do well in
3) Do a fun lab of your own creation

## Option 1: Take the average of your other labs
This will average your grade for labs 1-9 (not including project labs) and you submit nothing. However you must specify this in reflection.txt and push the change in order to count for credit

## Option 2: Make up a lab
Since solutions are posted, you will need to code, write tests, and answer reflection questions pertaining to questions realating to 

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

### Lab 7: Linked Lists

### Lab 8: BST

### Lab 9: Queues
