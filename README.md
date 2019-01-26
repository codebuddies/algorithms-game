# Harry Potter Algorithms Practice Game

You enter the game as a muggleborn witch/wizard during Harry's first year, and are sorted into Ravenclaw. You have to solve common CS algorithms in order to unlock the entrance to Ravenclaw Tower, pass your classes, win house points, and ultimately help Harry and his friends defeat Voldemort in your seventh year. 

How to solve an algorithm in this game:
- You will see scrambled blocks of code comments you can drag around on the right, and code on the left. Each code comment will correspond to a chunk of code.
- Click and drag the steps to solve the algorithm. Once they are in the correct order, you will unlock the algorithm and can move on to the next stage of the story.

# How do I contribute?
There are three ways you can contribute:
1) File an issue containing an algorithm problem and its solution
2) Add a card to the storyboard
3) Contribute to the codebase (Django/React app) that builds the game

## 1) Contribution type: Algorithms

1/ Create a new issue

2/ Fill out the following template:
```
**Problem**: 
#The name of the problem

**Examples**: 
#Example Test Cases

**Difficulty**: 
#Easy, Medium, or Hard

**Language**: 
#You can pick any language

**Steps to Solve**: 
#Write out the high-level steps you would take to solve this problem. Please make sure each of your steps correspond with the code solution below.

**Code Solution**: 
#Paste, using triple backticks, your solution to the problem. You can include a repl link instead of pasting the full solution, if you want

**OPTIONAL Notes**: 
#Add optional notes here about the solution (e.g. if it was recursive) 

**OPTIONAL Storyboard Notes**: 
Share any ideas about how this problem could be used in the story. Optional.

**OPTIONAL Source**: 
#Where did you get the problem? Is it from Cracking the Code Interview? Leetcode or Hackerrank? A blog or website? You can optionally share the source here. 
```

### Example:
```
**Problem**:
Reverse a String

**Examples**: 
reverseString(“hello”) should become “olleh”
reverseString(“world”) should become “dlrow”
reverseString(“wizard”) should return ”draziw”

**Difficulty**:
Easy

**Language**:
Javascript

**Steps to Solve**: 
Step 1. Use the split() method to return a new array
Step 2. Use the reverse() method to reverse the new created array
Step 3. Use the join() method to join all elements of the array into a string

**Code Solution**: 

function reverseString(str) {
    var splitString = str.split(""); 
    var reverseArray = splitString.reverse(); 
    var joinArray = reverseArray.join(""); 
    return joinArray;
}

**OPTIONAL Notes**: 
Assumes we can use built-in javascript functions

**OPTIONAL Storyboard Notes**: 
Could use this problem for a Mirror of Erised scene. (The task: read "Erised" backwards)

**OPTIONAL Source**: 
https://medium.freecodecamp.org/how-to-reverse-a-string-in-javascript-in-3-different-ways-75e4763c68cb
```

## 2) Contribution type: Storyboard

Please request to be added as a contributor to github.com/codebuddies. Then, add a card to [https://github.com/codebuddies/algorithms-game/projects/1](https://github.com/codebuddies/algorithms-game/projects/1).


## 3) Contribution type: Codebase

Look for the issues labeled `codebase`

