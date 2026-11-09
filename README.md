# cis165-lab8

Plan
Create a program that calculates the Area of a circle, rectangle and triangle and use if/else statements to give the person using the program a choice. Ending the Program when the person using it selects 4.


Tests 

Test / data	                              Expected result
Choice 1, radius 2	              Area 12.56636, subject to the display precision you state in the README.
Choice 2, length 3, width 4.5	              Area 13.5.
Choice 3, base 5, height 3	                Area 7.5.
Choice 4	                        Ends without dimension prompts or an area calculation.
Choice 0,then a separate run with choice 5	Each displays an invalid-choice error.
Separate runs: radius -1; rectangle length -1; rectangle width -1; triangle base -1; triangle height -1	Each displays an error; use positive values for any other dimension.
Choice 1, radius 0	                          Area 0.

Choice 1, radius 14                           Area 615.752
(Checking area of a circle with radius 14)

All Expected Results Match The Output.


How does your selection logic send each choice to the right calculation?
- By Using the if/else statements to check the number the person choses
  
Why is radius * radius correct while radius ^ 2 is not?
- Because ^2 doesn't work in C++ so you have to do it that way.
  
Why does the triangle calculation use 0.5 rather than integer division 1 / 2?
- So that it uses multiplication with decimals instead of integer division.
  
Where do you check negative dimensions, and how do you handle zero and choice 4?
- The code checks if any of the numbers are negative before the calculations, and will give an error if there is a negative. 0 is allowed and choice 4 just ends the program.


To run in onlineGDB open the file on the site check to see if its on c++ 17 then input a number 1-4 and values asked to run the code.
