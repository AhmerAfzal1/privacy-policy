# Use of Git

## Write simple commit
```sh
git status
git add .
git commit -am "Title here"
```

## Write commit title with its description

```sh
git status
git add .
git commit
```
To start typing press the <kbd>INSERT</kbd> key on your keyboard

    Commit title message
    
    Than write commit description detail message 

Press <kbd>ESC</kbd> after writing commit message now close the Vim editor with save changes by typing on the keyboard `:wq (w - write, q - quit):`
```sh
git push origin master
```

## Fetch from git repository
From github

## How do I force “git pull” to overwrite local files?
```sh
git fetch --all
```

Then
```sh
git reset --hard origin/master
```
