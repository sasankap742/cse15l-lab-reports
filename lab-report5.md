
The less command by default is used to view the content of a file without having to print it all to the terminal. Once you’re done viewing the file content, you can exit simply by pressing ‘q’ on keyboard. 

3 Alternate features of the less command

less <filename> command with the option -X  
Shows the file content as normal with the exception of leaving the content on the terminal when you exit by pressing ‘q’
Example 1:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503769-38eb386b-f6ee-401a-ae38-fed25c9a91b9.png)
  
Example 2:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503796-acb1aa1b-95be-4982-9657-c7c762563e37.png)
  
Example 3:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503808-0f8d08c6-e9e3-4284-815d-e891e99ec0c4.png)
  
less <filename> command with the option -N 
Shows the file content with the line numbers displayed.
Useful when looking at code, where you can use line numbers to navigate.

Example 1:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503881-d7d1dc45-82c6-4da3-a8e5-da64eeeb2504.png)
  
Example 2:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503889-2416d2f4-bcfd-47ef-a307-13e21dca5236.png)
  
Example 3:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503904-f84558cf-77a5-4835-8fec-3b90956c16e8.png)

less <filename> command with the option - +/pattern 
Shows the file content, searches forward and highlights where the pattern matches.Only Shows content of the file upto that last occurance of pattern.

Example 1:
  
  ![image](https://user-images.githubusercontent.com/78668680/201503917-64c51afa-8e4e-40f7-8af8-d8d92a72cd1c.png)
  
Example 2:
  Shows the content of the file up until the last occurrence of the pattern. 
  But because this file doesn’t contain the pattern, it shows blank
  
  ![image](https://user-images.githubusercontent.com/78668680/201503939-f122c739-3496-40b4-a61c-ebc9d8573d8b.png)
  
Example 3:
  Here, searching and highlighting the word "protein" that is actually in the file.

  ![image](https://user-images.githubusercontent.com/78668680/201503958-be06a694-21f9-43ff-8864-1f36607edb18.png)
  

