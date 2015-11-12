---
title: Pyraminx
permalink: /cubing/pyra/
layout: page
category1: Cubing
category1-url: /cubing/
category2: Pyraminx
category2-url: /cubing/pyra/
---

Pyraminx
========

The Pyraminx is a very interesting puzzle because unlike most others, it requires the cuber to know several methods to be fast. 
It also demands a lot of intuition as well as the use of algorithms, similarly to the 3x3. This page will introduce you to the
most basic methods and then the more advanced methods.

Beginner Method: LBL (Layer By Layer)
-------------------------------------

This guide will be written in the future.

Intermediate Method: Oka
------------------------

This guide will be written in the future.

Advanced Methods: 1-flip, WO, and Nutella
-----------------------------------------

Each of these advanced methods have three steps: first, solve the top into a specific case (like the first step in Oka, only the
case you put it in varies by method). Then, you use an algorithm to solve all of the remaining centers and the top. Lastly, you end up with
last layer just like in Oka and solve the last three edges as you would in the Oka method.

JP Bulman recommends that you start learning 1-flip when you're sub-10, WO when you are sub-8-sub-7.5, and Nutella when you are sub-7. 
For solving the tips, he solves two at the beginning solve (the top tip and the tip of the center you first move) and then two at the
end of the solve.

The notation used for these algorithms requires a little bit of explanation. The + or - indicate whether a center needs to move clockwise
or counter-clockwise. The centers are in the order R, L, B (so + - - means right center clockwise, left center counter-clockwise, and back
center counter-clockwise). When there are only two centers, they are in the order R, L, and when there is only one, the case indicates
which center needs to be rotated. The letter in {curly brackets} is the letter of the center that should have the "different" edge over it
(this will make sense once you start learning one of the methods). Cases are ordered by how many centers need to be rotated. While I invented
this notation, these algorithms are all taken from Drew Brads (XTownCuber on Youtube).

### 1-flip

1-flip is a not a difficult method and the algorithms are fairly intuitive. For 1-flip, the first step is to solve two of the top edges correctly
and insert the last one flipped backwards. The rest of the Pyraminx is solved just like in the other advanced methods. In this method, the bracketed
letter is which center the flipped edge should be over when you execute the algorithm.

#### Algorithms:

One  
<span class="alg">
R- {R}: R' U R L R' L'  
L+ {L}: L U' L' R' L R  
</span>
<br />
Two (R, L)  
<span class="alg">
- - {R}: R' U L'
</span>
*Just solve the center that needs to be rotated inwards, and then move the flipped edge over and solve the other center*  
<span class="alg">
+ + {L}: L U' R
</span>
*Pretty much same thing as the last case*  
<span class="alg">
+ - {L}: L R L R' U' R  
- + {R}: R' Dw R L' R' L R  
</span>
<br />
Three (R, L, B) *These all follow a similar pattern - solve the first center, then keep moving the unsolved edge in the top over the next center and solving that*  
<span class="alg">
- - - {R}: R' U' B' U' L'  
+ + + {L}: L U B U R  
- - + {R}: R' U' B U' L'  
+ + - {L}: L U B' U R
</span>

### WO

For WO, the entire top needs to be solved. The {} are just there for consistency of the notation - it doesn't matter how the top is rotated. This only covers good
cases - the cases not given are not worth learning because they are slow to execute.

#### Algorithms:

One  
<span class="alg">
R- {}: R' L' R' L R  
L+ {}: L R L R' L'  
</span>
<br />
Two (R, L)  
<span class="alg">
- - {}: R' L R' L' R L'  
+ + {}: L R' L R L' R  
</span>
<br />
Three (R, L, B)  
<span class="alg">
- + - {}: R' Dw R Dw R'  
- + + {}: L U' R' Dw' R  
</span>

### Nutella

For Nutella, one top edge should be solved correctly, while the other two should be in each other's places flipped so that the area across from the solved edge is
one solid color (meaning the edges are flipped the opposite of how they would be for Oka). Like for WO, only the good cases are given - the other ones are not good
for executing.

#### Algorithms:

One  
<span class="alg">
R- {B}: R L R L'  
R+ {B}: L R' L' R'  
<br />
</span>
Two (R, L)  
<span class="alg">
+ + {R}: L U [U] R' L R  
- - {L}: R' U' [U'] L R' L'  
</span>
<br />
Three (R, L, B)  
<span class="alg">
- - - {B}: R' L' Dw' R'  
+ + + {B}: R Dw L R  
+ - + {B}: L R L U B  
+ - - {B}: R' L' R' U' B'  
</span>
