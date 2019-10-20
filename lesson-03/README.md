<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>

# Install Atom.

We have realized that Notepad is terrible. Let's improve your programming environment by installing Atom.

[Please click here to open the Atom installer.](https://atom.io/){:target="_blank"}

Once we have Atom installed, let's continue learning!

# HTML Basics

## What is HTML?

HTML stands for Hypertext Markup Language. HTML describes the basic structure of a web page semantically, or in other words it conveys how to render the graphics of a web page to the browser.

![triad](wwwtriad.png?raw=true "triad")

Learning HTML is the first step in creating websites, combined with JavaScript and CSS you will be able to create aesthetically pleasing and functional websites. For now let's focus on how to add basic content on a page, like text and images!

## HTML: Basics

### Anatomy
Every HTML element is comprised of:
- Opening tag: the first HTML tag that contains the element name, surrounded by ` < ` and ` > `.
- Content: the information contained betwen the opening and closing tags.
- Closing tag: the second HTML tag that contains the element name, surrounded by ` </ ` and `>`.

![triad](element.png?raw=true "triad")


### Essential Elements

- **&lt;p&gt; Hello World! &lt;/p&gt;** <br/>
`p` stands for "paragraph" and will be your bread and butter element.

- **&lt;h_&gt; Heading &lt;\h_&gt;** <br/>
`h_` is a heading element, replace `_` with a number between 1 and 7 to choose the size of the heading.

- **&lt;a href="/"&gt; Link &lt;/a&gt;** <br/>
`a` stands for "anchor" it is used to redirect the user to another location in the same or other web pages.

- **&lt;button&gt;Click Me!&lt;/button&gt;** <br/>
As the name suggests, this element creates a clickable button.

- **&lt; img src="blank"/&gt;** <br />
`img` stands for "image", this element is used to embed images in the web page. Replace `blank` with the link to the image you want to display. Note how this element comprises of only one tag. The image tag is part of a family of HTML tag exceptions that only require one tag.

- **&lt;br/&gt;** <br>
`br` stands for "line break", this element adds a new line after the previous element. (Its functionality is similar to the "Enter" key on the keyboard ).

- **&lt;div/&gt; ... &lt;/div&gt;** <br/>
`div` stands for "division" (or section) in an HTML document. The `div` element is often used as a container for other HTML elements to style them with CSS or to perform certain tasks with JavaScript.

### Slightly more complex Elements

- **&lt;ul&gt; ... &lt;/ul&gt;    and     &lt;ol&gt; ... &lt;/ol&gt;** <br />
These are HTML list elements. `ul` creates an **unordered** list while `ol` creates an **ordered** list. <br/>
`li` which stands for "list item", is used to add items to the lists.

Ex:<br/>
&lt;ol&gt; <br/>
 &nbsp;&nbsp;&lt;li&gt; This &lt;/li&gt;<br/>
 &nbsp;&nbsp;&lt;li&gt; is &lt;/li&gt;<br/>
 &nbsp;&nbsp;&lt;li&gt; an &lt;/li&gt;<br/>
 &nbsp;&nbsp;&lt;li&gt; ordered &lt;/li&gt;<br/>
 &nbsp;&nbsp;&lt;li&gt; list. &lt;/li&gt;<br/>
&lt;/ol&gt;<br/>

Output:

1) This

2) is

3) an

4) ordered

5) list.

<br/>

- **&lt;table&gt; ... &lt;/table&gt;** <br/>
As the name suggests, this element is used to create table elements. <br/>

Ex:<br/>
&lt;table&gt; <br/>
 &nbsp;&nbsp;&lt;tr&gt; <br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;th&gt; Table Heading1 &lt;/th&gt;<br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;th&gt; Table Heading2 &lt;/th&gt;<br/>
 &nbsp;&nbsp;&lt;/tr&gt;<br/>
 &nbsp;&nbsp;&lt;tr&gt; <br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt; Table Data1 &lt;/td&gt;<br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt; Table Data2 &lt;/td&gt;<br/>
 &nbsp;&nbsp;&lt;/tr&gt;<br/>
 &nbsp;&nbsp;&lt;tr&gt; <br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt; Table Data1 &lt;/td&gt;<br/>
 &nbsp;&nbsp;&nbsp;&nbsp;&lt;td&gt; Table Data2 &lt;/td&gt;<br/>
 &nbsp;&nbsp;&lt;/tr&gt;<br/>
&lt;/table&gt;<br/>

Output: <br/>

![triad](table.png?raw=true "table")

**SO MANY TAGS!!** Let's examine them one by one:
  - `tr` stands for table row, this is used to add a row to the table, this element contains all the data in each row
  - `th` stands for table heading, this is used in the first row of each table for the heading, the content is **bold** by default
  - `td` stands for table data, this is used to add data in the table

## How to set up a proper HTML file
Professional HTML files have much more than just a body element containing the different HTML elements, they have an element hierarchy and most important of all they contain **metadata** (data about data) that tells the browser how to display your web page.

### Hierarchy
- `<!DOCTYPE html>` this is the first line of code inside a HTML file, it tells the browser that the file should be interpreted as a HTML file.

- The `html` element is the great-great-great-...-grandparent of all HTML elements and it's the **outermost** element in a HTML file. This is used to tell the browser that the contents inside the tags are proper HTML elements.

- The `head` element contains the metadata we mentioned before. Anything inside the `head` tag will not be displayed on the web page. This tag should be inside the `html` tag and outside the `body` tag.

- The `body` element contains all the other elements that you want to display on the web page. This tag should be inside the `html` tag and outside the `head` tag.

Ex:<br/>
![boiler_plate](broiler.png?raw=true "boiler plate")

### Metadata
The following HTML metadata elements should be declared inside the **`head`** element.
- The `title` element defines the title of the document and also the title displayed on the browser tab.
- The `style` element defines style information for the HTML page. More on this in the CSS lesson.
- The `link` element is used to link to external CSS style sheets.
- The `meta` element is used to specify author, description, and other metadata.
- The `script` element is used to define client-side JavaScript. More on this in the JavaScript lesson.
Ex: <br />
<br/>

![metadata](metadata.png?raw=true "metadata")

## Challenge!

Here is a really simple HTML page, try making an exact replica!

( Extra cookie points: try enclosing sections of the page inside `div` containers, you will find it useful later on ).

![solution](solution.png?raw=true "solution")

Raw text: [Link](brown_bear_raw.txt).

Spec file: [Link](brown_bear.png).

## Final Remarks
[Here](https://wes-chen.github.io/build-a-website/lesson-03/sample.html) is an example of things you could put on your website!

[Codecademy](https://www.codecademy.com/learn) does a pretty good job of teaching HTML. Run through [this HTML tutorial](https://www.codecademy.com/learn/learn-html) to learn more.

## Next Time

Next time, we learn about CSS. If you are a proactive student, please run through this [codecademy tutorial](https://www.codecademy.com/learn/learn-css) at your own pace before the next lesson.

Thanks for coming, see you next week!

<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>
