# Compilers Tests

A collaborative repo containing tests for the COMP207p compilers module. Includes a python script to run every test against your compiled lexer and parser.
If you use this repo please add any of your own test cases that at least use the naming convention n-<fileName>.s for files that should fail and p-<fileName>.s for files that should pass.

We are not sure if all of these tests are correct since we might have made different assumptions.

## Setting up
Copy all of the files in this repository into your compilers project.

Very important!! The tests will not run without this!!
Go into the sl directory and run make:
```
cd sl
make
```

Then in 
```
python3 runtests.py
```

Make sure you use python 3.5  to run the script because otherwise it might not work.
## Personalization
You can choose to either have a progress bar or to see how many tests you have failed. Just open up the runtests.py file and change the 'progressbar' global to either true or false, depending on if you want the progress bar or not.
