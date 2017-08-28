
This test repository is created for the members to test and learn to upload files to the github repository.

Fork the repository
====================

Navigate to the repository [page](https://github.com/osdevnet/test_assignment)

Press the "Fork" button in the upper right corner.

Now the copy of the repository will appear in your personal repository list.

More at https://help.github.com/articles/fork-a-repo/

Download the repository
=======================

Type

```git clone https://github.com/<yourusername>/test_assignment```

Create own directory, add files
===============================

```
# enter the newly downloaded directory
cd test_assignment
# create a directory with your username
mkdir yourusername
cd yourusername
# now you can create a file there
echo "test" > test.txt
# add it to the control version system
git add test.txt
# commit changes
git commit -a
# this will require you to type the description, let's say "test" and save the file.
#push changes back to your personal repository
git push origin master
```

Make a pull request.
====================

On your repository page, find "New pull request" button.

More at https://help.github.com/articles/creating-a-pull-request/


