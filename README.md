Step 1:
Create a Personal access token on github from settings to developer settings.

Step 2:

 Put that token on Jenkins. On Jenkins -> go to manage Jenkins -> system -> github -> put the access token as a plain text.

Step 3:

make a freestyle project on Jenkins and put mark sorce code manager as git. After that on build step -> select execute shell(as we are going to execute the command on sheel) -> put the command to run on shell. 

**Note: I give Jenkins user to use docker without sudo.**

Build Output:  
![image](https://github.com/MdRasel0/assignment-2-python/assets/52493009/8765db7f-1aa3-46ce-b6f1-da5bd3531a89)
![image](https://github.com/MdRasel0/assignment-2-python/assets/52493009/9dd17a64-b3c8-4401-b163-c1757db2115e)
 
Docker hub output:
![image](https://github.com/MdRasel0/assignment-2-python/assets/52493009/f3cebca9-d727-4069-b360-2a0e400272e6)

Application output:
![image](https://github.com/MdRasel0/assignment-2-python/assets/52493009/69101492-6fbe-47bd-bd91-cfbaafc21856)


 


