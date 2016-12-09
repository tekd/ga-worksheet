####Name:
####ScriptEd
####Topic: HTML, CSS, and JS

**Directions:** Project #2 on dash.ga.co asks you to create a blog for Jeff. Although you are not creating what someone can consider a blog, you are creating an intricate webpage using HTML, CSS and some JavaScript. Three skills that you will master in your time with ScriptEd. Log into your General Assembly account on dash.ga.co walk through the second project while answering the questions below. After completing this project you will be asked to convert this page into a four page website about your self.


##Project #2 Part #1: Header HTML
1. What is the purpose of the header tag? A header tag is made for headers and its similar to a body, however it is meant specifically for a website's header.

2. What is a Navigation Bar?
Navigation bar is just a list of link.
3. What tag do we use to make a navigation bar? <nav>

4.  <ul> Stands for unordered list
    <li> Stands for list items

5. What does the <a> tag do? The <a> is an anchor list, which makes list not just a text but links to another page.

6. What would the line of HTML below do? the line of HTML below would make it a link to a specific page, which is google.

``` html
<a href="http://www.google.com">Google</a>
```

##Project #2 Part #2: Style the Header with CSS

1. What advantages does the `<link>` tag have over the `<style>` tag?
The advantages of <link> tag is it includes CSS from an external file instead of writting it all out in HTML file.
2. What is normalize.css? Normalized.css is according to its websites and makes browser render all elements more consistently in line with modern standards so the page will look the same in any browser.

3. Why do we need to add a padding property to the `<ul>` tag?
We use padding property to the <ul> to make the list in the center.
4. What does the “inline” property do to a list of items? The "inline" property makes all links line up next to each others in a row.

5. What do the following padding values do?

    padding: 25px 50px 75px 100px;

    * top padding is 25px
    * right padding is 50px
    * bottom padding is 75px
    * left padding is 100px

    padding: 20px;

    * top padding is 0px
    * right padding is 20px
    * bottom padding is 0px
    * left padding is 20px

6. What is the difference between padding and margin? While margin creates space on the outside of an element, the padding creates space in the inside.

7. What did border-radius do to the square border around the image? it made the image's side more rounder.

##Project #2 Part #3: Responsive Design and Javascript

1. Why is responsive design becoming a more important aspect to consider when making a website compared to ten years ago?
websites before were designed differently and you couldn't access websites through your phone.
2. Why is it important to center and narrow text on a webpage? (think visually)
3. so it wont be all stretched out.

3. What does this line of HTML do to an object? `margin: 0 auto;`
4. it makes the line in the center instead of it being stretched out.

4. How does using `max-width` instead of `width` improve the readability of any webpage? max-width makes the article element smaller the XXpx and wont be any larger than that XXpx

5. The media query to the below  will not be activated unless… when the browser is a certain width.

    ``` css
@media (max-width: 500px) {
    body {
        background: red;
    }
}
    ```

6. What does each digit of this Hexidecimal Color Code represent? #E78 red

 E represents ...amount of redness

 7 represents ...amount of greenness

 8 represents ...amount of blueness

7. What is the Hex Color Code for true purple?  #F0F

8. javascript is the programming language that allows websites to be interactive.

9. This tag allows us to add JavaScript into any webpage? <script></script>       

10. What is an event? when you move,click,scroll press a key the browser fires off an event.

11. How does JavaScript use events? to select elements and listen for events.

**Activity** Copy all the text from your project so far into a new JS Bin workspace. From there you can change the site to an “About Me” website about yourself. To do this you will need to do the following:

- Manipulate much of the text and tags to represent yourself… Not Jeff

- Make sure that your "Like" button functions. If it does not work ask a teacher for guidance.



