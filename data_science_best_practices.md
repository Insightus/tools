# Data Science Best Practices

* Assume the data is wrong until you prove otherwise.  That is to say - check, check, check, and ideally build in automated checks that produce an error when appropriate

* Analysis should be reproducible - someone other than the original analyst should be able to figure out how to re-run the code and get the same results

* DRY - don't repeat yourself.  As with all programming, it's best to break things down into small, reusable functions as much as possible.  If you find yourself copying and pasting code, you're probably doing it wrong.

* Be nice to your future self (and your collaborators).  You can't overestimate how much more confusing your code will be when you look back at it.  Comment more than you ever think should be necessary.