# Rename folder/file from uppercase to lowercase 

- This practice is for making uppercase folder to lowercase by using git.

### How?

Step 1: create a new branch and do following command

* For Folder:

```shell
git mv CaseFolder tempFolder
git mv tempFolder caseFolder
```

* For File:

```shell
git mv CaseFile.xxx tempFile.xxx
git mv tempFile.xxx caseFile.xxx
```


Step 2: check all the folder and files are changed as <strong>`Renamed`</strong> status in git.


Step 3: Create the new PR and merge to the detination branch, like master


Step 4: Thanks & <a href="https://stackoverflow.com/questions/13201906/issue-with-renaming-a-directory-in-git-to-lowercase-while-ignorelowercase-true" target="_blank">Reference</a> ~~
