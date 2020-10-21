# Hangman and Decryption Project
- - - - - - - - - - - -
## Part 1: Implementation of the Hangman Game

The game begins with a greeting after prompting for the user's name. After a brief introduction, the user is asked if they would like to play the game.
If yes, the Hangman function is called and the game begins.

Next, the program randomly selects one word from this list: words = [“WHDSPQZ”, “XHO”, “TTDBFRT”, “QQJYF”, “ENQD”, “DNPK”, “CNTR”, “EHWHOD”, “TSVMOHOF”, “XNOCFQGTM”]
where the user is allowed 10 attempts to guess the word. The word is decoded *only* if the user guesses correctly before attempts are exhausted.

**Special Note**: This version of the program assumes only alphabetical input in the guessing portion of the game's implementation. Non-alphabetical input counts against the user's remaning guesses.
- - - - - - - - - - - - - 
## Part 1.2: Flowchart for the Hangman Game

![flowchart](https://github.com/lisalynn7/hangman-and-decryption/blob/main/hangmangame.png)
- - - - - - - - - - - - - 
## Part 2: Behind the Hangman encryption
The original words were previously **encrypted** using the logic from the following Flowchart: 

![flowchart](https://github.com/lisalynn7/hangman-and-decryption/blob/main/encode.png)

- - - - - - - - - - - 
## Part 2.1: Implementation to deocde the guessed word
I designed the flowchart below for the decryption mechanism and implemented it in the **decrypt()** function. The function takes the game's generated word from the list (ciphertext) as the parameter. It then returns the encoded message (plaintext) if the user wins the game. 

![flowchart](https://github.com/lisalynn7/hangman-and-decryption/blob/main/decode.jpg)
- - - - - - 
## Motivation :skull:
This project was created for INST126: Introduction to Programming for Information Science (Fall 2020)

## Authors
Walesia Robinson II
[@lisalynn7](http://github.com/lisalynn7)
