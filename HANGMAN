import random 
stages = ['''
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
''', '''
  +---+
  |   |
  O   |
 /|\  |
 /    |
      |
=========
''', '''
  +---+
  |   |
  O   |
 /|\  |
      |
      |
=========
''', '''
  +---+
  |   |
  O   |
 /|   |
      |
      |
=========''', '''
  +---+
  |   |
  O   |
  |   |
      |
      |
=========
''', '''
  +---+
  |   |
  O   |
      |
      |
      |
=========
''', '''
  +---+
  |   |
      |
      |
      |
      |
=========
''']
rand_list=["harry","potter","hermoine","granger","ron","weasley","dobey","hagrid","dumbledoor","snape"]

chosen_word=random.choice(rand_list)
print(chosen_word)
display=[]
for i in range(0,len(chosen_word)):
  display.append("_")
life=6
while True:
  guess=input("guess a letter : ").lower()
  for i in range(0,len(chosen_word)):
    if chosen_word[i]==guess:
      display[i]=chosen_word[i]
  if guess not in chosen_word:
    if life>0:
      life-=1
      print(stages[life])
    else:
      print("you lose")
      break

if "_" not in display:
  print("you win")
  

  



  

  
