# Statistical Physics Interactive Examples in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hoogenboom-lab/teaching/master)

###### Lead 
Professor Bart. W. Hoogenboom

###### Authors
- Luke K. Davis (@patherlkd)
- Lorenzo Braccini
- Livia Maskos
- Adrien Claret-Tournier

## How to use this repository

### Running the examples

1. Click on the Launch Binder button at the top of this README.

2. Wait for the remote server to build the repo *(can take a few moments)*, which will start a new window with the remote jupyter notebook directory.

3. Click on a jupyter notebook of your choice.

4. Click `Cell` and then `Run All` (Unless other running instructions specified).

Notes: Different cells take time to run, if on the left side of the notebook you see ``In[]`` (empty) it has not run yet. If you see ``In[*]`` it is currently running. If you see ``In[<number>]`` it has been executed (number relates to the order of its execution e.g. <number> = 1st to tun).

### Using the code

- Either clone/fork this repository.

- Download individual coding files.

### Issues and course content

Please contact the lead/ raise an issue on the repository.

## For the implementers (that have been granted push access):

### Github commands (assmuing UNIX (linux/Mac OS) terminal):

- To clone current version onto you local machine:
```
<terminal>$ git clone https://github.com/hoogenboom-lab/teaching.git
```
- To update your local copy with update remote changes:
```
<terminal>$ git pull origin master
```
- To remove a file (please take care when doing this):
```
<terminal>$ rm <file>
<terminal>$ git add .
<terminal>$ git commit -m "Removed <file>"
<terminal>$ git push origin master
```
- To add or change a file:
```
<terminal>$ jupyter notebook
```
Then add or change your code to the notebook and save to a sensible filename = <file>. If you are updating an existing notebook, save it to the **same filename**.

```
<terminal>$ git add <file>
<terminal>$ git commit -m "Added <file>.
<terminal>$ git push origin master
```
- If you encounter merge issues, please contact Luke Davis (via Slack/email/github).
