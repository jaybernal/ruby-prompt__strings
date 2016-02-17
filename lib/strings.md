---
title: Strings
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a String?

A string is anything within in quotes '' or ""

# What are some examples of information that would be Strings as opposed to some other data type?

Here are examples of Strings: '100' not a string 100, "Dog rule" "what the &*(*&^" 

# What is one way, using Ruby, to retrieve the 6th character in a String like `"Ada Lovelace"`? How about the 8th character? What happens if you try to retrieve the value of the _99th_ character (Or any character that doesn't exist)?

1. "ada lovelace" [6]   #the six character is 'v' but in ruby spaces are part of the character count. The six character is "o" the code would look like this  "ada lovelace" [5] . the reason is because the first number is actually 0 not 1, it called zero index

2. "ada lovelace" [7]
3. if you try to retrieve a value that doesn't exist, nil will return

# The previous question asks about finding, for example, the 6th character in a String. Is it possible to find the **-6th** (Notice the negative symbol!) character in a String? What does that even mean?

instead of searching from left to right, placing a negative will search right to left within the string.  also unlike before the negative does not search zero index.

# What is one way, using Ruby, to replace certain characters in a string with some other set of characters? For example, given `"Sumeet Jain"`, how would you replace all of the `e` characters in my name with exclamation marks? (So it would be `"Sum!!t Jain"`.)

"Sumeet Jain".gsub("e", "!")