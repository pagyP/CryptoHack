## Task 1
- Run great_snakes.py for the flag

## Task 2
- ASCII is a 7-bit encoding standard which allows the representation of text using the integers 0-127.
- Using the below integer array, convert the numbers to their corresponding ASCII characters to obtain a flag.
- [99, 114, 121, 112, 116, 111, 123, 65, 83, 67, 73, 73, 95, 112, 114, 49, 110, 116, 52, 98, 108, 51, 125]
- In Python, the chr() function can be used to convert an ASCII ordinal number to a character (the ord() function does the opposite).

## Task 3
- When we encrypt something the resulting ciphertext commonly has bytes which are not printable ASCII characters. If we want to share our encrypted data, it's common to encode it into something more user-friendly and portable across different systems.
- Hexadecimal can be used in such a way to represent ASCII strings. First each letter is converted to an ordinal number according to the ASCII table (as in the previous challenge). Then the decimal numbers are converted to base-16 numbers, otherwise known as hexadecimal. The numbers can be combined together, into one long hex string.
- Included below is a flag encoded as a hex string. Decode this back into bytes to get the flag.
- 63727970746f7b596f755f77696c6c5f62655f776f726b696e675f776974685f6865785f737472696e67735f615f6c6f747d
- In Python, the bytes.fromhex() function can be used to convert hex to bytes. The .hex() instance method can be called on byte strings to get the hex representation.


