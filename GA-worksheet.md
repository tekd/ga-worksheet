####Name: Shenisis Kirkland
####ScriptEd
####Topic: HTML, CSS, and JS

**Directions:** Project #2 on dash.ga.co asks you to create a blog for Jeff. Although you are not creating what someone can consider a blog, you are creating an intricate webpage using HTML, CSS and some JavaScript. Three skills that you will master in your time with ScriptEd. Log into your General Assembly account on dash.ga.co walk through the second project while answering the questions below. After completing this project you will be asked to convert this page into a four page website about your self.


##Project #2 Part #1: Header HTML
1. What is the purpose of the header tag?
 The header tag of a website holds other tags inside it like <body>.
2. What is a Navigation Bar?
 A navigation bar is a series of links in a website.
3. What tag do we use to make a navigation bar? 
 We use the <ul> tag to make a navagation bar.

4.  <ul> Stands for  unordered list
    <li> Stands for  list item 

5. What does the <a> tag do?
It creates a link to another page.

6. What would the line of HTML below do?

``` html
<a href="http://www.google.com">Google</a>
```
This line of html would create a link to google.com named Google.

##Project #2 Part #2: Style the Header with CSS

1. What advantages does the `<link>` tag have over the `<style>` tag?
 
 Both the link tag and the style tag are ways to include CSS in an html file. The link tag in particular accesses CSS from an external file instead of keeping it all written in the html like the style tag.

2. What is normalize.css?
 
 normalize.css is a CSS file that makes the code flexible to any browser. It renders all elements more consistently and in line with modern standards.

3. Why do we need to add a padding property to the `<ul>` tag?

  We needed to add the paddling property to the ul tag because the links were off-center after centering all the elements on the page. The browser compensated for the the bullet points, so we needed to add padding to counteract it and pad all sides.

4. What does the “inline” property do to a list of items?
 
 The inline property lines the list of items horizontally on the same line. They exist within the normal flow of text.

5. What do the following padding values do?

    padding: 25px 50px 75px 100px;
 These values create specific padding values for each side by controlling each side's paddling individually.
    * top padding is 25px
    * right padding is 50px
    * bottom padding is 75px
    * left padding is 100px

    padding: 20px;
 This value refers to all sides of the element because it's just one value.
    * top padding is 10px
    * right padding is 10px
    * bottom padding is 10px
    * left padding is 10px

6. What is the difference between padding and margin?
 Margin refers to the space outside and around an element. While padding refers the the space inside th element.

7. What did border-radius do to the square border around the image?
 The border-radius created the rounding effect on the border.

##Project #2 Part #3: Responsive Design and Javascript

1. Why is responsive design becoming a more important aspect to consider when making a website compared to ten years ago?
 Before ten years ago there were no smart phones, ipads, or tablets. Those new devices each have their own format. Responsive design allows these increasingly more popular devices to view the content as any other device.

2. Why is it important to center and narrow text on a webpage? (think visually)
  I think it's important for you to center the text because if it's centered and narrow it's within line-of-sight which makes it easier to read.

3. What does this line of HTML do to an object? `margin: 0 auto;`
  This line of HTML creates 0 margin on the top and bottom of the element and auto margin on the left and right. It centers the element to the center of the page.

4. How does using `max-width` instead of `width` improve the readability of any webpage?
  By using max-width instead of width it tells the a program to activate with a limit of width or max-width. This allows browsers with lesser widths to be able to read it.

5. The media query to the below  will not be activated unless…

    ``` css
@media (max-width: 500px) {
    body {
        background: red;
    }
}
    ```
    
This media query will not be activated unless the browser is smaller than 500px.

6. What does each digit of this Hexidecimal Color Code represent? #E78

 E represents a high level of red

 7 represents a level of greeness

 8 represents a level of blueness

7. What is the Hex Color Code for true purple?  #609

8. Javascript is the programming language that allows websites to be interactive.

9. This tag allows us to add JavaScript into any webpage? <script> </script>

10. What is an event?
An event is one result of using your mouse.

11. How does JavaScript use events?
Javascript uses events to listen to specific events and takes action when it happens.

**Activity** Copy all the text from your project so far into a new JS Bin workspace. From there you can change the site to an “About Me” website about yourself. To do this you will need to do the following:

- Manipulate much of the text and tags to represent yourself… Not Jeff

- Make sure that your "Like" button functions. If it does not work ask a teacher for guidance.



