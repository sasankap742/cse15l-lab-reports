Lab 1 tutorial

Installing VScode
![unnamed](https://user-images.githubusercontent.com/78668680/195763026-e29c9fe3-a434-4cba-a729-16e3ed2125bc.png)

Remotely Connecting
First, I used the command ssh and typed ssh taaccount@ieng6.ucsd.edu in the terminal
Afterwards, it asked me for the password. Because I was using a TA's acccount, I had the password copied. But each time I pasted it and pressed enter to submit the password, it failed. My mistake was assuming that the paste command would automatically work correctly inside the visual studio terminal. Copy Paste functiosn didn't work and I found out that there are setting to adjust the shortcuts. 
Trying Some Commands
![image](https://user-images.githubusercontent.com/78668680/195764883-f50a890c-5d41-430a-88e1-9dbddb51d0c3.png)
After connecting, I first tried to check what files were in the home directory. To list the files, I used the command ls. At first I didn't see the hello.txt file and thought there was only one file named perl5 but it turned out the blue colored names indicated folders. Then, I used the cat command to read the contents of the hello.txt file.
Moving Files with scp
![image](https://user-images.githubusercontent.com/78668680/195765401-d24bbd32-c423-4358-bcec-33d77d82b0f9.png)
The first mistake I made here was not being in the correct directory of the file that I wanted to move. Using the -cd command I navigated there. 
Then I was able to sucessfully use the scp command to copy the file over to the remote server.
Setting an SSH Key

Optimizing Remote Running
