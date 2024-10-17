
# Secret Code Program

This Python program lets users encode or decode a word or phrase. Based on the length of the word, it either manipulates the string in a specific way or simply reverses it.

## Features

- **Encode**: Modifies words by rearranging their characters and adding predefined characters.
- **Decode**: Reverts the encoded words back to their original form.

## How It Works

### Encoding

1. If the word is 3 or more characters long:
   - The first character of the word is moved to the end.
   - A string `char1 = "jhg"` is added at the beginning, and another string `char2 = "bas"` is appended at the end.
   - The final result is printed as the secret code.

2. If the word is less than 3 characters long:
   - The word is simply reversed.
   - The reversed word is printed as the secret code.

### Decoding

1. If the encoded word is 3 or more characters long:
   - It removes the first 3 characters (`jhg`) and the last 3 characters (`bas`).
   - The last character of the remaining word is moved to the front to reverse the encoding process.
   - The decoded word is printed.

2. If the word is less than 3 characters long:
   - The word is reversed back to its original form.
   - The reverse word is printed.

## How to Use

1. Clone or download this repository.
2. Run the `secret_code.py` file.
3. Choose either the encoding or decoding option when prompted.
4. Enter the word you want to encode or decode.
5. View the secret code or decoded word displayed in the console.

### Example

**Encoding:**

```bash
Do you want to code or decode the program? code
Enter a string: hello
Your secret code is: jhgellohbas
```

**Decoding:**

```bash
Do you want to code or decode the program? decode
Enter the words to be decoded: jhgellohbas
Your decoded word is: hello
```

## License

This project is open-source and freely available for use.
