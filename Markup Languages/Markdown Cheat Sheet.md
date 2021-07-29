# Markdown Language
<!--- This is how you comment! --->

# header H1
## header H2
### header H3
#### header H4
##### header H5
###### header H6
---
---

*Italic*  
_Italic_   
**Bold**  
__Bold__  
~~Strikethrough~~

Line Breaks:
Add 2 spaces after your line (only works after text) or add:
\
\
...etc.

### Unordered List
* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered List
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

### Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


### Images
![Cool Heart](https://cdn.dribbble.com/users/60166/screenshots/12018819/media/61f4e36108078f66d0ee007a37ca3880.jpg?compress=1&resize=400x300)

### Links
http://github.com - automatic!
[GitHub](http://github.com)

### Blockquotes
Quote:

> repeat or copy out (a group of words from a text or speech),
> typically with an indentation that one is not the original
> author or speaker.

### Inline Code
I think you should use an `<addr>` element here instead.

### Emojis
All emoji codes are here :wink:	: https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md



# Examples:
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Markdown Language](#markdown-language)

## General info
This project is simple Lorem ipsum dolor generator.
	
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
	
## Setup
To run this project, install it locally using npm:
```
$ cd ../lorem
$ npm install
$ npm start
```

## Extended Syntax
Not all Markdown applications support these elements.
### Footnote
Here is a sentence with a footnote. [^1]

[^1]: This is the footnote!
