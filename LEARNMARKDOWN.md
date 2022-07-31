### Mark down used for:
* Readme files
* Forum & blog posts
* Used in many static site Generators

Some of the Things You can format:

1. Heading
2. Lists
3. Emphasis
4. Links
5. Blocks of Code
6. Images
7. Blockquote
8. Horizontal Rules

<!-- For Heading -->
For Headings

Runs from h1 to h6 via (#)
# HEADING 1
## HEADING 2
### HEADING 3
#### HEADING 4
##### HEADING 5
###### HEADING 6

<!-- For Italics -->
## To italicisize

We can use * (astericks)

Or We can also use _ (hyphens) as demonstrated below

# *This is italicised*
## _This is also italicised_

<!-- For strong texts  -->
We can use double ** or double __

# **This is in bold**
## __This is also in bold__

<!-- For Strikethrough -->
We use double tilde

## ~~This text is striked throug using double tilde~~

<!-- For Horizontal Rule -->

This is like a separator
We use triple hyphens or triple underscores

---
### The Line Above has been created using triple hypens
___
### The line above has been created using triple underscores
___

<!-- Escaping characters -->
To escape characters we use \
\# We have escaped the # character
# We have not escaped the # character **Hello** & \*\*Hello\*\* are different

<!-- Blockquote -->
We use a greater than sign
> This is a block quote
> This is a block quote
> This is another block quote

<!-- Links -->
The text we want for the link goes in bracket [] and the links goes in parenthesis ()

[This is my github link](https://github.com/Thecodingobare)

<!-- Displaying a hover over our link -->
We add a space then "" at the end of our link

[This is my github link](https://github.com/Thecodingobare "This is my Github link")


<!-- Unordered Lists -->

We use a single asterick

* Am a product of a single asterick
* Me too!
* To nest me: use tab then input another asterick
    * Like so
    * Do not forget to add a space 

<!-- Ordered Lists -->

1. You add the number dot then space
2. That way
2. It also increment even if you add the same number as previous
3. Item four
    1. This is how we nest too
3. Unacheki

<!-- Inline code block -->
` Here we use backticks`

`Just like that`

<!-- Images -->
Similar to using links only that we put ! before the opening brackets

![This is how we add images](https://bit.ly/3QctDvH "A picture of me")

![I drew this](https://pbs.twimg.com/media/FAjLi5sXoAI300B.jpg)

___

# This is how Github uses markdown
___


<!-- Code Blocks -->
1. Code Blocks
Use triple back ticks
Example

```bash
npm install
npm start
```

2. We can also specify syntax specific code block
Say we want to do something in javascript

```javascript

function sayName(name){
    console.log("Your name is ", name)
}

console.log(sayName(Martin))

// output => Your name is Martin
```
For Python

```python
def SayName(name):
    print "Your name is ", name


// output
```

<!-- Tables -->

## Below is how we add tables in md for Github


|Name| Email|
|-----|---------|
|Martin| Martin@gmail.com|
|Martin| Martin@gmail.com|

<!-- Task Lists -->
It shows as checkboxes in Github if we use README.md

* [x] Task one which shows it is complete
* [] This task is not complete





