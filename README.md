# scripting-docs

**Essentials of Shell Scripting** began about 2015 as a small text file which
I used as a personal reminder of bash syntax, operators, and variable
expansion syntax. I was writing scripts on a daily basis and didn't want to
have to look up things in a book when I could grep a textfile and return a
paragraph of text.

Then I wanted things to remind myself about eval, expr, file descriptors, and
how to generate random numbers. The document grew and grew.

It is still a summary of different features, syntax issues, and usage habits
with ksh and bash, with occasional reminders of what ksh can do that bash
cannot, and vice versa. It is a reminder of things I (or you) should have
learned or used before: it is not a tutorial.

**Shell Scripting Best Practices** began a couple of years later when I was
passing on my experience to Unix engineers writing scripts for automated
processes, namely, cron and Control-M.

It's not so much a list of syntax trivia, as it is a list of warnings about
things to avoid, or hopefully awkward things to modify. I've seen bad code put
into Production because (for example) the way it was written it never produced
an error, but it also never did what it was intended to do.

Further, this document contains helpful ideas for code maintenance and
clarity. Most of my examples are bash, ksh, and the smaller Unix tools like
awk, grep, sed, and perl, since that is what our scripts used at that time.


----
Eric Pement
