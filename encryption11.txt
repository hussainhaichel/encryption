alphabet = 'abcdefghygklmnoprstuvwxyz'
key = 3
newMassage = ''
message = input('please enter a message:')
for character in message:
  position = alphabet.find(character)
  newPosition = (position + key)%26
  newCharacter = alphabet[newPosition]
  print('the new character is: ', newCharacter)