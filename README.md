# Code Fellows reading-notes
## *My reading notes for code fellows*

### Introduction

Hi my name is **Nick**.  I like video games and Legos. My fav DC hero is Batman.

<img src="seidel batman.jpg" width=40% height=40%>


<img src="Rich.gif" width=40% height=40%>


#### 3 reminders to keep myself in the growth mindset:

- This is supposed to be new and different!
- Keep trying!
- Commit to learning something new each day.

##### Link to my [Github](https://enviouscodefellow.github.io/reading-notes/) profile.

### Read 01 Notes

[GitHub Markdown Syntax] [1]
[1]: <[https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax](https://www.markdownguide.org/basic-syntax/)>

#### Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

#### Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL.

\!\[The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")

#### Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

##### Formatting the First Part of the Link
The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of brackets displays a label used to point to the link you’re storing elsewhere in your document.

Although not required, you can include a space between the first and second set of brackets. The label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.

This means the following example formats are roughly equivalent for the first part of the link:

* \[hobbit-hole]\[1]
* \[hobbit-hole] \[1]

##### Formatting the Second Part of the Link
The second part of a reference-style link is formatted with the following attributes:

1. The label, in brackets, followed immediately by a colon and at least one space (e.g., [label]: ).
2. The URL for the link, which you can optionally enclose in angle brackets.
3. The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.

This means the following example formats are all roughly equivalent for the second part of the link:

* \[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
* \[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
* \[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
* \[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
* \[1]: \<https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
* \[1]: \<https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
* \[1]: \<https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

You can place this second part of the link anywhere in your Markdown document. Some people place them immediately after the paragraph in which they appear while other people place them at the end of the document (like endnotes or footnotes).

### Read 02 Notes

#### Linux Tutorial - 1. The Command Line
##### Shortcuts

The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial. Take note of them as not only do they make your life easier, they often also save you from making silly mistakes such as typos.

* Shortcut: Here's your first shortcut. When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times. You can also edit these commands using the left and right arrow keys to move the cursor where you want.

#### Linux Tutorial - 2. Navigation
##### Summary
**Stuff we Learnt**
* pwd
Print Working Directory - ie. Where are we currently.
* ls
List the contents of a directory.
* cd
Change Directories - ie. move to another directory.

**Important Concepts**
* Relative path
A file or directory location relative to where we currently are in the file system.
* Absolute path
A file or directory location in relation to the root of the file system.

#### Linux Tutorial - 3. More About Files
##### Summary

**Stuff we Learnt**
* file:
    obtain information about what type of file a file or directory is.
* ls -a:
    List the contents of a directory, including hidden files.

**Important Concepts**
* Everything is a file under Linux
    Even directories.
* Linux is an extensionless system
    Files can have any extension they like or none at all.
* Linux is case sensitive
    Beware of silly typos.
