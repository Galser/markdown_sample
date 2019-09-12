# Main markdown sample file

This is the main fiule where I am going to ad in several commit my samples

## List of features (level 2 header) 

**Markdown syntax** allows us to : 

1. Format text
2. Create lists
3. Insert images
4. Create Headers and Quotes
5. Use basic syntax highlight for code
6. And some fancy extras (like tasks, emoji and so on), even in Pull Requests

### Format text (level 3 header, can be up to 6 levels)
We can apply **bold** as we use already did above or *italic* to some parts
We can have a special link formatting, for example [this markdown explanation from GitHub](https://guides.github.com/features/mastering-markdown/) 
or [this Markdown guide](https://www.markdownguide.org/basic-syntax/)

Note, headers can be created with alternative syntax 
----------------------------------------------------

Headers can be actually created with alternative syntax that slighlty reminds widely used in Python community RST format. 
For header 1 you create underlin with "=" symbol, for level 2 with symblo "-" like I did for this paragraph header. 

> We also can make blockquoptes, like this one

# Creating lists

We can have numbered lists :
1. One
2. Two
3. Many

Or we can have bulleted lists, for example with most popular Dutch fish species : 
* cod
* makrel AKA `Scrumbria Scumbriade` -> note here back-ticks used to make inline code highlight
* eurpoeean eel or officialy - `Anguilla anguilla`

And they can be nested also, iterating ove differnt formats : 
- We start with dash
- And then , if we have soimethign to nest
  * we putting two sapcves and star or dash
  * and - profit, we have list in list

# Insert images

Pretty straight forward. we can embed images, for example, above metnioned European eel : 
![Image of European Eel](https://upload.wikimedia.org/wikipedia/commons/5/58/Anguilla_anguilla.jpg)

# Headers and quotes
Now the headers are self-explnatory, just look one line above. As fro the quotes - we use ">" character to make them.
Once more about the same fish, quote from Wikipedia : 
>The European eel (Anguilla anguilla)[2] is a species of eel, a snake-like, catadromous fish. They can reach a length of 1.5 m (4 ft 11 in) in exceptional cases, but are normally around 60–80 cm (2.0–2.6 ft), and rarely reach more than 1 m (3 ft 3 in).
>
>Eels have been important sources of food both as adults (including the famous jellied eels of East London) and as glass eels. Glass-eel fishing using basket traps has been of significant economic value in many river estuaries on the western seaboard of Europe.

# Code 

If you want you code to look distinct in the text flow, just use back-ticks symbol, and either `wrap them inline` or go and span over several line, indeting them with four spaces : 

    package main
    import "fmt"
    func main() {
        fmt.Println("hello world")
    }

On GitHub we also cam have somethign that called fencing - with three backticks marking begin and end ofg the multipline block, especially  usefull with indent-based syntax languages like Python :

```
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```
And with fencing you can even explicitly specify syntax highlight, just comparfe this part with one above, same code : 

```python
x = 1
if x == 1:
    # indented four spaces
    print("x is 1.")
```

# Extras

( mostly by GitHUb, not supported in all places) 
From extras we can have tasks (lists can be ) 

- [ ] - the task that is not done
- [x] - or this , fancy, done one

Tables : 
Top 3 consume fish in NL 
Speciy | Percent 
-------|--------
Cod    | 60%
Mackrel| 20%
Eel    | 20%

And, sure - the world favorit emoji, for exampl of this cute  cat :cat2:

Plus some other feature that updated from time to time - SHA refernces, issue refernces  - links to Pull Request, mentioneing of @Galse ( <- user name ) , ~~strikethrough~~ 

_**That's all folks**_ ( bold + italic ) 
