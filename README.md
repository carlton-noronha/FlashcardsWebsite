# FlashcardsWebsite

### What are flashcards ?
Flashcards are cards bearing information on both sides of the card and is generally used to help with memorization of the specified information. 
This information is of the form **Term-Description** where the Term is generally the information that is known to the user and the Description is 
what needs to be memorized. The information to be memorized can be words in a foreign language or the captitals of countries and so on.

### Example
Assume we want to memorize the capitals of countries.

The front side of the card will have the information most likely know to the user.

![Front side of card](https://github.com/carlton-noronha/FlashcardsWebsite/tree/master/Flashcards/task/src/images/Front.jpg)

The back side of the card will have the information to be memorized

![Back side of card](https://github.com/carlton-noronha/FlashcardsWebsite/tree/master/Flashcards/task/src/images/Back.jpg)


### Technical

The website is written in HTML with designing done using CSS.

In CSS the concept of **Flexbox** was used to increase the flexibility of items. There are total of 9 cards. Each card is created with 4 `<div>` tags as follows:

```
<div class="container">
  <div class="card">
    <div class="front">FRONT</div>
    <div class="back">BACK</div>
  </div>
</div>
```
Using CSS properties like `transform`, `transition`, `transform-style`, `backface-visibility` and `z-index` we can achieve the Rotation effect to view the back of the card.

### Output
[Visit the website](http://carltonnoronha.byethost12.com/webprojects/flashcards.html "Flashvcards,html")

or

![Output Screenshot](https://github.com/carlton-noronha/FlashcardsWebsite/tree/master/Flashcards/task/src/images/Website.jpg)
