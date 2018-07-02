# KLJ Reports
## Directory Structure
This directory contains all reported cases. There is a sub directory for every month (e. g. "2018_07" for July 2018). In those 
directories every case gets its own markdown file.

The cases are numbered chronologically every year. So the case "KLJ 3/18" is the third case reported in the year 2018 and
the case "KLJ 490/19" is the 490th case reported in 2019. The file names have to match the case number. For example the file
of the first case mentioned would be "KLJ_3_18.md". The month in which a case is decided does not affect its case number.

## Case Report Files
Every report begins with a heading. This heading has to contain the case number and may contain a heading that briefly
describes the case. This heading can also be reffered to as "case name" Therefore the first line of each case file should look as follows:

```markdown
# KLJ XX/YY - Case Name
```

The heading is followed by an overview section that gives some general information on the case. The exact information that
it will contain can be specified once the first cases have been ruled and we know what information we can access. It is very
likely, however, that it will contain at least the date of the ruling, the subcourt and the number of jurors who ruled on the
case. This information is represented in a table. 

Furthermore, the overview shall contain the principle of law that was established by the ruling or the fact that makes the
ruling worthy to be reported. This short summary shall be emphasised.

With all this in mind the code of the overview section is going to look something like this:

```markdown
## Case Summary

General Information | Case XX/YY 
--- | ---
Court | General
Jurors | 5
Date | June 20th 2004

*Cats are not doges.*
```
