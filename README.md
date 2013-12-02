Adds some reminders about the git status of current working directory, to the bash prompt.
Mimics the github display of ahead/behind.


Two commits behind, seven commits ahead:

2 behind <--|-------> 7 ahead
master imac:bash-prompt-git-status jseb$ 


Six commits ahead:

|------> 6 ahead
master imac:bash-prompt-git-status jseb$ 


Eight commits behind:

8 behind <--------|
master imac:bash-prompt-git-status jseb$ 


Stash(es):

master [**] imag:bash-prompt-git-status jseb$


In sync with remote:

master imac:bash-prompt-git-status jseb$

Colour of branch name:
  green: working directory clean
  yellow: local changes
  red: untracked files
