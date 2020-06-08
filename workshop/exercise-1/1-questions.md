# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false ] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ true - in my understanding img should have at least an 'src' and an 'alt' attributes like in the lecture but this html works in the code preview anyway... ] `
<ul>
</ul>
<img/>
<ol>
    <li>one</li>
</ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

"A screen reader is a form of assistive technology (AT)[ that renders text and image content as speech or braille output" 
They help visually impaired or illiterate people access the content of a webpage or a software
See wikipedia https://en.wikipedia.org/wiki/Screen_reader

As for websites, screenreaders rely on the structure of HTML docs to organize and communicate content to their users. So as developers, we need to care about using the right HTML tags so screenreaders can optimally work and our website reach disabled users. 

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img>
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul> <li> <a>
c) You want to sell designer hats. You need to receive orders from the user.
<button> <form> <input>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
<button> can't have a clickable descendant.  Because <Button> is itself a clickable element, it cannot be the child of another button.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a`
anchor
b) `ol`
ordered list
c) `ul`
unordered list
d) `li`
list element
e) `tr`
table row
f) `th`
table head
g) `td`
table data

## Q7 - Usually, `td` elements are children of what kind of elements?
'tr'

## Q8 - What is the difference between td and th?
Both are table cells but 'th' is usually used in the first row as header of the column.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?
when we use an element that doesn't have any children

## Q11 - What is autofilling and why is it important?
A form is autofilled when the browser automatically completes its input fields based on values that the user has entered before. 
It is important because it is convenient for users so it improves the usability of the website. For example, if someone runs an online store or wants to improve communication with its customers, she would want to make sure autofilling works in order to make the experience of the website the smoother she can.

## Q12 - Which attributes are always present in an img element?
'src' and 'alt'

## Q13 - Which attribute is always present for an anchor tag?
'href' attribute