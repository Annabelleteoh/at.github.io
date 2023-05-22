# Lab Report 4


## Step 4 - Log into ieng6

## Step 5 - Clone your fork of the repository from your Github account
Keys pressed: <Command-C> git clone https://github.com/Annabelleteoh/lab7
 
![Image](https://github.com/Annabelleteoh/at.github.io/blob/main/git%20clone.png) 
  
## Step 6 - Run the tests, demonstrating that they fail
Keys pressed: <up><up><up><up><enter>, <up><up><up><up><enter> The javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java command was 4 up in the search history, so I used up arrow to access it. Then the java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ... command was 4 up in the history, so I accessed and ran it in the same way.
  
![Image](https://github.com/Annabelleteoh/at.github.io/blob/main/test%20failure.png)
  
## Step 7 - Edit the code file to fix the failing test
Keys pressed: 
  
vim ListExamples.java <enter> 
  
<down> all the way to the last index1 variable in merge, <right><right><right><right><right><right> to move cursor over "1" <x> to delete "1"

<a> <2> to append "2"
  
<esc> to go back to normal mode
  
<:wq> to save
 
 ![Image](https://github.com/Annabelleteoh/at.github.io/blob/main/file%20changes.png)
  
## Step 8 - Run the tests, demonstrating that they now succeed
  
Keys pressed: <up><up><up><enter> the javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java command was 3 up in the search history, so I used up arrow to access it. Then the java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ... command was 3 up in the history, so I accessed and ran it in the same way.
  
[Image](https://github.com/Annabelleteoh/at.github.io/blob/main/test%20sucess.png)

## Step 9 - Commit and push the resulting change to your Github account (you can pick any commit message!)