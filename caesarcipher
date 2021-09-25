import pycaesarcipher

word = pycaesarcipher.pycaesarcipher()

choice = input(''' Do you want to Encrypt, Decipher or Bruteforce? Type 1, 2, or 3
1 - Encrypt 
2 - Decipher
3 - Bruteforce 
--> ''')

if choice == '1':
    encrypt = input('Enter what you want to encrypt here. --> ')
    shift = input('For the shift, enter a number between 1 and 25. This will also be used to decypher later. -->')
    wordtoencrypt = word.caesar_encipher(encrypt, int(shift))
    print(wordtoencrypt + ' This is your encrypted message.')
elif choice == '2':
    decipher = input('Enter what you want to decypher here. --> ')
    shift = input('What is the shift key? It should be between 1 and 25 --> ')
    wordtodecrypt = word.caesar_decipher(decipher, int(shift))
    print(wordtodecrypt + ' This is the decyphered message.')
elif choice == '3':
    decipher = input('Enter code you want to decipher. ')
    for shift in range(1,26):
        wordtodecrypt = word.caesar_decipher(decipher, int(shift))
        print(wordtodecrypt)
else:
    print('Make a valid choice of 1, 2, 3.')
    
