# CS 426 - Asgn 4 - Nate Herrera

I adjusted overall visuals to be more aesthetically pleasing: fog, updated textures, etc. I chose neon colors to play into the theme of thieves and the overall futuristic tech aesthetic. Similar to coding IDE dark mode color schemes. The added barriers allow for more technical gameplay and to allow for unique moments by bouncing off the angled barriers or sneaking around players by hiding.

Physics Construct 1 (Collision) - Added bullet script, instead of deleting bullets on any impact they are deleted only when an item is tagged "Ground". The bounding walls are tagged this way to also delete the bullets upon collision.

Physics Construct 2 - Added Physics materials to bullets and newly added barriers. The properties allow the player to sneak along the barriers using friction and the bullets to bounce with bounce properties.

Billboard - Replaced existing billboards displaying part names with 2d transparent textures using the alpha channel and emission to make the signs stand out.

Lights - Added green Spotlight to highlight the green turn in post. Added Red light above player model (parented). Added Yellow light to bullet and emission.


# CS 426 - Homework 02

## Group Members:
Diego Bravo, Musa Elqaq, Nathaniel Herrera

----
# Project Overview:

This project revolves around exercise 4 of the CS 426 course at UIC.  Specifically, the goal of this project is as follows:

"This is a team-based assignment; you will work as a group along your assigned in-class group.  The result of this assignment will be a second Unity 3D game for your portfolio (the first being your Assignment 1). However, this game will be a (very, very) simple serious multiplayer networked game. For this assignment, your task is to continue working as a group and produce, in 14 days, a lightweight implementation of the simple mechanics game you designed in class. The reading next week (“How to Prototype a Game in 7 Days”, written by four game design students) may come in handy."

*[(via the project specification sheet)](https://docs.google.com/document/u/1/d/e/2PACX-1vRvnadYfHlk9rQSe9c8O7XEtAE2H5ivOPYtXa8XE8kKQnLCAeDaiRUcVDzPZUda2HLJSB-kuLp56zCx/pub)*

----

# Minimum Requirements:

Your game, while respecting the KISS principle (Keep It Simple, Silly)

- [x] 1.) Must be 3D, and

- [x] 2.) Must follow loosely a “Computer Architecture and Thieves” theme (your resources may be logical components, the goal might be to cache something, the environment might be inside a physical machine, your players might be thieves etc.) and

- [x] 3.) Must use at least one less common procedure/rule, in the vein of your Procedures/Rules exercise last week and

- [x] 4.) Must be a multiplayer, networked game, and

- [x] 5.) Must include a billboard with some text on it asking the serious test question, and

- [x] 6.) Must have a serious objective; i.e., by the end of the game, players should be able to answer correctly the test question you spelled out in E04. You may assume the test question would be answered outside the game, perhaps on paper; and

- [x] 7.) Must be accompanied by a README file with the names of your teammates, and briefly describing your FEs, including the multiplayer aspect, the unusual procedure/rule, how you followed the game theme, and the serious objective and question/answer. *(See section below the grading section.)*


Items 5) and 6) are extremely lightweight points.

As a reminder, the basic architecture of a computer typically looks like this:

<img width="700" alt="Basic Computer Architecture" src="https://github.com/user-attachments/assets/68fedc9b-958a-419b-861f-773030f9c342">

# Grading:

Grade will be based on:
- `20pts` design, quality and rigor of the 3D FEs (or formal elements)
- `20pts` at least one unusual procedure/rule
- `10pts` networking works
- `10pts` look and feel of your game aligned with the theme
- `10pts` billboard with serious question shown
- `10pts` README file
- `10pts` how much fun playing the game is

----

# Step 7 Response:
**Names:** Diego Bravo, Musa Elqaq, Nathaniel Herrera

**Formal Element Summary:**
Our formal elements included

**Multiplayer Aspect:**
Compete against another player to get all the parts first, while avoiding their attempts to sabotage you.

**Unusual Procedure/Rule:**
Players will have to choose between either turning in their parts, or converting them into bullets to use against their opponent.  This presents
them with a dilmena: Push myself forward, or push my enemies back?

**Adherence To Game Theme:**
We stuck with the game theme by modeling everything off the computer architecture diagram we were given when assigned this project.  Then we just added
more functionality and interactability for players.

**Serious Objective:**
The serious objective of this project was to provide a source of education in the field of engineering in a fun way.

**Serious Question/Answer:**
The serious question was "What are the physical components of a computer's architecture?".
It's answer would be the parts players collected, thus the expected correct answer for our serious objective: 
> - Arithmetic Logic Unit (ALU)
> - Control Unit
> - Memory
> - Input Devices
> - Output Devices
