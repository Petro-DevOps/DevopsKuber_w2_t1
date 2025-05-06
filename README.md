Instruction:

To create a new branch and switch to it at the same time, you can run the git checkout command with the -b switch:

$ git checkout -b development
Switched to a new branch "development"

This is shorthand for:

$ git branch development
$ git checkout development

Now you can commit your changes within this branch