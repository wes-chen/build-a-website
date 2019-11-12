<a href="https://wes-chen.github.io/build-a-website/">Return to course home</a>

# Bootstrap

## What are we going to learn about today?

Today we will be learning about Bootstrap, and how to incorporate it into our own website.

## What is Bootstrap?

[Bootstrap](https://getbootstrap.com/){:target="_blank"} is a popular front-end component library that makes life a lot easier for people who want to make websites. It is a framework, and it can help you in the following ways ([source](https://www.taniarascia.com/what-is-bootstrap-and-how-do-i-use-it/){:target="_blank"}):

-   Prevent repetition between projects
-   Utilize responsive design to allow your website to adapt to various screen sizes - mobile, desktop, and everything in between
-   Add consistency to design and code between projects and between developers
-   Quickly and easily prototype new designs
-   Ensure cross-browser compatibility

It is a lot easier to use Bootstrap's components to build a website rather than have to write all the CSS of your website yourself.

Bootstrap's [Get Started Page](https://getbootstrap.com/docs/4.3/getting-started/introduction/){:target="_blank"} seems a little daunting already, but we'll only be focusing on using their prebuilt components that don't require any JavaScript.

Last time, we made our own CSS styling. Bootstrap has already written some CSS classes for you.
Most Bootstrap components utilize the `<div>` element.

Bootstrap documentation is our best friend. [Check it out here!](https://getbootstrap.com/docs/4.3/getting-started/introduction/){:target="_blank"}

## Core Concepts

### Typography

Bootstrap automatically applies styling on elements that we learned in Lesson 3.

Headings (`<h1>` through `<h6>`) are changed, and we can apply the `display` class to make those heading even larger.

The `lead` class will make your text element stand out.

Bootstrap has also defined some inline elements for you to modify your text. These include:
  - `<mark>` = highlight
  - `<del>` = deleted text
  - `<s>` = strikethrough
  - `<ins>` = added text
  - `<u>` = underline
  - `<small>` = fine print
  - `<strong>` = bold
  - `<em>` = italicize

Check out Bootstrap documentation on typography [here](https://getbootstrap.com/docs/4.3/content/typography/){:target="_blank"}!

### Images, Tables, Figures

Bootstrap also makes your `<img>` and `<table>` elements prettier.

Check out documentation for images [here](https://getbootstrap.com/docs/4.3/content/images/){:target="_blank"}!

Check out documentation for tables [here](https://getbootstrap.com/docs/4.3/content/tables/){:target="_blank"}!

Bootstrap also styles a `<figure>` element. It allows for captions for your images.

Check out documentation for figures [here](https://getbootstrap.com/docs/4.3/content/figures/){:target="_blank"}!

### Bootstrap Components

Bootstrap gives us access to _a lot_ of new components.

Usually we will call these by using `<div>` elements.

For example, for an alert component, we call the `alert` class.
```HTML
<div class="alert alert-primary" role="alert">
  A simple primary alert—check it out!
</div>
```

Here is a comprehensive list of components Bootstrap provides, along with links to their documentation:
  - [Alerts](https://getbootstrap.com/docs/4.3/components/alerts/){:target="_blank"}
  - [Badges](https://getbootstrap.com/docs/4.3/components/badge/){:target="_blank"}
  - [Breadcrumbs](https://getbootstrap.com/docs/4.3/components/breadcrumb/){:target="_blank"}
  - [Buttons](https://getbootstrap.com/docs/4.3/components/buttons/){:target="_blank"}
  - [Button Groups](https://getbootstrap.com/docs/4.3/components/button-group/){:target="_blank"}
  - [Cards](https://getbootstrap.com/docs/4.3/components/card/){:target="_blank"}
  - [Carousels](https://getbootstrap.com/docs/4.3/components/carousel/){:target="_blank"}
  - [Collapses](https://getbootstrap.com/docs/4.3/components/collapse/){:target="_blank"}
  - [Dropdowns](https://getbootstrap.com/docs/4.3/components/dropdowns/){:target="_blank"}
  - [Forms](https://getbootstrap.com/docs/4.3/components/forms/){:target="_blank"}
  - [Input Groups](https://getbootstrap.com/docs/4.3/components/input-group/){:target="_blank"}
  - [Jumbotrons](https://getbootstrap.com/docs/4.3/components/jumbotron/){:target="_blank"}
  - [List Groups](https://getbootstrap.com/docs/4.3/components/list-group/){:target="_blank"}
  - [Media Objects](https://getbootstrap.com/docs/4.3/components/media-object/){:target="_blank"}
  - [Modals](https://getbootstrap.com/docs/4.3/components/modal/){:target="_blank"}
  - [Alerts](https://getbootstrap.com/docs/4.3/components/alerts/){:target="_blank"}
  - [Navs](https://getbootstrap.com/docs/4.3/components/navs/){:target="_blank"}
  - [Navbars](https://getbootstrap.com/docs/4.3/components/navbar/){:target="_blank"}
  - [Popovers](https://getbootstrap.com/docs/4.3/components/popovers/){:target="_blank"}
  - [Progress Bars](https://getbootstrap.com/docs/4.3/components/progress/){:target="_blank"}
  - [Spinners](https://getbootstrap.com/docs/4.3/components/spinners/){:target="_blank"}
  - [Toasts](https://getbootstrap.com/docs/4.3/components/toasts/){:target="_blank"}
  - [Tooltips](https://getbootstrap.com/docs/4.3/components/tooltips/){:target="_blank"}

### Utilities

You might want to adjust the positioning of your elements, or you may want certain functions that might not have text in them. Bootstrap utilities allow for you to do this.

Call utilities by calling their class, like you would any other CSS element.

Here are utilities that adjust positioning or style of elements:
- [Borders](https://getbootstrap.com/docs/4.3/utilities/borders/){:target="_blank"}
- [Clearfix](https://getbootstrap.com/docs/4.3/utilities/clearfix/){:target="_blank"}
- [Display](https://getbootstrap.com/docs/4.3/utilities/display/){:target="_blank"}
- [Flex](https://getbootstrap.com/docs/4.3/utilities/flex/){:target="_blank"}
- [Float](https://getbootstrap.com/docs/4.3/utilities/float/){:target="_blank"}
- [Overflow](https://getbootstrap.com/docs/4.3/utilities/overflow/){:target="_blank"}
- [Position](https://getbootstrap.com/docs/4.3/utilities/position/){:target="_blank"}
- [Shadows](https://getbootstrap.com/docs/4.3/utilities/shadows/){:target="_blank"}
- [Sizing](https://getbootstrap.com/docs/4.3/utilities/sizing/){:target="_blank"}
- [Spacing](https://getbootstrap.com/docs/4.3/utilities/spacing/){:target="_blank"}
- [Text](https://getbootstrap.com/docs/4.3/utilities/text/){:target="_blank"}
- [Vertical Align](https://getbootstrap.com/docs/4.3/utilities/vertical-align/){:target="_blank"}
- [Visibility](https://getbootstrap.com/docs/4.3/utilities/visibility/){:target="_blank"}

Here are utilities that might help you add functionality.
- [Close icon](https://getbootstrap.com/docs/4.3/utilities/close-icon/){:target="_blank"}
- [Colors](https://getbootstrap.com/docs/4.3/utilities/colors/){:target="_blank"}
- [Embed](https://getbootstrap.com/docs/4.3/utilities/embed/){:target="_blank"}
- [Stretched Link](https://getbootstrap.com/docs/4.3/utilities/stretched-link/){:target="_blank"}
- [Close icon](https://getbootstrap.com/docs/4.3/utilities/close-icon/){:target="_blank"}


### Layout and the Grid

[The grid](https://getbootstrap.com/docs/4.3/layout/grid/){:target="_blank"} is one of the most crucial concepts in using Bootstrap. Basically, you can divide a row into 12 "subunits" that you can combine to divide things evenly. You can divide your row in half, or in thirds, or in quarters with ease.

We activate a grid by calling the `container` class. Inside of containers, we will use `<div>` elements with the `row` class. Inside of rows, we will use `<div>` elements with the `col` class.

Here is an example of how we use the grid:
```html
<div class="container">
  <div class="row">
    <div class="col-sm">
      One of three columns
    </div>
    <div class="col-sm">
      One of three columns
    </div>
    <div class="col-sm">
      One of three columns
    </div>
  </div>
</div>
```


Check out grid documentation [here](https://getbootstrap.com/docs/4.3/layout/grid/){:target="_blank"}!

## PRE-CHALLENGE #01: Starting fresh.

We're going to be completely honest.

Having all these colors and random pictures aren't very suitable for a professional website that you will use to present your extracurricular activites and class projects.

Let's go ahead and start from a blank slate so we can build a website that you actually can present to your teacher and other friends. However, we won't make you delete your past website. Instead, we will rename your old `index.html` into something else, then make a new `index.html`.

Go ahead and open your File Explorer, then find your way towards where your `index.html` is located. This will probably through `Documents -> GitHub -> [username].github.io`.

At the top of the File Explorer, go ahead and click `View` then check-mark `File name extensions`. If you complete this step (or have completed it), then you should able to see the `.html` portion for `index.html`.

![rename-02](rename_pics/rename-02.png)

You should see `index.html` once you navigate to your website repository. It's alright if you see other files as well - we will only focus on `index.html`:

![rename-01](rename_pics/rename-01.png)

Once you find `index.html`, go ahead and right-click it and select `Rename`. Go ahead and rename it to `other.html`.

![rename-03](rename_pics/rename-03.png)
![rename-04](rename_pics/rename-04.png)

Right-click an empty area, then select `New -> Text Document`. Go ahead and name this new file `index.html`. If asked if you want to change it, select `Yes`.

![rename-03](rename_pics/rename-05.png)
![rename-04](rename_pics/rename-06.png)
![rename-04](rename_pics/rename-07.png)

Now that you have a fresh `index.html` to work off, please right-click `index.html`, click `Open with -> Atom` and copy the code in the next image into your new `index.html`. Please replace `<title>` with your own name!

![new](rename_pics/new.png)

## PRE-CHALLENGE #02: Add Bootstrap to your website (index.html).

Before you can add Bootstrap components to your website, you must first load Bootstrap into your `index.html` as a stylesheet. You can load Bootstrap by copy-pasting their stylesheet `<link>` into your `<head>` before all other stylesheets.

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
```

Go ahead and paste the entire `<link>` above into your `<head>` tag of your `index.html`.

If you have done it correctly, then when you open up your `index.html` in Atom, your current `index.html` should look something like this:

![pre-challenge](pre-challenge-better.png)

## CHALLENGE #01: Center a image, name and description with Bootstrap.

From starting fresh, your `index.html` file should look something like this now:

![challenge01-1](challenge01/challenge01-1.png)

From here, let's go ahead and set a picture as an `<img>`, my name as a `<h1>` and my description as a `<p>`. I have chosen a picture of UCSD's Geisel Library for my `<img>`, but please feel free to pick anything as long as it is appropriate. Once you selected a `src` for your image, go ahead and give it a `class="img-thumbnail"` and a `width="200px"`.

Giving it the class of `img-thumbnail` will use Bootstrap to give your image a rounded border around it.

Your `index.html` file should look something like this now:

![challenge01-2](challenge01/challenge01-2.png)

Afterwards, we want to surround the `<img>`, `<h1>` and `<p>` HTML tags with a `<div>` tag. In other words, we will have a total of 3 `<div>` and `</div>` pairs in our `index.html`. Once we have done that, we will want to surround the entire inner-body of `<body>` with a `<div>`, bringing our total of `<div>` and `</div>` pairs to 4.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge01-3](challenge01/challenge01-3.png)

Once you have all your `<div>` in place, please give your first `<div>` a `class="container"`. For the rest of the three `<div>`, please give them a `class="row justify-content-md-center"`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge01-4](challenge01/challenge01-4.png)

Once you completed all these steps, double-clicking your `index.html` and opening it in Google Chrome should show something like this:

![challenge01-5](challenge01/challenge01-5.png)

If you are able to see something similar to above, then that means you are able to use Bootstrap to center your HTML content! If you are satisfied with your results, then go ahead and open up GitHub Desktop to `commit` and `push` your changes to your website online!

## CHALLENGE #02: Add two columns for your class project and other experiences with Bootstrap.

Now that your `index.html` has a picture, your name and your description, let's go ahead and create two columns so that we can later add your class projects and your other experiences.

Within your `index.html`, look for `</body>`, the closing tag for `<body>`. Right above `</body>`, go ahead and add a `<div>`, then give it a `class="container"`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge02-1](challenge02/challenge02-1.png)

Within the new `<div>` with a `class="container"`, create another `<div>`, then give it a `class="row"`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge02-2](challenge02/challenge02-2.png)

Within the new `<div>` with a `class="row"`, create two more `<div>`, and give them a `class="col text-center"`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge02-3](challenge02/challenge02-3.png)

Within the two new `<div>` with a `class="col"`, add a `<h2>` for your class projects within one `<div>`, then add another `<h2>` for your other experiences within the other `<div>`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge02-4](challenge02/challenge02-4.png)

Once you completed all these steps, double-clicking your `index.html` and opening it in Google Chrome should show something like this:

![challenge02-5](challenge02/challenge02-5.png)

If you are able to see something similar to above, then that means you have succesfully created columns using Bootstrap! If you are satisfied with your results, then go ahead and open up GitHub Desktop to `commit` and `push` your changes to your website online!

## CHALLENGE #03: Add cards to your class projects and other experiences using Bootstrap.

Now that your `index.html` has two columns ready for you to add your class projects and other experiences, we can go ahead and add cards for those columns!

Underneath your `<h2>` for class projects, create a new `<div>`, then give it a `class="card"`. Within that new `<div>` with `class="card"`, create another `<div>`, then give it a `class="card-body"`.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge03-1](challenge03/challenge03-1.png)

Within your `<div>` with a `class="card-body"`, add a `<h5>` with a `class="card-title"`. Go ahead and put the title of a class project with the `<h5>` tags. For my purpose, I will put the build-a-website title.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge03-2](challenge03/challenge03-2.png)

Underneath the `<h5>` tag, add a `<p>` with a `class="card-text"`. Go ahead and put the description of a class project with the `<p>` tags. For my purpose, I will put description of the build-a-website program.

If you have followed these steps correctly, your `index.html` file should look something like this now:

![challenge03-3](challenge03/challenge03-3.png)

If you double-click your `index.html` and open it in Google Chrome should show something like this:

![challenge03-4](challenge03/challenge03-4.png)

If you are able to see something similar to above, then that means you have succesfully created a card using Bootstrap! Let's go ahead and add a few more cards to our columns.

I've gone ahead and added two cards to my experiences column.

If you are able to add two cards to your experience column, your `index.html` file should look something like this now:

![challenge03-5](challenge03/challenge03-5.png)

Once you completed all these steps, double-clicking your `index.html` and opening it in Google Chrome should show something like this:

![challenge03-6](challenge03/challenge03-6.png)

If you are able to see something similar to above, then that means you have succesfully created cards using Bootstrap! Go ahead and create more cards if you have more class projects and other experiences you want to talk about. If you are satisfied with your results, then go ahead and open up GitHub Desktop to `commit` and `push` your changes to your website online!

## Survey time!

<a href="https://docs.google.com/forms/d/e/1FAIpQLSdgsWcI1Y_uI8YAd3po9IOmRa-PUIsjm1HdMbU2f3HAsMn_Zg/viewform?usp=sf_link"><button>Lesson 5 Survey</button></a>
