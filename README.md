# MONSTER-HUNTER-SUNBREAK-CALCULATOR
Using sql and python to calculate damage output in the game Monster Hunter Rise: Sunbreak

This was just a practice project for me to incorporate sql with python. I like using math to find the best sets in a game I love, so I picked this damage calculator as a project. It may seem simple, but there are thousands of combinations of stats, so using a set of databases to determine which pieces were selected was a natural function of the program. After selecting pieces, its just algebra.  

Usage instructions:
*You need sqlite to use this program. I used Pycharm for coding, so adjust your pathing accordingly.* 

1) download the files
2) make sure the files are all loaded into python onto the same project and folder, so that the call functions can access them. 
3) run main
4) hit option 0 to load up the tables into the program. It will generate databases for sqlite to read from. 
5) hit 1 to select weapons and monsters
6) hit 2 to select skills (optional)
7) hit 3 to select motion values/ your attacks. Hitting 3 before option 1 will give you a warning and loop back to the main menu.  
8) hit 9 to exit

NOTE: When updating tables, you can make direct changes to the tables, then you hit option 0 to reset your databases and reload the updated data into them. 

version 1 (complete)
-does not have any error handling, so you need to have perfect inputs. 

version 1.1 (complete)
-weapons, monsters, parts, and skill lists will be remembered until you exit the program or overwrite inputs manually. 
-has basic error handling. Wrong inputs will force an exit from the current loop back to main menu. 
-lacks restrictions that would be 'illegal' in game. (ie attack up 7 and attack up 5 in the same skill pool). 

version 1.5 (complete)
-finished skills and monster databases associated exceptions. 
  -dragon conversion
  -handicraft/sharpnes upgrade
  -conditional/non conditional boosts
  -same skills, but with different levels loaded into the same list
-refer to 0 input for exact input syntax.
