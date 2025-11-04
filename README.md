A C program that generates random sentences based on a source text.

Output: 
- A sentence ending with ? (question)
- A sentence ending with ! (exclamation)

Algorithm:
- Text loading: #embed lets the program access the file
- Preprocessing: Removes non-printable characters
- Tokenization: Splits into words and maps successor relationships
- Generation: Follows random word chains starting with capital letters