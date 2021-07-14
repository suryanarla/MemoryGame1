# Memory Game Project

## Table of Contents

-   [Instructions](#instructions)
-   [Contributing](#contributing)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

_____________________________________________________________

## For implementing Memory Game Project,

# I did the following steps 

1.  Got all the cards in to the app.js file by using  '**Array.prototype.slice.call()**' and stored in an array named cardList.

2.  Created a function named **initGame**, it works when the page loaded. And implemented shuffle function in it.

3.  Added a 'click' eventlistener to each array element. when the event triggered, the **viewCard** function invokes. In viewCard function I added classlists accordingly. The timer also starts when clicking on any of the card for the first time.

4.  stored the card in an array after clicking on it. If the card value equals to 2 then increase the count of moves. And also checks for equality. If the two cards equl then applied few styles accordingly and empty the array (*opened[]*). Similarly if unmatched then applied few styles accordingly again empty the array.

5.  If the cards matched then assigned a class named '*match*'. and counts number of elements which are having the classname of match. If the count is 16 then it reaches to **endGame** function.

6.  The endGame function includes **clearInterval** function. It pauses the time. and also contain pop up window.
    in this function, I added a class called show. By default the model block is in hidden state.

7.  The **timer** I initialized minutes as 0 and seconds as 0. It repeats based on setInterval function. with 1 second of time interval.

8.  The Rating, for rating, I added additional styles with the selector of ' *.star* '. I diminished the star count based on number of moves.

    - If number of moves &lt;= 12 the the star count is 3
    - If number of moves  >12  && moves &lt;=16 the the star count is 2
    - Otherwise the count is 1.
9.  After completed the functionality, I focussed on **Responsive design**. Added meta tag with responsive design attributes. And then wrote few styles for various devices widths using *media queries*.

10.  Checked out my web site for accessibility and performance with **LightHouse** tool. And modified few styles according to that.  
