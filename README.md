# Linux-Cmd-Line-Hack-Chapt-2
Command Line Hacker: A hands-on self taught projects on Linux administration and cybersecurity

# Title: Linux Chapter 2 Exercises - Working with Text

## Objective: In this chapter, we focus on text manipulation using Linux commands like grep, sed, head, and tail. These exercises improve our ability to handle large text files in system administration.

## Table of Contents
1. [Grep and Text Processing](#grep-and-text-processing)
2. [Working with Large Files](#working-with-large-files)
3. [Extracting Data from Logs](#extracting-data-from-logs)

Exercise 1: Grep and Text Processing:
- ## Grep and Text Processing

    ### Command Used:
    -    grep -n "tomato" MyFavoriteRecipeWithNumbers.txt > Documents/NoTomatoRecipe.txt
    ### Files Used:
    - MyFavoriteRecipe.txt
### Explanation:
    - In this exercise, the grep command is used to find occurrences of the word "tomato" in the MyFavoriteRecipe.txt file and output the result with line numbers into a new file, NoTomatoRecipe.txt.
### Output:
    - 3: tomato paste
    - 7: cherry tomatoes


#Exercise 2: Working with Large Files:
## Working with Large Files
### Command Used:
    - head -n 20 ~/Documents/LongScript.sh
    - tail -n 20 ~/Documents/LongScript.sh
### Files Used:
    - LongScript.sh
### Explanation:
    - In this exercise, the head and tail commands are used to display the first and last 20 lines of a long
      shell script file. This allows for efficient navigation of large files without opening the entire document


#Exercise 3: Extracting Data from Logs:
## Extracting Data from Logs
### Command Used:
    - grep "error" ~/Documents/system.log
### Files Used:
    - system.log
### Explanation:
    - This command searches for any instances of the word "error" in the system log file. This is useful for
      quickly identifying system issues


#Exercise 4: Scripting with Sed:
## Scripting with Sed
### Command Used:
    - sed -n '/Meeting Start/,/Meeting End/p' MeetingNotes.txt > ExtractedMeetings.txt
### Files Used:
    - MeetingNotes.txt
### Explanation:
    - Using sed, we extract all lines between "Meeting Start" and "Meeting End" in the MeetingNotes.txt
      file. The output is saved to a new file, ExtractedMeetings.txt.


## Conclusion
After completing Chapter 2, I have gained a deeper understanding of how to manipulate text in Linux
using core tools such as grep, sed, and head. These skills will be invaluable when working with large
log files and performing system administration tasks.