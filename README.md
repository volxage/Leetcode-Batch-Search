# Leetcode-Batch-Search
While I was drafting a list of Leetcode problems to solve, I realized that the task I was doing could be automated and used it as an opportunity to learn more about Bash scripting.
The requirement is a file with the names of Leetcode problems, separated by line breaks. There can be whitespace anywhere, and it doesn't matter if letters are uppercased or not. With partial matches, the program prompts the user to pick from a list of options. The only thing the program lacks is fuzzy finding, which would add an extra dependency to the program.
To use this script, write a file of line-separated Leetcode problem titles, and then add the file name as an argument of the script when running it.
## For example:
`vim titles` or `nano titles` to edit the file
For the contents of the file:

Two Sum
Add two numbers
Longest Substring without repeating Characters
Median of Two Sorted Arrays
Longest Palindromic

Run the file with the proper argument: `./leetcode-search titles`
The program will ask for clarification on partial matches, for instance for Two Sum it will ask which Two Sum in the series you meant to choose. You will have to manually enter the number for that from the list.
The result:
`- ( ) 1. Two Sum
- ( ) 2. Add two numbers
- ( ) 3. Longest Substring without repeating Characters
- ( ) 4. Median of Two Sorted Arrays
- ( ) 5. Longest Palindromic`
