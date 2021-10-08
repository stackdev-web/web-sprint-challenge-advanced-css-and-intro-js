# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS and introductory JavaScript concepts. During this Sprint, you studied responsive web design, variable declaration, conditionals, loops, functions, arrays, and objects. In your challenge this week, you will demonstrate proficiency by creating a website of influential artists with data from an object.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in Responsive Design, and JavaScript Basics.


## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with.

### Commits
Commit your code regularly and meaningfully. 
## Interview Questions
### (please edit this file and write your answer below each question.)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?
    Accessibility is what allows people with differing considerations to all view a web page in the same way. For example, using sematic tags allows a machine to help someone with a special mouse or other instrument navigate the page, and using the 'alt' within tags allows a screen reader to explain to the blind what is on a page.

2. Talk about 3 different things you can do to ensure your website is accessible. 
    a) make sure to add 'alt' tags to every image on the site
    b) use semantic tags like --nav-- --header-- --table-- 
    c) use high contrast colors and even, using #494949 instead of solid black for text to make it easier for even non-accessibility users (puts less strain on their eyes).

3. How would you explain the concept of a variable to someone new to programming?
    A variable holds values for us temporarily (or longer) so that we can manipulate data. An example of using a variable would be if we wanted to calculate miles into kilometers. We would have different values to calculate each time, so a variable for miles and one allows us to plug in a new number of miles each time we need to make a calculation.

4. What is the purpose of using functions in code?
    Functions are ways of using a 'shortcut' to make common calculations or programming needs. For example, in the example of calculating miles to kilometers, we wouldn't want to have to re-type the calculation code every place where we needed to have this functionality. Instead we create one function, and then reference this function each time we want to complete the complication. In this way we keep our code DRY and are able to reuse common code throughout a program.

5. How do you access a key inside of an object inside of an array?
    The easiest way, for non-messy data, is to use dot notation and the element's index position. So we have the following array object:
     const array = [{
        key1: 10,
        key2: 'Fred',
        key3: 'Flinstone'
    }];

    To access the key here we first reference the array, then the index of the object item we want, then the key, as in:
 
 console.log(array[0].key1)

    This returns the value of 10.  If we only want the name of the keys, then we can try:
    
console.log(Object.keys(object1)); 

    This returns a list of all the keys within the object 'object' inside the 'array' array.
    

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

<!-- 1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
NOTE: tests will run in the JavaScript portion of this challenge only.
5. cd into your repo
6. open the terminal in your vs code and type `npm install` -->
<!-- 7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push. -->


### Testing & Debugging

<!-- Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this") -->

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Ensure your website is responsive at 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.



## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

🦄 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-2-Study-Guide-16f656025c8744458addb068e6348101)





