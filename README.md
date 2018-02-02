Create a repeating pattern of shapes using a `while` loop
=============================================
In this assignment you will write a program that uses at least one `while` loop to make many shapes on the screen. You may find 191-225 of the PythonProcessing.pptx PowerPoint slides and the [`while` Loops worksheet](https://github.com/APCSPrinciples/LoopsWorksheet/blob/master/README.md) helpful in completing this assignment.   

Start a new processing program and save it with a meaningful name like `Repeating`. Remember, the name of your program should start with a letter of the alphabet and should not contain spaces. You could make a pattern of five ellipses with the following code:
```python
noFill()
smooth()
ellipse(0,50,50,50)
ellipse(25,50,50,50)
ellipse(50,50,50,50)
ellipse(75,50,50,50)
ellipse(100,50,50,50)
```
 
What if you wanted a pattern of 100 ellipses? Copying and pasting 100 times is tedious. A better way would be to use a `while` loop that repeats 100 times. Look at the example program again. Notice that only the x position of each ellipse is changing. We could create a variable to hold that x position, and use a while loop to make the same five circles:
```python
noFill()
smooth()
x = 0
while x < 101:
   ellipse(x,50,50,50)
   x = x + 25
```
Your program can use as many different shapes as you like, but you need to use at least one `while` loop to make at least one of the shapes repeat. To make the pattern interesting, you should experiment with changing the x & y positions, size, color, opacity, `strokeWeight` and `fill` of your shapes. Have fun and be creative, your pattern doesn't have to look like any other. Don't hesitate to ask for help if your aren't sure how something is suppose to work.   

Samples of Student Work
-----------------------
[Kevin](https://trinket.io/embed/python/25b0117929?outputOnly=true&runOption=run&start=result)   
[Raineh](https://trinket.io/embed/python/5ca39edf7a?outputOnly=true&runOption=run&start=result)   
[Ryan](https://trinket.io/embed/python/5e6e58c50b?outputOnly=true&runOption=run&start=result)   
[Kelly](https://trinket.io/embed/python/04fcd53f85?outputOnly=true&runOption=run&start=result)   
[Wesley](https://trinket.io/embed/python/d4490b324e?outputOnly=true&runOption=run&start=result)   
[Annie](https://trinket.io/embed/python/3b18be1b51?outputOnly=true&runOption=run&start=result)   
[Jacob](https://trinket.io/embed/python/94a26abfda?outputOnly=true&runOption=run&start=result)   
[Nghi](https://trinket.io/embed/python/5fcf4b5e85?outputOnly=true&runOption=run&start=result)   
[Connie](https://trinket.io/embed/python/731e8923e7?outputOnly=true&runOption=run&start=result)   
[Rebecca](https://trinket.io/embed/python/b8bbd7c33f?outputOnly=true&runOption=run&start=result)   
[Alyssa](https://trinket.io/embed/python/0d664817ee?outputOnly=true&runOption=run&start=result)   
