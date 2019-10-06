# Ch2: 40-61

### Headings: 

- there are several types of headings disply in different sizes starting with `<h1>` and ending with `<h6>`,so is it just the size that the different between the heading tags or is it something else?

- The number beside the H letter refers to **how** much important that the head is 


### Paragrapghs:

- `<p>` by its name we could figure out what is the work of this tag


### **Bold** & *Italic*:

- here we also gonna mention the `<strong>` & `<em>` tags because they do the same thing,

- enclosing the text inside `<b> </b>` & `<strong> </strong>` will make the text bold but the differennt in the semantic.

- Same as `<em>` & `<i>` tags 


### Superscript & Subscript

- If `<sup>` make the text superscripted so what about `<sub>` ?


### White space

- White spaces inside the code editor don't affect the out put of this code like:

```
<p>
playing football
</p>
``` 

& 

```
<p>
playing       football
</p>
```

the output will be the same like this:

```
playing football

playing football
```

- the white space collapsing just help the code worker to orgnaize his code.


### Line Breaks & Horizental Rules

- So after we tested the white space, but how can we put a space between words inside the same paragraph? here comes the magic of `<br />` tag

- What if we wanna put a break line between lines inside the paragrapgh, there we could use `<hr />`


### Quotations

- sometimes you wanna qoute long text so you should use `<blockquote>` tag, but if it is short qoute use `<q>` tag.


### `<abbr>` 

- used for abbreviations, something that shows when you point at the text 


### Citations & Definitions 

1. `<cite>` to indecate that this is from someone

1. `<dfn>` to indecate that the text follows this tag is the definition of it 

- these two tags have some css effects on the output.


### I'm an Author 

- In this case you should use `<address>` tag to give your adress info


### Changes to Content

- `<ins>`: it __underline__ the text
- `<del>`: it ~strikethrough~ the text

<br />
<br />
<br />
<br />

# Ch10: 226-245

- Tjis is the form of the basic CSS

```
selector {
    property:value;
}
```

- Here comes some examples of property and their values:

1. color: orange;
1. float: left;
1. text-align: right;
1. font-family: Arial;
1. width: 50px;
1. hieght: 60%;

- There are three ways we can use CSS:

1. External CSS:
the css code will be in different file of the HTML code file

1. Internal CSS:
the css code will be inside the HTML code by using style tag

1. Inline CSS


<br />
<br />
<br />
<br />


# JS Ch 53-84:

- Script: a series of instructions that a computer can follow one-by-one.

- Statment: individual instruction or step.

- Comments: it doesn't the code but it helps you to know what is thos part of the code about.

- Variable: temporary storage that the bits of information needs to do its job.

- declaring variable:

` var Quantity; `

- Assign value to variable:

` quantity = value: `

### Data types:
1. Num
1. String
1. Boolean

### Rules for naming var:
1. must begin with a letter, $ or an (_).
1. musn't use (-) or (.) in a var name.
1. you can not use keywords
1. case sensitive 
1. use a name that describe the porpose of this var
1. if it is more than one letter use capital letter to sperate them

