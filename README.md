Coarse: CS 30
Period: 3
Date created: 20/09/21
Date last modified: 16/10/21
Name: Rabi Jasteen Juancito
Description: Adventure Game



Gameplan layout

Title : Mantik Village

# Ask the user to enter the game
print message: "Would you like to enter the game?" 

if user wants to play the game: user press ENTER
# After the user ENTER 
print message: “Hey Traveler! I’ve been waiting for your arrival, you finally came. Welcome to Mantik Village! This is going to be quite an adventure. ”

print another message: “Before we begin, here is a provided list of variables you can input to guide you along the way of your quest. You can also remember it as an algorithm: CEHIM

c = continue
e = exit
h = help
i = inventory
m = map

print message: “Input c to Continue the game”
# After user input C
print message about the plot of the game: “You along with thousands of locals died after an explosion that occurred when Zuko, the greatest enemy of them all invaded the Mantik village. You have now been reincarnated and are taking revenge to destroy Zuko. In order to destroy him you must find 2 special amulets to assemble back together. The amulets are found in 2 different territories, Monu territory and Gozen territory.”

print another message: “Well, before we begin our adventure. Choose a character:”
# List of available characters 

Kuro:
# Print a nested dict of Kuro’s inventory 
Kuro’s Inventory:
Level: 1
Default weapon: Sword
Damage: 0
Kills: 0
Max energy: 1.472
Protection: 10


Adachi:
# Print a nested dict of Adachi’s inventory 
Adachi’s Inventory:
Level: 1
Default weapon: Bow & Arrow
Damage: 0
Kills: 0
Max energy: 1.257
Protection: 17


# After user pick Kuro or Adachi:
print message: “Pick one friend to accompany you through your quests:

Attaku: 
print background info: Attaku was a former intelligent criminal investigator in Hashusai, his hometown in Japan. He is strong and has the ability of mind control and compels others to do as he wishes through physical contact.

Sorn: 
print background info: Sorn is a 12th grade student from Pohwet high school who is really fast and ability to make items disappear or come 

Harit: 
print background info: Harit is an intelligent former electrician from Isle Stadt where he used to work and discovered his powers. He has the ability to control electrical wave using his hands

Mako: 
print background info: Mako was born and raised in a small province called Neaustra Island. She is a former athlete and has the ability to mimic anything by watching it.


# After user chooses their companion
Print message: “Great! Now that we have our characters and companions chosen. Here are your lists of actions and directions:”

Actions = [attack, defend, heal, special ( 5 speed boost, 25 jump, 4 fly), quit]

Directions = [up, down, left, right]


Print another message: “Alright! Shall we begin our adventure? I can wait to destroy Zuko. Let’s Go!”

User input c to continue…
# First destination to find the first amulet
print message: “Welcome to the Monu Clan! Warning this place has many scattered enemies. Be careful! You goal is to go to get to the waterfall that is 800 km away to the North and find the amulet”

       

# Direction and action function after user inputs    
def actions_function():
“““print the list of actions for users to input”””
for a in actions:
print(f"- {a}")
action_input = input("Action: ")

def direction_function():
“““print the list of directions for users to input”””
for d in directions:
print(f"- {d}")
direction_input = input("Go: ")


print message: “Watch out!! Your first company just spotted you. Hurry! What do you want to do?”
action_input()


if action_input = “attack”:

elif action_input = “defend”:

elif action_input = “heal”:

elif action_input = “special”:

elif action_input = “quit”:


else: 
print: (invalid direction)




Map:


if user doesn’t want to play the game: 
print message: “Awh that’s too bad. I hope you come back again next time! Bye Bye!”
exit()



