#Develop a "choose your own adventure" Python Script
#Challenge Treasure Island

print("Welcome to Treasure Island. ")
print("Your mission, should you choose to accept it, is to find the 'booty'... B) ")
choice1 = input('You\'re at a crossroad, where do you want to go? Type "left" or "right". ').lower()

if choice1 == "left":
    choice2 = input('You\'ve arrived at the edge of a lake. There is an island at its center. Type "wait" to wait for a boat. Type "swim" if you choose to swim across. ').lower()
    if choice2 == "wait":
        choice3 = input("You step off the boat and onto the island. Walking along a path you encounter a house with 3 doors. The doors are painted red, yellow, and blue respectively. Which colored door do you wish to walk through? ").lower()
        if choice3 == "red":
         print("It's a room full of fire. Burn baby burn!!! >:D -GAME OVER- ")
        elif choice3 == "blue":
         print("You walk into a room full of serpants. You are hisss-tory! >:D -GAME OVER- ")
        elif choice3 == "yellow":
         print("You have found the treasure! Enjoy your lifetime of riches $$$ ")
        else:
         print("Ooops, you can't swim...to the depths with you. -GAME OVER- >:D ")
if choice1 == "right":
 print("You fell into a hole. -GAME OVER- >:D ")
