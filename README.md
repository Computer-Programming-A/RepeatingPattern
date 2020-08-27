Create a repeating pattern of shapes using a `while` loop
=============================================
In this assignment you will write a program that uses at least one `while` loop to make many shapes on the screen. You may find slides 84 - 120 in the [slide presentation](https://docs.google.com/presentation/d/1fm_Di0qR4HpRWTf8tJtcW3u5by3OrilfXIPZ517K1js/edit?usp=sharing) and the [`while` loops worksheet](https://github.com/Computer-Programming-A/LoopsWorksheet#while-loops-worksheet) helpful.   

Start a new [Game Lab program](https://code.org/educate/gamelab) and save it with a meaningful name like `RepeatingPattern`. You could make a pattern of five circles with the following code:
```javascript
  noFill();
  ellipse(100, 50, 50, 50);
  ellipse(125, 50, 50, 50);
  ellipse(150, 50, 50, 50);
  ellipse(175, 50, 50, 50);
  ellipse(200, 50, 50, 50);
```
 
What if you wanted a pattern of 100 circles? Copying and pasting 100 times is tedious. A better way would be to use a `while` loop that repeats 100 times. Look at the example program again. Notice that only the x position of each circle is changing. We could create a variable to hold that x position, and use a while loop to make the same five circles:
```javascript

  noFill();
  var x = 100;
  while (x < 201) {
    ellipse(x,50,50,50);
    x = x + 25;
  }

```
Your program can use as many different shapes as you like, but you need to use at least one `while` loop to make at least one of the shapes repeat. To make the pattern interesting, you should experiment with changing the x & y positions, size, color, `strokeWeight` and `fill` of your shapes. Have fun and be creative, your pattern doesn't have to look like any other. Don't hesitate to ask for help if your aren't sure how something is suppose to work. Submit the link to your finished program on google classroom.   

Samples of Student Work
-----------------------
[Duan](https://editor.p5js.org/Duan25/present/y6rLrOTA)   
[Bernice](https://editor.p5js.org/undefined/present/infDsJlI)   
[Nikhita](https://editor.p5js.org/Bluesnow/present/9ePh5C8r)   
[Curtis](https://editor.p5js.org/culee/present/IWU9Vqrb)   
[Ryan](https://editor.p5js.org/rylee15/present/HlbXoj_E)   
[Michaela](https://editor.p5js.org/michaela29/present/3IJbhQkJ)     
[Raineh](https://trinket.io/embed/python/5ca39edf7a?outputOnly=true&runOption=run&start=result)   
[Ryan](https://trinket.io/embed/python/5e6e58c50b?outputOnly=true&runOption=run&start=result)    
[Jacob](https://trinket.io/embed/python/94a26abfda?outputOnly=true&runOption=run&start=result)   
[Nghi](https://trinket.io/embed/python/5fcf4b5e85?outputOnly=true&runOption=run&start=result)   
[Connie](https://trinket.io/embed/python/731e8923e7?outputOnly=true&runOption=run&start=result)   

