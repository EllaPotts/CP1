# F21CP1
## Written notes from class

Sept. 8

GitHub:
Repository Deletion-
In order to delete a repository from GitHub, you must go into settings and type in a code to permanently delete it.
Repositories that have been deleted cannot be accessed or recovered.
Other Remote Repositories-
You can have a secondary remote repository that acts as a "backup to a backup", on something like BigBucket or GitLab.
Version Control-
You can also have multiple versions of a file on GitHub which allows you to utilize version control.
Create New Repository-
    github.com/new
    Choose a name for your project
    Write a description of the file
    Choose whether you want to add a README where you can place text information about your project
    Choose whether you want to add a .gitignore that tells the computer to ignore the files that are listed inside of it.
    Choose whether you want to add a license explaining how your code can be used.
    main will automatically be set as the default branch for all repositories.
    Once you create the repository, you can navigate to the files to begin writing or importing your code.


File extension: the suffix of a file describing to the computer what should be found inside (ex. .txt, .jar, .java, .md, .exe).
Any file that begins with a "." will not be read by the command line.

Committing:
    Always write a short message that tells you what you've changed in this version from the last one.
    Commit multiple times a day and don't delete anything until after you've committed that version to GitHub.  That way you can go back in case you changed something that didn't work.
    You should commit your test files at the same time as your code.
    You don't need to commit every time you add a comment or make  asmall change, but major changes should always be committed.
    If you can't describe your changes in one commit, you haven't committed enough!

File Editing tips:
# indicates a title
## indicates a subtitle
### smaller subtitle
#### smaller yet!
##### even smaller
###### gray and smallest

* add bullet point
- or like this
+ or even this

*Italicizes words!*

Regular words!

_Also italicizes words!_

**Bolds words.**

Regular words!

__Also bolds words.__

If you are bolding or italicizing within a word, use asterisks rather than underscores due to formatting issues.

> Block
> Quote
> 
> If you want to make an apple pie from scratch, you must first create the universe.

Make sure to add \> in empty lines too, and use \ to ignore formatting for symbols.

To add java code, use ```java (code) ```.

You must hit enter twice between lines to move to the next line in the code.

Max value of integer in java is Integer.MAX_VALUE (which is in all caps because it is a final int!) or MIN_VALUE for the lowest possible value.
This also works for doubles.
If you add one to the MAX_VALUE it loops around to the lowest value again.
You can also use Double.POSITIVE(or negative)_INFINITY!


### Note:
In the command prompt, you can use *JSHELL* to experiment with Java code;


# Some text editor testing...

# CP1
## Test 1
### Test 2
#### Test 3
##### Test 4
###### Test 5
* Just testing.
* Test some more.

### Remember that constants should be capitalized.
```java
final int BIG = 10_000_000;
```

During the class, I have learned about different infinities.  

```java
Integer.MAX_VALUE;
Double.MAX_VALUE + 1;
```
