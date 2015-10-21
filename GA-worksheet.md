####Name: Anthony Yang
####ScriptEd
####Topic: HTML, CSS, and JS

**Directions:** Project #2 on dash.ga.co asks you to create a blog for Jeff. Although you are not creating what someone can consider a blog, you are creating an intricate webpage using HTML, CSS and some JavaScript. Three skills that you will master in your time with ScriptEd. Log into your General Assembly account on dash.ga.co walk through the second project while answering the questions below. After completing this project you will be asked to convert this page into a four page website about your self.


##Project #2 Part #1: Header HTML
1. What is the purpose of the header tag? The purpose of the header tag is to hold up the information in the body of the website such as the image. 

2. What is a Navigation Bar? The navigation bar contains the list of links that guide people to another page. 

3. What tag do we use to make a navigation bar? <      >

4.  <ul> Stands for unorganized list. 
    <li> Stands for list items. 

5. What does the <a> tag do? The tag opens the link the website is linked to, without it, you're unable to open that link.

6. What would the line of HTML below do? The line below html directly open Google.

``` html
<a href="http://www.google.com">Google</a>
```

##Project #2 Part #2: Style the Header with CSS

1. What advantages does the `<link>` tag have over the `<style>` tag? The <link> tag lets you include CSS from an external file. 

2. What is normalize.css? It's a CSS file that preserve the CSS through any broswer. 

3. Why do we need to add a padding property to the `<ul>` tag? We need to add a padding property to the <ul> tag because
it centers the items on the list. 

4. What does the “inline” property do to a list of items? It makes every item listed to locate on the same line. 

5. What do the following padding values do?

    padding: 25px 50px 75px 100px;

    * top padding is 25 px
    * right padding is 50 px
    * bottom padding is 75 px
    * left padding is 100 px

    padding: 20px;

    * top padding is 20 px
    * right padding is 0 px
    * bottom padding is 0 px
    * left padding is 0 px

6. What is the difference between padding and margin?
The difference between padding and margin is padding creates space inside a border, yet margin is the space outside of it. 

7. What did border-radius do to the square border around the image?
The border radius kind of cut the sides of the square border and makes the square rounder.

##Project #2 Part #3: Responsive Design and Javascript

1. Why is responsive design becoming a more important aspect to consider when making a website compared to ten years ago?
Responsive design is a more important aspect because it preserve the layout of the webpage regardless of what device you access the webpage with. Back then, techonology wasn't perfected and when you switch gears to another device, it might change the design. Hence, responsive design does the opposite to not bemuse people.

2. Why is it important to center and narrow text on a webpage? (think visually)
It's important to center and narrow the text on a webpage because when readers read it, everything's centered. Nothing have to read left to right or just one sided. It makes the webpage more stylistic and modern.

3. What does this line of HTML do to an object? `margin: 0 auto;` The html tag centers the object. 

4. How does using `max-width` instead of `width` improve the readability of any webpage?
The image wouldn't exceed the maximum length set so the image wouldn't overshine the text.

5. The media query to the below  will not be activated unless… the browser size is not larger than 500px.

    ``` css
@media (max-width: 500px) {
    body {
        background: red;
    }
}
    ```

6. What does each digit of this Hexidecimal Color Code represent? #E78

 E represents ... the amount of redness.

 7 represents ... the amount of greenness.

 8 represents ... the amount of blueness.

7. What is the Hex Color Code for true purple?  #509

8. Javascript is the programming language that allows websites to be interactive.

9. This tag allows us to add JavaScript into any webpage? <script>

10. What is an event? An event is an alert informing the user something. 

11. How does JavaScript use events? They listen to the specific events and when it runs, it fires off the event. 

**Activity** Copy all the text from your project so far into a new JS Bin workspace. From there you can change the site to an “About Me” website about yourself. To do this you will need to do the following:

- Manipulate much of the text and tags to represent yourself… Not Jeff

- Make sure that your "Like" button functions. If it does not work ask a teacher for guidance.



