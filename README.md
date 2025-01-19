# Python-3
'''
Dice Roller Game
'''

import random
def roll_dice():
    print("Welcome to the Dice Roller Game!")
    while True:
        input("Press Enter key to roll the dice...")
        dice = random.randint(1, 6)
        print(f"You rolled a {dice}!")
        
        # Ask user if they want to roll again
        choice = input(" Do you want to roll again the Dice? (yes/no): ").lower()
        if choice != 'yes':
            print("Thanks for playing the dice roller Game! Goodbye!")
            break

# Run the dice roller
roll_dice()
