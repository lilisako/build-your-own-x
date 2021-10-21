# Build your own Git
This repository follows [Write yourself a Git!](https://wyag.thb.lt/#org4a4112c) by Thibault Polge. 

## Summary
- `init` : Initialize git repository. This command creates branches, objects, refs/tags, and refs/heads folders, as well as description, head, and config files. These contain all the information for git histories. 
- `cat-file`: Read the specified object's content from user input and display them. 
- `hash-object`: Read a file and computes its hash as an object. It has 4 modes, which are blob, commit, tag, and tree. 
- `log`: It shows a commits history.  Since one git commit object contains tree and parent information, it can chase back the history with commit objects.

## Gif animation
![git](https://user-images.githubusercontent.com/33516104/138294370-7eeefbd8-f32d-4bb3-a200-f3b820ce43ca.gif)
