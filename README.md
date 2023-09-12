# rock-paper-scissors-game
Play with computer 

import random

Rock = """
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
"""



Paper = """
     _______
---'    ____)____
           ______)
          _______)
         _______)
---.__________)
"""



Scissors="""
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
"""



game_name =[Rock,Paper,Scissors]


user_choice=int(input("enter your choice here type 0 for Rock 1 for Paper 2 for Scissors.\n"))

p
rint(game_name[user_choice])


computer_choice=random.randint(0,1)

print(computer_choice)

print(game_name[computer_choice])

if user_choice >=3 or computer_choice <0:
    print("invalid type you lose the round")

elif user_choice == 0 and computer_choice == 2:
    print("you win")

elif computer_choice == 0 and user_choice == 0:
    print("you lose")

elif computer_choice > user_choice:
  print("You lose")

elif user_choice > computer_choice:
  print("You win!")

elif computer_choice == user_choice:
  print("It's a draw")
