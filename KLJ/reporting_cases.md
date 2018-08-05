# KLJ Reports
## Directory Structure
This directory contains all reported cases. There is a sub directory for every month (e. g. "2018_07" for July 2018). In those 
directories every case gets its own markdown file.

The cases are numbered chronologically every year. So the case "KLJ 18/3" is the third case reported in the year 2018 and
the case "KLJ 19/490" is the 490th case reported in 2019. The file names have to match the case number. For example the file
of the first case mentioned would be "KLJ_18_3.md". The month in which a case is decided does not affect its case number.

**Pilot cases are referred to not as "KLJ" cases but as "KLJP" cases!**

## Case Report Files
Every report begins with a heading. This heading has to contain the case number and may contain a heading that briefly
describes the case. This heading can also be reffered to as "case name" Therefore the first line of each case file should
look as follows:

```markdown
# KLJ YY/XX - Case Name
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

General Information | Case YY/XX 
--- | ---
Court | General
Jurors | 5
Date | June 20th 2004

**Cats are not doges.**
```

Then the facts of the case are stated. In this section you sum up the procedural history, arguments brought before the court
and evidence that has been submitted.

```markdown
## Facts
On June 18th, 2004 an image submitted to Doges on Trial was challenged by a prosecuter. The picture showed a cat. The
prosecuter claims that the picture does not meet the requirements for a meme to be accepted to the doge meme database.
```

Afterwards, the verdict is stated and the justifications given (in case there are such) are summed up. In this section you can
use block quotes to quote jurors' justifications.

```markdown
## Decision
The jurors decided that the image in question does not show a doge and shall not become part of the doge meme database.
```

Eventually, the author can give their own opinion on the case and what it means for the development of the law of Kleros.
This can be done in the "Implications" section.

```markdown
## Implications
This case has established precedent for how cats shall be treated when being submitted to a curated list containing of doges.
It has shown that a simple cat cannot be submitted to such a list. This will allow jurors in future cases to decide on cases
concerning cats more easily.
```

At the bottom of the article you can give additional information for the reader. Such information can be references to related
cases or the addresses of the parties and the jurors.

In addition to that you can set key words that make the report easy to find when doing a full text search. These key words
shall be written in italics at the very bottom of the report.

```mardkdown
## Further information

Contract Address: 0x...

Party A: 0x...

Party B: 0x...

Juror 1: 0x...

...

Related Cases: KLJ AA/BB, KLJ CC/DD

*doge, cat, curated lists*
```

## Resources
Sometimes it is neccessary to attach images or other files to your reports. For this purpose there is a resources folder in
which you can store files belonging to your report. Every resource gets a number starting from 1 for every new case. You need
your case number and resource number to name the resource files correctly. So when your case "KLJ 18/4" needs three images you
name them as follows:

"18_4_res_1.png", "18_4_res_2.png" and "18_4_res_3.png".

## Template
When you want to create a report feel free to copy the following template:

```markdown
# KLJ YY/XX - Case Name

## Case Summary

General Information | Case YY/XX 
--- | ---
Court | 
Jurors | 
Date | 

## Facts

## Decision

## Implications

## Further Information
```
