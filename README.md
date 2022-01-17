//Alessandra Serrano
//Warm Up: Puzzle 

Given two strings ransomNote and magazine,
 return true if ransomNote can be constructed from magazine and false otherwise.
Each letter in magazine can only be used once in ransomNote.


Given two strings: ransomNote && magazine
- magazine will have letters in it
magazine = [ abcdabcssfjhksdjfhsdlfoaoiwefw]
ransomNote= [ pay twenty dollars ]

set up boolean function: lettersExist ( ransom , magazine) takes in 2 strings as parameters

1. Iterate through magazine string characters
2. For each character in magazine, compare to ransom note
3. If the letter is found in the ransom note string, remove it 
4. Move on to the next character in magazine, repeat steps 2 & 3

5. Else (letter from ransom note is not in not in magazine)
	exit for loop and return false for boolean function 

6. Otherwise (every letter in ransomnote was found in magazine, and subsequently removed from magazine)
then return true for lettersExist
