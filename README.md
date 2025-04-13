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
First, open your web browser and search for the website you want to download. Once you've found it, copy the URL from the address bar.: <br/>
<img src="<a href="https://ibb.co/sdg2QHJJ"><img src="https://i.ibb.co/hJgyHf11/Screenshot-2025-04-05-171100.png"  height="80%" width="80%" alt="steps"/>
<br />
<br />
Using the `wget` command followed by the URL, you can download the website you want. However, this basic command won’t preserve the website’s structure or download any linked pages recursively.:  <br/>
<img src="<a href="https://ibb.co/xSHT8jt8"><img src="https://i.ibb.co/d0gYJ2wJ/Screenshot-2025-04-05-171127.png" height="80%" width="80%" 
<br />
<br />
To our wget 'URL' command, we will add the --page-requisites option to download all the files needed for the proper display of the website.: <br/>
<img src="<a href="https://ibb.co/SwSbw2fQ"><img src="https://i.ibb.co/4RkzRc1s/Screenshot-2025-04-05-171216.png" height="80%" width="80%"
<br />
<br />
We'll also use the --convert-links option, which changes all the links so they work properly for local viewing.:  <br/>
<img src="<a href="https://ibb.co/VWdTX0F6"><img src="https://i.ibb.co/0jkrPp05/Screenshot-2025-04-05-171234.png" height="80%" width="80%" 
<br />
<br />
:  <br/>
Next, by using the --recursive option, we instruct wget to download all the files within the website, including links found on the site.:  <br/>
<img src="<a href="https://ibb.co/NfxkgLn"><img src="https://i.ibb.co/GG71fV3/Screenshot-2025-04-05-171255.png" height="80%" width="80%"
<br />
<br />
By using --level=inf, we tell wget to follow all the links, no matter how deep they go, and download the corresponding files.:  <br/>
<img src="<a href="https://ibb.co/1GkwC4zD"><img src="https://i.ibb.co/B29ShYnX/Screenshot-2025-04-05-171308.png" height="80%" width="80%" 
<br />
<br />
With the --no-parent option, we tell wget not to download parent folders and to only follow links to subdirectories.:  <br/>
<img src="<a href="https://ibb.co/k2zs0W9k"><img src="https://i.ibb.co/PGJv4f93/Screenshot-2025-04-05-171344.png" height="80%" width="80%"    
<br />
<br />
We can also shorten this by typing wget "the_wanted_url" -p -k -r -l=inf -np.: <br/>
<img src="<a href="https://ibb.co/PvntHfDM"><img src="https://i.ibb.co/C3ZWGTP6/Screenshot-2025-04-05-171700.png"  height="80%" width="80%" alt="steps"/>
<br />
<br />
We can make it even shorter using wget "the_wanted_url" -pkrlinf -np.:  <br/>
<img src="<a href="https://ibb.co/fGFyc9Gk"><img src="https://i.ibb.co/YTQ1rXTc/Screenshot-2025-04-05-171752.png" height="80%" width="80%" 
<br />
<br />
After downloading the website, we can open it locally from our folder by opening our web browser, clicking 'File,' and then selecting 'Open File'.: <br/>
<img src="<a href="https://ibb.co/RGn2CZ5K"><img src="https://i.ibb.co/1YVZ9hSN/Screenshot-2025-04-05-171912.png" height="80%" width="80%"
<br />
<br />
Go to the desired file.:  <br/>
<img src="<a href="https://ibb.co/XxpPqk6g"><img src="https://i.ibb.co/DfkFZgmy/Screenshot-2025-04-12-192402.png"  height="80%" width="80%" 
<br />
<br />
Continue.:  <br/>
<img src="<a href="https://ibb.co/whNQtgNn"><img src="https://i.ibb.co/4RZSktZb/Screenshot-2025-04-05-171954.png" height="80%" width="80%"
<br />
<br />
Open the file.:  <br/>
<img src="<a href="https://ibb.co/BKSZbmB2"><img src="https://i.ibb.co/0VdMTkry/Screenshot-2025-04-12-192324.png" height="80%" width="80%" 
<br />
<br />
And you are done.:  <br/>
<img src="<a href="https://ibb.co/N6L7JJRN"><img src="https://i.ibb.co/Z6hNFF9g/Screenshot-2025-04-05-172029.png" height="80%" width="80%" 
<br />
<br />                                              
You can even open the links located on the website.:  <br/>
<img src="<a href="https://ibb.co/LzmVjhqK"><img src="https://i.ibb.co/5WmbpxzZ/Screenshot-2025-04-05-172058.png" height="80%" width="80%" 
<br />
<br />
