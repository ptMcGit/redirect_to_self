# Redirect To Self

## What does it do?

This script allows you to "catch" the changes to a file at the end of a pipe and save those changes to the same file aka save a file in place.
Optionally, you can back the file up by providing option `-b`.

## How to use it

Pipe into the command and provide the name of the file you would like to write to:

     ... | redirect_to_self file1

Provide option b to back the file up:

     ... | redirect_to_self -b file1

