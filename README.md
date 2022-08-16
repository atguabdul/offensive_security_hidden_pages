# offensive_security_hidden_pages
hidden pages on  website using GoBuster


1st — Open a terminal



2nd — Find website pages that have been hidden

The reason for this is that many businesses will have their own admin portal, which will give their employees access to basic admin controls for day-to-day activities.

Command: gobuster -u <target> -w wordlist.txt dir
-u = to state the website we're scanning
-w = a list of words to iterate through to find hidden pages
  
  ![image](https://user-images.githubusercontent.com/102252719/184928941-66d7db4b-1dd1-492b-9988-0c93067cd673.png)

  You’ll notice that GoBuster examines the website for each term in the list, locating existing pages.

In the list of page/directory names, GoBuster will have told you the pages it found (indicated by Status: 200).
  
  
  
  
  


