import random
import string

characters = " " + string.punctuation + string.digits + string.ascii_letters
characters = list(characters)
key_word = characters.copy()

random.shuffle(key_word)

print(f"characters: {characters}")
print(f"key_word : {key_word}")

#Encryption
plain_text = input("Enter word or message to encrypt: ")
cipher_text = ""

for letter in plain_text:
    index = characters.index(letter)
    cipher_text += key_word[index]

print(f"original message: {plain_text}")
print(f"encrypted message: {cipher_text}")
