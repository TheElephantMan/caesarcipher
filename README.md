This is a simple little Caesar Cipher program that has the ability to Encrypt a message, Decrypt a message, or Brute Force an encrypted message that you don't know
the shift key of. The program is pretty self explainitory but choose 1 to encrypt 2 to decrypt or 3 to brute force.

For option 1:

The program will have you enter a message that you want encrypted. After that it will ask you to choose a shift key (1-26) this will be how many places your message is shifted so for example with a shift of 1 A=B B=C C=D etc. After that it will print your message and then say This is your encrypted message. Copy that and use it as you like.

For option 2:

If you have a message that is already encrypted it will ask you to enter your encrypted message. After that it will ask you for the shift. Here you will enter the number entered in the encryption so for example if you encrypted the message using 6 as your shift you will enter 6 again when it asks for the shift key. It will then print your decrypted message and then say This is your deciphered message. 

For option 3:

Using the brute force option will run all 26 shift keys and print them out. You will need to scroll through the list that was printed to find your message. All this option will ask you to do is enter your encrypted message and then will print out a list containing all the possible options.

From the `email-bot` directory:
```python -m venv pyenv```
```source pyenv/bin/activate```
```python3 -m pip install -r requirements.txt```
