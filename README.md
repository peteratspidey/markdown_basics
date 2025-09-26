# markdown_basics
this repo contains how to learn and implement Markdown for various purposes 
## how to add headings 
`# headings` # is used in starting for the headings
for first heading
`## h2 `
for second head
`### h3`
for third head
`#### h4`
for 4th head
`##### h5`
for 5th head
`###### h6`
for 6th head

> markdown only supports upto 6 headings

# text formatting

`*italic*`
> use `*` single asterisk for italic format in the start and end

`**bold**`
> use `**` double asterisk for bold text in start and end

`***bold and italic***`
> use `***` triple asterisk for bold and italic in start and end 


# Lists 
> use number and then dot 
1. ordered

` 1. item1 `

` 2. item2`

   ` 1. subitems1`
   
   ` 2. subitem2`

3. unordered
> use * for bullets
` * item 1 `

` * item 2 `

   ` * subitem 1`

   ` * subitem 2`
      
4. task lists
 use hyphen for tasks
`- item 1`

   `- subtiems1`

`- item2`

   `- subitems2`

   `- item3`

   
***another type***
use sqaure bracket with x for complete and blank for uncomplete
   `- [x] item 1 done `
   
   `- [x] item 2 done `
   
   `- [ ] item 3 undone `

> output

   - [x] item 1 done 
   
   - [x] item 2 done 
   
   - [ ] item 3 undone 

   
## 5. use code block
\` quote\`
> starts with '`' single backtick and ends with single backtick 

## 6. use code block for whole code body

\```bash
> write first line like this. starts with the 3 backtick and mention the type of code u are going to write ( bash, R ,python etc)

the code body
> second line starts with the code body

\```
> end with 3 backtick

## to use the link
`[LINK TEXT](https://www.google.com)`
> replace the word link text with the word u want and replace the link of the website with ur link

## to insert the image into a markdown text
`![Alt text](URL)`
> u can replace the word alt text with any keyword u want and change url to the link where the image is stored or with the path of the image

## emoji's
:+1: 
* `:+1:` is used to print thumbs up
* for more emoji use `:` then then after typing any keyword git will give u suggestions 


## table print
```
first header | second header
------------ | -------------
R1C1 | R1C2
R2Cl | R2C2
```
> the output will be 

first header | second header
------------ | -------------
R1C1 | R1C2
R2Cl | R2C2

## add a line 
```
---
```
> the output will be
---
