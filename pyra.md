---
title: Pyraminx
permalink: /cubing/pyra/
layout: page
category1: Cubing
category1-url: /cubing/
category2: Pyraminx
category2-url: /cubing/pyra/
---
#### Jump to:
<a href="#lbl"><button type="button" class="btn btn-primary homepage-btn">Beginner's Method (LBL)</button></a>
<a href="#oka"><button type="button" class="btn btn-primary homepage-btn">Oka</button></a>
<a href="#adv"><button type="button" class="btn btn-primary homepage-btn">Advanced Methods</button></a>
<a href="#1flip"><button type="button" class="btn btn-primary homepage-btn">1-flip</button></a>
<a href="#wo"><button type="button" class="btn btn-primary homepage-btn">WO</button></a>
<a href="#nutella"><button type="button" class="btn btn-primary homepage-btn">Nutella</button></a>

Pyraminx
========

The Pyraminx is a very interesting puzzle because unlike most others, it requires the cuber to know several methods to be fast. 
It also demands a lot of intuition as well as the use of algorithms, similarly to the 3x3. This page will introduce you to the
most basic methods and then the more advanced methods.

<span id="lbl" />

Beginner Method: LBL (Layer By Layer)
-------------------------------------

Layer by layer is a very simple method to learn - it requires very few algorithms, and all but the last step is intuitive. While this won't
get you record-setting times, it's a good way to start out with the puzzle. 

Before you start, you'll need to understand some basic terms. The "tips" are the pieces that are like corners - these are trivial to solve.
"Centers" are the pieces directly below the tips. Lastly, the "edges" are the pieces between centers. Notation is also good to know. Pyraminx
notation is identical to 3x3 notation, except are no D or F moves - the Pyraminx is held so that U, B, L, and R moves are possible.

To start, you'll need to solve three centers. To do this, pick a side to start. Then, figure out what color the side is supposed to be my
looking at either the tips - the side will turn out to be the color that all three tips contain. Now, turn the centers so that all of the
centers on the side are the same color.

Next, you need to solve three edges. Place the face with the solved centers on the bottom. Now, find the edge that goes between the side
facing you and the bottom face, and bring it to the side facing you so that the bottom-color part of it is facing you using U moves. Now,
place the edge where it belongs. If you can't figure out how to do this intuitively, the algorithms are <span class="alg">R' L R L'</span>
if the piece is on the right, or <span class="alg">L R' L' R</span> if the piece is on the left. Repeat this procedure until the bottom
layer is completely solved.

Now, you have a last layer case. There are 5 cases, and although you only need 3, learning all 5 is easy and will make you much faster.

<br />

Flip left and right edges in place: <span class="alg">R' L R L' U L' U' L</span> *(you should regrip after the first 4 moves so that the
U and L tips are in your hands)*  
Cycle edges counter-clockwise: <span class="alg">R' U' R U' R' U' R</span>  
Cycle edges clockwise: <span class="alg">R' U R U R' U R</span> OR <span class="alg">L U L' U L U L'</span>  
Flip 2 edges and cycle clockwise:<span class="alg">L U R U' R' L'</span>  
Flip 2 edges and cycle counter-clockwise: <span class="alg">R' U' L' U L R</span>  

Tips can be solved at any time. After executing one algorithm, your Pyraminx should be solved!

<span id="oka" />

Intermediate Method: Oka
------------------------

Oka is a little more advanced than LBL, but has the potential to be much faster. The first step is to pick a center and solve one of
the surrounding edges. Then, find another edge that goes in the top. Insert it so that it is in the *wrong* place (in the place of the
last top edge) flipped so that its colors *do not* match up with those of the top center.

Now, solve the bottom centers without messing up your two edges. To do this, move the edge you haven't solved over a center, twist as
needed, and do this for every edge until your bottom centers are done. It's recommended that you solve the tips during this step.

The next step is to finish off the top. find the edge on the bottom that doesn't contain the bottom color (meaning it is the last top
edge). Put this edge where it needs to go using R or L', then do a U or U' (whichever is needed so that the solved edges are not destroyed)
and then undo your first move. You now have the top solved as well as the bottom centers.

The last step is called L3E (Last 3 Edges). There are three types of cases: 2 edges flipped in place, one edge the same color as the center,
or all edges the same color as the center. If 2 edges are flipped in place, use the algorithm from LBL. Otherwise, see below.

If you have one edge the same color as the centers, hold the Pyraminx so that the unsolved face is facing you and the same-color edge is at
the bottom of the face. Find which color is on the other side of that edge, and do a U or U' so that the top center is now that color. Then,
move that edge using R or L' (depending on the case) so that it matches up with the colors of the centers it is between. Lastly, undo both
moves. The algorithms are below, but it's best if you understand it intuitively. 

Algorithm: <span class="alg">U L' U' L</span> (if other side of center-color edge has the same color as the right face)  
<span class="alg">U' R U R'</span> (if other side of center-color edge has the same color as the left face)

The other case has two algorithms, one for moving all the edges on F clockwise, and one for counter-clockwise.  
Clockwise: <span class="alg">L R' L' R R U' R' U</span> (you should regrip between the two R turns - that's not a typo)
Counter-clockwise: <span class="alg">R' L R L' L' U L U'</span> (you should regrip between the two L turns - that's not a typo)

That's all! You can get pretty fast with Oka, so keep practicing until you average around 9. Then, you can begin learning 1-flip.

<span id="adv" />

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

<span id="1flip" />

### 1-flip

1-flip is a not a difficult method and the algorithms are fairly intuitive. For 1-flip, the first step is to solve two of the top edges correctly
and insert the last one flipped backwards. The rest of the Pyraminx is solved just like in the other advanced methods. In this method, the bracketed
letter is which center the flipped edge should be over when you execute the algorithm.

#### Algorithms:

One  
<span class="alg">R- {R}: R' U R L R' L'</span>  
<span class="alg">L+ {L}: L U' L' R' L R</span>  
<br />

Two (R, L)  
<span class="alg">- - {R}: R' U L'</span>
*Just solve the center that needs to be rotated inwards, and then move the flipped edge over and solve the other center*  
<span class="alg">+ + {L}: L U' R</span>
*Pretty much same thing as the last case*  
<span class="alg">+ - {L}: L R L R' U' R</span>  
<span class="alg">- + {R}: R' Dw R L' R' L R</span>
<br />

Three (R, L, B) *These all follow a similar pattern - solve the first center, then keep moving the unsolved edge in the top over the next center and solving that*  
<span class="alg">- - - {R}: R' U' B' U' L'</span>  
<span class="alg">+ + + {L}: L U B U R</span>  
<span class="alg">- - + {R}: R' U' B U' L'</span>  
<span class="alg">+ + - {L}: L U B' U R</span>  

<span id="wo" />

### WO

For WO, the entire top needs to be solved. The {} are just there for consistency of the notation - it doesn't matter how the top is rotated. This only covers good
cases - the cases not given are not worth learning because they are slow to execute.

#### Algorithms:

One  
<span class="alg">R- {}: R' L' R' L R</span>  
<span class="alg">L+ {}: L R L R' L'</span>  
<br />

Two (R, L)  
<span class="alg">- - {}: R' L R' L' R L'</span>  
<span class="alg">+ + {}: L R' L R L' R</span>  
<br />

Three (R, L, B)  
<span class="alg">- + - {}: R' Dw R Dw R'</span>  
<span class="alg">- + + {}: L U' R' Dw' R</span>  

<span id="nutella" />

### Nutella

For Nutella, one top edge should be solved correctly, while the other two should be in each other's places flipped so that the area across from the solved edge is
one solid color (meaning the edges are flipped the opposite of how they would be for Oka). Like for WO, only the good cases are given - the other ones are not good
for executing.

#### Algorithms:

One  
<span class="alg">R- {B}: R L R L'</span>  
<span class="alg">R+ {B}: L R' L' R'</span>  
<br />

Two (R, L)  

<span class="alg">+ + {R}: L U [U] R' L R</span>  
<span class="alg">- - {L}: R' U' [U'] L R' L'</span>  
<br />
Three (R, L, B)  

<span class="alg">- - - {B}: R' L' Dw' R'</span>  
<span class="alg">+ + + {B}: R Dw L R</span>  
<span class="alg">+ - + {B}: L R L U B</span>  
<span class="alg">+ - - {B}: R' L' R' U' B'</span>  
