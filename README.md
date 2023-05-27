# MONSTER-HUNTER-SUNBREAK-CALCULATOR
Using sql and python to calculate damage output in the game Monster Hunter Rise: Sunbreak

This was just a practice project for me to incorporate sql with python. I like using math to find the best sets in a game I love, so I picked this damage calculator as a project. It may seem simple, but there are thousands of combinations of stats, so using a set of databases to determine which pieces were selected was a natural function of the program. After selecting pieces, its just algebra.  

Usage instructions:
You need sqlite to use this program. 

1) download the files
2) make sure the files are all loaded into python onto the same project and folder, so that the call functions can access them. 
3) run main
4) hit option 1 to load up the tables into the program. It will generate databases for sqlite to read from. 
5) hit option 2 to select your weapon, monster and monster body part. 
6) hit option 3 to select your skills
7) hit option 7 to select your number of hits and which moves you are using. It will then calculate the final damage. 
8) you can input any of the options to change your damage, or just quit. 

NOTE: When updating tables, you can make direct changes to the tables, then you hit option 0 to reset your databases and option 1 to reload the updated data into them. 

version 1
-does not have any error handling, so you need to have perfect inputs. 

version 2 goal
-interface is archaic and will aim for formal UI. 

version 3 goal
-store results into a database to perform analysis with. 

version 4 goal
-make this program an app (if possible)


