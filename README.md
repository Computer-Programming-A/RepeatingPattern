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
[Cameron](https://studio.code.org/projects/gamelab/QRR0yiOip3m85HjBjcpB2DZgyFUUsAvCKu1YWYOG2Ps)   
[Tommy](https://studio.code.org/projects/gamelab/FbH5iiGDwHqTM_223TfN17HYl3RAcVpKOS2eLIgGheo)   
[Rachel](https://studio.code.org/projects/gamelab/v_DthAkm__veoEY_aB0rWL1Hh10KfaIkQ5CQKiuM0oQ)   
[Tuan](https://studio.code.org/projects/gamelab/znaffrSBs9yR43o1KeaTSEa6KIjMRc3CLNwDaOKxJg8)   
[Sally](https://studio.code.org/projects/gamelab/Lpd1x7fjTpLfvZ0thtbiNewiws8Xys6CUKrM1aFUSZ8)   
[Stephanie](https://studio.code.org/projects/gamelab/bg2yydL853YfM72kHzF0d-4Y1nVa4PQto3zDDzC4oTQ)   
[Eva](https://studio.code.org/projects/gamelab/WlNR8khgfFm7qdPOC1IA-ujeHZdAuiRrP6STJau_h3s)   
[Juan](https://studio.code.org/projects/gamelab/U_skeWQ9cnwbUI0h8kUCwkiDaIszy4y3rL8GLAkm_lA)   
[Benjamin](https://studio.code.org/projects/gamelab/x6xxlW5C1vmDxB5pzwWhO_rS_75YqAKa5gAe2GjRq5A)   
[Tobias](https://studio.code.org/projects/gamelab/UJX8xrJ8MbSK8XRGhtkUtdVnh4939VErQfcw4E6gMek)   
[Maya](https://studio.code.org/projects/gamelab/yBEnfh05m3S79yqdtQ_rBOEO3qUft-_q89ncRNC0qxU)   
[Justin](https://studio.code.org/projects/gamelab/JbCJU54byiDHPCXycH-XqRLfXtYZMWpMU8CDdWhJyAw)   
[Frank](https://studio.code.org/projects/gamelab/Pm-lgxh8rF-wm98I_X0v13ozRDNJU6QTE2eytgFRPiA)   
[Gloria](https://studio.code.org/projects/gamelab/azRw8lCJcLNWA1QtDNSGvZ4fwFqRM6qtk6hGxqRnazs)   
[Naomi](https://studio.code.org/projects/gamelab/jAISSaxZHRc1Xnz4qkpFdgHlEMWg5mN_SuaaazjzXX8)   
[Damian](https://studio.code.org/projects/gamelab/8Uk5a36WRv_j_0IF81aRkA8VZvHenGmZ-VANxCuri2Y)   
[Niko](https://studio.code.org/projects/gamelab/VUMYK3uIv98Y2Wr2rEfbJQxPrbzsXaxnWWACCgB4u6U)   
[Kami](https://studio.code.org/projects/gamelab/SKONJr_u5jAu0IdPQW23tzahaNYWAPr7TeHco8dxIQc)   
[Tyler](https://studio.code.org/projects/gamelab/m0M6qquNvROhD-e_odXbPvQaAOPsIZIZelgZXSB4xSs)   
[Danil](https://studio.code.org/projects/gamelab/ic9SEKE-DEzkXUw20MVnHOHcT6X66sP6gUebD3cXe40)   
[Marco](https://studio.code.org/projects/gamelab/KF1eD8X0XQAPN7dSe58o61e9Mj9VuSje0_7ZcyYJrAM)   
[Tyler](https://studio.code.org/projects/gamelab/m0M6qquNvROhD-e_odXbPvQaAOPsIZIZelgZXSB4xSs)   
[Liam](https://studio.code.org/projects/gamelab/yW_IsC4wCYc3QR6aYfBoxlVMFtU7Hx8qAUFyQGBITko)   
  

