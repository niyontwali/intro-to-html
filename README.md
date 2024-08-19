# Introduction to HMTL
## Commands
- cd: changing directory
- ls: listing content
- ls -la: listing all content, even the hidden files
- mkdir: creating a directory/folder
- rm: for removing a directory and a file
**NOTE**: You will always add a flag of `-r`(recursive) to remove folder
- git init: initialize a git repository
- git add .: adds all content in the current directory to the stage area
- git commit -m "description": commit (save) the version of our changes
- git remote add origin url : links a remote repo to our local repo
- git push: pushes our codes to the remote repo

## Workflow of git
1. stage the changes (`git add .`)
2. commit the changes (`git commit -m "the description of your commit"`)
3. push the changes (`git push`)

## Branching and Merging
1. `git branch`: lists all branches on your repo
2. `git branch name_of_branch`: create a branch called `name_of_branch`
3. `git checkout name_of_branch`: Will switch to that branch with name (name_of_branch)
4. `git merge name_of_the_other_branch`: Will pull changes in the other branch and bring them to your current branch


## HMTL Elements (Tags)
### Types of Tags
- opening tag e.g <head>
- closing tag e.g </head>

**NOTE**: Self closing tags: These ones don't have opening and closing tag but just written like this: `<tag />

### HTML Headings
We have from 

### Attributes
1. src : source, which specifies the path of image
2. alt: alternative text to the image
3. id: identity of an element and can be used for css or referencing
4. styles: used for internal inline styling
5. target: used to provide behavior to your hyperlink opening
6. href: for reference
7. width and height: for sizes