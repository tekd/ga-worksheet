####Name: Samantha Nunez
####ScriptEd
####Topic: HTML, CSS, and JS

**Directions:** Project #2 on dash.ga.co asks you to create a blog for Jeff. Although you are not creating what someone can consider a blog, you are creating an intricate webpage using HTML, CSS and some JavaScript. Three skills that you will master in your time with ScriptEd. Log into your General Assembly account on dash.ga.co walk through the second project while answering the questions below. After completing this project you will be asked to convert this page into a four page website about your self.


##Project #2 Part #1: Header HTML
1. What is the purpose of the header tag? To put headers inside of. It's for headers.

2. What is a Navigation Bar? A navigation bar is like a "portal" to a list of links, to help users of the website access           specific information easier.

3. What tag do we use to make a navigation bar? you use a { } or use <ul> and <li>.

4.  <ul> Stands for __unordered list__
    <li> Stands for ___list___

5. What does the <a> tag do? it explicitly sets a value, or values for a link since links don't inherit values from their parent element.

6. What would the line of HTML below do?  It would create a link that takes you to google. You would see the word google as a link, but when you click it it takes you to http://www.google.com

``` html
<a href="http://www.google.com">Google</a>
```

##Project #2 Part #2: Style the Header with CSS

1. What advantages does the `<link>` tag have over the `<style>` tag? Instead of putting your CSS directly in the html file and taking up space-like the <style> tag, the <link> tag, is a connection from your html to a css, that has all he properties and attributes you want. It's advantageous because it makes your html shorter and easier to read-something especially convenient when you have dozens of style attributes.

2. What is normalize.css? it's a "thing" that basically renders the elements in your page consistent across all browsers and wherever your page is being seen, so it doesn't look messy.

3. Why do we need to add a padding property to the `<ul>` tag? to clear an area aroud nd the/a element and center the elements better.

4. What does the “inline” property do to a list of items? it makes them appear next to each other in the same line by default.

5. What do the following padding values do?

    padding: 25px 50px 75px 100px;

    * top padding is 25px
    * right padding is 50px
    * bottom padding is 75px
    * left padding is 100px

    padding: 20px;

    * top padding is 20px
    * right padding is 20px
    * bottom padding is 20px
    * left padding is 20px

6. What is the difference between padding and margin? Padding creates space on the inside of an element while margin creates space on the outside.

7. What did border-radius do to the square border around the image? It rounded off the corners.

##Project #2 Part #3: Responsive Design and Javascript

1. Why is responsive design becoming a more important aspect to consider when making a website compared to ten years ago? Responsive design is becoming more important because people today are lazy and impatient, and like things to be pretty. The less clicks it takes for me to get where I want to go, the better. It's easier and faster. Moreover, today there are hundreds of thousands of websites, and I guess the prettiest one wins, or something. You have to make your website stand out both visually and in terms of how efficient it is.

2. Why is it important to center and narrow text on a webpage? (think visually) If you center and narrow it, you only have to scroll down, but if the text just takes the whole width of the page, suddenly you have to scroll left, right, up and down. That's annoying, no one wants that.

3. What does this line of HTML do to an object? `margin: 0 auto;` It makes it so that theres 0 margin at the top and bottom, and auto margin at the left and right. This centers the text.

4. How does using `max-width` instead of `width` improve the readability of any webpage? max-width makes it so that the article elements cant be any bigger than whatever number you put in. it improves readability across different devices, for example, if your using a phone instead of a 15.6 inch laptop. It also keeps the page structured when you zoom in/out.

5. The media query to the below  will not be activated unless… you make the page narrower than 500px.

    ``` css
@media (max-width: 500px) {
    body {
        background: red;
    }
}
    ```

6. What does each digit of this Hexidecimal Color Code represent? #E78

 E represents ... the amount of redness

 7 represents ... the amount of greeness

 8 represents ... the amount of blueness

7. What is the Hex Color Code for true purple?  #990099

8. JAVASCRIPT is the programming language that allows websites to be interactive.

9. This tag allows us to add JavaScript into any webpage? <script>

10. What is an event? something that happens everytime you move your mouse, click something, mouse over things, press a key or scroll. by default they go unnotticed.

11. How does JavaScript use events?java can listen for specific events and sort of create reactions to them.

**Activity** Copy all the text from your project so far into a new JS Bin workspace. From there you can change the site to an “About Me” website about yourself. To do this you will need to do the following:

- Manipulate much of the text and tags to represent yourself… Not Jeff

- Make sure that your "Like" button functions. If it does not work ask a teacher for guidance.



