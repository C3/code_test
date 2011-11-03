The C3 Code Test Rules
==========
We'd like you to make a small script that checks a CSV file.  We don't want you to go crazy on this thing, we were thinking it would take a few hours of effort.  There's no language requirement and there's no one right answer. Once you've knocked something out just flick it back with whatever tests/output/thoughts you have (we're as interested in how you worked it out as what you finish up with).  Here's the brief, we've kept it super simple so if you have any questions feel free to ask rather than suffer not knowing :)

What we want:
A command line script  that reads the attached CSV file (data.csv) and implements the following four rules: 
1. Names cannot be less than four characters 
2. The code denoting state must be in the file states.csv
3.  The salary must be an integer and not a float 
4. The postcode must exist

If any of the first three rules are broken then we should get a warning message.  If the fourth rule is broken then we need an error
message.  Bonus points if you can filter the output using say a command line flag.  Bonus points also for pretty output.  We don't
mind what libraries you use or how long it takes, just make us feel warm and fuzzy about your programming skills and hopefully have a
little fun on the way :)
