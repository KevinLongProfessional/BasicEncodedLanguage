# BasicEncodedLanguage
This code will take a given string and an input file defining how it should be encoded and spit out the result. As my use case was limited, there are several limitations on this. It is capable of replacing words and characters with other strings and that's all it is meant to do. 

Input will be converted to upper case before processing, as my initial use case was creating a font file to use for a fictional writing system that has more than 26 characters. Thus I encoded some of the extra characters as lower case characters.

To run this code, navigate to it from a bash terminal and then type the following

./Encode "Hello World!"

It should then print out "basic example." It should be pretty straightforward to modify the encoding as the script is very short. I hope someone else finds this script to be useful.
