#  Damn it!

I lost my ugly rant text trying to get this thing to work... Oh well better for the world

## for those of you tuning in
I just spent 30 minutes trying to figure out why I kept getting
***fatal: <ANY URL>/info/refs not found: did you run git update-server-info on the server?***

But it seems that "I" am dumb because we are supposed to create a repo using the web page?   So much for technical advancements!


work done
     
     mkdir test
     cd test
     git init
     echo hi > test
     git add test 
     git commit -m "test" 
     git remote add origin https://github.com/classnote/test.git
     git push origin master
     
*total fail!*
     
     git remote rm  origin 
Tried SSH/HTTP git@ and classnote@ in all combinations EVERYTIME I got that error or was told "permission denied"
     
So then I manually created the repo and it worked?  

WTF? FWTF? sure I did something wrong but, it works now that I created it manually?
     
   
     

Anyway this is my prefered method 
	
	git remote add origin ssh://github.com/classnote/test.git
