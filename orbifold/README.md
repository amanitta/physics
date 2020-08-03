# Orbifold
Here we show how defining a certain simmetry on the torus can make it look almost like a sphere, except for the presence of 4 'special points'.</br>

## A simpler example
Before talking about the torus, let's consider a circle: this is a 1-dimensional manifold in which points are identified modulo the length of the circumference
itself, meaning

<a href="https://www.codecogs.com/eqnedit.php?latex=x&space;\sim&space;x&space;&plus;&space;2&space;\pi&space;R&space;n" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;\sim&space;x&space;&plus;&space;2&space;\pi&space;R&space;n" title="x \sim x + 2 \pi R n" /></a></br>

What happens if, on the circle, we also ask the equivalence

<a href="https://www.codecogs.com/eqnedit.php?latex=x&space;\sim&space;-x" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;\sim&space;-x" title="x \sim -x" /></a>

to hold?<br>
What we obtain with this is that on the line for example

<a href="https://www.codecogs.com/eqnedit.php?latex=-1&space;\sim&space;1,&space;-1&space;\sim&space;-1&space;&plus;&space;2&space;\pi&space;R&space;\longrightarrow&space;1&space;\sim&space;-1&space;&plus;&space;2&space;\pi&space;R" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-1&space;\sim&space;1,&space;-1&space;\sim&space;-1&space;&plus;&space;2&space;\pi&space;R&space;\longrightarrow&space;1&space;\sim&space;-1&space;&plus;&space;2&space;\pi&space;R" title="-1 \sim 1, -1 \sim -1 + 2 \pi R \longrightarrow 1 \sim -1 + 2 \pi R" /></a>

Only two points are left invariant by this identification:

<a href="https://www.codecogs.com/eqnedit.php?latex=0&space;\text{&space;and&space;}&space;\pi&space;R" target="_blank"><img src="https://latex.codecogs.com/gif.latex?0&space;\text{&space;and&space;}&space;\pi&space;R" title="0 \text{ and } \pi R" /></a>

which are said to be the **fixed points**.</br>
What we constructed in this way is written in mathematics as the _quotient_ between the circumference and the discrete simmetry identifying opposite points, which is represented by the _cyclic group of order two_:

<a href="https://www.codecogs.com/eqnedit.php?latex={S^1}/{\mathbb{Z}_2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{S^1}/{\mathbb{Z}_2}" title="{S^1}/{\mathbb{Z}_2}" /></a>

## The case of the torus
A torus is a compact two-dimensional manifold characterized by periodicity in both its coordinates, i.e.</br>

<a href="https://www.codecogs.com/eqnedit.php?latex=x&space;\sim&space;x&space;&plus;&space;2&space;\pi&space;R_1&space;m" target="_blank"><img src="https://latex.codecogs.com/gif.latex?x&space;\sim&space;x&space;&plus;&space;2&space;\pi&space;R_1&space;m" title="x \sim x + 2 \pi R_1 m" /></a></br>
<a href="https://www.codecogs.com/eqnedit.php?latex=y&space;\sim&space;y&space;&plus;&space;2&space;\pi&space;R_2&space;n" target="_blank"><img src="https://latex.codecogs.com/gif.latex?y&space;\sim&space;y&space;&plus;&space;2&space;\pi&space;R_2&space;n" title="y \sim y + 2 \pi R_2 n" /></a>

The effect of taking the quotient with respect to the cyclic group of order two is shown in the following animation

<p align="center">
<img src="https://github.com/amanitta/physics/blob/master/orbifold/torusToPillow.gif"/>
</p>

This is the orbifold

<a href="https://www.codecogs.com/eqnedit.php?latex={T^2}/{\mathbb{Z}_2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{T^2}/{\mathbb{Z}_2}" title="{T^2}/{\mathbb{Z}_2}" /></a>

What happens is that the initial donut-shaped object that we have gets transformed in some sort of pillow, with four points that clearly have a special role: these are the fixed points for this transformation, and in the image are located at the corners of the pillow. The presence of such points is what makes this space
qualitatively different from a sphere, though through a mathematical process called _blowup_ the two could be basically made equivalent to each other.

## Short glance into String Theory
One of the most well-known predictions of String Theory is the presence of extra spatial dimensions in which these tiny objects should be allowed to vibrate.</br>
In order to explain the reason why such dimensions have not been detected is saying that they are compactified. To get the idea of what this means, a very common
example is that of considering a very long and thin pipe. Someone looking from the distance would certainly think of that object as being 1-dimensional, having only length, but no real thickness, like a hair. A bug moving on the pipe, on the other end, would experience the presence of the second dimension, which was not manifest to the other observer for it was compactified with a radius too small to be perceived.</br>
In almost the same fashion, (most) string theorists believe the presence of multiple other spatial dimensions has never been detected in experiments because
their radii of compactification are way smaller than what current technology allows to investigate.</br>
With that being said, let's go back to the torus: this is indeed a quite simple, yet instructive example to start understanding how compactifications works.</br>
Indeed, it is quite difficult to perform calculations considering compact spaces other than the torus. Anyway we saw how the orbifold obtained taking the quotient
with respect to the cyclic group is almost the same as a sphere. Considering this particular space is though also very interesting.</br>
The focus here is to show how strings defined on the torus transform under the effect of the quotient operation.

### 1.
A general closed string just stays the same

<p align="center">
<img src="https://github.com/amanitta/physics/blob/master/orbifold/closedString.gif"/>
</p>

### 2.
General open string remain open...
<p align="center">
<img src="https://github.com/amanitta/physics/blob/master/orbifold/openUnbal.gif"/>
</p>
... we can see though that one of the string gets really near to closing, could there be a case in which an open string tranform into a closed one?

### 3.
An open string with its center of mass located on one of the fixed points will close under the effect of the symmetry relation
<p align="center">
<img src="https://github.com/amanitta/physics/blob/master/orbifold/openBal.gif"/>
</p>