# What is markdown?  

* Plain text format
* Easy to read
* Easy to write
* Easy to learn
* Easy to parse
* Lots of support
* Many extensions

## To preview markdown contents:
    go to Packages, choose markdown preview, Toggle Preview
This will show what the file looks like in a HTML form

## Emphasize
### italic:
*italic*
### strong:
**strong**
### code tag:   
`code tag`
### render as code:
    Put four space before this line, or a Tab
### render a block quote:
>to render a whole paragraph as a block quote, it is very easy. Here is an example of a block quote. It consists of two paragraphs.  
So here comes the second paragraph. And to render as a block quote, just put a > before the whole paragraph.  
>> To add a second block quote inside the first one, put two >> before it.
## Paragraph breaker:  
If you want to break a long paragraph,you just need to add two spaces at the end of the sentence, and type a return.
## headers:
header 1:  
put ====== after the line  
header 2:  
put ------ after the line
### Another way to make headers:  
put # before the sentence, one # is h1, ## is h2, maximum is ##### which is h5. Note: there should be a space between the # and the contents. Some people like to put # at the end to match, for example:
    ## header2 ##
## Put a horizontal line:
use three \*, here is an example:

## Unordered list:
* you can use \*
* you can use \-
* you can also use \+
 + if you put one indent, it will show as a second level
 + works with \*, \- and \+  

## Ordered list:
1. list 1
2. list 2
4. list 3
5. the number doesn't really matter, but recommended to keep things looking logical

## Create inline link:
[Amazon webpage](https://www.amazon.com/) is a good webpage I used to buy stuff
## Add a active link:
<https://www.amazon.com/> this is how it works with two angle brackets.

## reference link:
This is an example of a [link][1], this is useful to have all references to be listed at the end of the documents

[1]: https://www.amazon.com/

## Add image:
![Jap anime pic](https://images.alphacoders.com/205/205913.jpg)

# GFM Modifications

* Ignore underscores
* Strikethrough ~~style~~
* \[x] task lists
* [x] task lists
* Auto hot linking
* fenced codeblocks
* Tables

## treat as code on GitHub
```python
print("this is a python code")
```
## striketrhoug
this message ~~here~~ will be striked through

| Header One     | Header Two     | header 3 | header 4
| -------------  |  ------------- | :------: | --------:
| Item One       | Item           | a        |  b

right aligned: put \: at the end  
left aligned: put \: at first  
center alined: put \: at two ends \:  
you can also use markdown table on Github, it's much quicker

# Some important resources:
[Common Mark](https://commonmark.org/)  
[Github emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
