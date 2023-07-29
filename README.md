Python code

import random 
def roll_dice():
  while True: 
       dice_result = random.randint(1, 6) 
       print(f"You rolled a {dice_result}!") 
       user_choice = input("Do you want to roll again? (yes/no): ").lower() 
       if user_choice != "yes":
            break 
      Print("Let's roll the dice!")
      roll_dice() 
