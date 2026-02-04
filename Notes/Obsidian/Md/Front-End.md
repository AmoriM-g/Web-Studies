---
Date: 19-01-2026
tags:
  - Front-End
  - Full-Stack
---
___
- Every web site can be split into two parts: the frontend and the backend.
- The frontend is all the visual stuff you see on the web page: the images, the buttons, the text, etc
- The backend is what saves and manages your data, for example your amazon order history.

- Some of the technologies used in the frontend of a web application are:

## **HTML**

- Used to add content to a web page.
- [[HTML.canvas]]

## **CSS**

- Cascading Style Sheets.
- Used to style a web page.
- Let's you adjust colors, sizes, spacing, etc. 

- Similarly to JavaScript, CSS has some notable problems.
- Can't organize code into different files.
- Missing useful features.
- For that, we also use a bundler and a transpiler for CSS.

- There's a special name for this called a CSS **Preprocessor**.
- Preprocessor = bundler + transpiler.
- The most popular one is called **Sass**.

### **Sass**

- Let's us organize our CSS into different files.
- Let's us write enhanced CSS (CSS with more features).

### **Bootstrap**

- Once we had CSS Preprocessors, developers start to create **CSS Frameworks**, the most popular one being **Bootstrap**.
- CSS Frameworks are basically a whole bunch of CSS code that somebody else wrote, and it helps us solve common problems. Using a framework like Bootstrap saves us a lot of time.

## **JavaScript**

- Makes the web page interactive.

- The most important feature of JavaScript is the Document Object Model (DOM)
- Allows JavaScript to change the web page.

### **JavaScript Framework**

- However, using DOM directly is really repetitive, and hard to manage. That's why we usually use a JavaScript Framework.
- They give us a much nicer way to create our web page, and they take care of updating the page for us.
- Because of this, DOM is not used directly anymore.

The most popular ones are:

-  ReactJS
-  Angular
-  VueJS

- JavaScript as a language is missing a lot of features that other programming languages have. One of these features is being able to split up our code into different files, and to organize our code.
- To solve this we have to use something called a **bundler**. The most popular one is called **Webpack**.

### **Webpack**

- Let's us split up our JavaScript code into many different files. Once ready to be implemented into our web site, Webpack will combine, or *bundle*, all of these files into one JavaScript file that we can put in our web site.

Another tool that we use is called a **transpiler**. The most popular one is called **Typescript**.

### **Typescript**

- Adds extra features to JavaScript, letting us write an enhanced version of JavaScript, and then once we are done, it will transform the enhanced JavaScript back into normal JavaScript.
- This is because browsers like google chrome can only understand normal JavaScript.

---
## **References**

[[Front-End.canvas]]
[[HTML.canvas]]
