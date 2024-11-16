# Documentation

## Commands I used

git checkout -b about

// After making changes to index.html
git add index.html
git commit -m "Contact information"
git push origin about

The sequence of commands for merging the branch about:
git checkout main
git branch (for check)
git merge about

For merging home:  
git checkout -b home

After making changes and getting conflicts
git checkout main
git merge home
 Resolve conflicts in vscode interface
 git commit and push

Tagging:
git tag -a v1.0 -m "tagging first commit" fa76b0b  
git tag -a v1.1 -m "tagging style commit" 1c9849c  
To create the taggs 
git push origin --tags to push them.


To configure Git, I had to type the following:
git config user.name "apdl8-UA"  
git config user.email "apdl8@alu.ua.es"  

I did the rest of actions using VSCode interface