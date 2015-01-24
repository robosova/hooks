#Hooks
Git hooks. Actually, right now it's the only pre-push hook. :) 

##How to use
Just clone it and copy to /you/git/repo/.git/hooks and do chmod +x.

or

You can set hook for every project. Here's a usefull link: http://stackoverflow.com/questions/2293498/git-commit-hooks-global-settings

###pre-push hook
Hook for protect master branch from some debug code. You free to add to file stop_words whatever you don't want to see in you master branch. Change protected branch ("develop" by default).
