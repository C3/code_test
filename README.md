Teh C3 Code Test
================

We'd like you to build a thing that validates data in a CSV file.
We don't want you to go crazy on this thing, just a few hours.

- There's no one right answer.  
- There's also no language requirements, just please choose something sensible like Ruby or Python (cross-platform preferred).  
- While something from [Esolang](https://esolangs.org/) might warrant hacker cred, it makes our job harder. We prefer people who make our jobs easier.  
- Once you've given it a shot, get the code to us with whatever thoughts you have.  
- It's good to see easy to read code with nice comments and unit tests. Make sure there are instructions on how to build/run the program.  
- We're interested in the tradeoffs you make, and want to learn a bit about your process so it's best if you send us a git repo (e.g. GitHub, BitBucket, self-hosted, etc).  


**We're realistic, and we make mistakes ourselves; so don't make it perfect, unless you're bored enough to add ANSI colours :D**

The Brief
---------

Here's the brief, we've kept it super-simple, if you have questions then get in touch!

We're after a command-line based thing.
This thing reads the attached CSV files (`data1.csv` and `data2.csv`), and validates the data using these rules:

1. Names cannot be less than four characters 
2. The code denoting state must be in the file states.csv
3. The salary must be an integer, and not a float
4. The postcode must exist

If any of the first three rules are broken then we should get a warning message showing which rule/s were broken.
If the fourth rule is broken then we need an error message.

That's about it. Have fun.
