# MONSTER-HUNTER-SUNBREAK-CALCULATOR
Using sql and python to calculate damage output in the game Monster Hunter Rise: Sunbreak

This was just a practice project for me to incorporate sql with python. I like using math to find the best sets in a game I love, so picked a calculator. It may seem simple, but there are thousands of combinations of stats, so using a database to determine which pieces were selected was a natural function of the program. After selecting pieces, its just algebra.  

Usage instructions:
You need sqlite to use this program. 

1) download the files
2) make sure the files are all loaded into python onto the same project and folder, so that the call functions can access them. 
3) run main
4) hit option 1 to load up the tables into the program. It will generate databases for sqlite to read from. 

NOTE: When updating tables, you can make direct changes to the tables, then you hit option 0 to reset your databases and option 1 to reload the data into them. 

version 1

the interface is text based, so its going to ask you questions for each variable. You select the 2nd option (calculating without skills) or 3rd option (calculating with skills). It will ask you for weapon name, monster name, hitzone, motion value(s), and skill(s). These variables will be searched from the 5 databases, and then plugged into the equation for a final damage number.  
