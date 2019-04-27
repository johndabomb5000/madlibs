## Learning Content

### Learning HTML

* [Getting To Know HTML](html/1.md)
* [HTML Syntax & Document Structure](html/2.md)
* [HTML Text Elements](html/3.md)
* [HTML Links](html/4.md)
* [HTML Inputs](html/5.md)

### Learning CSS

* [CSS Fundamentals](css/1.md)
* [CSS Syntax and Formats](css/2.md)
* [CSS Selectors](css/3.md)
* [CSS Authority and Inheritance](css/4.md)
* [CSS Color](css/5.md)
* [CSS Fonts](css/6.md)

### Learning JavaScript

* [Intro to JavaScript](js/1.md)
* [JavaScript Variables](js/2.md)
* [JavaScript Functions](js/3.md)
* [JavaScript and HTML](js/4.md)
* [Calling JavaScript From HTML](js/5.md)

## Activity: Flatiron School MadLibs

This is an exercise that combines basic HTML, CSS, and JavaScript to make a simple web application.

### Instructions

* Make an HTML page that includes:
    * A title
    * A heading
    * An area for entering each of the words in the MadLib (hint: use `<input>` tags)
    * A button for submitting the words your user entered
    * An area for your MadLibs result (hint: use `<span>` tags with IDs for all of the words you'll substitute).
* Make a CSS page to style your HTML page. Some ideas:
    * Change the fonts and other typographic properties
    * Make the inputs and labels display on their own lines
    * Set the maximum width of long lines to keep them from running across the whole screen
    * Change the background color, text color, and border of the button
    * Change the style of cursor when hovering over the button
    * Modify the padding and margin of different elements to give everything some "breathing room" (remember, this works with the `<body>` element as well!
* Make a JavaScript file that *contains a function*. Inside of this function:
    * Store the values the user enters in the input fields in the HTML page in variables
    * Set the text of the relevant `<span>` elements in the HTML page equal to what you stored in the relevant variable
* Call the function in your JavaScript file *from the HTML page* when the button is clicked

### Demo

Check out the [demo](https://madlibs-baolyylzvg.now.sh) to see one way to do this!

### Example Mad Lib

Here is an example MadLib that you can use, but feel free to get creative!

```
Dear School Nurse:

[First name] [Last name] will not be attending school today. He/she has come down with a case of [illness] and has horrible [Plural names] and a/an [Adjective] fever. We have made an appointment with the [Adjective] Dr. [Silly word], who studied for many years in [Place] and has [Number] degrees in pediatrics. He will send you all the information you need. Thank you! 

Sincerely,
Mrs. Adjective.
```

### Deployment

You can deploy your madlibs to the internet and share it with your friends using [now.sh](https://zeit.co/now)!
