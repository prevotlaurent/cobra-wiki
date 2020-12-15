 
 # On GitHub interface
 
 ## 1. Create your first page / description
 
 1. Got to the wiki tab of the cobra-wiki repository
 2. Make a "New page"
 3. Fill the 3 fields (Versionning is about being clear and strict about this kind of "details):
    - Title : You should use ESR_XX as prefix to navigate later more easily in the pages we will create (XX being the number of your PhD project in CoBra)
    - Content : You can copy / paste your text here but be careful that it is real simple text / markdown  (here is [cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) for markdown 
    - message : This is **important** !! (your first message can be something "Created raw Phd Description")
 
  
 # Alternate : On local computer

 ## 0. Prelim / Install

 Install git
 In the command line :
 
```
git init
git clone https://github.com/prevotlaurent/cobra-wiki.wiki.git
``` 

 ## 1. Create your first page / description

Just edit in your favorite raw text editor the description of your PhD in markdown format and give it a name prefixed by ESR_XXX (XX being the number of your PhD project in CoBra)

The following commands are made for tracking changes in our repository and then *push* your new file to GitHub

```
git add ESR_XXX_YYY.md
git commit ESR_XXX_YYY.md - m "Created raw Phd Description"
git push
``` 


