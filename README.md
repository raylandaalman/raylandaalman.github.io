# Generation of Calculators

## What Is It? ##

This is a small single page app that shows different calculators and my experiences with them.

## What Tools are Used? ##

The app was made using vanilla HTML, CSS, and JavaScript.

## Why Use Vanilla Tools ##

The purpose of using vanilla tools, is to learn how to make a single page app without using a framework. All text that appears for the calculator descriptions are using "innerHTML" to add the connent. This is normally not recommended for any user input, as it is HTML code being entered and not simply text. Since this website does not have user input, "innerHTML" is acceptable here.

While I have used frameworks, like React, to make a from end, I wanted to hand-type my own single page app and state management to practice DOM manipulation.

The calculator brand, for example, does not change if switching from a TI to TI calculaor, or an HP to HP calculator. This is done by an object managing the state of what brand is showing. This way, only the content that needs to change will be.
