# COMPSCI 235 Lab Report 2
### Stanley Wu
## Notes

1. Git can track and record the changes you or a team makes to any code so that you can have multiple verses.
2. The commands to configure Git is ```git config --global user.name <name>``` and ```git config --global user.email <email>```
3. SSH keys are necessary to link your pc to your Github account.
4. The basic Git commands are: ```git status```, ```git pull```, ```git add -A```, ```git commit -m <message>```, ```git push```
5. Git best practices include:
- Testing before committing
- Commit finished work
- Write short meaningful comments
- Incremental approach
- Set standards
- Be polite in PR comments

## Reflection

I have learnt basic git commands to push and commit code to Github and the importance of cooperation.
In this lab I also learnt some git best practices as we practiced branching, forking, merging and pull requests.

## Solutions

Question 1.
What's the best way to commit your unfinished code
to GitHub without interrupt others? What commands do you need to achieve that?
- By creating branches to store the unfinished code and then committing to main after finishing.
- ```git branch <branch_name>``` and ```git checkout <branch_name>```

Question 2.
Explain the difference between merge and fork. Give an example for each use 
case.
- Merging combines two or more different branches and then is tested before combining with the main branch.
- For example if there are errors with merging we must solve them and then use git commands to send the changes.
- Forking however allows anyone to access the code and submit a push request.
- For example someone can clone the repository to their pc and make changes, but it will not affect the main repo untill the request is accepted by the owner.
- So the difference is that Merging is private as it only allows certain people to access but forking is public and allows everyone.





### Github Account

[Link](https://github.com/sharukyen) to my GitHub account.