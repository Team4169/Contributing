# Contributing
Guidelines for contributing to Team 4169 repositories  

When contributing to Team 4169 repositories please try and follow these guidelines. 

#Code
Please try and write neat code. What does this mean?
##Naming
When naming variables and functions please try and name them based on what they do.  
**Good**: `xAxisSensitivity`, `turnOnRadio()`  
**Bad**: `baconIsTheBest`, `klsdjfsdklfdsjsdklf()`

##Spacing
Add blank lines in your code when it makes sense. A good rule of thumb for adding line breaks is to add a blank line when you start doing a new thing. For example you could be defining variables and then you start calling functions, add an empty line.

##Comments
Try and keep your comments short, and informative. No one wants to read a novel.

#Git
Use the Github Glow([5 minute guide](https://guides.github.com/introduction/flow/)) model. 

##Github Flow TLDR
The master branch of a repository **always** has stable code. This means that at any given time we could clone down the master branch and run it on the robot. 

If you want to make a change to the code create a new branch from master. Then make you changes and submit a pull request. The other team members will review you code and eventually your code will be merged into the master branch.

##Commits
Please write clear and short commit messages. These messages should describe very quickly what you have changed in a commit.  

If you are adding just one thing is a commit use a short sentence
```
Added XBox controller Y button support
```
However if you are adding more than one feature please use shorter messages
```
+XBoxController Y button, +Mecanum Wheels, -Omni Wheels
```

##Naming Branches
Always name your branch names based on what they are doing.

 For example if you are addressing an issue name it `issue-#` or `heartbleed-bug`.

If you are adding a new feature name the branch based on the feature. So if you are adding PS3 Controller support name it `PS3-controller`
