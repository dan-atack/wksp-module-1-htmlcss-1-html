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

c) [ true ] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A program that enables people with visual impairments to access websites by converting written text into audio.




## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<h1>, <img>, <ul>, <li>, <div>


b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<h1>, <h2>, <ol>, <li>, <a>


c) You want to sell designer hats. You need to receive orders from the user.

<h1>, <h2>, <p>, <form>, <input>, <a>


## Q4 - Can a button be a child of a button? Explain your reasoning



Yes; you might have a survey or something where there's an 'if yes, then...' with a follow-up question that's only asked depending on the answer to the first part of the question. So the child button would only appear if you pressed 'yes' (assuming it's a Y/N kind of question here).


## Q5 - What is the most generic tag you can use?

<body>


## Q6 - What do the following achronyms stand for?

a) `a`  Anchor

b) `ol`  Ordered List

c) `ul`  Unordered List

d) `li`   List Item

e) `tr`   Table Row

f) `th`    Table Head

g) `td`    Table Data


## Q7 - Usually, `td` elements are children of what kind of elements?

Table Rows <tr>

## Q8 - What is the difference between td and th?

<th> designates the header column of a table so there should only be one of them in a table, whereas <td> is used to fill all the other cells, so there can be many of them.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

<h1> - not that desired text size should influence your choice of which HTML elements to use.

## Q10 - In which situation can you use self closing tags?

For image files or things that don't have any written content that would require a separate closing tag to avoid confusion.

## Q11 - What is autofilling and why is it important?

It lets you reuse input data, to save time or to store information.

## Q12 - Which attributes are always present in an img element?

src = Tells the browser where to find the image (on a local computer or on another web page)

alt = Like a title for the image; useful if the image fails to load, or for screen readers to make a page more accessible.

## Q13 - Which attribute is always present for an anchor tag?

href = The address the link leads to.

