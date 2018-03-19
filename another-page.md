---
layout: page
title: Another Page
---

This program lets the user pick a number between 0-2 and the computer also chooses a number between 0-2 whoever chooses the number that's higher wins the game. 

print("Hi please pick a number. Your choices are 0, 1, 2. The number with whoever randomly picks the higher number wins!") 

user_choice = int(input())

import random 
print ( 3 , 2 , 1 )

b = "0!" 
a = "1!" 
m = "2!"

dice_roll = random.randint(0,2)
print ("Computer chose..")
if dice_roll == 0: 
    print(b)
if dice_roll == 1:
    print(a)
if dice_roll == 2:
    print(m) 
    
if user_choice == dice_roll: 
    print("It is a tie")
elif user_choice == 0: 
    if dice_roll == 1: 
        print("The computer wins!")
    else: 
        print("The computer wins!")
elif user_choice == 1: 
    if dice_roll == 0: 
        print("you win!")
    else: 
        print("The computer wins!") 
elif user_choice == 2: 
    if dice_roll == 1: 
        print("you win!")
    else:
        print("The computer wins!")
elif user_choice == 2: 
    if dice_roll == 1: 
        print("The computer wins!")
    else: 
        print("you win!")
elif user_choice == 2: 
    if dice_roll == 0: 
        print("you win!")
