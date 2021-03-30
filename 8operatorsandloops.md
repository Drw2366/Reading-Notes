#### You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a *Boolean*: TRUE OR FALSE
![image](https://user-images.githubusercontent.com/74502839/112921585-04eee480-90d9-11eb-9adb-31f5990c2308.png)
# Comparison operators usually return single values of TRUE or False. Logical operators allow you to compare the results of more than one comparison operator
![image](https://user-images.githubusercontent.com/74502839/112922020-c279d780-90d9-11eb-9f96-263023e41123.png)
![image](https://user-images.githubusercontent.com/74502839/112922320-4d5ad200-90da-11eb-8902-f193397cbfc0.png)
# Loops
#### Loops checks a condiction. If it returns true, a code block will run.
#### Then the condition will be checked again and if it still returns true, the code block will again run again. It repeats until the condition return false. There are three common types of of loops.
# 1. For
# 2. While 
# 3. Do While
# In a *FOR* LOOP, the condiction is usaually a counter which is used to tell how many times a loop should run
# In a *WHILE* LOOP, the condiction can be something other than a counter, and the code will continue to loop for as long as the condiction is true.
# The DO...WHILE LOOP, is very similar to the *while* loop, but has one key difference: it will alaways run the statements inside the curly braces at least once, even if the condiction evalutes to *false*

![image](https://user-images.githubusercontent.com/74502839/113020518-ad8c5b00-9150-11eb-9f11-09c766024c8d.png)
# Initialize Variable
#### Whenever you are counting, you need a variable to keep track of the count. The first part of the for loop sets up the variable, often called i, that will be used to count the number of times the loop will run. 
#### This also sets up the starting value at which to start counting. The variable is set up before the loop is run and then that code is not returned to throughout subsequent runs through the for loop.
# Condition
#### The condition determines how long the loop runs. It should be dependent on the variable you initialized in part 1 of the loop. The condition is checked before entering the for loop each time, including the first.
#### The loop stops as soon as this condition is no longer true.
# Increment
#### The last piece of the for loop is the increment. It is the update piece of the loop. In order for the starting value of the variable to change we must update it each time through the loop. That is what the increment is used for. 
#### The increment is run at the end of each run through the for loop. i++ is just short hand for i = i + 1, which you might recognize as the counter pattern.

![image](https://user-images.githubusercontent.com/74502839/113021267-6b174e00-9151-11eb-99a6-959986602913.png)
