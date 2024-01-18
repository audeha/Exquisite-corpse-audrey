<p>Hello!</p>
<p>This is me, Oleh</p>
<p>How are you?</p>

<img 
src="https://scontent-bru2-1.xx.fbcdn.net/v/t39.30808-6/326317496_588890172576446_7965595345705202560_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=efb6e6&_nc_ohc=E04g-pPCsQQAX9jdOl9&_nc_ht=scontent-bru2-1.xx&oh=00_AfCvWDN2ENVwuOq_YUeYSqQnMj7LCgY_3ylOSy0sjoeanQ&oe=65AD9001" 
alt="BeCode logo" style="float:left;margin-right:10px;"/>

# This is the title of my story.
> Access the markdown cheatsheel with; curl cheat.sh/markdown

<details>
    <summary>Collapsed summary</summary>
    <p>So here I see what's collapsed content</p>
    <p>and how it looks.</p>
</details>

Actually I might just copy paste the whole thing. 
this is training anyway. 

It's just training, is what audrey said.
She went to grab some stuff from her shed
When she opened the door, she hit her head

# headers
# h1 header
###### h6 header
 
# blockquotes
> first level and paragraph
>> second level and first paragraph
>
> first level and second paragraph

# collapsed text
To create a collapsible section (collapsed by default) showing the text "Collapsed Item 
Title", use this:
<details>
    <summary>Collapsed Item Title</summary>
    <p>Collapsed content</p>
    <p>Other collapsed content.</p>
</details>

# lists
Sub-bullets can be done with 2+ spaces or 1 tab
## unordered - use *, +, or -
* Red
  * sub-bullet
    * sub-sub-bullet
* Green
  - sub with dash
  + sub with plus
* Blue

## ordered (smth's wrong here)
1. First
  1. First sub-item <-- this is the best supported format
2. Second
  * Unordered  <-- this also appears to be a widely supported format
3. Third
  a. Lettered  <-- there is mixed support for this format
4. Fourth
  i. using roman numerals  <-- there is mixed support for this format
  ii. more stuff 

## check list
There is limited support for rendering check lists:
- [ ] incomplete task
    - [ ] incomplete sub-task
    - [x] complete sub-task
- [x] complete task


# code
## code block with 4 spaces/1 tab
regular text
        code code code

## in-line code
or:
Use the `printf()` function

## code block with syntax support
or a code block (optionally specifying the language, more details here: 
https://rdmd.readme.io/docs/code-blocks):
```shell
alias ltr='ls -ltr'
alias latr='ls -latr'
```

## key bindings
<kbd>⌘F</kbd>

# hr's (horizontal rules) - three or more of the following
***
---
___

# links
The "Title" is optional
This is [an example](http://example.com "Title") inline link.

## Links to Headings
Assuming you have a heading called `# My First Heading` then link is the 
case-insensitive string with spaces replaced by dashes:
[Visible Link Text](#my-first-heading "Hover-text link title")

# image
![Alt Text](/Users/aude/Documents/becode/md_chsheet.png)

# formatting
Italic:
*em* _em_

Bold: 
**strong** __strong__

~~strikethrough~~

# Tables

## Table Alignment
The alignment applies to the table data, not the header.

Left-aligned Stuff | Right-aligned Stuff | Center-aligned Stuff
| :--- | ---: | :---:
Some left stuff   | Some right stuff  | Some center stuff 
Some left stuff   | Some right stuff  | Some center stuff 

## Special Characters in Tables
First Header  | Second Header
------------- | -------------
Some stuff   | things about stuff
Other Stuff  |  A \| B
