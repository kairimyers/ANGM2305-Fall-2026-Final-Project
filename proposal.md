# Custom Character Creator

## Repository
<https://github.com/kairimyers/ANGM2305-Fall-2026-Final-Project>

## Description
The Custom Character Creator allows the user to choose what the character will be. This relevent to digital arts & media because we are generating new images from layers.

## Features
- Fullscreen Display
  - Use pygame to display a fullscreen window to display the characters creation.
- Character Role and Type Selecter
	- The user will be able to select what role their character can be. Role Examples: Warrior, Mage, Archer, etc. Type Examples: Human, Elf, Robot, etc. The selection done from the terminal or from the display.
  - Character models and accessories are hand drawn and saved as png files inside of the src/images folder.
  - Use pygame.image.load to display the role and type image options on the screen using the pre drawn image files.
  - We will use pygame.event to let the user click left or right to switch options. And the Enter Key to make selection.
- Character Randomizer
	- If the user doesn't want to create their own character then they can use the randomizer. The selection done from the terminal or from the display.
  - Use the random function to generate a random character using the R key with pygame.event.
- Full Character Saved and Displayed to User
  - Images from the selections will be merged using pillow into a new image that displays the final character. 

## Challenges
- How to give the user the ability to select the character options.
- How to merge images together to form the character.
- How to display the finished character to the user.

## Outcomes
Ideal Outcome:
- User has the ability to build their character visually on screen. The user will use keyboard commands or on screen buttons to make selections.

Minimal Viable Outcome:
- User has the ability to build their character using commands in the terminal. The user will answer prompts in terminal to make selections.

## Milestones

- Week 1
  1. Draw character models and accesories.
  2. Create base application code.

- Week 2
  1. Create code for merging images.
  2. Display merged image to user.

- Week N (Final)
  1. Build character selection in terminal.
  2. Build character selection on the display.