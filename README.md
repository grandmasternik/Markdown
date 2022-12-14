# Markdown Cheatsheet

# Purpose
The purpose of this repo is to explore Markdown and create a cheatsheet for me to reference at any given time when creating a README.md.

## Heading
Headings require the use of the hash to determine it's size
Be sure to use a space after has to activate

# Largest Heading
## Second Largest Heading
### Third Largest Heading
#### Small Heading
##### Smaller Heading
###### Smallest Heading

## Styling Text
Listed below: syntax for indicating emphasis of text in .md file

**Bold text**  __Bold text__
*Italicized text* _Italicized text_
 ~~Strikethrough text~~
 **Bold and _nested italicized_ text**
 ***Text is both, bold and italicized***
 <sub>Subscript text</sub> 
 <sup>Superscript text</sup>

 ## Quoting Text
 Unquoted text
 >Quote text in md by using the greater than symbol


## Quoting Code
Use `backticks` to quote your code

### Basic Git command
`git status`
`git add`
`git commit`

## Suppoted Color Models
Call out colors within a sentence by using backticks in discussions, pull requests and isssues with a supported color model and a visualization of the color will be display. Examples below:
No leading or trailing spaces within the backticks.

### HEX
Syntax: `#RRGGBB` Ex: `#0960DA` 
### RGB
Syntax: `rgb(R,G,B)` Ex: `rgb(9, 105, 218)`
### HSL
Syntax: `hsl(H,S,L)` Ex: `hsl(212, 92%, 45%)`

## Links
Creating inline links by [wrappingtextin](wrappingURLin.com)   
Create a Markdown hyperlink [GrandmastNik Github](github.com/grandmasternik)

### Section Links

### Relative Links

## Images
![Displaying a Md image](linkforimage.here)

## Lists
Create an unordered list in md using:
- Kale
* Calaloo
+ Bok Choy

Create an ordered list in md using:
1. Blackberries
2. Blueberries
3. Raspberries

### Nested Lists
Create a nested list by indenting the list items in md:
1. Shopping List
    - Veggies
    - Fruits
    - Drinks
        - Water
            - Spring Water

## Task Lists
- [x] this is how you x outw
- [ ]
- [ ] mwbe
However, task list item description that begin with parenthesis must be escaped like so:
- [ ] \(Optional) Open sesame

## Mention People & Teams
Use the @ symbol to mention people or teams. This will notify the tagged team or people.
@grandmasternik 

## Reference issues or pull request
Use hash symbol (#)

## Uploading Assets
This can be don to issues, pull requests, comments and .md files from browser by dragging and dropping, pasting or a selection method

## Using Emoji
Add by typing :EMOJICODE: 
Ex: :+1 :shiptit:

## Footnotes
Add by use of bracket syntax
This is a[^1]
multi-line[^2]
footnot [^3]

## Hiding Content w/ Comments
Tell GitHub to hide content fom the rendered Markdown
Ex: <!-- Hiddden -->  
    Use <!hyphen hypen "whatever is the hidden text" -->

# Reference
[Github Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)