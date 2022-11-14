Part1
*In DocSearchServer.java, add a new line right before File[] paths = f.listFiles(); that prints out the toString of f and a message saying it’s a directory.
/File[] paths, <Enter> ,h, i,newline<Enter>,arrow up, System.out.println(f.toString() + “is a directory”), <esc>, :wq<Enter>
  
![image](https://user-images.githubusercontent.com/78668680/201557959-37bca355-ca4c-4ba3-a1f6-5637d3ea2282.png)
![image](https://user-images.githubusercontent.com/78668680/201557990-74d6aed2-177b-4f05-8a45-4e3a7dc096cf.png)

Part 2:
Consider performing the edit task you chose and re-running the program when you have to run it remotely. Time yourself twice:
1) Once, start in Visual Studio Code and make the edit there, then scp the file to the remote server and run it there to confirm it works 
(you can just run bash test.sh on the remote to test it out). Consider having the appropriate scp command in your command history or easily copy-pasteable!
--Took me around 1 minute 20 seconds. Most of it was because of having to edit the file then save before sending it to the remote server.  
  
2) Second, start already logged into a ssh session. Then, make the edit for the task you chose in Vim, then exit Vim and run bash test.sh.
--This took me like 60 seconds or less. Because It was much faster to edit and save in vim. Although, I still find moving around in vim difficult.
3) Which of these two styles would you prefer using if you had to work on a program that you were running remotely, and why?
--I would prefer to use vim if it’s a program running remotely because with more practice vim is definitely much faster to make edits to code and simply save. 
  Plus, I would not have to move files between local and remote, if I use vim.
4) What about the project or task might factor into your decision one way or another? (If nothing would affect your decision, say so and why!)
--If the task requires me to make significant changes to a file, then I might as well work on it in my local pc using the software that I am most comfortable with instead of on vim. 
  Perhaps this would also not affect me once I become really comfortable navigating in Vim without the mouse. But for now, I feel like I would only use vim for small tasks.

