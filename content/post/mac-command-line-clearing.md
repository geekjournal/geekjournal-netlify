---
title: "Mac Command Line Clearing"
date: 2018-02-12T10:49:41-06:00
draft: false
---

Note, these commands work on a MAC using the Terminal program.  I haven't tested these anywhere else.

OH MY GOODNESS!  I wish I had learned these commands a long time ago.  As I begin to do more with long commands, particulary operations style tasks with programs like Kubernetes, I find myself more and more wanting to clear the command line. I already knew about *reverse search*, but what I didn't know was how to clear a command if I didn't find the one I wanted in reverse search.  If you don't know what revese search is, go google for it now.  `ctrl`+`R` is a wonderful command and everyone who uses a command line should know it.  As for clearning long lines, I found this great [post on StackOverflow](https://stackoverflow.com/questions/9679776/how-do-i-clear-delete-the-current-line-in-terminal).

For my own sake of easy reference later, I'm reposting the commands I've found most useful here:

`Ctrl`+`C`: Exits any current command

`Ctrl`+`U`: Clears from cursor back to the beginning of the line

`Ctrl`+`K`: Clears from cursor to the end of the line

`Ctrl`+`A`: Takes the cursor to the beginning of a line

`Ctrl`+`E`: Takes the cursor to the end of the line

`Ctrl`+`W`: Remove words, backwards from cursor location

`Ctrl`+`XX`: Toggle cursor location between beginning of line and current position
  
`Ctrl`+`Y`: Recall a deleted line

---

And finally,
`Ctrl`+`L`: Clears entire terminal window, but leaves any currently typed command in place.

If you read this far, I hope you learned something new!
