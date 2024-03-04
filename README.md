# Morse Code Encoder

This Python script converts text into Morse code. It utilizes a dictionary for character mapping and handles user input gracefully. Additionally, it provides whitespace handling for word separation.

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/p0sin/morse-code-encoder.git
   cd morse-code-encoder
   ```

2. **Run the script:**
    ```bash
    python main.py
    ```

3. **Run the script:**
 Follow the prompts to enter the text you want to encode. The script will output the corresponding Morse code.  

# Morse Code Dictionary

The morse_code_dict dictionary maps characters to their Morse code representations. It includes letters (A-Z), numbers (0-9), and some punctuation marks.

```
morse_code_dict = {
    'A': '.-', 'B': '-...', 'C': '-.-.', ...,
    '0': '-----', '1': '.----', '2': '..---', ...,
    '.': '.-.-.-', ',': '--..--', '?': '..--..', ...,
    ' ': '       ',
}
```

Feel free to explore and modify the dictionary based on your needs.

# Contributing

If you would like to contribute to this project, please open an issue or submit a pull request. Contributions are welcome!