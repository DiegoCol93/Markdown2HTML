# Markdown to HTML

> Markdown is awesome! All your README.md are made in Markdown, but do you know how GitHub are rendering them?
> It’s time to code a Markdown to HTML!

You can test your own README.md file to generate a README.html file that can be opened or read on your browser, and optionally using -v you can se the output it generates on the console and have it generate basic indentation with the -s option.

Usage: ./markdown2html.py README.md README.html

- 0. Start a script
- 1. Headings
- 2. Unordered listing
- 3. Ordered listing
- 4. Simple text
- 5. Bold and emphasis text
- 6. ... but why??

Begin of sample README.md

If you want to try if your version runs correctly copy use this sample below.

#
# 
# #
## ##
### ###
#### ####
##### #####
###### ######
# # #
# H1 #
## H2 ##
### H3 ###
#### H4 ####
##### H5 #####
###### H6 ######
###### #A long level 6 (######) heading... # ######
####### There is no H7 heading... :P ######












### Unordered List ###
- ul>li{1}
- ul>li{2}
### Other Unordered List ###
- ul>li{1}
- ul>li{2}

### Empty Unordered Lists ###
-
- 
- -


-

- 

- -

### Ordered List ###
* ol>li{1}
* ol>li{2} 
### Other Ordered List ###
* ol>li{1}
* ol>li{2} 

### Empty Ordered Lists ###
*
* 
* *


*

* 

* *

Hello

I'm a text
with 2 lines

Hello, I'm text with no extra new line to a * element.
* This is an ordered list element.
Text with space at the end and no extra newline to a ###### element.
###### ###### #########################################
Hello, I'm text with no extra new line to a - element.
- This is an unordered list element.
###### ###### #########################################

# My title
- He**l**lo
- Bye

Hello

I'm **a** text
with __2 lines__

**Or in bold**

I'm **a
not Broken text, or am I?** ;)

((I will live in Caracas))

But it's [[private]]

So cool!

(())

TEST for the ((cContent))
((TEST for the cContent))

((
))

((

))

((CCCCcccCCC CCCcccCCC CCCcccCCC))
CCCCcccCCC ((CCCHcccCeCllCo)) CCCcccCCC

((CTCCChccciCCC CsCCccicCCsC CCaCcccCCC))

CCCCcccCCC ((CTCCeccscCtCC)) CCCcccCCC
