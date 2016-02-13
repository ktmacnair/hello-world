# hello-world
This is my test repo created while following along with the tutorial on github.com. 

We're going to be editing help.xml files directly in GitHub! 

## Fun with merge conflicts
I accidentally created a merge conflict already, because I made one change to this file in the master brand and another change to the same file in my "readme-edits" branch. Now I am going to add another change to see whether I can make the file conflict worse. Or maybe fix it. 


## Now we're cooking! 

I fixed the problems. How? Well I am not totally sure, to be honest. But somehow I managed to get all my changes made, new headings, new text. And merged a final pull request, and then got the awesome message that said it was safe to delete the (offensive) branch. Which I promptly did.
Then I had to figure out how to delete the darn branch on my local copy -- not at all intuitive. You click the gear icon in the top-right corner, and there's an option to delete the branch. Because I had already deleted the remote one, clicking "delete both" confused it. So then I told it to delete the local copy only. 
Now I am working in a brand-new branch so I can try this again. In a fit of originality, I named the branch "working." :-) 


Note to self re markdown files in Visual Studio: lines that have new but unsaved changes have yellow bar on the side of the screen. After I've saved the file, those changed lines now have a green bar on the side. 

## Committed to pull requests

So this is going to be the second set of changes I am making to this file right now. Add a heading, a sentence. Nothing big. Save, close, commit. 

### What happens now? 

Looks like that's gonna work just fine. But now my question is, what if I make changes to the file, save it, close it ... open it back up, make changes, save again ... will Git see that as two sets of changes or just one? 

(This is my second edit before making another commit. We'll see in just a second what happens.)

Beautiful. Git looks at it as just one set of changes, which is both good and expected behavior. Going to commit these changes now. 