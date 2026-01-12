# Process Writeup

## Name: Uday A
## Course: SEP 10
## Period: 2
## Concept: CLI

### Section: Context
 In the software engineering program so far we started to learn CLI and CLI commands. learning CLI was incredibly important due to us using for the rest of the year CLI we will be using it to complete assignments and other things. The goal was to be able to understand CLI to learn how to use cs50.dev . When learning CLI we learned it stands for Command lline-interface, and how important it is for every assignment we may do in the future. We learned,
* (ls) which lists the current files we are currently on at the time to check where we are in between files like double checking
* (mkdir) which make a directory like a file to work with and youcan name it to what you want it to be named.
* (rmdir) which is to remove a directory/file which is important to understand just in case you made a file or directory you dont want
* (mv) which renames another file only if one of two files already exist but if both files exist the first file you put would go under the second file you put
* (rm -rf) which delete the directory you put next to it and deletes whatever is in it no matter what.
* (cd) which is the  most important command to switch from other directorys and or files.

Learning all of this in a short period of time came with its challenges. Most challenging for me was to understand how exactly mv worked in moving files and changing their names.

### Goal
The main goal was to understand CLI concepts but specifically for me I wanted to understand how to make files and how i could organize them. One specific project is when we tried to recreate a tree of files in order and in the shortest usage of lines of code.

### Process
To make the shortest line of code to make the tree correctly, me and my partner split up the work evenly. We decided that I would take the creating the 
lines of code
mkdir (something) cd (something) mkdir (something2) mkdir (something3) and so on
```
 My partner tested the code and used
ls (something) cd (something) ls (something1 something 3)
to fact check We decided that he would help correct me on mistakes and I would do the work again and look over my errors. We worked through all of the easy stuff until we noticed that we couldn't go back to the parent directory. We had to refer to our unit 2 notes everytime we had a question. The question that we had trouble answering is how to go to the parent directory. Ultimately we understood and got it.

### Challenge 1
The first challenge I faced was with
mkdir (something) 

When trying to make a directory I kept misspelling mkdir and it wasn't working. I sat for 10 minutes going over my notes to try and understand why it wasn't making the directory. When I asked my partner he looked and realized I was misspelling the code but now i wont make that mistake again.
```CLI
 cd (back to parent directory)
```
When I added a directory I realized that I didnt know how to get out of it and enter the parent directory. I then went through the notes i had and relized all i had to do was cd .. to get to the parent directory. Then I tried it out and realized that it worked. That problem was quickly resolved when I realized how to get back to the parent directory.
### Challenge 2
The second and final challenge we faced was to correctly figure out the comand line mv . using mv were one of the hardest topics for me to understand. My partner struggled as well to use mv correctly and effiectiently. When trying to name a file something else we accidently kept switching files over.
```CLI
  mv (happy) (angry) 
```
We thought that the command line mv would change the name of the directory. So we used mv but quickly realized the names weren't correct and that the files were just switched. So we went back to our notes and asked other friends if they could check our work. Eventually one of our friends helped us realize that if both files are already in existence they will jsut switch spots and not be renamed. We then used mv to rename the directory correctly by using the name and adding 1 next to it. Then we saw that all the files and directorys were corecttly placed so we were finally reliefed.
```HTML
    <p>Which of the following is Java used for?</p>
  <label> 
      <input id="IOS" value="IOS" type="radio" name="topic" >IOS
  </label>
    <p></p>
  <labeL>
        <input id="Android" value="Android" type="radio" name="topic" >Andriod
  </labeL>
    <p></p>
  <labeL>
        <input id="Windows" value="Windows" type="radio" name="topic" >Windows
  </labeL>
    
    <p></p>
```
This separated the Radio buttons and allowed our radio buttons to be clear and concise.
### Result
The result ended is this:
* [Command line Challenge](https://classroom.google.com/c/ODAxMzIzMTE0NDAy/a/ODM3MTg0MjEwOTQz/details)
### Takeaways
This coding challenge taught me how important it is to reference notes and ask others. From now on I will try to take better notes for Free Code Camp lessons and what I don't understand. When I looked for the tags I was missing in my notes they were completely missing. I had to ask Essie and Simran to help me. I noticed they were able to help me because they had comprehensive notes that completely detailed what we learned. I plan to continue to update the HTML section of my notes to fill in the gaps of my knowledge. For the next Unit I will make sure to take notes on things I don't understand instead of having to be stuck and go back to Free Code Camp. 
