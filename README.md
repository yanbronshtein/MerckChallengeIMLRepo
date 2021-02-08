# Merck Challenge IML

## Setting up git environment
**Run the following in terminal on mac, windows powershell, or cmd**
```console
git clone https://github.com/yanbronshtein/MerckChallengeIMLRepo.git
```

## Working on code
**Before working on any code, type:**
**This allows you to pull all changes by other contributors**
```console
git pull
```



**Make changes to the code and commit frequently**
```console
git add . #Adds all modified files
```
**You can also add specific files**
```console
git add my_file.ipynb #Or any other extension
```

**Commit your messages with a meaningful commit message**
```console
git commit -m "Practicing coding chops with github"
```
**Push changes to github**
```console
git push
```

**You may be prompted to enter your username and password**
## Comparing code differences
**Install ```nbdime``` using the following command:**
```console
pip install nbdime
```


**Use the following command to make nbdime default for ipynb**
```console
nbdiff-web [<commit> [<commit>]] [<path>]
```
**Compare using rich web interface**
```console
nbdiff-web notebook_1.ipynb notebook_2.ipynb
```


**For more info, go to the following link**
[link]
(https://nbdime.readthedocs.io/en/latest/)



