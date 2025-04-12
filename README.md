<h1>How to download content from web servers using wget in the Linux terminal.</h1>


<h2>Description</h2>
How to download content from web servers using wget in the Linux terminal.


<h2>Environments Used </h2>

- <b>Linux Ubuntu</b>

 <h2>Overview:</h2>
We are going to download a website from our browser to store it on our local computer. In this case, we will be downloading https://en.wikipedia.org/wiki/Bird.
<br />


<h2>walk-through:</h2>


<p align="center">
<br />
<br />
Once you're in the terminal, you can check which directory you're in by typing the command "pwd". To store the user files, you can do this in the /home/username directory. If you're not there already, you can navigate to it by typing the command "cd /home/username".: <br/>
 <img src="<a href="https://ibb.co/sdg2QHJJ"><img src="https://i.ibb.co/hJgyHf11/Screenshot-2025-04-05-171100.png"  height="80%" width="80%" alt="steps"/>
<br />
<br />
To list all the directories located in /home/username, you will need to type the command "ls -l". After doing this, we will see that the directory 'school' already exists, and this is the directory the customer wants us to remove.":  <br/>
<img src="<a href="https://ibb.co/xSHT8jt8"><img src="https://i.ibb.co/d0gYJ2wJ/Screenshot-2025-04-05-171127.png" height="80%" width="80%" 
<br />
<br />
To remove the old 'school' directory along with its contents, we will use the command "rm -r school". To check that the directory has been removed, we can use the "ls -l" command.: <br/>
<img src="<a href="https://ibb.co/SwSbw2fQ"><img src="https://i.ibb.co/4RkzRc1s/Screenshot-2025-04-05-171216.png" height="80%" width="80%"
<br />
<br />
To create a new directory, we will use the command "mkdir school".:  <br/>
<img src="<a href="https://ibb.co/VWdTX0F6"><img src="https://i.ibb.co/0jkrPp05/Screenshot-2025-04-05-171234.png" height="80%" width="80%" 
<br />
<br />
:  <br/>
To grant the user read, write, and execute permissions, we will use the command "chmod u=rwx school". To check the permissions, we will run the command "ls -ld school".:  <br/>
<img src="<a href="https://ibb.co/NfxkgLn"><img src="https://i.ibb.co/GG71fV3/Screenshot-2025-04-05-171255.png" height="80%" width="80%"
<br />
<br />
Now, to create a subdirectory for each of his classes, we will use the command mkdir -p school/class. We will do this for both his science and math classes.:  <br/>
<img src="<a href="https://ibb.co/1GkwC4zD"><img src="https://i.ibb.co/B29ShYnX/Screenshot-2025-04-05-171308.png" height="80%" width="80%" 
<br />
<br />
To create a symbolic link, we will use the command "ln -s school 123".:  <br/>
<img src="<a href="https://ibb.co/k2zs0W9k"><img src="https://i.ibb.co/PGJv4f93/Screenshot-2025-04-05-171344.png" height="80%" width="80%"    
<br />
<br />
Once you're in the terminal, you can check which directory you're in by typing the command "pwd". To store the user files, you can do this in the /home/username directory. If you're not there already, you can navigate to it by typing the command "cd /home/username".: <br/>
 <img src="<a href="https://ibb.co/PvntHfDM"><img src="https://i.ibb.co/C3ZWGTP6/Screenshot-2025-04-05-171700.png"  height="80%" width="80%" alt="steps"/>
<br />
<br />
To list all the directories located in /home/username, you will need to type the command "ls -l". After doing this, we will see that the directory 'school' already exists, and this is the directory the customer wants us to remove.":  <br/>
<img src="<a href="https://ibb.co/fGFyc9Gk"><img src="https://i.ibb.co/YTQ1rXTc/Screenshot-2025-04-05-171752.png" height="80%" width="80%" 
<br />
<br />
To remove the old 'school' directory along with its contents, we will use the command "rm -r school". To check that the directory has been removed, we can use the "ls -l" command.: <br/>
<img src="<a href="https://ibb.co/RGn2CZ5K"><img src="https://i.ibb.co/1YVZ9hSN/Screenshot-2025-04-05-171912.png" height="80%" width="80%"
<br />
<br />
To create a new directory, we will use the command "mkdir school".:  <br/>
<img src="<a href="https://ibb.co/Y4HJz46s"><img src="https://i.ibb.co/gbkQ5bGK/Screenshot-2025-04-05-171938.png" height="80%" width="80%" 
<br />
<br />
:  <br/>
To grant the user read, write, and execute permissions, we will use the command "chmod u=rwx school". To check the permissions, we will run the command "ls -ld school".:  <br/>
<img src="<a href="https://ibb.co/whNQtgNn"><img src="https://i.ibb.co/4RZSktZb/Screenshot-2025-04-05-171954.png" height="80%" width="80%"
<br />
<br />
Now, to create a subdirectory for each of his classes, we will use the command mkdir -p school/class. We will do this for both his science and math classes.:  <br/>
<img src="<a href="https://ibb.co/LzhJgy3g"><img src="https://i.ibb.co/jvZWwYSw/Screenshot-2025-04-05-172003.png" height="80%" width="80%" 
<br />
<br />
To create a symbolic link, we will use the command "ln -s school 123".:  <br/>
<img src="<a href="https://ibb.co/N6L7JJRN"><img src="https://i.ibb.co/Z6hNFF9g/Screenshot-2025-04-05-172029.png" height="80%" width="80%" 
<br />
<br />                                              
Now, to create a subdirectory for each of his classes, we will use the command mkdir -p school/class. We will do this for both his science and math classes.:  <br/>
<img src="<a href="https://ibb.co/LzmVjhqK"><img src="https://i.ibb.co/5WmbpxzZ/Screenshot-2025-04-05-172058.png" height="80%" width="80%" 
<br />
<br />
