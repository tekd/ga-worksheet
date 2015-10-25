####Name: Angelica Hurtado
####ScriptEd
####Topic: HTML, CSS, and JS

**Directions:** Project #2 on dash.ga.co asks you to create a blog for Jeff Buckley. Although you are not creating what someone can consider a blog, you are creating an intricate webpage using HTML, CSS and some JavaScript. Three skills that you will master in your time with ScriptEd. Log into your General Assembly account on dash.ga.co walk through the second project while answering the questions below. After completing this project you will be asked to convert this page into a four page website about your self.


##Project #2 Part #1: Header HTML
1. What is the purpose of the header tag?
It's basically the tag the hold everything in the header.
2. What is a Navigation Bar?
The navigation bar is basically a list of links you want the person navigating your website to go to.
3. What tag do we use to make a navigation bar? <      >
<ul>
<li> </li>
</ul> 
4.  <ul> Stands for ____Unordered List_________________
    <li> Stands for __List Items____________________

5. What does the <a> tag do?
It adds the link to the list item.

6. What would the line of HTML below do?

``` html
<a href="http://www.google.com">Google</a>
```
It would allow a user to click a list item which would transfer them to Google.com
##Project #2 Part #2: Style the Header with CSS

1. What advantages does the `<link>` tag have over the `<style>` tag?
The <link> allows you to include CSS from an external line. This is better because then there won't be a large amount of text in the HTML part, allowing for ogranization and it's far easier to understand.
2. What is normalize.css?
It's a CSS file that makes browsers " render all elements more consistently and in line with modern standards. (Makes page look the same no matter what browser used.)
3. Why do we need to add a padding property to the `<ul>` tag?
So all sides of the page will be aligned with each other.

4. What does the “inline” property do to a list of items?
When placed in { display:} it aligns the listed items in a row.
5. What do the following padding values do?
It puts space to individual sides of a specific image/ page
    padding: 25px 50px 75px 100px;

    * top padding is _25_px
    * right padding is _50_px
    * bottom padding is _75_px
    * left padding is _100_px

    padding: 20px;

    * top padding is _20_px
    * right padding is _20_px
    * bottom padding is _20_px
    * left padding is _20_px

6. What is the difference between padding and margin?
Padding deals with the space "inside" while margin deals with the space "outside".

7. What did border-radius do to the square border around the image?
It rounded the corners of the image's border.
##Project #2 Part #3: Responsive Design and Javascript

1. Why is responsive design becoming a more important aspect to consider when making a website compared to ten years ago?
Nowadays we have different types of devices we use to access the internet, meaning the screen sizes will be different from each other changing the size of the webpage. Before this most devices we used to access the internet were relatively the same screen size. With responsive design the webpage will stay nice looking on any device size.
2. Why is it important to center and narrow text on a webpage? (think visually)
So it would be both appealing to the eye and fit more narrow screened devices.
3. What does this line of HTML do to an object? `margin: 0 auto;`
It aligns post texts to the center. Putting a specific space to the left and right of the page.
4. How does using `max-width` instead of `width` improve the readability of any webpage?
Max-width makes elements smaller than the size put in but not larger, so the elements are more compatible with other device screen sizes.
5. The media query to the below  will not be activated unless… browser is a certain width.

    ``` css
@media (max-width: 500px) {
    body {
        background: red;
    }
}
    ```

6. What does each digit of this Hexidecimal Color Code represent? #E78

 E represents ... The red aspect of the color.

 7 represents ... The green aspect of the color.

 8 represents ... The blue aspect of the color.

7. What is the Hex Color Code for true purple?  #f0f

8. ______Javascript_________ is the programming language that allows websites to be interactive.

9. This tag allows us to add JavaScript into any webpage? <script>          </script>

10. What is an event?
Events can include clicking on a word, hovering over it, or highlighting it etc.
11. How does JavaScript use events?
It uses it to take action, this action is what you want the computer to do when the event is done.
**Activity** Copy all the text from your project so far into a new JS Bin workspace. From there you can change the site to an “About Me” website about yourself. To do this you will need to do the following:

- Manipulate much of the text and tags to represent yourself… Not Jeff Buckley<3

- Make sure that your "Like" button functions. If it does not work ask a teacher for guidance.



