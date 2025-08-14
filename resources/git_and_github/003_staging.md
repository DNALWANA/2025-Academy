# Staging
Okay now that you have cloned an empty repository, you can then put something inside of it, for example: you can put whatever meme (in text mode) in meme.txt file.

So what is staging ? Staging is basically a state in which your changes are being **hold** before you commit it.

Basically git have this flow of state:

```
 clone a repository (if you dont currently have the repository in your local pc)               
 |                                                                                             
 +-> make changes (add something, delete something, edit something, whatever)                  
     |                                                                                         
     +-> stage the changes ("hold" the changes to later be commited)                           
         |                                                                                     
         +-> commit the changes ("save" your changes inside the git system)                    
             |                                                                                 
             +-> push the changes (upload your current git repository state to the git server) 
```

So after you make the changes, you can run either one of these commands:

- `git add {filename that you want to stage}`
- `git add {directory that you want to stage}`

Btw, you can also use asterisk "*" to stage multiple files, for example:
`git add meme*.txt`, this will stage meme1.txt, meme2.txt, meme3.txt all at once without having to run almost the same command repeatedly.

To see if your changes have been staged or not, you can run `git status` and you will see it in green color (if it have been staged), or red color (if it have not been staged yet).
