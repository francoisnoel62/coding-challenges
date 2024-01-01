
# CCWC - Count Characters, Words, and Lines

CCWC is a simple, yet effective, command-line utility written in Python for counting characters, words, and lines in text files or standard input. It's designed to be intuitive and easy to use for basic text analysis tasks.

## Features

- Count characters, words, and lines in a text file or standard input.
- Support for counting multibyte characters.
- Easy-to-use command-line interface.

## Installation

To use CCWC, you need Python installed on your system. No additional libraries are required.

1. Download the `ccwc.py` script.
2. Ensure it is executable (you might need to run `chmod +x ccwc.py` on Unix-based systems).
3. Optionally, you can add the script to your PATH for easier access.

## Usage

The basic command structure is:

```
ccwc [OPTION] [FILENAME] 
```

### Options

- `-c`: Count characters.
- `-l`: Count lines.
- `-w`: Count words.
- `-m`: Count characters (considering multibyte characters).
- `-h`: Display help and exit.

If no OPTION is specified, CCWC will count lines, words, and characters. If no FILENAME is specified, CCWC will take input from standard input.

### Examples

1. Count words in a file:

   ```
   ccwc -w myfile.txt
   ```

2. Count lines from standard input:

   ```
   cat myfile.txt | ccwc -l
   ```

3. Count characters, words, and lines in a file:

   ```
   ccwc myfile.txt
   ```

4. Display help:

   ```
   ccwc -h
   ```

## Inspiration
This code in ispired by https://codingchallenges.fyi, created by John Crickett

https://codingchallenges.fyi/challenges/challenge-wc
