
# Create a symlink

Open terminal to the location you wish to save your .bash_profile

Using the following command in terminal
```
  ln -s path/to/the/git/repo/.bash_profile .bash_profile
```

On my machine it is (relatively) located at Projects/personal/bashfile. So...

```
  ln -s Projects/personal/bashfile/.bash_profile .bash_profile
```  
You will now have a symlink to the version controlled .bash_profile

---

I have also included an example gitconfig and .git-completion.bash for your convenience.

If you want to install all of the configurations I have in this project,
run the following.
```
  ln -s Projects/personal/bashfile/.bash_profile .bash_profile
  ln -s Projects/personal/bashfile/.gitconfig .gitconfig
  ln -s Projects/personal/bashfile/.git-completion.bash .git-completion.bash
```

---

Lots of credit to natelandau

http://natelandau.com/my-mac-osx-bash_profile/

https://gist.github.com/natelandau/10654137

---
