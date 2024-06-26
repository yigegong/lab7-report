# lab7-report
## Step 4
![image](4.jpeg)
## Step 4 Keys pressed:
```
ssh <space> y8gong@ieng6.ucsd.edu <enter>
```
By entering `ssh y8gong@ieng6.ucsd.edu`, I logged into the ieng6 terminal.

## Step 5
![image](5.jpeg)
## Step 5 Keys pressed:
```
git <space> clone <space> <ctrl C> <ctrl V> <enter>
```

By entering `git clone ` and copying the ssh URL `git@github.com:yigegong/lab7.git`, I cloned the forked lab7 directory into my terminal.

## Step 6
![image](6.jpeg)
## Step 6 Keys pressed:
```
cd <space> lab7 <enter>
bash <space> test.sh <enter>
```

`cd lab7` directs into the lab7 directory where the test.sh file locates, and `bash test.sh` runs the test.sh file that contains the commands to run the test.

## Step 7
![image](7.jpeg)
## Step 7 Keys pressed:

```
vim <space> ListExample.java <enter>
<down><down><down><down><down><down><down><down> <left><left> `x` `i` `2` <esc> `:wq` <enter>
```

By pressing the <down> arrow key 8 times and <left> arrow key 2 times, I moved the cursor on the `1` in `index1`. `x` deletes the `1`, `i` enters the insert mode so I can type `2` to replace the deleted `1`. By changing the `index1` to `index2`, the bug is fixed. `<esc>` exits the insert mode, `:wq` and pressing the `<enter>` key saves the change just made and exit the vim editor.

## Step 8
![image](8.jpeg)
## Step 8 Keys pressed:
```
bash <space> test.sh <enter>
```

`bash test.sh` runs the test.sh file that contains the commands to run the test.

## Step 9
![image](9.jpeg)
## Step 9 Keys pressed:
```
git <space> add <space> -A <enter>
git <space> commit <space> -m <space> "bug fixed" <enter>
git <space> push <enter>
```
`git add -A` stages all the changes made within the lab7 directory locally, `git commit  -m "bug fixed"` saves the staged changes locally with the message "bug fixed", and `git push` saves the commited changes to the remote repository, which is my github account.

