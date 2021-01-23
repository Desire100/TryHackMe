## Linux Fundemental Part Two
[Link of this room](https://tryhackme.com/room/linux2).
#### Understanding Operators in Linux and Advanced File Operations.

### Tasks:
1. Connect into the machine using shiba2 as the username and pingutfw as the password  
   → <code>no answer needed</code>
2. Introduction to SSH  
    → <code>no answer needed </code>
3. Putty SSH  
   → <code>no answer needed </code>
4. Linux Operators “&&”  
      1- Meaning && allows you to execute a second command after the first one has executed successfully
5. Linux Operators “&”  
      1- & is a background operator, meaning say you run a command that takes 10 seconds to run, normally you wouldn't be able to run commands during that period.
6. Linux Operators “$”  
      1- The $ is an unusually special operator, as it is used to denote environment variables.  
      2- would you set nootnoot equal to 1111?    
         → <code>export nootnoot=1111 </code>  
      3-  What is the value of the home environment variable  
         → <code>/home/shiba2</code>
7. Linux Operators “ | ”  
      1- The | operator allows you to the take the output of a command and use it as input for a second.
8. Linux Operators “;”  
      1- The ; operators works like &&, however it does not require the first command to excute successfully.
9. Linux Operators “>”  
      1- “>” is the operator for output redirection. Meaning you can redirect the output of a command to a file.  
      2- How would you output twenty to a file called test?    
        → <code>echo twenty > test</code>
10. Linux Operators “>>”  
      1- >> does mainly the same thing as >, with one key difference. >> appends the output of a command to a file, instead of erasing it.
11. Binary -Shiba2  
      1- What is shiba3's password?    
         → <code>happynootnoises</code>  
12. Advanced File Operations   
      1- No answer needed
13. A bit of background  
      1- No answer needed
14. Chown Command  
      1- Allows you to change the user and group for any file.   
      2- How would you change the owner of file to paradox    
         → <code>chown paradox file </code>   
      3- What flag allows you to operate on every file in the directory at once?    
         → <code>-R</code>
15. chmod Command  
      1- Allows you to set the differenct permissions for a file.  
      2- What permissions mean the user can read the file, the group can read and write the file, and no one else can read, write or excute the file?    
        → <code>460</code>  
      3- What permissions mean the user can read, write, and execute the file, the group can read, write, and execute the file, 
      and everyone else can read, write, and execute the file?  
             → <code>777</code>
16. File Operation: rm (remove) command    
      1- What flag deletes every file in a directory?  
         → <code>-r </code>   
      2- How do you suppress all warning prompts?    
          → <code>-f</code>
17. File Operation: mv (move) command    
      1-How would you move file to /tmp?    
        → <code>mv file /tmp</code>
        
#### 18. Linux Fundemental 3
                                                                                                       

                                                    
