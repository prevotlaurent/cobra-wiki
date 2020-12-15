 
 # On GitHub interface
 
 ## 1. Create your first page / description
 
 1. Got to the wiki tab of the cobra-wiki repository
 2. Make a "New page"
 3. Fill the 3 fields (Versionning is about being clear and strict about this kind of "details):
    - Title : You should use ESR_XX as prefix to navigate later more easily in the pages we will create (XX being the number of your PhD project in CoBra)
    - Content : You can copy / paste your text here but be careful that it is real simple text / markdown  (here is [cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) for markdown 
    - message : This is **important** !! (your first message can be something like "Create raw Phd Description")
    
## 2. Indentify shared concepts / methods / references
 1. Read all other descriptions 
 2. Distribute to each other a file for editing / reviewing 
 3. *Edit* the file assigned, do not forget to inform the message box everytime you modified a page:
       - by suggesting hyper-links \[\[like that\]\] on concept / methods that are crucial and require some more explanation
       - by suggesting added references again by adding links with authors names
 4. You can see the history of the modifications by clicking on the "n revisions" text in the upper part of the page.
 5. Repeat the process until all PhD topics have been modified / reviewed by at least 2 other members.

## 3. Create shared concepts / methods pages
  1. Assign each other at least one these concepts / methods page
  2. Just click on one of the new links (in read) to open a page for editing the relevant page
  3. Edit as you wish (markdown format)
  4. Repeat the process until all concepts / methods are covered
  
## 4. Review shared concepts / methods
  1. Read those concept / methods page
  2. Add missing links to PhDs / other concepts, references 
  3. If needed for your PhD, propose alternative definition in the same page
 
 
 # Alternate : On local computer

 ## 0. Prelim / Install

 Install git
 In the command line :
 
```
git init
git config user.name "your github name"
git config user.email "email used for github"
git clone https://github.com/prevotlaurent/cobra-wiki.wiki.git
``` 

 ## 1. Create your first page / description

Just edit in your favorite raw text editor the description of your PhD in markdown format and give it a name prefixed by ESR_XXX (XX being the number of your PhD project in CoBra)

The following commands are made for tracking changes in our repository and then *push* your new file to GitHub

```
git add ESR_XXX_YYY.md
git commit ESR_XXX_YYY.md - m "Create raw Phd Description"
git push
``` 

## 2. Indentify shared concepts / methods / references
 1. Read all other descriptions 
 2. Distribute to each other a file for editing / reviewing 

```
git pull
git add "the-file-you-will-be-editing.md"
``` 

 3. *Edit* the file assigned with your favorite editor, do not forget to inform the message box everytime you modified a page:
       - by suggesting hyper-links \[\[like that\]\] on concept / methods that are crucial and require some more explanation
       - by suggesting added references again by adding links with authors names
       
```
git commit the-file-you-will-be-editing.md - m "Added wiki links"
git status
git push
```
 4. You can see the history of the modifications by clicking on the "n revisions" text in the upper part of the page.
 5. Repeat the process until all PhD topics have been modified / reviewed by at least 2 other members.

## 3. Create shared concepts / methods pages
  1. Assign each other at least one these concepts / methods page
  2. Create a file matching the name "your-new-file.md" of the missing link and edit it with your text editor

```
git add your_new_file.md
git commit your-new-file.md - m "Create new concept / method / reference page"
git push
``` 

  4. Repeat the process until all concepts / methods are covered
  
## 4. Review shared concepts / methods
  1. Read those concept / methods page
  2. Add missing links to PhDs / other concepts, references  (this could be done locally as well but I suggest to do it online)
  3. If needed for your PhD, propose alternative definition in the same page : 
  
```
git pull
```
     - Edit your file

```
git commit modified_file.md - m "Updated Concept / method definition"
git push
``` 


