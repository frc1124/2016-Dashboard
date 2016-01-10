2015
====

2015 Recycle Rush Robot Code

Branching Workflow
------------------

We want to use a [branching workflow](https://www.atlassian.com/git/tutorials/using-branches/) to control our code in this repo. That means, if you're working on a new feature, branch from a common commit, develop your feature on the new branch, and then merge your changes back in. There are a few base branches that should stay separate (and you can always create more, like for a drivetrain testing robot):
 - [master](https://github.com/frc1124/2015/tree/master): This should contain the code for the competition robot
 - [practice-bot](https://github.com/frc1124/2015/tree/practice-bot): This is where the code for the practice robot should reside. Again, features not yet ready should be developed in separate branches and merged in.
 - [blank-structure](https://github.com/frc1124/2015/tree/blank-structure): This contains an empty version of the base code. Branch this for creating new "robots". Eventually, structure improvements should be backported to this tree.

If you want to create a new empty branch, you can checkout the [base tag](https://github.com/frc1124/2015/releases/tag/base) and branch from there, which gets you an empty repo.
