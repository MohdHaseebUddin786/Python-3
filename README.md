# Python-3
'''
Dice Roller Game
'''

import random <br>
def roll_dice(): <br>
    print("Welcome to the Dice Roller Game!") <br>
    while True: <br>
        input("Press Enter key to roll the dice...") <br>
        dice = random.randint(1, 6) <br>
        print(f"You rolled a {dice}!") <br>
        
        # Ask user if they want to roll again
        choice = input(" Do you want to roll again the Dice? (yes/no): ").lower()
        if choice != 'yes':
            print("Thanks for playing the dice roller Game! Goodbye!")
            break

# Run the dice roller
roll_dice()
