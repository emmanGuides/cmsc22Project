# cmsc22Project



Simple Genshin Impact Gacha Simulator

##########################################################



Simulates the "Standard Banner" Gacha in Genshin impact in which:

- There are built-in 5 star characters, 5 star weapons, 4 star characters and weapons, and 3 star weapons
- Each 'Pull' from this Gacha simulator iterates through the random number generators in a method and returns a particular String from the Given parameters.
- 5 star weapons and characters have a Base Rate of .6% of dropping, and 4 star weapons/characters have a 5.1% rate
- "Hard Pity": If you've already had 89 'Pulls' from this Banner that no 5 star item/character is getting returned, the next pull (90th), will return a 5 star
-            - If you've already had 9 'Pulls' from this Banner that no 4 star weapon/character is getting returned, the next pull (10th), will return a 4 star
 
- "Soft Pity": If you're in the 60th and above 'Pull' without getting a 5 star weapon/character, the preceeding 'Pulls' will have their 5 and 4 star rate drops increased.

- You can also customize your own Banner, with your own elements be it 4 star, 3 star, or 5 star items and characters, with your own defined rates.
- This 'Personalized Banner' shares the same Hard and Soft pity mechanics with the Standard Banner.

*Creational - Singleton

*Structural - Facade

*Behavioral - Iterator

*Best practices used:              
- <2000 lines in src               
- Naming                           
- if-checks, indentations
- documentation
- exceptions
- etc.
