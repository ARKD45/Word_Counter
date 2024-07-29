This project is a simple Python script designed to count the number of words in a given passage. Here's a breakdown of how the project works:

1. **Input**: The program prompts the user to input a passage of text.
   ```python
   passage = input('Give your passage: \n ')
   ```

2. **Splitting the Text**: The passage is split into individual words using the `split(' ')` method, which divides the text at each space character.
   ```python
   words = passage.split(' ')
   ```

3. **Counting Words**: The length of the list of words is calculated using `len(words)`, which gives the total number of words in the passage.
   ```python
   count = len(words)
   ```

4. **Output**: The word count is printed to the console.
   ```python
   print(f'Word count: {count}')
   ```

### Explanation

- **Input Function**: `input()` is used to capture user input from the console.
- **Splitting the String**: The `split(' ')` function breaks the input string into a list of words by using a space character as the delimiter.
- **Counting Words**: `len()` is used to determine the number of items in the list, which corresponds to the number of words in the passage.
- **Formatted Output**: The `print()` function, combined with an f-string (`f'Word count: {count}'`), is used to output the word count in a readable format.

### Example Usage

When the script is run, it will prompt the user to enter a passage:
```
Give your passage: 
```
If the user inputs:
```
The quick brown fox jumps over the lazy dog.
```
The program will output:
```
Word count: 9
```

This project demonstrates basic string manipulation and user interaction in Python, making it a great starting point for beginners learning to work with text data.
