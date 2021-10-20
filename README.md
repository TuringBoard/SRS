# System Requirements Specification
This repository contains the `.tex` files for the System Requirements Specifications of the Turing Board.

### Instructions
Clone this repository using the `git clone` command in your file system. 
```
$ git clone https://github.com/TuringBoard/SRS.git
```

Once the repository is cloned, `cd` into the repository's directory.
```
$ cd SRS
```

You may observe that by default you are in the `(main)` branch. You **never** want to work on this branch. Create your own branch and then switch to it using the following commands:
```
$ git branch YOUR_NAME    # to create your own branch, you can name it anything but lets keep a standard
$ git checkout YOUR_NAME  # to switch to your branch
```

This will successfully switch the working tree to your branch. Make all the edits you need to the `.tex` files in `SRS Latex/tex/`, then push the changes to your branch using the following commands:
```
# Make sure you are in the root directory of the repository first, then
$ git add . 
$ git commit -m "Centered a div"
$ git push origin YOUR_NAME
```

Once you have successfully pushed to your branch, an automatic pull request should have been created for you in https://github.com/TuringBoard/SRS/pulls. Given there are no conflicts, you should be able to `Merge pull request` which will merge the edits from your branch into `main`. 
