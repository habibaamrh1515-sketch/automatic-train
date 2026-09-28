# land escape game
land escape game
Project Title: Treasure Island - Text-Based Adventure Game

Description: Treasure Island is an interactive, text-based adventure game built with Python. The project is designed to demonstrate core programming concepts like conditional logic (if/else), user input handling, and string manipulation in a fun and engaging way. The player is placed in a survival scenario where every decision determines their fate.

Key Features:

           .Interactive Storytelling: A branching narrative where user choices directly affect the game outcome.
           .Case-Insensitive Input Handling: Implemented using .lower() method to ensure the game accepts LEFT, Left, left without errors, improving User Experience (UX).
            Error-Free Input Parsing: Solved common string quotation conflicts by using alternate quote nesting to allow double quotes inside prompts.
            .Clean Conditional Logic: Uses nested if/else statements to create multiple game-ending scenarios (Win / Game Over).
Technologies Used:

            .Language: Python 3.13
            .IDE: PyCharm
            .Concepts Covered: Variables, input(), print(), if/elif/else, String Methods .lower()
How To Play:

1.The game starts at a crossroad.
2.Player must choose left or right.
3.Choosing right -> Instant Game Over (fall into a hole).
4.Choosing left -> Player reaches a lake and must choose to wait for a boat or swim across.
5.Only the correct sequence of choices leads to finding the treasure.
##Image project [https://www.amazon.eg/-/en/Festivous-Wishel-Treasure-Decorations-Simulation/dp/B07VDJMXQ7]

choice1 = input('where do you want to go? type "left" or "right": ').lower()

image project
image here

else: choice2 = input('type "wait" to wait for a boat or type "swim": ').lower()
