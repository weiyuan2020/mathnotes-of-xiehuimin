aT aT 0S ee . i Af TI:
LT EL HY - = a :
oy Ww L. - %
iw
=" . Ew
a A A Lia 3
SNTEAMATIONAL JEAIES 13 sire sore evi :
EEE WAR AE Se
Re i - ls my To a 1
: BE - LL L 1
Wi Li 2 k nl -_

-.
bE
hm y b
CAL ANALY ¥
‘ a
r v Jase -
’ e

1
= bw vi

| p> ii T
- & - ™
= i Lr
' »
ny " ; "
w ¥ . -.
f :
%
EY wy =
eT »
i i
- #* : : ;
- i ¥
eat © " #
Tp ’ r {

oe
INTERNATIONAL SERIES IN PURE
AND APPLIED MATHEMATICS

William Ted Martin, E. H. Spanier, G. Springer and
P. J. Davis. Consulting Editors

AHLFORS: Complex Analysis

Buck: Advanced Calculus

BUSACKER AND SAATY: Finite Graphs and Networks

CHENEY: Introduction to Approximation Theory

CHESTER: Techniques in Partial Differential Equations

CODDINGTON AND LEVINSON: Theory of Ordinary Differential Equations

CONTE AND DE Boor: Elementary Numerical Analysis: An Algorithmic Approach

DENNEMEYER: Introduction to Partial Differential Equations and Boundary Value
Problems

DETTMAN: Mathematical Methods in Physics and Engineering

GoLoMB AND SHANKS: Elements of Ordinary Differential Equations

GREENSPAN: Introduction to Partial Differential Equations

HammiNG: Numerical Methods for Scientists and Engineers

HILDEBRAND: Introduction to Numerical Analysis

HouseHOLDER: The Numerical Treatment of a Single Nonlinear Equation

KALMAN, FALB, AND ArBIB: Topics in Mathematical Systems Theory

Lass: Vector and Tensor Analysis

McCarty: Topology: An Introduction with Applications to Topological Groups

Monk: Introduction to Set Theory

Moore: Elements of Linear Algebra and Matrix Theory

MosTow AND SAMPSON: Linear Algebra

MouRrsUND AND Duris: Elementary Theory and Application of Numerical Analysis

PEARL: Matrix Theory and Finite Mathematics

P1PES AND HARVILL: Applied Mathematics for Engineers and Physicists

RALsTON: A First Course in Numerical Analysis

RITGER AND RosE: Differential Equations with Applications

RirT: Fourier Series

RUDIN: Principles of Mathematical Analysis

SHAPIRO: Introduction to Abstract Algebra

Simmons: Differential Equations with Applications and Historical Notes

Simmons: Introduction to Topology and Modern Analysis

SNEDDON: Elements of Partial Differential Equations

STRUBLE: Nonlinear Differential Equations
McGraw-Hill, Inc. .
New York St. Louis San Francisco Auckland Bogota
Caracas Lisbon London Madrid Mexico City Milan
Montreal New Delhi San Juan Singapore

Sydney Tokyo Toronto

WALTER RUDIN

Professor of Mathematics
University of Wisconsin-Madison

Principles of
Mathematical
Analysis

THIRD EDITION
This book was set in Times New Roman.

The editors were A. Anthony Arthur and Shelly Levine Langman;
the production supervisor was Leroy A. Young.

R. R. Donnelley & Sons Company was printer and binder.

This book is printed on acid-free paper.

Library of Congress Cataloging in Publication Data

Rudin, Walter, date
Principles of mathematical analysis.

(International series in pure and applied mathematics)
Bibliography: p.
Includes index.
1. Mathematical analysis. 1. Title.
QA300.R8 1976 515 75-17903
ISBN 0-07-054235-X

PRINCIPLES OF MATHEMATICAL ANALYSIS

Copyright © 1964, 1976 by McGraw-Hill, Inc. All rights reserved.
Copyright 1953 by McGraw-Hill, Inc. All rights reserved.

Printed in the United States of America. No part of this publication

may be reproduced, stored in a retrieval system, or transmitted, in any
form or by any means, electronic, mechanical, photocopying, recording, or
otherwise, without the prior written permission of the publisher.

30DOC/DOC098765432
Chapter 1

Chapter 2

Preface

The Real and Complex Number Systems

Introduction

Ordered Sets |

Fields

The Real Field

The Extended Real Number System
The Complex Field

Euclidean Spaces

Appendix

Exercises

Basic Topology

Finite, Countable, and Uncountable Sets
Metric Spaces

Compact Sets

Perfect Sets

CONTENTS
vi CONTENTS

Chapter 3

Chapter 4

Chapter 5

Connected Sets
Exercises

Numerical Sequences and Series

Convergent Sequences
Subsequences

Cauchy Sequences

Upper and Lower Limits
Some Special Sequences
Series

Series of Nonnegative Terms
The Number e

The Root and Ratio Tests
Power Series

Summation by Parts
Absolute Convergence
Addition and Multiplication of Series
Rearrangements

Exercises

Continuity

Limits of Functions

Continuous Functions

Continuity and Compactness
Continuity and Connectedness
Discontinuities

Monotonic Functions

Infinite Limits and Limits at Infinity
Exercises

Differentiation

The Derivative of a Real Function
Mean Value Theorems

The Continuity of Derivatives
L’Hospital’s Rule

Derivatives of Higher Order
Taylor’s Theorem

Differentiation of Vector-valued Functions

Exercises
Chapter 6

Chapter 7

Chapter 8

Chapter 9

Chapter 10

The Riemann-Stieltjes Integral

Definition and Existence of the Integral
Properties of the Integral

Integration and Differentiation
Integration of Vector-valued Functions
Rectifiable Curves

Exercises

Sequences and Series of Functions.

Discussion of Main Problem

Uniform Convergence

Uniform Convergence and Continuity
Uniform Convergence and Integration
Uniform Convergence and Differentiation
Equicontinuous Families of Functions
The Stone-Weierstrass Theorem

Exercises

Some Special Functions

Power Series

The Exponential and Logarithmic Functions

The Trigonometric Functions

The Algebraic Completeness of the Complex Field
Fourier Series

The Gamma Function

Exercises

Functions of Several Variables

Linear Transformations
Differentiation

The Contraction Principle

The Inverse Function Theorem
The Implicit Function Theorem
The Rank Theorem
Determinants

Derivatives of Higher Order
Differentiation of Integrals
Exercises

Integration of Differential Forms
Integration

CONTENTS vii

120

120
128
133
135
136
138

143

143
147
149
151
152
154
159
165

172

172
178
182
184
185
192
196

204

204
211
220
221
223
228
231
235
236
239

245
Chapter 11

Primitive Mappings

Partitions of Unity

Change of Variables
Differential Forms

Simplexes and Chains

Stokes’ Theorem

Closed Forms and Exact Forms
Vector Analysis

Exercises

The Lebesgue Theory

Set Functions

Construction of the Lebesgue Measure
Measure Spaces

Measurable Functions

Simple Functions

Integration

Comparison with the Riemann Integral
Integration of Complex Functions
Functions of Class #2

Exercises

Bibliography
List of Special Symbols
Index

248
PREFACE

This book is intended to serve as a text for the course in analysis that is usually
taken by advanced undergraduates or by first-year students who study mathe-
matics.

The present edition covers essentially the same topics as the second one,
with some additions, a few minor omissions, and considerable rearrangement, I
hope that these changes will make the material more accessible amd more attrac-
tive to the students who take such a course.

Experience has convinced me that it is pedagogically unsound (though
logically correct) to start off with the construction of the real numbers from the
rational ones. At the beginning, most students simply fail to appreciate the need
for doing this. Accordingly, the real number system is introduced as an ordered
field with the least-upper-bound property, and a few interesting applications of
this property are quickly made. However, Dedekind’s construction is not omit-
ted. It is now in an Appendix to Chapter 1, where it may be studied and enjoyed
whenever the time seems ripe.

The material on functions of several variables is almost completely re-
written, with many details filled in, and with more examples and more motiva-
tion. The proof of the inverse function theorem-the key item in Chapter 9-is
X PREFACE

simplified by means of the fixed point theorem about contraction mappings.
Differential forms are discussed in much greater detail. Several applications of
Stokes’ theorem are included.

As regards other changes, the chapter on the Riemann-Stieltjes integral
has been trimmed a bit, a short do-it-yourself section on the gamma function
has been added to Chapter 8, and there is a large number of new exercises, most
of them with fairly detailed hints.

I have also included several references to articles appearing in the American
Mathematical Monthly and in Mathematics Magazine, in the hope that students
will develop the habit of looking into the journal literature. Most of these
references were kindly supplied by R. B. Burckel.

Over the years, many people, students as well as teachers, have sent me
corrections, criticisms, ahd other comments concerning the previous editions
of this book. I have appreciated these, and I take this opportunity to express
my sincere thanks to all who have written me.

WALTER RUDIN
1

THE REAL AND COMPLEX NUMBER SYSTEMS

INTRODUCTION

A satisfactory discussion of the main concepts of analysis (such as convergence,
continuity, differentiation, and integration) must be based on an accurately
defined number concept. We shall not, however, enter into any discussion of
the axioms that govern the arithmetic of the integers, but assume familiarity
with the rational numbers (i.e., the numbers of the form m/n, where m and n
are integers and n # 0).

The rational number system is inadequate for many purposes, both as a
field and as an ordered set. (These terms will be defined in Secs. 1.6 and 1.12.)
For instance, there is no rational p such that p> =2. (We shall prove this
presently.) This leads to the introduction of so-called “‘irrational numbers”
which are often written as infinite decimal expansions and are considered to be
“approximated” by the corresponding finite decimals. Thus the sequence

1,1.4,1.41,1.414,1.4142,..

“tends to \/2.” But unless the irrational number /2 has been clearly defined,
the question must arise: Just what is it that this sequence “tends to’?
2 PRINCIPLES OF MATHEMATICAL ANALYSIS

This sort of question can be answered as soon as the so-called ‘“‘real
number system” is constructed.

1.1 Example We now show that the equation
0) p*=2

is not satisfied by any rational p. If there were such a p, we could write p = m/n
where m and n are integers that are not both even. Let us assume this is done.
Then (1) implies

(V3) m? =2n?,

This shows that m? is even. Hence m is even (if m were odd, m? would be odd),
and so m? is divisible by 4. It follows that the right side of (2) is divisible by 4,
so that n? is even, which implies that n is even.

The assumption that (1) holds thus leads to the conclusion that both m
and n are even, contrary to our choice of m and n. Hence (1) is impossible for
rational p.

We now examine this situation a little more closely. Let A be the set of
all positive rationals p such that p? < 2 and let B consist of all positive rationals
p such that p? > 2. We shall show that 4 contains no largest number and B con-
tains no smallest.

More explicitly, for every p in A we can find a rational q in 4 such that
p <q, and for every p in B we can find a rational c in B such that g < p.

To do this, we associate with each rational p > 0 the number

_ pP=2 2p+2
® g=p P+2 p42
Then

2(p* -2)
4 2.2=
“ q TEP,

If p is in A then p> -2 <0, (3) shows that c > p, and (4) shows that
q* <2. Thus gq is in 4.

If p is in B then p? - 2 > 0, (3) shows that 0 < g < p, and (4) shows that
c*>2. Thusgqisin B.

1.2 Remark The purpose of the above discussion has been to show that the
rational number system has certain gaps, in spite of the fact that between any
two rationals there is another: If r < s then r < (r + 5)/2 <5. The real number
system fills these gaps. This is the principal reason for the fundamental role
which it plays in analysis.
THE REAL AND COMPLEX NUMBER SYSTEMS 3

In order to elucidate its structure, as well as that of the complex numbers,
we start with a brief discussion of the general concepts of ordered set and field.

Here is some of the standard set-theoretic terminology that will be used
throughout this book.

1.3 Definitions If A is any set (whose elements may be numbers or any other
objects), we write x \in A to indicate that x is a member (or an element) of A.

If x is not a member of A, we write: x c A.

The set which contains no element will be called the empty set. If a set has
at least one element, it is called nonempty.

If A and B are sets, and if every element of A is an element of B, we say
that A is a subset of B, and write A c B, or B> A. If, in addition, there is an
element of B which is not in A, then A is said to be a proper subset of B. Note
that A c A for every set A.

If Ac Band B c A, we write A = B, Otherwise A # B.

1.4 Definition Throughout Chap. 1, the set of all rational numbers will be
denoted by Q.

ORDERED SETS

1.5 Definition Let S be a set. An order on S is a relation, denoted by <, with
the following two properties:

(i) If xe Sand y \in S then one and only one of the statements

x<y, x=}, y<x
is true.

(ii) If x,y,ze S,if x<yand y <z, then x<z

The statement “x < y’* may be read as "x is less than y’* or “‘x is smaller
than y** or “x precedes y *.

It is often convenient to write y > x in place of x <y.

The notation x < y indicates that x < y or x = y, without specifying which
of these two is to hold. In other words, x <y is the negation of x > y.

1.6 Definition An ordered set is a set .S in which an order is defined.
For example, Q is an ordered set if r <s is defined to mean that s - ris a
positive rational number.

1.7 Definition Suppose S is an ordered set, and E = S. If there exists a
f= S such that x < f for every x \in E, we say that E is bounded above, and call
B an upper bound of E.

Lower bounds are defined in the same way (with > in place of I).
4 PRINCIPLES OF MATHEMATICAL ANALYSIS

1.8 Definition Suppose § is an ordered set, E = §, and E is bounded above.
Suppose there exists an a \in S with the following properties:

(i) ais an upper bound of E.
(ii) If y <a then y is not an upper bound of E.

Then « is called the least upper bound d E [that there is at most one such
« is clear from (ii)] or the supremum d E, and we write

o=supE.

The greatest lower bound, or infimum, of a set E which is bounded below
is defined in the same manner: The statement

o=infE

means that a is a lower bound of E and that no 8 with ff > a is a lower bound
of E.

1.9 Examples

(a) Consider the sets A and B of Example 1.1 as subsets of the ordered
set Q. The set A is bounded above. In fact, the upper bounds of A are
exactly the members of B. Since B contains no smallest member, A has
no least upper bound in Q.

Similarly, B is bounded below: The set of all lower bounds of B
consists of A and of all re Q with r <0. Since A has no lasgest member,
B has no greatest lower bound in Q.

(b) If a =supE exists, then a may or may not be a member of E. For
instance, let E; be the set of all re Q with r <0. Let E, be the set of all
re Q with r £0. Then

sup E; =sup £, =0,

and 0c E;,0 \in E,.
(c) Let E consist of all numbers 1/n, where n=1, 2, 3,.... Then
sup E = 1, which is in E, and inf E = 0, which is not in E.

1.10 Definition An ordered set S is said to have the least-upper-boundproperty
if the following is true:
If E cS, E is not empty, and E is bounded above, then sup E exists in S.
Example 1.9(a) shows that Q does not have the least-upper-bound property.
We shall now show that there is a close relation between greatest lower
bounds and least upper bounds, and that every ordered set with the least-upper-
bound property also has the greatest-lower-bound property.
THE REAL AND COMPLEX NUMBER SYSTEMS §

1.11 Theorem Suppose S is an ordered set with the least-upper-bound property,
Bc S, B is not empty, and B is bounded below. Let L be the set of all lower
bounds of B. Then

a=supL

exists in S, and a = inf B.

In particular, inf B exists in S.

Proof Since B is bounded below, L is not empty. Since L consists of
exactly those y E.S which satisfy the inequality y < x for every x £ B, we
see that every x EB is an upper bound of L. Thus L is bounded above.
Our hypothesis about § implies therefore that L has a supremum in S;
call it a.

If y <a then (see Definition 1.8) y is not an upper bound of L,
hence y c B. It follows that a <x for every x EB. Thus aeL.

If a < J then f cL, since a is an upper bound of L.

We have shown that a eL but fc L if §>a. In other words, a
is a lower bound of B, but 8 is not if # > a. This means that a = inf B.

FIELDS

1.12 Definition A field is a set F with two operations, called addition and
multiplication, which satisfy the following so-called "field axioms" (A), (M),
and (D):

»)

M)

Axioms for addition

(Al) If x EF and y EF, then their sum x + y is in F.

(A2) Addition is commutative: x + y=y+ x for all x, yE F.

(A3) Addition is associative: (x+ y)+z=x + (y+ z)forallx, y,zEF.
(A4) F contains an element O such that 0 + x = x for every x EF.

(AS) To every x EF corresponds an element -xeF such that

x+(=x)=0.

Axioms for multiplication

(M1) If x eFand ye F, then their product xy is in F.

(M2) Multiplication is commutative: xy = yx for all x, y E F.

(M3) Multiplication is associative: (xy)z = x(pz) for all x, y, ZE F.
(M4) F contains an element I # 0 such that /x = x for every x EF.
(M5) If x E Fand x #0 then there exists an element 1/x E F such that

x (I/x)=1
6 PRINCIPLES OF MATHEMATICAL ANALYSIS

(D) The distributive law

x(y+2)=xy+ xz

holds for all x, y, ze F.

1.13

1.14

Remarks

(a) One usually writes (in any field)
x 2 3
X-ppx tytn ayn x , Xx, 2x,3x,...
in place of
1
x4 (=x (5) 9) + 2 Goods x ean xk xxx

(b) The field axioms clearly hold in Q, the set of all rational numbers, if
addition and multiplication have their customary meaning. Thus Q is a
field.

(c) Although it is not our purpose to study fields (or any other algebraic
structures) in detail, it is worthwhile to prove that some familiar properties
of Q are consequences of the field axioms; once we do this, we will not
need to do it again for the real numbers and for the complex numbers.

Proposition The axioms for addition imply the following statements.

(a) If x+y=x+ztheny=z.
b) Ifx+y=xtheny=0.
(c) If x+y=0theny= -x.
d) -(-x)=x.

Statement (a) is a cancellation law. Note that (b) asserts the uniqueness

of the element whose existence is assumed in (A4), and that (c) does the same
for (AS).

Proof If x + y =x + z, the axioms (A) give

y=0+y=(-x+x)+y=-x+(x+y)
=-x+(x+2)=(-x+x)+2=0+z=1z

This proves (a). Take z = 0 in (a) to obtain (b). Take z= -x in (a) to
obtain (c).
Since -x + x = 0, (c) (with -x in place of x) gives (d).
THE REAL AND COMPLEX NUMBER SYSTEMS 7

1.15 Proposition The axioms for multiplication imply the following statements.

(a Ifx#0and xy=xztheny=z.
b) Ifx#0and xy=xtheny=1.

(c) Ifx#0andxy=1 theny=1/x.
d) If x+#0 then 1/(1/x) = x.

The proof is so similar to that of Proposition 1.14 that we omit it.

1.16 Proposition The field axioms imply the following statements, for any x, y,
ze F.

(a) Ox=0.

(b) Ifx#0andy #0 then xy #0.

(©) (=x) = (xy) =x(-y).

d) (=x)(=y)=xy.

Proof Ox + Ox = (0 + 0)x = Ox. Hence 1.14(b) implies that Ox = 0, and

(a) holds.
Next, assume x # 0, y # 0, but xy =0. Then (a) gives

= GE =G)Glo-o

a contradiction. Thus (b) holds.
The first equality in (c) comes from

(=x) +xy=(-x+xy=0=0,

combined with 1.14(c); the other half of (c) is proved in the same way.
Finally,
(=x)=») = -[x(=»]= [CGN] =xy

by (c) and 1.14(d).

1.17 Definition An ordered field is a field F which is also an ordered set, such
that

(i) x+y<x+zifx,y,zeFandy<z,
(ii) xy>0ifxeF,yeF,x>0,andy>0.

If x > 0, we call x positive; if x <0, x is negative.

For example, Q is an ordered field.

All the familiar rules for working with inequalities apply in every ordered
field: Multiplication by positive [negative] quantities preserves [reverses] in-
equalities, no square is negative, etc. The following proposition lists some of
these.
8 PRINCIPLES OF MATHEMATICAL ANALYSIS

1.18 Proposition Thefollowing statements are true in every ordered field.

(a) If x>0 then -x <0, and vice versa.

(b) If x>0andy<z then xy <xz.

(c) Ifx<0andy<zthen xy> xz.

(d) If x #0 then x* > 0. In particular, 1 > 0.
(e) If0<x<ythen0<l1/y<l/x.

Proof

(a Ifx>0then0=-x+x>-x+0,sothat -x <0. If x <0 then
0=-x+x< -x+0, so that -x > 0. This proves (a).

(b) Since z>y, we have z-y>y -y=0, hence x(z-y)>0, and
therefore

xz =x(z -y) + xy > 0+ xy = xy.

(©) By (a), (b), and Proposition 1.16(c),
= [xz = l= (=x) -») >0,

so that x(z - y) <0, hence xz < xy.
(d) If x>0, part (ii) of Definition 1.17 gives x? > 0. If x <0, then
-x>0, hence (-x)>>0. But x2=(-x)? by Proposition 1.16(d).
Since 1 =12, 1 > 0.
(e) Ify>0andv<0,thenyv <0. Buty. (l/y)=1>0. Hence l/y > 0.

Likewise, 1/x > 0. If we multiply both sides of the inequality x <y by
the positive quantity (1/x)(1/y), we obtain 1/y <1/x.

THE REAL FIELD

We now state the existence theorem which is the core of this chapter.

1.19 Theorem There exists an ordered field R which has the least-upper-bound

property.
Moreover, R contains Q as a subfield.

The second statement means that Q = R and that the operations of
addition and multiplication in R, when applied to members of Q, coincide with
the usual operations on rational numbers; also, the positive rational numbers
are positive elements of R.

The members of R are called real numbers.

The proof of Theorem 1.19 is rather long and a bit tedious and is therefore
presented in an Appendix to Chap. 1. The proof actually constructs R from Q.
THE REAL AND COMPLEX NUMBER SYSTEMS 9

The next theorem could be extracted from this construction with very
little extra effort. However, we prefer to derive it from Theorem 1.19 since this
provides a good illustration of what one can do with the least-upper-bound

property.

1.20 Theorem
(a) If xe R, ye R, and x > 0, then there is a positive integer n such that
nx > y.

(b) Ifxe Rye R,and x < y, then there existsap \in Q suchthat x <p <y.

Part (a)is usually referred to as the archimedean property of R. Part (b)
may be stated by saying that Q is dense in R: Between any two real numbers
there is a rational one.

Proof

(a) Let A be the set of all nx, where n runs through the positive integers.
If (a) were false, then y would be an upper bound of A. But then A has a
least upper bound in R. Put a =sup A. Since x >0, a - x <a, and
2 - x is not an upper bound of A. Hence x - x < mx for some positive
integer m. But then a <(m + 1)x \in A, which is impossible, since « is an
upper bound of A.

(b) Since x <y, we have y - x > 0, and (a) furnishes a positive integer
n such that

n(y-x)>1.

Apply (a) again, to obtain positive integers m, and mm, such that m, > nx,
m, > -nx. Then

-m,; < hx < my.
Hence there is an integer m (with -m, < m < m, ) such that
m-1<nx<m.
If we combine these inequalities, we obtain
nx <m<1+nx<ny.

Since n > 0, it follows that
m
xX <= <y.
n

This proves (b), with p = m/n.
10 PRINCIPLES OF MATHEMATICAL ANALYSIS

We shall now prove the existence of nth roots of positive reals. This
proof will show how the difficulty pointed out in the Introduction (irration-

ality of J2) can be handled in R.

1.21 Theorem For every real x > 0 and every integer n> 0 there is one
and only one positive real y such that y" = x.

This number y is written x or x!/"

Proof That there is at most one such y is clear, since 0 < y, < y, implies
yi <ys.
Let E be the set consisting of all positive real numbers c such that
<x.
If t=x/(1+ x)then0<t<] Hencet"<t<x. ThustekE, and
Eis not empty.
If t> 1+ x then "= c> x, so that tc E. Thus | + x is an upper
bound of E.
Hence Theorem 1.19 implies the existence of

n

t

y=supE.

To prove that y" = x we will show that each of the inequalities y" < x
and y" > x leads to a contradiction.

The identity b"-a"=(b- a)" ' +b" 2a+ + +a") yields
the inequality

b' -a"<(b- ab"!

when 0 <a <b.

Assume y" < x. Choose h so that 0 <h < [ and
x - y!
h< -F5

n(y + Hn 1

Puta=y, b=y+h Then
(y+ h)' = yy <hn(y+ hy" '<hn(y+ 1)" <x-y"

Thus (y+ h)"<x, and y+ he E. Since y +h > y, this contradicts the
fact that y is an upper bound of E.
Assume y" > x. Put

Then 0 <k <y. If > y - k, we conclude that
YV=r<y -(y-kr<km'l'=y -x
Thus "> x, and tc E. It follows that y - k is an upper bound of E.
THE REAL AND COMPLEX NUMBER SYSTEMS 11

But y - k <y, which contradicts the fact that y is the least upper bound
of E.

Hence y" = x, and the proof is complete.
Corollary If a and b are positive real numbers and n is a positive integer, then

(ab)! = al’"biin,
Proof Puta =a'/", f=b'" Then
ab = o"B" = (af),

since multiplication is commutative. [Axiom (M2) in Definition 1.12.]

The uniqueness assertion of Theorem 1.21 shows therefore that

(ab)! = af = a*l"btim,

1.22 Decimals We conclude this section by pointing out the relation between
real numbers and decimals.

Let x > 0 be real. Let ny be the largest integer such that no < x. (Note that
the existence of #y depends on the archimedean property of R.) Having chosen

Hg, Nyy... , Ng_y, let ng be the largest integer such that
Ho + do hk gx
°710 10 =
Let E be the set of these numbers
n ny
-4+ += k=0,1,2,...).
©) mot ptr (k=0,12..)

Then x = sup E. The decimal expansion of x is
6) Rg .mnyny..c.

Conversely, for any infinite decimal (6)the set E of numbers (5) is bounded
above, and (6)is the decimal expansion of sup E.

Since we shall never use decimals, we do not enter into a detailed
discussion.

THE EXTENDED REAL NUMBER SYSTEM

1.23 Definition The extended real number system consists of the real field R
and two symbols, +00 and -oco. We preserve the original order in R, and
define

-0 <x< +o
for every x \in R.
12 PRINCIPLES OF MATHEMATICAL ANALYSIS

It is then clear that + 00 is an upper bound of every subset of the extended
real number system, and that every nonempty subset has a least upper bound.
If, for example, E is a nonempty set of real numbers which is not bounded
above in R, then sup E = +00 in the extended real number system.

Exactly the same remarks apply to lower bounds.

The extended real number system does not form a field, but it is customary
to make the following conventions:

(a) If x is real then

X + 00 = +00, X - 00 = -a0, -  =- =0.
+0 =
(b) If x>0then x (+) = +00, x*(-00)=-00.
(©) Ifx<O0thenx-(+00)=-00,x:(-00)= +00.

When it is desired to make the distinction between real numbers on the
one hand and the symbols +00 and - «0 on the other quite explicit, the former
are called finite.

THE COMPLEX FIELD

1.24 Definition A complex number is an ordered pair (a, b) of real numbers.
"Ordered" means that (a, b) and (b, a) are regarded as distinct if a # b.

Letx = (a, b),y = (c,d) be two complex numbers. We write x =y if and
only if a =c and b=d. (Note that this definition is not entirely superfluous;
think of equality of rational numbers, represented as quotients of integers.) We
define

x+y=(a+cb+d),

xy = (ac - bd, ad + bc).
1.25 'Theorem These definitions d addition and multiplication turn the set of

all complex numbers into afield, with (0, 0) and (1, 0) in the role 0 and 1.

Proof We simply verify the field axioms, as listed in Definition 1.12.
(Of course, we use the field structure of R.)

Let x = (a, b),y = (c, d), z = (e,f).
(Al) is clear.
(A2) x+y=a+eb+d)=(c+ad+b)=y+x
THE REAL AND COMPLEX NUMBER SYSTEMS 13

(A3) x+y)+z=(a+c,b+4d)+ (ef)
=a+c+eb+d+f)
=(a,b)¥ (+e d+f)=x+a +2).
(A4) x+0=(a,b) + (0,0) =(a, b) =x.
(AS) Put -x=(-a,-b). Then x + (- x)=(0,0)=0.
(M1) is clear.
(M2) xy=(ac- bd, ad + bc)=(ca- db, da + cb) = yx.
(M3) (x¥)z= (ac - bd, ad + bc)e, f)
= (ace - bde - adf - bef, acf - bdf + ade + bce)
= (a,b)(ce - df, cf + de) = x(yz).
(M4) 1x =(1, 0)(a, b) = (a, b) = x.
(MS) If x #0 then (a,b)# (0,0), which means that at least one of the
real numbers a, b is different from 0. Hence a? + 5? > 0, by Proposition
1.18(d), and we can define

b(n oh)
x \a*+b* 7)
Then
1 a -b
FD ao) = 0-1
DO) x(r+2)=(a,b)c+ed+f)
= (ac + ae - bd - bf, ad + af + bc + be)
= (ac- bd, ad + bc) + (ae - bf, af + be)
=xy + xz

x

1.26 Theorem For any real nutnbers a and b we have

(a,0)+ (5,0) = (a+ 5,0), (a,0)b,0) = (ab,0).

The proof is trivial.

Theorem 1.26 shows that the complex numbers of the form (a, 0) have the
same arithmetic properties as the corresponding real numbers a. We can there-
fore identify (a,0) with a. This identification gives us the real field as a subfield
of the complex field.

The reader may have noticed that we have defined the complex numbers
without any reference to the mysterious square root of -/. We now show that
the notation (a, b) is equivalent to the more customary a + bi.

1.27 Definition i= (0,1).
14 PRINCIPLES OF MATHEMATICAL ANALYSIS

1.28 Theorem i’= -1I.
Proof i? =(0,1)0,1)=(-1,0)= -1.

1.29 Theorem If a and b are real, then (a,b) =a + bi.

Proof
a+ bi=(a0)+(b,000,1)
=(a,0+©,b)=(a,b).

1.30 Definition If a, b are real and z =a + bi, then the complex number
Z =a - bi is called the conjugate of z. The numbers a and b are the real part
and the imaginary part of z, respectively.

We shall occasionally write

a = Re(2). b = Im(2).

1.31 Theorem If z and w are complex, then

(a) z+ w=Z+W,

(b) w=2"%,

(c) 2 +z =2Re(2), 7-7 =2ilm(2),

(d) zz is real and positive (except when 7 =0).

Proof (a), (b),and (c)are quite trivial. To prove (d), write z = a + bi,
and note that zZ = a’ + b>.

1.32 Definition If z is a complex number, its absolute value |z| is the non-
negative square root of zZ; that is, |z| = (z2)"/%.

The existence (and uniqueness) of |z| follows from Theorem 1.2/ and
part (d)of Theorem 1.31.

Note that when x is real, then X = x, hence |x| =+/x2. Thus |x| = x
ifx>0, |x| = -xif x <0.

1.33 Theorem Let z and w be complex numbers. Then

(a) |z| >0 unless z=0, |0]| =0,
®) [2] = Iz,
(0) [zw] = |z{[w]
THE REAL AND COMPLEX NUMBER SYSTEMS 15

Proof (a)and (b)are trivial. Put z=a+ bi, w=c +di, witha, b, c, d
real. Then

|zw|2 = (ac - bd)* + (ad+ bc)* =(a® + b*)(* +d?) = |z|*|w|?

or [zw]? = (lel [wl)®. Now (c)follows from the uniqueness assertion of
Theorem 1.21.
To prove (d), note that a’ < a? + b?, hence

la] = Ja* < Ja + b2.

To prove (e), note that Zw is the conjugate of zw, so that zw + zw =
2 Re (zw). Hence

[z+ w|2=(Z+WEZ+ WP) =z2Z+2F+2Zw+ ww
= |z|2 +2 Re (zW) + |w|?
<|z|*+2|zW| + |w|?
= [z| + 2|z]{w| + [w]* = (lz] + [w])*

Now (e)follows by taking square roots.
1.34 Notation If xy, ..., x, are complex numbers, we write
XX + hx, = 3 x
j=1

We conclude this section with an important inequality, usually known as
the Schwarz inequality.

1.35 Theorem EX a,,..., a, and by, ..., b, are complex numbers, then

Proof Put A =X|a;|? B =Z|b;|?, C=Za;b; (in all sums in this proof,
Jj runs over the values 1,..., n). If B=0, thenb, = -- =b, = 0, and the
conclusion is trivial. Assume therefore that B > 0. By Theorem 1.31 we
have
Y |Ba; - Cb, |* = ¥. (Ba; - Cb;)(Ba; - Cb;)
=B*) |a|*-BCY a;b;- BC} a;b; + |C|*Y |b,|?
- B%A - B|C|?
= B(4B - |C|?).

16 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since each term in the first sum is nonnegative, we see that
B(4B- |C|H>0.
Since B > 0, it follows that AB - [C|? > 0. This is the desired inequality.

EUCLIDEAN SPACES

1.36 Definitions For each positive integer k, let R* be the set of all ordered
k-tuples
X= (x1, x3, “ees XE),

where xy, ..., Xx; are real numbers, called the coordinates of x. The elements of
R* are called points, or vectors, especially when k > 1. We shall denote vectors
by boldfaced letters. If y = (yy, ..., ¥) and if « is a real number, put

X+Yy=0X+Y eos Xk +20)»
ax = (0x, ..., 0X)

so that x +yeR and ax e RY. This defines addition of vectors, as well as
multiplication of a vector by a real number (a scalar). These two operations
satisfy the commutative, associative, and distributive laws (the proof is trivial,
in view of the analogous laws for the real numbers) and make R* into a vector
space over the real field. The zero element of R* (sometimes called the origin or
the null vector) is the point 0, all of whose coordinates are 0.
We also define the so-called "inner product’ (or scalar product) of x and

y by

k

X'y= 2 xii
“

and the norm of x by
3 1/2
x =x = (32)
1

The structure now defined (the vector space R* with the above inner
product and norm) is called euclidean k-space.

1.37 Theorem Suppose x, y, z \in  RY, and a is real. Then

(a |x| =0;
(b) |x| =0ifand only if x =0;
(0) Jax] - [af |x];

a |x-y| <|x[lyl;
a x+y <x +1yl;
Of) |x-z|<|x-y|+]|y-z|.
THE REAL AND COMPLEX NUMBER SYSTEMS 17

Proof (a), (b), and (c) are obvious, and (d) is an immediate consequence
of the Schwarz inequality. By (d) we have

(X+y|?=x+y) x+y)
=X"X+2x'y+y'y
< |x|? + 2|x|{y| + yl?
=(Ix| + [y])%

so that (e) is proved. Finally, (f) follows from (e) if we replace x by
Xx-yandybyy-z

1.38 Remarks Theorem 1.37 (a), (b), and (f) will allow us (see Chap. 2) to
regard R* as a metric space.

R! (the set of all real numbers) is usually called the line, or the real line.
Likewise, R? is called the plane, or the complex plane (compare Definitions 1.24
and 1.36). In these two cases the norm is just the absolute value of the corre-
sponding real or complex number.

APPENDIX

Theorem 1.19 will be proved in this appendix by constructing R from Q. We
shall divide the construction into several steps.

Step 1 The members of R will be certain subsets of Q, called cuts. A cut is,
by definition, any set a = Q with the following three properties.

(I) ais not empty, and a # Q.
(Il) Ifpea,qeQ, and q <p, then q \in  a.
(III) Ifpea, then p <r for some r \in a.
The letters p, q, 1, . .. will always denote rational numbers, and a, B, y, ...
will denote cuts.

Note that (III) simply says that a has no largest member: (II) implies two
facts which will be used freely:

Ifpeaand gcathen p<g.
If rc cand r <sthen sc a.

Step 2 Define "a < f° to mean: a is a proper subset of f.

Let us check that this meets the requirements of Definition 1.5.

If a < Band B <vyitisclearthata <y. (A proper subset of a proper sub-
set is a proper subset.) It is also clear that at most one of the three relations

a<f, a= B<a
18 PRINCIPLES OF MATHEMATICAL ANALYSIS

can hold for any pair a, f. To show that at least one holds, assume that the
first two fail. Then « is not a subset of ff. Hence there is a p \in  a with p & f.
If qe B, it follows that q <p (since p c 8), hence q ea, by (II). Thus ca.
Since fi # «, we conclude: ff < a.

Thus R is now an ordered set.

Step 3 The ordered set R has the least-upper-bound property.

To prove this, let A be a nonempty subset of R, and assume that fe R
is an upper bound of A. Define y to be the union of all x \in A. In other words,
pey if and only if p \in « for some «x \in A. We shall prove that y eR and that
y = sup A.

Since A is not empty, there exists an ay \in A. This a is not empty. Since
®%y cy, y is not empty. Next, y c ff (since a c f for every a \in A), and therefore
y # Q. Thus y satisfies property (I). To prove (II) and (111), pick p \in y. Then
p  \in ay for some a; \in A. If q <p, then q \in ay, hence q \in  y; this proves (II). If
rea, is so chosen that r > p, we see that r \in y (since a, = y), and therefore y
satisfies (111).

Thus y eR.

It is clear that a <y for every x \in A.

Suppose 6 <y. Then there is an s \in y and that sc6. Since sey, sea
for some a \in A. Hence 6 <a, and 6 is not an upper bound of A.

This gives the desired result: y = sup A.

Step4 If eR and f \in R we define a + § to be the set of all sums r +s, where
reoand sep.
We define 0* to be the set of all negative rational numbers. It is clear that
0* is a cut. We verify that the axioms for addition (see Definition 1.12) hold in
R, with 0* playing the role of 0.
(Al) We have to show that a + fis a cut. It is clear that a +f is a
nonempty subset of Q. Take r' c a, s'cB. Then r' +s’ >r +s for all
choices of rea, se. Thus r' +s c a+ p. It follows that « + 8 has
property (I).

Pick pea +B. Then p=r+s, with rea, sep. If q<p, then
q-s<r, so q-sea, and q=(q-s)+sea+ B. Thus (II) holds.
Choose tea so that t >r. Thenp <t+ sand t+sea+ j. Thus (III)
holds.

(A2) o+ Bisthe setof all r +s, with r \in a, s \in f. By the same definition,
f+ ais the set of all s+r. Sincer+s=s+r forall re Q, se Q, we
havea + f =f +a.

(A3) As above, this follows from the associative law in Q.

(A4) Ifreaand se 0% thenr +s <r, hencer + sec. Thusa+ 0* Ci
To obtain the opposite inclusion, pick p \in «, and pick r \in a, r > p. Then
THE REAL AND COMPLEX NUMBER SYSTEMS 19

p-re0* and p=r+(p-r)ea + 0% Thus « = a+ 0*. We conclude
that a + 0* = a.
(A5) Fix ae R. Let f8 be the set of all p with the following property:

There exists r > 0 such that -p - rc a.

In other words, some rational number smaller than -p fails to
be in a.

We show that f \in R and that a + § = 0*.

Ifsc xandp= -s- 1, then -p - 1 c a, hence pe f. So pis not
empty. If q \in a, then -gc f. So ff # Q. Hence f satisfies (I).

Pick pep, and pick r>0, so that -p -réc a. If q<p, then
-q-r>-p-r, hence -q-réca. Thus qef, and (II) holds. Put
t=p +(r/2). Then t>p, and -t-(r/2)= -p -rc a, so that te f.
Hence f satisfies (111).

We have proved that f \in R.

If reaxand s \in  ff, then -sc a, hence r< -s, r +5 <0. Thus
a+ fc Ox

To prove the opposite inclusion, pick ve 0*, put w = -/2. Then
w > 0, and there is an integer n such that nw \in a but (n + 1)w c a. (Note
that this depends on the fact that Q has the archimedean property!) Put
p= -(n + 2)w. Then pe f, since -p - wc a, and

v=nw+pea +f.
Thus 0* = a + f.
We conclude that a + f = 0%.
This # will of course be denoted by -a.

Step 5 Having proved that the addition defined in Step 4 satisfies Axioms (A)
of Definition 1.12, it follows that Proposition 1.14 is valid in R, and we can
prove one of the requirements of Definition 1.17:

¥a f,yeRandf<y, thena+f<a+ty.

Indeed, it is obvious from the definition of + in R thata + f ca + y; if
we had o + fi =« + y, the cancellation law (Proposition 1.14) would imply
B=1.

It also follows that a > 0* if and only if -a < 0%,

Step 6 Multiplication is a little more bothersome than addition in the present
context, since products of negative rationals are positive. For this reason we
confine ourselves first to RT, the set of all a \in R with a > 0*.

If ae RY and fe R*, we define af to be the set of all p such that p < rs
for some choice of rea, se f,r>0,5>0.

We define 1* to be the set of all q < 1.
20 PRINCIPLES OF MATHEMATICAL ANALYSIS

Then the axioms ( M )and ( D ) of Definition 1.12 hold, with R* in place of F,
and with 1* in the role of 1.

The proofs are so similar to the ones given in detail in Step 4 that we omit
them.

Note, in particular, that the second requirement of Definition 1.17 holds:
If a > 0* and f > 0* then aff > 0*.

Step 7 We complete the definition of multiplication by setting «0* = 0*a = 0%,
and by setting
(-a)(-p) fa<0% f<0%
af = { =[(-)B] if a <O0* f>0%
=o. (=p) ifa>0%p<0*
The products on the right were defined in Step 6.
Having proved (in Step 6) that the axioms (M) hold in R™, it is now
perfectly simple to prove them in R, by repeated application of the identity

= -(-7) which is part of Proposition 1.14. (See Step 5.)
The proof of the distributive law

a(B + 7) = af + oy
breaks into cases. For instance, suppose a> 0% f <0% f+7y>0* Then
y = (Bf + 7) + (- pf), and (since we already know that the distributive law holds
in RY)

ay=af +7) +a (=f).
But a: (=f) = -(2f). Thus

af + oy =a(B + y)

The other cases are handled in the same way.

We have now completed the proof that R is an orderedfield with the least-
upper-bound property.

Step 8 We associate with each re Q the set r* which consists of all pe Q
such that p <r. Itis clear that each r* is a cut; that is, r* \in R. These cuts satisfy
the following relations:

(a) r*+s*=(r+s),
(b) r¥s* =(rs)*,
(c) r*<s*ifandonly ifr <s.

To prove (a), choose per* + s*. Then p=u+uv, where u<r, v<s.
Hence p < r +s, which says that p \in (r + s)*.
THE REAL AND COMPLEX NUMBER SYSTEMS 21

Conversely, suppose pe(r+s)*. Then p<r+s. Choose c so that

2t=r+s5-p, put
r=r-ts=s-t

Then r' \in r*, s'es*, and p =r’ +5’, so that pe r* + s*

This proves (a). The proof of (b)is similar.

If r < s then re s*, but rc r*; hence r* < s*.

If r* <s* then there is a pe s* such that pécr* Hence r<p<s, so
that r <s.

This proves (c).

Step 9 We saw in Step 8 that the replacement of the rational numbers r by the
corresponding "rational cuts’ r* \in R preserves sums, products, and order. This
fact may be expressed by saying that the ordered field Q is isomorphic to the
ordered field Q* whose elements are the rational cuts. Of course, r* is by no
means the same as r, but the properties we are concerned with (arithmetic and
order) are the same in the two fields.

It is this identification of Q with Q* which allows us to regard Q as a
subfield of R.

The second part of Theorem 1.19 is to be understood in terms of this
identification. Note that the same phenomenon occurs when the real numbers
are regarded as a subfield of the complex field, and it also occurs at a much
more elementary level, when the integers are identified with a certain subset of Q.

It is a fact, which we will not prove here, that any two orderedfields with
the least-upper-bound property are isomorphic. The first part of Theorem 1.19
therefore characterizes the real field R completely.

The books by Landau and Thurston cited in the Bibliography are entirely
devoted to number systems. Chapter 1 of Knopp's book contains a more
leisurely description of how R can be obtained from Q. Another construction,
in which each real number is defined to be an equivalence class of Cauchy
sequences of rational numbers (see Chap. 3), is carried out in Sec. 5 of the book
by Hewitt and Stromberg.

The cuts in Q which we used here were invented by Dedekind. The
construction of R from Q by means of Cauchy sequences is due to Cantor.
Both Cantor and Dedekind published their constructions in 1872.

EXERCISES

Unless the contrary is explicitly stated, all numbers that are mentioned in these exer-
cises are understood to be real.

1. If ris rational (r# 0) and x is irrational, prove that r + x and rx are irrational.
22

2,

Ww

PRINCIPLES OF MATHEMATICAL ANALYSIS

. Prove that there is no rational number whose square is 12.

. Prove Proposition 1.15.

. Let E be a nonempty subset of an ordered set; suppose « is a lower bound of E
and B is an upper bound of E. Prove that « <p.

5. Let A be a nonempty set of real numbers which is bounded below. Let -A4 be

10

the set of all numbers - x, where x \in 4. Prove that
inf 4 = -sup(- A).

. Fix b>1,
(a) If m, n, p, q are integers, n > 0, g > 0, and r = m/n = p/q, prove that
(bmyr» -_ (b*)t/a,
Hence it makes sense to define b" = (b™)'/",
(b) Prove that b"** = b'b* if r and s are rational.
(c) If x is real, define B(x) to be the set of all numbers 5‘, where c is rational and
t <x. Prove that
b" = sup B(r)
when r is rational. Hence it makes sense to define
* = sup B(x)

for every real x.
(d) Prove that b**¥ = b*b* for all real x and y.

. Fix b>1, y>0, and prove that there is a unique real x such that 5* =y, by
completing the following outline. (This x is called the logarithm of y to the base b.)
(a) For any positive integer n, b" - 1 >n(b- 1).

(b) Hence b- 1 > n(b'"- 1).

(cc) If t>1and n> (b-1)/(t- 1), then b'/" < t.

(d) If w is such that b” < y, then b**"/» < y for sufficiently large n; to see this,
apply part (c) witht =y b=".

(e) If b* > y, then b*~"'™ > y for sufficiently large n.

(f) Let A be the set of all w such that 5” < y, and show that x = sup A satisfies
b* =y.

(g) Prove that this x is unique.

. Prove that no order can be defined in the complex field that turns it into an ordered
field. Hint: -1 is a square.

. Suppose z=a-+ bi, w=c-+di. Define z<w if a<c, and also if a=c but
b < d. Prove that this turns the set of all complex numbers into an ordered set.
(This type of order relation is called a dictionary order, or lexicographic order, for
obvious reasons.) Does this ordered set have the least-upper-bound property ?

. Suppose z = a + bi, w =u + iv, and

BN Iw] + u 1/2 BN [w| -u 1/2
a = (Lele , b= - .
11.

13.

14.

15.
16.

17.

18.

19.

20.

THE REAL AND COMPLEX NUMBER SYSTEMS 23

Prove that z2 = w if v > 0 and that (7)? = w if v <0. Conclude that every complex
number (with one exception!) has two complex square roots.

If z is a complex number, prove that there exists an r => 0 and a complex number
w with |w| = 1 such that z =rw. Are wand r always uniquely determined by z?

. If z,, ..., zy are complex, prove that

zit zat tz al +z) + +
If x, y are complex, prove that
lll = I] < x=.
If z is a complex number such that |z| = 1, that is, such that zZ = 1, compute

[T4224 1-2]

za].

Under what conditions does equality hold in the Schwarz inequality?
Suppose k >3, x, y \in  R*, [x -y| =d>0, and r >0. Prove:
(a) If 2r > d, there are infinitely many z \in R* such that
|z-x| =|z-y| =r.

(b) If 2r -=d, there is exactly one such z,
(c) If 2r << d, there is no such z.
How must these statements be modified if k is 2 or 1?
Prove that

Ix +yl*+[x-y* =2|x]*+2]y|*
if XxeR" and ye R". Interpret this geometrically, as a statement about parallel-
ograms.
If k >2 and xe R%, prove that there exists y \in R* such that y #0 but x+y =0.
Is this also true if k =17
Suppose a \in  R', b \in R*. Find c \in R* and r > 0 such that

|x -a] =2|x-b|
if and only if |x -c| =r.
(Solution: 3c =4b-a, 3r =2|b-al.)
With reference to the Appendix, suppose that property (111) were omitted from the
definition of a cut. Keep the same definitions of order and addition. Show that

the resulting ordered set has the least-upper-bound property, that addition satisfies
axioms (Al) to (A4) (with a slightly different zero-element!) but that (AS) fails.
2

BASIC TOPOLOGY

FINITE, COUNTABLE, AND UNCOUNTABLE SETS

We begin this section with a definition of the function concept.

2.1 Definition Consider two sets A and B, whose elements may be any objects
whatsoever, and suppose that with each element x of A there is associated, in
some manner, an element of B, which we denote by f(x). Then fis said to be a
function from A to B (or a mapping of A into B). The set A is called the domain
off (we also say fis defined on A), and the elements f(x) are called the values
off. The set of all values off is called the range off.

22 Definition Let A and B be two sets and let f be a mapping of A into B.
If Ec A, f(E) is defined to be the set of all elements f(x), for xe E. We call
f(E)the image of E under f. In this notation, f(A )is the range off. It is clear
that f(A)c B. Iff (A)= B, we say thatf'maps A onto B. (Note that, according
to this usage, onto is more specific than into.)

If E c B, f YE) denotes the set of all x \in  A such that f(x)e E. We call
f=! (E)the inverse image of E under f. If y eB, f(y) is the set of all xe A
BASIC TOPOLOGY 25

such that f(x) =y. If, for each y e B,f ~!(») consists of at most one element
of A, then f is said to be a 1-1 (one-to-one) mapping of A into B. This may
also be expressed as follows: f is a 1-1 mapping of A into B provided that
f(x) # f(x,) whenever x, #x,, x, EA, x,  \in 4.

(The notation x; # x, means that x; and x, are distinct elements; other-
wise we write X, = X,.)

2.3 Definition If there exists a 1-1 mapping of A onto B, we say that A and B
can be putin 1-1 correspondence, or that A and B have the same cardinal number,
or, briefly, that A and B are equivalent, and we write A ~ B. This relation
clearly has the following properties :

1t is reflexive: A ~ A.
It is symmetric: If A ~ B, then B~ A.
It is transitive: If A~ B and B~ C, then A ~ C.

Any relation with these three properties is called an equivalence relation.

2.4 Definition For any positive integer n, let J, be the set whose elements are
the integers 1, 2, ..., n; let J be the set consisting of all positive integers. For any
set A, we say:

(a) Aisjinite if A ~ J, for some n (the empty set is also considered to be
finite).

(b) Ais infinite if A is not finite.

(c) Ais countableif A ~1J.

(d) A is uncountable if A is neither finite nor countable.

(e) A is at most countable if A is finite or countable.

Countable sets are sometimes called enumerable, or denumerable.

For two finite sets A and B, we evidently have A ~ B if and only if 4 and
B contain the same number of elements. For infinite sets, however, the idea of
"having the same number of elements’ becomes quite vague, whereas the notion
of 1-1 correspondence retains its clarity.

2.5 Example Let A be the set of all integers. Then A is countable. For,
consider the following arrangement of the sets A and J:
26 PRINCIPLES OF MATHEMATICAL ANALYSIS

We can, in this example, even give an explicit formula for a function f
from J to A which sets up a 1-1 correspondence:

n

3 (n even),

Jn) = -
r= dd)
| 2 (n odd).

2.6 Remark A finite set cannot be equivalent to one of its proper subsets.
That this is, however, possible for infinite sets, is shown by Example 2.5, in
which J is a proper subset of A.

In fact, we could replace Definition 2.4(b) by the statement: A is infinite if
A is equivalent to one of its proper subsets.

2.7 Definition By a sequence, we mean a function f defined on the set J of all
positive integers. Iff (n)= x,, for ne J, it is customary to denote the sequence
f by the symbol {x,), or sometimes by x;, X,, X3,.... The values off, that is,
the elements x, , are called the ferms of the sequence. If A is a set and if x, \in A
for all neJ, then {x,} is said to be a sequence in A, or a sequence of elements of A.

Note that the terms xy, X, , X3,... of a sequence need not be distinct.

Since every countable set is the range of a 1-1 function defined on J, we
may regard every countable set as the range of a sequence of distinct terms.
Speaking more loosely, we may say that the elements of any countable set can
be "arranged in a sequence."

Sometimes it is convenient to replace J in this definition by the set of all
nonnegative integers, i.e., to start with O rather than with 1.

2.8 Theorem Every infinite subset of a countable set A is countable.

Proof Suppose E = A, and E is infinite. Arrange the elements x of A in
a sequence {x,) of distinct elements. Construct a sequence {#,} as follows:

Let n; be the smallest positive integer such that x, \in E. Having
chosen ny, ...,m_ (k=2,3,4,...), let n; be the smallest integer greater
than »,_, such that x, \in E.

Putting f(k) = x,, (k=1, 2,3,...), we obtain a 1-1 correspondence
between E and J.

The theorem shows that, roughly speaking, countable sets represent

the "smallest" infinity: No uncountable set can be a subset of a countable
set.

2.9 Definition Let A and Q be sets, and suppose that with each element a of
A there is associated a subset of which we denote by E,.
BASIC TOPOLOGY 27

The set whose elements are the sets E, will be denoted by {E,}. Instead
of speaking of sets of sets, we shall sometimes speak of a collection of sets, or
a family of sets.

The union of the sets E, is defined to be the set S such that x \in Sif and only
if x \in E, for at least one a \in A. We use the notation

5=E.
aed
If A consists of the integers 1, 2, ..., n, one usually writes
S=J En.
m=1
3) S=E,VE,u- UE,

If A is the set of all positive integers, the usual notation is

The symbol oo in (4) merely indicates that the union of a countable col-
lection of sets is taken, and should not be confused with the symbols + co, - co,
introduced in Definition 1.23.

The intersection of the sets E, is defined to be the set P such that x e P if
and only if x \in E, for every a \in A. We use the notation

P=) E,

acd

™ P= (En,

as for unions. If A Nn Bis not empty, we say that A and B intersect; otherwise
they are disjoint.

2.10 Examples

(a) Suppose Ej consists of 1,2,3 and E, consists of 2, 3,4. Then
E, u E, consists of 1, 2, 3, 4, whereas E; Nn E, consists of 2, 3.
28 PRINCIPLES OF MATHEMATICAL ANALYSIS

(b) Let A be the set of real numbers x such that 0 < x <1. For every
x \in A, let E, be the set of real numbers y such that 0 < y < x. Then

(a) E cE ifandonlyif0<x<z<1;
(ii) UE. = Ei;

xeA
(iii) ( E, is empty;

xeA

(i) and (ii) are clear. To prove (iii), we note that for every y > 0, yc E,
if x <y. Hence y c( eeu Ex.

2.11 Remarks Many properties of unions and intersections are quite similar
to those of sums and products; in fact, the words sum and product were some-
times used in this connection, and the symbols £ and IT were written in place

of | J and ).

The commutative and associative laws are trivial:
8) AUB=BuU A; AnB=Bn A.
9) (AuB)uC=A4AuU (BUC); (ANB) NnC=An(BnC).

Thus the omission of parentheses in (3) and (6) is justified.
The distributive law also holds:

(10) An(BuC)=(AnB)uAnC().

To prove this, let the left and right members of (10) be denoted by E and F,
respectively.

Suppose xe E. Then xe A and xe Bu C, that is, x \in B or x \in C (pos-
sibly both). Hence xe A n Bor xe A n C, so that xe F. Thus Ec F.

Next, suppose x \in  F. Thenxe An Bor xe An C. Thatis, xe A, and
xeBu CC. Hence xe An (Bu C), so that Fc E.

It follows that E = F.

We list a few more relations which are easily verified:

(11) Ac Av B,

(12) An Bc A.

If 0 denotes the empty set, then

(13) Au0=4, An0=0.
If A = B, then

(14) AUB=B, AnB=A.
BASIC TOPOLOGY 29

2.12 Theorem Let{E,), n=1,2,3,..., bea sequence of countable sets, and put

00
(15) S= U E,.
n=1
Then S is countable.

Proof Let every set E, be arranged in a sequence {x}, k=1,2,3,...
and consider the infinite array

(16)

in which the elements of E£, form the nth row. The array contains all
elements of S. As indicated by the arrows, these elements can be
arranged in a sequence

mn Xetd Xone X125 X31. X225 X135 Xa1s X32, X23. X145 «+.

If any two of the sets E, have elements in common, these will appear more
than once in (17). Hence there is a subset T of the set of all positive
integers such that S~T, which shows that S is at most countable
(Theorem 2.8). Since E; = S, and E, is infinite, S is infinite, and thus
countable.

Corollary Suppose A is at most countable, and, for every a \in A, B, is at most
countable. Put

T=|JB..
ach
Then T is at most countable.

For T is equivalent to a subset of (15).

2.13 Theorem Let A be a countable set, and let B, be the set of all n-tuples
(a,, ...,a), wherea, \in  A (k=1,...,n), and the elements a,, ...,a, need not be
distinct. Then B, is countable.

Proof That B, is countable is evident, since By = A. Suppose B,_ is
countable (n=2,3,4,...). The elements of B, are of the form

(18) (ba) (be B,_ ae A).

For every fixed b, the set of pairs (b,a) is equivalent to A, and hence
countable. Thus B, is the union of a countable set of countable sets. By
Theorem 2.12, B, is countable.

The theorem follows by induction.
30 PRINCIPLES OF MATHEMATICAL ANALYSIS

Corollary The set d all rational numbers is countable.

Proof We apply Theorem 2.13, with n = 2, noting that every rational r
is of the form b/a, where a and b are integers. The set of pairs (a, b), and
therefore the set of fractions b/a, is countable.

In fact, even the set of all algebraic numbers is countable (see Exer-
cise 2).

That not all infinite sets are, however, countable, is shown by the next
theorem.

2.14 Theorem Let A be the set d all sequences whose elements are the digits 0
and 1. This set A is uncountable.
The elements of A are sequences like 1,0,0, 1,0, 1, 1, 1, ....

Proof Let E be a countable subset of A, and let E consist of the se-
quences Sy, S3,83,.... We construct a sequence § as follows. If the nth
digit in s, is 1, we let the nth digit of s be 0, and vice versa. Then the
sequence s differs from every member of E in at least one place; hence
sc E. But clearly se A, so that Eis a proper subset of A.

We have shown that every countable subset of A is a proper subset
of A. It follows that A is uncountable (for otherwise A would be a proper
subset of A, which is absurd).

The idea of the above proof was first used by Cantor, and is called Cantor's
diagonal process; for, if the sequences sy, §,, $3, ... are placed in an array like
(16), it is the elements on the diagonal which are involved in the construction of
the new sequence.

Readers who are familiar with the binary representation of the real
numbers (base 2 instead of 10) will notice that Theorem 2.14 implies that the
set of all real numbers is uncountable. We shall give a second proof of this
fact in Theorem 2.43.

METRIC SPACES

2.15 Definition A set X, whose elements we shall call points, is said to be a
metric space if with any two points p and q of X there is associated a real
number d(p, q), called the distance from p to g, such that

(a) d(p,q)>0ifp+#q;dp.p)=0;
(6) d(p,q) =d(q.p);
(c) d(p,q)<d(p,r) + dr, gq), for any re X.

Any function with these three properties is called a distance function, or
a metric.
BASIC TOPOLOGY 31

2.16 Examples The most important examples of metric spaces, from our
standpoint, are the euclidean spaces R*, especially R' (the real line) and R? (the
complex plane); the distance in R* is defined by

(19) dx,y) = |x-y| (x, yeR".

By Theorem 1.37, the conditions of Definition 2.15 are satisfied by (19).

It is important to observe that every subset Y of a metric space X is a metric
space in its own right, with the same distance function. For it is clear that if
conditions (a) to (c) of Definition 2.15 hold for p, q, r \in X, they also hold if we
restrict p,q. r to lie in Y.

Thus every subset of a euclidean space is a metric space. Other examples
are the spaces ¥(K) and #2(u), which are discussed in Chaps. 7 and 11, respec-
tively.

2.17 Definition By the segment (a, b) we mean the set of all real numbers x
such that a < x <b.

By the interval [a. b] we mean the set of all real numbers x such that
a<x<b

Occasionally we shall also encounter "half-open intervals’ [a, b) and (a, b];
the first consists of all x such that a < x <b, the second of all x such that
a<x<hbh

Ifa; <b; fori=1,...,k, the set of all points x =(x,, ..., X;) in R* whose
coordinates satisfy the inequalities a; < x; <b; (1 <i<k) is called a k-cell.
Thus a 1-cell is an interval, a 2-cell is a rectangle, etc.

If xe R* and r > 0. the open (or closed) ball B with center at x and radius r
is defined to be the set of all y \in R* such that |y - x| <r (or |y -x|< 7).

We call a set Ec R¥ convex if

X+(1-2)yeE

whenever xe E,ye E, and 0 < A < I.
For example, balls are convex. For if |y -x| <r, |z-x| <r, and
0 < A <1, we have

[dy + (1 ~ Dz -x| = |Ay x) + (1 = Hz - x)|
<Aly-x| +d =Nz-x| <ir+ 1 =Mr
=r.

The same proof applies to closed balls. It is also easy to see that k-cells are
convex.
32 PRINCIPLES OF MATHEMATICAL ANALYSIS

2.18 Definition Let X be a metric space. All points and sets mentioned below
are understood to be elements and subsets of X.

(a) A neighborhood of p is a set N,(p) consisting of all c such that
d(p, gq) < r,for some r > 0. The number r is called the radius of N,(p).

(b) A point p is a limit point of the set E if every neighborhood of p
contains a point q # p such that g \in  E.

(cc) If pe E and p is not a limit point of E, then p is called an isolated
point of E.

(d) Eis closed if every limit point of E is a point of E.

(e) A point p is an interior point of E if there is a neighborhood N ofp
such that N = E.

(f) Eis open if every point of E is an interior point of E.

(g) The complement of E (denoted by E \in )is the set of all points pe X
such that pc E.

(h) Eis perfect if E is closed and if every point of E is a limit point
of E.

(i) E is bounded if there is a real number M and a point g \in X such that
d(p,q)< M for all pe E.

(j) E is dense in X if every point of X is a limit point of E, or a point of
E (or both).

Let us note that in R' neighborhoods are segments, whereas in R? neigh-
borhoods are interiors of circles.
2.19 Theorem Every neighborhood is un open set.

Proof Consider a neighborhood E = N,(p), and let c be any point of E.
Then there is a positive real number 4 such that

d(p,q) =r -h.
For all points s such that d(g, s) < h, we have then
d(p,s) <d(p,q)+ dg, s)<r-h+h=r,
so that s \in E. Thus c is an interior point of E.
2.20 Theorem If p is a limit point of a set E, then every neighborhood of p
contains infinitely many points of E.

Proof Suppose there is a neighborhood N of p which contains only a
finite number of points of E. Let gy,...,g, be those points of N n E,
which are distinct from p, and put

r= min d(p, qm)

I<m<n
BASIC TOPOLOGY 33

[we use this notation to denote the smallest of the numbers d(p, 4), ...,
d(p, q,)]. The minimum of a finite set of positive numbers is clearly posi-
tive, so that r > 0.

The neighborhood N,(p) contains no point gc of E such that q # p,
so that p is not a limit point of E. This contradiction establishes the
theorem.

Corollary A finite point set has no limit points.

221 Examples Let us consider the following subsets of R?:

(a) The set of all complex z such that |z| < I.

(b) The set of all complex z such that |z| < I.

(c) A nonempty finite set.

(d) The set of all integers.

(e) The set consisting of the numbers 1/n(n=1,2,3,...). Let us note
that this set E has a limit point (namely, z =0) but that no point of E is
a limit point of E; we wish to stress the difference between having a limit
point and containing one.

(f) The set of all complex numbers (that is, R?).

(g) The segment (a,b).

Let us note that (d),(e),(g)can be regarded also as subsets of R'.
Some properties of these sets are tabulated below:

Closed Open Perfect Bounded

(a) No Yes No Yes
® Yes No Yes Yes
(© Yes No No Yes
a Yes No No No
(a No No No Yes
0) Yes Yes Yes No
(9) No No Yes

In (g), we left the second entry blank. The reason is that the segment
(a,b) is not open if we regard it as a subset of RZ, but itis an open subset of R".

2.22 Theorem Let {E,} be a (finite or infinite) collection of sets E,. Then
(20) Y Ej = (ED.

Proof Let A and B be the left and right members of (20). If x \in A, then
x c\, E,, hence x c E, for any a, hence x \in E{ forevery a, so that x  [ ES.
Thus A < B.
34 PRINCIPLES OF MATHEMATICAL ANALYSIS

2.23

Conversely, if x \in B, then x \in E for every a, hence x c E, for any o,
hence x c J, Es, so that x \in (UU, E,)*. Thus Bc A.
It follows that A = B.

Theorem A set Eis open if and only if its complement is closed.

Proof First, suppose E \in  is closed. Choose x \in E. Then x c Ec, and x is
not a limit point of E°. Hence there exists a neighborhood N of x such
that En N is empty, that is, N c E. Thus X is an interior point of E,
and E is open.

Next, suppose E is open. Let x be a limit point of E°. Then every
neighborhood of X contains a point of E°, so that x is not an interior point
of E. Since E is open, this means that x \in E°. It follows that Eis closed.

Corollary A set F is closed if and only if its complement is open.

2.24

an

Theorem

(a) For any collection {G,} of open sets, |); G, is open.

(b) For any collection {F,} of closed sets, (a Fy is closed.

(c) For anyfinite collection Gy, ..., G, of open sets, (Vi=1 G; is open.
(d) For anyfinite collection Fy, ..., F, of closed sets,\ {= F} is closed.

Proof Put G =J,G,. If xeG, then xe G, for some a. Since X is an
interior point of G,, X is also an interior point of G, and G is open. This
proves (a).

By Theorem 2.22,

(0 oo) =U FD,

and Fy is open, by Theorem 2.23. Hence (a)implies that (21) is open so
that (, F, is closed.

Next, put H = ()/., G;. For any x \in H, there exist neighborhoods
N; of x, with radii r;, such that N;c G;(i=1,...,n). Put

r=min (ry, ..., 1),
and let N be the neighborhood of x of radius r. Then N c G; fori =,
..,n, so that N c H, and His open.
By taking complements, (d)follows from (c):

(07)

i=1
BASIC TOPOLOGY 35

2.25 Examples In parts (c)and (d)of the preceding theorem, the finiteness of
11
the collections is essential. For let G, be the segment (- = 2) (n=1,2,3,...).

Then G, is an open subset of R*. Put G = (2, G,. Then G consists of a single
point (namely, Xx = 0) and is therefore not an open subset of R.

Thus the intersection of an infinite collection of open sets need not be open.
Similarly, the union of an infinite collection of closed sets need not be closed.

2.26 Definition If X is a metric space, if E c X, and if E' denotes the set of
all limit points of E in X, then the closure of E is the set E=EU E".

2.27 Theorem If X isa metric space and E cc X, then

(a) Eis closed,
(b) E =E if and only if E is closed,
(c) E c F for every closed set F c X such that E cc F.

By (a)and (c), E 1s the smallest closed subset of X that contains E.

Proof

(a) Ifpe Xand pc E thenp is neither a point of E nor a limit point of E.
Hence p has a neighborhood which does not intersect E. The complement
of E is therefore open. Hence E is closed.

(b) If E =E, (a) implies that E is closed. If Eis closed, then E' cE
[by Definitions 2.18(d) and 2.261, hence E =E.

(c) If Fis closed and Fo E, then Fo F', hence Fo E'. Thus Fo E.

2.28 Theorem Let E be a nonempty set of real numbers which is bounded above.
Lety =sup E. ThenyeE. Hence y \in  E if E is closed.

Compare this with the examples in Sec. 1.9.

Proof If y \in E then ye E. Assume yc E. For every h > 0 there exists
then a point x \in E such that y - 2 <x <y, for otherwise y - h would be
an upper bound of E. Thus y is a limit point of E. Hence y \in E.

2.29 Remark Suppose Ec Yc X, where Xis a metric space. To say that E
is an open subset of X means that to each point p \in E there is associated a
positive number r such that the conditions d(p,q) <r, g \in  X imply that q \in E.
But we have already observed (Sec. 2.16) that Y is also a metric space, so that
our definitions may equally well be made within ¥. To be quite explicit, let us
say that E is open relative to Y if to each p \in E there is associated an r > Q such
that gq \in E whenever d(p,q) <r and ge Y. Example 2.21(g) showed that a set
36 PRINCIPLES OF MATHEMATICAL ANALYSIS

may be open relative to Y without being an open subset of X. However, there
is a simple relation between these concepts, which we now state.

2.30 Theorem Suppose Y <= X. A subset E of Y is open relative to Y if and
only if E = Y nn G for some open subset G of X.

Proof Suppose E is open relative to Y. To each p \in E there is a positive
number r, such that the conditions d(p,q) <r,,qe Y imply that ge E.
Let ¥, be the set of all ge X such that d(p, q) <r,, and define
G=V,.
peE

Then G is an open subset of X, by Theorems 2.19 and 2.24.

Since pe V, forall pe E, itis clear that Ec Gn Y.

By our choice of ¥,, we have ¥, n Y = E for every p \in E, so that
Gn Yc E. Thus E=G n Y, and one half of the theorem is proved.

Conversely, if G is open in X and E=G Nn Y, every pe FE has a
neighborhood ¥, = G. Then ¥V, n Y < E, so that E is open relative to Y.

COMPACT SETS

2.31 Definition By an open cover of a set E in a metric space X we mean a
collection {G,} of open subsets of X such that £ < | J, G,.

2.32 Definition A subset K of a metric space X is said to be compact if every
open cover of K contains a finite subcover.

More explicitly, the requirement is that if {G,} is an open cover of XK, then
there are finitely many indices a, ..., a, such that

Kc G, uu,

The notion of compactness is of great importance in analysis, especially
in connection with continuity (Chap. 4).

It is clear that every finite set is compact. The existence of a large class of
infinite compact sets in R* will follow from Theorem 2.41.

We observed earlier (in Sec. 2.29) that if £ « Y < X, then E may be open
relative to Y without being open relative to X. The property of being open thus
depends on the space in which E is embedded. The same is true of the property
of being closed.

Compactness, however, behaves better, as we shall now see. To formu-
late the next theorem, let us say, temporarily, that K is compact relative to X if
the requirements of Definition 2.32 are met.
BASIC TOPOLOGY 37

2.33 Theorem Suppose K < Y < X. Then K is compact relative to X if and
only if K is compact relative to Y.

By virtue of this theorem we are able, in many situations, to regard com-

pact sets as metric spaces in their own right, without paying any attention to
any embedding space. In particular, although it makes little sense to talk of
open spaces, or of closed spaces (every metric space X is an open subset of itself,
and is a closed subset of itself), it does make sense to talk of compact metric
spaces.

(22)

(23)

2.34

2.35

Proof Suppose K is compact relative to X, and let {V,} be a collection
of sets, open relative to Y, such that K = {J, V,. By theorem 2.30, there
are sets G,, open relative to X, such that V, = Y n G,, for all a; and since
K is compact relative to X, we have

Kc Gy uu,

for some choice of finitely many indices a, ..., «,. Since Kc Y, (22)
implies

KcV, u-ul,.

This proves that K is compact relative to Y.

Conversely, suppose K is compact relative to Y, let {G,} be a col-
lection of open subsets of X which covers K, and put ¥, = Y nn G,. Then
(23) will hold for some choice of ay, ...,a,; and since V, = G,, (23)
implies (22).

This completes the proof.

Theorem Compact subsets of metric spaces are closed.

Proof Let K be a compact subset of a metric space X. We shall prove
that the complement of K is an open subset of X.

Suppose pe X, pc K. If ge K, let V, and W, be neighborhoods of p
and g, respectively, of radius less than 4d(p, q) [see Definition 2.18(a)].
Since K is compact, there are finitely many points gy, ..., g, in K such that

KecW, vuuWw, =W

If V=V, n:-nV,, then Vis a neighborhood of p which does not
intersect W. Hence V < Kc, so that p is an interior point of K°. The
theorem follows.

Theorem Closed subsets of compact sets are compact.

Proof Suppose F< K c X, Fis closed (relative to X), and K is compact.
Let {V,} be an open cover of F. If Fcis adjoined to {V,}, we obtain an
38 PRINCIPLES OF MATHEMATICAL ANALYSIS

open cover Q of K. Since K is compact, there is a finite subcollection ®
of Q which covers XK, and hence F. If Fcis a member of ®, we may remove
it from ® and still retain an open cover of F. We have thus shown that a
finite subcollection of {V,} covers F.

Corollary If Fis closed and K is compact, then F n K is compact.

Proof Theorems 2.24(b) and 2.34 show that Fn K is closed; since
Fn Kc K, Theorem 2.35 shows that Fn K is compact.

2.36 Theorem If{K,} is a collection of compact subsets of a metric space X such
that the intersection of every finite subcollection of {K,} is nonempty, then (| K,
is nonempty.

Proof Fix a member K, of {K,} and put G, = K. Assume that no point
of K; belongs to every K,. Then the sets G, form an open cover of Kj;
and since K, is compact, there are finitely many indices a, ..., a, such
that K; « G,, U *** U G,,. But this means that

KinK,n nk,

is empty, in contradiction to our hypothesis.

Corollary If {K,} is a sequence of nonempty compact sets such that K, > K,, ,,
(n=1,2,3,...), then(\§ K, is not empty.

2.37 Theorem If E is an infinite subset of a compact set K, then E has a limit
point in K.

Proof If no point of K were a limit point of E, then each g \in K would
have a neighborhood V, which contains at most one point of E (namely,
gq, if ge E). It is clear that no finite subcollection of {V;} can cover Ej
and the same is true of K, since E - K. This contradicts the compactness
of K.

2.38 Theorem If {I,} is a sequence of intervals in R', such that I,>1I,.,
(n=1,2,3,...), then NT I, is not empty.

Proof If I, =[a,, b,)], let E be the set of all a,. Then E is nonempty and
bounded above (by b;). Let x be the sup of E. If m and n are positive
integers, then

4, S Api < bmn <b,

so that x < b,, for each m. Since it is obvious that a, < x, we see that
xel,form=1,2,3,....
2.39

BASIC TOPOLOGY 39

Theorem Let k be a positive integer. If {L) is a sequence d k-cells such

that Lo 71, (n=1,2,3,...), then NT L is not empty.

2.40

Proof Let I, consist of all points x = (x,, ..., X;) such that
a,;<x;<b,; (1<j<k;n=123,..),

and put I, ; =[a,; b,;]. For each j, the sequence {/,;} satisfies the
hypotheses of Theorem 2.38. Hence there are real numbers xJ(I <j<k)
such that

a, ;<xt<h,;, (I<jskin=123..).

nj =

Setting x* = (xT, ..., xy), we see that x*el, for n=1,2,3,.... The
theorem follows.

Theorem Every k-cell is compact.

Proof Let I be a k-cell, consisting of all points Xx = (X,, ..., X;) such
that a, <x; <b; (1 <j<k). Put

Then |x -y| <4,ifxel,yel

Suppose, to get a contradiction, that there exists an open cover {G,)
of I which contains no finite subcover of I. Put c; =(a; + b;)/2. The
intervals [a;, c] and [c;, b;] then determine 2 k-cells Q; whose union is I.
At least one of these sets Q;, call it I,, cannot be covered by any finite
subcollection of {G,) (otherwise I could be so covered). We next subdivide
I and continue the process. We obtain a sequence {I,) with the following
properties:

(a ILL

(b) 1, is not covered by any finite subcollection of {G,);
(c) ifxel,andyel,, then [x -y| <27"4.

By (a) and Theorem 2.39, there is a point x* which lies in every I,.
For some a,x*e \in G,. Since G, is open, there exists r > 0 such that
|y - x*| <r implies that ye G,. If n is so large that 27"3 <r (there is
such an n, for otherwise 2' < d/r for all positive integers n, which is
absurd since R is archimedean), then (c) implies that I, = G,, which con-
tradicts (b).

This completes the proof.

The equivalence of (a) and (b) in the next theorem is known as the Heine-

Borel theorem.
40 PRINCIPLES OF MATHEMATICAL ANALYSIS

2.41 Theorem Ifa set E in R¥ has one d thefollowing three properties, then it
has the other two:

(a) Eis closed and bounded.
(b) Eis compact.
(c) Every infinite subset d Ehas a limit point in E.

Proof If (a) holds, then E < I for some k-cell I, and (b) follows from
Theorems 2.40 and 2.35. Theorem 2.37 shows that (b) implies (c). It
remains to be shown that (c) implies (a).

If E is not bounded, then E contains points x, with

|x,| >n n=1273..).

The set S consisting of these points x, is infinite and clearly has no limit
point in R¥, hence has none in E. Thus (c) implies that E is bounded.

If Eis not closed, then there is a point x, \in R¥ which is a limit point
of E but not a point of E. For n=1,2,3,..., there are points x, \in E
such that (x, - Xo| <1/n. Let S be the set of these points x . Then S is
infinite (otherwise |% - X,| would have a constant positive value, for
infinitely many n), S has X, as a limit point, and S has no other limit
point in R¥. For if y \in R*, y # Xo, then

|X, = ¥| = |X -¥| - | Xs - Xo]

1 1
2 [xo - yl -, 251% yl
for all but finitely many n; this shows that y is not a limit point of S
(Theorem 2.20).
Thus S has no limit point in E; hence E must be closed if (c) holds.

We should remark, at this point, that (b) and (c) are equivalent in any
metric space (Exercise 26) but that (a) does not, in general, imply (b) and (c).
Examples are furnished by Exercise 16 and by the space #2, which is dis-
cussed in Chap. 11.

2.42 Theorem (Weierstrass) Every bounded infinite subset  R* has a limit
point in R*.

Proof Being bounded, the set Ein question is a subset of a k-cell I = R¥.
By Theorem 2.40, I is compact, and so E has a limit point in I, by
Theorem 2.37.
BASIC TOPOLOGY 41

PERFECT SETS

243 Theorem LetP be a nonempty perfect set in R*. Then P is uncountable.

Proof Since P has limit points, P must be infinite. Suppose P is count-
able, and denote the points of P by x,, X,, X3,.... We shall construct a
sequence {V, ,of neighborhoods, as follows.

Let ¥, be any neighborhood of x,. If ¥; consists of all y \in R* such
that |y - x, | <r, the closure V; of V, is the set of all ye R*such that
ly -x| <r.

Suppose V, has been constructed, so that V, nn P is not empty. Since
every point of P is a limit point of P, there is a neighborhood V, ,, such
that () Vo, = V,, (ii) x, c V,.1, (ii) V,+, nP is not empty. By (iii),
V, +1 satisfies our induction hypothesis, and the construction can proceed.

Put K, = V, n P. Since V, is closed and bounded, V, is compact.
Since x, c K,,,, no point of P lies in NT K,, Since K, < P, this implies
that (\¥ K, js empty. But each K, is nonempty, by (iii), and K, » K,,,,
by (i); this contradicts the Corollary to Theorem 2. 36.

Corollary Ecery interval [a, b] (a <b) is uncountable. In particular, t/e set
all real numbers is uncountable.

2.44 The Cantor set The set which we are now going to construct shows
that there exist perfect sets in R! which contain no segment.

Let E, be the interval [0, 1]. Remove the segment (4, ), and let E; be
the union of the intervals

[0,3] [3 11.

Remove the middle thirds of these intervals, and let E, be the union of the
intervals

[0,3] [3,3]. [5 3). [85 1].
Continuing in this way, we obtain a sequence of compact sets £,, such that

(a Ei2E E>".

H

(b) E, is the union of 2” intervals, each of length 37".
The set

p= NE

is called the Cantor set. P is clearly compact, and Theorem 2.36 shows that P
is not empty.
42 PRINCIPLES OF MATHEMATICAL ANALYSIS

No segment of the form

(2 5)

24

3m ’ 3m
where k and m are positive integers, has a point in common with P. Since every
segment (a, ff) contains a segment of the form (24), if

fa

ITM <
6

’
P contains no segment.

To show that P is perfect, it is enough to show that P contains no isolated
point. Let x \in P, and let S be any segment containing x. Let J, be that interval
of E, which contains x. Choose n large enough, so that J, = S. Let x, be an
endpoint of I,, such that x, # x.

It follows from the construction of P that x, \in P. Hence x is a limit point
of P, and P is perfect.

One of the most interesting properties of the Cantor set is that it provides
us with an example of an uncountable set of measure zero (the concept of
measure will be discussed in Chap. 11).

CONNECTED SETS

2.45 Definition Two subsets A and B of a metric space X are said to be
separated if both A n B and A n B are empty, i.e., if no point of A lies in the
closure of B and no point of B lies in the closure of A.

A set E < Xis said to be connected if E is not a union of two nonempty
separated sets.

2.46 Remark Separated sets are of course disjoint, but disjoint sets need not
be separated. For example, the interval [0,1] and the segment (1, 2) are not
separated, since 1 is a limit point of (I, 2). However, the segments (0, /) and
(1. 2) are separated.

The connected subsets of the line have a particularly simple structure:

2.47 Theorem A subset E of the real line R" is connected if and only if it has the
following property: If xe E, ye E, and x < z <Y, then Z \in  E.

Proof If there exist x \in  E. y \in E, and some z \in (x, y) such that z c E, then
E = A, u B, where

A,= En (-o,z), B,= En (z, ©).
BASIC TOPOLOGY 43

Since x \in A, and y \in B,, A and B are nonempty. Since A, = (-0, z)and
B, = (z, ©), they are separated. Hence E is not connected.

To prove the converse, suppose Eis not connected. Then there are
nonempty separated sets A and B such that A u B=E. Pick x \in  A, y \in  B,
and assume (without loss of generality) that x <y. Define

z=sup(A nx, y]).

By Theorem 2.28, 7 \in A; hence z c B. In particular, x < 7 <y.

If 7 c A, it follows that Xx < z < y and z c E.

If z \in  A, then 7cB, hence there exists z, such that z<z, <y and
72, c B. Thenx<z, <yandz cE.

EXERCISES

1.

Prove that the empty set is a subset of every set.

2. A complex number is said to be algebraic if there are integers ao, ..., a,, not all

[NY Ir Sa)

zero, such that

ap" +a" + +a,_,z+a,=0,

Prove that the set of all algebraic numbers is countable. Hint: For every positive
integer N there are only finitely many equations with

n+ lao] + |a,| +-+ |a.| =N.

. Prove that there exist real numbers which are not algebraic.

. Is the set of all irrational real numbers countable?

. Construct a bounded set of real numbers with exactly three limit points.

. Let E' be the set of all limit points of a set E. Prove that E' is closed. Prove that

E and E have the same limit points. (Recall that E= EU E'.) Do Eand E'always
have the same limit points?

. Let A,, A;, As, ... be subsets of a metric space.

(a) If B, = |Ji=1 Ai, prove that B, = Ji, 4, forn=1,2,3, ....
(b) If B= J, A:, prove that B> J 4.
Show, by an example, that this inclusion can be proper.

. Is every point of every open set E < R? a limit point of E? Answer the same

question for closed sets in R%.

. Let E° denote the set of all interior points of a set E. [See Definition 2,18(e);

E” is called the interior of E.]

(a) Prove that E” is always open.

(b) Prove that E is open if and only if E” = E.

(c) If G< E and G is open, prove that G < E°.

(d) Prove that the complement of E° is the closure of the complement of E.
(c) DoE and E always have the same interiors?

(f) Do E and E” always have the same closures?
4

10.

11.

PRINCIPLES OF MATHEMATICAL ANALYSIS

Let X be an infinite set. Forp \in X and g \in X, define
1 (fp#q)

d(p,q)= A
0 (if p = q).

Prove that this is a metric. Which subsets of the resulting metric space are open?
Which are closed? Which are compact?
For x \in R' and y \in R, define

dix, y) = (x =»)?
dax, y= Vx - yl,
d(x, yy -| x? - y?,
da(x, y) = |x -2y|,

dx, y) = X=?

T+ |x-y|
Determine. for each of these, whether it is a metric or not.
12. Let K < R* consist of 0 and the numbers 1/n, forn=1,2, 3, .... Prove that Kis

18.
19.

20.

21.

compact directly from the definition (without using the Heine-Borel theorem).

. Construct a compact set of real numbers whose limit points form a countable set.
. Give an example of an open cover of the segment (0, 1) which has no finite sub-

cover.

. Show that Theorem 2.36 and its Corollary become false (in R', for example) if the

word "compact" is replaced by "closed" or by "bounded."

. Regard Q, the set of all rational numbers, as a metric space, with d(p,q) =|p - q].

Let E be the set of all p \in Q such that 2 <p? <3. Show that E is closed and
bounded in Q, but that Eis not compact. Is E open in Q?

. Let E be the set of all x \in [0, 1] whose decimal expansion contains only the digits

4 and 7. Is E countable? Is E dense in [0, 1]? Is E compact? Is E perfect?

Is there a nonempty perfect set in R' which contains no rational number?

(a) If A and B are disjoint closed sets in some metric space X, prove that they
are separated.

(b) Prove the same for disjoint open sets.

(c) Fixpe X, 8 >0, define A to be the set of all g \in X for which d(p, q) <3, define
B similarly, with > in place of <<. Prove that A and B are separated.

(d) Prove that every connected metric space with at least two points is uncount-
able. Hint: Use (c).

Are closures and interiors of connected sets always connected? (Look at subsets
of R?.)

Let A and B be separated subsets of some R*, suppose a \in A, b \in  B, and define

pt)=(1-1ta+1tb
for fe R'. Put Ag =p~'(A), Bo =p '(B). [Thus t \in  Aq if and only if p(t) A]
22.

23.

24.

25.

26.

27.

28.

29.

BASIC TOPOLOGY 45

(a) Prove that Ao and By are separated subsets of R'.

(b) Prove that there exists Zo \in (0, 1) such that p(to) c AU B.

(c) Prove that every convex subset of R* is connected.

A metric space is called separable if it contains a countable dense subset. Show
that R* is separable. Hint: Consider the set of points which have only rational
coordinates.

A collection {¥,} of open subsets of X is said to be a base for X if the following
is true: For every x \in X and every open set G < X such that x \in G, we have
x \in V, © G for some a. In other words, every open set in X is the union of a
subcollection of {V.}.

Prove that every separable metric space has a countable base. Hint: Take

all neighborhoods with rational radius and center in some countable dense subset
of X.
Let X be a metric space in which every infinite subset has a limit point. Prove that
Xis separable. Hint: Fix 6 >0, and pick x; \in X. Having chosen Xi, ..., x, \in X,
choose x; \in X, if possible, so that d(x, x;,,)>6 for i=1,...,j. Show that
this process must stop after a finite number of steps, and that X can therefore be
covered by finitely many neighborhoods of radius 8. Take6 =1/n(n=1,2,3,...),
and consider the centers of the corresponding neighborhoods.

Prove that every compact metric space K has a countable base, and that K is
therefore separable. Hint: For every positive integer n, there are finitely many
neighborhoods of radius 1/n whose union covers K.

Let X be a metric space in which every infinite subset has a limit point. Prove
that X is compact. Hint: By Exercises 23 and 24, X has a countable base. It
follows that every open cover of X has a countable subcover {G.},n=1,2,3,....
If no finite subcollection of {G.} covers X, then the complement F, of G; U .** U G,
is nonempty for each n, but (}F, is empty. If Eis a set which contains a point
from each F,, consider a limit point of E, and obtain a contradiction.

Define a point p in a metric space X to be a condensation point of a set E< X if
every neighborhood of p contains uncountably many points of E.

Suppose E © R*, E is uncountable, and let P be the set of all condensation
points of E. Prove that P is perfect and that at most countably many points of E
are not in P. In other words, show that P° n E is at most countable. Hint: Let
{V,; be a countable base of R*, let i be the union of those V, for which E n V,,
is at most countable, and show that P = W*.

Prove that every closed set in a separable metric space is the union of a (possibly
empty) perfect set and a set which is at most countable. (Corollary: Every count-
able closed set in R* has isolated points.) Hint: Use Exercise 27.

Prove that every open set in R* is the union of an at most countable collection of
disjoint segments. Hint: Use Exercise 22.
46 PRINCIPLES OF MATHEMATICAL ANALYSIS

30. Imitate the proof of Theorem 2.43 to obtain the following result:

If R*=(J{F,, where each F, is a closed subset of R*, then at least one F,
has a nonempty interior.

Equivalent statement: If Gn is a dense open subset of R*, for n =1,2,3,...,
then ()£G. is not empty (in fact, it is dense in KR).

(This is a special case of Baire's theorem; see Exercise 22, Chap. 3, for the general
case.)
3

NUMERICAL SEQUENCES AND SERIES

As the title indicates, this chapter will deal primarily with sequences and series
of complex numbers. The basic facts about convergence, however, are just as
easily explained in a more general setting. The first three sections will therefore
be concerned with sequences in euclidean spaces, or even in metric spaces.

CONVERGENT SEQUENCES

3.1 Definition A sequence {p,} in a metric space X is said to converge if there
is a point p \in X with the following property: For every \in > O there is an integer
N such that n > N implies that d(p,, p) <e. (Here d denotes the distance in X.)

In this case we also say that {p,} converges to p, or that p is the limit of
{p.} [see Theorem 3.2(b)], and we write p, = p, or

lim p, =p.

n-+oo

If {p,) does not converge, it is said to diverge.
48 PRINCIPLES OF MATHEMATICAL ANALYSIS

It might be well to point out that our definition of "convergent sequence"
depends not only on {p,) but also on X; for instance, the sequence {1/n} con-
verges in R* (to 0), but fails to converge in the set of all positive real numbers
[with d(x,y) = |x -y|]. In cases of possible ambiguity, we can be more
precise and specify "convergent in X'’ rather than "convergent."

We recall that the set of all points p, (n=1,2, 3,...) is the range of {p,).
The range of a sequence may be a finite set, or it may be infinite. The sequence
{p,) is said to be bounded if its range is bounded.

As examples, consider the following sequences of complex numbers
(that is, X = R?):

(a) Ifs,=1/n, then lim, s, = 0; the range is infinite, and the sequence
is bounded.

(b) If s,=n? the sequence {s, is unbounded, is divergent, and has
infinite range.

(c) If s,=1+[(- 1)"/n], the sequence {s,} converges to 1, is bounded,
and has infinite range.

(d) If s, =i" the sequence {s,} is divergent, is bounded, and has finite
range.

(e) Ifs,=1m=1,2,3,...), then {s,} converges to 1, is bounded, and
has finite range.

We now summarize some important properties of convergent sequences
in metric spaces.

3.2 Theorem Let{p,) be a sequence in a metric space X.

(a) {p,) converges to p \in X if and only if every neighborhood of p contains
p, for all butfinitely many n.

(b) IfpeX.p' eX, andif {p,} converges to p and to p', then p' =p.

(c) E{p,) converges, then {p,} is bounded.

(d) EFEc Xandifpisa limit point d E, then there is a sequence{p,) in E

such that p = limp, .

n= ao
Proof (a) Suppose p, »p and let V be a neighborhood of p. For
some c > 0, the conditions d(g,p) <&,qe X imply q \in V. Correspond-
ing to this &, there exists N such that n> N implies d(p,,p) <s Thus
n> N implies p, \in V.

Conversely, suppose every neighborhood of p contains all but
finitely many of the p,. Fix c > 0, and let V be the set of all q \in X such
that d(p,q) <e. By assumption, there exists N (corresponding to this V)
such that p, \in V if n> N. Thus d(p,,p) <é& if n> N; hence p, -p.
NUMERICAL SEQUENCES AND SERIES 49

(hb) Lete>0 be given. There exist integers N, N' such that
E
nz=N implies d(Ps,p)< 3

E

n=N' implies d(p,,p') <5

2
Hence if n > max (N, N'), we have

d(p, p’) < d(p, pa) + d(p,, p) <e.

Since E was arbitrary, we conclude that d(p, p') = 0.
(c) Suppose p, »p. There is an integer N such that n> N
implies d(p,,p)<1. Put

r=max{l,d(p,,p), ...,d(py,P)}.

Then d(p,,p)<rforn=1,23,....

d) For each positive integer n, there is a point p, \in E such that
d(p,,p) <1/n. Given E>0, choose N so that Ne>1. If n>N, it
follows that d(p,, p) <e. Hence p, -p.

This completes the proof.

For sequences in R¥ we can study the relation between convergence, on

the one hand, and the algebraic operations on the other. We first consider
sequences of complex numbers.

3.3 Theorem Suppose {s.}, {t.} are complex sequences, and lim, s,=s,

lirn,,,

t, =1t. Then

(a) im(s,+ct)=s5+1;

noo

(b) lim cs, = cs, lirn (cts) =c+s, for any number c;

Hoc n-o
(c) lim su, = st;

n-oc

| |
(d) lim - =~, provided s, #0 (n=1.2,3,...), and s #0.
s

n= ow Sn
Proof

(a) Given c > 0, there exist integers Ny, N, such that
. . E
n>N, implies |s,- 5] <3

E
n>N, implies |[t - | <3
50 PRINCIPLES OF MATHEMATICAL ANALYSIS

If N = max (N,, N,), then n > N implies
[p+ t)- (+0) <|s,-s| + |, -t] <e.
This proves (a). The proof of (b)is trivial.
(c) We use the identity
a) Sul, - St = (8, - S)(t, - t)+ s(t, - 1) + t(s, - 5).
Given & > 0, there are integers Ny, N, such that
n>N, implies |[s,-s| < Je
n>N, implies |1, -1|< Je
If we take N = max (N,, N,), n > N implies
(5, = $)(tn - | <,
so that

lim (s, - s)(t, - t)=0.

We now apply (a)and (b)to (1), and conclude that

lim (s,t, - st)=0.

now
(d) Choosing m such that [s, - s| <%[s| if n> m, we see that
Is.| > ls] (mzm)
Given c > 0, there is an integer N > m such that » > N implies
|s, - s| <3%|s]|%.

Hence, for n > N,

2
STE sl<e

5,5

34 Theorem
(a) Suppose x, eR'(n=123,..) and
X= (Cg py uns Opn)
Then {x,} converges to x = (or, ..., un) if and only if
a lima, =o; (1<j<k).

nw
NUMERICAL SEQUENCES AND SERIES 51

(b) Suppose {x,), {y.} are sequences in R¥,{B,} is a sequence of real numbers,
and X, = x,y, =» y, B, =f. Then

lim(x, +y,)=x+y, limx, y,=x.y, lim §, x, = fx.
n-aow n=o

noo

Proof
(a) If x,- x, the inequalities

[o- < |x, =x,
which follow immediately from the definition of the norm in R*, show that
(2) holds.

Conversely, if (2) holds, then to each & >0 there corresponds an

integer N such that n > N implies

&
Vk

lo, - a] <

(1<j<k).
Hence n > N implies

: 2
2 lat; - ol |

ji=1

x= x =|

so that x,,- x. This proves (a).
Part (b) follows from (a)and Theorem 3.3.

SUBSEQUENCES

3.5 Definition Given a sequence {p,/, consider a sequence {n,) of positive

integers, such that n, <n, <n, <.... Then the sequence {p,} is called a
subsequence of {p,}. If {p,} converges, its limit is called a subsequential limit
of {p}.

It is clear that {p,} converges to p if and only if every subsequence of

{p,,Jconverges to p. We leave the details of the proof to the reader.

3.6 Theorem

(a) If {ps} is a sequence in a compact metric space X, then some sub-
sequence of {p,) converges to a point of X.
(b) Every bounded sequence in R¥ contains a convergent subsequence.
52 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof

(a) Let E be the range of {p,). 1f E is finite then there is a p \in  E and a
sequence {n;} with ny <n, <ny <++-, such that

Png = Pn, =""" =P.

The subsequence {p,,} so obtained converges evidently to p.

If E is infinite, Theorem 2.37 shows that E has a limit point p \in X.
Choose n, so that d(p, p,,) < I. Having chosen n,, ..., n;_;, we see from
Theorem 2.20 that there is an integer n; > n;_, such that d(p, p,,) <1/i.
Then {p,} converges to p.

(b) This follows from (a), since Theorem 2.4] implies that every bounded
subset of R* lies in a compact subset of R*.

3.7 Theorem The subsequential limits of a sequence {p,) in a metric space X
form a closed subset of X.

Proof Let E* be the set of all subsequential limits of {p,) and let c be a
limit point of E* We have to show that g \in E*.

Choose n, so that p, # g. (If no such n, exists, then E* has only
one point, and there is nothing to prove.) Put 6 =d(g, p,). Suppose
n,, ...,n;_y are chosen. Since cq is a limit point of E*, there is an x \in E*
with d(x,q)<27'6. Since x \in E* there is an n;>n;_; such that
d(x, p,) <2~'6. Thus

dg, pa) <2'778
for i=1,2,3,.... This says that {p,} converges to g. Hence q \in E*.

CAUCHY SEQUENCES

3.8 Definition A sequence {p,) in a metric space X is said to be a Cauchy
sequence if for every &c > O there is an integer N such that d(p,, p,,) <eifn = N
and m > N.

In our discussion of Cauchy sequences, as well as in other situations
which will arise later, the following geometric concept will be useful.

3.9 Definition Let E be a nonempty subset of a metric space X, and let S be
the set of all real numbers of the form d(p, c), with p \in E and q \in E. The sup
of Sis called the diameter of E.
NUMERICAL SEQUENCES AND SERIES 53

If{p,} is a sequence in Xand if Ey consists of the POINtS Py, Px 1s PNs2y ves

it is clear from the two preceding definitions that {p,} is a Cauchy sequence
f and only if

lim diam Ey = 0.

Now

3.10 Theorem

311

(a) If E is the closure of a set E in a metric space X, then
diam E = diam E.
(b) If K, is a sequence of compact sets in X such that K,> K,.,
(n=1,2,3,...) and if
lim diam K,, = 0,

n= 00
then NK. consists of exactly one point.
Proof
(a) Since Ec E, it is clear that
diam E < diam E.
Fix £ > 0, and choose p \in E, q \in E. By the definition of E, there are
points p', c', in E such that d(p, p')<c,d(q,q') < e. Hence
dp, q) <d(p.p') + dp’ q') + dq’, q)
<2e+d(p',q')<2e+ diam E.
It follows that
diam E < 2c + diam E,

and since & was arbitrary, (a)is proved.

(hb) Put K= NK, By Theorem 2.36, K is not empty. If K contains
more than one point, then diam K > 0. But for each n, XK, = K, so that
diam KX, > diam K. This contradicts the assumption that diam K, -0.

Theorem

(a) Inany metric space X, every convergent sequence is a Cauchy sequence.

(b) If X is a compact metric space and if {p,} is a Cauchy sequence in X,
then {p,) converges to some point of X.

(c) In R*, every Cauchy sequence converges.

Note: The difference between the definition of convergence and
the definition of a Cauchy sequence is that the limit is explicitly involved
in the former, but not in the latter. Thus Theorem 3.11(b) may enable us
54 PRINCIPLES OF MATHEMATICAL ANALYSIS

3)

to decide whether or not a given sequence converges without knowledge
of the limit to which it may converge.

The fact (contained in Theorem 3.11) that a sequence converges in
R* if and only if it is a Cauchy sequence is usually called the Cauchy
criterion for convergence.

Proof

(a) If p,->p and if c > 0, there is an integer N such that d(p, p,) <  \in 
for all n> N. Hence

d(Pns Pm) < d(Pn, P) + A(p, Pm) <2e

as soon as # > N and m > N. Thus {p,} is a Cauchy sequence.

(b) Let {p,} be a Cauchy sequence in the compact space X. For
N=1,273,..., let Ey be the set consisting of PN, Py+1s PN+2s-=+
Then

lim diam Ey = 0,

Now
by Definition 3.9 and Theorem 3.10(a). Being a closed subset of the
compact space X, each Ey is compact (Theorem 2.35). Also Ey © Ey, 1,
so that Ex © Ey+y.

Theorem 3.10(b) shows now that there is a unique p \in X which lies
in every Ey.

Let c>0 be given. By (3) there is an integer Ny such that
diam Ey <e if N>N,. Since p \in Ey, it follows that d(p,q) <e for
every q \in  Ey, hence for every qe Ey. In other words, d(p, p,) <c if
n > Ny. This says precisely that p, - p.

(c) Let {X,} be a Cauchy sequence in R*. Define Ey as in (b), with x;
in place of p;. For some N, diam Ey < 1. The range of {x,} is the union
of Ey and the finite set {Xy,...,Xy_;}. Hence {x,) is bounded. Since
every bounded subset of R* has compact closure in R* (Theorem 2.41),
(c) follows from (b).

3.12 Definition A metric space in which every Cauchy sequence converges is
said to be complete.

Thus Theorem 3.11 says that all compact metric spaces and all Euclidean

spaces are complete. Theorem 3.11 implies also that every closed subset £ of a
complete metric space X is complete. (Every Cauchy sequence in E is a Cauchy
sequence in X. hence it converges to some p \in X, and actually p \in E since E is
closed.) An example of a metric space which is not complete is the space of all
rational numbers, with d(x,y) = |x -y|.
NUMERICAL SEQUENCES AND SERIES 55

Theorem 3.2(c) and example (d) of Definition 3./ show that convergent
sequences are bounded, but that bounded sequences in R¥ need not converge.
However, there is one important case in which convergence is equivalent to
boundedness; this happens for monotonic sequences in R!.

3.13 Definition A sequence {s,} of real numbers is said to be
(a) monotonically increasing if 5, < §,.1 (n=1,2,3,...);
(6) monotonically decreasing if 8, > $,41 (n=1,2,3,...).

The class of monotonic sequences consists of the increasing and the
decreasing sequences.

3.14 Theorem Suppose {S,} is monotonic. Then {s,) converges if and only if it
is bounded.

Proof Suppose s, < 5,4, (the proof is analogous in the other case).
Let E be the range of {s,}. If {s,} is bounded, let s be the least upper
bound of E. Then

Ss, <8 n=1,2,3..).
For every E > 0, there is an integer N such that
s-e<sy<s,

for otherwise s - &c would be an upper bound of E. Since {s,} increases,
n > N therefore implies

s-e<s5, <5,

which shows that {s,} converges (to s).
The converse follows from Theorem 3.2(c).

UPPER AND LOWER LIMITS

3.15 Definition Let {s,} be a sequence of real numbers with the following
property: For every real M there is an integer N such that n > N implies
S, > M. We then write

Sp, - + 00.
Similarly, if for every real M there is an integer N such that n > N implies
5, < M, we write
56 PRINCIPLES OF MATHEMATICAL ANALYSIS

It should be noted that we now use the symbol - (introduced in Defini-
tion 3.1) for certain types of divergent sequences, as well as for convergent
sequences, but that the definitions of convergence and of limit, given in Defini-
tion 3.1, are in no way changed.

3.16 Definition Let {s,} be a sequence of real numbers. Let E be the set of
numbers x (in the extended real number system) such that s, - x for some
subsequence {s, }. This set E contains all subsequential limits as defined in
Definition 3.5, plus possibly the numbers +00, - 00.

We now recall Definitions 1.8 and 1.23 and put

s* =supE,
Sy = inf E.

The numbers s*, s, are called the upper and lower limits of {s,}; we use the
notation
lim sup s, = s*, lim inf s, = sx.
n-w n- oc
3.17 Theorem Let {s,} be a sequence of real numbers. Let E and s* have the
same meaning as in Definition 3.16. Then s* has the following two properties:

(a) s*eE.
(b) If x > s*, there is an integer N such that n > N implies s,, < X.

Moreouer, s* is the only number with the properties (a) and (b).

Of course, an analogous result is true for sy.
Proof

(a) Ifs* = +00, then Eis not bounded above; hence {s,} is not bounded
above, and there is a subsequence {s,, } such that s,, - + co.

If s* is real, then Eis bounded above, and at least one subsequential
limit exists, so that (a) follows from Theorems 3.7 and 2.28.

If s* = - co, then E contains only one element, namely -co, and
there is no subsequential limit. Hence, for any real M, s, > M for at
most a finite number of values of n, so that 5, =» - oo.

This establishes (a) in all cases.

(b) Suppose there is a number x >s* such that s, > x for infinitely
many values of n. In that case, there is a number y \in E such that
y =x > s*, contradicting the definition of s*.

Thus s* satisfies (a) and (b).

To show the uniqueness, suppose there are two numbers, p and q,
which satisfy (a) and (b), and suppose p <q. Choose x such thatp <x <q.
Sincep satisfies (b), we have s, < x for n = N. But then q cannot satisfy (a).
NUMERICAL SEQUENCES AND SERIES 57

3.18 Examples

(a) Let {s,} be a sequence containing all rationals. Then every real
number is a subsequential limit, and
lim sup s, = + 0, lim inf s, = - co.

(b) Lets,=(-=1"/[1 + (1/n)]. Then
limsups, =1, liminfs, = -1.

(c) For a real-valued sequence {s,}, lim s, = s if and only if

lim sup 5, = lim inf s, = 5.
n- wo n-o
We close this section with a theorem which is useful, and whose proof is
quite trivial:

3.19 Theorem Ifs,<t, for n> N, where N is fixed, then

lim inf s, < lim infc,,

n= n- oo

lim sup s, < lim sup #,.

n= n-o

SOME SPECIAL SEQUENCES

We shall now compute the limits of some sequences which occur frequently.
The proofs will all be based on the following remark: If 0 < x, <s, for n > N,
where N is some fixed number, and if s, -0, then x, -0.

3.20 Theorem

(a If p>0, then lim = =0.

noo

() Ifp>0, thenlim Jp = 1.

(© limYn=1.

n
d) If p> 0 anda is real, then lim - =0.
d Ifp lim

(e) If |x| <1, then lim x" = 0.

n= ©
58 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof

(a) Take n> (1/e)"/?. (Note that the archimedean property of the real
number system is used here.)

(by If p>1, put x, =p - 1. Then x, >0, and, by the binomial
theorem,
1 + nx, I a + x)! =p,
so that
0< Xp < r-1
n

Hence x, »0. Ifp = I, (b) is trivial, and if 0 <p < 1, the result is obtained
by taking reciprocals.

(c) Putx,= Yn - 1. Then x, > 0, and, by the binomial theorem,

Hence

0svs [2 (n> 2).

(d) Let k be an integer such that k > a, k > 0. For n > 2k,
nn-1)-am-k+1) , np"

a+r > Qt = , Ja
Hence
© ok
0< gp <i (n> 2K).

Since a - k <0, n*"* +0, by (a).
(e) Take a=0in (d).

SERIES

In the remainder of this chapter, all sequences and series under consideration
will be complex-valued, unless the contrary is explicitly stated. Extensions of
some of the theorems which follow, to series with terms in R¥, are mentioned
in Exercise 15.
NUMERICAL SEQUENCES AND SERIES 59

3.21 Definition Given a sequence {a,), we use the notation

) a, (p<q)

to denote the sum a, +a, +.‘ +a, With {a,) we associate a sequence
{s,}, where

For {s,) we also use the symbolic expression

a, +a; ta, +
or, more concisely,

a Sa

The symbol (4) we call an infinite series, or just a series. The numbers
s, are called the partial sums of the series. If {s,) converges to s, we say that
the series converges, and write

The number s is called the sum of the series; but it should be clearly under-
stood that s is the limit of a sequence of sums, and is not obtained simply by
addition.

If {s,} diverges, the series is said to diverge.

Sometimes, for convenience of notation, we shall consider series of the
form

(5) Lan

And frequently, when there is no possible ambiguity, or when the distinction
is immaterial, we shall simply write Za, in place of (4) or (5).

It is clear that every theorem about sequences can be stated in terms of
series (putting a, = s,, and a, = §, - §,-; for n > 1), and vice versa. But it is
nevertheless useful to consider both concepts.

The Cauchy criterion (Theorem 3.11) can be restated in the following
form:

3.22 Theorem Za, converges if and only if for every \in > 0 there is an integer
N such that

©)

ifm=nz=N.

m
2 a
k=n

<e

60 PRINCIPLES OF MATHEMATICAL ANALYSIS

In particular, by taking m =n, (6) becomes

la,| Ic (n=N).
In other words:

3.23 Theorem If Za, converges, then lim, , a, = 0.

The condition a, = 0 is not, however, sufficient to ensure convergence
of Za,. For instance, the series

diverges; for the proof we refer to Theorem 3.28.

Theorem 3.14, concerning monotonic sequences, also has an immediate
counterpart for series.

3.24 Theorem A series of nonnegative’ terms converges if and only if its
partial sums form a bounded sequence.

We now turn to a convergence test of a different nature, the so-called
"comparison test."

3.25 Theorem
(a) Ifla| <c, for n= No, where Ng is some fixed integer, and if Cc,
converges, then La, converges.
(b) Ifa, 2d, 20 for n= Ng, and if Xd, diverges, then Xa, diverges.
Note that (b) applies only to series of nonnegative terms a,.
Proof Given \in > 0, there exists N = Ny such that m > n > N implies

m
Y a <e,
k=

by the Cauchy criterion. Hence

m
Ya
k=n

m m
<Ylal<Ya<e
k=n

and (a) follows.
Next, (b) follows from (a), for if Za, converges, so must Xd, [note
that (b) also follows from Theorem 3.24].

1 The expression ‘ nonnegative" always refers to real numbers.
NUMERICAL SEQUENCES AND SERIES 61

The comparison test is a very useful one; to use it efficiently, we have to
become familiar with a number of series of nonnegative terms whose conver-
gence or divergence is known.

SERIES OF NONNEGATIVE TERMS

The simplest of all is perhaps the geometric series.

3.26 Theorem If 0 <x <1, then

F x > 1, the series diverges.

Proof If x #1,

1 - x"t1

n
S,= 3 xk=
¥=o

The result follows if we let n = 00. For x = 1, we get

1-x

I+14+14-,
which evidently diverges.
In many cases which occur in applications, the terms of the series decrease
monotonically. The following theorem of Cauchy is therefore of particular

interest. The striking feature of the theorem is that a rather ""thin'' subsequence
of {a,) determines the convergence or divergence of Za,.

3.27 Theorem Suppose a, >a, >a, >.'*>0. Then the series ) | a, con-
verges if and only if the series

©) 5 kay =a, +2a, + 4a, + 8ag +
K=0

converges.

Proof By Theorem 3.24, it suffices to consider boundedness of the
partial sums. Let
Ss, =a, ta +: +a,

te=a; +2a, + + 2a
62 PRINCIPLES OF MATHEMATICAL ANALYSIS

For n < 2%,
Spl a, + (a, +a) + + (apt + amy)
<a, +2a, ++ + 2%a
=I,
so that
(8) Sy < ty.
On the other hand, if n > 2%,
Saar + a+ (a+ay) ++ (aak-14y +0 + ax)
>a, ta, +2a, +... +2 tay
=,

so that

©) 25, 2 ty.

By (8) and (9), the sequences {s,} and {#;} are either both bounded
or both unbounded. This completes the proof.

1
3.28 Theorem - converges if p > | and diverges ifp < I.
n

Proof If p <0, divergence follows from Theorem 3.23. If p>0,
Theorem 3.27 is applicable, and we are led to the series

kp

Now, 2! "<1 if and only if 1 - p <0, and the result follows by com-
parison with the geometric series (take x = 2! 77 in Theorem 3.26).
As a further application of Theorem 3.27, we prove:

329 Theorem FKp>1,
(10 5!
) Z2n(iog ny

converges; if p <1, the series diverges.

Remark 'logn” denotes the logarithm of n to the base e (compare Exercise 7,
Chap. I); the number c will be defined in a moment (see Definition 3.30). We
let the series start with n = 2, since log [ = 0.
NUMERICAL SEQUENCES AND SERIES 63

Proof The monotonicity of the logarithmic function (which will be
discussed in more detail in Chap. 8) implies that {log n) increases. Hence
{1/nlogn) decreases, and we can apply Theorem 3.27 to (10); this
leads us to the series

kd 1 ® 1 1 © 1

k,_ -= -_- = -
(an pI 2¥(log 25)? 2 (klog2)? (log PL ke’

and Theorem 3.29 follows from Theorem 3.28.

This procedure may evidently be continued. For instance,

= 1

(12)

n=3nlognloglogn
diverges, whereas
& 1

(13) pI log n(log log n)?

converges.

We may now observe that the terms of the series (12) differ very little
from those of (13). Still, one diverges, the other converges. If we continue the
process which led us from Theorem 3.28 to Theorem 3.29, and then to (12) and
(13), we get pairs of convergent and divergent series whose terms differ even
less than those of (12) and (13). One might thus be led to the conjecture that
there is a limiting situation of some sort, a boundary’ with all convergent
series on one side, all divergent series on the other side-at least as far as series
with monotonic coefficients are concerned. This notion of "boundary is of
course quite vague. The point we wish to make is this: No matter how we make
this notion precise, the conjecture is false. Exercises 11(b) and 12(b) may serve
as illustrations.

We do not wish to go any deeper into this aspect of convergence theory,
and refer the reader to Knopp's "Theory and Application of Infinite Series,"
Chap. IX, particularly Sec. 41.

THE NUMBER e

z 1

3.30 Definition e = .
n=0N !

Heren!=1-2-3--nifn>1,and 0! = 1.
64 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since
=1+1 + ! 1
S=ltity trast tra
1 1
<l+lds++ +m <3,

the series converges, and the definition makes sense. In fact, the series converges
very rapidly and allows us to compute e with great accuracy.

It is of interest to note that e can also be defined by means of another
limit process; the proof provides a good illustration of operations with limits:

1 n
3.31 Theorem lirn 1 + J =e.

no

Proof Let
n 1 1 n
= - t =11 |.
n= 5 . ( +)

By the binomial theorem,

1 1 1 1 2
t,=1+1+-(1-- -(1 == _Z
" + +5 J) +50 Alt ’) +

Hence t, <'s,,, so that
(14) limsupt, <e,

na

by Theorem 3.79. Next, if n > m,

nlateg (ieee (1-0) (1-220).
2! n m! n n

Let n - oo, keeping m fixed. We get

o 1 1
liminff, 21 +1 +75 + to
so that
Sp, < lim inf c,
n-ow
Letting m - co, we finally get
15) e < lim inf c, .
no a

The theorem follows from (14) and (15).
NUMERICAL SEQUENCES AND SERIES 65

1 .
The rapidity with which the series Y, ~ converges can be estimated as
n!

follows: If s, has the same meaning as above, we have

1 1 1
Ly mE 4 4...
CSTD Ge) Tar
Grn Tar Trp nin
so that
1
(16) 0<e-s,<-
nln

Thus 5,4, for instance, approximates ec with an error less than 1077, The
inequality (16) is of theoretical interest as well, since it enables us to prove the
irrationality of e very easily.

3.32 Theorem e is irrational.

Proof Suppose e is rational. Then e = p/q, where p and c are positive
integers. By (16),

1
(17) 0<qlfe-s)<-
q

By our assumption, gle is an integer. Since

1 1
ds =atfl 4145400)

is an integer, we see that q!(e - s,) is an integer.
Since c > 1, (17) implies the existence of an integer between 0 and 1.
We have thus reached a contradiction.

Actually, e is not even an algebraic number. For a simple proof of this,
see page 25 of Niven's book, or page 176 of Herstein's, cited in the Bibliography.

THE ROOT AND RATIO TESTS

3.33 Theorem (Root Test) Given Za, , put a = lim sup / |a,]|.

n-o0
Then
(a) ifa<1, Za, converges;

(b) ifa>1,Za,diverges;
(c) ifa=1, the test gives no information.
66 PRINCIPLES OF MATHEMATICAL ANALYSIS

3.34

Proof If a< 1, we can choose f so that a< pf <1, and an integer N
such that

la, <p
for n > N [by Theorem 3.17(b)]. That is, n = N implies
la,| <p"

Since 0 < B <1, ZB" converges. Convergence of Za, follows now from
the comparison test.
If a> 1, then, again by Theorem 3.17, there is a sequence {n,) such

%/ | an] a.
Hence |a,| > 1 for infinitely many values of n, so that the condition

a, - 0, necessary for convergence of Za,, does not hold (Theorem 3.23).
To prove (c), we consider the series

1 <1
To Xo

For each of these series a = 1, but the first diverges, the second converges.

that

Theorem (Ratio Test) The series Za,

Qn +1

(a) converges if lim sup <1,

n= ow

(b) diverges if

n+
a

21 for all n = ny, where ny is some fixed integer.
n

Proof If condition (a) holds, we can find f < 1, and an integer N, such
that

An+1
a,

<p

for n 2 N. In particular,

lan+1] < Blayl,
|an+2] < Blays+i| < Blan],

laws ,| < BPlay].
NUMERICAL SEQUENCES AND SERIES 67

That is,
la,| < lay|B~-

for n> N, and (a) follows from the comparison test, since Zf" converges.
If |a,+,| = |a,| for n> ny, it is easily seen that the condition a, » 0
does not hold, and (b) follows.

Note: The knowledge that lim a,.,/a, = 1 implies nothing about the
convergence of £a,. The series £1/n and £1/n? demonstrate this.

3.35 Examples

(a) Consider the series

1 11,1 1,1. 1 1. ..
23 2232023 337 0% 3 ’
for which
fim inf 22 = Jim bf =0,
n-o n n= 3
lin inf &/a, = lim *" =,
Lax] n-+w 5 J3
lim sup /a, = lim >" 11
n- oo " n= 2" V2

: An +1 1 ; "
limsup = lim [5] = +0.
n- ow a, n-o 2
The root test indicates convergence; the ratio test does not apply.
(b) The same is true for the series

1 1 1 1 1 1 1
tlre itt etm Tat

2 4 32 16 128 64
where
lim inf 9 ZL)
no Gp, 8
lim sup Gtr _ 2,
n= n
but

lim a, =}.
68 PRINCIPLES OF MATHEMATICAL ANALYSIS

3.36 Remarks The ratio test is frequently easier to apply than the root test,
since it is usually easier to compute ratios than nth roots. However, the root
test has wider scope. More precisely: Whenever the ratio test shows conver-
gence, the root test does too; whenever the root test is inconclusive, the ratio
test is too. This is a consequence of Theorem 3.37, and is illustrated by the
above examples.

Neither of the two tests is subtle with regard to divergence. Both deduce
divergence from the fact that a, does not tend to zero as n - co.

3.37 Theorem For any sequence {c,} d positive numbers,

n=o n=w

n=w

Proof We shall prove the second inequality; the proof of the first is
quite similar. Put

a = lim sup == Gut1

n= Cn
If a = + oo, there is nothing to prove. If a is finite, choose f > a. There
is an integer N such that
Cnt < p
Cy
for n > N. In particular, for any p > 0,
eyiktr SPeysx (k=0,1,...,p=1).

Multiplying these inequalities, we obtain

CN+p < Bren,

or
<cyp¥:-p" (m=N).
Hence
Jens YexB By
so that

(18) lim sup ¥/c, < B,
NUMERICAL SEQUENCES AND SERIES 69

by Theorem 3.20(b). Since (18) is true for every > a, we have

lim sup Ye, <a.

n=

POWER SERIES

3.38 Definition Given a sequence {c,} of complex numbers, the series
(19) Yo
n=0

is called a power series. The numbers c, are called the coefficients of the series;
zis a complex number.

In general, the series will converge or diverge, depending on the choice
of z. More specifically, with every power series there is associated a circle, the
circle of convergence, such that (19) converges if z is in the interior of the circle
and diverges if z is in the exterior (to cover all cases, we have to consider the
plane as the interior of a circle of infinite radius, and a point as a circle of radius
zero). The behavior on the circle of convergence is much more varied and can-
not be described so simply.

3.39 Theorem Given the power series Xc,z", put

se 1
a = lim sup &/|c,|, R="

n= w

(Ifa=0,R= +00; ifa= +00, R=0) Then Zc,z" converges if |z| <R, and
diverges f |z| > R.

Proof Put a, = c,z", and apply the root test:

|2|

lim sup a = |z| lim sup Neal =F
ow

nw n=

Note: R is called the radius of convergence of Zc, z".

3.40 Examples
(a) The series Zn" 2" has R = 0.

a4 . . . .
(b) The series Xo has R = +00. (In this case the ratio test is easier to

apply than the root test.)
70 PRINCIPLES OF MATHEMATICAL ANALYSIS

(c) The series £2" has R =1. If |z| = I, the series diverges, since {z"}

does not tend to 0 as n - co.

z"
(d) The series x: - has R = 1. It diverges if z= 1. It converges for all

other z with |z| = y (The last assertion will be proved in Theorem 3.44.)

(e) The series DE has R = I. Tt converges for all z with |z| = 1, by

the comparison test, since |z"/n?| = 1/n%.

SUMMATION BY PARTS

341 Theorem Given two sequences{a,}, {b,}, put

A,=Y a

k=0

ifn=0; put A_; =0. Then, if 0 < p <q, we have

q qz1
(20) Y a,b, = y Ab, = bysy) ei Ab, it 4,-
n=p

n=p

Proof

pe

q a q 9-1
Y aby =) (Ay - Ap-y)by=Y Ab, - 3S Apbyyy,
n=p n=p n=p n=p-1

and the last expression on the right is clearly equal to the right side of

(20).

Formula (20), the so-called "partial summation formula," is useful in the
investigation of series of the form Za,b,, particularly when {b,} is monotonic.

We shall now give applications.

3.42 Theorem Suppose

(a) the partial sums An of Za, form a bounded sequence;

(b) bo=by2by>";
(c) limb, =0.

had]

Then Za, b, converges.
343

NUMERICAL SEQUENCES AND SERIES 71

Proof Choose M such that |4,| < M for all n. Given &> 0, there is an
integer N such that by < (c/2M). For N <p <cq, we have

q Lid)
Y a,b,|= | 2 An(by = bys) + Agby - 41h,
n=p iad 4
q-1
<M Y. (by = busy) + by + b,
n=p

=2Mb, <2Mby <:.

Convergence now follows from the Cauchy criterion. We note that the
first inequality in the above chain depends of course on the fact that
by ~bp1 20.

Theorem Suppose

(a) ler] = lea] = les] 203
(b) Com-1 20, Cm <0 (m=1,2, 3,..0;
(c) lim, c,=0.

Then Zc, converges.

Series for which (b) holds are called "alternating series''; the theorem was

known to Leibnitz.

34

Proof Apply Theorem 3.42, with a, = (= 1)"*%, b, = |c,|.

Theorem Suppose the radius of convergence of Zec,2" is 1, and suppose

CoC 2c", lim, qc, =0. Then Zc, 7" converges at every point on the
circle | z| = 1, except possibly at 7 = 1.

Proof Put a,=7", b,=c,. The hypotheses of Theorem 3.42 are then
satisfied, since

Cries
1-2|’

| 4a] =

1 - z+
2 -
m=0 | 1-2

if |z] =1,z#1.

ABSOLUTE CONVERGENCE

The series Za, is said to converge absolutely if the series Z|a, | converges.

345

Theorem ¥ Za, converges absolutely, then Za, converges.
72 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof The assertion follows from the inequality

plus the Cauchy criterion.

3.46 Remarks For series of positive terms, absolute convergence is the same
as convergence.

If Za, converges, but X|a,| diverges, we say that Za, converges non-
absolutely. For instance, the series

y {=
n
converges nonabsolutely (Theorem 3.43).
The comparison test, as well as the root and ratio tests, is really a test for
absolute convergence, and therefore cannot give any information about non-
absolutely convergent series. Summation by parts can sometimes be used to

handle the latter. In particular, power series converge absolutely in the interior
of the circle of convergence.

We shall see that we may operate with absolutely convergent series very
much as with finite sums. We may multiply them term by term and we may
change the order in which the additions are carried out, without affecting the
sum of the series. But for nonabsolutely convergent series this is no longer true,
and more care has to be taken when dealing with them.

ADDITION AND MULTIPLICATION OF SERIES

347 Theorem If Za,-A, and Zb,-B, then X(a, +b) =A +B, and
Cca, = cA,for any fixed c.

Proof Let

Then
A + B, = (a + by).
Since lim, , A, = A and lim,, B, = B, we see that
lim(4,+B) =A +B.
n=

The proof of the second assertion is even simpler.
NUMERICAL SEQUENCES AND SERIES 73

Thus two convergent series may be added term by term, and the result-
ing series converges to the sum of the two series. The situation becomes more
complicated when we consider multiplication of two series. To begin with, we
have to define the product. This can be done in several ways; we shall consider
the so-called “Cauchy product.”

3.48 Definition Given Xa, and Xb,, we put

=Y ab, (1=0,1,2,..)
k=0

and call Zc, the product of the two given series.

This definition may be motivated as follows. If we take two power
series Xa,z" and Xb, z", multiply them term by term, and collect terms contain-
ing the same power of z, we get

0 0

Y oa, 2" Y b,2"=(ap+ az + az? + Wbo + biz + byz* +0)

n=0 n=0
= aobo + (ao hy + arho)z + (ag by + arb; + ay bo)z” + ++
=Co+ Cz +c 2h +r

Setting z = 1, we arrive at the above definition.

3.49 Example If

n n
A, = a, B,=Y b,, Co=Y cs
k=0 0 k=0

and A, - A, B, » B, then it is not at all clear that {C,} will converge to AB,
since we do not have C, = 4, B,. The dependence of {C,} on {4,} and {B,} is
quite a complicated one (see the proof of Theorem 3.50). We shall now show
that the product of two convergent series may actually diverge.

The series

© (=) 1 11

lm - + -- 4
PIS J2U3 U4

converges (Theorem 3.43). We form the product of this series with itself and

obtain

2 11 1 1 1
y. c,=1 + -) + - of --
"So V2 V2 N32 3

1 1 1 1
- - - + - + EEE
(7 J3V2 23 =) "
74 PRINCIPLES OF MATHEMATICAL ANALYSIS

so that
(13 --
" 50 /(n -k + Dk +1)
Since
n 2 no \? n 2
- 1 D=(|=-+1} -(=- <(=+1) .
(=k + Dk +1) (3+ ) 5 K) <(3+1)
we have

so that the condition c, -» 0, which is necessary for the convergence of Zc,, is
not satisfied.

In view of the next theorem, due to Mertens, we note that we have here
considered the product of two nonabsolutely convergent series.

3.50 Theorem Suppose

m
(a) Y a, converges absolutely,
n=0

®) Ya,=4,
n=0
(©) > b,=B,
n=0
(d) cx=Y ayb,, (1=0,1,2,..).
k=0
Then
> c,= AB
n=0

That is, the product of two convergent series converges, and to the right
value, if at least one of the two series converges absolutely.

Proof Put
A, =) a, B,=) by, C,=Y a, B,=B,- B.
=o =0 k=0
Then
C,=aobo + (apghy + ajby) +++ + (apb, + ab,_, +++ + a,b)
=ayB,+a;B,_, + +a,By
=ao(B + B,) + ay(B + Bu-1) + + + a (B + Bo)
=A,B + agp, + a B.-1 + + a,Bo
NUMERICAL SEQUENCES AND SERIES 75

Put
n= ao fn + aiBn-1 ++ a, fo.
We wish to show that C, - AB. Since A, B - AB, it suffices to
show that
1) limy, =0.
n=
Put
0
a= S la, .
n=0

[It is here that we use (a).] Let c >0 be given. By (c), B, = 0. Hence we
can choose N such that |8,| Le for » > N, in which case

[7a] < 1Boay+ + + Byun] + |By+1Gn-y-1 + *** + Bao]
<|Boa, +" + Pya,-n| + ea.
Keeping N fixed, and letting n - co, we get

lim sup |7,| < ea,
n=
since a, = 0 as k = oo. Since c is arbitrary, (21) follows.

Another question which may be asked is whether the series Zc,, if con-
vergent, must have the sum AB. Abel showed that the answeris in the affirma-
tive.

3.51 Theorem KF the series Xa,, Zb,, Zc, converge to A, B, C, and
c,=aob, ++ + a,b, then C= AB.

Here no assumption is made concerning absolute convergence. We shall
give a simple proof (which depends on the continuity of power series) after
Theorem 8.2.

REARRANGEMENTS

3.52 Definition Let {k,},n=1,2,3,..., be a sequence in which every
positive integer appears once and only once (that is, {k,} is a 1-1 function from
J onto J, in the notation of Definition 2.2). Putting

a, =a, (=1,2,3,..

we say that Za, is a rearrangement of Za,,.
76 PRINCIPLES OF MATHEMATICAL ANALYSIS

If {s,}, {s,} are the sequences of partial sums of Za,, Za, it is easily seen
that, in general, these two sequences consist of entirely different numbers.
We are thus led to the problem of determining under what conditions all
rearrangements of a convergent series will converge and whether the sums are
necessarily the same.

3.53 Example Consider the convergent series

22) T=d+i-d+i-d+-

and one of its rearrangements

(23) Lydd -d+s+dr-d+

in which two positive terms are always followed by one negative. If s is the
sum of (22), then

s<l-3+45=2%.

Since
1 1 1
-_-t--==>0
k-3 Tak-1 x
for k > 1, we see that s3 < sg <s5 <-**, where s, is nth partial sum of (23).
Hence

lim sup s, > 53 = 2,

nro

so that (23) certainly does not converge to s [we leave it to the reader to verify
that (23) does, however, converge].
This example illustrates the following theorem, due to Riemann.

3.54 Theorem Let Xa, be a series of real numbers which converges, but not
absolutely. Suppose
-0 <a<f< oo.

Then there exists a rearrangement a, with partial sums s, such that

(24) lim inf 5, = a, lim sup s;, = B.
n-ro0 n-*o0
Proof Let
la,| + a, as] -a,

Pn 2 ’ n 2
(25)

NUMERICAL SEQUENCES AND SERIES 77

Then p, -q, =a, p,+c =lal,p.=0,q 20. The series Zp,, Zq,
must both diverge.
For if both were convergent, then

(pn + qa) = Z| a,

would converge, contrary to hypothesis. Since

divergence of Zp, and convergence of Xg, (or vice versa) implies diver-
gence of Xa,, again contrary to hypothesis.

Now let Py, P,, P3, ... denote the nonnegative terms of Za,, in the
order in which they occur, and let Q,, a,, Qs, ... be the absolute values
of the negative terms of Za,, also in their original order.

The series £P,, CQ, differ from Zp,, Cq, only by zero terms, and
are therefore divergent.

We shall construct sequences {m,), {k,), such that the series

Pit +P = 01 ~ = Qu + Ppt
+ Puy = Qtr - = Qi ts

which clearly is a rearrangement of Xa, , satisfies (24).
Choose real-valued sequences {a,), {B,} such that a, >a, B,-pB,

oy < Bu 3 Bi > 0.
Let m,, k, be the smallest integers such that

P, +...1tP, > By,

Pitt Py, - 0 - = Oy <oy;
let m,, k, be the smallest integers such that
Pit 4P, -Q == Qt Puri + + Py, > Bo,
P+ +P, -0 -...- Qu, tPui1t... +P, - Cis

- = Op <

and continue in this way. This is possible since £P, and £Q, diverge.
If x,, y, denote the partial sums of (25) whose last terms are P,,_,
- Qk, then

[Xp - Bal <P, [ye - a] <Q, -

Since P, +0 and Q, -0 as n-» oo, we see that x, > ff, y, -» a.
Finally, it is clear that no number less than a or greater than f can
be a subsequential limit of the partial sums of (25).
78 PRINCIPLES OF MATHEMATICAL ANALYSIS

3.55 Theorem [If Za, is a series of complex numbers which converges absolutely,
then every rearrangement of Xa, converges, and they all converge to the same sum.

Proof Let Za, be a rearrangement, with partial sums s,. Given &> 0,
there exists an integer N such that m >n > N implies

(26)

on

la] <e.

i

n

Now choose p such that the integers 1, 2, ..., N are all contained in the
set ky, ka, ..., Kk, (we use the notation of Definition 3.52). Then if n > p,
the numbers a,, ...,a, will cancel in the difference s, -s,, so that
|s, - Si! <E by (26). Hence {s;} converges to the same sum as {5,}.

EXERCISES

1. Prove that convergence of {s,} implies convergence of {|s.|}. Is the converse true?
2. Calculate lim (V 1? +n - n).

3. Ifs; = V2, and
sar =V2u4 Ws (n=12,3 1

prove that {s,} converges, and that s, <2 forn=1, 2, 3, ... .
4. Find the upper and lower limits of the sequence {s.} defined by

Sam-1 1
5 Sam+y =% + Sam.

5; =0; Sam =">5-3 3
5. For any two real sequences {a.), {b,), prove that
lim sup (a, + ba) < fim sup a, + lim sup ba,
provided the sum on the right is not of the form «0 - x.
6. Investigate the behavior (convergence or divergence) of Za, if

a n,=Vn+1- Vn,
_ Va+1-Vn,

0) an = -;
Hn
© a=(¥n-1;
I
(d)a = EE for complex values of z.
7. Prove that the convergence of Xa, implies the convergence of
Va,

Xs

h
NUMERICAL SEQUENCES AND SERIES 79

8. If Ca, converges, and if {b) is monotonic and bounded, prove that Za,b, con-
verges.
9. Find the radius of convergence of each of the following power series:

2"
(a) Xn’, ®) X57

2n n
(c) PR (d) Xn

10. Suppose that the coefficients of the power series Ya, z" are integers, infinitely many
of which are distinct from zero. Prove that the radius of convergence is at most 1.
11. Suppose a. >0, 5, =a, ++. + a,, and Za, diverges.

a
1+a.

(a) Prove that diverges.

(b) Prove that

vet 4. an +x >1 Sx
SN+1 Sn +k SN+k
and deduce that X Zdiverges.
n
(c) Prove that
Gel 1

and deduce that 3% converges.
(dj What can be said about

da, dn 9
27 + na. and Xia :

12. Suppose a. >>0 and Za, converges. Put

Fa= 2. Gm.
nn
(a) Prove that
a an [2
a Eee
I) Fn Fm

if m <n, and deduce that hapa diverges.

n
80

13.

14.

PRINCIPLES OF MATHEMATICAL ANALYSIS

(b) Prove that

an - -
vr. < 2AVr, - Viney)

an
and deduce that. + converges.
In

Prove that the Cauchy product of two absolutely convergent series converges
absolutely.
If {s,} is a complex sequence, define its arithmetic means a, by

g =f nt ts (n=0,1,2,..).

n+1

(a) If lim s, = s, prove that lirn 6» =.
(b) Construct a sequence {s.} which does not converge, although lirn a. = 0.
(c) Canithappen thats, > Oforall #and that lirn sup $s, = ©, although lirn , = 0?
(d)Put a. = Sn - Su-1, for 22> 1. Show that

1
n+ 1

Sp - Op = 3s kay .
k=1
Assume that lim (na,) = 0 and that {o,} converges. Prove that {s.} converges.
[This gives a converse of (a), but under the additional assumption that na,- 0.]
(e) Derive the last conclusion from a weaker hypothesis: Assume M < ©,
|nas| <M for all n, and lin 0, =o. Prove that lirn s, - a, by completing the
following outline:

If m < 12 then

m+ 1 1 LJ
Sp - a. = (= om t- > (n= s0.

1T- IM j=m+

For these i,

Is 5 <OZOM _(nmm- DM
Ter TO omy

Fix  \in c >0 and associate with each n the integer m that satisfies

<P7f cm
MET Ie sm ’

Then (m+ 1)/(n -m) 7 1/c and |s, - 5] < Me. Hence

lim sup|s, - o| < Me.

Since & was arbitrary, lirn 5, = a.
15.

16.

17.

18.

19.

NUMERICAL SEQUENCES AND SERIES 81

Definition 3.21 can be extended to the case in which the a. lie in some fixed R*.
Absolute convergence is defined as convergence of Za. |. Show that Theorems
3.22, 3.23, 3.25(a), 3.33, 3.34, 3.42, 3.45, 3.47, and 3.55 are true in this more
general setting. (Only slight modifications are required in any of the proofs.)

Fix a positive number a. Choose x; > Va, and define x, x3, Xs, ..., by the

1 o
Xn41 = 3 xt .

(a) Prove that {x,) decreases monotonically and that lim x, = Va.
(b) Put & = xp - Va, and show that

recursion formula

2 2
£, Ep
<

2x, 2Va

Eny1 =

so that, setting 8 = 2V a,
£1

Err (3) (n=1,23,...).

(c) This is a good algorithm for computing square roots. since the recursion
formula is simple and the convergence is extremely rapid. For example, if a = 3
and x, = 2, show that &,/8 < 4% and that therefore

es <4 .1071°, gs <4.10732,
Fix a > 1. Take x; > Va, and define

2
o + Xp oa - X,

T+x. "0 1+x

Xn+1 =

(a) Prove that x, >x3>xs 3"...

(b) Prove that x, <x ®Xg <....

(c) Prove that lim x, - Va.

(d) Compare the rapidity of convergence of this process with the one described
in Exercise 16.

Replace the recursion formula of Exercise 16 by

where p is a fixed positive integer, and describe the behavior of the resulting
sequences {X,}.
Associate to each sequence a = {«,}, in which a,, is 0 or 2, the real number

X=2 5

Prove that the set of all x(a) is precisely the Cantor set described in Sec. 2.44.
82

20.

21.

22.

23.

24.

25.

PRINCIPLES OF MATHEMATICAL ANALYSIS

Suppose {p.) is a Cauchy sequence in a metric space X, and some subsequence
{pm} converges to a point pe X. Prove that the full sequence {Ps} converges to p.
Prove the following analogue of Theorem 3.10(b): If {E,} is a sequence of closed
nonempty and bounded sets in a complete metric space X, if En > Eqyy, and if

lim diam E. = 0,

n-+®

then (\¥ En consists ofexactly one point.

Suppose X is a nonempty complete metric space, and {G.} is a sequence of
dense open subsets of X. Prove Baire's theorem, namely, that (PG is not
empty. (In fact, it Is dense in X.) Hint: Find a shrinking sequence of neighbor-
hoods E, such that E, = G., and apply Exercise 21.

Suppose {p.) and {q,) are Cauchy sequences in a metric space X. Show that the
sequence {d(pn,qn)} converges. Hint: For any m, n,

d(pn, qn) < d(pn, Pr) + d(Pm, qn) + d(Gn , Gn);
it follows that
|d(pn, gn) - d(Pm, Gm) |

is small ifm and n are large.
Let X be a metric space.
(a) Call two Cauchy sequences {p.), {q.) in X equivalent if

lim d(p, 4») =0.

Prove that this is an equivalence relation.
(b) Let X* be the set of dll equivalence classes so obtained. If Pe X* Q& X*,
{p.} \in P,{g.} \in Q, define

AP, Q) - lim d(pr, qn);

by Exercise 23, this limit exists. Show that the number A(P, Q )is unchanged if
{pn} and {q.) are replaced by equivalent sequences, and hence that Ais a distance
functionin X*.

(c) Prove that the resulting metric space X* is complete.

(d) For each p< X, there is a Cauchy sequence dil of whose terms are p; let P,
be the element of X* which contains this sequence. Prove that

A(P,, Po) =d(p, q)

fordl p,qs X. In other words, the mapping defined by a(p) = P, is an isometry
(i.e., a distance-preserving mapping)of X into X*.

(e) Prove that c(X) is dense in X*, and that c(X) = X* if X is complete. By (d),
we may identify X and o(X) and thus regard X as embedded in the complete
metric space X*. We call X* the completionof X.

Let X be the metric space whose points are the rational numbers, with the metric
d(x, y)=|x - y|. What is the completion ofthis space? (Compare Exercise 24.)
4

CONTINUITY

The function concept and some of the related terminology were introduced in
Definitions 2.1 and 2.2. Although we shall (in later chapters) be mainly interested
in real and complex functions (i.e., in functions whose values are real or complex
numbers) we shall also discuss vector-valued functions (i.e., functions with
values in R*) and functions with values in an arbitrary metric space. The theo-
rems we shall discuss in this general setting would not become any easier if we
restricted ourselves to real functions, for instance, and it actually simplifies and
clarifies the picture to discard unnecessary hypotheses and to state and prove
theorems in an appropriately general context.

The domains of definition of our functions will also be metric spaces,
suitably specialized in various instances.

LIMITS OF FUNCTIONS

4.1 Definition Let X and Y be metric spaces; suppose E = X,f maps E into
Y, and p is a limit point of E. We writef (x) - c as x - p, or

(1) limf (x) =cq

x-p
84 PRINCIPLES OF MATHEMATICAL ANALYSIS

if there is a point c \in Y with the following property: For every c > 0 there
exists a 6 > 0 such that

J) dy(f(x),q) <ec
for all points x \in E for which
3) 0 < dy(x, p) <0.

The symbols dy and dy refer to the distances in X and Y, respectively.

If X and/or Yare replaced by the real line, the complex plane, or by some
euclidean space R*, the distances dy , dy are of course replaced by absolute values,
or by norms of differences (see Sec. 2.16).

It should be noted that pe X, but that p need not be a point of E
in the above definition. Moreover, even if pe E, we may very well have
Fp) # lim,..,, f(x).

We can recast this definition in terms of limits of sequences:

4.2 Theorem Let X, Y, Ef, and p be us in Definition 4.1. Then

“) limf(x)=gcq
xp

if and only if

© lim £(p,) =c

for every sequence {p,} in E such that
(6) pn#p, limp, =p.

Proof Suppose (4) holds. Choose {p,} in E satisfying (6). Let c >0
be given. Then there exists 6 >0 such that dy(f(x),q)<e if xeE
and 0 <dy(x,p)<6. Also, there exists N such that n> N implies
0 <dy(pn,p) <6. Thus, for n>N, we have dy(f(p,),q)<eg, which
shows that (5) holds.

Conversely, suppose (4)is false. Then there exists some & > 0 such
that for every 6 > 0 there exists a point x \in E (depending on 9), for which
dy(f(x),q)= \in but 0 <dy(x,p)<6. Taking6, =1/n(n=1,2,3,...), we
thus find a sequence in E satisfying (6) for which (5) is false.

Corollary [ff has a limit at p, this limit is unique.

This follows from Theorems 3.2() and 4.2.
CONTINUITY 85

4.3 Definition Suppose we have two complex functions, f and g, both defined
on E. Byf 4g we mean the function which assigns to each point x of E the
number f(x) + g(x). Similarly we define the difference f - g, the product fg,
and the quotient f/g of the two functions, with the understanding that the quo-
tient is defined only at those points x of E at which g(x) # 0. Iff assigns to each
point x of E the same number c, then f is said to be a constant function, or
simply a constant, and we write f =c. Iff and g are real functions, and if
f(x) = g(x) for every x \in E, we shall sometimes write f > g, for brevity.
Similarly, iff and gc map E into R*, we define f + g and f, g by

T+)(x) =x) + g(x), (89x =x). g(x);
and if A is a real number, (Af)(x) = M(x).

44 Theorem Suppose E c X, a metric space, p is a limit point  E,f and g
are complex functions on E, and

lim £(x) = A, lim g(x) =

xp xp

Then (a) lim 63 "Om A + B;
(b) fim (f9)x) =

© lim (oo -4 SN
xp

Proof In view of Theorem 4.2, these assertions follow immediately from

the analogous properties of sequences (Theorem 3.3).

Remark Iff and gc map E into R*, then (a) remains true, and (b) becomes
(®) lim (fr g)x) =

xp

(Compare Theorem 3.4.)

CONTINUOUS FUNCTIONS

45 Definition Suppose X and Yare metric spaces, E cc X, p \in E, and f maps
Einto Y. Thenf is said to be continuous at p if for every \in > 0 there exists a
6 > 0 such that

dy(f(x), f(p) < &

for all points x \in E for which dx(x,p) <0.
Iff is continuous at every point of E, thenf is said to be continuous on E.
It should be noted thatf has to be defined at the point p in order to be
continuous at p. (Compare this with the remark following Definition 4.1.)
86 PRINCIPLES OF MATHEMATICAL ANALYSIS

Ifp is an isolated point of E, then our definition implies that every function
f which has E as its domain of definition is continuous at p. For, no matter
which & > 0 we choose, we can pick 6 > 0 so that the only point x \in E for which
dy(x,p) <6is x =p, then

dy(f(x), f(p)) =0 <e.
4.6 Theorem In the situation given in Definition 4.5, assume also that p is a
limit point of E. Then f is continuous at p if and only if lim, f(x) =f(p).

Proof This is clear if we compare Definitions 4.1 and 4.5.
We now turn to compositions of functions. A brief statement of the

following theorem is that a continuous function of a continuous function is
continuous.

47 Theorem Suppose X, Y, Z are metric spaces, E = X, f maps E into Y, g
maps the range off, f(E), into Z, and h is the mapping of E into Z defined by

h(x) -g(f(x)) (xe E).

Iff is continuous at a point p \in E and ifg is continuous at the point f(p), then h is
continuous at p.

This function / is called the composition or the composite off and g. The
notation

h=gef
is frequently used in this context.

Proof Let £c>0 be given. Since g is continuous at f(p), there exists
n > 0 such that

dz(9(v), 9(f(p)) < gif dy(y, f(P)) <n and ye f(E).
Since f is continuous at p, there exists 6 > 0 such that
dy(f(x), f(p)) <n if d(x, p) < Sand xe E.

It follows that

dz(1(x), h(p)) = dz(9(f (x). 9(f(P))) < &

if dy(x, p) <d and x \in E. Thus h is continuous at p.
48 Theorem A mapping f'of a metric space X into a metric space Y is con-
tinuous on X if and only iff ~*(V) is open in X for every open set V in Y.

(Inverse images are defined in Definition 2.2.) This is a very useful charac-
terization of continuity.
CONTINUITY 87

Proof Suppose fis continuous on X and V is an open setin Y. We have
to show that every point off ~!(¥) is an interior point off ~!(¥). So,
suppose p \in X and f(p) \in V. Since V is open, there exists c > 0 such that
ye Vif dy(f(p),y)< ce; and since f is continuous at p, there exists 6 > 0
such that dy(f(x), f(p)) < c if d(x, p) <6. Thus x ef }(V) as soon as
dy(x, p) <9.

Conversely, suppose f ~!(¥) is open in X for every open set V in Y.
Fix pe X and c > 0, let V be the set of all ye Y such that dy(y, f(p)) < &.
Then Vis open; hence f ~*(¥) is open; hence there exists § > 0 such that
x ef Y(V)as soon as dy(p, x) <6. Butif xe f~Y(¥), then f(x) eV, so
that dy(f(x), f(p)) < e.

This completes the proof.

Corollary A mapping f of a metric space X into a metric space Y is continuous if
and only iff ~'(C) is closed in X for every closed set C in Y.

This follows from the theorem, since a set is closed if and only if its com-

plement is open, and since f ~'(E \in ) = [ f~'(E)]° for every E  Y.

We now turn to complex-valued and vector-valued functions, and to

functions defined on subsets of R*.

4.9 Theorem Let f and g be complex continuous functions on a metric space X.
Then f + g, fg, and fg are continuous on X.

4.10

(M

In the last case, we must of course assume that g(x) # 0, for all x \in X.
Proof At isolated points of X there is nothing to prove. At limit points,

the statement follows from Theorems 4.4 and 4.6.

Theorem

(a) Let fi, ...,[; be real functions on a metric space X, and let £ be the
mapping of X into R* defined by

fx) = (ix), .... A(x) (xe X);

then f is continuous ifandonly if each of the functions fy, ..., fy is continuous.

(0) Iff and g are continuous mappings of X into R*, then f+ g and f . g
are continuous on X.

The functions fj, ..., fi are called the components of f. Note that
f + g is a mapping into R*, whereas f . g is a real function on X.
88 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Part (a) follows from the inequalities

1469) = 100] = 166) = 09] ={ 3. ie 1017)’

for j=1,..., k. Part (b) follows from (a) and Theorem 4.9.

4.11 Examples If x,, ..., x, are the coordinates of the point x eR¥, the
functions c; defined by
® ox) =x; (xeR"

are continuous on R¥, since the inequality

[x)= $Y] < [x -y]

shows that we may take § = c in Definition 4.5. The functions c; are sometimes
called the coordinate functions.
Repeated application of Theorem 4.9 then shows that every monomial

® XPX LL xg

where ny, ..., n, are nonnegative integers, is continuous on R*. The same is
true of constant multiples of (9), since constants are evidently continuous. It
follows that every polynomial P, given by

(10) P(X) =Zc,,.., X}'... Xx (x  \in RY,

is continuous on R*. Here the coefficients Cy om are cOmplex numbers, ny, ... , Ay

are nonnegative integers, and the sum in (10) has finitely many terms.
Furthermore, every rational function in x, ..., X;, that is, every quotient

of two polynomials of the form (10), is continuous on R* wherever the denomi-
nator is different from zero.
From the triangle inequality one sees easily that

(11) [1x] = |yl|<] = (x, yeRY. |

Hence the mapping x - |x| is a continuous real function on R*.

If now f is a continuous mapping from a metric space X into R*, and if c
is defined on X by setting c(p) = |f(p)|, it follows, by Theorem 4.7, that c is a
continuous real function on X.

4.12 Remark We defined the notion of continuity for functions defined on a
subset E of a metric space X. However, the complement of E in X plays no
role whatever in this definition (note that the situation was somewhat different
for limits of functions). Accordingly, we lose nothing of interest by discarding
the complement of the domain off. This means that we may just as well talk
only about continuous mappings of one metric space into another, rather than
CONTINUITY 89

of mappings of subsets. This simplifies statements and proofs of some theorems.
We have already made use of this principle in Theorems 4.8 to 4.10, and will
continue to do so in the following section on compactness.

CONTINUITY AND COMPACTNESS

413 Definition A mapping f of a set E into R¥ is said to be bounded if there is
a real number M such that |f(x)| < M for all xe E.

4.14 Theorem Suppose f is a continuous mapping of a compact metric space
X into a metric space Y. Then f(X) is compact.

Proof Let {V,} be an open cover off (X). Since fis continuous, Theorem
4.8 shows that each of the sets f ~!(V,) is open. Since X is compact,

there are finitely many indices, say a, ..., a,, such that
(12) Xcf-'WVe)u...ouf'(V,).

Since f(f~*(E)) c E for every E c Y, (12)implies that
(13) fX)cVyu...uV,, .

This completes the proof.

Note: We have used the relation f(f Y(E)) cE, valid for Ec Y. If
E c X, then f~'(f(E)) © E; equality need not hold in either case.
We shall now deduce some consequences of Theorem 4.14.

415 Theorem [ffis a continuous mapping of a compact metric space X into
RY, then f(X) is closed and bounded. Thus, f is bounded.

This follows from Theorem 2.41. The result is particularly important
when fis real:

416 Theorem Suppose f is a continuous real function on a compact metric
space X, and

(14) M = sup fp), m= inf f(p).

Then there exist points p, q \in X such that f(p)= M and f(q)=m.

The notation in (14) means that M is the least upper bound of the set of
all numbers f(p), where p ranges over X, and that m is the greatest lower bound
of this set of numbers.
90 PRINCIPLES OF MATHEMATICAL ANALYSIS

The conclusion may also be stated as follows: There exist points p and q
in X such that £(q) < f(x) <f(p)for all x \in X; that is, f attains its maximum
(at p) and its minimum (at q).

Proof By Theorem 4.15, f(X) is a closed and bounded set of real num-
bers; hence f (X) contains

M = supf(X) and m = inff (X),
by Theorem 2.28.

4.17 Theorem Suppose f is a continuous 1-1 mapping of a compact metric
space X onto a metric space Y. Then the inverse mapping f ~! dejinedon Y by

[TU =x (xeX)

is a continuous mapping d Y onto X.

Proof Applying Theorem 4.8 to f~! in place off, we see that it suffices
to prove thatf(V) is an open set in Y for every open set Vin X. Fix such
aset V.

The complement V \in  of Vis closed in X, hence compact (Theorem
2.35); hence f(Vc) is a compact subset of Y (Theorem 4.14) and so is
closed in Y (Theorem 2.34). Sincef is one-to-one and onto, f(¥') is the
complement of f(Vc). Hence f(V') is open.

4.18 Definition Letf be a mapping of a metric space X into a metric space Y.
We say thatf is uniformly continuous on X if for every & > 0 there exists 6 > 0
such that

(15) dy(f(p), f(a) <c

for all p and q in X for which dy(p,q) <6.

Let us consider the differences between the concepts of continuity and of
uniform continuity. First, uniform continuity is a property of a function on a
set, whereas continuity can be defined at a single point. To ask whether a given
function is uniformly continuous at a certain point is meaningless. Second, if
f is continuous on X, then it is possible to find, for each & > 0 and for each
pointp of X,a number 6 > 0 having the property specified in Definition 4.5. This
6 depends on c and on p. Iff is, however, uniformly continuous on X, then it is
possible, for each c > 0, to find one number 6 > 0 which will do for all points
p of X.

Evidently, every uniformly continuous function is continuous. That the
two concepts are equivalent on compact sets follows from the next theorem.
CONTINUITY 91

4.19 Theorem Let f be a continuous mapping of a compact metric space X
into a metric space Y. Then f is uniformly continuous on X.

Proof Let c >0 be given. Since f is continuous, we can associate to
each point p \in X a positive number c(p) such that

oo  \in 

(16) qe X, dy(p.q) < c(p) implies dy(f(p), /(q)) <3

Let J(p) be the set of all c \in X for which
an dx(p, 9) < 3c(p).

Since p  \in J(p), the collection of all sets J(p) is an open cover of X, and

since Xis compact, there is a finite set of points py, ..., p, in X, such that
(18) XcJ(p)u  ul(p)

We put

19) 0 =4 min [c(p,), ..., c(p)].

Then 6 > 0. (This is one point where the finiteness of the covering, in-
herent in the definition of compactness, is essential. The minimum of a
finite set of positive numbers is positive, whereas the inf of an infinite set
of positive numbers may very well be 0.)

Now let g and p be points of X, such that dy(p, g) <6. By (18), there
is an integer m, 1 <m < n, such that pe J(p,,); hence

(20) dp, Pr) < 36(Pn);

and we also have

dx(q, pn) < dp, q) + dx(p, Pm) <0 + 30(Pn) < $(Pm)-
Finally, (16) shows that therefore

dy(f (0). S(a) < dy (f(D). fp) + dx(f(a). S(Pn)) <8.

This completes the proof.

An alternative proof is sketched in Exercise 10.
We now proceed to show that compactness is essential in the hypotheses
of Theorems 4.14, 4.15, 4.16, and 4.19.

4.20 Theorem Let E be a noncompact set in R*. Then

(a) there exists a continuous function on E which is not bounded;
(b) there exists a continuous and bounded function on E which has no
maximum.

If, in addition, E is bounded, then
92 PRINCIPLES OF MATHEMATICAL ANALYSIS

(21)

22)

(23)

(c) there exists a continuous function on E which is not uniformly
continuous.

Proof Suppose first that E is bounded, so that there exists a limit point
Xo of E which is not a point of E. Consider

1
fx) =x (x \in E).

This is continuous on E (Theorem 4.9), but evidently unbounded. To see
that (21) is not uniformly continuous, let c > 0 and 6 > 0 be arbitrary, and
choose a point x \in E such that |x - xo| <6. Taking t close enough to
Xp, We can then make the difference | f(t) -f(x)| greater than e, although
|t - x| <6. Since this is true for every 6 > O,f is not uniformly continu-
ous on E.

The function g given by

(xeE)

1
g(x) = 1+ (x = xy)?

is continuous on E, and is bounded, since 0 < g(x) <1. Itis clear that

sup g(x) =1,
xeE
whereas g(x) < 1 for all x \in E. Thus g has no maximum on E.
Having proved the theorem for bounded sets E, let us now suppose
that E is unbounded. Then f(x) = x establishes (a), whereas

x2

h(x) = iT (xe E)
establishes (b), since
sup h(x) =1
xeE

and A(x) <1 for all x \in E.

Assertion (c) would be false if boundedness were omitted from the
hypotheses. For, let E be the set of all integers. Then every function
defined on E is uniformly continuous on E. To see this, we need merely
take 6 < 1 in Definition 4.18.

We conclude this section by showing that compactness is also essential in

Theorem 4.17.
CONTINUITY 93

4.21 Example Let X be the half-open interval [0,2n) on the real line, and
let f be the mapping of X onto the circle Y consisting of all points whose distance
from the origin is 1, given by

24) f(r) = (cos t,sint)  (0<t<2m).

The continuity of the trigonometric functions cosine and sine, as well as their
periodicity properties, will be established in Chap. 8. These results show that
f is a continuous 1-1 mapping of X onto Y.

However, the inverse mapping (which exists, since f is one-to-one and
onto) fails to be continuous at the point (1, 0) = f(0). Of course, Xis not com-
pact in this example. (It may be of interest to observe that f ! fails to be
continuous in spite of the fact that Y is compact!)

CONTINUITY AND CONNECTEDNESS

4.22 Theorem If fis a continuous mapping d a metric space X into a metric
space Y, and F E is a connected subset  X, thenf (E) is connected.

Proof Assume, on the contrary, that f(E) =A U B, where A and B are
nonempty separated subsets of ¥. Put G =E nf "!(4), H =E nf ~!(B).

Then E = G U H, and neither G nor His empty.

Since A c A (the closure of A), we have G cf ~!(A); the latter set is
closed, since f is continuous; hence G c f~!(4). It follows that f(G) c A.
Since f(H) =B and 4 n B is empty, we conclude that G n H is empty.

The same argument shows that G ~ H is empty. Thus G and H are
separated. This is impossible if E is connected.

4.23 Theorem Let f be a continuous real function on the interval [a, b]. If
f(a) <f(b) and if cc is a number such that f(a) < c <f(b), then there exists a
point x \in (a, b) such thatf (x) = c.

A similar result holds, of course, if f(a) > f(b). Roughly speaking, the
theorem says that a continuous real function assumes all intermediate values on
an interval.

Proof By Theorem 2.47, [a, b] is connected; hence Theorem 4.22 shows
that f([a, b]) is a connected subset of R', and the assertion follows if we
appeal once more to Theorem 2.47.

4.24 Remark At first glance, it might seem that Theorem 4.23 has a converse.
That is, one might think that if for any two points x; < x, and for any number c
between f(x) and f(x,) there is a point x in (x,, x,) such thatf(x) =c, then f
must be continuous.

That this is not so may be concluded from Example 4.27(d).
94 PRINCIPLES OF MATHEMATICAL ANALYSIS

DISCONTINUITIES

If x is a point in the domain of definition of the function f at which f is not
continuous, we say thatf is discontinuous at x, or thatf has a discontinuity at x.
Iff is defined on an interval or on a segment, it is customary to divide discon-
tinuities into two types. Before giving this classification, we have to define the
right-hand and the left-hand limits off at x, which we denote byf (x +) andf (x-),
respectively.

4.25 Definition Let f be defined on (a,b). Consider any point x such that
a <x <b. We write

flx+)=c

iff (t,) -q as n- 00, for all sequences {#,} in (x, b) such that t, = x. To obtain
the definition of f(x-), for a < x <b, we restrict ourselves to sequences {t,) in
(a, x).

It is clear that any point x of (a, b), lim f(c) exists if and only if

tox

ft) =f(x=) = lim £1).

4.26 Definition Letf be defined on (a,b). Iff is discontinuous at a point x,
and if f(x+) and f(x -) exist, then fis said to have a discontinuity of the first
kind, or a simple discontinuity, at x. Otherwise the discontinuity is said to be of
the second kind.

There are two ways in which a function can have a simple discontinuity:
either f(x +) # f(x -) [in which case the value f(x) is immaterial], or f(x+) =
S(x=) #f(0).

4.27 Examples
(a) Define

_ 1 (x rational),
fx) = b (x irrational).

Then f has a discontinuity of the second kind at every point x, since
neither £(x+) nor f(x-) exists.
(b) Define

x (x rational),
S00) = H (x irrational).
CONTINUITY 95

Then fis continuous at x = 0 and has a discontinuity of the second
kind at every other point.

(c) Define
x+2 (-3<x<-2),
fx)=(-x-2 (-2<x<0),
x+2 O<x<l)

Then f has a simple discontinuity at x =0 and is continuous at
every other point of (-3, 1).
(d) Define

1
fo) = sin po (x #0),

0 (x = 0).

Since neither (0+) nor f(0-) exists, f has a discontinuity of the
second kind at x =0. We have not yet shown that sin x is a continuous
function. If we assume this result for the moment, Theorem 4.7 implies
that f is continuous at every point x # 0.

MONOTONIC FUNCTIONS

We shall now study those functions which never decrease (or never increase) on
a given segment.

4.28 Definition Let f be real on (a,b). Then f is said to be monotonically
increasing on (a, b) if a < x < y <b implies f(x) < f(y). If the last inequality
is reversed, we obtain the definition of a monotonically decreasing function. The
class of monotonic functions consists of both the increasing and the decreasing
functions.

4.29 Theorem Let f be monotonically increasing on (a, b). Then f(x+) and
f(x-) exist at every point of x of (a, b). More precisely,

sup f(t) =f(x-) < f(x) <f(x+) = inf S(O).

a<t<x

Furthermore, if a < x < y <b, then

Sx) <fO-).

Analogous results evidently hold for monotonically decreasing functions.
96 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof By hypothesis, the set of numbers f(#). where a < t < x, is bounded
above by the number f(x), and therefore has a least upper bound which
we shall denote by A. Evidently A <f(x). We have to show that
A =f(x-).

Let c >0 be given. It follows from the definition of A as a least
upper bound that there exists 6 > 0 such that a < x - é < x and

(27) A-e<f(x-90)< A.
Since f is monotonic, we have
(28) fx=0)<f(t)y< A (x-d<t<x).

Combining (27)and (28), we see that
f(t) -A| <e (x-=d<t<x).

Hence f(x-) =A.
The second half of (25)is proved in precisely the same way.
Next, if a < x <y <b. we see from (25) that

29 f(x+) = inf f(t) = inf f(c).
x<t<b x<t<y
The last equality is obtained by applying (25) to (a, y) in place of (a,b).
Similarly,
(30) Sf(y=) = sup f(t) = sup f(t).
a<t<y x<t<y

Comparison of (29)and (30) gives (26).
Corollary Monotonic functions have no discontinuities of the second kind.

This corollary implies that every monotonic function is discontinuous at
a countable set of points at most. Instead of appealing to the general theorem
whose proof is sketched in Exercise /7, we give here a simple proof which is
applicable to monotonic functions.

4.30 Theorem Let f be monotonic on (a,b). Then the set of points of (a,b) at
which f is discontinuous is at most countable.

Proof Suppose, for the sake of definiteness, that f is increasing. and
let E be the set of points at which f is discontinuous.

With every point x of E we associate a rational number r(x) such
that

flx=) < r(x) <flx+).
CONTINUITY 97

Since x, <x, implies f(x;+) <f(x,-), we see that r(x) # r(x,) if
X{ # X;.

We have thus established a 1-1 correspondence between the set £ and
a subset of the set of rational numbers. The latter, as we know, is count-
able.

4.31 Remark It should be noted that the discontinuities of a monotonic
function need not be isolated. In fact, given any countable subset E of (a, b).
which may even be dense, we can construct a function f, monotonic on (a, b),
discontinuous at every point of E, and at no other point of (a,b).

To show this: let the points of E be arranged in a sequence {x,},

n=1,2, 3,.... Let {c,} be a sequence of positive numbers such that Zc,
converges. Define
3D SD =3Y c (a<x<b)

Xp <x

The summation is to be understood as follows: Sum over those indices n
for which x, < x. If there are no points x, to the left of x. the sum is empty;
following the usual convention, we define it to be zero. Since (31) converges
absolutely. the order in which the terms are arranged is immaterial.

We leave the verification of the following properties off to the reader:

(u) f is monotonically increasing on (a, b);
(b) fis discontinuous at every point of Ein fact,

Sx) = f(x =) =,
(c) fis continuous at every other point of (a, b).

Moreover, it is not hard to see that f(x-) =f (x) at all points of (a, b). If
a function satisfies this condition, we say that f is continuousfrom the left. If
the summation in (31) were taken over all indices n for which x, < x, we would
have f(x+) = f(x) at every point of (a, b); that is, f would be continuous from
the right.

Functions of this sort can also be defined by another method; for an
example we refer to Theorem 6.16.

INFINITE LIMITS AND LIMITS AT INFINITY

To enable us to operate in the extended real number system, we shall now
enlarge the scope of Definition 4.1, by reformulating it in terms of neighborhoods.

For any real number x, we have already defined a neighborhood of x to
be any segment (x - 6, Xx + 6).
98 PRINCIPLES OF MATHEMATICAL ANALYSIS

4.32 Definition For any real c, the set of real numbers x such that x > c is
called a neighborhood of + oo and is written (c, + 0). Similarly, the set (- co, c)
is a neighborhood of - co.

4.33 Definition Letf be a real function defined on E = R. We say that
f(t)» Aast-x,

where A and x are in the extended real number system, if for every neighborhood
U of A there is a neighborhood V of x such that V n Eis not empty, and such
that f(r) e Uforallte Vn E, t # x.

A moment's consideration will show that this coincides with Definition
4.1 when A and x are real.

The analogue of Theorem 4.4 is still true, and the proof offers nothing
new. We state it, for the sake of completeness.

434 Theorem Letf and g be defined on E = R. Suppose

f(t)=4, ga)-B ast- x.
Then
(a) f(t)- A" implies A" =A.
B) (f+9Xt)- A+B,
(c) (fo)r)- AB,
(d) (flg)t)- A/B,
provided the right members d (b), (c), and (d) are dejined.
Note that 00 - 00, 0 - 00, 00/00, 4/0 are not defined (see Definition 1.23).

EXERCISES
1. Supposef is a real function defined on R* which satisfies

lim [fix+h -f(x-m]1=0

for every x \in R'. Does this imply thatf is continuous?
2. Iff is a continuous mapping of a metric space X into a metric space Y, prove that

f(E)< f(E)
for every set E < X. (E denotes the closure of E.) Show, by an example, that
T(E) can be a proper subset of f(E).
3. Letf be a continuous real function on a metric space X. Let Z(f) (the zeroset off)

be the set of all p \in X at which f(p) =0. Prove that Z(f) is closed.
4. Letf and g be continuous mappings of a metric space X into a metric space Y,
10.

11.

12.

13.

CONTINUITY 99

and let E be a dense subset of X. Prove that f(E) is dense in f(X). If g(p) =f(p)
for all p \in E, prove that g(p) = f(p) for all pe X. (In other words, a continuous
mapping is determined by its values on a dense subset of its domain.)

. Iff is a real continuous function defined on a closed set E < R*, prove that there

exist continuous real functions g on R! such that g(x) = f(x) for all x \in E. (Such
functions g are called continuous extensions off from E to R'.) Show that the
result becomes false if the word "closed" is omitted. Extend the result to vector-
valued functions. Hint: Let the graph of g be a straight line on each of the seg-
ments which constitute the complement of E (compare Exercise 29, Chap. 2).
The result remains true if R* is replaced by any metric space, but the proof is not
so simple.

. Iff'is defined on E, the graph off is the set of points (x, f(x)), for x \in E. In partic-

ular, if Eis a set of real numbers, andf'is real-valued, the graph off is a subset of
the plane.

Suppose E is compact, and prove thar f is continuous on E if and only if
its graph is compact.

. If E< X and iff is a function defined on X, the restriction off to E is the function

g whose domain of definition is E, such that g(p) = f(p) forp \in E. Definef and g
on R? by: f(0,0)-g(0,0) = 0, f(x,y) -xy?/(x* + y*), g(x, ») -xp*/(x* +")
if (x,y) #(0,0). Prove that f is bounded on R? that g is unbounded in every
neighborhood of (0, 0), and that f is nor continuous at (0, 0); nevertheless, the
restrictions of both f and g to every straight line in R? are continuous!

. Letf'be a real uniformly continuous function on the bounded set Ein R'. Prove

that f is bounded on E.
Show that the conclusion is false if boundedness of E is omitted from the
hypothesis.

. Show that the requirement in the definition of uniform continuity can be rephrased

as follows, in terms of diameters of sets: To every & >> 0 there exists a 6 > 0 such
that diam f(E) < c for all E< X with diam E <8.
Complete the details of the following alternative proof of Theorem 4.19: Iff is not
uniformly continuous, then for some & > 0 there are sequences {p,), {q,) in X such
that dx(p.,q) - 0 but dy(f(p.),f(g.)) > e. Use Theorem 2.37 to obtain a contra-
diction.
Suppose f is a uniformly continuous mapping of a metric space X into a metric
space Y and prove that {f(x,)} is a Cauchy sequence in Y for every Cauchy se-
quence {x,} in X. Use this result to give an alternative proof of the theorem stated
in Exercise 13.
A uniformly continuous function of a uniformly continuous function is uniformly
continuous.

State this more precisely and prove it.
Let E be a dense subset of a metric space X, and letf'be a uniformly continuous
real function defined on E. Prove thatf has a continuous extension from E to X
100 PRINCIPLES OF MATHEMATICAL ANALYSIS

14.

15.

16.

17.

18.

19.

(see Exercise S for terminology). (Uniqueness follows from Exercise 4.) Hint: For
each pe X and each positive integer n, let V,(p) be the set of all g \in  E with
d(p,q) <1/n. Use Exercise 9 to show that the intersection of the closures of the
sets f(Vi(p)), f(V2(p)), ..., consists of a single point, say g(p), of R!. Prove that
the function g so defined on X is the desired extension of f.

Could the range space R* be replaced by R*? By any compact metric space?
By any complete metric space? By any metric space?
Let I =[0, 1] be the closed unit interval. Suppose fis a continuous mapping of I
into I. Prove that f(x) = x for at least one x \in I.
Call a mapping of X into Y open if f(¥) is an open set in Y whenever Vis an open
set in X.

Prove that every continuous open mapping of R! into R' is monotonic.
Let [x] denote the largest integer contained in x, that is, [x] is the integer such
that x - 1 < [x] < x; and let (x) = x - [x] denote the fractional part of x. What
discontinuities do the functions [x] and (x) have?
Let f be a real function defined on (a, b). Prove that the set of points at which f
has a simple discontinuity is at most countable. Hint: Let E be the set on which
f(x-) <f(x+). With each point x of E, associate a triple (p,q, r) of rational
numbers such that
(a f(x-=) <p <f(x+),
(b) a <q <t<ximplies f(t) <p,
(c) x <t<r<b implies f(t) > p.
The set of all such triples is countable. Show that each triple is associated with at
most one point of E. Deal similarly with the other possible types of simple dis-
continuities.
Every rational x can be written in the form x = m/n, where n > 0, and m and » are
integers without any common divisors. When x = 0, we take n = 1. Consider the
function f defined on R! by

0 (x irrational),
fx) = (1 ( 7)

- x =|.

n n

Prove that fis continuous at every irrational point, and that f has a simple discon-
tinuity at every rational point.
Suppose f is a real function with domain R* which has the intermediate value
property: If f(a) < c < f(b), then f(x) = c for some x between a and b.

Suppose also, for every rational r, that the set of all x with f(x) = r is closed.

Prove that fis continuous.

Hint: If x, - xo but f(x,) > r > f(xo) for some r and all n, then f(t.) =r
for some t, between x, and x,; thus c, - xo. Find a contradiction. (N. J. Fine,
Amer. Math. Monthly, vol. 73, 1966, p. 782.)
20.

21.

22.

23.

CONTINUITY 101

If E is a nonempty subset of a metric space X, define the distance from xe X to E
by
pe(x) = inf d(x, z).
zeE

(a) Prove that p(x) = 0 if and only if x \in E.
(b) Prove that p; is a uniformly continuous function on X, by showing that
[pe(x) - pe(¥)| < d(x, »)

forall xe X, ye X. f

Hint: pp(x) < d(x, z) <d(x, y) + d(y, z), so that

pe(x) <d(x,y) + pe(¥).

Suppose K and F are disjoint sets in a metric space X, K is compact, F is closed.
Prove that there exists 8 > 0 such that d(p,q) >8 if pe K, ge F. Hint: pris a
continuous positive function on K.

Show that the conclusion may fail for two disjoint closed sets if neither is
compact.
Let A and B be disjoint nonempty closed sets in a metric space X, and define

pap)
= \in X).
A7) pa(p) + pa(p)
Show that fis a continuous function on X whose range lies in [0, 1], that f(p) =0
precisely on 4 and f(p) = 1 precisely on B. This establishes a converse of Exercise
3: Every closed set A = X is Z(f) for some continuous real fon X. Setting
V=f\0, 4), W=f"4a, 1),

show that Vand W are open and disjoint, and that A < V, B< W. (Thus pairs of
disjoint closed sets in a metric space can be covered by pairs of disjoint open sets.
This property of metric spaces is called normality.)

A real-valued function f defined in (a, b) is said to be convex if

Sx +1 = Ny) <M) +1 = Nf)

whenever a <x <b, a<y <b, 0 <A<1. Prove that every convex function is
continuous. Prove that every increasing convex function of a convex function is
convex. (For example, if fis convex, so is e’.)

If fis convex in (a, b) and if a << s << t <u < b, show that

fO) - 16) _ S00) = SG) _ SG) -f

t-s = u-s = u-t

. Assume that fis a continuous real function defined in (a, b) such that

x+y\ _ fx) +f»)
(252) a

for all x, y \in (a, b). Prove that fis convex.
102 PRINCIPLES OF MATHEMATICAL ANALYSIS

25. If A < R* and B = R, define 4 + B to be the set of all sums x + y with xe 4,
y \in B.
(a) If K is compact and C is closed in R*, prove that K + C is closed.
Hint: Take zc K+ C, put F =z - C, the set of all z- y with ye C. Then
K and F are disjoint. Choose 8 as in Exercise 21. Show that the open ball with
center z and radius & does not intersect K + C.
(b) Let « be an irrational real number. Let C, be the set of all integers, let C, be
the set of all na with ne C,. Show that C, and C; are closed subsets of R' whose
sum C, + C; is not closed, by showing that C; + C; is a countable dense subset
of R.
26. Suppose X, Y, Z are metric spaces, and Y is compact. Let f map X into Y, let
g be a continuous one-to-one mapping of Y into Z, and put A(x) = g(f(x)) for
x \in X.
Prove that f is uniformly continuous if 4 is uniformly continuous.
Hint: g=' has compact domain g(Y), and f(x) = g~'(h(x)).
Prove also that fis continuous if 4 is continuous.
Show (by modifying Example 4.21, or by finding a different example) that
the compactness of Y cannot be omitted from the hypotheses, even when X and
Z are compact.
5

DIFFERENTIATION

In this chapter we shall (except in the final section) confine our attention to real
functions defined on intervals or segments. This is not just a matter of con-
venience, since genuine differences appear when we pass from real functions to
vector-valued ones. Differentiation of functions defined on R¥ will be discussed

in Chap. 9.

THE DERIVATIVE OF A REAL FUNCTION

5.1 Definition Let f be defined (and real-valued) on [q, b]. For any x \in [a, b]
form the quotient

_SO)-f®)

== (a<t<b, t#x),

M ot)

and define

2) f(x) = lim c(r),
104 PRINCIPLES OF MATHEMATICAL ANALYSIS

provided this limit exists in accordance with Definition 4.1.

We thus associate with the function f a function f’ whose domain
is the set of points x at which the limit (2) exists; f’ is called the derivative
of f.

If f' is defined at a point x, we say that f is differentiable at x. If fis
defined at every point of a set E c [a, b], we say that fis differentiable on E.

It is possible to consider right-hand and left-hand limits in (2); this leads
to the definition of right-hand and left-hand derivatives. In particular, at the
endpoints a and b, the derivative, if it exists, is a right-hand or left-hand deriva-
tive, respectively. We shall not, however, discuss one-sided derivatives in any
detail.

If f is defined on a segment (a, b) and if a < x < b, then f'(x) is defined
by (1) and (2), as above. But f’(a) and f”(b) are not defined in this case.

5.2 Theorem Let f be defined on [a, b]. If fis differentiable at a point x \in [a, b],
then f is continuous at x.

Proof Ast - x, we have, by Theorem 4.4,

St) f(x) = fe 1 hei (t=x)-> f(x): 0=0.

The converse of this theorem is not true. It is easy to construct continuous
functions which fail to be differentiable at isolated points. In Chap. 7 we shall
even become acquainted with a function which is continuous on the whole line
without being differentiable at any point!

5.3 Theorem Suppose f and g are defined on [a, b] and are differentiable at a
point x \in [a, bl. Then f + g, fg, and f|g are differentiable at x, and

a (+9) x) =f) +g (x);
®) (fH) x) =f (X)g(x) + f(x)g' x);

© (2) co Lg),

In (c), we assume of course that g(x) # 0.
Proof (a) is clear, by Theorem 4.4. Let h = fg. Then

h(t) = h(x) = f(D[g(t) - g(x) + gf (1) = f(%)].
DIFFERENTIATION 105

If we divide this by # - x and note that f(t) - f(x) as t > x (Theorem 5.2),
(b) follows. Next, let &# =f/g. Then

We) - hx) 1 FO =f) gt) - g(x)
=x = sa [OT -/e) |

-Xx t-x
Letting t - x, and applying Theorems 4.4 and 5.2, we obtain (c).

5.4 Examples The derivative of any constant is clearly zero. If fis defined
by f(x) = x, then f(x) = 1. Repeated application of (b) and (c) then shows that
x" is differentiable, and that its derivative is nx"~?, for any integer n (if n <0,
we have to restrict ourselves to x # 0). Thus every polynomial is differentiable,
and so is every rational function, except at the points where the denominator is
zero.

The following theorem is known as the ‘‘chain rule” for differentiation.
It deals with differentiation of composite functions and is probably the most
important theorem about derivatives. We shall meet more general versions of it
in Chap. 9.

5.5 Theorem Suppose f is continuous on [a, bl, f'(x) exists at some point
x \in [a, b], g is defined on an interval I which contains the range of f, and g is
differentiable at the point f(x). If

h(t) =g(f(t)) (a<t<b),

then h is differentiable at x, and

3) h(x) = g'(fGNS (3).

Proof Let y = f(x). By the definition of the derivative, we have
(©) Sf) = f(x) = = fx) + u®)],
5) 9(s) = 9») = (s = Ng'B) + v()],

where te [a, b],sel,and u(r) >0ast- x,v(s) >0ass-y. Lets=/f(2).
Using first (5) and then (4), we obtain
h(t) - h(x) = g(f(1)) - 9(f (x)
=[f(t) =f] [g) + v(s)]
= =x) [f+ u®)] [g») + vis)

or, if t # x,

t) - h(x
© MOHD 1g) + oo 1) + utr)
Letting 7 - x, we see that s - y, by the continuity of f, so that the right
side of (6) tends to g'(y)f'(x), which gives (3).
106 PRINCIPLES OF MATHEMATICAL ANALYSIS

5.6 Examples
(a) Let f be defined by

a!
™ fx) = x sin T (x #0),
0 (x=0).

Taking for granted that the derivative of sin x is cos x (we shall
discuss the trigonometric functions in Chap. 8), we can apply Theorems
5.3 and 5.5 whenever x # 0, and obtain

(®) f(x) = sin L_ Loos L (x #0).
x x x

At x = 0, these theorems do not apply any longer, since 1/x is not defined
there, and we appeal directly to the definition: for 7 #0,

fO-fO_ 1

sin -
t-0 t

As t - 0, this does not tend to any limit, so that f'(0) does not exist.
(b) Let f be defined by

gin
©) fx) = x“ sin po (x #0),
0 (x =0),

As above, we obtain
(10) f(x) =2xsi cos (x #0)
x) = in - po x .

At x = 0, we appeal to the definition, and obtain

Sf) =f) | . 1 .
0 |= |tsin; < | (t #0);
letting t - 0, we see that
an f(0)=0.

Thus f is differentiable at all points x, but f’ is not a continuous
function, since cos (1/x) in (10) does not tend to a limit as x - 0.
DIFFERENTIATION 107

MEAN VALUE THEOREMS

5.7 Definition Let f be a real function defined on a metric space X. We say
that f has a local maximum at a point p \in Xif there exists 6 > 0 such that f(g) XT
f(p) for all g \in X with d(p, q) <6.

Local minima are defined likewise.

Our next theorem is the basis of many applications of differentiation.
5.8 Theorem Let f be dejined on [a,b]; iff has a local maximum at a point
x \in  (a,b), and iff'(x)exists, then f'(x) = 0.

The analogous statement for local minima is of course also true.

Proof Choose 6 in accordance with Definition 5.7, so that

a<x-0<x<x+0<bh.
Ifx - 6<t<x, then
fO-fa
t-Xx

Letting r - x, we see that f'(x)> 0.
If x <t<x +6, then

f0=-1e) _,
t- x ~ 7

which shows that f'(x) XT 0. Hence f(x) =0.

5.9 Theorem [ff and g are continuous real functions on [a,b] which are
differentiable in (a,b), then there is a point x \in (a,b) at which

(©?) - f(a)]g'(x) = [9(b) - g(a)]f" (x).
Note that differentiability is not required at the endpoints.
Proof Put
h(t) = [f() - fa]g(t) - [9(®) - ga]f (1)  (aa<z<b).
Then h is continuous on [a,b], h is differentiable in (a, b), and
(12) h(a) - f(b)g(a) - f(a)g(b) = h(D).

To prove the theorem, we have to show that A’(x) = 0 for some x \in (a, b).
If h is constant, this holds for every x  \in (a,b). If h(t) > h(a) for
some f \in  (a,b), let x be a point on [a,b]at which h attains its maximum
108 PRINCIPLES OF MATHEMATICAL ANALYSIS

(Theorem 4.16). By (12), x \in (a, b), and Theorem 5.8 shows that A(x) = 0.
If A(t) < h(a) for some t \in  (a, b), the same argument applies if we choose
for x a point on [a, b] where h attains its minimum.

This theorem is often called a generalized mean value theorenz; the following
special case is usually referred to as ""the' mean value theorem:

5.10 Theorem If fis a real continuous function on [a, b] which is differentiable
in (a, b), then there is a point x \in (a, b) at which
Sb) = fla) = (b - a) f(x).
Proof Take g(x) =x in Theorem 5.9.

5.11 Theorem Suppose f is differentiable in (a, b).
(a) ff'(x) 20 forall x \in (a, b), then f is monotonically increasing.
(b) If f'(x)=0 for all x \in (a, b), then fis constant.
(©) Iff(x) <0 forall x \in (a, b), then f is monotonically decreasing.

Proof All conclusions can be read off from the equation

Sx) = F(x) = (x2 - x)" (0),

which is valid, for each pair of numbers x,, x, in (a, b), for some x between
x; and Xx,.

THE CONTINUITY OF DERIVATIVES

We have already seen [Example 5.6(b)] that a function f may have a derivative
Jf" which exists at every point, but is discontinuous at some point. However, not
every function is a derivative. In particular, derivatives which exist at every
point of an interval have one important property in common with functions
which are continuous on an interval: Intermediate values are assumed (compare
Theorem 4.23). The precise statement follows.

5.12 Theorem Suppose fis a real differentiable function on [a, b] and suppose
f'(a) <A <f'(b). Then there is a point x \in (a, b) such that f(x) = A.
A similar result holds of course if f'(a) > f(b).
Proof Put g(r) =f(t) - It. Then g’(a) <0, so that g(t,) < g(a) for some
t; \in (a,b), and g'(b) > 0, so that g(r,) <g(b) for some , \in (a, b). Hence
g attains its minimum on [a, b] (Theorem 4.16) at some point x such that
a <x <b. By Theorem 5.8, g'(x) = 0. Hence f(x) = A.
DIFFERENTIATION 109

Corollary [ff is differentiable on [a,b], then f' cannot have any simple dis-
continuities on [a,b].

But f’ may very well have discontinuities of the second kind.

L'HOSPITAL'S RULE

The following theorem is frequently useful in the evaluation of limits.

5.13 Theorem Suppose f andg are real and differentiable in (a,b),and g'(x) #0
for all xe (a,b), where -o0 <a <b< +00. Suppose

(13) ACN as x- a.
g'(x)

If

(14) f(x) = 0 and g(x) > 0 as x > a,

or if

(15) g(x) > +o as x >a,

then

(16) ACER as x - a.
9(x)

The analogous statement is of course also true if x = b, or if g(x) > - 0
in (15). Let us note that we now use the limit concept in the extended sense of
Definition 4.33.

Proof We first consider the case in which - 00 <A < +00. Choose a
real number q such that A <q, and then choose r such that A <r <gq.
By (13) there is a point c \in (a,b) such that a < x < c implies

£1)
Fre

If a <x <y<ec, then Theorem 5.9 shows that there is a point te (x,y)
such that

17)

ff -fo» _f1 0 _
g(x) - g(») FOR

Suppose (14)holds. Letting x - a in (18), we see that

(18)

(19) -<r<gq (a<y<o).
g
110 PRINCIPLES OF MATHEMATICAL ANALYSIS

Next, suppose (15) holds. Keeping y fixed in (18), we can choose
a point c, \in (a, y) such that g(x) > g(y) and g(x) > 0 if a < x < c;. Multi-
plying (18) by [g(x) - g(»))/g(x), we obtain
[0 a0) 10) alice

0 0 gx) gl
If we let x =a in (20). (15) shows that there is a point c, \in (a, c;)
such that
21) TACT (a<x<ey)
g(x)
Summing up, (19) and (21)show that for any q, subject only to the
condition A < g, there is a point c, such that f(x)/g(x) <qif a <x <c,.
In the same manner, if -00 <A < +0, and p is chosen so that
p < A, we can find a point c3 such that
fx)
(22) p< 70) (a <x<cy),

and (16)follows from these two statements.

DERIVATIVES OF HIGHER ORDER

5.14 Definition Iff has a derivative f' on an interval, and iff" is itself differen-
tiable, we denote the derivative off' by f” and call ” the second derivative off.
Continuing in this manner, we obtain functions

0A A ALLY A
each of which is the derivative of the preceding one. fis called the nth deriva-
tive, or the derivative of order n, off.

In order for f™ (x )to exist at a point x, f® 1 (I) must exist in a neighbor-
hood of x (or in a one-sided neighborhood, if x is an endpoint of the interval
on which f is defined), and f"~!” must be differentiable at x. Since f*~ 1) must
exist in a neighborhood of x, /"~?) must be differentiable in that neighborhood.

TAYLOR'S THEOREM

5.15 Theorem Suppose f is a real function on [a,b], n is a positive integer,
SCY is continuous on [a,b] f(t) exists for every 1 \in  (a,b). Let a, f be distinct
points of [a.b],and define

n- (a)

23) P(t) = Z, 7s (t - a)k.

DIFFERENTIATION 111

Then there exists a point x between o and f3 such that

(n)
(4) 0 =pp + Day

For n = 1, this is just the mean value theorem. In general, the theorem
shows that f can be approximated by a polynomial of degree n - 1, and that
(24)allows us to estimate the error, if we know bounds on |f™(x)|.

Proof Let M be the number defined by
(25) SB) =P(p) + M(p - 2)"
and put
(26) 9g) =f) - P(t) - M(t- a)" (a<t<b).

We have to show that n!M = f™(x) for some x between « and f. By
(23)and (26),

27) g(t) =f") - nM (a<t<b).
Hence the proof will be complete if we can show that g(x) = 0 for some
x between a and f.
Since P¥ (a) = f® (a) for k =0,....n - 1, we have
(28) ga)y=g'a) =.= gD) =0.

Our choice of M shows that g(ff) =0, so that g'(x;) =0 for some x;
between a and f3, by the mean value theorem. Since g'(x) = 0, we conclude
similarly that g"(x;) = 0 for some x, between « and x,. After n steps we
arrive at the conclusion that g(x.) = 0 for some x, between « and x, _q,
that is, between x and f.

DIFFERENTIATION OF VECTOR-VALUED FUNCTIONS

5.16 Remarks Definition 5.1 applies without any change to complex functions
f defined on [a,b], and Theorems 5.2 and 5.3, as well as their proofs, remain
valid. Iff, and f, are the real and imaginary parts of f, that is, if

Fa) =A) + if2(t)
for a < t <b, where f;(t) and f,(c) are real, then we clearly have
(29) f= f{(x) + if;(x);

also, f is differentiable at x if and only if both f; and f, are differentiable at x.
112 PRINCIPLES OF MATHEMATICAL ANALYSIS

Passing to vector-valued functions in general, i.e., to functions f which
map [a, b] into some R*, we may still apply Definition 5.1 to define f(x). The
term c(c) in (1) is now, for each t, a point in R¥, and the limit in (2) is taken with
respect to the norm of Rt. In other words, f'(x) is that point of R* (if there is
one) for which

f(t fi
(30) lim [10 = bid 2 - f(x |e.
tx tr -
and f' is again a function with values in RF.
Iff,, ..., fi are the components of f, as defined in Theorem 4.10, then
(31 f=... f)

and f is differentiable at a point x if and only if each of the functions fj, ..., fx
is differentiable at x.

Theorem 5.2 is true in this context as well, and so is Theorem 5.3(a) and
(b), iffg is replaced by the inner product f « g (see Definition 4.3).

When we turn to the mean value theorem, however, and to one of its
consequences, namely, L’Hospital’s rule, the situation changes. The next two
examples will show that each of these results fails to be true for complex-valued
functions.

5.17 Example Define, for real x,
(32) f(x) =e™ = cos x + isin x.

(The last expression may be taken as the definition of the complex exponential
e'*; see Chap. 8 for a full discussion of these functions.) Then

(33) fam) -fO)=1-1=0,
but
(34) f(x) = ie™

so that [f'(x)| = 1 for all real x.
Thus Theorem 5.10 fails to hold in this case.

5.18 Example On the segment (0, 1), definef (x) = x and

39%) g(x) =x + x%e!¥,
Since |e'*| = 1 for all real t, we see that
(36) AC

x=0 ax)
Next,
(37)

so that
(38)
Hence
(39)
and so

(40)

20...
ge) =1+ fax - Zen O<x<l),

g(x) 2n-Uielon
Xx x
fel __1 x
g'(x) g(x)" 2-x
tim £5) Zo,
x=0 g(x)

DIFFERENTIATION 113

By (36) and (40), L’'Hospital’s rule fails in this case. Note also that g'(x) #0

on (0, 1), by (38).

However, there is a consequence of the mean value theorem which, for
purposes of applications, is almost as useful as Theorem 5.70, and which re-
mains true for vector-valued functions: From Theorem 5.10 it follows that

(41

lf) -fa] <b -a) sup. Lf (01

5.19 Theorem Suppose f is a continuous mapping of [a.b] into R* and f is
differentiable in (a, b). Then there exists x \in (a,b) such that

f(b) - fa)| <(b-a)|f'(x)|.
Proof" Put z = f(b) - f(a). and define
ot) =z-1(t)

Then c is a real-valued continuous function on [a,b ]which is differentia-
ble in (a,b). The mean value theorem shows therefore that

eb) - ea) = (b - a)p'(x) = (b - a)z- f(x)
for some x \in (a,b). On the other hand,
ob) - pla) =z f(b) -~z fla) =z z = |z|*.

(a<t<b).

The Schwarz inequality now gives
lz]? = (0 -a)lz-f(x)| <(b-a)|z| |[f()]

Hence |z| <(b- a)|f(x)|, which is the desired conclusion

1V. P. Havin translated the second edition of this book into Russian and added this
proof to the original one.
114 PRINCIPLES OF MATHEMATICAL ANALYSIS

EXERCISES
1. Let f be defined for all real x, and suppose that
[£G) =f] < (x ~ py)?
for all real x and y. Prove that fis constant.
2. Suppose f(x) >0in (a,b). Prove that fis strictly increasing in (a,b), and let g be
its inverse function. Prove that g is differentiable, and that

g (f(x) = (a<x <b).

x) G )

3. Suppose g is a real function on R', with bounded derivative (say |g’| <M). Fix
£>0, and define f(x) - x + eg(x). Prove that fis one-to-one if & is small enough.
(A set of admissible values of \in can be determined which depends only on M.)

4. If

Cy Crs Ce
7

n n-+1

>

where Co, ..., Cy are real constants, prove that the equation
Co + Cix4 ++ 4 Coy x" 1 4 Cyx"=0

has at least one real root between 0 and 1.
5. Suppose fis defined and differentiable for every x > 0, and f’(x) > 0 as x - + 0.
Put g(x) = f(x+ 1) - f(x). Prove that g(x) -0 as x - + oo.
6. Suppose
(a) fis continuous for x > 0,
(b) f(x) exists for x >0,

(e) (0) 0,
(d)f' is monotonically increasing.
Put
x
00 =" =o)

and prove that g is monotonically increasing.
7. Suppose f'(x),g'(x) exist, g'(x) #0, and f(x) = g(x) =0. Prove that

fa) _fx)
im-= =-
x g(t) g&)
(This holds also for complex functions.)
8. Suppose f' is continuous on [a,b]and \in >0. Prove that there exists 8 >0 such
that

fi) - fx) HE

py - flo <e
10.

11.

12.

13.

14.

15.

DIFFERENTIATION 115

whenever 0< | - x| <6, a<x<b, a<t<b. (This could be expressed by
saying that fis uniformly differentiable on [a,b Jif f’ is continuous on [a,b ].) Does
this hold for vector-valued functions too?

. Let f be a continuous real function on RY, of which it is known that f(x) exists

for all x #0 and that f(x) = 3 as x = 0. Does it follow that f’(0) exists?
Suppose fand g are complex differentiable functions on (0, 1), f(x) = 0,9(x) = 0,
f(x) =A, g'(x) Bas x -0, where A and Bare complex numbers, B #0. Prove
that
NEw)
xs0g(x) B
Compare with Example 5.18. Hint:

fx) (fo |. x

io lx

x
A.
PS BPE RTE)
Apply Theorem 5.13 to the real and imaginary parts of f(x)/x and g(x)/x.
Suppose fis defined in a neighborhood of x, and suppose f“(x) exists. Show that

lim fae Bp Soh) =2/(x) _ Sx).

Show by an example that the limit may exist even if f"(x) does not.
Hint: Use Theorem 5.13.
If f(x) =] x|3, compute f(x), f”(x) for all real x, and show that f* (0) does not
exist.
Suppose a and c are real numbers, c > 0, and fis defined on [-1, 1] by

(x? sin (|x|) Gf x #0),
0 - 0 (if x =0).

Prove the following statements:

(a) fis continuous if and only if a >0.

(b) £(0) exists if and only if a > I.

(c)f’ is bounded if and only if a > 1 c.

(d)f' is continuous if and only if a>1+c.

(e)f"(0) exists if and only if a > 2 + c.

(f)f” is bounded if and only if a >2 + 2c.

(g)f" is continuous if and only if a > 2 + 2c.

Let f be a differentiable real function defined in (a, b). Prove that fis convex if
and only iff' is monotonically increasing. Assume next that f”(x) exists for
every x \in (a,b),and prove that fis convex if and only if f(x) >0 forall x \in (a,b).
Suppose a  \in R', fis a twice-differentiable real function on (a, ©), and Mo, M,, M,
are the least upper bounds of |f(x)|, |f'(x)|, |f"(x)|, respectively, on (a, x).
Prove that

Mi <4M,M,.
116 PRINCIPLES OF MATHEMATICAL ANALYSIS

Hint: If h > 0, Taylor's theorem shows that

F0) = 35 Ue +20) = f= (6)
for some £ \in (x, x + 2h). Hence

M
1/0] <hM, +22.

To show that M? - 4M, M; can actually happen, take a = - 1, define
2x2 -1 (-=1<x<0),

fx)={x2-1
x41

0 <x<w),

and show that Mo =1, M, -=4, M, -=4.
Does M$ <4M,M; hold for vector-valued functions too?
16. Suppose fis twice-differentiable on (0, ez ) f” is bounded on (0, 2), and f(x)->0
as x - oc, Prove that f(x) => 0 as x -> ©,
Hint: Let a => oc in Exercise 15.
17. Suppose fis a real, three times differentiable function on [-/, 1], such that
f(=D)=0, fO=0, [fM)=1, [fO)=
Prove that f(x) > 3 for some x  \in (-1, 1).
Note that equality holds for #(x* + x2).
Hint: Use Theorem 5.15, with a =0 and 8 = +1, to show that there exist
s \in  (0,1) and t \in (-1, 0) such that
Fs) +r) -6.
18. Suppose fis a real function on [a,b], n is a positive integer, and f=" exists for
every t \in [a,b]. Let a, B, and P be as in Taylor's theorem (5.15). Define

Al SO - £8)

on) = -B

for t \in [a,b] ,t # B, differentiate
fO-f(B)=(t_ BO)

n - I times at f = qa, and derive the following version of Taylor's theorem:
Q"~V(a)
(n-1!
19. Suppose f is defined in (-1, 1) and f'(0) exists. Suppose -I <a, <Ba<1,

a, -»0, and B, -0 as n - ©. Define the difference quotients

S(Ba) - f(x)
Boman

f£(B) =P(B) + (B- ay.

D,=
20.

21.

22.

23.

DIFFERENTIATION 117

Prove the following statements:

(a) If a, <0 < B,, then lirn D, =£7(0).

(b) If 0 <a, < PB, and {8./(Bx - a,)} is bounded, then lin D, =f (0).
(c) Iff' is continuous in (- 1, 1), then lirn D, = f’(0).

Give an example in which fis differentiable in (-1, 1) (butf"' is not contin-
uous at 0) and in which a,,, 8, tend to 0 in such a way that lim D, exists but is differ-
ent from f7(0).

Formulate and prove an inequality which follows from Taylor's theorem and
which remains valid for vector-valued functions.

Let E be a closed subset of R'. We saw in Exercise 22, Chap. 4, that there is a
real continuous functiont on R' whose zero set is E. Is it possible, for each closed
set E, to find such an f which is differentiable on R', or one which is # times
differentiable, or even one which has derivatives of all orders on R'?

Suppose f is a real function on (- oc, «). Call x a fixed point off if f(x) = x.
(a) Iff is differentiable and f'(f) # 1 for every real t, prove that f has at most one
fixed point.

(b) Show that the function f defined by

SO =1+(1 +e)

has no fixed point, although 0 < f(t) <1 for all real t.

(c) However, if there is a constant A < | such that |f’(c)| < A for all real c, prove
that a fixed point x off exists, and that x = lirn x,, where x, is an arbitrary real
number and

Xn =f(xn)

forn=1,2,3....
(d) Show that the process described in (c)can be visualized by the zig-zag path

(xy, x2) => (x2, x2) > (x2, X3) > (x35, x3) > (x3, Xa) > ++.
The function f defined by

x3 +1

fx) = 3

has three fixed points, say a, f, y, where
-2<a<-1, 0<pB<l, l<y<2.

For arbitrarily chosen x,, define {x,} by setting X»+ = f(x,).
(a) If x; < a, prove that Xx, = - 2 as n - 00.

(b) If a < x, <7, prove that x, =f as n - 0.

(c) If y < xy, prove that x, > +0 as n > ©.

Thus B can be located by this method, but a and 7 cannot.
118 PRINCIPLES OF MATHEMATICAL ANALYSIS

24. The process described in part (c) of Exercise 22 can of course also be applied to

25.

functions that map (0, 20) to (0, ©).
Fix some a > 1, and put

a+ x
T+ x'

fx) = iE + 2). g(x) =

Both fand g have Va as their only fixed point in (0, 2). Try to explain, on the
basis of properties of fand g, why the convergence in Exercise 16, Chap. 3, is so
much more rapid than it is in Exercise 17. (Compare f’ and g', draw the zig-zags
suggested in Exercise 22.)

Do the same when 0 <a < 1.
Suppose f is twice differentiable on [a,b], f(a) <0, f(b) >0, f'(x)=8>0, and
0<f"(x)<M for all X \in  [a,b]. Let \in be the unique point in (a,b) at which
f& =o.

Complete the details in the following outline of Newton's method for com-
puting &.
(a) Choose xy \in (5,b), and define {x,} by

SOx)
S£(xn)

Interpret this geometrically, in terms of a tangent to the graph off.
(b) Prove that X,+1 < x. and that

Xny = Xn -

lim x, = &.
fog

(c) Use Taylor's theorem to show that

Stn)
2f"(xx)

Xop1- E=

(xn - 6)?

for some . \in (c, x,).
(d)If A =M]/28, deduce that

0S x0 - E52 [AC = OI

(Compare with Exercises 16 and 18, Chap. 3.)
(e) Show that Newton's method amounts to finding a fixed point of the function
g defined by

gx)=x- JO) ,
f(x)
How does g(x )behave for x near £?

(f)Put f(x) =x"? on (-o0, ©) and try Newton's method. What happens?
26.

27.

28.

29.

DIFFERENTIATION 119

Suppose fis differentiable on [a,b],f(a) =0, and there is a real number A such
that {f'(x)| <Alf(x) on [a,b]. Prove that f(x)=0 for all x \in [a,b]. Hint: Fix
Xo \in [a,b], let
Mo =sup| f(x), ~~ M.=sup|f' (x)!
for a <x < xo. For any such x,
[f(x] <M (xo - a)< A(xo - a)Mo.
Hence Mo =0 if A(xo -a)< 1. Thatis, f=0o0n [a,x,]. Proceed.
Let c be a real function defined on a rectangle R in the plane, given by a <x <b,
oI y I B. A solution of the initial-value problem
V=4(xy, yad=c (2Ilc<p)
is, by definition, a differentiable function fon [a,b Jsuch that f(a) =c, a I f(x) <B,
and
FO) =d(x, fx) (a<x<b).
Prove that such a problem has at most one solution if there is a constant A such
that
[(x, y2) = $x, y0)| < Aly2 = yi]
whenever (x, y1) \in R and (x,»2) \in R.
Hint: Apply Exercise 26 to the difference of two solutions. Note that this
uniqueness theorem does not hold for the initial-value problem

y=y17 ¥0)=0,
which has two solutions: f(x) = 0 and f(x) = x?/4. Find all other solutions.

Formulate and prove an analogous uniqueness theorem for systems of differential
equations of the form

Vi =x yi, 20, ya) =c; G=1,..., 4k).
Noie that this can be rewritten in the form
V=c(l,y), ya=c
where y = (y1, ..., yx) ranges over a k-cell, c is the mapping of a (k + 1)-cell
into the Euclidean k-space whose components are the functions iy... bx,and c

is the vector (c,,..., cx). Use Exercise 26, for vector-valued functions.
Specialize Exercise 28 by considering the system

Yi=yier G=1,..,k=1),
k
ye=f(x)- py 9x),

where f, 1, ... , gx are continuous real functions on [a,b ],and derive a uniqueness
theorem for solutions of the equation
YP + gx)y ED 4 + ga (0) + gi(x)y = f(x),

subject to initial conditions

ya)y=c, ya =c,, ces YEG) =k
6

THE RIEMANN-STIELTJES INTEGRAL

The present chapter is based on a definition of the Riemann integral which
depends very explicitly on the order structure of the real line. Accordingly,
we begin by discussing integration of real-valued functions on intervals. Ex-
tensions to complex- and vector-valued functions on intervals follow in later
sections. Integration over sets other than intervals is discussed in Chaps. 10
and 11.

DEFINITION AND EXISTENCE OF THE INTEGRAL

6.1 Definition Let [a,b] be a given interval. By a partition P of [a,b] we
mean a finite set of points xg, Xq, ..., X,, Where

a=x0<x< <x: <x, =b.
We write

Ax; =X; - Xi-1 (i=1,...,n).
THE RIEMANN-STIELTIES INTEGRAL 121

Now suppose fis a bounded real function defined on [a,b]. Corresponding to
each partition P of [a,b] we put

M; = sup f(x) (xi; <x <x),
m; = inf f(x) (xi Sx <x),

UPS) = 3. Mi Ax,

L(P,f) =) m;Ax;,
i=

and finally

(1 [ rx - inf UP, f),

a) |

where the inf and the sup are taken over all partitions P of [a,b]. The left
members of (1) and (2) are called the upper and lower Riemann integrals off
over [a,b], respectively.

If the upper and lower integrals are equal, we say that £ is Riemann-
integrable on [a,b], we write fe # (that is, # denotes the set of Riemann-
integrable functions), and we denote the common value of (1) and (2) by

fx = sup L(P, f),

a

4) [ra
or by

b
(4) ) f(x) dx.

This is the Riemann integral of f over [a,b]. Since f is bounded, there
exist two numbers, m and M, such that

mfx) M (asx<b).
Hence, for every P,
m(b-a)<L(P.f)< UP,f)< M(b-a),
so that the numbers L(P,£) and U(P, f) form a bounded set. This shows that
the upper and lower integrals are defined for every bounded function f. The
question of their equality, and hence the question of the integrability off, is a

more delicate one. Instead of investigating it separately for the Riemann integral,
we shall immediately consider a more general situation.
122 PRINCIPLES OF MATHEMATICAL ANALYSIS

6.2 Definition Let a be a monotonically increasing function on [a, b] (since
(a) and a(b) are finite, it follows that « is bounded on [a, b]). Corresponding to
each partition P of [a, b], we write

Aa; = a(x;) - a(x;-y).

It is clear that Aa; > 0. For any real function f which is bounded on [a, b]
we put

UP, f, a) = > M; Aa;

L(P.f, 0) = 3 m; Aa,
i=1
where M;, m1; have the same meaning as in Definition 6.1, and we define

-=b
(5) | fda = inf UP, f, 2),

b
©) [fds = sup LP. £, 0),

the inf and sup again being taken over all partitions.
If the left members of (5) and (6) are equal, we denote their common
value by

i [rae

or sometimes by

b
®) [1 da.

This is the Riemann-Stieltjes integral (or simply the Stieltjes integral) of
f with respect to «, over [a, b].

If (7) exists, i.e., if (5) and (6) are equal, we say thatf is integrable with
respect to a, in the Riemann sense, and write f \in 2(a).

By taking a(x) = x, the Riemann integral is seen to be a special case of
the Riemann-Stieltjes integral. Let us mention explicitly, however, that in the
general case « need not even be continuous.

A few words should be said about the notation. We prefer (7) to (8), since
the letter x which appears in (8) adds nothing to the content of (7). It is im-
material which letter we use to represent the so-called "variable of integration."
For instance, (8) is the same as

[L710 dot).
THE RIEMANN-STIELTJES INTEGRAL 123

The integral depends on f; a, a and b, but not on the variable of integration,
which may as well be omitted.

The role played by the variable of integration is quite analogous to that
of the index of summation: The two symbols

n
Cis 3 Cx
K=1

mean the same thing, since each means c; + c;, +... + c,.

Of course, no harm is done by inserting the variable of integration, and
in many cases it is actually convenient to do so.

We shall now investigate the existence of the integral (7). Without saying
so every time, f will be assumed real and bounded, and « monotonically increas-

ops

ing on [a,b ];and, when there can be no misunderstanding, we shall write [ in

place of [

6.3 Definition We say that the partition P* is a refinement of P if P “op

(that is, if every point of P is a point of P*). Given two partitions, Py and P,,
we say that P* is their common refinement if P* =P, u P,.

6.4 Theorem If P* is a refinement of P, then

9) L(P,f, 2) < L(P*,f, 2)
and
(10) U(P*, f, 0) < U(P, f, a).

Proof To prove (9), suppose first that P* contains just one point more
than P. Let this extra point be x* and suppose x;.;< x* <x;, where
x;-; and x; are two consecutive points of P. Put
wy = inf f(x) (xi I x I x%),
wy =inff(x) (x*I x <x).
Clearly wy =m; and w, > m;, where, as before,
m;=inff(x) (x <Sx=< xy)
Hence
L(P*,f,a) - L(P, f, a)
= wy[a(x*) - alx;-1)] + walalx;) - a(x*)] - mo(x;) - a(x;-4)]
= (wy - mla(x®) - ax; -)] + (Wy - mfalx;) - a(x*)] = 0.

If P* contains k points more than P, we repeat this reasoning k
times, and arrive at (9). The proof of (10) is analogous.
124 PRINCIPLES OF MATHEMATICAL ANALYSIS

b Tb
6.5 Theorem [ fda <| fda.
Proof Let P* be the common refinement of two partitions P, and P,.
By Theorem 6.4,
L(Py, fy 0) < L(P*, foo) < UP, f, 0) < U(P,, /, 0).
Hence
an L(Py, f, 0) < U(P2. f, 2).

If P, is fixed and the sup is taken over all Py, (11) gives

(12) J fda < U(P,, f, a).

The theorem follows by taking the inf over all P, in (12).

6.6 Theorem fe Ra) on [a,b] if and only if for every \in >0 there exists a
partition P such that

(13) UP, fa) - L(P, f, 2) <e.

Proof For every P we have

LPS) < [fdas [ras < UP, f, ).

Thus (13)implies

0< [rdu- [da <c.

Hence, if (13)can be satisfied for every £ > 0, we have

| fda = | fda,
that is, f \in Z(«).
Conversely, suppose f \in  %(x), and let \in > 0 be given. Then there

exist partitions P; and P, such that

(14) UP foo) = [fda <35,

(15) [rdn- 1p. 1, <3:
THE RIEMANN-STIELTIES INTEGRAL 125

We choose P to be the common refinement of P, and P,. Then Theorem
6.4, together with (14)and (15), shows that

UPS 0) < UP fi) < [fut = <L(Pr fo) + 6 SLPS) + 0,
so that (13)holds for this partition P.

Theorem 6.6 furnishes a convenient criterion for integrability. Before we

apply it, we state some closely related facts.

6.7

6.8

(16)

Theorem
(a) If (13) holds for some P and some  \in , then (13)holds (with the same  \in )

for every refinement of P.
(b) If (13) holds for P ={xq, ..., X,} and if s;, t; are arbitrary points in
[xi-1, X], then
Xz fis) = f(t) Aa; <e.
(c) If fe (x) and the hypotheses of (b) hold, then

<é.

3 fy d= [ f da

Proof Theorem 6.4 implies (a). Under the assumptions made in (b),
both f(s;) and f(1;) lie in [m;, M], so that |f(s;) - f(t;)] <M; = m;. Thus

$17) = up] Ba < UPS) = LIP. fr),

which proves (b). The obvious inequalities

L(P. fia) < 3 f(t) Aa; < U(P, fy)

LP, fi) < [fda < UP, fa)

and
prove (c).

Theorem [ff is continuous on [a,b] then fe R(x) on [a,b].
Proof Let &>0 be given. Choose # > 0 so that
[a(b) - a(a)ln <e.

Since f is uniformly continuous on [a,b] (Theorem 4.19), there exists a
6 > 0 such that

If) =f) <n
126 PRINCIPLES OF MATHEMATICAL ANALYSIS

if xe [a,b], tela, b], and |x -t| <0.
If P is any partition of [a,b] such that Ax, <9 for all i, then (16)
implies that
17) M,-m;<n (i-1,...,n)
and therefore

U(P.f, ®) - L(P, f, 0) = Yom, -~ my) Ax;

<n Ax; =nlad) - wa) <e
i=
By Theorem 6.6, f \in Z(®).

6.9 Theorem [ff is monotonic on [a,b],and if a is continuous on [a,b], then
fe Ra). (We still assume, of course, that a is monotonic.)

Proof Lete>0 be given. For any positive integer n, choose a partition
such that
a(b) - aa)

= 22 i= 1).
n

Ax

This is possible since a is continuous (Theorem 4.23).
We suppose that fis monotonically increasing (the proof is analogous
in the other case). Then

M;=f(x), my = f(x;-1) (i=1,...,n),
a(b) - 10

so that

UP. fs) - L(P,f, 0) = PY [fC - fxs]

- 40 0-10 Uf) -fa] <e

if n is taken large enough. By Theorem 6.6, f \in %(«).

6.10 Theorem Suppose f is bounded on [a,b], f has only finitely many points
of discontinuity on [a,b], and a is continuous at every point at which f is discon-
tinuous. Then f \in R(x).

Proof Lete > 0 be given. Put M = sup |f(x)|, let E be the set of points
at which f is discontinuous. Since E is finite and a is continuous at every
point of E, we can cover E by finitely many disjoint intervals [u;, v;] =
[a,b] such that the sum of the corresponding differences a(v;) - a(u;) is
less than  \in . Furthermore, we can place these intervals in such a way that
every point of En (a, b) lies in the interior of some [u;, v;].
THE RIEMANN-STIELTIES INTEGRAL 127

Remove the segments (4;, v;) from [a,b]. The remaining set K is
compact. Hence fis uniformly continuous on K, and there exists 6 > 0
such that | f(s) -f(c)| <cifseK, tek, |s-1| <9.

Now form a partition P ={xc, x;,..., x) of [a,b], as follows:
Each uj; occurs in P. Each vj occursin P. No point of any segment (u;, v;)
occurs in P. If x;_, is not one of the «;, then Ax; <6.

Note that M; - m; <2M for every i, and that M; - m; <E unless
X;-1 is one of the u;. Hence, as in the proof of Theorem 6.8,

UP, f, 2) - L(P, f, 2) < [a(b) - o(a)]e + 2M.

Since E is arbitrary, Theorem 6.6 shows that f' \in  Z(c).
Note: If fand « have a common point of discontinuity, then f need not

be in (x). Exercise 3 shows this.

6.11 Theorem Suppose f \in  R() on [a,b], m <f< M, c is continuous on
[m, M], and h(x) = c(f(x))on [a,b]. Then he R(x) on [a,b].

(18)

(19)

Proof Choose E> 0. Since c is uniformly continuous on [m,M], there
exists 6 >0 such that 6 <t and |a(s) - c(t)| <k if |s-t] <5 and
s, tem, M].

Since /' \in  Z(%), there is a partition P ={xg, X;,..., x,) of [a,b]such
that

U(P, f, a) = L(P, f, a) < 8°.

Let M;, m; have the same meaning as in Definition 6.7, and let ME, mf
be the analogous numbers for /. Divide the numbers 1, ..., n into two
classes: ie Aif M; -m;<6,i \in B if M;-m;>4.

For ie A, our choice of 6 shows that M} - mf <E.

For ie B, M}¥ -m} < 2K, where K=sup|c(t)|, n<t<M. By
(18), we have

3Y Aw; <Y (M; - mm) Ax; < 8?
ieB

ieB
so that ) ; gp Ax; <6. lt follows that
UP. hyo)- L(P, Jia) = Y (M}¥ - mf) Aa; + Ch - mf) Ao;
aA HS
< ooh) - ala)] + 2K8 < e[a(b) - a(a) + 2K].

Since c was arbitrary, Theorem 6.6 implies that he (a).
Remark: This theorem suggests the question: Just what functions are

Riemann-integrable? The answer is given by Theorem 11.33(b).
128 PRINCIPLES OF MATHEMATICAL ANALYSIS

PROPERTIES OF THE INTEGRAL

6.12 Theorem
(a) If fi \in Ra) arid f, \in A(2) on [a,b], then

Si +12 e A),

cf e R(a) for every constant c, and
b b b
[h+ryda=] fdas | fran,
h b
[ cfda = of fd.
(b) If fi(x) fox) on [a, b], then

b b
; fidad [ fy du.

(c) If fe A(a) on [a,b] and if a<c <b, then fe R(x) on [a,c] and on
[c, b], and

[ra +[ ran [yd
(d) Iffe RR) on [a,b]and if |f(x)| <M on [a,b], then
| [sax
(e) Iffe Ray) and f \in  Ray), then f \in  R(ay + ay) and

[rd +a = fdo + | fa:

< Mab) - a(a)].

iffe A(x) and c is a positive constant, then f \in R(ca) and
b b
[" fdca) = c | fda.

Proof Iff=f, +f; and P is any partition of [a,b], we have
(20) L(P, fy, 0) + L(P, f2, ®) < L(P, f, ®)
SUP, f,0) < UP, fi, 0) + UP, f2, »).

Iff, \in (a) and f, \in A(x), let \in > 0 be given. There are partitions P;
(j= 1, 2) such that

UP; fi, 0) = L(P;, f;, o) <&.
an

6.13

THE RIEMANN-STIELTJES INTEGRAL 129

These inequalities persist if P; and P, are replaced by their common
refinement P. Then (20) implies
UP, f, a) - L(P, f, x) < 2,

which proves that fe 2(a).

With this same P we have

UP, fy, 0) < [ fydu +c (G=1,2);
hence (20) implies
[fda < UP fi) <[fida+ [fy da + 2e

Since & was arbitrary, we conclude that

[fdu< {fdas § fda

If we replace f, and f; in (21) by -f, and -f,, the inequality is
reversed, and the equality is proved.

The proofs of the other assertions of Theorem 6./2 are so similar
that we omit the details. In part (c)the point is that (by passing to refine-
ments) we may restrict ourselves to partitions which contain the point c,
in approximating { f da.

Theorem [ffe A(x) and g \in A(%) on [a,b], then
(a) fge A):

ab b
bf] e #00 and | fd <| fl da.

Proof If we take c(c) = t2, Theorem 6.1 | shows that 2 \in &(x) if fe R(x).
The identity

dg=(f+9*-(/-9)
completes the proof of (a).
If we take c(z) = ||, Theorem 6.11 shows similarly that |f| \in (2).
Choose c = +1, so that
cf fdx>0.

| ffda| =c[fda=[cfdu<||f| da,

Then

since cf < |f]

6.14 Definition The unit step function I is defined by

B fo (x<0),
I= ll a>o0).
130 PRINCIPLES OF MATHEMATICAL ANALYSIS

6.15 Theorem If a <s<b, f is bounded on [a,b], f is continuous at s, and
a(x) = I(x - 5), then

b
) fda = f(s).

Proof Consider partitions P= {x,, x;,Xx,,x,), where x,=a, and
XxX; =8§<x,<x, =>b. Then

UP. f,0)=M,, LPfa)=m,.
Since f is continuous at s, we see that M, and m, converge to f(s) as

X; >.

6.16 Theorem Suppose c,>0 for 1, 2,3, ..., Zc, converges, {s,} is a sequence
of distinct points in (a,b), and

(22) a(x) = ¥ cu d(x = s,).

Let f be continuous on [a,b]. Then

b [=]
23) [[rda=3 cuss.

=1

Proof The comparison test shows that the series (22) converges for
every x. Its sum a(x) is evidently monotonic, and a(a) = 0, a(b) = Zc, .
(This is the type of function that occurred in Remark 4.31.)

Let £ > 0 be given, and choose N so that

9G
Yc. <e
N+1

Put
N 0
(x) = Y Cn I(x - Sn) a(x) = Y ca I(x - Sp).
n=1 N+1
By Theorems 6.12 and 6.15,
b N
249 [de = sents).
Since o,(b) - a,(a) <e,

25) < Ms,

[" fda

(26)

THE RIEMANN-STIELTJES INTEGRAL 131

where M = sup|f(x)|. Since a =a, + a,, it follows from (24) and (25)
that

[sa - 3 f(s) < ME.
“a i=1

If we let N- co, we obtain (23).

6.17 Theorem Assume a increases monotonically and «' \in R on [a,b]. Let f
be a bounded real function on [a,b].

an

(28)

(29)

(30)

E29)

Then f \in  R(x) if and only if fo’ \in R. In that case

b b
| fda = Jo f(x)’ (x) dx.
Proof Let e>0 be given and apply Theorem 6.6 to ci’ There is a par-
tition P = {x,, ..., x,,)of [a,b]such that
U(P,a'y - L(P,a')<e.
The mean value theorem furnishes points #; \in [x;_y, x;] such that
Aa; = o'(1;) Ax;
fori=1,...,n Ifs; e[x;_y, x;], then

Ax; <e,

LZ las) =o)
by (28)and Theorem 6.7(h). Put M = sup|f(x)|. Since
ha Ss) Ax; = 1p) Ax;
it follows from (29) that
16) Ag, = 3 flsds) Ax;| < Me.
In particular,
2. f(s) Ax, < U(P, fo) + Ms,

for all choices of s; \in [x;_,. x;], so that
UP, f, a) < U(P, fa") + Me.
The same argument leads from (30)to

UP, fx')< UP, f, 0) + ME.
Thus
|U(P, f, ci) - UP, fa')| < ME.
132 PRINCIPLES OF MATHEMATICAL ANALYSIS

Now note that (28) remains true if P is replaced by any refinement.
Hence (31) also remains true. We conclude that

“<b +b
[" fda - [fx (x) dx | < Me.
But c is arbitrary. Hence
=b Tb
(32) [[fdu=] fou) dx,

for any bounded f. The equality of the lower integrals follows from (30)
in exactly the same way. The theorem follows.

6.18 Remark The two preceding theorems illustrate the generality and
flexibility which are inherent in the Stieltjes process of integration. If ois a pure
step function [this is the name often given to functions of the form (22)], the
integral reduces to a finite or infinite series. If a has an integrable derivative.
the integral reduces to an ordinary Riemann integral. This makes it possible
in many cases to study series and integrals simultaneously, rather than separately.

To illustrate this point, consider a physical example. The moment of
inertia of a straight wire of unit length, about an axis through an endpoint, at
right angles to the wire, is

(33) [x dm

where m(x) is the mass contained in the interval [0,x]. If the wire is regarded
as having a continuous density p, that is, if m’(x) = p(x), then (33) turns into

1
(34) fo x? p(x) dx.

On the other hand, if the wire is composed of masses m; concentrated at
points x;, (33) becomes

(3%) > xi om.

Thus (33) contains (34) and (35) as special cases, but it contains much
more; for instance, the case in which m is continuous but not everywhere
differentiable.

6.19 Theorem (change ofvariable) Suppose c is a strictly increasing continuous
function that maps an interval [A,B] onto [a,b]. Suppose o is monotonically
increasing on [a,b] and f \in A(«) on [a,b]. Define and g on [A,B] by

(36) BO) = ale), 90) = Se).
THE RIEMANN-STIELTIESINTEGRAL 133

Then g \in R(f) and

(37)

(38)

(39)

B b
| gdp =| fdr.
4 Ja
Proof To each partition P = {Xy, ..., x,} of [a,b ]corresponds a partition
Q ={yos-..» Va of [A,B], s0 that x; = ca(p;). All partitions of [A,B]

are obtained in this way. Since the values taken by f on [x;_y, x;] are
exactly the same as those taken by g on [y;_, y;|, we see that

U(Q.9. B= U(P, f, 9), L(Q, g, B) = L(P,f, a).

Since f \in Z(x), P can be chosen so that both U(P, f, a) and L(P, f, a)
are close to { fda. Hence (38), combined with Theorem 6.6, shows that
g \in A(P) and that (37)holds. This completes the proof.

Let us note the following special case:
Take a(x) = x. Then ff = ca. Assume c'  \in # on [A,B]. If Theorem
6.17 is applied to the left side of (37), we obtain

I" fy dx - [ Fo)e'G) dy.
- la

KS

INTEGRATION AND DIFFERENTIATION

We still confine ourselves to real functions in this section. We shall show that
integration and differentiation are, in a certain sense, inverse operations.

6.20 Theorem Let fe on [a,b]. Fora I x <b, put

F(x) = I" feed.

Ri

Then F is continuous on [a,b]; furthermore, iff is continuous at a point xy of
[a,b], then F is differentiable at x, , and

F'(x0) = f(xo).

Proof Since fe, f is bounded. Suppose |f(#)| <M for a<t<b.
Ifa<x<y<hb, then

\F() - F(x)| = Ir di < M(y - x),

by Theorem 6.12(c) and (d). Given £ > 0, we see that
[FO ~ Ff <g,
134 PRINCIPLES OF MATHEMATICAL ANALYSIS

provided that |y - x|<e&/M. This proves continuity (and, in fact,
uniform continuity) of F.

Now suppose fis continuous at xo. Given & > 0, choose 6 > 0 such
that

f(t) = f(xo)| < &
if |t - xo) <6, and a <t <b. Hence, if
Xo-0<S§<xo<t<xo+06 and a<s<i<b,
we have, by Theorem 6.12(d),
Fu) -F)

1050 =| 5 [0 = son an] <2
- 8s
It follows that F'(x,) = f (xo).

6.21 The fundamental theorem of calculus ff \in %# on [a,b] and if there is
a differentiable function F on [a,b] such that F' =f, then

[ fi) dx = F(b) - F(a).

Proof Let £>0 be given. Choose a partition P = {xq, ..., X,} of [a,b]
so that U(P,f)- L(P,f )< &. The mean value theorem furnishes points
te [x;_4, x;] such that

F(x;) - F(x;_y) = f(t;) Ax;
fori=1,...,n. Thus
>. ft) Ax; = F(b) - F(a).
i=1
It now follows from Theorem 6.7(c) that

F(b) - F(a) - [ f(x) dx | <e.

Since this holds for every  \in c > 0, the proof is complete.

6.22 Theorem (integration by parts) Suppose F and G are differentiable func-
tionson [a,b], F' =fe R, and G' = g \in 92. Then

[7 (x)g(x) dx = F(b)G(b) - F(a)G(a) - [rece dx.

Proof Put H(x)= F(x)G(x) and apply Theorem 6.2/ to H and its deriv-
ative. Note that H' \in 92, by Theorem 6.13.
THE RIEMANN-STIELTJES INTEGRAL 135

INTEGRATION OF VECTOR-VALUED FUNCTIONS

6.23 Definition Let), ..., f, be real functions on [a, b], and let f = (f, ..., f})
be the corresponding mapping of [a, b] into R*. If « increases monotonically
on [a, b], to say that f \in Z(«) means that f; \in #(«) forj=1, ..., k. If this is the
case, we define

[fax = (I fds, [4 a).

In other words, [f du is the point in R* whose jth coordinate is [f; da.

It is clear that parts (a), (c), and (ec) of Theorem 6.12 are valid for these
vector-valued integrals; we simply apply the earlier results to each coordinate.
The same is true of Theorems 6.17, 6.20, and 6.21. To illustrate, we state the
analogue of Theorem 6.21.

6.24 Theorem IffandF map [a, b] into R*, iff \in # on [a, b), and if F' = {, then
b
| 1(t) dt = F(b) - F(a).

The analogue of Theorem  \in .13(b) offers some new features, however, at
least in its proof.

6.25 Theorem If f maps [a, b] into R* and if f \in R(x) for some monotonically
increasing function a on [a, b], then |f| \in #(«), and

(40) | [1 dif < | 11] da.

Proof Iff,,...,f, are the components of f, then
(41) fl = (ff + +S

By Theorem 6.11, each of the functions f belongs to Z(«); hence so does
their sum. Since x? is a continuous function of x, Theorem 4.17 shows
that the square-root function is continuous on [0, M], for every real M.
If we apply Theorem 6.11 once more, (41) shows that |f| \in Z(«).

To prove (40), puty = (yy, ..., »i), where y; = |/; do. Then we have
y = [f dx, and

¥12= Ty = Ly, [fda=[(T 0) dr
By the Schwarz inequality,
(42) Yr < lyf] (a<t1<b);
136 PRINCIPLES OF MATHEMATICAL ANALYSIS

hence Theorem 6.12(b) implies
3) v2 < Iy| [ If] da

If y =0, (40)is trivial. If y # 0, division of (43) by |y| gives (40).

RECTIFIABLE CURVES

We conclude this chapter with a topic of geometric interest which provides an
application of some of the preceding theory. The case k = 2 (i.e., the case of
plane curves) is of considerable importance in the study of analytic functions
of a complex variable.

6.26 Definition A continuous mapping y of an interval [a,b]into R* is called
a curve in R*. To emphasize the parameter interval [a,b], we may also say that
vis a curve on [a,b].

If y is one-to-one, y is called an arc.
If y(a) = y(b), y is said to be a closed curve.

It should be noted that we define a curve to be a mapping, not a point set.
Of course, with each curve y in R¥ there is associated a subset of R, namely
the range of y, but different curves may have the same range.

We associate to each partition P ={x,,..., X,} of [a,b] and to each
curve y on [a,b] the number

A, 3) = 3 13000) = yi].

The ith term in this sum is the distance (in R*) between the points y(x;_,) and
y(x;). Hence A(P, y) is the length of a polygonal path with vertices at y(xo),
y(xy), ..., y(x,), in this order. As our partition becomes finer and finer, this
polygon approaches the range of y more and more closely. This makes it seem
reasonable to define the length of y as

A(y) = sup A(P, y),

where the supremum is taken over all partitions of [a,b].

If A(y) < oo, we say that y is rectifiable.

In certain cases, A(y) is given by a Riemann integral. We shall prove this
for continuously differentiable curves, i.e., for curves y whose derivative y' is
continuous.
THE RIEMANN-STIELTJES INTEGRAL 137

6.27 Theorem If y' is continuous on [a, b], then y is rectifiable, and
b ’
AG) = [17] di.
Proof Ifa <x;_; <x, <b, then

[70x = y(xi-)| =

[vo a <[" vol.

Xi
Hence
b ’
AP. 3) < [170] de
for every partition P of [a, b]. Consequently,
4 ’
AG = [ 170) dr

To prove the opposite inequality, let c > 0 be given. Since 9’ is

uniformly continuous on [a, b], there exists § > 0 such that
[7'(s) = ¥'()] <e if |s-1t] <0.

Let P={x,,..., x,} be a partition of [a, b], with Ax; < J for all i. If
Xi-y <t < x;, it follows that

[YO < [v(x] +e
Hence

[7 1dr = 1y0e] Ax, +e Ax,

= IN [Y() + v(x) - yO] a +e Ax;

<

[vo a + IN [7/(x) - 70] al +o Ax;
< [yx - vxi- | + 28 Ax.
If we add these inequalities, we obtain
b
[17al dt < AP, 9) + 266 - a)

< A(Y) + 2&(b - a).
Since c was arbitrary,

[ire dr < A).

This completes the proof.
138 PRINCIPLES OF MATHEMATICAL ANALYSIS

EXERCISES

1. Suppose a increases on [a,b], a <xo <b, a is continuous at Xo, f(xo) =1, and
f(x) =0 if x # Xo. Prove that fe %(e) and that { fda=0.

2. Suppose f£>0, fis continuous on [a, b], and [* fx)ax =0. Prove that f(x)=0

for all x  \in [a, b]. (Compare this with Exercise 1.)

3. Define three functions B,, B82, Bs as follows: B,(x) =0 if x <0, B(x) =1 if x >0
for j=1, 2, 3; and B,(0) = 0, 8,(0) =1, B5(0) = 4. Let f be a bounded function on
[-1 11.

(a) Prove that fe Z(B,) if and only if (0+) = f(0) and that then
[fag = 1).

(b) State and prove a similar result for B..

(c) Prove that f \in  Z(B5) if and only if fis continuous at 0.
(d) If fis continuous at 0 prove that

(ras. (rag. ~[ rdps =r.

4. If f(x) = 0 for all irrational x, f(x) = 1 for all rational x, prove that f c Z on[a, b]
for any a <b.

5. Suppose fis a bounded real function on [a, b], and £2  \in % on [a,b]. Does it
follow that fe Z? Does the answer change if we assume that f3 \in 2?

6. Let P be the Cantor set constructed in Sec. 2.44. Let f be a bounded real function
on [0, 1] which is continuous at every point outside P. Prove that f \in  Z% on [0, 1].
Hint: P can be covered by finitely many segments whose total length can be made
as small as desired. Proceed as in Theorem 6.10.

7. Suppose fis a real function on (0, 1] and f \in  Z on [c, 1] for every c > 0. Define

I fa) dx = lim [ f(x) dx

if this limit exists (and is finite).

(a) If fe & on [0, 1], show that this definition of the integral agrees with the old
one.

(b) Construct a functionf such that the above limit exists, although it fails to exist
with | f} in place off.
8. Suppose f \in  & on [a, b] for every b>a where a is fixed. Define

Ed b
[ f(x) dx = lim | FQ) dx
a bw Ja
if this limit exists (and is finite). In that case, we say that the integral on the left

converges. If it also converges after f has been replaced by | f|, it is said to con-
verge absolutely.
10.

THE RIEMANN-STIELTJES INTEGRAL 139

Assume that f(x) > 0 and that f decreases monotonically on [1, «). Prove
that

[100 ax
converges if and only if
2m

converges. (This is the so-called ‘“‘integral test’ for convergence of series.)

. Show that integration by parts can sometimes be applied to the ‘improper’

integrals defined in Exercises 7 and 8. (State appropriate hypotheses, formulate a
theorem, and prove it.) For instance show that

“eosx d=" sin x
o 14+x Tro &

Show that one of these integrals converges absolutely, but that the other does not.
Let p and cg be positive real numbers such that

1
-t 1 =1,
pq
Prove the following statements.
(a) If u=>0 and v > 0, then
q
uv <4 i z.
p q

Equality holds if and only if u? = v7.
(b) If fe R(x), g \in R(x), f>0,g =>0, and

[rr aa= 1= [ora
then
[[rodn<t.

(c) If fand g are complex functions in %#(«), then

<([1riraa] {rate

This is Holder's inequality. When p=g=2 it is usually called the Schwarz
inequality. (Note that Theorem 1.35 is a very special case of this.)

(d) Show that Holder's inequality is also true for the ‘improper’ integrals de-
scribed in Exercises 7 and 8.

140 PRINCIPLES OF MATHEMATICAL ANALYSIS

11. Let a be a fixed increasing function on [a,b]. For u \in #(«), define

b 1/2
[lee] = \ judo] .

Suppose f, g, h \in #(«), and prove the triangle inequality
If -hll.<| -gllz+ lig - All:
as a consequence of the Schwarz inequality, as in the proof of Theorem 1.37.
12. With the notations of Exercise 11, suppose f \in  #(x) and £>0. Prove that
there exists a continuous function g on [a,b] such that [If - g|l, <e.
Hitrt: Let P= {xo0,..., Xx} be a suitable partition of [a, b], define
Xi -
Ax,

- Xi-1

t t
flxi-) + Ax, fxs)

g(t)
if xo << xi.
13. Define
ax+1
f(x) =| sin (12) dt.

(a) Prove that | f(x) <1/x if x >0.
Hint: Put t? = u and integrate by parts, to show that f(x) is equal to

cos (x?) __cos [(x+1)2]  &+tD2cos “4
TC 2eFD TJ, wer

Replace cos u by - 1.
(b) Prove that

2f(x) = cos (x?) = cos [ (x4 1] + r(x)

where |r(x)| <c/x and c is a constant.
(cc) Find the upper and lower limits of xf(x), as x - 0.

(d) Does [sin (t?)dt converge?
14. Deal similarly with
Axl
f(x)= | sin (e*) dt.
Show that
er f(x) <2
and that
e*f(x) = cos (e*) - e~* cos (e*+') + r(x),

where |r(x)| < Ce~*, for some constant C.
15.

16.

17.

18.

THE RIEMANN-STIELTJES INTEGRAL 141

Suppose f is a real, continuously differentiable function on [a, b], f(a) = f(b) =
and

pb
[ 2) dx=1.
Prove that

[areas ax=-y
and that
| [f7(0))? dx [ xX3f(x) dx > 1.
For 1 <s < «0, define
= 1
is) = Pp) pr

(This is Riemann’s zeta function, of great importance in the study of the distri-
bution of prime numbers.) Prove that

a w=s[ =k

and that

® t= [a
where [x] denotes the greatest integer < x.

Prove that the integral in (b) converges for all s > 0.

Hint: To prove (a), compute the difference between the integral over [1, N]
and the Nth partial sum of the series that defines {(s).
Suppose « increases monotonically on [a, b], g is continuous, and g(x) = G'(x)
for a <x <b. Prove that

[ato dx = G(B)a(b) - G(a)oa) ['G da,

Hint: Take g real, without loss of generality. Given P= {xo, X1, ..., Xn},
choose #; \in (x;-1, x;) so that g(#;) Ax; = G(x;) - G(x;-;). Show that

3 aleg(t) Ax, = G(b)a(b) - G(a)a(a) hy Glxi-1) Aa.

Let yy, v2, ys be curves in the complex plane, defined on [0, 27] by
yi(1) - e', ya(t) - ex, va(t) = e2®it sia (1/0)

Show that these three curves have the same range, that y, and y. are rectifiable,
that the length of y, is 2m, that the length of y, is 4m, and that y; is not rectifiable.
142 PRINCIPLES OF MATHEMATICAL ANALYSIS

19. Let y, be a curve in R¥, defined on [a, b]; let c be a continuous 1-1 mapping of
[c, d] onto [a, b], such that c(c) = a; and define y.(s) = y.(c(s)). Prove that vy, is
an arc, a closed curve, or a rectifiable curve if and only if the same is true of y,.
Prove that y, and vy, have the same length.
7

SEQUENCES AND SERIES OF FUNCTIONS

In the present chapter we confine our attention to complex-valued functions
(including the real-valued ones, of course), although many of the theorems and
proofs which follow extend without difficulty to vector-valued functions, and
even to mappings into general metric spaces. We choose to stay within this
simple framework in order to focus attention on the most important aspects of
the problems that arise when limit processes are interchanged.

DISCUSSION OF MAIN PROBLEM

7.1 Definition Suppose {f,}, n=1,2,3,..., is a sequence of functions
defined on a set FE, and suppose that the sequence of numbers { f,(x)} converges
for every x \in E. We can then define a function f by

M fe) =limf(x)  (xeE).
144 PRINCIPLES OF MATHEMATICAL ANALYSIS

Under these circumstances we say that {f,} converges on E and that f is
the limit, or the limit function, of { f,}. Sometimes we shall use a more descriptive
terminology and shall say that “{f,} converges to f pointwise on E” if (1) holds.
Similarly, if Zf,(x) converges for every x \in E, and if we define

a f0=F00  (xeB),

the function fis called the sum of the series Xf, .

The main problem which arises is to determine whether important
properties of functions are preserved under the limit operations (1) and (2).
For instance, if the functions f, are continuous, or differentiable, or integrable,
is the same true of the limit function? What are the relations between f, and 1”,
say, or between the integrals of f, and that of f?

To say that fis continuous at a limit point x means

lim f(2) =f).

Hence, to ask whether the limit of a sequence of continuous functions is con-
tinuous is the same as to ask whether
3) lim lim f(t) = lim lim f(z),

tx nro n+ tx
i.e., whether the order in which limit processes are carried out is immaterial.
On the left side of (3), we first let n - co, then t - x; on the right side, t -» x
first, then n - co.

We shall now show by means of several examples that limit processes
cannot in general be interchanged without affecting the result. Afterward, we
shall prove that under certain conditions the order in which limit operations
are carried out is immaterial.

Our first example, and the simplest one, concerns a ‘‘double sequence.”

7.2 Example Form=1,2,3,...,n=1,2,3,..., let

m
Sm n = .
! m+n
Then, for every fixed n,
lims, ,=1,
m= x
so that
4 lim lims,, =I.

n+ m-o
SEQUENCES AND SERIES OF FUNCTIONS 145

On the other hand, for every fixed m,

lim s,,,, = 0,

n-ro
so that
5) lim lim s, , = 0.
m= nw
7.3 Example Let

2

Fe = a (xreal;n=0,1,2,...),
and consider
6 3 yx
JO) = 00 = 2 fy

Since f,(0) = 0, we have (0) = 0. For x # 0, the last series in (6) is a convergent
geometric series with sum 1 + x? (Theorem 3.26). Hence

0 (x =0),

© J =] +x (x #0),

so that a convergent series of continuous functions may have a discontinuous
sum.

7.4 Example Form =1,2,3,..., put

Soul) = lim (cos m!nx)?".

n=

When m!x is an integer, f,,(x) = 1. For all other values of x, f,,(x) = 0. Now let

f(x) = lim f(x).
m= 0

For irrational x, f,,(x) = 0 for every m; hence f(x) =0. For rational x, say
x = p/q, where p and g are integers, we see that m!x is an integer if m > g, so
that f(x) = 1. Hence
Lo Von [0 (x irrational),
® Jim lim (cos minx) 1 (x rational).

We have thus obtained an everywhere discontinuous limit function, which
is not Riemann-integrable (Exercise 4, Chap. 6).
146 PRINCIPLES OF MATHEMATICAL ANALYSIS

7.5 Example Let

sin nx
Jn
f(x) =lim f(x) =0.

®) Julx) =

and

(xreal,n=1,2,3,...),

Then f'(x) = 0, and
fax) = Jn COS nx,

so that {f,} does not converge to f’. For instance,
fi0) = /n = +o

as n - oo, whereas (0) = 0.

7.6 Example Let
(10) Li) =n*x(1 =x)" 0<x<l,n=1,23,...).
For 0 < x <1, we have

lim f(x) = 0,

by Theorem 3.20(d). Since f,(0) = 0, we see that
(11) lim f(x) = 0 O<x<l).

n- ow

A simple calculation shows that

1 1
[ x(1 = x2) dx = rt
Thus, in spite of (11),
1 n?
[fe de=5- + 0

as n- ow.
If, in (10), we replace n? by n, (11) still holds, but we now have

1 n 1
li =lm -=_,
a [50 de=lim 27573
whereas

I | lim £10] dx = 0.

n-+oo
SEQUENCES AND SERIES OF FUNCTIONS 147

Thus the limit of the integral need not be equal to the integral of the limit,
even if both are finite.

After these examples, which show what can go wrong if limit processes
are interchanged carelessly, we now define a new mode of convergence, stronger
than pointwise convergence as defined in Definition 7.1, which will enable us to
arrive at positive results.

UNIFORM CONVERGENCE

7.7 Definition We say that a sequence of functions {f,},n=1,2,3,...,
converges uniformly on E to a function f if for every c > 0 there is an integer N
such that » > N implies

(12) 100) - (0) <e

for all x \in E.

It is clear that every uniformly convergent sequence is pointwise con-
vergent. Quite explicitly, the difference between the two concepts is this: If {£,}
converges pointwise on E, then there exists a function f such that, for every
e > 0, and for every x \in E, there is an integer N, depending on c and on x, such
that (12) holds if n > N; if {f,} converges uniformly on E, it is possible, for each
c > 0, to find one integer N which will do for all x \in E.

We say that the series Zf,(x) converges uniformly on FE if the sequence
{s,} of partial sums defined by

M=

Six) = s(x)

i=1

converges uniformly on E.
The Cauchy criterion for uniform convergence is as follows.

7.8 Theorem The sequence of functions {f,}, defined on E, converges uniformly
on E if and only if for every c > 0 there exists an integer N such that m > N,
n> N, x \in E implies

(13) [x)= fulX) | < &.

Proof Suppose {f,} converges uniformly on E, and let f be the limit
function. Then there is an integer N such that n > N, x \in E implies

0 =f] <3»
so that
00) =u] < 1100) =F (| + f() = fy) | <

ifn>N,m>N, xekE.
148 PRINCIPLES OF MATHEMATICAL ANALYSIS

Conversely, suppose the Cauchy condition holds. By Theorem 3.11,
the sequence {f,(x)} converges, for every x, to a limit which we may call
f(x). Thus the sequence {f,} converges on E, to f. We have to prove that
the convergence is uniform.

Let c > 0 be given, and choose N such that (13) holds. Fix n, and
let m - oo in (13). Since f,,(x) = f(x) as m - co, this gives

(14) Ix) =f) <e

for every n > N and every x \in E, which completes the proof.
The following criterion is sometimes useful.

7.9 Theorem Suppose

lim f(x) =/(x) (xeE).

Put
M,= sup [fulx) = f(x).

Then f, = f uniformly on E if and only if M,,- 0 as n - oo.

Since this is an immediate consequence of Definition 7.7, we omit the
details of the proof.

For series, there is a very convenient test for uniform convergence, due to
Weierstrass.
7.10 Theorem Suppose{f,} is a sequence of functions defined on E, and suppose
fix) <M, (xeE,n=1,2,3,...).
Then Xf, converges uniformly on E if EM, converges.

Note that the converse is not asserted (and is, in fact, not true).

Proof If TM, converges, then, for arbitrary c > 0,

370)

<> M;<ce (x  \in E),

provided m and n are large enough. Uniform convergence now follows
from Theorem 7.8.
SEQUENCES AND SERIES OF FUNCTIONS 149

UNIFORM CONVERGENCE AND CONTINUITY

7.11 Theorem Suppose f, - f uniformly on a set E in a metric space. Let x be
a limit point of E, and suppose that

(15) lim £,(2) =4, a®=123..).
Then {A,} converges, and
(16) lim £2) =lim4,.
In other words, the conclusion is ft
a7 lim lim £,(t) = lim lim £,(1).

Proof Let c > 0 be given. By the uniform convergence of {f,}, there
exists N such that n > N, m > N, t \in E imply

(18) [£0 - ful) | Se.
Letting c - x in (18), we obtain
|4, - An | <e

for n> N,m>N, so that {4,} is a Cauchy sequence and therefore
converges, say to A.
Next,

(19) FO -A|<|fO)-£O1+ HO - 4,1 + 14, - 4].

We first choose n such that
20) FO ~ £0] <5

for all c \in E (this is possible by the uniform convergence), and such that
QI 4, =A] <5:

Then, for this n, we choose a neighborhood V of x such that

a) 0) = Au] <3

if te VANE, t#x.
Substituting the inequalities (20) to (22) into (19), we see that

[f()- 4] <e,
provided r \in Vn E, t#x. This is equivalent to (16).
150 PRINCIPLES OF MATHEMATICAL ANALYSIS

7.12 Theorem If{f,} is a sequence of continuous functions on E, and if f, > f
uniformly on E, then fis continuous on E.

This very important result is an immediate corollary of Theorem 7.11.

The converse is not true; that is, a sequence of continuous functions may
converge to a continuous function, although the convergence is not uniform.
Example 7.6 is of this kind (to see this, apply Theorem 7.9). But there is a case
in which we can assert the converse.

7.13 Theorem Suppose K is compact, and

(a) {/.} is a sequence of continuous functions on K,
(b) {f.} converges pointwise to a continuous function f on K,
(c) fix) =fos (x) forall xeK,n=1,2,3,....
Then f, - f uniformly on K.
Proof Put g,=f,-f Then g, is continuous, g, -»0 pointwise, and
gn =9g,+y. We have to prove that g, - 0 uniformly on XK.

Let c > 0 be given. Let K, be the set of all xe K with g,(x) > e.
Since g,, is continuous, K,, is closed (Theorem 4.8), hence compact (Theorem
2.35). Since g, > g,+1, We have K, > K,,. Fix xe K. Since g,(x) -0,
we see that x c K,, if n is sufficiently large. Thus x c N K,. In other words,
N K, is empty. Hence Ky is empty for some N (Theorem 2.36). It follows
that 0 < g,(x) <eforall xe Kand forall» > N. This proves the theorem.

Let us note that compactness is really needed here. For instance, if
1
fx) =-- O<x<l;n=1,2,3..)
nx +1
then f(x) -» 0 monotonically in (0, 1), but the convergence is not uniform.

7.14 Definition If X is a metric space, ¥(X) will denote the set of all complex-
valued, continuous, bounded functions with domain X.

[Note that boundedness is redundant if X is compact (Theorem 4.15).
Thus %(X) consists of all complex continuous functions on X if X is compact.]
We associate with each fe ¥(X) its supremum norm

If = sup [SG
Since f is assumed to be bounded, [[f|< co. It is obvious that | f| = 0 only if
f(x) =0 for every x \in X, that is, only if f=0. If # =f + g, then
Ih) | < fC) | + 1g) | < If + lgll
for all x \in X; hence
If + gl < If + lgll.
SEQUENCES AND SERIES OF FUNCTIONS 151

If we define the distance between fe ¥(X) and g \in  \in (X) to be [If -g],
it follows that Axioms 2.15 for a metric are satisfied.

We have thus made  \in (X) into a metric space.

Theorem 7.9 can be rephrased as follows:

A sequence {f,} converges to f with respect to the metric of  \in (X) if and
only if f,, = f uniformly on X.

Accordingly, closed subsets of %(X) are sometimes called uniformly
closed, the closure of a set &/ =  \in (X) is called its uniform closure, and so on.

7.15 Theorem The above metric makes ¥(X) into a complete metric space.

Proof Let{f,} be a Cauchy sequence in ¥(X). This means that to each
ec > 0 corresponds an N such that | f, -f,| <& if n> N and m > N.
It follows (by Theorem 7.8) that there is a function f with domain X to
which {f,} converges uniformly. By Theorem 7.12, f is continuous.
Moreover, f is bounded, since there is an n such that |f(x) - f,(x)| <1
for all x \in X, and f, is bounded.

Thus fe%(X), and since f, -f uniformly on X, we have
If-=fol »0asn- co.

UNIFORM CONVERGENCE AND INTEGRATION

7.16 Theorem Let a be monotonically increasing on (a, b]. Suppose f, \in &(«)
onla,b], forn=1,2,3,..., and suppose f, - f uniformly on (a, b]. Then f \in R(x)
on [a, b], and

(23) | ’ fda = lim | ’r da.

(The existence of the limit is part of the conclusion.)

Proof It suffices to prove this for real f,. Put

(24) &, = sup |f(x) = f(x),

the supremum being taken over a <x <b. Then

Some <f<Sf +8,
so that the upper and lower integrals of f (see Definition 6.2) satisfy

25) [th ~ 6) du < [ fda <[ra< +6) de.

Hence

0< [ faa - [ fn < 26,[u(b) - a(a)].
152 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since c, = 0 as n - co (Theorem 7.9), the upper and lower integrals of f
are equal.
Thus f \in Z(x). Another application of (25) now yields

(26) Ix fx - [4 a

This implies (23).

< ead) - oa).

Corollary If f, \in #(a) on [a, b] and if

fx) = py fx) (a<x<D),
the series converging uniformly on [a, b), then

[ra=% [fan

In other words, the series may be integrated term by term.

UNIFORM CONVERGENCE AND DIFFERENTIATION

We have already seen, in Example 7.5, that uniform convergence of { f,} implies
nothing about the sequence {f,}. Thus stronger hypotheses are required for the
assertion that f;) - f'if f, = f.

7.17 Theorem Suppose {f,} is a sequence of functions, differentiable on [a, b]
and such that {f,(x,)} converges for some point x, on [a,b]. If {f,} converges
uniformly on [a, b), then {{,} converges uniformly on [a, b], to a function f, and

a7) Sa=lmfix)  (a<x<b).
Proof Lete > 0 be given. Choose N such that n > N, m > N, implies
8) £0) = ful) | <5
and

(29) |fa®) 01 < 35 p (aa<t <b).
(30)

 \in 20)

(32)

(33)

SEQUENCES AND SERIES OF FUNCTIONS 153

If we apply the mean value theorem 5.19 to the function f, - f,,, (29)
shows that
[x -tle e

2W-a) 2

a) = fu) = fo) + fu) | <

for any x and f on [a, b], if n> N, m > N. The inequality
1x) = fu) |< 1fu) = SonlX) = Sul) + SXo) | + 1Fa(¥0) = Su(x0) |
implies, by (28) and (30), that
[fux) - f(x) | <e (a<x<bn=N,m=N),
so that {f,} converges uniformly on [a, 5]. Let
fx) =limf(x) (a<x<b).

n-+ow
Let us now fix a point x on [a, b] and define

J) = 10) _ SO -fx)
-X

t t-Xx

ba) = é()

fora <t <b, t# x. Then
lim §()=fix)  (n=1,2,3,..).
=x

The first inequality in (30) shows that

(6a) - Gu(D) | < (n= N,mz=N),

&
2(b - a)

so that {c,} converges uniformly, for 7 # x. Since {f,} converges to f, we
conclude from (31) that

lim c,(t) = c(1)

n-+o

uniformly fora <t <b, t # x.
If we now apply Theorem 7.11 to {c,}, (32) and (33) show that

lim c(t) = lim f(x);
tx n-+w
and this is (27), by the definition of c(c).

Remark: If the continuity of the functions f, is assumed in addition to

the above hypotheses, then a much shorter proof of (27) can be based on
Theorem 7.16 and the fundamental theorem of calculus.
154 PRINCIPLES OF MATHEMATICAL ANALYSIS

7.18 Theorem There exists a real continuous function on the real line which is
nowhere differentiable.

Proof Define
(34) o(x) = |x] (-1<x<1)

and extend the definition of (x) to all real x by requiring that
(35 a(x +2) = p(x).

Then, for all 5s and c,

(36) lp) =e] < |s-1].
In particular, c is continuous on R'. Define

(37 J) = ¥ area.

Since 0 <c <1, Theorem 7.10 shows that the series (37) converges
uniformly on R!. By Theorem 7.12, fis continuous on R.
Now fix a real number x and a positive integer m. Put
(38) ES
where the sign is so chosen that no integer lies between 4™x and 4™(x + J,,).
This can be done, since 4™|0,,| = +. Define
_ p(x + 5.) - c(4"x)
hE
When n > m, then 45, is an even integer, so that y, =0. When0 <n <m,
(36) implies that |y,| <4".
Since |y,,| = 4™, we conclude that

Sx + 6m) - f(x)

(39)

Om
m=1
>3"- 33
n=0
=46"+ 1)

As m- ©, 6,, ~ 0. It follows that fis not differentiable at x.

EQUICONTINUOUS FAMILIES OF FUNCTIONS

In Theorem 3.6 we saw that every bounded sequence of complex numbers
contains a convergent subsequence, and the question arises whether something
similar is true for sequences of functions. To make the question more precise,
we shall define two kinds of boundedness.
SEQUENCES AND SERIES OF FUNCTIONS 155

7.19 Definition Let {f,} be a sequence of functions defined on a set E.

We say that{f,} is pointwise bounded on E if the sequence { f,(x)} is bounded
for every x \in E, that is, if there exists a finite-valued function c defined on E
such that

i) <o(x) (xeEn=1,23..).

We say that {f,} is uniformly bounded on E if there exists a number M
such that

fi) <M (xeE,n=1,2,3,...).

Now if { f,} is pointwise bounded on E and E| is a countable subset of E,
it is always possible to find a subsequence {f, } such that {f, (x)} converges for
every x \in E;. This can be done by the diagonal process which is used in the
proof of Theorem 7.23.

However, even if {f,} is a uniformly bounded sequence of continuous
functions on a compact set E, there need not exist a subsequence which con-
verges pointwise on E. In the following example, this would be quite trouble-
some to prove with the equipment which we have at hand so far, but the proof
is quite simple if we appeal to a theorem from Chap. 11.

7.20 Example Let
fu(x) = sin nx O0O<x<2n,n=1,23,...).

Suppose there exists a sequence {nm} such that {sin n,x} converges, for every
x \in [0, 2n]. In that case we must have

lim (sin mx - sin m4 x) = 0 0 <x <2nm);

k=

hence

(40) lim (sin mx - sin mx)? =0 (0 < x <2n).
k=

By Lebesgue’s theorem concerning integration of boundedly convergent
sequences (Theorem 11.32), (40) implies
2n
(41) lim [ (sin mx - sin nx) dx = 0.
k= “0

But a simple calculation shows that
2n
[ (sin mex - sin ny, x)? dx = 2m,
0

which contradicts (41).
156 PRINCIPLES OF MATHEMATICAL ANALYSIS

Another question is whether every convergent sequence contains a
uniformly convergent subsequence. Our next example will show that this
need not be so, even if the sequence is uniformly bounded on a compact set.
(Example 7.6 shows that a sequence of bounded functions may converge
without being uniformly bounded; but it is trivial to see that uniform conver-
gence of a sequence of bounded functions implies uniform boundedness.)

7.21 Example Let

x2

FO = ara ay

O<x<ln=123,..).

Then [f(x)| <1, so that {/,} is uniformly bounded on [0, 1]. Also
limf(x)=0 ©<x<I),

n= ow
but

43) = (n=1,23..)

so that no subsequence can converge uniformly on [0, I].

The concept which is needed in this connection is that of equicontinuity;
it is given in the following definition.

7.22 Definition A family &# of complex functions f defined on a set E in a
metric space X is said to be equicontinuous on E if for every &c > 0 there exists a
6 > 0 such that

fx) =f) <e

whenever d(x, y) < 9d, x \in E, y \in E, and fe #. Here d denotes the metric of X.

It is clear that every member of an equicontinuous family is uniformly
continuous.

The sequence of Example 7.21 is not equicontinuous.

Theorems 7.24 and 7.25 will show that there is a very close relation
between equicontinuity, on the one hand, and uniform convergence of sequences
of continuous functions, on the other. But first we describe a selection process
which has nothing to do with continuity.

7.23 Theorem If{f,} is a pointwise bounded sequence of complex functions on
a countable set E, then {f,} has a subsequence {f, } such that {f, (x)} converges for
every x \in E.
SEQUENCES AND SERIES OF FUNCTIONS 157

Proof Let{x;},i=1,2,3,..., be the points of E, arranged in a sequence.
Since {f,(x,)} is bounded, there exists a subsequence, which we shall
denote by {f] 4}, such that {f; ,(x,)} converges as k » co.

Let us now consider sequences Sy, S,, Sy, ..., which we represent
by the array

Sy: fia fiz fis fia
Sat fou faz fas Sra
Sy fin fiz S33 Sia

and which have the following properties:

(a) S, is a subsequence of S,_,, forn=2,3,4,....

) {fux(x,)} converges, as k- co (the boundedness of {f,(x,)}

makes it possible to choose S, in this way);

(c) The order in which the functions appear is the same in each se-

quence; i.e., if one function precedes another in S|, they are in the same

relation in every S,, until one or the other is deleted. Hence, when

going from one row in the above array to the next below, functions

may move to the left but never to the right.

We now go down the diagonal of the array; i.e., we consider the
sequence
S: fin faz fiz Saar

By (c), the sequence S (except possibly its first n - 1 terms) is a sub-
sequence of S,, for n=1,2,3,.... Hence (b) implies that {f, .(x)}
converges, as n - oo, for every x; \in E.

7.24 Theorem If K is a compact metric space, if f, \in c(K) for n=1,2,3, ...,
and if {f,} converges uniformly on K, then{f,} is equicontinuous on K.

42)

43)

Proof Let c >0 be given. Since {f,} converges uniformly, there is an
integer N such that

Ifa=Ssll<e (n> N).

(See Definition 7.14.) Since continuous functions are uniformly con-
tinuous on compact sets, there is a é > 0 such that

fix) = fin) | <e

ifl<i<N and d(x,y) <9.
If n > N and d(x, y) < 9, it follows that

x) =) < fix) = AX) [+ IE) -AO) | + 1fv0) = £0) | < 3e.

In conjunction with (43), this proves the theorem.
158 PRINCIPLES OF MATHEMATICAL ANALYSIS

7.25 Theorem If K is compact, if f,  \in e c(K) for n=1,2,3,..., and if {f,} is
pointwise bounded and equicontinuous on K, then

(44)

(45)

(46)

(a) {f,} is uniformly bounded on K,
(b) {f.} contains a uniformly convergent subsequence.

Proof

(a) Let e > 0 be given and choose § > 0, in accordance with Definition
7.22, so that

1x) =f) <e

for all n, provided that d(x, y) <4.

Since K is compact, there are finitely many points p,,...,p, in K
such that to every x \in K corresponds at least one p; with d(x, p;) <4.
Since {f,} is pointwise bounded, there exist M; < oo such that |f,(p,)| < M,
for all n. If M=max(M,,...,M,), then |f(x)| <M +c for every
x \in K. This proves (a).

(b) Let E be a countable dense subset of K. (For the existence of such a
set E, see Exercise 25, Chap. 2.) Theorem 7.23 shows that {f,} has a
subsequence {f, } such that {f, (x)} converges for every x \in E.

Put f, =g;, to simplify the notation. We shall prove that {g;}
converges uniformly on XK.

Let c > 0, and pick 6 > 0 as in the beginning of this proof. Let
V(x, 8) be the set of all y \in K with d(x, y) <4. Since E is dense in K, and
K is compact, there are finitely many points x, ..., x,, in E such that

Ke V(x, 8) uu V(x, 9d).

Since {g.(x)} converges for every x \in E, there is an integer N such
that

lgi(xs) - g(x) | <e

whenever i> N,j>N,1 <s<m.
If x \in K, (45) shows that x \in V(x,, J) for some s, so that

lg:(x) -gi(x)| <e
for every i. If i > N and j > N, it follows from (46) that

g(x) = g(x) | < 19x) - gi(x,) | +g:(x0) - g(x) | + 1g,(x) - g(x) |
< 3e.

This completes the proof.
SEQUENCES AND SERIES OF FUNCTIONS 159

THE STONE-WEIERSTRASS THEOREM

7.26 Theorem If fis a continuous complex function on |[a, bl, there exists a
sequence of polynomials P, such that

lim P(x) = f(x)

n-+o

uniformly on (a, b]. If f is real, the P, may be taken real.

This is the form in which the theorem was originally discovered by

Weierstrass.

(47)

(48)

(49)

Proof We may assume, without loss of generality, that [a, b] = [0, 1].
We may also assume that f(0) = f(1) = 0. For if the theorem is proved
for this case, consider

gx) =f) -fO) -x[f(D -f(O)] (O=<x<1).

Here c(0) = g(1) = 0, and if g can be obtained as the limit of a uniformly
convergent sequence of polynomials, it is clear that the same is true for f,
since f - cg is a polynomial.

Furthermore, we define f(x) to be zero for x outside [0, 1]. Then f
is uniformly continuous on the whole line.

We put

0.x) =c(l=x¥)" (=123..),

where c, is chosen so that
[ 0) dx=1 (n=1,23,..).
We need some information about the order of magnitude of c,. Since
M (1 = x2) dx = 2f (1 - x2) dx > 2[""a - xX?) dx
-1 [4] 0

vn
22" (1 = nx?) dx
0
4

it follows from (48) that

en <n.
160 PRINCIPLES OF MATHEMATICAL ANALYSIS

(50)

(51)

The inequality (1 - x2)" > 1 - nx? which we used above is easily
shown to be true by considering the function

(1 =x?" = 1 + nx?

which is zero at x = 0 and whose derivative is positive in (0, 1).
For any 6 > 0, (49) implies

0.x) </n(1=&y  (a< |x| <1),

so that Q, - 0 uniformly ind < |x| <1.
Now set

P(x) = [ SEHD md O<x<1),
Our assumptions about f show, by a simple change of variable, that
r=] sr 0mdi=[ 100 - va,
and the last integral is clearly a polynomial in x. Thus {P,} is a sequence

of polynomials, which are real if fis real.
Given c > 0, we choose d > 0 such that |y - x| < é implies

SO) - f(D] <3:

Let M =sup [f(x)|. Using (48), (50), and the fact that Q,(x)>0, we
see that for0 <x <1,

1
2) = 1001 = || [16x + 0 = F100 a

1

<[ f+ 0 =f 100 di
re ed 1
<2M| Q(ndi+ al, 0,1) di + 2M [ 0,1) dt

&
<4M Jn (1-8 +5

<é

for all large enough n, which proves the theorem.

It is instructive to sketch the graphs of Q, for a few values of n; also,

note that we needed uniform continuity of f to deduce uniform convergence
of {P,}.
SEQUENCES AND SERIES OF FUNCTIONS 161

In the proof of Theorem 7.32 we shall not need the full strength of
Theorem 7.26, but only the following special case, which we state as a corollary.

7.27 Corollary For every interval [- a, a] there is a sequence of real poly-
nomials P, such that P,0) = 0 and such that
lim P(x) = |x|

uniformly on [ - a, a].

Proof By Theorem 7.26, there exists a sequence {P}} of real polynomials
which converges to |x| uniformly on [- a, a]. In particular, P)(0)- 0
as n - oo. The polynomials

P(x) =Pi(x)=Pr0) (n=123..)
have desired properties.

We shall now isolate those properties of the polynomials which make
the Weierstrass theorem possible.

7.28 Definition A family of of complex functions defined on a set E is said
to be an algebra if (i) f+ g \in o#, (ii) fg \in &/, and (iii) cf \in of for all fe of, g \in A
and for all complex constants c, that is, if o is closed under addition, multi-
plication, and scalar multiplication. We shall also have to consider algebras of
real functions; in this case, (iii) is of course only required to hold for all real c.

If of has the property that fe of whenever feo (n=1,2,3,...) and
f,, = f uniformly on E, then «/ is said to be uniformly closed.

Let 2 be the set of all functions which are limits of uniformly convergent
sequences of members of «/. Then Z is called the uniform closure of of. (See
Definition 7.14.)

For example, the set of all polynomials is an algebra, and the Weierstrass
theorem may be stated by saying that the set of continuous functions on [a, b]
is the uniform closure of the set of polynomials on [a, 5].

7.29 Theorem Let B be the uniform closure of an algebra of of bounded
functions. Then A is a uniformly closed algebra.

Proof If fe # and g \in 4, there exist uniformly convergent sequences
{f.},{g,} such that f, » f,g, > g and f, \in &/, g, \in of. Since we are dealing

with bounded functions, it is easy to show that
Sot ao Sta, fi9-f9, fad,

where c is any constant, the convergence being uniform in each case.
Hence f +g \in 8, fg \in B, and cf \in 4, so that 4 is an algebra.
By Theorem 2.27, # is (uniformly) closed.
162 PRINCIPLES OF MATHEMATICAL ANALYSIS

7.30 Definition Let of be a family of functions on a set E. Then & is said
to separate points on E if to every pair of distinct points x, x, \in E there corre-
sponds a function fe & such that f(x,) # f(x).

If to each x \in E there corresponds a function g \in & such that g(x) #0,
we say that of vanishes at no point of E.

The algebra of all polynomials in one variable clearly has these properties
on R'. An example of an algebra which does not separate points is the set of
all even polynomials, say on [-1, 1], since f(- x) = f(x) for every even function f.

The following theorem will illustrate these concepts further.

7.31 Theorem Suppose sf is an algebra of functions on a set E, of separates
points on E, and of vanishes at no point of E. Suppose x, x, are distinct points
of E, and c,, c, are constants (real if of is a real algebra). Then &f contains a
function f such that
Sx) =cy, f(x) =c,.
Proof The assumptions show that of contains functions g, 4, and &
such that

gx) #g(x2), h(x) #0,  k(x;) #0.

Put
u = gk - g(x,)k, v = gh -g(x,)h.

Then u \in of, v \in of, u(x,) = v(x,) = 0, u(x,) # 0, and v(x,) # 0. Therefore

cv cu
- +
o(xy)  u(xz)

f=

has the desired properties.

We now have all the material needed for Stone’s generalization of the
Weierstrass theorem.

7.32 Theorem Let of be an algebra of real continuous functions on a compact
set K. If of separates points on K and if of vanishes at no point of K, then the
uniform closure # of sf consists of all real continuous functions on K.

We shall divide the proof into four steps.

STEP | If fe &B, then |f| \in &.
Proof Let
(52) a=sup |[f(x)| (xeK)
SEQUENCES AND SERIES OF FUNCTIONS 163

and let c > 0 be given. By Corollary 7.27 there exist real numbers
Cys ++. Cp Such that

(33)

n
Lew' = | <c (-as<y<a)

Since 4 is an algebra, the function

g= Y af!
i=1
is a member of #. By (52) and (53), we have
9x) = If) || <e (xk).
Since 4 is uniformly closed, this shows that |f| \in 4.

STEP 2 If fe # and g \in B, then max (f, g) \in # and min (f, g) \in B.

By max (f; g) we mean the function 4 defined by

Jf if f(x) = g(x),
HD =lat0 if 1) < g(x),

and min (f, g) is defined likewise.

Proof Step 2 follows from step 1 and the identities

max (f,9) = L344 al,
min (9) = 34 - V0,

By iteration, the result can of course be extended to any finite set
of functions: If f,..., f, \in &, then max (f},...,f,) \in #8, and

min (fy, ...,f,) \in AB.
STEP 3 Given a real function f, continuous on K, a point x \in K, and c > 0, there
exists a function g, \in B such that g (x) = f(x) and
(54) :(>f)-ce (tek).

Proof Since of = # and &f satisfies the hypotheses of Theorem 7.31 so
does #. Hence, for every y \in K, we can find a function 4, \in # such that

(55) h(x) =f(x), mb») =SO)
164 PRINCIPLES OF MATHEMATICAL ANALYSIS

(56)

(57)

By the continuity of A, there exists an open set J,, containing y,
such that

h(®)>f(t)-c (tel).
Since XK is compact, there is a finite set of points y,, ..., y, such that
Kc J, uv.
Put
gx =max(h,,...,h,).

By step 2, g. cB, and the relations (55) to (57) show that g, has the other
required properties.

STEP 4 Given a real function f, continuous on K, and c > 0, there exists a function
h \in B such that

(58)

|h(x) = f(x) | <e (x eK).

Since 4 is uniformly closed, this statement is equivalent to the conclusion

of the theorem.

(59)

(60)

(61)

(62)

Proof Let us consider the functions g,, for each x \in KX, constructed in
step 3. By the continuity of g,, there exist open sets V, containing x,
such that

(0 <fO+e (tel).

Since K is compact, there exists a finite set of points x, ..., x,
such that
KeV,u- ub.
Put
h=min(g,,,...,9.)

By step 2, h \in #, and (54) implies

ht) > f-e (tek),
whereas (59) and (60) imply

ht) <ft)+e (tek).
Finally, (58) follows from (61) and (62).
SEQUENCES AND SERIES OF FUNCTIONS 165

Theorem 7.32 does not hold for complex algebras. A counterexample is

given in Exercise 21. However, the conclusion of the theorem does hold, even
for complex algebras, if an extra condition is imposed on &/, namely, that 2
be self-adjoint. This means that for every fe & its complex conjugate f must

also belong to &; f is defined by f(x) = f(x).

7.33 Theorem Suppose of is a self-adjoint algebra of complex continuous
functions on a compact set K, o separates points on K, and of vanishes at no
point of K. Then the uniform closure # of o consists of all complex continuous
functions on K. In other words, o is dense  \in (K).

Proof Let 7; be the set of all real functions on K which belong to «7.

If fe o and f= u + iv, with u, v real, then 2u = f + f, and since &/
is self-adjoint, we see that ue oy. If x; # x,, there exists fe &/ such
that f(x,) = 1, f(x,) = 0; hence 0 = u(x,) # u(x,) = 1, which shows that
«fp separates points on K. If x \in K, then g(x) # 0 for some g \in &, and
there is a complex number 4 such that Ag(x) > 0; if f= Ag, f=u + iv, it
follows that u(x) > 0; hence &/, vanishes at no point of K.

Thus « satisfies the hypotheses of Theorem 7.32. It follows that
every real continuous function on KX lies in the uniform closure of «7p,
hence lies in #. If fis a complex continuous function on K, f= u +iv,
then u \in 8, v \in AB, hence fe #4. This completes the proof.

EXERCISES

1.

Prove that every uniformly convergent sequence of bounded functions is uni-
formly bounded.

. If {f.} and {g.} converge uniformly on a set E, prove that {f, + g.} converges

uniformly on E. If, in addition, {f,} and {g.} are sequences of bounded functions,
prove that { f,g.} converges uniformly on E.

. Construct sequences {f.}, {g.} which converge uniformly on some set E, but such

that {f.g.} does not converge uniformly on E (of course, {f.g.} must converge on
E).

. Consider

1
1+ nx’

For what values of x does the series converge absolutely? On what intervals does
it converge uniformly? On what intervals does it fail to converge uniformly? Is f
continuous wherever the series converges? Is f bounded?
166 PRINCIPLES OF MATHEMATICAL ANALYSIS

0 G; <x).
n
Show that {f,} converges to a continuous function, but not uniformly. Use the

series T f, to show that absolute convergence, even for all x, does not imply uni-
form convergence.

. Prove that the series

x*+n
2

n

T(r

converges uniformly in every bounded interval, but does not converge absolutely
for any value of x.

. Forn=1,2,3,..., x real, put

x

Sox) = Tone

Show that {f,} converges uniformly to a function f, and that the equation
f= tim f(x)

is correct if x # 0, but false if x =0.

If

0 (x <0),
I=\;  (x>o)

if {x,} is a sequence of distinct points of (a, b), and if £|c.| converges, prove that
the series

[=F ellx-x) (a<x<b)

converges uniformly, and that fis continuous for every x # x,.

. Let {f.} be a sequence of continuous functions which converges uniformly to a

function f on a set E. Prove that

lim x) = f(x)

for every sequence of points x, \in E such that x, - x, and x \in E. Is the converse of
this true?
SEQUENCES AND SERIES OF FUNCTIONS 167

10. Letting (x) denote the fractional part of the real number x (see Exercise 16, Chap. 4,

11.

12.

13.

for the definition), consider the function

2, (nx)

fx)= Zz ges (x real).

Find all discontinuities of f, and show that they form a countable dense set.
Show that fis nevertheless Riemann-integrable on every bounded interval.
Suppose {f+}, {ga} are defined on E, and
(a) Z f, has uniformly bounded partial sums;
(b) g»- 0 uniformly on E;
(c) 91(x) = g2(x) 2 ga(x) = for every x \in E.

Prove that T f,g. converges uniformly on E. Hint: Compare with Theorem
3.42.
Suppose g and fo(n=1, 2, 3, ...) are defined on (0, «), are Riemann-integrable on
[c, T] whenever 0 <t <T < oo, | fa| <g, fo =f uniformly on every compact sub-
set of (0, «), and

[ot dx < 00,

Prove that

«© a®
lim [ fx) dx= [ F(x) dx.
n=® Jo 0

(See Exercises 7 and 8 of Chap. 6 for the relevant definitions.)

This is a rather weak form of Lebesgue’s dominated convergence theorem
(Theorem 11.32). Even in the context of the Riemann integral, uniform conver-
gence can be replaced by pointwise convergence if it is assumed that fe Z. (See
the articles by F. Cunningham in Math. Mag., vol. 40, 1967, pp. 179-186, and
by H. Kestelman in Amer. Math. Monthly, vol. 77, 1970, pp. 182-187.)

Assume that {f,} is a sequence of monotonically increasing functions on R! with
0 < fi(x) <1 for all x and all n.
(a) Prove that there is a function f and a sequence {n.} such that

SG) = lim f(x)

for every x \in R'. (The existence of such a pointwise convergent subsequence is
usually called Helly’s selection theorem.)
(b) If, moreover, f is continuous, prove that f,, =f uniformly on compact sets.
Hint: (i) Some subsequence {f,,} converges at all rational points r, say, to
f(r). (ii) Define f(x), for any x \in R", to be sup f(r), the sup being taken over all
r < x. (iii) Show that f,,(x) = f(x) at every x at which f is continuous. (This is
where monotonicity is strongly used.) (iv) A subsequence of {f,} converges at
every point of discontinuity of f since there are at most countably many such
points. This proves (a). To prove (b), modify your proof of (iii) appropriately.
168 PRINCIPLES OF MATHEMATICAL ANALYSIS

14.

15.

16.

17.

18.

19.

Let f be a continuous real function on R' with the following properties:
0< f(#) <1, f(t + 2) = f(c) for every t, and
0  O<:<}¥)

TO=\  g=i<w.

Put ®(c) = (x(c), y(t), where

X= F270, = 527),

Prove that a is continuous and that ® maps I = [0, 1] onto the unit square /2 < R2.
If fact, show that ® maps the Cantor set onto 72.
Hint: Each (xo, yo) \in I? has the form

Xo = 22 am, Yo =X 2 "an

where each a; is 0 or 1. If
to=73 37'"'(2a)
i=1

show that f(3*#0) = ax, and hence that x(c,) = xo, y(t0) = yo.

(This simple example of a so-called ‘space-filling curve” is due to I. J.
Schoenberg, Bull. A.M.S., vol. 44, 1938, pp. 519.)
Suppose fis a real continuous function on R?, f(t) = f(nt) for n=1,2,3, ..., and
{/.} is equicontinuous on [0, 1]. What conclusion can you draw about f?
Suppose { f.} is an equicontinuous sequence of functions on a compact set K, and
{fa} converges pointwise on K. Prove that { f,} converges uniformly on K.
Define the notions of uniform convergence and equicontinuity for mappings into
any metric space. Show that Theorems 7.9 and 7.12 are valid for mappings into
any metric space, that Theorems 7.8 and 7.11 are valid for mappings into any
complete metric space, and that Theorems 7.10, 7.16, 7.17, 7.24, and 7.25 hold for
vector-valued functions, that is, for mappings into any R*.
Let {f.} be a uniformly bounded sequence of functions which are Riemann-inte-
grable on [a, b], and put

Fo=[ fd (a<x<b).

Prove that there exists a subsequence {F,,} which converges uniformly on [a, 6].
Let K be a compact metric space, let S be a subset of ¥(K). Prove that S is compact
(with respect to the metric defined in Section 7.14) if and only if S is uniformly
closed, pointwise bounded, and equicontinuous. (If .S is not equicontinuous,
then § contains a sequence which has no equicontinuous subsequence, hence has
no subsequence that converges uniformly on K.)
20.

21.

22.

23.

SEQUENCES AND SERIES OF FUNCTIONS 169

If fis continuous on [0, 1] and if
1
| fx" dx=0 (n=0,1,2,...),
[J]

prove that f(x) =0 on [0, 1]. Hint: The integral of the product of f with any
1

polynomial is zero. Use the Weierstrass theorem to show that [X fi (x)dx=0.

Let K be the unit circle in the complex plane (i.e., the set of all z with |z| = 1), and

let «7 be the algebra of all functions of the form

fe) = 3 c.e™ (0 real).
=o

Then &/ separates points on K and .&/ vanishes at no point of K, but nevertheless
there are continuous functions on K which are not in the uniform closure of <7.
Hint: For every fe of

2r
[ Fee’? df = 0,
0

and this is also true for every f in the closure of #7.
Assume f \in A(x) on [a, b], and prove that there are polynomials P, such that

b
tim | | f= Pa]? do =O.

(Compare with Exercise 12, Chap. 6.)
Put Po = 0, and define, for n=0,1, 2, ...,

2 - Pix
Pri = Pio + T70,
Prove that
lim P(x) = |x|,

uniformly on [-1, 1].

(This makes it possible to prove the Stone-Weierstrass theorem without first
proving Theorem 7.26.)

Hint: Use the identity

Py
x] = Pasi) = [1x] ol - bol ple)
to prove that 0 < P(x) < P,. (x) < |x| if |x| <1, and that

|x)" 2
- < - Zt
|x| - Pax) (s 5 <7

if |x| <1.
170 PRINCIPLES OF MATHEMATICAL ANALYSIS

24.

25.

Let X be a metric space, with metric d. Fix a point a \in X. Assign to eachpe X
the function f, defined by
fox) =d(x,p) -d(x,a) (xe X).

Prove that | f,(x)| <d(a, p) for all x \in X, and that therefore f, \in  \in (X).
Prove that
Ife - fall =d(p,q)

for all p,q \in X.

If ®(p) =f; it follows that © is an isometry (a distance-preserving mapping)
of X onto ®(X) < 4(X).

Let Y be the closure of ®(X)in ¥(X). Show that Y is complete,

Conclusion: X is isometric to a dense subset of a complete metric space Y.
(Exercise 24, Chap. 3 contains a different proof of this.)
Suppose c is a continuous bounded real function in the strip defined by
0<x<1, -w <y< co. Prove that the initial-value problem

Y=9cxy, y0)=c
has a solution. (Note that the hypotheses of this existence theorem are less stringent
than those of the corresponding uniqueness theorem; see Exercise 27, Chap. 5.)
Hint: Fix n. Fori=0,..., n, put x,=i/n. Let f, be a continuous function
on [0, 1] such that £,(0) = c,

Sut) = (xi, fulx1)) if xi <t<xi44,
and put
A(t) = f(t) - (8, £1),

except at the points x;, where A,(z) = 0. Then
fi = c+ [ [4 f0) + Mol dr.

Choose M < «© so that |c| <M. Verify the following assertions.

(a) fal <M, |A:| <2M, A eR, and | £2] <|c| + M = M,, say, on [0, 1], for
all n.

(b) {f+} is equicontinuous on [0, 1], since | fz] <M.

(c) Some { f»,} converges to some f, uniformly on [0, 1].

(d) Since c is uniformly continuous on the rectangle 0 <x <1, |y| <M,,

Bt, fur(1)) => b(t, £(1))

uniformly on [0, 1].
(e) A(t) -> 0 uniformly on [0, 1], since

A(t) = $(xi, fx) - $2, £1)

in (xi, Xi41).
26.

SEQUENCES AND SERIES OF FUNCTIONS 171

(f) Hence
FG =e [ $e £10) a.
o
This fis a solution of the given problem.
Prove an analogous existence theorem for the initial-value problem
Vy =2(kxy), y0=c

where now c \in R¥, y \in R¥, and &® is a continuous bounded mapping of the part of
Rk! defined by 0 <x <1, y \in R* into R*. (Compare Exercise 28, Chap. 5.) Hint:
Use the vector-valued version of Theorem 7.25.
8

SOME SPECIAL FUNCTIONS

POWER SERIES

In this section we shall derive some properties of functions which are represented
by power series, i.e., functions of the form

1) fe) =3 eu
or, more generally,
2 fx) =3 cx =a).

These are called analytic functions.

We shall restrict ourselves to real values of x. Instead of circles of con-
vergence (see Theorem 3.39) we shall therefore encounter intervals of conver-
gence.

If (1) converges for all x in (-R, R), for some R> 0 (R may be + 0),
we say that fis expanded in a power series about the point x = 0. Similarly, if
(2) converges for |x - a| < R, fis said to be expanded in a power series about
the point x = a. As a matter of convenience, we shall often take a = 0 without
any loss of generality.
SOME SPECIAL FUNCTIONS

8.1 Theorem Suppose the series
3) 2 ox"
converges for |x| < R, and define

a f(x) = Se (|x| < B.

173

Then (3) converges uniformly on [-R + &, R - c], no matter which c > 0

is chosen. The function fis continuous and differentiable in (- R, R), and
©) Se) = Yn (xl <A).
Proof Let e> 0 be given. For |x| < R - c, we have
lew] < fe (R =e)";
and since

Se, (R-e)"

converges absolutely (every power series converges absolutely in the
interior of its interval of convergence, by the root test), Theorem 7.10

shows the uniform convergence of (3) on [-R + c, R - &].
Since Yn -1 as n - oo, we have
lim sup Ynle, = lim sup Yel,
n- oo n=

so that the series (4) and (5) have the same interval of convergence.

Since (5) is a power series, it converges uniformly in [-R +g,
R -c], for every e > 0, and we can apply Theorem 7.17 (for series in-

stead of sequences). It follows that (5) holds if |x| < R -e.

But, given any x such that |x| < R, we can find an c > 0 such that

|x| < R -&. This shows that (5) holds for |x| < R.
Continuity of f follows from the existence of f* (Theorem 5.2).

Corollary Under the hypotheses of Theorem 8.1, f has derivatives of all

orders in (- R, R), which are given by

(6) SOG) =Y n(n -1) (n-k + De, x" 7k

n=k
In particular,
7) 80) = ke, (k=0,1,2,...).

(Here £9) means f, and f® is the kth derivative of f; fork = 1, 2, 3, ...).
174 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Equation (6) follows if we apply Theorem 8.1 successively to f,
ff" .... Putting x = 0 in (6), we obtain (7).

Formula (7) is very interesting. It shows, on the one hand, that the
coefficients of the power series development of f are determined by the values
of [and of its derivatives at a single point. On the other hand, if the coefficients
are given, the values of the derivatives of f at the center of the interval of con-
vergence can be read off immediately from the power series.

Note, however, that although a function / may have derivatives of all
orders, the series Zc, x", where c, is computed by (7), need not converge to f(x)
for any x # 0. In this case, f cannot be expanded in a power series about x = 0.
For if we had f(x) = Za, x", we should have

n'a, = (0);

hence a, = c,. An example of this situation is given in Exercise 1.

If the series (3) converges at an endpoint, say at x = R, then fis continuous
not only in (- R, R), but also at x = R. This follows from Abel’s theorem (for
simplicity of notation, we take R = 1):

8.2 Theorem Suppose Zc, converges. Put

Se =3 ex (-l<x<]).

Then

a®) lim f(x) = Sen

x=1

Proof Lets,=co + +cc,, 5-1 =0. Then

m m m-1
Yoenx" = (sp= 8S-)X"=(1 =X) Y 5, x" + 5, x".
n=0 n=0 n=0

For |x| <1, we let m - co and obtain

©) f= =F 5x.

Suppose s = lim s,. Let c > 0 be given. Choose N so that n > N

n= on

implies
SOME SPECIAL FUNCTIONS 175

Then, since
1-0Yx=1 (x|<1),
n=0

we obtain from (9)
© N e
f= s|=|(1 = 0) % (sn =| SA =0) X |sn=s][x]" +3 <2

if x > 1 - 4, for some suitably chosen é > 0. This implies (8).
As an application, let us prove Theorem 3.51, which asserts: If Za,, Zb,,
Zc, , converge to A, B, C, and if c, = ayb, + + a, by, then C= AB. We let

fe) =F ax =F bx = Gr

for 0 < x <1. For x < 1, these series converge absolutely and hence may be
multiplied according to Definition 3.48; when the multiplication is carried out,
we see that

(10) Sx) gx) =h(x) (O<x<l).
By Theorem 8.2,
(11) f(x) 4, g(x) - B, h(x)->C

as x -» 1. Equations (10) and (11) imply 4B = C.
We now require a theorem concerning an inversion in the order of sum-
mation. (See Exercises 2 and 3.)

8.3 Theorem Given a double sequence {a;;}, i=1,2,3,...,j=1,2,3,...,
suppose that

(12) Y lay =b;  (i=1,23..)
and Lb; converges. Then
(13) py p ay =} 2 a.

Proof We could establish (13) by a direct procedure similar to (although
more involved than) the one used in Theorem 3.55. However, the following
method seems more interesting.
176 PRINCIPLES OF MATHEMATICAL ANALYSIS

Let E be a countable set, consisting of the points x,, x, X,, ..

suppose x, = Xo as n - co. Define

(14) fixe) = 3 ay (i=1,2,3,..),

(15) fy =Ya;  (n=123.)
i=1

(16) 00 =3 fi» eb.

., and

Now, (14) and (15), together with (12), show that each f; is con-
tinuous at x,. Since |fi(x)| <b; for x \in E, (16) converges uniformly, so

that g is continuous at x, (Theorem 7.11). It follows that
Y Yay= 3 fit) = g(x) = lim g(x)

= lim § f(x) = lim : px?

n-owi=1 n-w i=1
. n =o} a aD

= lim }’ Ya;=3 Ya.
nw j=1 01 istic

8.4 Theorem Suppose

f= 3 eux

the series converging in |x| < R. If -R <a < R, then f can be expanded in a
power series about the point x = a which converges in |x -a| < R - |a|, and

a7 fo) =

wo fn)
SLD G-ar  (x-al<R- la)

This is an extension of Theorem 5.15 and is also known as Taylor’s

theorem.

Proof We have

f= 3 alr - a) + al

II
i118
o

5
M
-
Sx

©

3
Il

=

) a" "(x - a)

JE (2) ere] era

II
is
SOME SPECIAL FUNCTIONS 177

This is the desired expansion about the point x = a. To prove its validity,
we have to justify the change which was made in the order of summation.
Theorem 8.3 shows that this is permissible if

as) 5 5 Ch (on) a "(x - a"

n=0m=0 m

converges. But (18) is the same as

0
(19) > lal (1x = al +a],
and (19) converges if |x -a| + |a| < R.
Finally, the form of the coefficients in (17) follows from (7).

It should be noted that (17) may actually converge in a larger interval than
the one given by |x -a| < R - |al.

If two power series converge to the same function in (- R, R), (7) shows
that the two series must be identical, i.e., they must have the same coefficients.
It is interesting that the same conclusion can be deduced from much weaker
hypotheses:

8.5 Theorem Suppose the series Xa,x" and Xb,x" converge in the segment
S =(-R, R). Let E be the set of all x \in S at which

(20) y a,x" = y b,x".

n=0 n=0
If E has a limit point in S, then a, =b, forn =0, 1, 2, .... Hence (20) holds for
all xe S.

Proof Putc,=a,-b, and
a1) FG) =Y cx" (xeS).
n=0

Then f(x) =0 on E.

Let A be the set of all limit points of E in S, and let B consist of all
other points of S. It is clear from the definition of “limit point” that B
is open. Suppose we can prove that 4 is open. Then 4 and B are disjoint
open sets. Hence they are separated (Definition 2.45). Since S=A4 U B,
and S is connected, one of 4 and B must be empty. By hypothesis, 4 is
not empty. Hence Bis empty, and 4 = S. Since f is continuous in S,
Ac E. Thus E=S, and (7) shows that c,=0forn=0, 1, 2, ..., which
is the desired conclusion.
178 PRINCIPLES OF MATHEMATICAL ANALYSIS

Thus we have to prove that 4 is open. If x, \in 4, Theorem 8.4 shows
that

a) fe) =F dix =x (x= xo <R= |x).

We claim that d, = 0 for all n. Otherwise, let k be the smallest non-
negative integer such that d, #0. Then

(23) Sx) =x -x0)g(x) (|x - xo] <R-|x]),
where
(24) g(x) = YL diinlx - Xo)"

Since g is continuous at x, and
9(xo) = dy #0,

there exists a § > 0 such that g(x) #0 if |x - x,| <d. It follows from
(23) that f(x) #0 if 0 < |x - xo| <6. But this contradicts the fact that
X, is a limit point of E.

Thus d, = 0 for all n, so that f(x) = 0 for all x for which (22) holds,
i.e., in a neighborhood of x,. This shows that 4 is open, and completes
the proof.

THE EXPONENTIAL AND LOGARITHMIC FUNCTIONS
We define

© Vd
(25) Ea)=Y =
n=0 Mn:
The ratio test shows that this series converges for every complex z. Applying
Theorem 3.50 on multiplication of absolutely convergent series, we obtain

© SM a gm © on Zh -k
E()E(w) = =
aEw) =3 -7 Xoo Eo Eo kin - k)!
© 1a na, 2 Ew
=y - wk yy ET
py PIN (+) PX n!

which gives us the important addition formula
(26) E(z + w) = E(z2)E(w) (z, w complex).
One consequence is that

a7 EQE(-2)=E(z-z)=E0)=1  (z complex).
SOME SPECIAL FUNCTIONS 179

This shows that E(z) # 0 for all z. By (25), E(x) > 0 if x > 0; hence (27) shows
that E(x) > 0 for all real x. By (25), E(x) = +00 as x - +00; hence (27) shows
that E(x) » 0 as x » -oo along the real axis. By (25), 0 < x < y implies that
E(x) < E(y); by (27), it follows that E(-y) < E(-x); hence E is strictly in-
creasing on the whole real axis.

The addition formula also shows that

El h) - E Eh) -1
8) lim ZEN = Ea _ por im ED = _ py.
h=0 h h=0 h
the last equality follows directly from (25).
Iteration of (26) gives
(29) E(zy + + + z,) = E(z;) + E(z,).
Let us take z;, = -++ =z, =1. Since E(1) =e, where e is the number defined
in Definition 3.30, we obtain
(30) En) =c" (n=1,2,3,...).
If p = n/m, where n, m are positive integers, then
(31 [E(p)I" = E(mp) = E(n) =  \in ",
so that
(32) E(p) = ef (p > 0, p rational).

It follows from (27) that E(-p) = e~? if p is positive and rational. Thus (32)
holds for all rational p.
In Exercise 6, Chap. 1, we suggested the definition

(33) x* = sup x”,

where the sup is taken over all rational p such that p < y, for any real y, and
x > 1. If we thus define, for any real x,

(34) e* = sup ef (p < x, p rational),

the continuity and monotonicity properties of E, together with (32), show that
(35) E(x) =e*

for all real x. Equation (35) explains why E is called the exponential function.
The notation exp (x) is often used in place of e*, expecially when x is a
complicated expression.
Actually one may very well use (35) instead of (34) as the definition of e*;
(35) is a much more convenient starting point for the investigation of the
properties of e*. We shall see presently that (33) may also be replaced by a
more convenient definition [see (43)].
180 PRINCIPLES OF MATHEMATICAL ANALYSIS

We now revert to the customary notation, e*, in place of E(x), and sum-
marize what we have proved so far.

8.6 Theorem Let e* be defined on R' by (35) and (25). Then
(a) e* is continuous and differentiable for all x;
(Bb) (e) =e";
(c)  \in " is a strictly increasing function of x, and  \in * > 0;
d) =e;
(e) ef>+mwasx->+w,e*>0asx-> -ow0;
(f) lim, x"e™* =0, for every n.
Proof We have already proved (a) to (e); (25) shows that
. xt 1
ef > -
(n+ 1)!
for x > 0, so that

n+ 1)!
wer < Ay
X

and (f) follows. Part (f) shows that e* tends to + co “faster” than any
power of x, as x = + 0.

Since E is strictly increasing and differentiable on R!, it has an inverse
function L which is also strictly increasing and differentiable and whose domain
is E(R"), that is, the set of all positive numbers. L is defined by

(36) EL) =y (>0),

or, equivalently, by

(37) L(E(x)) =x (x real).

Differentiating (37), we get (compare Theorem 5.5)
L'(E(x))- E(x) =1.

Writing y = E(x), this gives us

(38) L'(y)= (y>0).

1
y
Taking x = 0 in (37), we see that L(1) = 0. Hence (38) implies

(39) L(y) =
SOME SPECIAL FUNCTIONS 181

Quite frequently, (39) is taken as the starting point of the theory of the logarithm
and the exponential function. Writing u = E(x), v = E(y), (26) gives

L(uw) = (E(x) EG) = L(E(x + y)) =X + y,
so that
(40) Luv) = L(u) + L(v) (u>0,v>0).
This shows that L has the familiar property which makes logarithms useful
tools for computation. The customary notation for L(x) is of course log x.
As to the behavior of log x as x » +00 and as x -»0, Theorem 8.6(c)

shows that
log x » +00 as x = +00,

log x > - as x = 0.
It is easily seen that
(41) x" = E(nL(x))

if x > 0 and n is an integer. Similarly, if m is a positive integer, we have
1

(42) xm = E ( 1) ,
m

since each term of (42), when raised to the mth power, yields the corresponding
term of (36). Combining (41) and (42), we obtain

(43) x* = E(aL(x)) = e*1°8*

for any rational a.

We now define x? for any real « and any x > 0, by (43). The continuity
and monotonicity of E and L show that this definition leads to the same result
as the previously suggested one. The facts stated in Exercise 6 of Chap. 1, are
trivial consequences of (43).

If we differentiate (43), we obtain, by Theorem 5.5,

(44) (x) = E(aL(x)) - 2 - axl,

Note that we have previously used (44) only for integral values of «, in which
case (44) follows easily from Theorem 5.3(b). To prove (44) directly from the
definition of the derivative, if x* is defined by (33) and « is irrational, is quite
troublesome.

The well-known integration formula for x* follows from (44) if « # - 1,

and from (38) if x = -1. We wish to demonstrate one more property of log x,
namely,
(45) lim x *logx=0

x=+w0
182 PRINCIPLES OF MATHEMATICAL ANALYSIS

for every a > 0. That is, log x =» + co “slower” than any positive power of x,
as x = + 00.
For if 0 < c < «, and x > 1, then

x XxX
x*logx = x7* | td < x7 | te dt
1 v1
xt-1 xc
. <
e 3

and (45) follows. We could also have used Theorem 8.6(f) to derive (45).

THE TRIGONOMETRIC FUNCTIONS

Let us define
(46) C(x) = i [E(ix) + E(-ix)], Sx) = 5 [E(ix) - E(-ix)].

We shall show that C(x) and S(x) coincide with the functions cos x and sin x,
whose definition is usually based on geometric considerations. By (25), E(Z) =

E(2). Hence (46) shows that C(x) and S(x) are real for real x. Also,
47) E(ix) = C(x) + iS(x).

Thus C(x) and S(x) are the real and imaginary parts, respectively, of E(ix), if
x is real. By (27),

| Eix)|? = E(ix)E(ix) = E(ix)E(-ix) = 1,

so that
(48) |E(ix)| = 1 (x real).

From (46) we can read off that C(0) = 1, S(0) = 0, and (28) shows that
(49) C'(x) = -S(x), S'(x) = C(x).

We assert that there exist positive numbers x such that C(x) =0. For
suppose this is not so. Since C(0) =1, it then follows that C(x) > 0 for all
x > 0, hence S’'(x) > 0, by (49), hence S is strictly increasing; and since S(0) = 0,
we have S(x) > 0 if x > 0. Hence if 0 < x < y, we have

(50) SX - x) < [sw dt = Cx) - CY) <2.

The last inequality follows from (48) and (47). Since S(x) > 0, (50) cannot be
true for large y, and we have a contradiction.
SOME SPECIAL FUNCTIONS 183

Let x, be the smallest positive number such that C(x,) = 0. This exists,
since the set of zeros of a continuous function is closed, and C(0) #0. We
define the number © by

(31) n=2Xg.

Then C(n/2) =0, and (48) shows that S(n/2) = £1. Since C(x) > 0 in
(0, /2), S is increasing in (0, 7/2); hence S(n/2) = 1. Thus

5)

and the addition formula gives

(52) E(ni)= -1, EQni)=1;
hence
(53) E(z + 2ni) = E(2) (z complex).

8.7 Theorem

(a) The function E is periodic, with period 2mi.

(b) The functions C and S are periodic, with period 2m.

(c) If0<t< 2m, then E(it) #1.

(d) If z is a complex number with |z| =1, there is a unique t in [0, 27)
such that E(it) = z.

Proof By (53), (a) holds; and (b) follows from (a) and (46).
Suppose 0 < t < n/2 and E(it) = x + iy, with x, y real. Our preceding
work shows that 0 < x < 1, 0 < y < 1. Note that

E(a4it) = (x + ip)* = x* - 6x29? + p* + dixp(x? - 2).
If E(4it) is real, it follows that x* - »? = 0; since x2 + y% = 1, by (48),

we have x2 = yp? = 1, hence E(4ir) = -1. This proves (c).
If0<1t <t, <2m, then

E(it)[E(in)]™" = E(it, - ity) #1,

by (c). This establishes the uniqueness assertion in (d).

To prove the existence assertion in (d), fix z so that |z| = 1. Write
z = x + iy, with x and yp real. Suppose first that x >0 and y > 0. On
[0, n/2], C decreases from 1 to 0. Hence C(r) = x for some c \in [0, 7/2].
Since C2 + S? =1 and S > 0 on [0, 7/2], it follows that z = E(it).

If x <0 and y > 0, the preceding conditions are satisfied by -iz.
Hence -iz = E(it) for some c \in [0, 7/2], and since i = E(ni/2), we obtain
z = E(i(t + =/2)). Finally, if y <0, the preceding two cases show that
184 PRINCIPLES OF MATHEMATICAL ANALYSIS

-z = E(it) for some  \in (0, nr). Hence z = - E(it) = E(i(t + n)).
This proves (d), and hence the theorem.

It follows from (d) and (48) that the curve y defined by
(54) yt) = Ea{t) (0<t<2nm)

is a simple closed curve whose range is the unit circle in the plane. Since
y(t) =iE(it), the length of 7 is

27
IN [y'(t)| dr = 2m,

by Theorem 6.27. This is of course the expected result for the circumference of
a circle of radius 1. It shows that =, defined by (51), has the usual geometric
significance.

In the same way we see that the point y(c) describes a circular arc of length
to as t increases from 0 to f,. Consideration of the triangle whose vertices are
7 =0, 23 = (to), z3 = C(t)
shows that C(c) and S(c) are indeed identical with cos c and sin c, if the latter

are defined in the usual way as ratios of the sides of a right triangle.

It should be stressed that we derived the basic properties of the trigono-
metric functions from (46) and (25), without any appeal to the geometric notion
of angle. There are other nongeometric approaches to these functions. The
papers by W. F. Eberlein (Amer. Math. Monthly, vol. 74, 1967, pp. 1223-1225)
and by G. B. Robison (Math. Mag., vol. 41, 1968, pp. 66-70) deal with these
topics.

THE ALGEBRAIC COMPLETENESS OF THE COMPLEX FIELD

We are now in a position to give a simple proof of the fact that the complex
field is algebraically complete, that is to say, that every nonconstant polynomial
with complex coefficients has a complex root.

8.8 Theorem Suppose aq, ..., a, are complex numbers, n> 1, a, #0,
Pz) =) az"
0

Then P(z) = 0 for some complex number z.

Proof Without loss of generality, assume a, = 1. Put
(55) u=inf |P(z)| (z complex)

If |z| = R, then
(56) |P(z)| 2 R'[1 = |a,-|R™" = ++ = |ao| R™"].
SOME SPECIAL FUNCTIONS 185

The right side of (56) tends to co as R - co. Hence there exists R, such
that |P(z)| > pif |z| > Ry. Since |P| is continuous on the closed disc
with center at 0 and radius R,, Theorem 4.16 shows that | P(z,)| = u for
some z,.

We claim that yu = 0.

If not, put Q(z) = P(z + z,)/P(zy). Then Q is a nonconstant poly-
nomial, Q(0) =1, and | Q(z)| > 1 for all z. There is a smallest integer k,
1 < k <n, such that

(57) 02) =1+b"+ +b,2",  b #0.
By Theorem 8.7(d) there is a real 6 such that
(58) e®by = - | by.

x Lo
k ,
If r > 0 and r*|b,| < 1, (58) implies

[14 be rke™®| = 1 -r*|b,],
so that

[Q(re®)| <1 = r*{|by| = r|bysy] = =o = r"7¥[b, |}

For sufficiently small r, the expression in braces is positive; hence
| Q(re'®)| < 1, a contradiction.
Thus u = 0, that is, P(zy) = 0.

Exercise 27 contains a more general result.

FOURIER SERIES

8.9 Definition A trigonometric polynomial is a finite sum of the form
N

(59) f(x) =a, + (a, cos nx + b, sin nx) (x real),
n=1

where ay, ..., ay, by, ..., by are complex numbers. On account of the identities
(46), (59) can also be written in the form

(60) 0) =Y een (xreal),
N

which is more convenient for most purposes. It is clear that every trigonometric
polynomial is periodic, with period 27.

If n is a nonzero integer, e™* is the derivative of c*/in, which also has
period 27. Hence

Lo x, [1 (ifn=0),
®D) le a= lo (fn=+1, £2,...).
186 PRINCIPLES OF MATHEMATICAL ANALYSIS

Let us multiply (60) by e™™, where m is an integer; if we integrate the
product, (61) shows that

62) oy = . [ 3 F(x)e™™ dx

for [m| < N. If |[m| > N, the integral in (62) is 0.

The following observation can be read off from (60) and (62): The
trigonometric polynomial f, given by (60), is real if and only if c_, = c, for
n=0,...,N.

In agreement with (60), we define a trigonometric series to be a series of
the form

(63) Yc, e™ (x real);

the Nth partial sum of (63) is defined to be the right side of (60).

If fis an integrable function on [-=, ©], the numbers c,, defined by (62)
for all integers m are called the Fourier coefficients of f, and the series (63) formed
with these coefficients is called the Fourier series of f.

The natural question which now arises is whether the Fourier series of f
converges to f, or, more generally, whether f'is determined by its Fourier series.
That is to say, if we know the Fourier coefficients of a function, can we find
the function, and if so, how?

The study of such series, and, in particular, the problem of representing a
given function by a trigonometric series, originated in physical problems such
as the theory of oscillations and the theory of heat conduction (Fourier’s
“Théorie analytique de la chaleur” was published in 1822). The many difficult
and delicate problems which arose during this study caused a thorough revision
and reformulation of the whole theory of functions of a real variable. Among
many prominent names, those of Riemann, Cantor, and Lebesgue are intimately
connected with this field, which nowadays, with all its generalizations and rami-
fications, may well be said to occupy a central position in the whole of analysis.

We shall be content to derive some basic theorems which are easily
accessible by the methods developed in the preceding chapters. For more
thorough investigations, the Lebesgue integral is a natural and indispensable
tool.

We shall first study more general systems of functions which share a
property analogous to (61).

8.10 Definition Let {c,} (n =1,2,3,...) be a sequence of complex functions
on [a, b], such that

(64) [608 G) dx=0 (nm).
SOME SPECIAL FUNCTIONS 187

Then {c,} is said to be an orthogonal system of functions on [a, b]. If, in addition,

b
(65) [18.12 ax =1

for all n, {c,} is said to be orthonormal.
For example, the functions (27) %c™* form an orthonormal system on
[-n, =]. So do the real functions

1 cosx sin x cos 2x sin 2x
NCAR

If {c,} is orthonormal on [a, b] and if

(66) 6 = [ 180) d (n=1,2,3,..),

we call c, the nth Fourier coefficient of f relative to {c,}. We write

0

67) Sx) ~ )) Cn Pu(X)
and call this series the Fourier series of f (relative to {c,}).

Note that the symbol ~ used in (67) implies nothing about the conver-
gence of the series; it merely says that the coefficients are given by (66).

The following theorems show that the partial sums of the Fourier series
of f have a certain minimum property. We shall assume here and in the rest of
this chapter that fe #, although this hypothesis can be weakened.

8.11 Theorem Let {c,} be orthonormal on [a, b]. Let

(68) $5) = 3 Gn b)
be the nth partial sum of the Fourier series of f, and suppose
(69) 1X) = 3 Vn PX):
m=1
Then
b b
(70) [Vf =sil2 dx [17-1] dx,

and equality holds if and only if
(71) Ym=Cn (m=1,...,n).

That is to say, among all functions 1,, s, gives the best possible mean
square approximation to f.
188 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Let } denote the integral over [q, b], £ the sum from 1 to n. Then
[£1= [ST 30 = 3 nim

by the definition of {c,,},

[1612 = [t= [ 90u EL 5b = 3 7?
since {c,,} is orthonormal, and so

[1r=nl2=[112 = [f= [J+ [10]?

= [1/12 = Z tnTn = Zn tm + Tm
= [112 = len? + T 17m cal,

which is evidently minimized if and only if y,, = c,,.
Putting y,, = c,, in this calculation, we obtain

(12) [150012 dx = 3 fel? = [ 1/00 dx,

since f|f-1,|* = 0.

8.12 Theorem If {c,} is orthonormal on [a, b], and if

©

SG) ~ 3 ead),
then
0 b
(73) Y lal? < [If] dx
In particular,
(74) lim c, = 0.
Proof Letting n- oo in (72), we obtain (73), the so-called ‘‘Bessel

inequality.”

8.13 Trigonometric series From now on we shall deal only with the trigono-
metric system. We shall consider functions f that have period 2z and that are
Riemann-integrable on [-m, nr] (and hence on every bounded interval). The
Fourier series of fis then the series (63) whose coefficients c, are given by the
integrals (62), and

N
(75) sn(x) = sa(fs x) = 2 cpe™
SOME SPECIAL FUNCTIONS 189

is the Nth partial sum of the Fourier series of f. The inequality (72) now takes
the form

1 n 2 N 2 1 pom 5
(76) 57] solar =3 lel? <5 [f)* ax
In order to obtain an expression for sy that is more manageable than (75)
we introduce the Dirichlet kernel
No sin (N + $)x
7 D = mx - .
an Wx) = 3 ce sin (x/2)

The first of these equalities is the definition of Dy(x). The second follows if
both sides of the identity

(e™ - 1)Dy(x) PIN+ 1x _ p= iNx

-ix/2

are multiplied by e
By (62) and (75), we have

wfi=Y

“2n

AT N
| f()Y emo dr,
-n -N

I f(t)e dt ei"

so that
9 sfi9=5 | 0D = 1dr = n |” see= np a.

The periodicity of all functions involved shows that it is immaterial over which
interval we integrate, as long as its length is 2z. This shows that the two integrals
in (78) are equal.

We shall prove just one theorem about the pointwise convergence of
Fourier series.

8.14 Theorem If, for some x, there are constants 6 > 0 and M < oo such that

79) [fC + 1) = fx) < Mt]

for all te (=, 5), then

(80) Jim sy(f3 x) = f(x).
Proof Define

81) NICER C)

sin (7/2)
190 PRINCIPLES OF MATHEMATICAL ANALYSIS

for 0 < || < =, and put g(0) = 0. By the definition (77),

1 n
5 [RC dx =1.
Hence (78) shows that

su(f3 x) - f(x) = = (0 sin (v+ 3) dt

1 p= t . 1 rr" ot
-7 I. EC cos 5] sin Nt dt + In I. [0 sin i cos Nt dt.

By (79) and (81), g(t) cos (#/2) and g(z) sin (c/2) are bounded. The last
two integrals thus tend to 0 as N - oo, by (74). This proves (80).

Corollary If f(x) =0 for all x in some segment J, then lim sy(f; x) =0 for
every x \in J.

Here is another formulation of this corollary:
If f(t) = g(t) for all t in some neighborhood of x, then
sy(f3 x) = sn(g; x) = sy(f-g; x) >0as N- co.

This is usually called the localization theorem. It shows that the behavior
of the sequence {sy(f; x)}, as far as convergence is concerned, depends only on
the values of f in some (arbitrarily small) neighborhood of x. Two Fourier
series may thus have the same behavior in one interval, but may behave in
entirely different ways in some other interval. We have here a very striking
contrast between Fourier series and power series (Theorem 8.5).

We conclude with two other approximation theorems.

8.15 Theorem If f is continuous (with period 2n) and if \in > 0, then there is a
trigonometric polynomial P such that

[P(x) -f(x)| <e

for all real x.

Proof If we identify x and x + 27, we may regard the 2n-periodic func-
tions on R' as functions on the unit circle 7, by means of the mapping
x =e. The trigonometric polynomials, i.e., the functions of the form
(60), form a self-adjoint algebra «/, which separates points on 7, and
which vanishes at no point of 7. Since T is compact, Theorem 7.33 tells
us that o/ is dense in  \in (7°). This is exactly what the theorem asserts.

A more precise form of this theorem appears in Exercise 15.
SOME SPECIAL FUNCTIONS 191

8.16 Parseval’s theorem Suppose f and g are Riemann-integrable functions
with period 2, and

82) SO ~ Tee, gl) ~ Y pee.
Then
(83) lim = [1700 = su(f3 0] dx =0,
Noo 2nd
(84) - fga dx =Y 7
Pr = nVn>
55) = lr de=3 fe?
oe =) AES

Proof Let us use the notation
1 n 5 2
(56) A LCI

Let c > 0 be given. Since fe # and f(r) = f(- nr), the construction
described in Exercise 12 of Chap. 6 yields a continuous 2n-periodic func-
tion A with

(87) If=hl, <e.

By Theorem 8.15, there is a trigonometric polynomial P such that
|h(x) - P(x)| <e for all x. Hence [A - P|, <e. If P has degree N,,
Theorem 8.11 shows that

(88) Ih - snl < lh = Pll, <e
for all N > Ny. By (72), with h - fin place of f,
(89) lsn(h) = sh(Nll2 = lsy(h = Dla < Nh = fll. <e

Now the triangle inequality (Exercise 11, Chap. 6), combined with
(87), (88), and (89), shows that

(90) If = sv(Nl2 <3 (N= No).
This proves (83). Next,
1m LA TR Rp- N
on) | sgde=Y eso gde=) ed,

and the Schwarz inequality shows that

1 < [17=sxlgl <{[1r=su2 le"

[1a [sw

192 PRINCIPLES OF MATHEMATICAL ANALYSIS

which tends to 0, as N - oo, by (83). Comparison of (91) and (92) gives
(84). Finally, (85) is the special case g = f of (84).

A more general version of Theorem 8.16 appears in Chap. 11.

THE GAMMA FUNCTION

This function is closely related to factorials and crops up in many unexpected
places in analysis. Its origin, history, and development are very well described
in an interesting article by P. J. Davis (Amer. Math. Monthly, vol. 66, 1959,
pp. 849-869). Artin’s book (cited in the Bibliography) is another good elemen-
tary introduction.

Our presentation will be very condensed, with only a few comments after
each theorem. This section may thus be regarded as a large exercise, and as an
opportunity to apply some of the material that has been presented so far.

8.17 Definition For 0 < x < oo,
0

(93) I(x) = | let dr.
0

The integral converges for these x. (When x < 1, both 0 and oo have to
be looked at.)

8.18 Theorem
(a) The functional equation
I'(x +1) =xI'(x)
holds if 0 < x < co.

b) T(h+1)=nlforn=1,2,3,....
(c) log I is convex on (0, ©).

Proof An integration by parts proves (a). Since I'(1) =1, (a) implies

(b), by induction. If 1 <p < oo and (1/p) + (1/g) = 1, apply Holder's
inequality (Exercise 10, Chap. 6) to (93), and obtain

r(: + p < I(0)'/?T(y)e.
Pq
This is equivalent to (c).

It is a rather surprising fact, discovered by Bohr and Mollerup, that
these three properties characterize I' completely.
SOME SPECIAL FUNCTIONS 193

8.19 Theorem If fis a positive function on (0, ©) such that

(a fix+1)=xf(x),
® fM=1,

(c) logf is convex,

then f(x) = I'(x).

94)

(99)

Proof Since I satisfies (a), (5), and (c), it is enough to prove that f(x) is
uniquely determined by (a), (b), (c), for all x > 0. By (a), it is enough to
do this for x \in (0, 1).
Put c =logf. Then
p(x +1) = p(x) + log x (0< x < 00),

(1) =0, and c is convex. Suppose 0 < x < 1, and nis a positive integer.
By (94), c(n + 1) = log(n!). Consider the difference quotients of c on the
intervals [n,n + 1], [n+ 1,n+ 1+ x], [n+ 1,n + 2]. Since c is convex

tog < WHLFD 00H 10g r 41),

Repeated application of (94) gives
en + 1+ x) = p(x) + log [x(x + 1) *+* (x + n)].
Thus

02 009 og [cr] <i 141).

The last expression tends to 0 as n -» co. Hence c(x) is determined, and
the proof is complete.
As a by-product we obtain the relation

I(x) = lim nin”
lim -
now X(X +1) (x +n)

at least when 0 < x < 1; from this one can deduce that (95) holds for all x > 0,
since I'(x + 1) = xI'(x).

8.20 Theorem If x>0andy>0, then

(96)

Ix)re)
I'x+y) ’

1
| FY ty d=
[4s]

This integral is the so-called beta function B(x, y).
194 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Note that B(1, y) = 1/y, that log B(x, y) is a convex function of
x, for each fixed y, by Holder’s inequality, as in Theorem 8.18, and that

x
Oo” Bx + 1,y) = - B(x, y).
x+y
To prove (97), perform an integration by parts on
Bx+1,y) [ ( ! ) a YY dy
x = -_- - .
These three properties of B(x, y) show, for each y, that Theorem 8.19

applies to the function f defined by

rr
£0) = YEE

Hence f(x) = I'(x).

B(x, y).

8.21 Some consequences The substitution c = sin? a turns (96) into

HE - - re)re)
98 2 0)2>~1 9)2y-1 do = .
(98) J Gin0 oso) Ford
The special case x = y = 4 gives
(99) ra) =.
The substitution c = s? turns (93) into
(100) I(x) -2 sB lem ds (0< x < w).
0
The special case x = } gives
(101) [ eds =m.
By (99), the identity
2x1 +1
(102) Mx) =>- r(3)r(*5)
J 2 2

follows directly from Theorem 8.19.

8.22 Stirling’s formula This provides a simple approximate expression for

I'(x + 1) when x is large (hence for n! when #n is large). The formula is
I'x+1)

103 -_-=
(103) so (x/e)* 2nx
SOME SPECIAL FUNCTIONS 195

Here is a proof. Put # = x(1 + u) in (93). This gives
(104) Tx +1)=x**'e™™ | [(1 + we du.
-1
Determine /(u) so that (0) = 1 and
u?
(105) (1 + ue ™™ =exp [5h]

if -1 <w<oo,u#0. Then

IN)

(106) hu) = = [u - log (1 + w)].

[NY

u

It follows that /1 is continuous, and that 4(u) decreases monotonically from co
to 0 as u increases from -1 to co.
The substitution u = s 2x turns (104) into

(107) T(x +1) = xe /2x I Ws) ds
where
_ (expl=s*h(s /20)]  (=/x/2<s< 0),
Ys) = e c< -Jx/2).

Note the following facts about yr. (s):
(a) For every s, ,(s) »e™*" as x - 0.
(b) The convergence in (a) is uniform on [- 4, A], for every 4 < co.
(c) When s <0, then 0 < (5) <e™*.

(d) When s > 0 and x > 1, then 0 < (5s) < (5).

(© 13 ¥n(s)ds < co.

The convergence theorem stated in Exercise 12 of Chap. 7 can therefore
be applied to the integral (107), and shows that this integral converges to Jn
as x - 00, by (101). This proves (103).

A more detailed version of this proof may be found in R. C. Buck’s
“Advanced Calculus,” pp. 216-218. For two other, entirely different, proofs,
see W. Feller’s article in Amer. Math. Monthly, vol. 74, 1967, pp. 1223-1225
(with a correction in vol. 75, 1968, p. 518) and pp. 20-24 of Artin’s book.

Exercise 20 gives a simpler proof of a less precise result.
196 PRINCIPLES OF MATHEMATICAL ANALYSIS

EXERCISES
1. Define

[emt (x #0),
I =1o (x=0).

Prove that f has derivatives of all orders at x=0, and that f™(0)=0 for
n=123,....

2. Let a; be the number in the ith row and jth column of the array

-1 0 0 0
3 -1 0 0
t 3 -1 0
¥ t 3 -1
so that
0 i<j),
ay={-1 i=),
27-1 i>)
Prove that

3. Prove that

if ai; > 0 for all i and j (the case +c = + © may occur).
4. Prove the following limit relations:

(a) lim br=1_ logb  (b>0).
x0 Xx

(b) lim log (1 +x) =1.
x0 x

(0) lim(1 +x) =e.
x-=0

(d) lim (1 + 2) =e,

now
10.

SOME SPECIAL FUNCTIONS

. Find the following limits

(a) tim =A £0"
x=0 x :

(b) lim -2

nsx lOgn

[nn - 11.

© lim tan x - x
6 x(1 - cos x)”

. x-sinx
(d) lim --,
x=»0 tan x - x

. Suppose f(x) f(y) = f(x + y) for all real x and y.

(a) Assuming that fis differentiable and not zero, prove that
f(x) =e*

where cc is a constant.
(b) Prove the same thing, assuming only that f is continuous.

LIf0< x <3 prove that
2 _sinx 1
x
. Forn=20,1,2,..., and x real, prove that

|sin nx| < n|sin x].

197

Note that this inequality may be false for other values of n. For instance,

|sin #7 | > §|sin =|.

. (a) Put sy = 14 (3) + +++ (1/N). Prove that

lim (sy - log N)
Nox

exists. (The limit, often denoted by v, is called Euler’s constant. Its numerical

value is 0.5772.... It is not known whether y is rational or not.)
(b) Roughly how large must m be so that N = 10™ satisfies sy > 100?
Prove that Y_ 1/p diverges; the sum extends over all primes.

(This shows that the primes form a fairly substantial subset of the positive

integers.)
198 PRINCIPLES OF MATHEMATICAL ANALYSIS

Hint: Given N, let py, ..., px be those primes that divide at least one in-
teger <N. Then

The last inequality holds because
(1-x)"'<e?

ifo<x <4
(There are many proofs of this result. See, for instance, the article by
I. Niven in Amer. Math. Monthly, vol. 78, 1971, pp. 272-273, and the one by
R. Bellman in Amer. Math. Monthly, vol. 50, 1943, pp. 318-319.)
11. Suppose f \in  Z on [0, A) for all A < «©, and f(x) > 1 as x > +. Prove that

©

lim c | ei f()dx=1 (1>0).
t=0 0

12. Suppose 0 <8 <r, f(x) =1if |x| <3, f(x)=0if 8 < |x| <=, and f(x + 27) =
f(x) for all x.
(a) Compute the Fourier coefficients of f.
(b) Conclude that

$ sin (nd) 7 -38

PI 3 0 <d<m).
(c) Deduce from Parseval’s theorem that
© sin? "0d T-38
3 =
n=1

(d) Let 8 -0 and prove that

(e) Put 8 = 7/2 in (c). What do you get?
13. Put f(x) = x if 0 < x < 2m, and apply Parseval’s theorem to conclude that

2

©]
Tae
SOME SPECIAL FUNCTIONS 199

14. If f(x) = (mw - |x|)? on [-m, 7], prove that
f=T+ +52 - cos nx

and deduce that

(A recent article by E. L. Stark contains many references to series of the form
> n~*, where s is a positive integer. See Math. Mag., vol. 47, 1974, pp. 197-202.)
15. With D, as defined in (77), put

Kn) = 577 | > D(x).
Prove that
_ 1 1-cos(N+ Dx
Kv =§7 1-cos x
and that
(a) Ky=0,
1 n
®) 52 [ Knwdr=1,
2

(c) Kn(x) <-

<3 Ty H0<d<|xl<m

If sy = sx(f; x) is the Nth partial sum of the Fourier series of f, consider
the arithmetic means

So + S144 sw
N+1

aN =
Prove that
-
of =5[ fx- Ku),
TJ en

and hence prove Fejér’s theorem:
If f is continuous, with period 2m, then ox(f; x) - f(x) uniformly on [-m, mw].
Hint: Use properties (a), (b), (c) to proceed as in Theorem 7.26.
16. Prove a pointwise version of Fejér’s theorem:
If fe R and f(x +), f(x -) exist for some x, then

lim on(f; x) =H f(x +) + f(x-)]
200 PRINCIPLES OF MATHEMATICAL ANALYSIS

17.

18.

19.

20.

Assume f is bounded and monotonic on [-, 7), with Fourier coefficients c,, as
given by (62).

(a) Use Exercise 17 of Chap. 6 to prove that {nc,} is a bounded sequence.

(b) Combine (a) with Exercise 16 and with Exercise 14(e) of Chap. 3, to conclude
that

lim Sn(f3 x) = Hf (x+) + f(x-)]
for every x.
(c) Assume only that f \in  Z on [-m, m] and that f is monotonic in some segment
(2, B)< [-m, 7]. Prove that the conclusion of (b) holds for every x \in («, B).
(This is an application of the localization theorem.)
Define
f(x)=x®-sin? x tan x
g(x) = 2x? -sin? x - x tan x.
Find out, for each of these two functions, whether it is positive or negative for all
x \in (0, m/2), or whether it changes sign. Prove your answer.

Suppose f is a continuous function on R?, f(x + 2m) = f(x), and «/7 is irrational.
Prove that

lim + 3 feet n= [fdr

oe Ni=1 X + T2mlo.

for every x. Hint: Do it first for f(x) = e'**.
The following simple computation yields a good approximation to Stirling's
formula.

For m=1,2,3,..., define

fx)=(m+1-=x)logm-+ (x -m)log(m=+1)
if m<x <m+ 1, and define

xX
gx) ==" -1+logm

if m- 4 <x <m-+ % Draw the graphs of fand g. Note that f(x) <log x < g(x)
if x >1 and that

I f(x)dx=1log(n)-4logn> -% + [" g(x) dx.

Integrate log x over [1, n]. Conclude that
F<log(nh)-(n+4Hlogn+n<l
forn=2,3,4,.... (Note: log V2m ~ 0918....) Thus

118 n!
Serv, ©
21.

22.

SOME SPECIAL FUNCTIONS 201

Let
1 n
Li=5-[ ID) dt (n=1,2,3,....

Prove that there exists a constant C > 0 such that
L,>Clogn n=1,2,3,...),

or, more precisely, that the sequence
4
|r. -; log )
m

is bounded.
If « is real and -1 < x < 1, prove Newton's binomial theorem

(1+x)2=1+ gral ntD,

= n!

Hint: Denote the right side by f(x). Prove that the series converges. Prove that
(1 +x) f(x) = af (x)

and solve this differential equation.
Show also that

- 2 I'(n+ a)
(I=-n==3 WT ©

if -1<x<1anda>0.

. Let y be a continuously differentiable closed curve in the complex plane, with

parameter interval [a, b], and assume that y(c) # 0 for every c \in [a, b]. Define the
index of y to be
RAO)
Ind) =32), 50%
Prove that Ind (y) is always an integer.

Hint: There exists c on [a, b] with c’ = y'/y, p(a) = 0. Hence y exp(-q)
is constant. Since y(a) = y(b) it follows that exp c(b) = exp g(a) = 1. Note that
a(b) = 2mi Ind (y).

Compute Ind (y) when y(t) =e", a = 0, b = 2.

Explain why Ind (y) is often called the winding number of y around 0.

. Let y be as in Exercise 23, and assume in addition that the range of y does not

intersect the negative real axis. Prove that Ind (y) =0. Hint: For 0 <c< 0,
Ind (y + c) is a continuous integer-valued function of c. Also, Ind (y +c)-0
as c- 0.
202 PRINCIPLES OF MATHEMATICAL ANALYSIS

25.

26.

27.

28.

Suppose y, and y. are curves as in Exercise 23, and

[yit) - yo) < [7a] (aa<t <b).
Prove that Ind (y,) = Ind (y2).

Hint: Put y =y2/y,. Then |1 -vy| <1, hence Ind (y) = 0, by Exercise 24.

Also,

v_v_¥

Y Y2 1 ’
Let y be a closed curve in the complex plane (not necessarily differentiable) with
parameter interval [0, 27], such that y(t) # O for every c \in [0, 27].

Choose 8 > 0 so that |y(c)| > for all  \in [0, 27]. If P, and P, are trigo-
nometric polynomials such that |P,(t) - y(t)| <&/4 for all  \in [0, 27] (their exis-
tence is assured by Theorem 8.15), prove that

Ind (P,) = Ind (P,)
by applying Exercise 25.

Define this common value to be Ind (y).

Prove that the statements of Exercises 24 and 25 hold without any differenti-
ability assumption.

Let f be a continuous complex function defined in the complex plane. Suppose
there is a positive integer » and a complex number c # 0 such that

lim z="f(z) = c.

Iz]

Prove that f(z) = 0 for at least one complex number z.

Note that this is a generalization of Theorem 8.8.

Hint: Assume f(z) #0 for all z, define

y(t) = f(re')

for 0 <r < oo, 0 <t< 2m, and prove the following statements about the curves
Vel
(a) Ind (yo) = 0.
(b) Ind (y,) = n for all sufficiently large r.
(c) Ind (y,) is a continuous function of r, on [0, =).
[In (b) and (c), use the last part of Exercise 26.]

Show that (a), (b), and (c) are contradictory, since n > 0.
Let D be the closed unit disc in the complex plane. (Thus z \in D if and only if
|z] <1.) Let g be a continuous mapping of D into the unit circle 7. (Thus,
|g(z)| = 1 for every z \in D.)

Prove that g(z) = -z for at least one z \in T..

Hint: For0<r<1,0<t< 2m, put

y(t) = g(re"),

and put Y(t) = e~ y(t). If g(z) # -z for every z \in T, then {)(t) # -1 for every
t \in [0, 27]. Hence Ind (07) = 0, by Exercises 24 and 26. It follows that Ind (y,) =1.
But Ind (yo) = 0. Derive a contradiction, as in Exercise 27.
SOME SPECIAL FUNCTIONS 203

29. Prove that every continuous mapping f of D into D has a fixed point in D.
(This is the 2-dimensional case of Brouwer’s fixed-point theorem.)
Hint: Assume f(z) # z for every z \in D. Associate to each z \in D the point
g(z) \in T which lies on the ray that starts at f(z) and passes through z. Then g
maps D into T, g(z) = z if z \in T, and g is continuous, because
9(2) =z -s(2)[f(2) - 2],
where s(z) is the unique nonnegative root of a certain quadratic equation whose

coefficients are continuous functions of and z. Apply Exercise 28.
30. Use Stirling’s formula to prove that

Px +c)
Im = F® =

for every real constant c.

31. In the proof of Theorem 7.26 it was shown that

! 2\n 4
[Law dx =

forn=1, 2,3, ... . Use Theorem 8.20 and Exercise 30 to show the more precise
result

- 1 -
lim Vn | (1- x?) dx = Va.
Imve)
9

FUNCTIONS OF SEVERAL VARIABLES

LINEAR TRANSFORMATIONS

We begin this chapter with a discussion of sets of vectors in euclidean n-space R".
The algebraic facts presented here extend without change to finite-dimensional
vector spaces over any field of scalars. However, for our purposes it is quite
sufficient to stay within the familiar framework provided by the euclidean spaces.

9.1 Definitions

(a) A nonempty set X = R" is a vector space if x + ye X and cxe X
for all xe X, ye X, and for all scalars c.
b) Ifx,...,x,eR"and cy,..., c are scalars, the vector

eXy + + aX,

is called a linear combination of x,, ..., x,. If S< R" and if E is the set

of all linear combinations of elements of S, we say that S spans E, or that
E is the span of S.

Observe that every span is a vector space.
FUNCTIONS OF SEVERAL VARIABLES 205

(c) A set consisting of vectors Xy,..., X, (we shall use the notation
{X1,...,X,} for such a set) is said to be independent if the relation
c1xy +... + cx, = 0implies that c; =... = c, =0. Otherwise {Xy,..., X;}

is said to be dependent.

Observe that no independent set contains the null vector.
(d) If a vector space X contains an independent set of r vectors but con-
tains no independent set of r + 1 vectors, we say that X has dimension r,
and write: dim X =r.

The set consisting of 0 alone is a vector space; its dimension is O.
(e) An independent subset of a vector space X which spans X is called
a basis of X.

Observe that if B =(x,,...,X,} is a basis of X, then every x \in X
has a unique representation of the form x = Xc;x;. Such a representation
exists since B spans X, and it is unique since B is independent. The

numbers cy, ..., c, are called the coordinates of x with respect to the
basis B.
The most familiar example of a basis is the set {e;, ...,  \in ,}, where

e, is the vector in R" whose jth coordinate is 1 and whose other coordinates
are all 0. If xe R", x =(x,, ..., x,), then x =Xx,e;. We shall call

{en,...,e,}
the standard basis of R".

9.2 Theorem Let r be a positive integer. If a vector space X is spanned by a
set of r vectors, then dim X <r.

Proof If this is false, there is a vector space X which contains an inde-
pendent set Q ={y, ...,¥,+} and which is spanned by a set S, consisting
of r vectors.

Suppose 0 <i <r, and suppose a set S; has been constructed which
spans X and which consists of all y; with 1 <j <i plus a certain collection
of r - i members of Sy, say x,, ..., X,-;. (In other words, S; is obtained
from S, by replacing i of its elements by members of Q, without altering
the span.) Since S; spans X, y;. is in the span of S;; hence there are
scalars a,, ..., a;4(, b,, ..., b,_;, with a; = 1, such that

(+1

r-i
Y a;¥; + Y bx, =0.
= K=1

If all b,’s were O, the independence of Q would force all a;’s to be 0, a
contradiction. It follows that some X, \in S; is a linear combination of the
other members of T; = S; © {y;,}. Remove this x, from 7; and call the
remaining set S;.;. Then S;,, spans the same set as T;, namely X, so
that S;,, has the properties postulated for S; with i + 1 in place of i.
206 PRINCIPLES OF MATHEMATICAL ANALYSIS

Starting with S,, we thus construct sets S;,...,S,. The last of
these consists of yy,...,y,, and our construction shows that it spans X.
But Q is independent; hence y,,, is not in the span of S,. This contra-
diction establishes the theorem.

Corollary dim R" =n.

9.3

9.4

Proof Since {e,. ..., e,} spans R", the theorem shows that dim R" <n.
Since {ey ..., e,} is independent, dim R" > n.

Theorem Suppose X is a vector space, and dim X =n.

(a) A set E of n vectors in X spans X if and only if E is independent.

(b) X has a basis, and every basis consists of n vectors.

(c) Ifl <r<nandiy,,..., Y,} is an independent set in X, then X has a
basis containing {y,. ..., ¥,}.

Proof Suppose EF ={xy,..., Xx,}. Sincedim X =n, the set {x,,...,X,,y}
is dependent, for every y \in X. If E is independent, it follows that y is in
the span of E; hence E spans X. Conversely, if E is dependent, one of its
members can be removed without changing the span of E. Hence E
cannot span X, by Theorem 9.2. This proves (a).

Since dim X =n, X contains an independent set of »n vectors, and
(a) shows that every such set is a basis of X; (b) now follows from 9.1(d)
and 9.2.

To prove (c), let {x,...., x,} be a basis of X. The set

spans X and is dependent, since it contains more than »n vectors. The
argument used in the proof of Theorem 9.2 shows that one of the x;’s is
a linear combination of the other members of S. If we remove this x; from
S, the remaining set still spans X. This process can be repeated r times
and leads to a basis of X which contains {y, ..., y,}. by (a).

Definitions A mapping A of a vector space X into a vector space Y is said

to be a linear transformation if

A(Xy + X,) = AX, + AX,, A(ex) = cAX

for all x, x,, x, \in X and all scalars c. Note that one often writes Ax instead
of A(x) if A is linear.

Observe that 40 = 0 if 4 is linear. Observe also that a linear transforma-

tion 4 of X into Y is completely determined by its action on any basis: If
FUNCTIONS OF SEVERAL VARIABLES 207

{Xy,...,X,} is a basis of X, then every x \in X has a unique representation of the
form

and the linearity of A allows us to compute Ax from the vectors Ax,, ..., Ax,
and the coordinates cy, ..., c, by the formula
n
Ax =Y c; Ax.
i=1

Linear transformations of X into X are often called linear operators on X.
If A is a linear operator on X which (i) is one-to-one and (ii) maps X onto
X, we say that A is invertible. In this case we can define an operator 4! on X
by requiring that A- (Ax) = x for all xe X. It is trivial to verify that we then
also have A(A “1x) =x, for all x \in X, and that A™! is linear.

An important fact about linear operators on finite-dimensional vector
spaces is that each of the above conditions (i) and (ii) implies the other:

9.5 Theorem A linear operator A on a jinite-dimensional vector space X is
one-to-one if and only if the range of A is all of X.

Proof Let {X;...., X,} be a basis of X. The linearity of A shows that
its range A(A) is the span of the set Q ={Ax,, ..., Ax,}. We therefore
infer from Theorem 9.3(a) that (A) = X if and only if Q is independent.
We have to prove that this happens if and only if A is one-to-one.
Suppose A is one-to-one and Lc; Ax, =0. Then A(Xcx;) =0, hence

Yeix; =0, hence c; =... =c, =0, and we conclude that Q is independent.
Conversely, suppose Q is independent and A(Xc;x;) =O. Then
Y¥c;Ax, =0. hence c; =... =c,=0, and we conclude: Ax =0 only if

x =0. {now Ax = Ay, then AX - y)=Ax - Ay =0,s0 that x - y =0,
and this says that A is one-to-one.

9.6 Definitions

(a) LetL(X,Y )bethesetof all linear transformations of the vector space
X into the vector space Y. Instead of L(X, X), we shall simply write L( X).
If A,, A, EL(X, Y)and if c,, c, are scalars, define c;A, + c, A, by

(cA; +c, Ax =c Aix +c, Ax (xe X).
It is then clear that c, A, + c, A, e L(X, Y).
(b) If X,Y, Z are vector spaces, and if A £ L(X. Y)and BE L(Y,Z), we
define their product BA to be the composition of A and B:

(BA)X = B(Ax) (xe X).

Then BAe L(X, Z).
208 PRINCIPLES OF MATHEMATICAL ANALYSIS

9.7

Note that BA need not be the same as AB, even if X =Y =Z.
(c) For AeL(R", R™), define the norm | Al of A to be the sup of all
numbers | Ax|, where x ranges over all vectors in R" with |x| < 1.
Observe that the inequality

|Ax| < [4] |x]
holds for all x \in R". Also, if 2 is such that |Ax| < A|x| for all xe R",
then 4] < 4.
Theorem

(a) If Ae L(R", R™), then |A| < oc and A is a uniformly continuous
mapping of R" into R™.
(b) If A, Be L(R", R™) and c is a scalar, then

4+ Bl <All +1Bl,  lcdll =|c| [4].

With the distance between A and B defined as |A - B|, L(R", R™) is a
metric space.
(c) If Ae L(R", R™) and Be L(R™, RY), then

|BA| < |B] |All.
Proof

(a) Let {e,,...,e,} be the standard basis in R" and suppose x = Zce;,
|x| <1, so that |c;| <1fori=1,...,n Then

lax] =|} ci de;| <} lei] |de;| <} | Ae
so that

|All <3 | Ae] < co.
i=1

Since | Ax - Ay| < 4] |x -y| if x, y \in R", we see that 4 is uniformly
continuous.
(b) The inequality in (b) follows from

(4 + Bx| = | Ax + Bx| < | Ax| + |Bx| < (| 4] + |B]) |x].
The second part of (b) is proved in the same manner. If
A, B, Ce L(R", R™),
we have the triangle inequality

l4-Cl=I(4-B+B-C)|<l4-B|+[B-C|,
FUNCTIONS OF SEVERAL VARIABLES 209

and it is easily verified that | 4 - B|| has the other properties of a metric
(Definition 2.15).
(cc) Finally, (c)follows from

[BAX] = [B(Ax)| < [|B | Ax| < || BI || 4] |x|.

Since we now have metrics in the spaces L(R", R"), the concepts of open

set, continuity, etc., make sense for these spaces. Our next theorem utilizes
these concepts.

9.8 Theorem Let Q be the set of all invertible linear operators on R".

(nH

a

(a) IfA \in Q, Be L(R"), and
IB-All- 47") <1,

then Be Q.
(b) Ris an open subset of L(R"), and the mapping A - A~! is continuous
on R.

(This mapping is also obviously a | - I mapping of R onto Q,
which is its own inverse.)

Proof

(a) Put |A™'| =1/x. put B - A =f. Then ff <a. For every xR",

ax] =A Ax] <a AH] | Ax]
= |Ax| < [(4 - B)x| + | Bx| < B|x| + | Bx|,
so that
(a- px < [Bx]  (xeR).

Since oo - > 0, (1) shows that Bx # 0 if x #0. Hence Bis | - I
By Theorem 9.5, BER. This holds for all B with ( B- Al <a. Thus
we have (a)and the fact that R is open.
(b) Next, replace x by B~'yin (1). The resulting inequality

(=PpIB7y|<|BB 'y|=|y] (yeR)
shows that |B™'| < (r - B)~'. The identity
B'-A4'=B'4-BA",
combined with Theorem 9.7(c), implies therefore that

_F
ae ~ f)

This establishes the continuity assertion made in (b),since f -»0 as B- A.

IB7 =A < |B!) [A= BI 47) <
210 PRINCIPLES OF MATHEMATICAL ANALYSIS

9.9 Matrices Suppose {X,..., X,} and {y,, ..., y,} are bases of vector spaces
X and Y, respectively. Then every A \in L(X, Y) determines a set of numbers
a;; such that

3) Ax; =X a; y; (1<j<n).

It is convenient to visualize these numbers in a rectangular array of m rows
and n columns, called an m by n matrix:

ayy diz Ain

a a a
[l= 2 2 ”

Ant Amz °° Cp

Observe that the coordinates a,; of the vector 4x; (with respect to the basis
{¥Y1, ++, ¥m}) appear in the jth column of [A]. The vectors Ax; are therefore
sometimes called the column vectors of [A]. With this terminology, the range
of A is spanned by the column vectors of [A].

If x = Zc; x;, the linearity of A, combined with (3), shows that

4) Ax -¥ (£0 c) Yi.

=

Thus the coordinates of Ax are X;a;;c;. Note that in (3) the summation
ranges over the first subscript of a;;, but that we sum over the second subscript
when computing coordinates.

Suppose next that an m by n matrix is given, with real entries a;;. If A is
then defined by (4), it is clear that A \in L(X, Y) and that [A Jis the given matrix.
Thus there is a natural 1-1 correspondence between L(X, Y) and the set of all
real m by n matrices. We emphasize, though, that [A Jdepends not only on A
but also on the choice of bases in X and Y. The same A may give rise to many
different matrices if we change bases, and vice versa. We shall not pursue this
observation any further, since we shall usually work with fixed bases. (Some
remarks on this may be found in Sec. 9.37.)

If Z is a third vector space, with basis {z,,...,z,}, if A is given by (3),
and if

By: =) bu, (BAX; = cis
then A \in L(X, Y), Be L(Y,Z), BA \in L(X, Z), and since
B(Ax;) = BY aijyi = ) a;; By,
t 13

=X ay Xba =2 (Zz buy) Zz,
FUNCTIONS OF SEVERAL VARIABLES 211

the independence of {z,, ..., z,} implies that

®) ay =2 bua (I<sk<p l<j<n).

This shows how to compute the p by n matrix [BA] from [B] and [4]. If we
define the product [B][4] to be [BA], then (5) describes the usual rule of matrix
multiplication.

Finally, suppose {X, ..., X,} and {y, ..., ¥..} are standard bases of R" and
R™ and A is given by (4). The Schwarz inequality shows that

| Ax |? =y Z ai; 65)" <y (Z al: ) 4) =Y ajix|*
t J 4 J J LJ

Thus
6) 41 < (2 ai.

LJ
If we apply (6) to B- A in place of 4, where 4, Be L(R", R™), we see
that if the matrix elements a;; are continuous functions of a parameter, then the
same is true of 4. More precisely:

If S is a metric space, if ayy, ..., a, are real continuous functions on S,
and if, for each p \in S, A, is the linear transformation of R" into R™ whose matrix
has entries a;(p), then the mapping p- A, is a continuous mapping of S into
L(R", R™).

DIFFERENTIATION

9.10 Preliminaries In order to arrive at a definition of the derivative of a
function whose domain is R" (or an open subset of R"), let us take another look
at the familiar case n = 1, and let us see how to interpret the derivative in that
case in a way which will naturally extend to n > 1.

If fis a real function with domain (a, b) = R' and if x \in (a, b), then f'(x)
is usually defined to be the real number

Sx +h) - f(x)
0 mee,

provided, of course, that this limit exists. Thus

®) Sx +h) = f(x) =f") + rh)
where the “remainder” r(#) is small, in the sense that
9) lim ré) =0.

h=0
212 PRINCIPLES OF MATHEMATICAL ANALYSIS

Note that (8) expresses the difference f(x + 4) - f(x) as the sum of the
linear function that takes h to f’(x)h, plus a small remainder.

We can therefore regard the derivative of f at x, not as a real number,
but as the linear operator on R' that takes 4 to f'(x)h.

[Observe that every real number o gives rise to a linear operator on R';
the operator in question is simply multiplication by a. Conversely, every linear
function that carries R' to R' is multiplication by some real number. It is this
natural 1-1 correspondence between R' and L(R') which motivates the pre-
ceding statements. ]

Let us next consider a function f that maps (a, b) = R! into R™. In that
case, f'(x) was defined to be that vector y \in R™ (if there is one) for which
a0) i [£0 8)

h=0

y; =0.

We can again rewrite this in the form
(11) f(x + h) - f(x) = hy + r(h),

where r(h)/h - 0 as h- 0. The main term on the right side of (11) is again a
linear function of A. Every y \in R™ induces a linear transformation of R' into
R™, by associating to each he R' the vector hy \in R™. This identification of R™
with L(R', R™) allows us to regard f(x) as a member of L(R!, R™).

Thus, if fis a differentiable mapping of (a, b) = R' into R™, and if x \in (a, b),
then f(x) is the linear transformation of R' into R™ that satisfies

i FG) = £00) = FG _

12 0,
12) Jim p
or, equivalently,
f h) - f(x) -f’
03) i CHB) = 1G) - Ton] _
h=0 [A]

We are now ready for the case n > 1.
9.11 Definition Suppose E is an open set in R", f maps E into R", and x \in E.
If there exists a linear transformation A of R" into R™ such that

(14) Jim x +B) - f(x) - 4h| =

0,
h~0 h|

then we say that f is differentiable at x, and we write
(15) f'(x) =A.

If f is differentiable at every x \in E, we say that f is differentiable in E.
FUNCTIONS OF SEVERAL VARIABLES 213

It is of course understood in (14) that h \in R". If |h| is small enough, then
x + h \in E, since E is open. Thus f(x + h) is defined, f(x + h) \in R™, and since
Ae L(R", R™), Ahe R". Thus
f(x +h) - f(x) - Ahe R™.
The norm in the numerator of (14) is that of R™. In the denominator we have
the R"-norm of h.

There is an obvious uniqueness problem which has to be settled before
we go any further.

9.12 Theorem Suppose E and f are as in Definition 9.11, x \in E, and (14) holds
with A = A, and with A = A,. Then A; = A,.
Proof If B=A4, - A4,, the inequality
| Bh| < [£(x +h) = f(x) - 4;h| + [f(x +b) - f(x) - 4, h]|
shows that |Bh|/|h| - 0 as h- 0. For fixed h # 0, it follows that
| B(th)
-
[th]

The linearity of B shows that the left side of (16) is independent of t.
Thus Bh =0 for every he R". Hence B =0.

(16) 0 as t-0.

9.13 Remarks
(a) The relation (14) can be rewritten in the form
(17 f(x +h) - f(x) =’ (Xh + r(h)

where the remainder r(h) satisfies

(18) tim EOL _

- =0.
no |h

We may interpret (17), as in Sec. 9.10, by saying that for fixed x and small
h, the left side of (17) is approximately equal to f'(x)h, that is, to the value
of a linear transformation applied to h.

(b) Suppose f and E are as in Definition 9.11, and f is differentiable in E.
For every x \in E, f'(x) is then a function, namely, a linear transformation
of R" into R™. But f’ is also a function: f’ maps E into L(R", R™).

(c) A glance at (17) shows that f is continuous at any point at which f is
differentiable.

(d) The derivative defined by (14) or (17) is often called the differential
of f at x, or the total derivative of { at x, to distinguish it from the partial
derivatives that will occur later.
214 PRINCIPLES OF MATHEMATICAL ANALYSIS

9.14 Example We have defined derivatives of functions carrying R" to R™ to
be linear transformations of R" into R™. What is the derivative of such a linear
transformation? The answer is very simple.

IfAeL(R" R")and f x \in  R", then
(19) A(X) = A.
Note that x appears on the left side of (19), but not on the right. Both

sides of (19)are members of L(R", R"), whereas Ax \in R".
The proof of (19)is a triviality, since

(20) A(x +h)- Ax=Ah,
by the linearity of A. With f(x)= Ax, the numerator in (/4)is thus O for every
he R" In (17), r(h) = 0.

We now extend the chain rule (Theorem 5.5) to the present situation.

9.15 Theorem Suppose Eis an open set in R", f maps E into R", { is dzfferentiable
at Xo \in E, gc maps an open set containing f(E )into R*, and g is differentiable at
f(Xo). Then the mapping F of E into R* dejined by

F(x) = gf (x)
is dzfferentiable at Xo, and
a1) F'(xo) = g'(f (xo) (Xo).

On the right side of (21), we have the product of two linear transforma-
tions, as defined in Sec. 9.6.

Proof Puty, =f(Xg), A = (Xo), B =g'(Yo), and define
uth) = (xo +h) - [(xo) - Ah,
v(k) =g(yo + k) - 8(Yo) - Bk,

for all he R" and k \in R™ for which f(x, + &) and g(y, + k) are defined.
Then

(22) |u(h)| = g(h)|h|, [v(K)| = n(k)|Kk]|,
where gh) » 0 as 7 - 0 and n(k)- 0 as k > 0.
Given h, put k = (Xo +h) - f(Xo). Then

(23) |k| = | 4h +uh)| < [14] + e()] |h],
and
F(xo + i) - F(xo) - BAh =g(y, + Kk) - g(yo) - B4h
- B(k- Ah) + v(k)
= Bu(h) + v(k).
FUNCTIONS OF SEVERAL VARIABLES 215

Hence (22) and (23) imply, for h # 0, that
| F(xo +h) - F(x,) - BAh|
[h|

Let h-0. Then &h)-0. Also, k= 0, by (23), so that 5(k)- 0.
It follows that F'(x,) = BA, which is what (21) asserts.

< |1Bl eh) + [14] + eb) nk).

9.16 Partial derivatives We again consider a function f that maps an open
set E c R" into R". Let {e,,...,e,} and {u,, ..., u,} be the standard bases of
R" and R™. The components off are the real functions fi, ..., f,, defined by

24) 100 = 3. fou (xe E),

or, equivalently, by f(x) = f(x) u;, 1 <i Im.
For xe E, 1<i<m,1<j<n, we define

fim £06 + 10) = fix)
t=0 t

(25) (D;£)(x)

provided the limit exists. Writing fi(x,,..., x,) in place of f(x), we see that
Df; is the derivative of f; with respect to x;, keeping the other variables fixed.
The notation

of

(26) ox,

is therefore often used in place of D;f;, and D,f; is called a partial derivative.

In many cases where the existence of a derivative is sufficient when dealing
with functions of one variable, continuity or at least boundedness of the partial
derivatives is needed for functions of several variables. For example, the
functions f and g described in Exercise 7, Chap. 4, are not continuous, although
their partial derivatives exist at every point of R?. Even for continuous functions.
the existence of all partial derivatives does not imply differentiability in the sense
of Definition 9.11; see Exercises 6 and 14, and Theorem 9.21.

However. if f is known to be differentiable at a point Xx, then its partial
derivatives exist at x, and they determine the linear transformation f'(x)
completely:

9.17 Theorem Suppose f maps an open set E = R" into R", andf is dzfferentiable
at a point x \in E. Then the partial derivatives (D,;f;)(x) exist, and

a7 £/(x)e; = So, fu Ain).

i
216 PRINCIPLES OF MATHEMATICAL ANALYSIS

Here, as in Sec. 9.16, {e,, ...,c,} and {u,,...,u,} are the standard bases
of R" and R™.

Proof Fix j. Since f is differentiable at x,
f(x + te;) - f(x) =1'(x)(te;) + r(te))
where |r(te;)|/t = 0 as t »0. The linearity of f'(x) shows therefore that

28) lim f(x + a - f(x)

t-0

=Tf'(x)e;.

If we now represent f in terms of its components, as in (24), then (28)
becomes

(29) lim 3 frie) J, (xe,
t-=0i=1

It follows that each quotient in this sum has a limit, as t = 0 (see Theorem
4.10), so that each (D;f;)(x) exists, and then (27) follows from (29).

Here are some consequences of Theorem 9.17:
Let [f'(x)] be the matrix that represents f'(x) with respect to our standard
bases, as in Sec. 9.9.

Then f'(x)e; is the jth column vector of [f'(x)], and (27) shows therefore
that the number (D;f;)(x) occupies the spot in the ith row and jth column of
[f'(x)]. Thus

(D1 f)X) + (Duf)X)
[(f'ex)] =

(Difu)®) rr (Dofn)(X)
If h = Zhe; is any vector in R", then (27) implies that

0) ron 3.1 3 (,facon),

9.18 Example Let y be a differentiable mapping of the segment (a, b) = R*
into an open set E< R" in other words, y is a differentiable curve in E. Let f
be a real-valued differentiable function with domain E. Thusf is a differentiable
mapping of E into R'. Define

a3n 9) =f) (aa<t<b).

The chain rule asserts then that

(2) gO =romONa (a<t<b).
FUNCTIONS OF SEVERAL VARIABLES 217

Since y'(t)e L(R', R") and f'(y(t)) \in L(R", R'), (32) defines g(t) as a linear
operator on R!. This agrees with the fact that g maps (a, b) into R*. However,
g'(t) can also be regarded as a real number. (This was discussed in Sec. 9.10.)
This number can be computed in terms of the partial derivatives of f and the
derivatives of the components of y, as we shall now see.

With respect to the standard basis {e;, ..., e,} of R", [y'(c)] is the n by 1
matrix (a “column matrix”) which has 7; (c) in the ith row, where y,, ..., y, are
the components of y. Forevery x \in E, [f'(x)] is the 1 by n matrix (a “row matrix”)
which has (D;f)(x) in the jth column. Hence [c'(c)] is the 1 by | matrix whose
only entry is the real number

(33) gt) = 3 (Dif): (0).

This is a frequently encountered special case of the chain rule. It can be
rephrased in the following manner.

Associate with each xe E a vector, the so-called “gradient” of f at x,
defined by

ED) (VHX) = 3. (Df We.
Since

(39) 70 = ¥ 1 We,

(33) can be written in the form

(36) g®) = (NEW) -y'(a),

the scalar product of the vectors (Vf)(y(c)) and y'(c).
Let us now fix an x \in E, let u \in R" be a unit vector (that is, |u| = 1), and
specialize y so that

(37) y(t) =X + tu (- oo <t< 0).
Then y(t) = u for every ct. Hence (36) shows that
(38) g'(0) = (V(x) - u.
On the other hand, (37) shows that
g(t) - g(0) = f(x + ru) - f(x).
Hence (38) gives

9) fi FOF 10) = £0)

t=0 t

= (VHX u
218 PRINCIPLES OF MATHEMATICAL ANALYSIS

The limit in (39)is usually called the directional derivative off at x, in the
direction of the unit vector u, and may be denoted by (D, f)(X).

Iff and x are fixed, but u varies, then (39) shows that (D, f)(X) attains its
maximum when u is a positive scalar multiple of (Vf)(x). [The case (Vf)(x) =0
should be excluded here.]

If u = Zu,e;, then (39) shows that (D, f)(x) can be expressed in terms of

ivio

the partial derivatives off at x by the formula

(40) (Du f)(x) = py (Dif )X)u;.
Some of these ideas will play a role in the following theorem.

9.19 Theorem Suppose [ maps a convex open set E = R" into R", | is differen-
tiable in E, and there is a real number M such that

fl < M
for every x \in E. Then
£6) - fa)| < Mb - a
forallac E, be E.
Proof Fix ae E, be E. Define
y#) =(1 - t)a + tb
for all te R' such that y(t)e E. Since E is convex, y(c)e Eif 0 Xt 7 I.

Put
g(t) = ; 6).
Then
gO) =£'GON® =; GO)b - a),
so that

[gO] < If" GEN) [b-al < M[b- al
for all re [0,1]. By Theorem 5.19,
lg(1) - gO) < M[b _ al.
But g(0) = f(a) and g(1) = f(b). This completes the proof.

Corollary If, in addition, £'(x) = 0 for all x \in E, then f is constant.

Proof To prove this, note that the hypotheses of the theorem hold now
with M =0.
FUNCTIONS OF SEVERAL VARIABLES 219

9.20 Definition A differentiable mapping f of an open set Ec R" into R" is
said to be continuously differentiable in E if f' is a continuous mapping of E
into L(R", R™).

More explicitly, it is required that to every x \in E and to every &c >0
corresponds a 6 > 0 such that

If'y) -'x)ll<e

ifyeFand |x -y|<d.
If this is so, we also say that f is a %'-mapping, or that f \in c'(E).

9.21 Theorem Suppose f maps an open set E = R" into R™. Then fe %'(E)
andonly if thepartial derivatives D; f; exist and are continuous on Efor 1 <i<m,
I<j<n

Proof Assume first that f \in  \in '(E). By (27),
(D;f)(x) = (f'(x)e) * u;
for all i, j, and for all x \in E. Hence
(Dif)y) = (Df)x) ={f'(y) -T'(X)]e;} . u,
and since |u| = |e;| =1, it follows that
(D3) = (DIX < |H() - 1 (x)]e|
< f(y) - fF’).
Hence D;f; is continuous.
For the converse, it suffices to consider the case m =1. (Why?)
Fix xe E and c > 0. Since E is open, there is an open ball S c E, with

center at Xx and radius r, and the continuity of the functions D;f shows
that » can be chosen so that

(a1) (DH) - DH] <= (eS, 1<j<n.

Suppose h =Zh;e;, |h| <r, putv, =0,andv, = he, + + he,
for <k <n. Then

n

(42) Sh) = f(x) = [f(x +v) = fx + v0].

j=1

Since |v] <1 for I <k <n and since S is convex, the segments with end
points x + Vv;_, and x + v; lie in S. Since v; =v;_; + h; \in ;, the mean
value theorem (5.10) shows that the jth summand in (42) is equal to

(DX + vy + 0;h;e))
220 PRINCIPLES OF MATHEMATICAL ANALYSIS

for some 0; \in (0, 1), and this differs from h;(D;f)(X) by less than |A;|e/n,
using (41). By (42), it follows that

n 1»
Sex +) = £00 = Lh(D,N)9| <= 3 |hyle < [hls

for all h such that |[h| <r.

This says that f is differentiable at x and that f'(x) is the linear
function which assigns the number ZA;(D;f)(x) to the vector h = Zh;e;.
The matrix [ f(x) Jconsists of the row (D{f)(X), ...,(D,f)x); and since
D,f,..., D,f are continuous functions on E, the concluding remarks of
Sec. 9.9 show that f \in   \in '(E).

THE CONTRACTION PRINCIPLE

We now interrupt our discussion of differentiation to insert a fixed point
theorem that is valid in arbitrary complete metric spaces. It will be used in the
proof of the inverse function theorem.

9.22 Definition Let X be a metric space, with metric d. If c maps X into X
and if there is a number c < I such that

(43) d(e(x), o(»)) <c d(x, y)

for all x, y \in X, then c is said to be a contraction of X into X.

9.23 Theorem If X is a complete metric space, and if a is a contraction of X
into X, then there exists one and only one x \in X such that c(x) = x.

In other words, c has a unique fixed point. The uniqueness is a triviality,
for if a(x) = x and a(¥) = y, then (43) gives d(x, y)< c d(x, y), which can only
happen when d(x, y) =0.

The existence of a fixed point of c is the essential part of the theorem.
The proof actually furnishes a constructive method for locating the fixed point.

Proof Pick xq \in X arbitrarily, and define {x,) recursively, by setting
(44) X41 = a(x,) n=0,1,2,...).
Choose c < I so that (43)holds. For n> I we then have
dX 41, Xp) = d(a(X,), 9(x,-1)) < cd(x,, X,- 1).
Hence induction gives

(45) A(Xp4 15 Xp) < "d(x, Xo) n=0,1,2,...).
FUNCTIONS OF SEVERAL VARIABLES 221

If n < m, it follows that

dp x) <3 dixie)

i=n+1
< (c" + ent 4+ cm d(x,, Xo)
<1 =o) d(xy, x0)]e"

Thus {x,) is a Cauchy sequence. Since Xis complete, lim x, = x for some
xe X.

Since c is a contraction, c is continuous (in fact, uniformly con-
tinuous) on X. Hence

a(x) = lim a(x,) = lim x, ; =x.

n-w n= w

THE INVERSE FUNCTION THEOREM

The inverse function theorem states, roughly speaking, that a continuously
differentiable mapping f is invertible in a neighborhood of any point x at which
the linear transformation f'(x)is invertible :

9.24 Theorem Suppose [ is a  \in '-mapping of an open set E = R" into R", f(a)
is invertible for some a \in E. and b = f(a). Then

(a) there exist open sets Uand Vin R" such that a \in  U, be V, { is one-to-
oneon U, and {(U)=V ;
(b) if gis the inverse o ff [whichexists, by (a)] defined in V by

gf(x) =x (xe),
then ge  \in '(V).

Writing the equation y = f(x) in component form, we arrive at the follow-
ing interpretation of the conclusion of the theorem: The system of n equations

yi=filxy,....x)  (1<i<n)

can be solved for x,, ..., x, in terms of y;,..., y,, if we restrict x and y to small
enough neighborhoods of a and b; the solutions are unique and continuously
differentiable.

Proof
(a) Putf’(a) =A, and choose / so that
(46) 24471 = 1.
222 PRINCIPLES OF MATHEMATICAL ANALYSIS

47

(48)

(49)

(50)

(51)

Since f' is continuous at a, there is an open ball U c E, with center at a,
such that
f(x) -A4| <1 xe).
We associate to each ye R”" a function a, defined by
ox) =x+ A" y -f(x)) (xeE).

Note that £(x) = y if and only if x is ajixedpoint of a.

Since a'(x) =1- A7'(x)=A-"(A - ['(x)), (46) and (47) imply
that

loll <3 (xel).
Hence
[p(x1) = a(x3)] <x; = xy (xy, x, \in UV),

by Theorem 9.19. It follows that c has at most one fixed point in U, so

that f(x) = y for at most one x \in U.
Thus fis | - 1 in U.

Next, put V={f(U), and pick yo \in V. Then y, =f(x;) for some
Xo \in U. Let B be an open ball with center at Xo and radius r > 0, so small
that its closure B liesin U. We will show that y e Vwhenever | y - yo | < Ar.
This proves, of course, that Vis open.

Fix y. |y - ¥o| < Ar. With c as in (48),
_ . RP
[a(X0) = Xo| = [47'(Y = yo) < 47" [lAr =3-
If x \in B, it therefore follows from (50) that
[p(x) = Xo| < [a(x) = a(x0)| + [9(X0) - Xo|

<llx-x| +s
= |x =x <r;
2 0

hence a(x) \in B. Note that (50)holds if x; \in B. Xx, = B.
Thus c is a contraction of B into B. Being a closed subset of R".
B is complete. Theorem 9.23 implies therefore that c has a fixed point
x  \in B. For this x, f(x)=y. Thus yef(B)cf(U)= V.
This proves part (a) of the theorem.

(b) Pick yeV, y+keV. Then there exist xe U, x + he U, so that
y=1f(x),y+tk=f(x+h). With c as in (48),

ox +h) - (x) =h+ A7'[f(x) - f(x +h] =h- 47k.
By (50), |h - A"'k| <1|h|. Hence |4™'k|>1|h
Ih < 2047] [Kk] = 27K].

, and
FUNCTIONS OF SEVERAL VARIABLES 223

By (46), (47), and Theorem 9.8, f'(x) has an inverse, say T. Since
g(y+k)- 8) - Tk =h- Tk = =T[f(x + h) - f(x) - f(x)h],
(51) implies

ley +k) - gy) - Tk| [7] [f(x +h) - f(x) - {Goh
Ik| oA [h|

As k = 0, (51) shows that h - 0. The right side of the last inequality
thus tends to 0. Hence the same is true of the left. We have thus proved
that g’(y) = T. But T was chosen to be the inverse off '(x) = f’(g(y)). Thus

(52) gm =e! (el)

Finally, note that g is a continuous mapping of V onto U (since g
is differentiable), that f' is a continuous mapping of U into the set Q of
all invertible elements of L(R"), and that inversion is a continuous mapping
of Q onto Q, by Theorem 9.8. If we combine these facts with (52), we see
that ge  \in '(V).

This completes the proof.

Remark. The full force of the assumption that f \in   \in '(E) was only used
in the last paragraph of the preceding proof. Everything else, down to Eq. (52),
was derived from the existence of f(x) for x \in E, the invertibility of f'(a), and
the continuity off" at just the point a. In this connection, we refer to the article
by A. Nijenhuis in Amer. Math. Monthly, vol. 81, 1974, pp. 969-980.

The following is an immediate consequence of part (a) of the inverse
function theorem.

9.25 Theorem Iff is a  \in ’-mapping d an open set E c R" into R" and if f'(x)
is invertiblefor every x \in E, then f(W) is an open subset d R"for every open set
W cE.

In other words, f is an open mapping of E into R".

The hypotheses made in this theorem ensure that each point x \in E has a
neighborhood in which f is 1-1. This may be expressed by saying that f is
locally one-to-one in E. But f need not be 1-1 in E under these circumstances.
For an example, see Exercise 17.

THE IMPLICIT FUNCTION THEOREM i

Iff is a continuously differentiable real function in the plane, then the equation
f(x,y) =0 can be solved for y in terms of x in a neighborhood of any point
224 PRINCIPLES OF MATHEMATICAL ANALYSIS

(a, b)at which f(a,b)=0 and 0f/0y # 0. Likewise, one can solve for x in terms
of y near (a, b) if 0f/0x # 0 at (a, b). For a simple example which illustrates
the need for assuming df/dy # 0, consider f(x, y) =x? + y* - I.

The preceding very informal statement is the simplest case (the case
m =n =| of Theorem 9.28) of the so-called "implicit function theorem." Its
proof makes stronguse of the fact that continuously differentiable transformations
behave locally very much like their derivatives. Accordingly, we first prove
Theorem 9.27, the linear version of Theorem 9.28.

9.26 Notation If x =(x,,...,X,) \in R" and y=(y,,..., Yu) \in R", let us write
(x,y) for the point (or vector)

(X15 ves Xps Vis oes Ym) ERP

In what follows, the first entry in (x, y) or in a similar symbol will always be a
vector in R", the second will be a vector in R™.

Every A \in L(R"*™, R") can be split into two linear transformations A, and
A,, defined by

(53) A h=AMh,0), Ak=A0k)
for any he R", k \in R". Then A,  \in e L(R"),A, \in L(R", R"), and
(4) AM, K) =A. h + 4k

The linear version of the implicit function theorem is now almost obvious.

9.27 Theorem If Ae L(R"™™, R")and if A, is invertible, then there corresponds
to every k \in R" a unique h \in R" such that Ath, k)=0.
This h can be computed from k by the formula

(55) h=-(4,)"'4,k
Proof By (54), A(h, k)=0 if and only if
Ah + 4k=0,
which is the same as (55) when A, is invertible.
The conclusion of Theorem 9.27 is, in other words, that the equation
A(h, k) =0 can be solved (uniquely) for 4 if k is given, and that the solution h

is a linear function of k. Those who have some acquaintance with linear algebra
will recognize this as a very familiar statement about systems of linear equations.

9.28 Theorem Let f be a 4'-mapping of an open set E< R**™ into R", such
that f(a, b) = 0 for some point (a, b)< E.
Put A =f'(a, b) and assume that A, is invertible.
FUNCTIONS OF SEVERAL VARIABLES 225

Then there exist open sets Uc R"*™ and Wc R™, with (a,b)e U and
be W, having the following property:
To every ye W corresponds a unique x such that

(56) (x,y)e U and f(x,y) =0.
If this x is defined to be g(y), then g is a %"-mapping of W into R", g(b) = a,
eh) fey.) =0 (yew),
and
(58) g'(b) = -(4,)7'4,.

The function g is "implicitly" defined by (57). Hence the name of the
theorem.

The equation f(X,y) =0 can be written as a system of n equations in
n + m variables:

(59) TTT TT TTT
So(Xys eee Xp Vinee Yi) =0.

The assumption that A, is invertible means that the n by n matrix

2 tt i
Dif + Dif,

evaluated at (a, b) defines an invertible linear operator in R"; in other words,
its column vectors should be independent, or, equivalently, its determinant
should be #0. (See Theorem 9.36.) If, furthermore, (59) holds when X = a and
y = b, then the conclusion of the theorem is that (59) can be solved for x4, ..., x,
in terms of yy, ..., y,,, for every y near b, and that these solutions are continu-
ously differentiable functions of y.

Proof Define F by
(60) Fix,y) =x. 5.9) (x, y)eE)

Then F is a %’-mapping of E into R"*™. We claim that F(a, b) is an
invertible element of L(R"*™):
Since f(a, b) =0, we have

fa+h, b+ k) = Ah, k) + rh, k),
where r is the remainder that occurs in the definition of f(a, b). Since

F(a +h, b+k) - F(a, b) = (f(a +h, b +k), k)
= (A(h, k), k) + (r(h, k), 0)
226 PRINCIPLES OF MATHEMATICAL ANALYSIS

(61)

(62)

(63)

(64)

(65)

it follows that F'(a, b) is the linear operator on R"*™ that maps (h, k) to
(A(h, k), k). If this image vector is 0, then A(h, k) =0 and k = 0, hence
A(h, 0) = 0, and Theorem 9.27 implies that h = 0. It follows that F'(a, b)
is 1-1; hence it is invertible (Theorem 9.5).

The inverse function theorem can therefore be applied to F. It shows
that there exist open sets UU and Vin R"*™, with (a, b) \in  U, (0, b) \in V, such
that F is a 1-1 mapping of U onto V.

We let W be the set of all ye R™ such that (0,y) eV. Note that
be W.

It is clear that Wis open since V is open.

If ye W, then (0, y) = F(x, y) for some (x, y) \in U. By (60),f(x,y) =0
for this x.

Suppose, with the same y, that (x, y)e U and f(x’, y) =0. Then

Fx',y) = (f(x,y), y) = (f(x,y), ¥) = F(x, y).

Since F is 1-1 in U, it follows that x' = x.
This proves the first part of the theorem.

For the second part, define g(y), for y \in W, so that (g(y), y) \in U and
(57) holds. Then

Fe), y)=0,y) (eW)

If G is the mapping of V onto U that inverts F, then G \in 4’, by the inverse
function theorem, and (61) gives

 \in ). 9) =G0,y) (yew)

Since G \in  \in ’, (62) shows that ge 4’.
Finally, to compute g'(b), put (g(y), y) = ©(y). Then

Yk Ek Kk) (EW ker.

By (57), f(®(y)) =0in W. The chain rule shows therefore that

f(a(y)®'(y) =0.
When y = b, then ®(y) = (a, b), and f'(®(y)) = A. Thus

AD'(b) =0.
It now follows from (64), (63), and (54), that
Ag (bk + 4,k = A(g (bk, k) = AD'(b)k = 0

for every k \in R™. Thus

Ag'(b) + 4,=0.
FUNCTIONS OF SEVERAL VARIABLES 227

This is equivalent to (58), and completes the proof.

Note. In terms of the components of f and g, (65) becomes

n

X (Dif). b)(D.g,;)(b) = -(D,+.f)a, b)

j=
5-2)
i=1 \0x;/ \0y Oyx

where l <i<n 1 <k<m.

For each k, this is a system of #» linear equations in which the derivatives
0g;/0y, (1 <j <n) are the unknowns.

or

9.29 Example Take n =2, m =3, and consider the mapping f = (f}, f;) of
R® into R? given by

Six x2 Y1, Y2, Ya) =2 \in " + Xp, -4y, +3

So(X1s X25 Y1s V2, ¥3) = X3  \in 08 x1 - 6x1 +2); - )3.
Ifa=(0, 1)and b = (3, 2, 7), then f(a, b) = 0.

With respect to the standard bases, the matrix of the transformation
A =1'(a,b) is

w-[2 14

w=l2 wef

We see that the column vectors of [4,] are independent. Hence A, is invertible

and the implicit function theorem asserts the existence of a c’-mapping g, defined

in a neighborhood of (3, 2, 7), such that g(3, 2,7) = (0, 1) and f(g(y), y) =0.
We can use (58) to compute g'(3, 2, 7): Since

Hence

1-140" <5 [§ 73]

(58) gives

1 -
[g'G, 2, Nl == 20 6 2

w
| n-
Lure
No
|
[SEEN
|
Flanll =
Il
Le |
|
Nh pe
wo vb
t
+ Se
S-
228 PRINCIPLES OF MATHEMATICAL ANALYSIS

In terms of partial derivatives, the conclusion is that

Dyg, =% D,g, =
Dg, =-}% Dg, =
at the point (3, 2, 7).

THE RANK THEOREM

Although this theorem is not as important as the inverse function theorem or
the implicit function theorem, we include it as another interesting illustration
of the general principle that the local behavior of a continuously differentiable
mapping F near a point x is similar to that of the linear transformation F(x).

Before stating it, we need a few more facts about linear transformations.

9.30 Definitions Suppose X and Y are vector spaces, and A \in L(X, Y), as in
Definition 9.6. The null space of A, A (A), is the set of all x \in X at which Ax = 0.
It is clear that #'(4) is a vector space in X.

Likewise, the range of A, (A), is a vector space in Y.

The rank of A is defined to be the dimension of #(4).

For example, the invertible elements of L(R") are precisely those whose
rank is n. This follows from Theorem 9.5.

If Ae L(X, Y)and A hasrank O, then Ax =Ofor all xe A, hence A (4) = X.
In this connection, see Exercise 25.

9.31 Projections Let X be a vector space. An operator P \in L(X) is said to be
a projection in X if P? =P.

More explicitly, the requirement is that P(Px) = Px for every x \in X. In
other words, P fixes every vector in its range Z(P).

Here are some elementary properties of projections:

(a) If Pis a projection in X, then every x \in X has a unique representation
of the form

X=X; +X;

where x, \in R(P), x, \in /'(P).

To obtain the representation, put x; = Px, Xx, =x - Xx;. Then
Px, = Px - Px, = Px - P>x =0. As regards the uniqueness, apply P to
the equation x =x, + X,. Since X; \in #(P), Px, = X,; since Px, = 0, it
follows that x, = Px.
(b) If X is a finite-dimensional vector space and if X, is a vector space in
X, then there is a projection Pin X with #(P) = X,.

FUNCTIONS OF SEVERAL VARIABLES 229

If X, contains only 0, this is trivial: put Px =0 for all x \in X.
Assume dim X, =k > 0. By Theorem 9.3, X has then a basis
{uy,...,u,} such that {u,, ..., w} is a basis of X,. Define

P(cyuy + + + cu) =cjuy + 0 + cu

for arbitrary scalars cy, ..., c,.
Then Px =x for every x \in X{, and X; = Z(P).
Note that {u, ,,, ..., u,} is a basis of #/(P). Note also that there are

infinitely many projections in X, with range Xi, if 0 < dim X, < dim X.

9.32 Theorem Suppose m, n, r are nonnegatioe integers, m > r, n>r, Fis a
%'-mapping of an open set E c R" into R™, and ¥'(X) has rank r for every x \in E.
Fixae E, put A =F'(a), let Y, be the range of A, and let P be a projection
in R™ whose range is Y,. Let Y, be the null space of P.
Then there are open sets U and V in R", witha e \in  U, U < E, and there is a
1-1  \in '-mapping H of V onto U (whose inverse is also of class  \in ') such that

(66) F(H(x)) = Ax + (4x) (xeV)
where a is a %'-mapping of the open set AV) < Y, into Y,.

After the proof we shall give a more geometric description of the informa-
tion that (66) contains.

Proof If r = 0, Theorem 9.19 shows that F(x) is constant in a neighbor-
hood U of a, and (66) holds trivially, with V = U, H(X) = x, c(0) = F(a).

From now on we assume r >0. Since dim Y; =r, Y; has a basis
{¥1,..., ¥.}. Choosez, \in R"so that Az; =y,;(I <i <r), and define a linear
mapping S of Y; into R" by setting

(67) Sey + +eay)=cz + +z,
for all scalars c,, ...,c,.
Then ASy; = Az; =y; for | <i <r. Thus
(68) ASy=y (vel).

Define a mapping G of E into R" by setting
69) G(x) = x + SP[F(x) - Ax] (xe E).

Since F(a) = A, differentiation of (69) shows that G'(a) = I, the identity
operator on R". By the inverse function theorem, there are open sets UU
and Vin R", with a \in U. such that G is a 1-1 mapping of U onto V whose
inverse His also of class c”. Moreover, by shrinking U and V, if necessary,
we can arrange it so that Vis convex and H'(x) is invertible for every x \in V.
230 PRINCIPLES OF MATHEMATICAL ANALYSIS

(70)

(7)

(72)

3)

(74)

(75)

(76)

(7)

(78)

Note that ASPA = A, since PA =A and (68) holds. Therefore (69)
gives
AG(x) = PF(x) (xe E).
In particular, (70) holds for x \in U. If we replace x by H(x), we obtain
PFH(x)) = Ax  (x£V).
Define
U(x) = FH(x)) - Ax xeV).

Since PA = A, (71) implies that Py(x) =0 for all xe V. Thus c is a
%’-mapping of V into Y,.

Since V is open, it is clear that A(V) is an open subset of its range
RA) =Y,.

To complete the proof, i.e., to go from (72)to (66), we have to show
that there is a  \in ’-mapping c of A(V) into Y, which satisfies

o(Ax) =x) (xe).
As a step toward (73), we will first prove that

P(x) = Y(xz)

if x, eV, x, eV, Ax; = Ax,.
Put ®(x) = F(H(x)), for xe V. Since H'(x) has rank » for every
x \in V, and F'(x) has rank r for every x \in U, it follows that

rank a'(x) = rank F(H(x))H'(x) =r (xe V).
Fix x e V. Let M be the range of (x). Then Mc R™. dim M =r.
By (7),
PO'(x) = A.

Thus P maps M onto #(A4) =Y;. Since M and Y; have the same di-
mension, it follows that P (restricted to M )is I-1.

Suppose now that Ah =0. Then P®'(x)h =0, by (76). But
a’'(x)he M, and Pis I-1 on M. Hence a'(x)h =0. A look at (72) shows
now that we have proved the following:

If xe Vand Ah =0, then Y'(x)h = 0.

We can now prove (74). Suppose x; \in V, x, V. Ax, = Ax,. Put
h =x, - x, and define

g(t) =y(x, + th) O<t<).
The convexity of V shows that x; + the V for these t. Hence
gt) =y' (x; +thh=0 O<t<gl),
FUNCTIONS OF SEVERAL VARIABLES 231

so that g(1) = g(0). But g(1) = ¥(x,) and g(0) = (x). This proves (74).
By (74), y(x) depends only on Ax, for x \in V. Hence (73) defines c
unambiguously in A(V). It only remains to be proved that c \in  \in ".
Fix yo \in A(V), fix xq \in V so that Ax, =Y,. Since V is open, Yo has
a neighborhood Win Yj such that the vector

79 X =Xq + SY - Yo)
lies in V for all y e W. By (68),
AX =AXg +Y-Yo=YV.
Thus (73) and (79) give
(80) Py) =¥(xo - Sy, + 8y) (ye W).

This formula shows that c \in  \in ’ in W, hence in A(V), since y, was chosen
arbitrarily in A(V).
The proof is now complete.

Here is what the theorem tells us about the geometry of the mapping F.
If y e F(U) then y = F(H(x)) for some x \in V, and (66) shows that Py = Ax.
Therefore

an y=Py+o(Py) (yeFU).

This shows that y is determined by its projection Py, and that P, restricted
to F(U), is a 1-1 mapping of F(U) onto A(V). Thus F(U) is an "r-dimensional
surface" with precisely one point "over" each point of A(V). We may also
regard F(U) as the graph of c.

If ®(x) = F(H(x)), as in the proof, then (66) shows that the level sets of ®
(these are the sets on which ® attains a given value) are precisely the level sets of
A in V. These are "flat" since they are intersections with V of translates of the
vector space A°(4). Note that dim A"(4) =n - r (Exercise 25).

The level sets of F in U are the images under H of the flat level sets of ®
in V. They are thus '"(n - r)-dimensional surfaces" in U.

DETERMINANTS

Determinants are numbers associated to square matrices, and hence to the
operators represented by such matrices. They are O if and only if the corre-
sponding operator fails to be invertible. They can therefore be used to decide
whether the hypotheses of some of the preceding theorems are satisfied. They
will play an even more important role in Chap. 10.
232 PRINCIPLES OF MATHEMATICAL ANALYSIS

9.33 Definition If (jy, ...,J,) is an ordered n-tuple of integers, define

(82) (is «5 Ju) = [1 s8n Gy = Jp),

p<q
where sgn x =1 if x>0, sgn x=-1 if x<0, sgn x =0 if x =0. Then
$s(ji,.-»j) =1, -1, or 0, and it changes sign if any two of the j's are inter-
changed.

Let [A Jbe the matrix of a linear operator A on R", relative to the standard
basis {ey, ..., e,}, with entries a(i, j)in the ith row and jth column. The deter-
minant of [A ]is defined to be the number
(83) det [4] = ¥ 5G» + Jal, j)a(2. ja) + a(n, jy).

The sum in (83)extends over all ordered n-tuples of integers (j,, ...,j,) with
1<j, <n

The column vectors X; of [A ]are

(84) X; = 2 ai.)e; (1<j<n)
“=
It will be convenient to think of det [A ]as a function of the column vectors
of [A]. If we write
det (Xq,..., x) =det [A],

det is now a real function on the set of all ordered n-tuples of vectors in R".

9.34 Theorem

(a) If I is the identity operator on R", then
det [I]=det (e,...,e,) = 1.

(b) det is a linear function of each of the column vectors X;, if the others are
held fixed.

(c) If [A], is obtained from [A] by interchanging two columns, then
det [A],= -det [A].

(d) If [A]has two equal columns, then det [A ]= 0.

Proof If A =1, then a(i,i) = | and a(i,j) = 0 for i # j. Hence
det [IT]=s(1,2,...,n)=1,

which proves (a). By (82), (jy, ...,J,) = 0 if any two of the ’s are equal.
Each of the remaining n!/ products in (83) contains exactly one factor
from each column. This proves (b). Part (c)is an immediate consequence
of the fact that s(jy, ...,j,) changes sign if any two of the j's are inter-
changed, and (d)is a corollary of (c).
9.35

(83)

(86)

(87)

(88)

(89)

9.36

(90)

FUNCTIONS OF SEVERAL VARIABLES 233

Theorem If [A Jand [B Jare n by n matrices, then
det ([B|[4]) = det [B]det [A].
Proof If x,, ..., x, are the columns of [A | define
Ag(Xy,..., X,) = AplA] = det ([BI[4]).
The columns of [B][A] are the vectors Bx,, ..., Bx,. Thus
Ap(xy,...,X,) =det(BXy,..., Bx,).

By (86) and Theorem 9.34, A, also has properties 9.34 (b)to (d). By (b)
and (84),

AglA] = Ag (2 a(i, Deir Xa, ...u%,) - X ati 1) Age; Xz, ....X,).

Repeating this process with x, ..., x,, we obtain
Agld] = y a(iy, Da(iy, 2) -- a(i,, n) Age, Sees e;),

the sum being extended over all ordered n-tuples (i, ..., #,) with
1 <i. <n. By(c)and (d),

Age, ....e,) =t(iy.....0,) Agley, ...,e,),
where t = 1.0, or - I, and since [B][/] = [B](85)shows that
Agley, ....e,) =det [B].
Substituting (89)and (88) into (87), we obtain
det ([BIl4]) = {} a(iy, 1)... a(i,, n)t(iy...., i,)} det [B],
for all # by #» matrices [A Jand [B]. Taking B =1. we see that the above
sum in braces is det [A J. This proves the theorem.
Theorem A linear operator A on R" is invertible ¥ and only if det [A J# 0.
Proof If A is invertible. Theorem 9.35 shows that
det [AJdet [A] =det [AA] =det [I]=1,
so that det [A J# O.

If A is not invertible, the columns x,, ..., X, of [A Jare dependent
(Theorem 9.5); hence there is one, say, X, , such that

Xo +) cx; =0
J#k

for certain scalars c;. By 9.34 (b)and (d),X, can be replaced by x; + c;X;
without altering the determinant, if j # k. Repeating, we see that X; can
234 PRINCIPLES OF MATHEMATICAL ANALYSIS

be replaced by the left side of (90), i.e., by 0, without altering the deter-
minant. But a matrix which has 0 for one column has determinant O.
Hence det [A ]=0.

9.37 Remark Suppose {e,,...,e,} and {uy,...,u,} are bases in R".
Every linear operator A on R" determines matrices [A Jand [A],, with entries
a;; and a;;, given by

Ae; =} ae, Au; = au;
If u; = Be; = Ib;;e;, then Au; is equal to
)) oy; Bey = ) Ay j ) bye; = ) z bux)  \in ;,
and also to

ABe; = A 2 bie =3 (Z abi) e;.

Thus Xb; 0; = Za, by;, or
on [Bll4]y = [4][B].
Since B is invertible, det [B J#0. Hence (91), combined with Theorem 9.35,
shows that
92) det [A]y =det [A].
The determinant of the matrix of a linear operator does therefore not

depend on the basis which is used to construct the matrix. It is thus meaningful
to speak of the determinant of a linear operator, without having any basis in mind.

9.38 Jacobians 1ff maps an open set E = R"into R", and iff is differen-
tiable at a point x \in E, the determinant of the linear operator f'(x) is called
the Jacobian o ffat x. In symbols,

93) Je(x) =det f(x).
We shall also use the notation

Oyys eves Vu)
(X15 ons Xp)

for Je(X), if (Vyy oes Yu) = [(X,, «ves Xp).

In terms of Jacobians, the crucial hypothesis in the inverse function
theorem is that Jg(a) #0 (compare Theorem 9.36). If the implicit function
theorem is stated in terms of the functions (59), the assumption made there on
A amounts to

e)

of1s os fo)

- 7 £0.
Horm m)
FUNCTIONS OF SEVERAL VARIABLES 235

DERIVATIVES OF HIGHER ORDER

9.39 Definition Suppose f is a real function defined in an open set E c R",

with partial derivatives D,f,..., D,f. If the functions Dif are themselves

differentiable, then the second-order partial derivatives off are defined by
D;f=D;D;f (j=1,...,n)

If all these functions D;;f are continuous in E, we say that f is of class c" in E,

or that fe  \in "(E).

A mapping f of E into R™ is said to be of class c" if each component off
is of class  \in ".

It can happen that D;;f # Dj; f at some point, although both derivatives
exist (see Exercise 27). However, we shall see below that D;;f = D;;f whenever
these derivatives are continuous.

For simplicity (and without loss of generality) we state our next two
theorems for real functions of two variables. The first one is a mean value
theorem.

9.40 Theorem Suppose f is defined in an open set E c R?, and D,f and D,,f
exist at every point of E. Suppose Q c E is a closed rectangle with sides parallel
to the coordinate axes, having (a,b) and (a+h,b=+k) as opposite vertices
(h#0, k #0). Put

Af, Q) =fla+hb+k)-fla+ hb) -flab+k) +f(ab).

Then there is a point (x,y) in the interior of Q such that

95) Af, Q) = hk(Dy, f)(x, »).
Note the analogy between (95) and Theorem 5.10; the area of Q is hk.

Proof Putu(t)=f(t,b+ k)- f(t,b). Two applications of Theorem 5.10
show that there is an x between a and a + h, and that there is a y between
b and b+ k, such that

ACS, Q) = ula + h) - u(a)
= hu'(x)
=h[(D1f)(x, b + k) - (D1 f)(x, b)]
= hk(D3,f)(%, ¥)-
9.41 Theorem Suppose f is dejined in an open set E c R?, suppose that Df,

D,,f, and D,f exist at every point of E, and D,,f is continuous at some point
(a,b) \in E.
236 PRINCIPLES OF MATHEMATICAL ANALYSIS

(96)

Then Dy, f exists at (a,b) and
(D12f)a, b) = (Dy, f) a, b).

Corollary Dp, f= D,,fif fe 6"(E).

7

Proof Put A =(D,f)(a,b). Choose c>0. If Q is a rectangle as in
Theorem 9.40, and if h and k are sufficiently small, we have

[A - (Dy, fx, p)| <e
for all (x,y) \in Q. Thus

by (95). Fix h, and let k = 0. Since D,f exists in E, the last inequality

implies that

(D2f)a + h, b) - (D,f)(a. b)
h

Since & was arbitrary, and since (97) holds for all sufficiently small
h #0, it follows that (Dy, f)(a, b) = A. This gives (96).

Al<e

DIFFERENTIATION OF INTEGRALS

Suppose c is a function of two variables which can be integrated with respect
to one and which can be differentiated with respect to the other. Under what
conditions will the result be the same if these two limit processes are carried out
in the opposite order? To state the question more precisely: Under what
conditions on c can one prove that the equation

98)

dt el
7 [ ot, t)ydx = I a (x,t) dx

is true? (A counter example is furnished by Exercise 28.)

(99)

It will be convenient to use the notation

c'(x) = p(x, 1).

Thus c' is. for each c, a function of one variable.

9.42 Theorem Suppose

(a) (x, t)is definedforal x I b,c<t<d;
(b) «is an increasing function on [a,b];
FUNCTIONS OF SEVERAL VARIABLES 237

(c) ©' \in  Ra) for every te [cd];
(d) c<s<d, and to every c > 0 corresponds a 6 > 0 such that

[(D2g)x, t) - (Dy Xx, 5) <e
Jor all xe [a,b ]and for all tes - 6,5 +6).

Dejine
b
(100) FO = [ox 1)dux)  (c<r<d),

Then (D, a) \in A(x), f'(s)exists, and
b
(101) f(s) = | (D; o)(x, 5) d(x).

Note that (c) simply asserts the existence of the integrals (100) for all
t \in  [c,d]. Note also that (d )certainly holds whenever D, c is continuous on the
rectangle on which c is defined.

Proof Consider the difference quotients

w(x, 1) - o(x, 1) - o(x, s)
t-5

for 0< |t - 5] <6. By Theorem 5.10 there corresponds to each (x,c) a
number u between s and c such that

U(x. 1) = (Dy )(x, u).
Hence (d)implies that
(102) W(x. 1) = (Dy 9x. 5) <e  (asxs<b, 0<|t-s]<6).
Note that

FOSS _ yt) do),

t- 5 Ya

(103)

By (102), ¥'-=(D, c)’, uniformly on [a,b], as t-s. Since each
W'e A(x), the desired conclusion follows from (103) and Theorem 7.16.

9.43 Example One can of course prove analogues of Theorem 9.42 with
(-o00, 0) in place of [a,b]. Instead of doing this, let us simply look at an
example. Define

(104) fi) = [ e”** cos (xt) dx

Y-m
238 PRINCIPLES OF MATHEMATICAL ANALYSIS

and
m

(105) g(t) = - [ xe™* sin (xt) dx,

for -u0 < t< oo. Both integrals exist (they converge absolutely) since the
absolute values of the integrands are at most exp (- x?) and |x| exp (-x?),
respectively.

Note that g is obtained fromf by differentiating the integrand with respect
to t. We claim thatf is differentiable and that

(106) f(0)=gt) (=o <t< 0).

To prove this, let us first examine the difference quotients of the cosine:
if #>0, then
cos (x+ ff) - cosa | . JEL .
cosaHp) cosa oy == ) (sin 2 - sin t) dt.
p Ba
Since |sin x - sin t| < |# - «|, the right side of (107) is at most $/2 in absolute
value; the case § <0 is handled similarly. Thus

(107)

cos (2 + ff) - cos a
B

for all f (if the left side is interpreted to be 0 when ff = 0).
Now fix t, and fix # #0. Apply (108) with « = xt, f = xh; it follows from
(104) and (105) that

Si +h) =f)
h

(108) + sina

< [Al

- g(t)

< |h f x2e™* dx.
When h - 0, we thus obtain (106).
Let us go a step further: An integration by parts. applied to (104), shows
that
r® _ 2 Sin (xt) dx.

(109) f(t) = 2] xe ;

Thus #f(t) = - 2c(t), and (106) implies now that f satisfies the differential
equation

(110) X(t) + tf (1) =0.

If we solve this differential equation and use the fact that f(0) = NE (see Sec.
8.21), we find that

. 2
(111) fo =vrew (= 4)

The integral (104) is thus explicitly determined.
FUNCTIONS OF SEVERAL VARIABLES 239

EXERCISES

1.

10.

11.

12.

If .S is a nonempty subset of a vector space X, prove (as asserted in Sec. 9.1) that
the span of Sis a vector space.

. Prove (as asserted in Sec. 9.6) that BA is linear if A and Bare linear transformations.

Prove also that A-? is linear and invertible.

. Assume A \in L(X, Y) and Ax = 0 only when x = 0. Prove that A is then 1-1.

. Prove (as asserted in Sec. 9.30) that null spaces and ranges of linear transforma-

tions are vector spaces.

. Prove that to every A \in L(R", R') corresponds a unique y \in R" such that Ax =X .y.

Prove also that A |= ly].
Hint: Under certain conditions, equality holds in the Schwarz inequality.

. If f(0,0)=0 and

Xy

Mit if (x, y) # (0, 0),

fx, 3) =

prove that (D, f)(x,y) and (D.f)(x, y) exist at every point of R% although f is
not continuous at (0, 0).

. Suppose that fis a real-valued function defined in an open set E < R", and that

the partial derivatives Df, ..., D,f are bounded in E. Prove thatfis continuous
in E.
Hint: Proceed as in the proof of Theorem 9.21.

. Suppose that f is a differentiable real function in an open set E < R", and that f

has a local maximum at a point x \in E. Prove that f(x) = 0.

. If f is a differentiable mapping of a connected open set E< R" into R", and if

f’(x) = 0 for every x \in E, prove that f is constant in E.

[ff is a real function defined in a convex open set E = R", such that (D, f)}(x)=0
for every x \in E, prove that f(x) depends only on Xz, ..., X,,.

Show that the convexity of E can be replaced by a weaker condition, but
that some condition is required. For example, if # -2 and E is shaped like a
horseshoe, the statement may be false.

Iff and g are differentiable real functions in R", prove that
VU) =fYg+9%f
and that T(1If) = - f= 2Vf wherever f +0.
Fix two real numbers a and b, 0 <a <b. Define a mapping f = (fi, f2, f3) of R?
into R* by
fi(s,t)==(b+acoss)cost
S2(s,1) = (b+ acoss)sint

f3(s,t) = asin s.
240 PRINCIPLES OF MATHEMATICAL ANALYSIS

13.

14.

15.

Describe the range K of f. (It is a certain compact subset of R*.)
(a) Show that there are exactly 4 points p \in K such that

(VE (p)) =0.

Find these points.
(b) Determine the set of all q \in Ksuch that

(Vf) (a) =0.

(c) Show that one of the points p found in part (a) corresponds to a local maxi-
mum off,, one corresponds to a local minimum, and that the other two are
neither (they are so-called "saddle points").

Which of the points q found in part (h) correspond to maxima or minima?
(d) Let h be an irrational real number, and define g(t) = f(z, At). Prove that g is a
1-1 mapping of R' onto a dense subset of K. Prove that

|g'(r)|* = a> + h*(b + a cos 1),
Suppose f is a differentiable mapping of R' into R? such that |f(1)| = 1 for every t.

Prove that f'(z) -f() = 0.
Interpret this result geometrically.

Define £(0, 0) = 0 and
x? .
fx, y) = pr if (x, y) # (0, 0).

(a) Prove that D;jand Df are bounded functions in R?. (Hence f is continuous.)
(b) Let u be any unit vector in R*>. Show that the directional derivative (D, f)(0, 0)
exists, and that its absolute value is at most 1.
(c) Let vv be a differentiable mapping of R' into R? (in other words, y is a differ-
entiable curve in R?), with (0) =(0, 0) and y’(0)|> 0. Put g(r) = f((c)) and
prove that g is differentiable for every t \in R*.

If y \in 6’, prove that g \in  \in ".
(d) In spite of this, prove that f is not differentiable at (0, 0).

Hint: Formula (40) fails.

Define £(0, 0) = 0, and put

4x5)?
(x* + y?)?

fx, y) =x? 4+ y* - 2x2
if (x,y) # (0, 0).
(a) Prove, for all (x,y) \in R?, that
4xty? <(x* + y?)2.

Conclude that f is continuous.
16.

17.

18.

19.

20.

21.

FUNCTIONS OF SEVERAL VARIABLES 241

(b) For 0 <0 < 2m, - 0 <t< ow, define
go(t) = f(t cos 6, t sin 6).

Show that ge(0) = 0, go(0) = 0, g,(0) = 2. Each ge has therefore a strict local
minimum at 7 = 0.

In other words, the restriction of f to each line through (0, 0) has a strict
local minimum at (0, 0).
(c) Show that (0, 0) is nevertheless not a local minimum for f] since f(x, x?) = -x*.
Show that the continuity of f” at the point a is needed in the inverse function
theorem, even in the case n = 1: If

f(r) =1t+ 2*sin (3)

for + #0, and f(0) = 0, then f’(0) = 1, f’ is bounded in (-1, 1), but f is not
one-to-one in any neighborhood of 0.
Let f == (/, /2) be the mapping of R? into R?* given by

fi(x,y) =e*cos y, fax, y) =e sin y.
(a) What is the range of f?
(b) Show that the Jacobian of fis not zero at any point of R2. Thus every point
of R? has a neighborhood in which fis one-to-one. Nevertheless, f is not one-to-
one on R2%,
(c) Put a = (0, 7/3), b= f(a), let g be the continuous inverse of f, defined in a
neighborhood of b, such that g(b) =a. Find an explicit formula for g, compute
f'(a) and g’(b), and verify the formula (52).
(d) What are the images under f of lines parallel to the coordinate axes?
Answer analogous questions for the mapping defined by

u=x*-y? v=2xy.

Show that the system of equations

Ix+y-z+ur=0

x-=y+2z+u=0

2x +2y -3z42u=0
can be solved for x, y, « in terms of z; for x, z, u in terms of y; for y, z, u in terms
of x; but not for x, y, z in terms of u.
Take n= m= 1 in the implicit function theorem, and interpret the theorem (as
well as its proof) graphically.
Define fin R? by
S(x,y) =2x% = 3x* 4 2p° + 32.

(a) Find the four points in R? at which the gradient of fis zero. Show that f has
exactly one local maximum and one local minimum in R2.
242 PRINCIPLES OF MATHEMATICAL ANALYSIS

22.

23.

24.

25.

26.

27.

28.

(b) Let S be the set of all (x, y) \in R? at which f(x,y) =0. Find those points of
S that have no neighborhoods in which the equation f(x, y) = 0 can be solved for
y in terms of x (or for X in terms of y). Describe S as precisely as you can.
Give a similar discussion for

f(x,y) = 2x3 + 6xy? = 3x2 + 3y>.
Define f in R* by
SOG, py) =x + e¥ + ys.
Show that f(0,1, -1) =0,(Df)(0,1, -1) #0, and that there exists therefore a

differentiable function g in some neighborhood of (1, -1) in R?, such that
g(1, -1)=0 and

f(g, 2), y1, 2) = 0.

Find (D1g)(1, -1) and (D29)(1, = 1).
For (x,y) # (0,0), define f - (f1,/2) by
x2 -y? xy

Hx = 705 Six =570
Compute the rank of f(x,y), and find the range off.
Suppose A \in L(R", R™), let r be the rank of A.
(a) Define S as in the proof of Theorem 9.32. Show that SA is a projection in R"
whose null space is A (4) and whose range is #(S). Hint: By (68), SASA = SA.
(b) Use (a) to show that

dim A(A) + dim #(A) = n.

Show that the existence (and even the continuity) of D,.f does not imply the
existence of Dy f. For example, let f(x, y) = g(x), whereg is nowhere differentiable.
Put £(0, 0) = 0, and
xy -y?)

fx, y)= XT
if (x,y) # (0,0). Prove that
(a) f, Dif, Df are continuous in R?;
(b) D,.f and D,,f exist at every point of R?, and are continuous except at (0, 0);

(©) (D12/)0,0) = 1, and (D2.0f)0,0) = -1.

For t >=0, put
x B O<x<Vi) ~
px, )={-x+2Vr (Vi<x<2Vi)
0 (otherwise),

and put a(x,r) = - (x, |#]) if + <O.
29.

30.

FUNCTIONS OF SEVERAL VARIABLES 243

Show that c is continuous on R?, and
(D29)(x,0) = 0

for all x. Define

f= gtx nx

Show that f(t) = t if |] <}. Hence
SO #[" (Dig)x, 0) dx.

Let E be an open set in R", The classes  \in ’(E) and  \in ”(E) are defined in the text.
By induction, ¥¥(E) can be defined as follows, for all positive integers k: To say
that f \in  \in '¥(E) means that the partial derivatives D, f, ..., D.f belong to  \in “ =X E).

Assume f \in a“(E). and show (by repeated application of Theorem 9.41)
that the kth-order derivative

Dyyiy oe nf= DD, "ee Dif

is unchanged if the subscripts /y, ..., Ix are permuted.
For instance, if # > 3, then

Dyz13f= Dain f
for every f \in §“.

Let f \in c™(E), where E is an open subset of R". Fix a \in E, and suppose x \in R"
is so close to 0 that the points

p(t) =a-+ tx
lie in E whenever 0 <t <1. Define
h(t) = f(p(t))

for all c \in R* for which p(t) \in E.
(a) For 1 <<k <<m, show (by repeated application of the chain rule) that

AOE) = (Diy ot, HPO) Xi, ex.

The sum extends over all ordered k-tuples (iy, ..., i) in which each i; is one of the
integers 1, ..., n.
(b) By Taylor's theorem (5.15),

m=1 HD 0 hm t
h(1) = py : ) al )

for some f (0, 1). Use this to prove Taylor's theorem in n variables by showing

that the formula
244 PRINCIPLES OF MATHEMATICAL ANALYSIS

31.

m-1

fa+x=% EE Disa) xr)

represents f(a + x) as the sum of its so-called "Taylor polynomial of degree
m - 1,” plus a remainder that satisfies

Each of the inner sums extends over all ordered k-tuples (ii, ...,#), as in
part (a);as usual, the zero-order derivative off is simply f, so that the constant
term of the Taylor polynomial off at a is f(a).

(c) Exercise 29 shows that repetition occurs in the Taylor polynomial as written in
part (b). For instance, Dy,3 occurs three times, as Dyy3, D131, D311. The sum of
the corresponding three terms can be written in the form

3(Di Dsf)a)xi xs.

Prove (by calculating how often each derivative occurs) that the Taylor polynomial
in (b) can be written in the form

(DY... Da" f)(a)

x.
s,! oS!

3 xt B
Here the summation extends over all ordered n-tuples (sy, ..., S.) such that each
si is a nonnegative integer, and 5, +... +5, <m - 1.

Suppose £  \in %® in some neighborhood of a point a \in R?, the gradient off is 0
at a, but not all second-order derivatives off are 0 at a. Show how one can then
determine from the Taylor polynomial off at a (of degree 2) whether f has a local
maximum, or a local minimum, or neither, at the point a.

Extend this to R" in place of R2.
10

INTEGRATION OF DIFFERENTIAL FORMS

Integration can be studied on many levels. In Chap. 6, the theory was developed
for reasonably well-behaved functions on subintervals of the real line. In
Chap. 11 we shall encounter a very highly developed theory of integration that
can be applied to much larger classes of functions, whose domains are more
or less arbitrary sets, not necessarily subsets of R". The present chapter is
devoted to those aspects of integration theory that are closely related to the
geometry of euclidean spaces, such as the change of variables formula, line
integrals, and the machinery of differential forms that is used in the statement
and proof of the n-dimensional analogue of the fundamental theorem of calculus,
namely Stokes’ theorem.

INTEGRATION

10.1 Definition Suppose I*is a k-cell in R¥, consisting of all

X= (xg, ...,X)
such that
0) a, <x; <b; (i=1,...,k),
246 PRINCIPLES OF MATHEMATICAL ANALYSIS

I is the jcell in R’ defined by the first j inequalities (1), and f is a real con-
tinuous function on I*.
Put f = f;, and define f,_, on I*"! by

bi
Seer xe) = [Ars een Xion, x0) dx.

The uniform continuity of f, on I* shows that f,_, is continuous on I¥7!,
Hence we can repeat this process and obtain functions f;, continuous on I, such
that f;_, is the integral of f;, with respect to x;, over [a;, b;]. After k steps we
arrive at a number f,, which we call the integral of f over I*; we write it in the
form

©) I fx)dx or [7

A priori, this definition of the integral depends on the order in which the
k integrations are carried out. However, this dependence is only apparent. To
prove this, let us introduce the temporary notation L(f) for the integral (2)
and L'(f) for the result obtained by carrying out the k integrations in some
other order.

10.2 Theorem For every fe  \in (I¥), L(f) = L'(f).
Proof If i(x) = hy(x,) *- I(x), where /; \in 6([a;, b)]), then

Lh) = nr h(x) dx; = L'(h).

If «7 is the set of all finite sums of such functions #4, it follows that L(g) =
L'(g) for all g \in o. Also, &f is an algebra of functions on I* to which the
Stone-Weierstrass theorem applies.

k
Put V =] (b; - a). If fe  \in (I") and & > 0, there exists g \in & such
1

that [If - g| < &/V, where |f| is defined as max |f(x)| (x \in I¥). Then
|L(f-9)| <e& |[L'(f-g)| <e, and since

LN -LN=LS=-g9+L(g~-1),

we conclude that |L(f) - L'(f)| <2e.
In this connection, Exercise 2 is relevant.

10.3 Definition The support of a (real or complex) function f on R* is the
closure of the set of all points x \in R* at which f(x) #0. If fis a continuous
INTEGRATION OF DIFFERENTIAL FORMS 247

function with compact support, let I* be any k-cell which contains the support
of f, and define

3) [f= LS

The integral so defined is evidently independent of the choice of I*, provided
only that I* contains the support of f.

It is now tempting to extend the definition of the integral over R* to
functions which are limits (in some sense) of continuous functions with compact
support. We do not want to discuss the conditions under which this can be
done; the proper setting for this question is the Lebesgue integral. We shall
merely describe one very simple example which will be used in the proof of
Stokes’ theorem.

10.4 Example Let Q* be the k-simplex which consists of all points x =
(x45... x) in R* for which x; + ** + x, <1 and x; 20 foi i=1, ..., k. If
k = 3, for example, Q is a tetrahedron, with vertices at 0, e,, e, , 5. If fe (0%),
extend f to a function on I* by setting f(x) = 0 off Q*, and define

a [.r=].r
Here I* is the “unit cube” defined by
0<x;<1 (I1<i<k).
Since / may be discontinuous on I*, the existence of the integral on the
right of (4) needs proof. We also wish to show that this integral is independent

of the order in which the k single integrations are carried out.
To do this, suppose 0 < é < 1, put

1 (t<1-9)
(5) ot = = (I-d<t<)
0 (1<0p),
and define
6) FO) =o(x, + + x)f(x)  (xel",

Then Fe 6(1%).

Put y = (xy, ..., Xk-1), X= (y, x). For each ye I*"!, the set of all x,
such that F(y, x3) # f(y; X;) is either empty or is a segment whose length does
not exceed d. Since 0 < c < 1, it follows that

(N | Fier) = fie <0IfI (yel*™),
248 PRINCIPLES OF MATHEMATICAL ANALYSIS

where | f]|| has the same meaning as in the proof of Theorem 10.2, and F;_,,
fx-1 are as in Definition 10.1.
As 6 - 0, (7) exhibits f,_; as a uniform limit of a sequence of continuous
functions. Thus f,_, \in  \in (I*""), and the further integrations present no problem.
This proves the existence of the integral (4). Moreover, (7) shows that

(8) | [Foo dx - I F(x) dx| <5|f].

Note that (8) is true, regardless of the order in which the k single integrations
are carried out. Since Fe %(I*), [F is unaffected by any change in this order.
Hence (8) shows that the same is true of [f.

This completes the proof.

Our next goal is the change of variables formula stated in Theorem 10.9.
To facilitate its proof, we first discuss so-called primitive mappings, and parti-
tions of unity. Primitive mappings will enable us to get a clearer picture of the
local action of a ¥’-mapping with invertible derivative, and partitions of unity
are a very useful device that makes it possible to use local information in a
global setting.

PRIMITIVE MAPPINGS

10.5 Definition If G maps an open set Ec R" into R", and if there is an
integer m and a real function g with domain E such that

® G(x) =) x;e; +g(X)e, (xeE),
itm
then we call G primitive. A primitive mapping is thus one that changes at most
one coordinate. Note that (9) can also be written in the form
(10) G(x) =x + [g(x) - x, ley.

If g is differentiable at some point a \in E, so is G. The matrix [o;;] of the
operator G'(a) has

an (D1g)a), ..., (Dp g)a), ..., (Dn g)a)

as its mth row. For j # m, we have «;; = 1 and a;; =0 if i # j. The Jacobian
of G at a is thus given by

(12) Jo(a) = det[G'(a)] = (D,, 9)(a),
and we see (by Theorem 9.36) that G'(a) is invertible if and only if (D,, g)(a) # 0.
INTEGRATION OF DIFFERENTIAL FORMS 249

10.6 Definition A linear operator B on R" that interchanges some pair of
members of the standard basis and leaves the others fixed will be called a flip.
For example, the flip B on R* that interchanges e, and e, has the form

(13) B(xye; + xye; + x33 + xe) = X11 + Xp \in , + X3 \in 3 + X48;
or, equivalently,
(14) B(x;e; + xe, + x3e3 + x,e,) =x, \in  + Xx,8;, + x383+ x5 \in ,.

Hence B can also be thought of as interchanging two of the coordinates, rather
than two basis vectors.

In the proof that follows, we shall use the projections Py, ..., P, in R",
defined by Py x = 0 and

(15) P,x=xe + + x,e,

for | <m <n. Thus P, is the projection whose range and null space are
spanned by {e,, ..., e,} and {e,., ..., e,}, respectively.

10.7 Theorem Suppose F is a  \in '-mapping of an open set E = R" into R", 0 \in E,
F(0) = 0, and F'(0) is invertible.
Then there is a neighborhood of 0 in R" in which a representation

(16) F(x) =B,* B,_;G, 2" = G(x)

is valid.
In (16), each G; is a primitive %'-mapping in some neighborhood of 0;
G,(0) = 0, G|(0) is invertible, and each B, is either a flip or the identity operator.

Briefly, (16) represents F locally as a composition of primitive mappings
and flips.

Proof Put F=F,. Assume 1 <m<n-1, and make the following
induction hypothesis (which evidently holds for m = 1):
V,, is a neighborhood of 0, F,, \in  \in '(V,,) ,F,.(0) = 0, F, (0) is invertible,

and
17) Pp iF, (x)=P,_ 1x (x \in V,).
By (17), we have
(18) F(x) = Po X + aXe,
where a,,, ..., «, are real c’-functions in V,,. Hence

(19) FiO), = 3 (D,x)0);.
250 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since F,,(0) is invertible, the left side of (19) is not 0, and therefore there
is a k such that m < k <n and (D,, ,)(0) # 0.

Let B,, be the flip that interchanges m and this k (if k = m, B,, is the
identity) and define

(20) G(x) =x + [ox(X) - Xplem (xevV,).

Then G,, e¥c'(V,), G,, is primitive, and G0) is invertible, since
(Dn 24)(0) #0.

The inverse function theorem shows therefore that there is an open
set U,,, with 0 U,, = V,,, such that G,, is a 1-1 mapping of U,, onto a
neighborhood V,,,, of 0, in which G,' is continuously differentiable.
Define F,,,, by

an Foi) =B,F,cG'(y) (YE Vins)

Then FF, \in 4’ (Vist), Fuie:1(0)=0, and F, (0) is invertible (by
the chain rule). Also, for xe U,,

(22) P,F, (G(x) =P,B,F,(x)
= P,[P,_ x + a(x)e, + ]
=P, 1x + a (x)e,
=P, G(x)
so that
23) PF) =Py (YE Vins).

Our induction hypothesis holds therefore with m + 1 in place of m.

[In (22), we first used (21), then (18) and the definition of B,,, then
the definition of P,,, and finally (20).]

Since B,, B,, = 1, (21), with y = G,,(x), is equivalent to

(24) F(x) = BF, (G(x) (xe U,).
If we apply this with m = 1, ..., n - 1, we successively obtain
F=F, = BF, G,
=BB,F3:G,0cG,="""
=B, BF, eG, yo 2G

in some neighborhood of 0. By (17), F, is primitive. This completes the
proof.
INTEGRATION OF DIFFERENTIAL FORMS 251

PARTITIONS OF UNITY
10.8 Theorem Suppose K is a compact subset of R", and {V,} is an open cover
of K. Then there exist functions yy, ..., ys \in  \in (R") such that

(a) 0<y,<1for1<i<s;

(b) each \; has its support in some V,, and

© Y(x)+ + + yx) =1 for every xe K.

Because of (c), {y/;} is called a partition of unity, and (b) is sometimes
expressed by saying that {;} is subordinate to the cover {V,}.

Corollary If fe  \in (R") and the support of f lies in K, then

25) f= Lu.
Each yf has its support in some V,.

The point of (25) is that it furnishes a representation of f as a sum of
continuous functions yf with ‘small’ supports.

Proof Associate with each x \in K an index a(x) so that x \in V,,. Thea
there are open balls B(x) and W(x), centered at x, with

(26) B(X) © W(X) = W(X) & Vag -
Since K is compact, there are points Xj, ..., X, in K such that
27 Kc B(x) vu B(x).

By (26), there are functions c,, ..., c, \in  ¥(R"), such that c(x)=1 on
B(x;), (x) = 0 outside W(x;), and 0 < c;(x) <1 on R". Define y, = c,

and
(28) Visi = =) (1 = 0)9i+,
fori=1,...,5s-1.
Properties (a) and (b) are clear. The relation
29) it A= 1= (=) (1-9)

is trivial for / = 1. If (29) holds for some i < s, addition of (28) and (29)
yields (29) with i + 1 in place of i. It follows that

5

(0) bh Yix)=1- IT [1 - ix] (x \in R™).

i=1 i=1

If xe K, then x \in B(x;) for some /, hence c,(x) = 1, and the product in
(30) is 0. This proves (c).
252 PRINCIPLES OF MATHEMATICAL ANALYSIS

CHANGE OF VARIABLES

We can now describe the effect of a change of variables on a multiple integral.
For simplicity, we confine ourselves here to continuous functions with compact
support, although this is too restrictive for many applications. This is illustrated
by Exercises 9 to 13.

10.9 Theorem Suppose T is a 1-1  \in '-mapping of an open set E - R* into R*
such that Jx(x) # 0 for all x \in E. If fis a continuous function on R* whose support
is compact and lies in T(E), then

an [ J0dy=] FT)IH00)] dx.

We recall that J; is the Jacobian of 7. The assumption J;(x) # 0 implies,
by the inverse function theorem, that 7”! is continuous on T(E), and this
ensures that the integrand on the right of (31) has compact support in E
(Theorem 4.14).

The appearance of the absolute value of J(x) in (31) may call for a com-
ment. Take the case k = 1, and suppose T is a 1-1 ¥’-mepping of R' onto R'.
Then Jy(x) = T'(x); and if T is increasing, we have

(32) [Jody = | ATT dx

by Theorems 6.19 and 6.17, for all continuous f with compact support. But if
T decreases, then T'(x) <0; and if f is positive in the interior of its support,
the left side of (32) is positive and the right side is negative. A correct equation
is obtained if 7’ is replaced by |T'| in (32).

The point is that the integrals we are now considering are integrals of
functions over subsets of R¥, and we associate no direction or orientation with
these subsets. We shall adopt a different point of view when we come to inte-
gration of differential forms over surfaces.

Proof It follows from the remarks just made that (31) is true if Tis a
primitive %’-mapping (see Definition 10.5), and Theorem 10.2 shows
that (31) is true if 7 is a linear mapping which merely interchanges two
coordinates.

If the theorem is true for transformations P, Q, and if S(x) = P(Q(x)),
then

[1a dz = [ fP)ITs| dy
= [FPN THQ] [7g] dx

= | S(S00) [sx] dx,
INTEGRATION OF DIFFERENTIAL FORMS 253

since
Jp(Q(x)) g(x) = det P'(Q(x)) det Q'(x)
= det P'(Q(x))Q'(x) = det S'(x) = J(x),

by the multiplication theorem for determinants and the chain rule. Thus
the theorem is also true for S.
Each point a \in E has a neighborhood U < E in which

(33) Tx) =T(a) + By "+" Buy Gro Gyoy 2 2 Gy (x -a),

where G; and B; are as in Theorem 10.7. Setting V = T(U), it follows
that (31) holds if the support of flies in VV. Thus:

Each point y \in T(E) lies in an open set V, = T(E) such that (31) holds
for all continuous functions whose support lies in V,.

Now let f be a continuous function with compact support K = T(E).
Since {V,} covers K, the Corollary to Theorem 10.8 shews that f= Zi, f,
where each y; is continuous, and each ; has its support in some V,.
Thus (31) holds for each yf, and hence also for their sum f.

DIFFERENTIAL FORMS

We shall now develop some of the machinery that is needed for the n-dimen-
sional version of the fundamental theorem of calculus which is usually called
Stokes’ theorem. The original form of Stokes’ theorem arose in applications of
vector analysis to electromagnetism and was stated in terms of the curl of a
vector field. Green's theorem and the divergence theorem are other special
cases. These topics are briefly discussed at the end of the chapter.

It is a curious feature of Stokes’ theorem that the only thing that is difficult
about it is the elaborate structure of definitions that are needed for its statement.
These definitions concern differential forms, their derivatives, boundaries, and
orientation. Once these concepts are understood, the statement of the theorem
is very brief and succinct, and its proof presents little difficulty.

Up to now we have considered derivatives of functions of several variables
only for functions defined in open sets. This was done to avoid difficulties that
can occur at boundary points. It will now be convenient, however, to discuss
differentiable functions on compact sets. We therefore adopt the following
convention:

To say that f is a %’-mapping (or a ¥"-mapping) of a compact set
D c R* into R" means that there is a %’-mapping (or a %’-mapping) g of
an open set Wc R* into R" such that D = W and such that g(x) = f(x) for
all xe D.
254 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.10 Definition Suppose E is an open set in R". A k-surface in E is a c'-
mapping ® from a compact set D = R* into E.

D is called the parameter domain of ®. Points of D will be denoted by
u= (uy, ..., up).

We shall confine ourselves to the simple situation in which D is either a
k-cell or the k-simplex Q* described in Example 10.4. The reason for this is
that we shall have to integrate over D, and we have not yet discussed integration
over more complicated subsets of R¥. It will be seen that this restriction on D
(which will be tacitly made from now on) entails no significant loss of generality
in the resulting theory of differential forms.

We stress that k-surfaces in E are defined to be mappings into E, not
subsets of E. This agrees with our earlier definition of curves (Definition 6.26).
In fact, 1-surfaces are precisely the same as continuously differentiable curves.

10.11 Definition Suppose E is an open set in R". A differential form of order
k > 1 in E (briefly, a k-form in E) is a function w, symbolically represented by
the sum

(34) o=Y a... , (dx; A Adxg
(the indices iy, ..., i, range independently from 1 to n), which assigns to each
k-surface ® in E a number o(®) = [4 w, according to the rule
( ( Xi oes Xi)

35 = i a (Ou) --* du,
3) la JZ a al (w) uy, oy Uy) !
where D is the parameter domain of ®.

The functions a;, ...; are assumed to be real and continuous in E. 1f
oy, ..., c, are the components of ®, the Jacobian in (35) is the one determined

by the mapping

(uy, REE] uy) - (c;,(w), ARE] c;, (0).
Note that the right side of (35) is an integral over D, as defined in Defini-
tion 10.1 (or Example 10.4) and that (35) is the definition of the symbol fo w.
A k-form w is said to be of class c" or c” if the functions a, ... ; in (34)
are all of class c’ or c”.
A O-form in E is defined to be a continuous function in E.

10.12 Examples
(a) Let y be a l-surface (a curve of class c’) in R®, with parameter
domain [0, 1].
Write (x, y, z) in place of (xy, x,, x3), and put

w=xdy+ydx.
(36)

INTEGRATION OF DIFFERENTIAL FORMS 255

Then

[a=[ Ban0) +2050 dt = 2103: = 7,0:00).

Note that in this example I, depends only on the initial point y(0)
and on the end point (1) of y. In particular, f, w = 0 for every closed
curve y. (As we shall see later, this is true for every 1-form w which is
exact.)

Integrals of 1-forms are often called line integrals.

(b) Fix a>0,b > 0, and define

y(t) =(acost, bsint) 0 <t<2n),

so that y is a closed curve in R?. (Its range is an ellipse.) Then

[ xdy = (ab cos? t dt = nab,

J Jo
whereas
2n
[yax= - [ ab sin? t dt = - nab.
v Jo

Note that [, x dy is the area of the region bounded by y. This is a
special case of Green's theorem.
(c) Let D be the 3-cell defined by

0<r<l, 0<0<m, 0<o<2m
Define ®(r, 0, c) = (x, y, z), where

x = rsin 0 cos c
y=rsin0sin c

z=rcos 0.
Then
a(x, y, 2) .
Jo(r, 6, 0) = 3.0.9) r? sin 0
Hence
4
[ dx Ady Adz = [(Jo=2
‘o ’p 3

Note that ® maps D onto the closed unit ball of R?, that the mapping
is 1-1 in the interior of D (but certain boundary points are identified by
®), and that the integral (36) is equal to the volume of ®(D).
256 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.13 Elementary properties Let w, w,, w, be k-forms in E. We write , = ,
if and only if w,(®) = w,(®) for every k-surface ® in E. In particular, » = 0
means that w(®) = 0 for every k-surface ® in E. If c is a real number, then
cw is the k-form defined by

37) [w= [
Ld Ld
and w = w; + w, means that
(38) [lo = [Lon + Il. o,

for every k-surface ® in E. As a special case of (37), note that - w is defined so
that

39 -0)=-| do.

(39) [cor==] do
Consider a k-form

(40) o=aX)dx; A Adx;,

and let a be the k-form obtained by interchanging some pair of subscripts in
(40). If (35) and (39) are combined with the fact that a determinant changes
sign if two of its rows are interchanged, we see that
(41) B= -w
As a special case of this, note that the anticommutative relation
(42) dx; A dx; = -dx; A dx;
holds for all i and j. In particular,
(43) dx; Ndx;=0 (i=1,...,n).

More generally, let us return to (40), and assume that i, = i, for some
r #s. If these two subscripts are interchanged, then a = w, hence w =0, by
(41).

In other words, if w is given by (40), then w = 0 unless the subscripts
iy, ..., Ix are all distinct.

If w is as in (34), the summands with repeated subscripts can therefore
be omitted without changing w.

It follows that O is the only k-form in any open subset of R", if k > n.

The anticommutativity expressed by (42) is the reason for the inordinate
amount of attention that has to be paid to minus signs when studying differential
forms.
INTEGRATION OF DIFFERENTIAL FORMS 257

10.14 Basic k-forms If i, ..., i, are integers such that 1 <ij <i, <'-
<i, <n, and if I is the ordered k-tuple {i,, ..., iy}, then we call I an increasing
k-index, and we use the brief notation

(44) dxp=dx; A Adx;,.

These forms dx; are the so-called basic k-forms in R".

It is not hard to verify that there are precisely n!/k!(n - k)! basic k-forms
in R"; we shall make no use of this, however.

Much more important is the fact that every k-form can be represented in
terms of basic k-forms. To see this, note that every k-tuple {ji, ..., ji} of distinct
integers can be converted to an increasing k-index J by a finite number of inter-
changes of pairs; each of these amounts to a multiplication by -1, as we saw
in Sec. 10.13; hence

(45) dxj A ccc Adx;, = ej, jk) dx;

where &(jy, ..., ji) is 1 or -1, depending on the number of interchanges that
are needed. In fact, it is easy to see that

(46) (ys +s i) = 8Cas +0 JW)

where s is as in Definition 9.33.
For example,

dx; Adxs Adxy Adx, = -dx; Adx, Adxs A dxs
and
dx, A dx, Adxy=dx, Adxy Adx,.

If every k-tuple in (34) is converted to an increasing k-index, then we
obtain the so-called standard presentation of w:

(47) © = by(x)dx;.

T
The summation in (47) extends over all increasing k-indices 1. [Of course, every
increasing k-index arises from many (from k!, to be precise) k-tuples. Each

b; in (47) may thus be a sum of several of the coefficients that occur in (34).]
For example,

x, dx; Adxy - Xx, dxy A dx, + x5dx, Adxsy + dx; Adx,
is a 2-form in R® whose standard presentation is
(1 =x) dx; Adx, + (x3 + x3) dx, Adxy.

The following uniqueness theorem is one of the main reasons for the
introduction of the standard presentation of a k-form.
258 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.15 Theorem Suppose
(48) w= bx) dx,
1

is the standard presentation of a k-form w in an open set Ec R". If w =0 in E,
then b(x) = 0 for every increasing k-index I and for every x \in E.

Note that the analogous statement would be false for sums such as (34),
since, for example,

dx, A dx, + dx, ndx; =0.

Proof Assume, to reach a contradiction, that b,(v) > 0 for some ve E
and for some increasing k-index J ={j,,..., j;}. Since b, is continuous,
there exists 4 > 0 such that b,(x) > 0 for all xe R" whose coordinates
satisfy |x; -v;| < h. Let D be the k-cell in R* such that ue D if and
only if |u,| <hforr=1,..., k. Define

(49) Ou) =v + 5 ue; (ue D).

Then ® is a k-surface in E, with parameter domain D, and b,(®(u)) > 0
for every ue D.
We claim that

(50) IN w= I b,(®(u)) du.

Since the right side of (50) is positive, it follows that w(®) # 0. Hence
(50) gives our contradiction.

To prove (50), apply (35) to the presentation (48). More specifically,
compute the Jacobians that occur in (35). By (49),

Xj ey Xj) =1
uy, «oy uy) ’

For any other increasing k-index I # J, the Jacobian is 0, since it is the
determinant of a matrix with at least one row of zeros.

10.16 Products of basic k-forms Suppose
(51) I={i,...,i,}, J={ji ody

where 1 <i; < +  <i,<nand 1 <j, <- <j, <n. The product of the cor-
responding basic forms dx; and dx, in R" is a (p + c)-form in R", denoted by
the symbol dx; A dx, and defined by

(52) dxpndxy=dx;, Aco Adxg Ndxg Acc dx;
INTEGRATION OF DIFFERENTIAL FORMS 259

If I and J have an element in common, then the discussion in Sec. 10.13
shows that dx; A dx; =0.

If I and J have no element in common, let us write [/, J] for the increasing
(p + g)-index which is obtained by arranging the members of J U J in increasing
order. Then dx, 5 is a basic (p + g)-form. We claim that

(53) dx; A dx; =(=1) "dx, pn

where « is the number of differences j, - i; that are negative. (The number of
positive differences is thus pg - a.)
To prove (53), perform the following operations on the numbers

(54) fener dpi Jus oeesdy

Move i, to the right, step by step, until its right neighbor is larger than i,.
The number of steps is the number of subscripts # such that i, < j,. (Note that
0 steps are a distinct possibility.) Then do the same fori,_,,..., i. The total
number of steps taken is a. The final arrangement reached is [Z, J]. Each step,
when applied to the right side of (52), multiplies dx; A dx; by -1. Hence (53)
holds.

Note that the right side of (53) is the standard presentation of dx; A dx.

Next, let K = (ky, ..., k,) be an increasing r-index in {1, ..., n}. We shall
use (53) to prove that

(55) (dx; A dxy) A dxg = dx; A (dx; A dxg).

If any two of the sets /, J, K have an element in common, then each side
of (55) is 0, hence they are equal.

So let us assume that 7, J, K are pairwise disjoint. Let [/, J, K] denote
the increasing (p + gq + r)-index obtained from their union. Associate f with
the ordered pair (J, K) and y with the ordered pair (/, K) in the way that « was
associated with (7, J) in (53). The left side of (55) is then

(=1D)*dxpy, jy Adxg = (= 1)% -1)fty dxr 5. x
by two applications of (53), and the right side of (55) is
(=D dx; A dxpy xy = (= DA(-1)**? dxyr, 5, xy-

Hence (55) is correct.

10.17 Multiplication Suppose w and 4 are p- and g-forms, respectively, in
some open set E = R", with standard presentations
(56) w=) bx) dx, A=) cyx) dx,

I

J

where I and J range over all increasing p-indices and over all increasing g-indices
taken from the set {1, ..., n}.
260 PRINCIPLES OF MATHEMATICAL ANALYSIS

Their product, denoted by the symbol a A 4, is defined to be
(57) oA A=) b(x)c,(x) dx; A dx.
I,J
In this sum, 7 and J range independently over their possible values, and dx; A dx;
is as in Sec. 10.16. Thus w A Ais a (p + g)-form in E.

It is quite easy to see (we leave the details as an exercise) that the distribu-
tive laws

(0, +o) Ad=(w;, AA) + (0; AR)
and
OAM +A)=aAl)+ (AL)

hold, with respect to the addition defined in Sec. 10.13. If these distributive
laws are combined with (55), we obtain the associative law

(58) aA)Ao=wA(AAo)

for arbitrary forms w, 4, c in E.
In this discussion it was tacitly assumed that p > 1 and c > 1. The product
of a 0-form f with the p-form w given by (56) is simply defined to be the p-form

Jo =of = Xs (x)by(x) dx;.

It is customary to write fw, rather than f A w, when fis a 0-form.

10.18 Differentiation We shall now define a differentiation operator d which
associates a (k + 1)-form dw to each k-form w of class c’ in some open set
Ec Rr

A 0-form of class c’ in E is just a real function fe c'(E), and we define

(59) df = 3 (Df) dx.

If w = Zb (x) dx; is the standard presentation of a k-form w, and b; \in c'(E)
for each increasing k-index I, then we define

(60) do = (db;) A dx;.

I

10.19 Example Suppose E is open in R", fe c'(E), and y is a continuously
differentiable curve in E, with domain [0, 1]. By (59) and (35),

(61) [r=] 3 auneenmic a.
INTEGRATION OF DIFFERENTIAL FORMS 261

By the chain rule, the last integrand is (f° y)'(c). Hence

(62)

[ df =f) = £60),

and we see that f, df is the same for all y with the same initial point and the same
end point, as in (a) of Example 10.12.

Comparison with Example 10.12(b) shows therefore that the 1-form x dy

is not the derivative of any O-form f. This could also be deduced from part (b)
of the following theorem, since

d(x dy) =dx Andy #0.

10.20 Theorem

(63)

(64)

(a) If w and A are k- and m-forms, respectively, of class  \in ' in E, then
dw A A) = (dw) A L+(=1)*w Adi
(b) If wis of class  \in " in E, then d*w = 0.
Here d?w means, of course, d(dw).

Proof Because of (57) and (60), (a) follows if (63) is proved for the
special case

w= fdx,, A=gdx,

where f, g \in c'(E), dx; is a basic k-form, and dx, is a basic m-form. [If
k or m or both are 0, simply omit dx; or dx; in (64); the proof that follows
is unaffected by this.] Then

w AL=fgdx; A dx.

Let us assume that / and J have no element in common. [In the other
case each of the three terms in (63) is 0.] Then, using (53),

d(w A 2) = d(fg dx; A dx;) =(=1)*d(fg dx; 1) -
By (59), d(fg) = f dg + g df. Hence (60) gives

dw AA) =(=1)"(fdg + gdf) A dx 5
= (gdf+fdg) An dx; dx.

Since dg is a 1-form and dx is a k-form, we have

dg A dx; = (=1)*dx; A dg,
262 PRINCIPLES OF MATHEMATICAL ANALYSIS

by (42). Hence
dw AA) = (df Adxp) A (gdxy) + (=D*fdx,) A (dg A dx)
= (dw) A A+ (=o A di,

which proves (a).
Note that the associative law (58) was used freely.
Let us prove (b) first for a 0-form fe  \in ":

df= fl 3, (x) dx )
= S d(D,f) A dx;
i=

= 3 (Dy) dx, A dx,.
i, j=1

Since D;;f= D;;f (Theorem 9.41) and dx; A dx, = -dx, A dx;, we see
that df = 0.

If w =fdx;, as in (64), then dw = (df) A dx. By (60), d(dx;) = 0.
Hence (63) shows that

d*w = (d*f) A dx; =0.
10.21 Change of variables Suppose E is an open set in R", T is a ¥’-mapping
of E into an open set ¥ = R", and w is a k-form in ¥, whose standard presenta-
tion is
(65) w= )) by) dy; .

(We use y for points of V, x for points of E.)
Lett, ..., t, be the components of T: If

Y=01 ym) =TX)
then y; = 1;(x). Asin (59),
(66) dt; = (D;1)(x) dx; (I<i<m).
j=1
Thus each dt; is a 1-form in E.
The mapping 7 transforms w into a k-form wy in E, whose definition is

(67) wr= Yb (TX) dt, A Ad.

1
In each summand of (67), I = {i}, ..., i} is an increasing k-index.

Our next theorem shows that addition, multiplication, and differentiation
of forms are defined in such a way that they commute with changes of variables.
INTEGRATION OF DIFFERENTIAL FORMS 263

10.22 Theorem With E and T as in Sec. 10.21, let w and 1 be k- and m-forms
in V, respectively. Then

(a (+ Ar=or+irifk=m;
b) (aAXr=wp Air;
(c) d(wr) = (dw) if w is of class  \in ' and T is of class  \in ".

Proof Part (a) follows immediately from the definitions. Part (b) is
almost as obvious, once we realize that
(68) (dy, Aor Ady )r=dt, Ao Ad

regardless of whether {i|, ..., i} is increasing or not; (68) holds because
the same number of minus signs are needed on each side of (68) to produce
increasing rearrangements.

We turn to the proof of (c). If fis a 0-form of class c’ in V, then

Six) =f(T(x), df= LDS XY) dy;
By the chain rule, it follows that
(69) d(fr) = 2 (Dfr)(x) dx;
= ) )) (Dif NT x))(D; 1:)(x) dx;
= 2 (Dif XT (x)) dt;

=r.
Ifdyr=dy, An Ady, then (dy) =dt; A+ Ad
10.20 shows that
(70) d((dy)r) = 0.

(This is where the assumption 7 \in c” is used.)
Assume now that w = fdy,;. Then

or = fr(x) (dy)
and the preceding calculations lead to
d(wr) = d(fr) A (dy Dr = df)r A (dy Dr
= (df) A dy)r = (dw)r.
The first equality holds by (63) and (70), the second by (69), the third by
part (b), and the last by the definition of dw.

The general case of (c) follows from the special case just proved, if
we apply (a). This completes the proof.

and Theorem

ix?
264 PRINCIPLES OF MATHEMATICAL ANALYSIS

Our next objective is Theorem 10.25. This will follow directly from two
other important transformation properties of differential forms, which we state
first.

10.23 Theorem Suppose T is a c'-mapping of an open set E = R" into an open
set V.< R™, Sis a  \in '-mapping of V into an open set W = RF, and is a k-form
in W, so that wg is a k-form in V and both (wg) and wgy are k-forms in E, where
ST is defined by (ST)(x) = S(T (x)). Then
an (ws)r = 0st.

Proof If w and A are forms in W, Theorem 10.22 shows that

(0 A Ds)r = (ws A A)r = (Ws)r A (gr
and
(w A Bsr = gr A st.

Thus if (71) holds for w and for 4, it follows that (71) also holds for w A A.
Since every form can be built up from O-forms and 1-forms by addition
and multiplication, and since (71) is trivial for O-forms, it is enough to
prove (71) in the case w = dz,, c=1, ..., p. (We denote the points of
E, V, W by x,y, z, respectively.)

Lett, ..., t, be the components of 7, let s,, ..., 5, be the compo-
nents of S, and let ry, ..., r, be the components of ST. If w = dz,, then
wg = ds, = ) (D;5)(y) dy;,

J
so that the chain rule implies
(as)r = 3 (D;s)(T®) di;
J
= )) (D; 5, )(T (x)) )) (D;1))(x) dx;
J i

= (Dir)(X) dx; = dr, = wgr.
7

10.24 Theorem Suppose w is a k-form in an open set E <= R", ® is a k-surface
in E, with parameter domain D < R¥, and A is the k-surface in R¥, with parameter
domain D, defined by A(u) = u(ue D). Then

0=| we.
CRIRE
Proof We need only consider the case

w=a(x)dx; A Adx,.
7)

INTEGRATION OF DIFFERENTIAL FORMS 265

If c,, ..., c, are the components of ®, then
we =a(®) dp; A 0 Ado.
The theorem will follow if we can show that
dpi, A Ado =J)duy A A dug,
where

o(x;,, RN Xi)
Jw) = Oy, ..., uy) ’

since (72) implies
[w= a®au)/() du
vo *D

We -
A

= | AaW)IW duty A+ A dug = |

Let [A] be the k by k matrix with entries

wp, q) = (D9: )w)  (pg=1,....k).
Then

dpi, = «(p.q) du,

q
so that

dp, A Ady, =) a(l,qy) alk, q) dug, Ao A dug,

In this last sum, gy, ..., g, range independently over 1, ..., k. The anti-
commutative relation (42) implies that

dug, A ccc A dug =5(qy, qi) dup Ace A dy,

where s is as in Definition 9.33; applying this definition, we see that
dp; A Adp =det[A)duy A 0 A du;

and since J(u) = det [4], (72) is proved.

The final result of this section combines the two preceding theorems.

10.25 Theorem Suppose T is a c'-mapping of an open set E = R" into an open
set V.< R™ ® is a k-surface in E, and w is a k-form in V.

Then

| w=] or.
TO a
266 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Let D be the parameter domain of ® (hence also of 7®) and
define A as in Theorem 10.24.
Then

[eo = [, Wre = [ (w1)o = [, ar.

The first of these equalities is Theorem 10.24, applied to T® in place of ®.
The second follows from Theorem 10.23. The third is Theorem 10.24,
with wy in place of w.

SIMPLEXES AND CHAINS

10.26 Affine simplexes A mapping f that carries a vector space X into a
vector space Y is said to be affine if f - f(0) is linear. In other words, the require-
ment is that

(73) f(x) = (0) + Ax

for some 4 \in L(X, Y).

An affine mapping of R¥ into R" is thus determined if we know (0) and
f(e;) for 1 <i < k; as usual, {e,, ..., c} is the standard basis of R*.

We define the standard simplex Q* to be the set of all ue R* of the form

k
(74) u=>3 ae
i=1
such that oa; >0fori=1,..., k and Za; < 1.
Assume now that py, py, ..., px are points of R". The oriented affine
k-simplex
(75) o=[Po,Pr> 5 Pi]

is defined to be the k-surface in R" with parameter domain QF which is given
by the affine mapping

k
(76) ola; + + + oe) = Po + La = Po):

Note that o is characterized by

an 00) =po, o(e)=p; (forl=<i<k),
and that
(78) o(u) = py + Au (ue QY

where 4 \in L(R¥, R") and Ae; =p; - p, for 1 <i <k.
INTEGRATION OF DIFFERENTIAL FORMS 267

We call o oriented to emphasize that the ordering of the vertices po, ..., Px
is taken into account. If
(79) G =[pigs Pips +5 Pir)
where {iy, i}, ..., i,} is a permutation of the ordered set {0, 1, ..., k}, we adopt
the notation
(80) G=5(ig, i1s .-, i),

where s is the function defined in Definition 9.33. Thus é = +0, depending on
whether s = 1 or s = -1. Strictly speaking, having adopted (75) and (76) as
the definition of a, we should not write &§ = c unless i, =0, ..., i, =k, even
ifs(ig, ..., i) = 1; what we have here is an equivalence relation, not an equality.
However, for our purposes the notation is justified by Theorem 10.27.

If 6 = eo (using the above convention) and if c = 1, we say that and c
have the same orientation; if e = -1, & and o are said to have opposite orienta-
tions. Note that we have not defined what we mean by the “orientation of a
simplex.”” What we have defined is a relation between pairs of simplexes having
the same set of vertices, the relation being that of “having the same orientation.”

There is, however, one situation where the orientation of a simplex can
be defined in a natural way. This happens when n = k and when the vectors
P: - Po (1 <i <k) are independent. In that case, the linear transformation A
that appears in (78) is invertible, and its determinant (which is the same as the
Jacobian of c) is not 0. Then o is said to be positively (or negatively) oriented if
det A is positive (or negative). In particular, the simplex [0, e,, ..., c] in R¥,
given by the identity mapping, has positive orientation.

So far we have assumed that k > I. An oriented 0-simplex is defined to
be a point with a sign attached. We write 6 = +p, or 6 = - po. If 0 =cp,
(e = +1) and if fis a O-form (i.e., a real function), we define

[=o

10.27 Theorem If c is an oriented rectilinear k-simplex in an open set E < R"
and if 6 = eo then
31) [o=c]w

for every k-form w in E.

Proof For k=0, (81) follows from the preceding definition. So we
assume k > 1 and assume that c is given by (75).
268 PRINCIPLES OF MATHEMATICAL ANALYSIS

Suppose 1 <j<k, and suppose 6 is obtained from o by inter-
changing p, and p;. Then e = -1, and

6(u) =p; + Bu (ue Q%,

where B is the linear mapping of R* into R” defined by Be; = p, - Pp;
Be, =p; -p; if i #/. If we write de; =x; (1 <i<k), where 4 is given
by (78), the column vectors of B (that is, the vectors Be;) are

X; = Xj Xo = Xp, =X, Xu - Xj, ee, Xp - XL

If we subtract the jth column from each of the others, none of the deter-
minants in (35) are affected, and we obtain columns x, ..., X;_;, -X,,
Xji1 -., Xc. These differ from those of 4 only in the sign of the jth
column. Hence (81) holds for this case.

Suppose next that 0 <i <j < k and that & is obtained from o by
interchanging p; and p;. Then &(u) = p, + Cu, where C has the same
columns as A, except that the ith and jth columns have been inter-
changed. This again implies that (81) holds, since c = - 1.

The general case follows, since every permutation of {0, 1, ..., k} is
a composition of the special cases we have just dealt with.

10.28 Affine chains An affine k-chain I in an open set E = R" is a collection
of finitely many oriented affine k-simplexes o,, ..., 0, in E. These need not be
distinct; a simplex may thus occur in I" with a certain multiplicity.

If Tis as above, and if w is a k-form in E, we define

(82) [[o= 5 [ o

i=1vq;
We may view a k-surface ® in E as a function whose domain is the collec-
tion of all k-forms in E and which assigns the number [4 w to w. Since real-

valued functions can be added (as in Definition 4.3), this suggests the use of the
notation

(83) I'=o,+ "+o,

or, more compactly,
(84) r=%o
i=1

to state the fact that (82) holds for every k-form w in E.

To avoid misunderstanding, we point out explicitly that the notations
introduced by (83) and (80) have to be handled with care. The point is that
every oriented affine A-simplex o in R" is a function in two ways, with different
domains and different ranges, and that therefore two entirely different operations
INTEGRATION OF DIFFERENTIAL FORMS 269

of addition are possible. Originally, o was defined as an R"-valued function
with domain Q*; accordingly, o, + o, could be interpreted to be the function
o that assigns the vector o,(u) + o,(u) to every ue Q; note that c is then again
an oriented affine A-simplex in R"! This is not what is meant by (83).

For example, if 0, = -o, as in (80) (that is to say, if c, and o, have the
same set of vertices but are oppositely oriented) and if I’ =o, + 7,, then
fra=0 for all ®, and we may express this by writing I’ =0 or 0; + 6, =0.
This does not mean that a,(u) + g,(u) is the null vector of R".

10.29 Boundaries For k > |, the boundary of the oriented affine k-simplex
0 = [po P1> +++» Pl
is defined to be the affine (k - 1)-chain
k
(85) Go = (=D/Por Biss Perso Bl
i
For example, if c = [py, p,, p.J, then

do = [py, 2] = [Po P2] + [Po, Pi] = [Pos Pi] + [P1s P2] + [P25 Pols

which coincides with the usual notion of the oriented boundary of a triangle.

For | <j < k, observe that the simplex a; = [pg, ..., Pj-1, Pj+1> +s Pil
which occurs in (85) has Q*~! as its parameter domain and that it is defined by
(86) oy(u) = po + Bu (ue a*7h),

where B is the linear mapping from R*"! to R" determined by
Be; =p, - po (if 1<i<j-1),
Be; =pi+1 - Po (if j<i<k-=1).
The simplex
00 = [Pi P2s + +s Pil:
which also occurs in (85), is given by the mapping
oo(u) =p, + Bu,

where Be; =p; - py for <i<k- 1.

10.30 Differentiable simplexes and chains Let 7" be a c”-mapping of an open
set £ = R"into an open set ¥ = R™; T need not be one-to-one. If ois an oriented
affine k-simplex in E, then the composite mapping ® = T= c (which we shall
sometimes write in the simpler form 70) is a k-surface in V, with parameter
domain Q*. We call ® an oriented k-simplex of class 6".
270 PRINCIPLES OF MATHEMATICAL ANALYSIS

A finite collection ¥ of oriented k-simplexes a,, ..., ®, of class  \in ” in V
is called a k-chain of class  \in " in V. If w is a k-form in V, we define

(87) l,e= 5 le

and use the corresponding notation ¥ = X®;.
If T' = Xo; is an affine chain and if ®; = To o;, we also write W =T oT,
or

(88) TQ 0) =) To.

The boundary é® of the oriented k-simplex ® = To o is defined to be the
(k - 1) chain

(89) od = T (do).

In justification of (89), observe that if T is affine, then ® =T og is an
oriented affine k-simplex, in which case (89) is not a matter of definition, but is
seen to be a consequence of (85). Thus (89) generalizes this special case.

It is immediate that 0® is of class c" if this is true of ®.

Finally, we define the boundary c¥ of the k-chain W = X®; to be the
(k - 1) chain

(90) ov =Y oo,

10.31 Positively oriented boundaries So far we have associated boundaries to
chains, not to subsets of R". This notion of boundary is exactly the one that is
most suitable for the statement and proof of Stokes’ theorem. However, in
applications, especially in R? or R®, it is customary and convenient to talk
about “‘oriented boundaries’ of certain sets as well. We shall now describe
this briefly.

Let Q" be the standard simplex in R", let c, be the identity mapping with
domain Q". As we saw in Sec. 10.26, o, may be regarded as a positively oriented
n-simplex in R". Its boundary do, is an affine (# - 1)-chain. This chain is
called the positively oriented boundary of the set Q".

For example, the positively oriented boundary of Q3 is

les, e;. e3] - [0,e;, e3] + [0, ef, e5] - [0, ey, e,].

Now let 7 be a 1-1 mapping of Q" into R", of class c”, whose Jacobian is
positive (at least in the interior of Q"). Let E = T(Q"). By the inverse function
theorem, E is the closure of an open subset of R". We define the positively
oriented boundary of the set E to be the (n - 1)-chain

OT = T (day),
and we may denote this (n - 1)-chain by GE.
INTEGRATION OF DIFFERENTIAL FORMS 271

An obvious question occurs here: If E=T,(Q") = T,(Q"), and if both
T, and T, have positive Jacobians, is it true that 07, = c7,? That is to say,
does the equality

J w =| w
eT oT,

hold for every (n - 1)-form w? The answer is yes, but we shall omit the proof.
(To see an example, compare the end of this section with Exercise 17.)

One can go further. Let
Q=E, u'r UE

Crs

where E; = T(Q"), each T has the properties that 7 had above, and the interiors
of the sets E; are pairwise disjoint. Then the (n - 1)-chain

OT, + +++ + oT, = 0Q

is called the positively oriented boundary of Q.
For example, the unit square /? in R? is the union of c,(Q?) and ,(0?),
where

ag,(u) =u, a(n) =e; +e, -u
Both c, and o, have Jacobian | > 0. Since
co, =[0,e,e,], ag, =1[e; +e,,e,,c]
we have
doy = [e,, e;] - [0, e;] + [0, e,],
Co, =[e,,e;] -[e, +e,,e]+[e, +e,,e,];
The sum of these two boundaries is
Ir =1[0,e,]+ [e,, e, +e] + [e, + e;,  \in ,] + [e;, 0],
the positively oriented boundary of 2. Note that [e,, e,] canceled [e, , ,].
If ® is a 2-surface in R™, with parameter domain I, then ® (regarded as
a function on 2-forms) is the same as the 2-chain
Dog, +Doo,.
Thus
0D =06(®o0ay) + (P= a,)
= B(da,) + D(da,) = DAI).
In other words, if the parameter domain of ® is the square 72, we need

not refer back to the simplex Q?, but can obtain é® directly from 912.
Other examples may be found in Exercises 17 to 19.
272 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.32 Example For 0 <u <r, 0<v<2nr, define
2(u, v) = (sin u cos v, sin u sin v, COS u).

Then X is a 2-surface in R®, whose parameter domain is a rectangle D = R?,
and whose range is the unit sphere in R*. Its boundary is

Z=X0D)=vy +7,+7:+ 7s
where
y1(u) = Z(u, 0) = (sin u, 0, cos u),
72(v) = Z(n,v) = (0,0, -1),
y3(u) = Z(n - u, 21) = (sin u, 0, - cos u),
740) = Z(0, 27 - v) = (0, 0, 1),

with [0, n] and [0, 27] as parameter intervals for x and v, respectively.

Since y, and y, are constant, their derivatives are 0, hence the integral of
any 1-form over y, or y, is 0. [See Example 1.12(a).]

Since y3(¥) = y(n - u), direct application of (35) shows that

[e==]e

for every 1-form w. Thus [,; w = 0, and we conclude that 4% = 0.

(In geographic terminology, 0X starts at the north pole »N, runs to the
south pole S along a meridian, pauses at S, returns to N along the same meridian,
and finally pauses at N. The two passages along the meridian are in opposite
directions. The corresponding two line integrals therefore cancel each other.
In Exercise 32 there is also one curve which occurs twice in the boundary, but
without cancellation.)

STOKES’ THEOREM

10.33 Theorem If is a k-chain of class  \in " in an open set V < R" and if o
is a (k - 1)-form of class  \in ' in V, then

©1) [do=| o.
a 4 voy
The case kK =m = 1 is nothing but the fundamental theorem of calculus
(with an additional differentiability assumption). The case k = m = 2 is Green’s
theorem, and k =m = 3 gives the so-called ‘‘divergence theorem’ of Gauss.
The case k =2, m = 3 is the one originally discovered by Stokes. (Spivak’s
INTEGRATION OF DIFFERENTIAL FORMS 273

book describes some of the historical background.) These special cases will be
discussed further at the end of the present chapter.

92)

93)

4

99)

(96)

Proof It is enough to prove that

[ do = I, w

for every oriented k-simplex ® of class c” in V. For if (92) is proved and
if ¥ = Z®,, then (87) and (89) imply (91).
Fix such a ® and put
o=1[0,e,..., el

Thus o is the oriented affine k-simplex with parameter domain Q* which
is defined by the identity mapping. Since ® is also defined on QF (see
Definition 10.30) and ® \in %”, there is an open set E = R* which contains
Q%, and there is a ¥"-mapping T of E into V such that ® = T-o. By
Theorems 10.25 and 10.22(c), the left side of (92) is equal to

[ do = Ii (dw) =| d(wy).

Another application of Theorem 10.25 shows, by (89), that the right side

of (92) is
[i = [ron = I. or:

é

Since wy is a (k - 1)-form in E, we see that in order to prove (92)
we merely have to show that

di=| 4
[#=],
for the special simplex (93) and for every (k - 1)-form A of class  \in ' in E.
If kK = 1, the definition of an oriented O-simplex shows that (94)

merely asserts that

al

[wy du=£(1) = (0)

v0
for every continuously differentiable function f on [0, 1], which is true
by the fundamental theorem of calculus.

From now on we assume that k > 1, fix an integer r (1 <r <k),
and choose fe  \in '(E). It is then enough to prove (94) for the case

A=fX)dx; A Adx oy AdXp py A Ady

since every (k - 1)-form is a sum of these special ones, for r=1, ..., k.
274 PRINCIPLES OF MATHEMATICAL ANALYSIS

By (85), the boundary of the simplex (93) is

k :
do =ley,...,e] + (= Dir,
i=
where
T,=00,e,..., \in _1, \in i1y.-.s \in l
fori=1,..., k. Put

To=1[ \in , \in 1, ..., \in  1, \in iq... el

Note that 7, is obtained from [e,, ...,  \in ] by r - 1 successive interchanges
of e, and its left neighbors. Thus

7) do =(=1y"1 + 3 (=r.

Each 1; has Q*"! as parameter domain.
If x = to(u) and ue Q*!, then

u; (1<j<r),
(98) Xp=l=(u + +uy) (=r)
lus (r<j<k).

Ifl<i<k ue a' and x = 7,(u), then

(4 (I1<j<i),
(99) x= 10 (=i)
luo, i<i<h).
For 0 <i <k, let J; be the Jacobian of the mapping

(100) Us ves toy) = (Xgs oes Xoops Xppgs eves Xi)

induced by 7;. When / = 0 and when i = r, (98) and (99) show that (100)
is the identity mapping. Thus J, = 1, J, = 1. For other i, the fact that
x; =0 in (99) shows that J; has a row of zeros, hence J; = 0. Thus

(101) [4=0 (i#0,i #7),
by (35) and (96). Consequently, (97) gives
(102) [ A=(=1r7t ity A

= (=U [fCeo() - fe) do.
INTEGRATION OF DIFFERENTIAL FORMS 275

On the other hand,
dl =(Df)X)dx, Adx; A rr Adx,_y AdXpqg Are Adxy
= (=I) HD YX) dx; A +o A dx,

so that
(103) [a= (D,f)(x) dx.
a Qk

We evaluate (103) by first integrating with respect to x,, over the interval
[0,1 -(x; + + Xpoy + X00 + 0 +X),

put (Xg, «voy Xpoqs Xppgs eves Xi) = (Uy, ..., Uy_y), and see with the aid of
(98) that the integral over Q* in (103) is equal to the integral over Q¥~!
in (102). Thus (94) holds, and the proof is complete.

CLOSED FORMS AND EXACT FORMS

10.34 Definition Let w be a k-form in an open set £ = R". Ifthereisa (k - 1)-
form Ain E such that w = d2, then w is said to be exact in E.

If w is of class ¥’ and dw = 0, then w is said to be closed.

Theorem 10.20(b) shows that every exact form of class 4” is closed.

In certain sets E, for example in convex ones, the converse is true; this
is the content of Theorem 10.39 (usually known as Poincaré’s lemma) and
Theorem 10.40. However, Examples 10.36 and 10.37 will exhibit closed forms
that are not exact.

10.35 Remarks

(a) Whether a given k-form w is or is not closed can be verified by
simply differentiating the coefficients in the standard presentation of w.
For example, a 1-form

(104) w=) f{x)dx;,
i=1
with f; \in c'(E) for some open set E < R", is closed if and only if the
equations
(105) (D; f(x) = (Di f))(x)

hold for all i, jin {1, ..., n} and for all x \in E.
276 PRINCIPLES OF MATHEMATICAL ANALYSIS

Note that (105) is a “pointwise” condition; it does not involve any
global properties that depend on the shape of E.

On the other hand, to show that w is exact in E, one has to prove
the existence of a form A, defined in E, such that dA = w. This amounts
to solving a system of partial differential equations, not just locally, but
in all of E. For example, to show that (104) is exact in a set E, one has
to find a function (or 0-form) g \in c’(E) such that

(106) (D;g)x)=f(x) (XeE 1<i<n).
Of course, (105) is a necessary condition for the solvability of (106).

(b) Let w be an exact k-form in E. Then there is a (k ~ 1)-form 4 in E
with dA = w, and Stokes’ theorem asserts that

(107) [o=[ a=] 2

for every k-chain W of class c” in E.
If ¥; and W¥, are such chains, and if they have the same boundaries,

it follows that
w=| o.
LL. LL.

In particular, the integral of an exact k-form in E is O over every
k-chain in E whose boundary is 0.

As an important special case of this, note that integrals of exact
1-forms in E are 0 over closed (differentiable) curves in E.

(c) Let w be a closed k-form in E. Then dw = 0, and Stokes’ theorem
asserts that

(108) [,o = [do =0

for every (k + 1)-chain ¥ of class c” in E.
In other words, integrals of closed k-forms in E are 0 over k-chains
that are boundaries of (k + 1)-chains in E.

(d) Let ¥ be a (k + 1)-chain in FE and let 4 be a (k - 1)-form in E, both
of class #”. Since d%/ = 0, two applications of Stokes’ theorem show that

(109) [7 = [4 = [ a =0.

We conclude that 8% = 0. In other words, the boundary of a
boundary is 0.
See Exercise 16 for a more direct proof of this.
INTEGRATION OF DIFFERENTIAL FORMS 277

10.36 Example Let E = R? - {0}, the plane with the origin removed. The

1-form
xdy -ydx

110, ha AE fui

(110)

is closed in R* - {0}. This is easily verified by differentiation. Fix r > 0, and

define

(111) y(t) = (rcost, rsint) 0<t< 2m).

Then y is a curve (an ‘‘oriented 1-simplex”) in R* - {0}. Since (0) = y(2n),
we have

(112) dy =0.
Direct computation shows that
(113) [n=2n#0.
v
The discussion in Remarks 10.35(b) and (c) shows that we can draw two

conclusions from (113):

First, n is not exact in R* - {0}, for otherwise (112) would force the integral
(113) to be 0.

Secondly, y is not the boundary of any 2-chain in R* - {0} (of class 4"),
for otherwise the fact that # is closed would force the integral (113) to be 0.

10.37 Example Let E = R® - {0}, 3-space with the origin removed. Define

_xdyadztydzndx+zdx Ady
= (x? +3? + z2)32

(114) c

where we have written (x, y, z) in place of (xy, x,, x3). Differentiation shows
that dc = 0, so that { is a closed 2-form in R* - {0}.

Let I be the 2-chain in R® - {0} that was constructed in Example 10.32;
recall that I is a parametrization of the unit sphere in R®. Using the rectangle
D of Example 10.32 as parameter domain, it is easy to compute that

(115) [=] sinududo=dr 0.

As in the preceding example, we can now conclude that { is not exact in
R® - {0} (since 0X = 0, as was shown in Example 10.32) and that the sphere T
is not the boundary of any 3-chain in R® - {0} (of class 6”), although 4% = 0.
The following result will be used in the proof of Theorem 10.39.
278 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.38 Theorem Suppose E is a convex open set in R", fe  \in '(E), p is an integer,
l<p<n, and
(116) (D;/)x)=0 (p<j<nxekE).
Then there exists an Fe  \in '(E) such that
117) (D,F)x)=/(x), (D;F)x)=0 (p<j<nxekE)
Proof Write x = (x/, x,, x"), where
X = (xp, ony Xoo) X= (Xpagy ees Xp)
(When p =1, x’ is absent; when p =n, x" is absent.) Let VV be the
set of all (x, x,) \in R? such that (x, x,, x") \in E for some x". Being a
projection of E, Vis a convex open set in R?. Since E is convex and (116)

holds, f(x) does not depend on x". Hence there is a function c, with
domain V, such that
J) =o, x,)
for all xe E.
If p=1, Vis a segment in R' (possibly unbounded). Pick ce V
and define

x1
F(x) = | o(t)dt  (xeE).
c
If p> 1, let U be the set of all x"e RP~! such that (x, x,)e V for
some x,. Then U is a convex open set in RP™! and there is a function

a \in  \in '(U) such that (x, a(x’)) \in V for every x’ \in U; in other words, the
graph of « lies in V (Exercise 29). Define

Foo ="

a(x’

ox, nd (xeE).
)
In either case, F satisfies (117).
(Note: Recall the usual convention that [ means - [§if b <a.)

10.39 Theorem If E < R" is convex and open, if k > |, if ® is a k-form of
class  \in ' in E, and if do = 0, then there is a (k - 1)-form 1 in E such that » = dA.

Briefly, closed forms are exact in convex sets.

Proof For p=1,...,n, let Y, denote the set of all k-forms w, of class
%' in E, whose standard presentation
(118) w= fUX)dx,
I
does not involve dx, ,, ..., dx,. In other words, I < {l, ..., p} if f(x) # 0

for some x \in E.
INTEGRATION OF DIFFERENTIAL FORMS 279

We shall proceed by induction on p.

Assume first that we ¥;. Then w=f(x)dx,. Since dw =0,
(D;f)(x) =0for1 <j <n, xeE. By Theorem 10.38 there is an F \in c'(E)
such that D,F = fand D;F=0 for 1 <j<n. Thus

dF = (D,F)(x) dx, = f(x) dx, = 0.

Now we take p > 1 and make the following induction hypothesis:
Every closed k-form that belongs to Y,_, is exact in E.
Choose w \in Y, so that dw = 0. By (118),

(119) ) 3 Dif) dx; A dx; = do = 0,

Consider a fixed j, with p <j <n. Each I that occurs in (118) lies in
{1,...,p}. If I, I, are two of these k-indices, and if /; # I,, then the
(k + 1)-indices (1y,j), (I,,j) are distinct. Thus there is no cancellation,
and we conclude from (119) that every coefficient in (1i8) satisfies

(120) (D; f(x) =0 (xe E,p<j<n).
We now gather those terms in (118) that contain dx, and rewrite w
in the form
(121) w=o+y fx)dx; Adx,,
Io
where a \in Y,_,, each I, is an increasing (k - 1)-indexin {I,...,p - 1},
and I = (I,, p). By (120), Theorem 10.38 furnishes functions F; \in c'(E)
such that
(122) D,Fy=f;, D;F,=0 (p<j<n).
Put
(123) B= 2 Fix) dxy,
0

and define y = w - (-1)*"* dB. Since fis a (k - 1)-form, it follows that
p
y=w- ) 2. (D; Fx) dxy, A dx;
0J=

p-1
=o - L LDF) dx, A dx;,

which is clearly in Y,_,. Since dw =0 and d?f =0, we have dy = 0.
Our induction hypothesis shows therefore that y=du for some
(k - 1)-form pin E. If A = pu + (-1)*" 18, we conclude that w = dj.

By induction, this completes the proof.
280 PRINCIPLES OF MATHEMATICAL ANALYSIS

10.40 Theorem Fix k, | <k <n. Let Ec R" be an open set in which every
closed k-form is exact. Let T be a 1-1  \in "-mapping of E onto an open set U = R"
whose inverse S is also of class 6".

Then every closed k-form in U is exact in U.

Note that every convex open set E satisfies the present hypothesis, by
Theorem 10.39. The relation between E and U may be expressed by saying
that they are  \in "-equivalent.

Thus every closed form is exact in any set which is  \in "-equivalent to a convex
open set.

Proof Let w be a k-form in U, with dw =0. By Theorem 10.22(c),
wr is a k-form in E for which d(w;) =0. Hence wy = dA for some
(k - 1)-form A in E. By Theorem 10.23, and another application of
Theorem 10.22(c),

= (n)s = (dA) = (iy).

Since Ag is a (k - 1)-form in U, w is exact in U.

10.41 Remark In applications, cells (see D=finition 2.17) are often more con-
venient parameter domains than simplexes. If our whole development had
been based on cells rather than simplexes, the computation that occurs in the
proof of Stokes’ theorem would be even simpler. (It is done that way in Spivak’s
book.) The reason for preferring simplexes is that the definition of the boundary
of an oriented simplex seems easier and more natural than is the case for a cell.
(See Exercise 19.) Also, the partitioning of sets into simplexes (called ‘‘triangu-
lation™’) plays an important role in topology, and there are strong connections
between certain aspects of topology, on the one hand, and differential forms,
on the other. These are hinted at in Sec. 10.35. The book by Singer and Thorpe
contains a good introduction to this topic.

Since every cell can be triangulated, we may regard it as a chain. For
dimension 2, this was done in Example 10.32; for dimension 3, see Exercise 18.

Poincaré’s lemma (Theorem 10.39) can be proved in several ways. See,
for example, page 94 in Spivak’s book, or page 280 in Fleming's. Two simple
proofs for certain special cases are indicated in Exercises 24 and 27.

VECTOR ANALYSIS

We conclude this chapter with a few applications of the preceding material to
theorems concerning vector analysis in R3. These are special cases of theorems
about differential forms, but are usually stated in different terminology. We
are thus faced with the job of translating from one language to another.
INTEGRATION OF DIFFERENTIAL FORMS 281

10.42 Vector fields Let F = Fe, + Fe, + Fye; be a continuous mapping of
an open set Ec R® into R®. Since F associates a vector to each point of E, F
is sometimes called a vector field, especially in physics. With every such F is
associated a 1-form

(124) Jg=Fydx + F,dy+ Fy dz
and a 2-form
(125) wg=F dy Adz + F,dz Andx + Fydx Ady.

Here, and in the rest of this chapter, we use the customary notation (x, y, z)
in place of (x,, x,, x3).

It is clear, conversely, that every 1-form 4 in E is Ag for some vector field
Fin E, and that every 2-form w is wy for some F. In R*, the study of 1-forms
and 2-forms is thus coextensive with the study of vector fields.

If ue c'(E) is a real function, then its gradient

Vu = (D,u)e, + (Dy ule, + (Dyu)e;
is an example of a vector field in E.
Suppose now that F is a vector field in E, of class c’. Its curl V x F is the
vector field defined in E by
V x F=(D,F; - DyFy)e; + (D3 Fy - Di Fy)e; + (DF, - D, Fe;
and its divergence is the real function V - F defined in E by
V-¥=DF + D,F,+ D;F;.

These quantities have various physical interpretations. We refer to the
book by O. D. Kellogg for more details.
Here are some relations between gradients, curls, and divergences.

10.43 Theorem Suppose E is an open set in R®, ue %"(E), and G is a vector
field in E, of class C".

(a) If F=Vu, then Vx F=0.

(b) If F=V xG,thenV-F=0.

Furthermore, if E is  \in "-equivalent to a convex set, then (a) and (b) have
converses, in which we assume that F is a vector field in E, of class  \in ':

(a) IfV x F=0, then F = Vu for some ue %"(E).

0") IfV:-F=0,thenF =V x G for some vector field G in E, of class  \in "

Proof If we compare the definitions of Vu, V x F, and V + F with the

differential forms Ag and wg given by (124) and (125), we obtain the
following four statements:
282 PRINCIPLES OF MATHEMATICAL ANALYSIS

F=Vu if and only if Az =du.
VxF=0 if and only if diz =0.
F=VxG if and only if wg =dig.
V:F=0 if and only if dwg =0.

Now if F = Vu, then Ap = du, hence d1g = d*u = 0 (Theorem 10.20),
which means that V x F = 0. Thus (a) is proved.

As regards (a’), the hypothesis amounts to saying that dig = 0 in E.
By Theorem 10.40, Ag = du for some O-form u. Hence F = Vu.

The proofs of (b) and (b") follow exactly the same pattern.

10.44 Volume elements The k-form
dx; A cr A dx

is called the volume element in R*. It is often denoted by dV (or by dV, if it
seems desirable to indicate the dimension explicitly), and the notation

(126) [/® dx, A A do=[ fav

is used when ® is a positively oriented k-surface in R* and fis a continuous
function on the range of ®.

The reason for using this terminology is very simple: If D is a parameter
domain in R¥, and if ® is a 1-1 ¥’-mapping of D into R¥, with positive Jacobian
Jo, then the left side of (126) is

[ fawIs du=[ 700 dx,

by (35) and Theorem 10.9.

In particular, when f= 1, (126) defines the volume of ®. We already saw
a special case of this in (36).
The usual notation for dV, is dA.

10.45 Green’s theorem Suppose E is an open set in R*, a \in c'(E), f \in c'(E),
and Q is a closed subset of E, with positively oriented boundary 0Q, as described
in Sec. 10.31. Then

127) [ a dx + B dy) = [ fie - 2) dA.
INTEGRATION OF DIFFERENTIAL FORMS 283

Proof Put A =adx + fdy. Then
di. = (Dx) dy A dx + (Df)dx Ady
= (Df - D,a) d4,
and (127) is the same as
[a= as,
Ja IN
which is true by Theorem 10.33.
With a(x, y) = -y and f(x, y) = x, (127) becomes
(128) 3 dy-ydo=aa,
0
the area of Q.
With « = 0, 8 = x, a similar formula is obtained. Example 10.12(b) con-

tains a special case of this.

10.46 Area elements in R® Let ® be a 2-surface in R, of class ¥’, with pa-
rameter domain D = R%. Associate with each point (u, v) \in D the vector

Lng) day) dy)

Ni = .
(129) (u, v) 3 0) e; + a, 0)©? + wv) e3
The Jacobians in (129) correspond to the equation
(130) (x, y, z) = Ou, v).

If fis a continuous function on ®(D), the area integral of f over ® is
defined to be

(131) [ fad = [ £(au, v))| Nw, v)| du db.
vo D
In particular, when f= 1 we obtain the area of ®, namely,
(132) A®) = | [N(u, v)| du dv.
D

The following discussion will show that (131) and its special case (132)
are reasonable definitions. It will also describe the geometric features of the
vector N.

Write ® = c,e, + a,e, + aie3, fix a point po = (uy, vo) \in D, put
N =N(p,), put

(133) 2; = (D19)ao),  Bi=(D20)®0) (i=1,2,3)
284 PRINCIPLES OF MATHEMATICAL ANALYSIS

and let Te L(R?, R®) be the linear transformation given by
3
(134) T(u,v) = (a;u + B;v)e;.
i=1

Note that 7 = ®'(p,), in accordance with Definition 9.11.

Let us now assume that the rank of Tis 2. (If itis 1 or 0, then N = 0, and
the tangent plane mentioned below degenerates to a line or to a point.) The
range of the affine mapping

(u, v) > ®(po) + Tu, v)

is then a plane II, called the tangent plane to ® at p,. [One would like to call
IT the tangent plane at ®(p,), rather than at p, ; if ® is not one-to-one, this runs
into difficulties.]

If we use (133) in (129), we obtain

(135) N= (a; 83 - az fr)e; + (a3 By - a1 B3)es + (12 - 22 Bes,
and (134) shows that

3 3
(136) Te, =) oe;, Te, =) PBre;.
i=1 i=1

A straightforward computation now leads to
(137) N (Te) = 0=N-+(Te,).

Hence N is perpendicular to IT. It is therefore called the normal to ® at p,.
A second property of N, also verified by a direct computation based on

(135) and (136), is that the determinant of the linear transformation of R® that

takes {e,, e,, e;} to {Te,, Te,, N} is |N|? > 0 (Exercise 30). The 3-simplex

(138) [0, Te,, Te,, N]

is thus positively oriented.

The third property of N that we shall use is a consequence of the first two:
The above-mentioned determinant, whose value is |N|?, is the volume of the
parallelepiped with edges [0, Te,], [0, Te,], [0, N]. By (137), [0, N] is perpen-
dicular to the other two edges. The area of the parallelogram with vertices

(139) 0, Tey, Tey, Tle, + c;)

is therefore |NJ|.

This parallelogram is the image under T of the unit square in R%. If E
is any rectangle in R?, it follows (by the linearity of 7) that the area of the
parallelogram T(E) is

(140) A(T(E)) = |N| A(E) = [] Nu, vo)| du do.
INTEGRATION OF DIFFERENTIAL FORMS 285

We conclude that (132) is correct when ® is affine. To justify the definition
(132) in the general case, divide D into small rectangles, pick a point (ug, vo)
in each, and replace ® in each rectangle by the corresponding tangent plane.
The sum of the areas of the resulting parallelograms, obtained via (140), is then
an approximation to A(®). Finally, one can justify (131) from (132) by approxi-
mating f by step functions.

10.47 Example Let 0 <a <b be fixed. Let K be the 3-cell determined by

0<t<a, 0<u<2n, 0<v<2nm
The equations
X=tcosu
(141) y=(b+tsinu)cosv

z=(b+tsinu)sinv

describe a mapping ¥ of R? into R*® which is I-1 in the interior of K, such that
Y(K) is a solid torus. Its Jacobian is

_ 0x, p, 2)

fo = at, u, v)

=t(b + tsinu)
which is positive on K, except on the face = 0. If we integrate Jy over K, we
obtain

vol (W(K)) = 2n’a’b

as the volume of our solid torus.

Now consider the 2-chain ® = dW. (See Exercise 19.) ¥ maps the faces
u = 0 and u = 2n of K onto the same cylindrical strip, but with opposite orienta-
tions. W¥ maps the faces v = 0 and v = 2m onto the same circular disc, but with
opposite orientations. ¥ maps the face r = 0 onto a circle, which contributes 0
to the 2-chain c¥. (The relevant Jacobians are 0.) Thus ® is simply the 2-surface
obtained by setting + = a in (141), with parameter domain D the square defined
by0<u<2m 0<v<2nm

According to (129) and (141), the normal to ® at (4, v) \in D is thus the
vector

N(u, v) = a(b + a sin u)n(u, v)
where

n(u, v) = (cos u)e, + (sin u cos v)e, + (sin u sin v)e;.
286 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since |n(u, v)| = 1, we have |N(u, v)| = a(b + a sin u), and if we integrate this
over D, (131) gives

A(®) = 4n’ab

as the surface area of our torus.

If we think of N= N(u, v) as a directed line segment, pointing from
®(u, v) to Ou, v) + N(u, v), then N points outward, that is to say, away from
Y(K). This is so because Jy > 0 when t = a.

For example, take u = v = n/2, t = a. This gives the largest value of z on
Y(K), and N = a(b + a)e; points “upward” for this choice of (u, v).

10.48 Integrals of 1-forms in R®> Let y be a %’-curve in an open set E = R3,
with parameter interval [0, 1], let F be a vector field in E, as in Sec. 10.42, and
define Ag by (124). The integral of Ag over y can be rewritten in a certain way
which we now describe.

For any u  \in [0, 1],

VW) = vi(we, + v2(wes + y3(u)es

is called the tangent vector to y at u. We define t = t(u) to be the unit vector in
the direction of y’(x). Thus

Yu) = yw) tw).

[If y'(u) = 0 for some u, put t(u) = e,; any other choice would do just as well.]
By (35),

N 3 a1
[2e=3 | Fly du
vy i=1v0

(142) = J FO) + du

= J, FO) - 1) ya)| du

Theorem 6.27 makes it reasonable to call |y'(u)| du the element of arc
length along y. A customary notation for it is ds, and (142) is rewritten in the
form

(143) [2=[®-vas

Since t is a unit tangent vector to y, F + tis called the tangential component
of F along y.
INTEGRATION OF DIFFERENTIAL FORMS 287

The right side of (143) should be regarded as just an abbreviation for the
last integral in (142). The point is that F is defined on the range of y, but t is
defined on [0, 1]; thus F + t has to be properly interpreted. Of course, when y
is one-to-one, then t(x) can be replaced by t(y(x)), and this difficulty disappears.

10.49 Integrals of 2-forms in R> Let ® be a 2-surface in an open set E = R3,
of class 4’, with parameter domain D < R?. Let F be a vector field in E, and
define wg by (125). As in the preceding section, we shall obtain a different
representation of the integral of wg over ®.

By (35) and (129),

[ Wp = [ (Fi dy Adz + Fydz A dx + Fy dx A dy)
Yo Yo

du dv

= | \ o ®) 8», 2) + (Fo) (z, x) + (Fo 0) a(x, y)|

au, v) au, v) au, v)l
= [ F(®(u, v)) * N(u, v) du dv.
YD
Now let n=n(u, v) be the unit vector in the direction of N(u, v). [If

N(u, v) = 0 for some (u, v) \in D, take n(u, v) = e,.] Then N= |N|n, and there-
fore the last integral becomes

[ F(®(u, v)) * n(u, v)|N(u, v)| du dv.

*D
By (131), we can finally write this in the form
(144) [(wp=[ (F-n)da.

Yo Yo

With regard to the meaning of F + n, the remark made at the end of Sec. 10.48

applies here as well.
We can now state the original form of Stokes’ theorem.

10.50 Stokes’ formula If F is a vector field of class  \in ' in an open set E = R3,
and if ® is a 2-surface of class  \in " in E, then

(145) [o x F) ndd = [ -1) ds.

Proof Put H=V x F. Then, as in the proof of Theorem 10.43, we have

(146) wg = diy.
288 PRINCIPLES OF MATHEMATICAL ANALYSIS

Hence

[xP mdd=] aH-mas= | po.
[J

= J dre = [e=] E10 ds.

Here we used the definition of H, then (144) with H in place of F,
then (146), then-the main step-Theorem 10.33, and finally (143),
extended in the obvious way from curves to 1-chains.

10.51 The divergence theorem If F is a vector field of class  \in ' in an open set
Ec R? and if Q is a closed subset of E with positively oriented boundary 0S
(as described in Sec. 10.31) then

(147) | (V-F)dV=| (F-n)dd.
Q vo
Proof By (125),
dog= (VV -F)dx Andy Andz=(V-F)dV.
Hence

I (V-F)dv= I. dog = [ wg = I. (F + n) dA,

by Theorem 10.33, applied to the 2-form wg, and (144).

EXERCISES

1. Let H be a compact convex set in R¥, with nonempty interior. Let fe  \in (H), put
f(x) =0 in the complement of H, and define { fas in Definition 10.3.
Prove that | f is independent of the order in which the k integrations are
carried out.
Hint: Approximate f by functions that are continuous on R* and whose
supports are in H, as was done in Example 10.4.
2. Fori=1,2,3,..., let c, \in  \in (R") have support in (27!,2'~", such that fe, =1.
Put

f5,3) = 2 [90 = peri)

Then f has compact support in R?, fis continuous except at (0, 0), and
[dy [fx ) dx =0 but [ax [repr dy=1.

Observe that fis unbounded in every neighborhood of (0, 0).
INTEGRATION OF DIFFERENTIAL FORMS 289

3. (a) If Fis as in Theorem 10.7, put A = F'(0), F;(x) = A~'F(x). Then Fi(0)= I.
Show that

Fi(x) = Gro Garo +0 G(X)

in some neighborhood of 0, for certain primitive mappings G,,..., G,. This
gives another version of Theorem 10.7:

F(x) =F (0)G,° G,_; 0" 0 G(x).

(b) Prove that the mapping (x, y) = (», x) of R? onto R? is not the composition
of any two primitive mappings, in any neighborhood of the origin. (This shows
that the flips B; cannot be omitted from the statement of Theorem 10.7.)

4. For (x, y) \in R?, define

F(x, y) = (e* cosy - 1, e* sin y).
Prove that F = G, o G,, where
Gi(x,y)=(e*cosy- 1, )
G(u, v) = (u, (1 + u) tan v)

are primitive in some neighborhood of (0, 0).
Compute the Jacobians of G;, G,, F at (0, 0). Define

H(x, y) = (x, e sin y)
and find
H,(u, v) = (h(u, v), v)

so that F = H, o H, is some neighborhood of (0, 0).

5. Formulate and prove an analogue of Theorem 10.8, in which K is a compact
subset of an arbitrary metric space. (Replace the functions c; that occur in the
proof of Theorem 10.8 by functions of the type constructed in Exercise 22 of
Chap. 4.)

6. Strengthen the conclusion of Theorem 10.8 by showing that the functions i; can
be made differentiable, and even infinitely differentiable. (Use Exercise 1 of
Chap. 8 in the construction of the auxiliary functions g;.)

7. (a) Show that the simplex Q* is the smallest convex subset of R* that contains
0,e,...,6 \in .

(b) Show that affine mappings take convex sets to convex sets.

8. Let H be the parallelogram in R? whose vertices are (1, 1), (3, 2), (4, 5), (2, 4).
Find the affine map 7 which sends (0, 0) to (1, 1), (1, 0) to (3, 2), (0, 1) to (2, 4).
Show that Jr = 5. Use T to convert the integral

a= e*~Vdx dy
H

to an integral over I? and thus compute «.
290 PRINCIPLES OF MATHEMATICAL ANALYSIS

9.

10.

11.

12.

Define (x, y) = T(r, 0) on the rectangle
0<r<a, 0<f<2m
by the equations
x =rcosf, y=rsinf.
Show that 7 maps this rectangle onto the closed disc D with center at (0, 0) and

radius a, that 7 is one-to-one in the interior of the rectangle, and that Jr(r, 6) =r.
If f \in  \in (D), prove the formula for integration in polar coordinates:

ra pan
[RL ydxdy = J I (T(r, O)r dr db.

Hint: Let Do be the interior of D, minus the interval from (0, 0) to (0, a).
As it stands, Theorem 10.9 applies to continuous functions f whose support lies in
Do. To remove this restriction, proceed as in Example 10.4.
Let a - oo in Exercise 9 and prove that

wo 2n
| Gey) dy = [ [ FTC, O))r dr db,

for continuous functions f that decrease sufficiently rapidly as|x| + |y| -> ©.
(Find a more precise formulation.) Apply this to
f(x,y) = exp (-x* -y?)
to derive formula (101) of Chap. 8.
Define (u, v) = T(s, t) on the strip
0<s< oo, 0<r<l1
by setting u = 5s - st, v = st. Show that 7 is a 1-1 mapping of the strip onto the
positive quadrant Q in R*. Show that Jz(s, 1) = s.
For x > 0, y > 0, integrate
wx le-upy-le-v
over Q, use Theorem 10.9 to convert the integral to one over the strip, and derive
formula (96) of Chap. 8 in this way.
(For this application, Theorem 10.9 has to be extended so as to cover certain
improper integrals. Provide this extension.)
Let I* be the set of all u= (uy, ..., uw) \in R* with 0 <u; <1 for all i; let Q* be the
set of all x = (xy, ..., xx) \in R* with x, >0, =x; <1. (I* is the unit cube; Q* is
the standard simplex in R*.) Define x = 7T(u) by
X1 =U
x2 = (1 - uu,

Xe= (=u) (1 - thmr)ltsc.
13.

14.
15.

16.

17.

18.

INTEGRATION OF DIFFERENTIAL FORMS 291

Show that
k k
> xi=1-T101- wu).
I=1 i=1
Show that T maps I* onto Q*, that Tis 1-1 in the interior of I*, and that its
inverse S is defined in the interior of Q* by u; = x; and

Xi
fori=2,...,k. Show that

Jr) = (1 - uM =u)! 2+ (1 - wea),
and

Js) =[1 =x) -x1- x2) (I -xs = - x9] 7h

Let ry, ..., r, be nonnegative integers, and prove that

riled

Fl... xk rr
[= a ax k+ri+- +r!

Hint: Use Exercise 12, Theorems 10.9 and 8.20.

Note that the special case ry = ++ =r, = 0 shows that the volume of Q*
is 1/k!.
Prove formula (46).
If w and A are k- and m-forms, respectively, prove that

w AA=(=1)"A A w.

If k >2 and 0 = [po, pi, - . ., Pi] is an oriented affine k-simplex, prove that 2g = 0,
directly from the definition of the boundary operator &. Deduce from this that
&*¥ = 0 for every chain ¥'.

Hint: For orientation, do it first for k = 2, k = 3. In general, if i <j, let a
be the (kK - 2)-simplex obtained by deleting p, and p, from o. Show that each oy;
occurs twice in c%0, with opposite sign.

Put J? = 7, + 7,, where

71 =1[0,e.,e +e], 7,=-[0,e;,e, +e].
Explain why it is reasonable to call J? the positively oriented unit square in R2,
Show that J? is the sum of 4 oriented affine 1-simplexes. Find these. What is
ory - 72)?

Consider the oriented affine 3-simplex

or =[0,e,e +e, e; +e, + es]

in R3. Show that o, (regarded as a linear transformation) has determinant 1.
Thus o, is positively oriented.
292 PRINCIPLES OF MATHEMATICAL ANALYSIS

19.

20.

21.

Let 0,,...,06 be five other oriented 3-simplexes, obtained as follows:
There are five permutations (is, i», 73) of (1, 2, 3), distinct from (1, 2, 3). Associate
with each (iy, i, 73) the simplex

(is, 13, 13)[0, 1,  \in 1y + \in iy,  \in y +  \in ; + 55]

where s is the sign that occurs in the definition of the determinant. (This is how 7,
was obtained from 7, in Exercise 17.)

Show that o,, ..., os are positively oriented.

Put J3= 0, +++ + 0s. Then J? may be called the positively oriented unit
cube in R?3,

Show that aJ2 is the sum of 12 oriented affine 2-simplexes. (These 12 tri-
angles cover the surface of the unit cube 73.)

Show that x = (x, x2, x3) is in the range of o, if and only if 0 < x3 <x:
<a 1.

Show that the ranges of oy, ..., 0s have disjoint interiors, and that their
union covers 13. (Compare with Exercise 13; note that 3! = 6.)
Let J2 and J? be as in Exercise 17 and 18. Define

Boi (u,v) = (0, u, v), Byy(u,v)= (1, u,v),
Bou, v) = (4,0,0),  Bi(u,v)=(u, 1,0),
Bos(u, v) = (u,v,0),  Bis(u,v) = (u,v, 1).

These are affine, and map R? into R3.
Put B8,,=B.(J?), for r=0,1,i=1,2,3. Each 8, is an affine-oriented
2-chain. (See Sec. 10.30.) Verify that

a= (= 1/Boi- Bu),

in agreement with Exercise 18.
State conditions under which the formula

[fdo=] fo-[ a ne

is valid, and show that it generalizes the formula for integration by parts.
Hint: d(fw)= (df) N w+ fdw.
As in Example 10.36, consider the 1-form
xdy -ydx
= "x2 Ty?
in R? - {0}.
(a) Carry out the computation that leads to formula (113), and prove that dn = 0.

(b) Let y(t) = (r cos t, r sin t), for some r > 0, and let I" be a ¥"-curve in R? - {0},
INTEGRATION OF DIFFERENTIAL FORMS 293

with parameter interval [0, 27], with T'(0) = I'(2m), such that the intervals [(r),
T'(1)] do not contain 0 for any r  \in [0, 27]. Prove that

[= = 2m.

Hint: For 0 <r <2m, 0 <u <1, define
Ot, u) = (1 - u) T(t) + w(t).

Then a is a 2-surface in R? - {0} whose parameter domain is the indicated rect-
angle. Because of cancellations (as in Example 10.32),

oD =1"-1y.

Use Stokes’ theorem to deduce that

J K ) ki
r 7
because dn = 0.

(c) Take I'(1)=(acost, bsint) where a>0,b>0 are fixed. Use part (b) to
show that

[ ab dt = 2m,

Jo a*cos? t+ b?sin®t

(d) Show that
y
=d tan=
7 (or an 2)
in any convex open set in which x # 0, and that
X
=d| - arc tan-
1a are)

in any convex open set in which y #0.
Explain why this justifies the notation » = d#, in spite of the fact that 7 is
not exact in R? - {0}.

(e) Show that (b) can be derived from (d).
(f) If I is any closed %’-curve in R? - {0}, prove that

1 ~
- = Ind(T).
2] 7 nd(T)

(See Exercise 23 of Chap. 8 for the definition of the index of a curve.)
294 PRINCIPLES OF MATHEMATICAL ANALYSIS

22. As in Example 10.37, define { in R® - {0} by

_xdy Ndz+ydz Ndx+zdx Ndy
=

{
where r = (x? + y% + 2z2)'/2, let D be the rectangle given by 0 <u <m, 0 <v < 2m,
and let ¥ be the 2-surface in R3, with parameter domain D, given by

Xx = sin u cos v, y=sinusinv, Z = COS U.

(a) Prove that d{ =0 in R® - {0}.

(b) Let S denote the restriction of T to a parameter domain E < D. Prove that
[t=] sinududo= acs),
s JE
where A denotes area, as in Sec. 10.43. Note that this contains (115) as a special

case.

(c) Suppose g, hy, h,, hs, are  \in ”-functions on [0, 1], g > 0. Let (x, y, z) = O(s, 1)
define a 2-surface ®, with parameter domain 7%, by

x=g(Ohi(s), y=gOhs), z=g(Dhs(s).

Prove that

[=o
o
directly from (35).
Note the shape of the range of ®a: For fixed s, ®(s, 7) runs over an interval
on a line through 0. The range of ® thus lies in a “cone” with vertex at the origin.

(d) Let E be a closed rectangle in D, with edges parallel to those of D. Suppose
fe¥"(D),f>0. Let Q be the 2-surface with parameter domain E, defined by

Qu, v) = f(u, v) = (4, v).
Define S as in (b) and prove that

[=] =a.

(Since S is the “radial projection” of Q into the unit sphere, this result makes it
reasonable to call {af the “solid angle” subtended by the range of Q at the origin.)
Hint: Consider the 3-surface ¥ given by

W(t, u,v) = [1 - t+ tf(u, v)] = (u, v),

where (4, v) \in E,0 <1 <1. For fixed v, the mapping (1, u) > W(t, u, v) is a 2-sur-
23.

INTEGRATION OF DIFFERENTIAL FORMS 295

face ® to which (c) can be applied to show that fol = 0. The same thing holds
when u is fixed. By (a) and Stokes’ theorem,

[ c= [Laz=o.

(e) Put A= - (z/r)y, where
_xdy-ydx
Tx? +?

’

as in Exercise 21. Then A is a 1-form in the open set ¥ = R? in which x? 4 2 > 0.
Show that { is exact in V by showing that

{=dA

(f) Derive (d) from (e), without using (c).
Hint: To begin with, assume 0 <u <m on E. By (e),

[e=] 2 and [i=] n

Show that the two integrals of A are equal, by using part (d) of Exercise 21, and by
noting that z/r is the same at Z(u, v) as at Qu, v).

(9) Is { exact in the complement of every line through the origin?
Fix n. Define r= (x} + +++ + x})V/? for 1 <k <n, let E, be the set of all x \in R"
at which r, > 0, and let w, be the (k - 1)-form defined in E, by

k
w= (rd Zo (=D! 'xedxy Avo Adxiog Adxisr Aves A dx.

Note that w, = 3, ws = {, in the terminology of Exercises 21 and 22. Note
also that
E,cE,c-cE,=R"-{0}.
(a) Prove that dw, = 0 in E,.
(b) For k =2,...,n, prove that w, is exact in E,_,, by showing that
wx = d(fiwx-1) = (df) A wi_y,
where f(x) = (- 1)* gu(x,/r) and

alt) = [ (-sHe=dgs  (-1<t<l).
-1

Hint: f, satisfies the differential equations
x (Vf)x)=0
and

(DufX) = ph :
ri)
296 PRINCIPLES OF MATHEMATICAL ANALYSIS

24.

25.

26.

27.

(c) Is w, exact in E,?
(d) Note that (b) is a generalization of part (e) of Exercise 22. Try to extend some
of the other assertions of Exercises 21 and 22 to w,, for arbitrary n.

Let w =Xai(x) dx; be a 1-form of class ¥” in a convex open set E < R". Assume
dw = 0 and prove that w is exact in E, by completing the following outline:
Fix p \in E. Define

f= wo «ch.

[P.X]

Apply Stokes’ theorem to affine-oriented 2-simplexes [p, x, y] in E. Deduce that
n 1
SO =f = 300 -x) [ all = 0x + ty) de
= 0

for x \in E, y \in E. Hence (D;f)(x) = a(x).

Assume that w is a 1-form in an open set E = R" such that

[w=0

for every closed curve y in E, of class ’. Prove that w is exact in E, by imitating
part of the argument sketched in Exercise 24.

Assume w is a 1-form in R® - {0}, of class c” and dw =0. Prove that w is exact in
RR? - {0}.

Hint: Every closed continuously differentiable curve in R®- {0} is the
boundary of a 2-surface in R® - {0}. Apply Stokes’ theorem and Exercise 25.

Let E be an open 3-cell in R3, with edges parallel to the coordinate axes. Suppose
(a,b,c) \in E, fie? (E)fori=1,2,3,

w=f1dy Ndz+f,dz \dx + fs dx Ady,
and assume that dw = 0 in E. Define
A=gidx+g.dy

where
z y
a3 =[ fx yds -[ fixed
c b
9:5, 3,2) = - [ fil, v5) ds,
for (x, y,z) \in E. Prove that dA= w in E.

Evaluate these integrals when w = { and thus find the form A that occurs in
part (e) of Exercise 22.
28.

29.

30.

31.

INTEGRATION OF DIFFERENTIAL FORMS 297

Fix b >a > 0, define
a(r, 0) = (r cos 0, r sin 6)

for a <r <b,0<6 <2m. (The range of ® is an annulus in R%) Put w = x3 dy,
and compute both

to verify that they are equal.

Prove the existence of a function « with the properties needed in the proof of
Theorem 10.38, and prove that the resulting function F is of class c’. (Both
assertions become trivial if E is an open cell or an open ball, since « can then be
taken to be a constant. Refer to Theorem 9.42.)

If N is the vector given by (135), prove that

xy B. a2fs - asf
det oa B: asf - af

x3 Bs ofa - asf

~ IN|.

Also, verify Eq. (137).
Let E < R? be open, suppose g \in  \in "(E), h c  \in ”(E), and consider the vector field
F=gVh.
(a) Prove that
V-F=gV*+ (Sg) (Yh)
where V2h = VU - (Vh) = Sé2h/cxt is the so-called “Laplacian” of 4.

(b) If © is a closed subset of E with positively oriented boundary cQ (as in
Theorem 10.51), prove that

N ch
[toven+ So) hwy =| g7 da
fe] von

where (as is customary) we have written ch/én in place of (VA) -n. (Thus éh/én
is the directional derivative of 4 in the direction of the outward normal to c \in , the
so-called normal derivative of h.) Interchange g and #4, subtract the resulting
formula from the first one, to obtain

ch
[ (g¥2h- hv) av =| (+3 ! 2) dA.
Ja a \ on on
These two formulas are usually called Green's identities.
(c) Assume that A is harmonic in E; this means that V2 = 0. Take g = 1 and con-
clude that
| eh ga -o.
[4

a on
298 PRINCIPLES OF MATHEMATICAL ANALYSIS

32.

Take g = h, and conclude that # = 0 in Q if A = 0 on 2Q.
(d) Show that Green’s identities are also valid in R2.

Fix 8,0 <8 <1. Let Dbethesetofall (6, t) \in R*suchthat0 <0 <m, -8 <r<8.
Let ®a be the 2-surface in R?, with parameter domain D, given by

x = (1 - tsin 6) cos 20
y= (1 - tsin 0) sin 20
z=tcos 0

where (x, y, z) = ®(0, t). Note that ®(m, t) = ®(0, -1t), and that ® is one-to-one
on the rest of D.

The range M = ®(D) of ® is known as a Mdbius band. 1t is the simplest
example of a nonorientable surface.

Prove the various assertions made in the following description: Put
p= (0, =8), p> = (m, =8), ps = (7, 8), ps = (0, 8), ps = ps. Put yi=[p:, pi+1],
i=1,...,4,and put T', = ®oy,. Then

oO =T,+T,+T3+T,.
Puta= (1,0, -8),b=(1,0, 8). Then
Op) =P(ps) =a,  O(p2)=D(ps)=b,

and o® can be described as follows.

I", spirals up from a to b; its projection into the (x, y)-plane has winding
number +1 around the origin. (See Exercise 23, Chap. 8.)

T', = [b, a].

I"; spirals up from a to b; its projection into the (x, y) plane has winding
number - 1 around the origin.

I'y = [b, a].

Thus o® =I", + T'; + 2T',.

If we go from a to b along I'; and continue along the “edge” of M until we
return to a, the curve traced out is

I=I,-T1%,,
which may also be represented on the parameter interval [0, 27] by the equations

x = (1 + 8 sin 6) cos 20
y= (1+ 8 sin 0) sin 26
z= -38cos 6.

It should be emphasized that I" # é®: Let n be the 1-form discussed in
Exercises 21 and 22. Since dn = 0, Stokes’ theorem shows that
INTEGRATION OF DIFFERENTIAL FORMS 299

But although T is the “geometric” boundary of M, we have

[ n = 4a.

In order to avoid this possible source of confusion, Stokes’ formula (Theorem
10.50) is frequently stated only for orientable surfaces ®.
11

THE LEBESGUE THEORY

It is the purpose of this chapter to present the fundamental concepts of the
Lebesgue theory of measure and integration and to prove some of the crucial
theorems in a rather general setting, without obscuring the main lines of the
development by a mass of comparatively trivial detail. Therefore proofs are
only sketched in some cases, and some of the easier propositions are stated
without proof. However, the reader who has become familiar with the tech-
niques used in the preceding chapters will certainly find no difficulty in supply-
ing the missing steps.

The theory of the Lebesgue integral can be developed in several distinct
ways. Only one of these methods will be discussed here. For alternative
procedures we refer to the more specialized treatises on integration listed in
the Bibliography.

SET FUNCTIONS

If 4 and B are any two sets, we write A - B for the set of all elements x such
that x \in A, x c B. The notation 4 - B does not imply that B = 4. We denote
the empty set by 0, and say that 4 and B are disjoint if An B=0.
THE LEBESGUE THEORY 301

11.1 Definition A family # of sets is called a ring if A \in # and B \in Z implies
(1) AU Be, A-BeA.
Since A "B= A - (A - B), we also have A n Be Z if # is a ring.
A ring 2 is called a g-ring if
2 UA, ez
n=1

whenever A, e Z (n=1,2,3,...). Since

NAn=di= J (4 = 4),

we also have

if Z is a o-ring.

11.2 Definition We say that c is a set function defined on Z if c assigns to
every A \in # a number c(A) of the extended real number system. c is additive
if A n B=0 implies

3) c(4 © B) = §(4) + c(B),
and c is countably additive if A; n A; = 0 (i # J) implies

oc 0
a # (04) = oan.

We shall always assume that the range of c does not contain both + oo
and - oo; for if it did, the right side of (3) could become meaningless. Also,
we exclude set functions whose only value is +00 or - oo.

It is interesting to note that the left side of (4) is independent of the order
in which the A4,’s are arranged. Hence the rearrangement theorem shows that
the right side of (4) converges absolutely if it converges at all; if it does not
converge, the partial sums tend to + oo, or to - co.

If c is additive, the following properties are easily verified:

® $0) =0.
© PlAy0 ud) = GA) + + P(4,)
if A; n A; = 0 whenever i # J.
302 PRINCIPLES OF MATHEMATICAL ANALYSIS

M H(A; L 42) + c(4; Nn Ay) = c(4) + (4).
If c(4) = 0 for all 4, and 4, c= 4,, then
8) #4) < c(4,).

Because of (8), nonnegative additive set functions are often called
monotonic.

©) $(4 - B) = cp(4) - c(B)
if Bc 4, and |(cB)| < + ©.

11.3 Theorem Suppose c is countably additive on a ring R. Suppose A, \in R
n=1,23,..),A4,cA,c Ay, A \in eR, and

A= U4.
Then, as n - 0,
a(4,) => c(A).
Proof Put B, = A4,, and
B,=A,-A,_, (1=23..).
Then B,nB;=0fori#j,A,=B, vu B,, and 4 = |JB,. Hence

$d) = Y 48)
and

94) = 3 48).

CONSTRUCTION OF THE LEBESGUE MEASURE

11.4 Definition Let R? denote p-dimensional euclidean space. By an interval
in R” we mean the set of points Xx = (xy, ..., x,) such that

(10) a; <x; <b; (=1..,p)

or the set of points which is characterized by (10) with any or all of the <
signs replaced by <. The possibility that a; = b; for any value of / is not ruled
out; in particular, the empty set is included among the intervals.
THE LEBESGUE THEORY 303

If A is the union of a finite number of intervals, 4 is said to be an elemen-
tary set.
If I'is an interval, we define

mit) = [1 (6: = ap.

no matter whether equality is included or excluded in any of the inequalities (10).
If A=1, u-- ul, and if these intervals are pairwise disjoint, we set
an m4) = ml) + ++ + m(I).
We let & denote the family of all elementary subsets of RP”.
At this point, the following properties should be verified:
(12) c&is a ring, but not a o-ring.
(13) If A  \in &, then A is the union of a finite number of disjoint intervals.
(14) If A \in & m(A) is well defined by (11); that is, if two different decompo-
sitions of A into disjoint intervals are used, each gives rise to the same
value of m(A).
(15) m is additive on &.

Note that if p = 1, 2, 3, then m is length, area, and volume, respectively.

11.5 Definition A nonnegative additive set function c defined on & is said to
be regular if the following is true: To every A \in & and to every c > 0 there
exist sets F \in &, G \in & such that Fis closed, G is open, F< 4 = G, and

(16) dG) -e < P(A) < o(F) +e.

11.6 Examples

(a) The set function m is regular.
If 4 is an interval, it is trivial that the requirements of Definition

11.5 are satisfied. The general case follows from (13).
(b) Take R?=R!, and let « be a monotonically increasing func-
tion, defined for all real x. Put

ula, b)) = a(b-) - aa-),

ula, b)) = a(b+) - ala-),

ua, b]) = a(b+) - x(a +),

u((a, b)) = a(b-) - a(a+).
Here [a, b) is the set a <x <b, etc. Because of the possible discon-
tinuities of a, these cases have to be distinguished. If u is defined for
304 PRINCIPLES OF MATHEMATICAL ANALYSIS

clementary sets as in (11), u is regular on &. The proof is just like that
of (a).

Our next objective is to show that every regular set function on & can be
extended to a countably additive set function on a o-ring which contains §&.

11.7 Definition Let u be additive, regular, nonnegative, and finite on &.
Consider countable coverings of any set E < RP by open elementary sets A4,:

Ec |JA4,
n=1
Define
(17) WHE) = inf u(4,),

the inf being taken over all countable coverings of E by open elementary sets.
W*(E) is called the outer measure of E, corresponding to pu.
It is clear that u*(E) > 0 for all £ and that

(18) WHE) < p*(E,)
if E, c E,.

11.8 Theorem

(a) For every A \in &, p*(A4) = u(A).
(b) IfE=|JE,, then
1

(19) WHE) < 3 WHE).
=
Note that (a) asserts that p* is an extension of u from & to the family of
all subsets of RP. The property (19) is called subadditivity.
Proof Choose A  \in 6 and c > 0.

The regularity of yu shows that A is contained in an open elementary
set G such that u(G) < u(A4) +e. Since p*(4) < u(G) and since c was
arbitrary, we have

(20) w*(A) < (A).
The definition of p* shows that there is a sequence {4,} of open

elementary sets whose union contains A, such that

Sua) < WA) +e.
THE LEBESGUE THEORY 305

The regularity of x shows that 4 contains a closed elementary set F such
that u(F) > u(A4) - c; and since F is compact, we have

Fc Au Udy

for some N. Hence
N
PA) Sp(F)+e<p(dy ur Udy)+e<Y u(d,) +e < pA) + 2.
1

In conjunction with (20), this proves (a).

Next, suppose E = | JE,, and assume that u*(E,) < + oo for all a.
Given c > 0, there are coverings {Au}, k=1,2,3,..., of E, by open
elementary sets such that

an (A) < WHE) +27".

p18

Then
KES YY HAS LIME) +

and (19) follows. In the excluded case, i.e., if u*(E,) =+ oo for some a,
(19) is of course trivial.

11.9 Definition For any 4 = RP, Bc RP, we define

(22) S(4, B)=(4 - B)u (B- A),
(23) d(A, B) = pu*(S(A, B)).
We write 4, > 4 if
lim d(A4, 4,) =0.

If there is a sequence {4,} of elementary sets such that 4, » A, we say
that A is finitely y-measurable and write 4 \in Mp(p).

If A is the union of a countable collection of finitely y-measurable sets,
we say that A4 is u-measurable and write 4 \in M(w).

S(A, B) is the so-called “symmetric difference” of 4 and B. We shall see
that d(A4, B) is essentially a distance function.

The following theorem will enable us to obtain the desired extension of yu.

11.10 Theorem MN(u) is a o-ring, and p* is countably additive on M(p).

Before we turn to the proof of this theorem, we develop some of the
properties of S(4, B) and d(A, B). We have
306 PRINCIPLES OF MATHEMATICAL ANALYSIS

(24) S(A, B) = S(B, 4),  S(4, 4) =0.

(25) S(4, B) = S(4, C) u S(C, B).
S(4; U A4,, B, U By)

(26) S(A, Nn A,, B, nn By); © S(4;, By) u S(4,, B,).
S(4, - A, B, - 5)

(24) is clear, and (25) follows from
(A-B)c(A-C)u(C-B), (B-A)c(C-A)u(B-C).
The first formula of (26) is obtained from
(4, U A4,)-(B, vu B,) =(A4, - B)) vu (4, - B)).

Next, writing £c for the complement of £, we have

S(4, n A4,, By 0 B,) = S(A{ v AS, Bf u BS)

c S(44, BY) u S(45, BS) = S(4,, B,) u S(4,, B,);
and the last formula of (26) is obtained if we note that
A - A, =A, 0 45.
By (23), (19), and (18), these properties of S(4, B) imply

7) d(A, B)=d(B, A),  d(A, A) =0,
(28) d(4, B) < d(A, C) + d(C, B),
d(A, v A,, B, U B,)
29) d(4y 0 4;, By 0 By) <d(Ay, By) + d(4;, By).

dA, - 4, By, - B,)

The relations (27) and (28) show that d(A4, B) satisfies the requirements
of Definition 2.15, except that d(4, B) = 0 does not imply 4 = B. For instance,
if pu =m, A is countable, and B is empty, we have

d(A, B) = m*(4) = 0;
to see this, cover the nth point of 4 by an interval 7, such that
m(l,) <2".
But if we define two sets 4 and B to be equivalent, provided
d(4, B) =0,

we divide the subsets of RP” into equivalence classes, and d(A4, B) makes the set
of these equivalence classes into a metric space. (ut) is then obtained as the
closure of &. This interpretation is not essential for the proof, but it explains
the underlying idea.
THE LEBESGUE THEORY 307

We need one more property of d(A4, B), namely,
(30) [u*(A) - pX(B)| < d(4, B),
if at least one of u*(4), u*(B) is finite. For suppose 0 < u*(B) < u*(4).
Then (28) shows that
d(4,0)<d(A, B)+ d(B, 0),
that is,
u*(A4) <d(4, B) + u*(B).
Since p*(B) is finite, it follows that
u*(A4) - p(B) < d(4, B).

Proof of Theorem 11.10 Suppose A \in Mp(u), B \in M(x). Choose {4,},
{B,} such that 4, \in c&. B, \in &, A, > A, B,-> B. Then (29) and (30) show

that

(31) A,vu B,»>AUB,

(32) A,nB,->A nN B,

(33) A,- B,-»A-B,

(34) uH(A,) = pA),
and p*(4) < + oo since d(4,, A) »0. By (31) and (33), Mx(u) is a ring.
By (7),

WA) + u(B,) = (4, v B,) + u(4, Nn B,).
Letting n - oo, we obtain, by (34) and Theorem 11.8(a),
u*(A4) + p*(B) = p*(4 v B) + p*(4 n B).

If An B=0, then u*(4 n B) =0.

It follows that p* is additive on M p(n).

Now let 4 \in M(u). Then A can be represented as the union of a
countable collection of disjoint sets of Me(u). For if A=|)A, with
A; \in Mp(pn), write A; = A, and

A,=(A{v- vd) -Auvud yy) (=234..).
Then

(335) A=]4,
n=1
is the required representation. By (19)

(36) WA < SHA)
308 PRINCIPLES OF MATHEMATICAL ANALYSIS

(37

(38)

On the other hand, 4 © 4; U + U 4,; and by the additivity of
u* on My(u) we obtain

PHA) = p*(Ay © cr UA) = pr(Ay) + + pt(Ay).
Equations (36) and (37) imply

WHA) = Su)

Suppose p*(A) is finite. Put B, = A, U + U A4,. Then (38) shows
that

di, BY =u [) 4)= 3 wd) =0

as n- co. Hence B,- A; and since B, \in My(p), it is easily seen that
Ae Me(w).
We have thus shown that 4 \in Mp(u) if 4 \in M(u) and p*(4) < + oo.
It is now clear that p* is countably additive on M(u). For if

A=J4,,

where {4,} is a sequence of disjoint sets of M(x), we have shown that (38)
holds if u*(A4,) < + oo for every n, and in the other case (38) is trivial.

Finally, we have to show that M(u) is a o-ring. If 4, e Mw), n=1,
2,3, ..., itis clear that U A, \in M(u) (Theorem 2.12). Suppose A \in M(p),
Be M(u), and

0 Ee
A={4, B=UB,
n=1

Ed
Il
-

where A4,, B, \in Me(p). Then the identity
A,nB=|J (4,0 B)
i=1
shows that 4, Nn B \in M(y); and since

p*(A4, NB) < p*(4,) < + oo,

A, Nn BeW(n). Hence A,- BeMg(u), and A - BeM(u) since
A-B=J= (4, B).

We now replace pu*(4) by p(A) if 4  \in e M(u). Thus yu, originally only de-

fined on &, is extended to a countably additive set function on the o-ring
M(u). This extended set function is called a measure. The special case up =m
is called the Lebesgue measure on RP”.
THE LEBESGUE THEORY 309

11.11 Remarks

(39)

(40)

(a) If Ais open, then 4 \in M(1). For every open set in RP? is the union
of a countable collection of open intervals. To see this, it is sufficient to
construct a countable base whose members are open intervals.

By taking complements, it follows that every closed set is in (uw).
(b) If A eM) and & > 0, there exist sets F and G such that

FcAcG,
Fis closed, G is open, and
wG - A) <e, wd -F)<e.

The first inequality holds since u* was defined by means of coverings
by open elementary sets. The second inequality then follows by taking
complements.

(c) We say that E is a Borel set if E can be obtained by a countable
number of operations, starting from open sets, each operation consisting
in taking unions, intersections, or complements. The collection # of all
Borel sets in R? is a o-ring; in fact, it is the smallest o-ring which contains
all open sets. By Remark (a), Ee M(p) if E \in A.

(d) If A e M(w), there exist Borel sets F and G such that Fc 4 = G,
and

WG - A) = (A - F)=0.

This follows from (b) if we take c = 1/n and let n - oo.

Since A = Fu (4 - F), we see that every 4 \in M(y) is the union of a
Borel set and a set of measure zero.

The Borel sets are y-measurable for every pu. But the sets of measure
zero [that is, the sets E for which p*(E) = 0] may be different for different
Is.

(e) For every pu, the sets of measure zero form a o-ring.

(f) In case of the Lebesgue measure, every countable set has measure
zero. But there are uncountable (in fact, perfect) sets of measure zero.
The Cantor set may be taken as an example: Using the notation of Sec.
2.44, it is easily seen that

mE)=a3) (=123,..);

and since P = E,, P < E, for every n, so that m(P) = 0.
310 PRINCIPLES OF MATHEMATICAL ANALYSIS

MEASURE SPACES

11.12 Definition Suppose X is a set, not necessarily a subset of a euclidean
space, or indeed of any metric space. X is said to be a measure space if there
exists a o-ring M of subsets of X (which are called measurable sets) and a non-
negative countably additive set function u (which is called a measure), defined
on M.

If, in addition, X \in 9M, then X is said to be a measurable space.

For instance, we can take X = RP, MM the collection of all Lebesgue-
measurable subsets of R?, and u Lebesgue measure.

Or, let X be the set of all positive integers, Mt the collection of all subsets
of X, and u(E) the number of elements of E.

Another example is provided by probability theory, where events may be
considered as sets, and the probability of the occurrence of events is an additive
(or countably additive) set function.

In the following sections we shall always deal with measurable spaces.
It should be emphasized that the integration theory which we shall soon discuss
would not become simpler in any respect if we sacrificed the generality we have
now attained and restricted ourselves to Lebesgue measure, say, on an interval
of the real line. In fact, the essential features of the theory are brought out
with much greater clarity in the more general situation, where it is seen that
everything depends only on the countable additivity of u on a o-ring.

It will be convenient to introduce the notation

an {x|P}

for the set of all elements x which have the property P.

MEASURABLE FUNCTIONS

11.13 Definition Let f be a function defined on the measurable space “X, with
values in the extended real number system. The function fis said to be measur-
able if the set

42) {xf (x) > a}

is measurable for every real a.

11.14 Example If X= RP and MM =M(u) as defined in Definition 11.9,
every continuous f is measurable, since then (42) is an open set.
THE LEBESGUE THEORY 311

11.15 Theorem Each of the following four conditions implies the other three:

(43) {x|f(x) > a} is measurable for every real a.
(44) {x|f(x) = a} is measurable for every real a.
(45) {x|f(x) < a} is measurable for every real a.
(46) {x| f(x) < a} is measurable for every real a.

Proof The relations

x|fx) =a} = 0 [rire > a=),
xf) <a} =X - {x|f(x) 2 a},
lf <a =) [rire <a),

n=1
xf) >a} =X-{x|f(x) <a}
show successively that (43) implies (44), (44) implies (45), (45) implies
(46), and (46) implies (43).

Hence any of these conditions may be used instead of (42) to define
measurability.

11.16 Theorem If f is measurable, then |f| is measurable.
Proof

xf] <a} ={x|f(x) <a} nn {x|f(x) > - a}.

11.17 Theorem Let {f,} be a sequence of measurable functions. For x \in X, put

gx) =supf(x) (n=1,2,3,..),
h(x) = lim sup f(x).

Then g and h are measurable.
The same is of course true of the inf and lim inf.
Proof
{x|g(x) >a} = | {x|/fu(x) >a},
n=1

h(x) = inf g(x),
where g(x) = sup f,(x) (n > m).
312 PRINCIPLES OF MATHEMATICAL ANALYSIS

Corollaries

(a) Iffand g are measurable, then max (f, g) and min (f, g) are measurable.
If
“47n ff =max(£,0), f~ = -min(f,0),

it follows, in particular, that f* and f~ are measurable.
(b) The limit of a convergent sequence of measurable functions is measurable.

11.18 Theorem Let f and g be measurable real-valued functions defined on X,
let F be real and continuous on R*, and put

h(x) = F(f(x),9(x)) (xeX).

Then h is measurable.
In particular, f + g and fg are measurable.

Proof Let
G, ={(u, v)| Fu, v) > a}.

Then G, is an open subset of R?, and we can write

where {/,} is a sequence of open intervals:
I={(uv)|a,<u<b,, c,<v<dp}
Since
{x|a, <f(x) <b} = {x|f(x) > a} n {x|f(x) < bs}
is measurable, it follows that the set
{x| (f(x), g(x) \in I} = {x]a, < f(x) < by} Nn {x|c, < g(x) < d,}

is measurable. Hence the same is true of
{x| h(x) > a} = {x|(f(x), g(x) \in G,}
= J &1( 0. ax) e 1)

Summing up, we may say that all ordinary operations of analysis, includ-
ing limit operations, when applied to measurable functions, lead to measurable
functions; in other words, all functions that are ordinarily met with are measur-
able.

That this is, however, only a rough statement is shown by the following
example (based on Lebesgue measure, on the real line): If A(x) = f(g(x)), where
THE LEBESGUE THEORY 313

f is measurable and g is continuous, then / is not necessarily measurable.
(For the details, we refer to McShane, page 241.)

The reader may have noticed that measure has not been mentioned in
our discussion of measurable functions. In fact, the class of measurable func-
tions on X depends only on the o-ring 9M (using the notation of Definition 11.12).
For instance, we may speak of Borel-measurable functions on RP, that is, of
function f for which

{xf (x) >a}

is always a Borel set, without reference to any particular measure.

SIMPLE FUNCTIONS

11.19 Definition Let s be a real-valued function defined on X. If the range
of sis finite, we say that s is a simple function.
Let Ec X, and put

_[I (eB),
(48) K(x) = 0 (x c E).
Kp is called the characteristic function of E.
Suppose the range of s consists of the distinct numbers c;,...,c,. Let

E={x|s(x)=c} (i=1,...,n).
Then

(49) s=) cKg,,
n=1

that is, every simple function is a finite linear combination of characteristic
functions. It is clear that s is measurable if and only if the sets Ey, ..., E, are
measurable.

It is of interest that every function can be approximated by simple
functions:

11.20 Theorem Let f be a real function on X. There exists a sequence {s,} of
simple functions such that s,(x) - f(x) as n = co, for every x \in X. If f is measur-
able, {s,} may be chosen to be a sequence of measurable functions. If f > 0, {s,}
may be chosen to be a monotonically increasing sequence.

Proof If f> 0, define

Bu=fy| pr siw<gl  R=blwzn

314 PRINCIPLES OF MATHEMATICAL ANALYSIS

forn=1,2,3,...,i=1,2,...,n2". Put
nj - 1
(50) Sy = xX - Ke. + nKg,.

In the general case, let f =f* - f~, and apply the preceding construction
tof* andto f.

It may be noted that the sequence {s,} given by (50) converges
uniformly to f'if fis bounded.

INTEGRATION

We shall define integration on a measurable space X, in which 9 is the o-ring
of measurable sets, and pu is the measure. The reader who wishes to visualize
a more concrete situation may think of X as the real line, or an interval, and of
u as the Lebesgue measure m.

11.21 Definition Suppose

1) sa) = 3 Kp) (xeX,e>0)
i=1

is measurable, and suppose E \in MM. We define

(52) Ig(s) = Xz c;u(E N Ey).
If f is measurable and nonnegative, we define

(53) [ di =sup 1).

where the sup is taken over all measurable simple functions s such that 0 < 5s < f.
The left member of (53) is called the Lebesgue integral of f, with respect
to the measure yu, over the set E. It should be noted that the integral may have
the value + co.
It is easily verified that

(54) | sdu=1xs)
E
for every nonnegative simple measurable function s.
11.22 Definition Let f be measurable, and consider the two integrals
(55) [raw [fds
E E
where f* and f ~ are defined as in (47).
THE LEBESGUE THEORY 315

If at least one of the integrals (55) is finite, we define

(56) [fau=[ f*du-[ fd.
YE YE E

If both integrals in (55) are finite, then (56) is finite, and we say that f is
integrable (or summable) on E in the Lebesgue sense, with respect to u; we write
fe Pu) on E. If pu =m, the usual notation is: f \in  & on E.

This terminology may be a little confusing: If (56) is +00 or - co, then
the integral of f over E is defined, although f is not integrable in the above
sense of the word; fis integrable on E only if its integral over FE is finite.

We shall be mainly interested in integrable functions, although in some
cases it is desirable to deal with the more general situation.

11.23 Remarks The following properties are evident:

(a) If fis measurable and bounded on E, and if p(E)< + oo, then
fe #(u) onE.
(b) Ifa<f(x)<bforxekE, and u(E) < +00, then
au(E) < I fdu < bu(E).
(c) Iffand ge Lu) on E, and if f(x) < g(x) for x \in E, then
| fdu< | g du.
E E
d) Iffe (un) on E, then cf \in L(u) on E, for every finite constant c, and
[ ofdu=c| fd.
E E
(e) If w(E)=0, and f is measurable, then
[ rdu=o.
E
(f) IffeP(p)onE, AM, and 4 c E, then fe £(u) on A.
11.24 Theorem

(a) Suppose f is measurable and nonnegative on X. For A \in IR, define

57 P(A) = [ Sdn
316 PRINCIPLES OF MATHEMATICAL ANALYSIS

(58)

(59)

(60)

Then c is countably additive on IN.
(b) The same conclusion holds if f \in ¥(u) on X.

Proof It is clear that (b) follows from (a) if we write f=f" -f~ and

apply (a)tof* and tof.
To prove (a), we have to show that

#4) = 3 94)

if 4,eMan=1,2,3,...), A;,nA;=0 for i#j, and 4 = J 4,.
If f is a characteristic function, then the countable additivity of c is
precisely the same as the countable additivity of yu, since

[ Kg du = (A NE).

If fis simple, then f is of the form (51), and the conclusion again
holds.

In the general case, we have, for every measurable simple function s
such that 0 < s <f,

[, sdu -3 [ sd <3 B(A4,).

Therefore, by (53),
#4) < 3 604).

Now if c(A4,) = + oo for some n, (58) is trivial, since P(A) = P(A,).
Suppose c$(A4,) < + wo for every n.

Given c > 0, we can choose a measurable function s such that
0 < s <f, and such that

[ sduz] rdu=e, [sanz] sau-e
Hence

dui) =| sdu=[ sdu+ [, s di > P(A) + $42) - 2,

1 Az

so that

D(A; U 43) 2 (Ar) + c(4).
THE LEBESGUE THEORY 317

It follows that we have, for every n,
(61) $A; UU A) 2 P(A) +0 + B(4,).
Since 4 © 4; U *- U A,, (61) implies

©) #4) > 5 pd),
and (58) follows from (59) and (62).
Corollary If AeM, Be M, Bc A, and (A - B) =0, then
[ fdu=] fdu.
Ja ’B

Since A = B U (4 - B), this follows from Remark 11.23(e).

11.25 Remarks The preceding corollary shows that sets of ianeasure zero are
negligible in integration.
Let us write f ~ g on FE if the set

{x[f(x) # g(x)} nN E

has measure zero.

Then f~ f; f~ g implies g ~ f; and f~ g, g ~ h implies f ~ h. That is,
the relation ~ is an equivalence relation.

If f~ g on E, we clearly have

[ fau=[ gdn,
YA vA

provided the integrals exist, for every measurable subset 4 of E.

If a property P holds for every x \in E - A, and if u(4) = 0, it is customary
to say that P holds for almost all x \in E, or that P holds almost everywhere on
E. (This concept of “almost everywhere” depends of course on the particular

_measure under consideration. In the literature, unless something is said to the
contrary, it usually refers to Lebesgue measure.)

If fe £(u) on E, it is clear that f(x) must be finite almost everywhere on E.
In most cases we therefore do not lose any generality if we assume the given
functions to be finite-valued from the outset.

11.26 Theorem If fe ¥(u) on E, then |f| \in £(u) on E, and

(63) J rau] < [171 an.
318 PRINCIPLES OF MATHEMATICAL ANALYSIS

Proof Write E=A4 uu B, where f(x)>0 on 4 and f(x) <0 on B.
By Theorem 11.24,

[Aftdu=[ ft dust | (fl du=] fdas] f~du< +e,

so that |f| \in (un). Since f< |f| and -f < |f], we see that

[ fan < [ fl du, - [sau < | fl de,
and (63) follows.

Since the integrability of f implies that of |f|, the Lebesgue integral is
often called an absolutely convergent integral. It is of course possible to define
nonabsolutely convergent integrals, and in the treatment of some problems it is
essential to do so. But these integrals lack some of the most useful properties
of the Lebesgue integral and play a somewhat less important role in analysis.

11.27 Theorem Suppose f is measurable on E, |f| <g, and g \in ¥(u) on E.
Then f \in £(u) on E.

Proof We have f* <gandf™ <g.

11.28 Lebesgue’s monotone convergence theorem Suppose E \in IM. Let {f,} be
a sequence of measurable functions such that

(64) 0 <fi(x) <fo(x) <cve (x \in E).
Let f be defined by

(65) fix) > f(x)  (xeE)

as n- oo. Then

(66) [ fodu-| sau (noo).

YE E

Proof By (64) it is clear that, as n - oo,

(67) I, fodu-a

for some a; and since [f, < [f, we have

(68) a< [ fd.
(69)

(70)

(Mn)

(72)

THE LEBESGUE THEORY 319

Choose c such that 0 <cc <1, and let s be a simple measurable
function such that 0 <s <f. Put

E, = {x|f,(x) = es(x)} n=1,2,3,...).
By (64), E, < E; < E3 = ++; and by (65),
0
E= U E,.
For every n,

[[frduz] fiduze] sau

We let n - co in (70). Since the integral is a countably additive set function
(Theorem 11.24), (69) shows that we may apply Theorem 11.3 to the last
integral in (70), and we obtain

o> c| sdu.
E
Letting c - 1, we see that
o> [ s du,
YE
and (53) implies
o> du.
[rs u

The theorem follows from (67), (68), and (72).

11.29 Theorem Suppose f =f, + f,, where fie L(u) on E (i=1,2). Then
fe Zon E, and

(73)

[ fau=| fidu+ | fran.
YE YE YE

Proof First, suppose f; > 0, f, > 0. If f; and f, are simple, (73) follows
trivially from (52) and (54). Otherwise, choose monotonically increasing
sequences {s,}, {s,} of nonnegative measurable simple functions which
converge to f;,f,. Theorem 11.20 shows that this is possible. Put
Ss, = 8, +s,. Then

[, Ss, du = [ sy du + ) so du,

and (73) follows if we let n - co and appeal to Theorem 11.28.
320 PRINCIPLES OF MATHEMATICAL ANALYSIS

Next, suppose f; = 0,f, <0. Put
A={x|f(x) 20}, B={x|f(x) <0}.
Then f, f;, and -f, are nonnegative on 4. Hence
(74) [ fdu=[ rau (~frdu=] fau~][ fd

Similarly, -f, f;, and -f, are nonnegative on B, so that

[[Crydu=] fidut[ (=Ndn.
or
(75) [frdu=[ rdu~| fda,

and (73) follows if we add (74) and (75).

In the general case, E can be decomposed into four sets E; on each
of which f(x) and f,(x) are of constant sign. The two cases we have proved
so far imply

[rau=| fide+| fou (=1,2,39),
Ei E; v Ei
and (73) follows by adding these four equations.
We are now in a position to reformulate Theorem 11.28 for series.

11.30 Theorem Suppose E \in M. If{f,} is a sequence of nonnegative measurable
functions and

(76) fx) = IAC (xe E),
then
[ fdu=3 | fu.
E n=1"E

Proof The partial sums of (76) form a monotonically increasing sequence.
11.31 Fatou’s theorem Suppose E eM. If {f,} is a sequence of nonnegative
measurable functions and

f(x) =lim inf f(x) (x \in E),

then
7) [ fdu<timinf | f, du.
YE n-w E
THE LEBESGUE THEORY 321

Strict inequality may hold in (77). An example is given in Exercise 5.
Proof Forn=1,23,...and x \in E, put
gux) =inff(x) (=n).

Then g, is measurable on E, and

(78) 0<g(x) g(x) <-,
79 gu(%) < f(%),
(80) u(x) f(x)  (n-o0).

By (78), (80), and Theorem 11.28,
81 dl du,
(81) [nd] rau
so that (77) follows from (79) and (81).

11.32 Lebesgue’s dominated convergence theorem Suppose E \in IM. Let {f,} be
a sequence of measurable functions such that

(82) Six) = f(x)  (xeE)

as n - oo. If there exists a function g \in ¥(u) on E, such that
(83) fix) <9(x) (1=1,2,3,...,x \in E),
then

84 li = .

(89) lim [ fydu=[ fan

Because of (83), {f,} is said to be dominated by g, and we talk about
dominated convergence. By Remark 11.25, the conclusion is the same if (82)
holds almost everywhere on E.

Proof First, (83) and Theorem 11.27 imply that f, \in L(x) and fe L(u)
on E.
Since f, + g > 0, Fatou’s theorem shows that

[ (f +g) du < lim inf [ +g) du,
or

(85) [ ran < lim inf [ 7, du.
322 PRINCIPLES OF MATHEMATICAL ANALYSIS

Since g - f, > 0, we see similarly that

[ =P du<liminf [ (9-1) dy,

YE n-o E
so that

- fu <timinf | ~ | fu],
E n=w YE
which is the same as
(86) | fdu > lim sup [ fd.
E n-o E
The existence of the limit in (84) and the equality asserted by (84)

now follow from (85) and (86).

Corollary If u(E) < + 0, {f,} is uniformly bounded on E, and f,(x) - f(x) on E,
then (84) holds.

A uniformly bounded convergent sequence is often said to be boundedly
convergent.

COMPARISON WITH THE RIEMANN INTEGRAL

Our next theorem will show that every function which is Riemann-integrable
on an interval is also Lebesgue-integrable, and that Riemann-integrable func-
tions are subject to rather stringent continuity conditions. Quite apart from the
fact that the Lebesgue theory therefore enables us to integrate a much larger
class of functions, its greatest advantage lies perhaps in the ease with which
many limit operations can be handled; from this point of view, Lebesgue’s
convergence theorems may well be regarded as the core of the Lebesgue theory.

One of the difficulties which is encountered in the Riemann theory is
that limits of Riemann-integrable functions (or even continuous functions)
may fail to be Riemann-integrable. This difficulty is now almost eliminated,
since limits of measurable functions are always measurable.

Let the measure space X be the interval [a, b] of the real line, with yu =m
(the Lebesgue measure), and 9M the family of Lebesgue-measurable subsets
of [a, b]. Instead of

| fdm

it is customary to use the familiar notation
b

| fdx

a
THE LEBESGUE THEORY 323

for the Lebesgue integral of f over [a, b]. To distinguish Riemann integrals
from Lebesgue integrals, we shall now denote the former by

a| fa.

11.33 Theorem

(87)

(88)

(89)

(90)

On

92)

(a) IffeRonla,b], then fe ZL on la, bl, and
b b
[rax=2 | fx.
(b) Suppose f is bounded on [a, b). Then fe Z on [a, b] if and only if f is
continuous almost everywhere on [a, b].

Proof Suppose f is bounded. By Definition 6.1 and Theorem 6.4 there
is a sequence {P,} of partitions of [a, b], such that P,,, is a refinement
of P,, such that the distance between adjacent points of P, is less than
1/k, and such that

lim L(P,. f) = [ fax, lim UPS) =A fax.
> k= x

k= x

(In this proof, all integrals are taken over [a, b].)
If Pp, ={xo, Xq, ..., X,}, With xq = a, x, = b, define

U(a) = Lia) = f(a);
put U(x) = M; and L;(x) =m; for x;_, <x <x;, 1 <i <n, using the

notation introduced in Definition 6.1. Then

LP. f) = [Lidx, UP. f) = [Uydx,
and
L(x) <L(x)< + <f(x) << Ux) < U(x)
for all x \in [a, b], since P,,, refines P,. By (90), there exist
L(x) = lim L(x), U(x) = Jim U(x).

Observe that L and U are bounded measurable functions on [a, 5],
that

L(x) <f(x) < U(x) (a<x<b),
324 PRINCIPLES OF MATHEMATICAL ANALYSIS

and that

(93) 12 dx = [fax, [Udx =a (fax,

by (88), (90), and the monotone convergence theorem.

So far, nothing has been assumed about f except that fis a bounded
real function on [a, b].

To complete the proof, note that fe Z if and only if its upper and
lower Riemann integrals are equal, hence if and only if

(94) [Ldx = [Uadx;
since L < U, (94) happens if and only if L(x) = U(x) for almost all
x \in [a, b] (Exercise 1).
In that case, (92) implies that

(95) L(x) =f(x) = U(x)

almost everywhere on [a, b], so that f is measurable, and (87) follows
from (93) and (95).

Furthermore, if x belongs to no Py, it is quite easy to see that U(x) =
L(x) if and only if fis continuous at x. Since the union of the sets P, is count-
able, its measure is 0, and we conclude that f is continuous almost every-
where on [a, b] if and only if L(x) = U(x) almost everywhere, hence
(as we saw above) if and only if fe Z.

This completes the proof.

The familiar connection between integration and differentiation is to a
large degree carried over into the Lebesgue theory. If fe # on [a, b], and

(96) Fo =| fd asx<b),

Ya

then F'(x) = f(x) almost everywhere on [a, b].
Conversely, if F is differentiable at every point of [a, b] (“almost every-
where” is not good enough here!) and if F' \in & on [a, b], then

Fo) - Fa) =[ F()  (asx<b).

For the proofs of these two theorems, we refer the reader to any of the
works on integration cited in the Bibliography.
THE LEBESGUE THEORY 325

INTEGRATION OF COMPLEX FUNCTIONS

Suppose f is a complex-valued function defined on a measure space X, and
f =u + iv, where u and v are real. We say that f is measurable if and only if
both u and v are measurable.

It is easy to verify that sums and products of complex measurable functions
are again measurable. Since

If = (u? + v2)?
Theorem 11.18 shows that |f| is measurable for every complex measurable f.
Suppose u is a measure on X, E is a measurable subset of X, and fis a

complex function on X. We say that f \in #(u) on E provided that fis measurable
and

©7) [If du < +0,
E
and we define
[ fu= [ udp +i | v du
YE YE E

if (97) holds. Since |u| < |f|, |v] <|f], and |f] < |u| + |v], it is clear that
(97) holds if and only if u \in # (i) and v \in & (1) on E.

Theorems 11.23(a). (d), (e), (f), 11.24(b), 11.26, 11.27, 11.29, and 11.32
can now be extended to Lebesgue integrals of complex functions. The proofs
are quite straightforward. That of Theorem 11.26 is the only one that offers
anything of interest:

If fe (uw) on E, there is a complex number c, |c| = 1, such that

ef fduzo.

Put g = cf =u + iv, wand v real. Then

[7 du

The third of the above equalities holds since the preceding ones show that
fg duis real.

=c[ fdu=][ gdu=[ udns[ If du.

FUNCTIONS OF CLASS #°

As an application of the Lebesgue theory, we shall now extend the Parseval
theorem (which we proved only for Riemann-integrable functions in Chap. 8)
and prove the Riesz-Fischer theorem for orthonormal sets of functions.
326 PRINCIPLES OF MATHEMATICAL ANALYSIS

11.34 Definition Let X be a measurable space. We say that a complex
function fe #2(u) on X if fis measurable and if

[112 du < + co.
X

If u is Lebesgue measure, we say fe £2. For fe £*(u) (we shall omit the
phrase “on X”’ from now on) we define

i=] raf”

and call |f|| the #?(x) norm of f.
11.35 Theorem Suppose fe L*(u) and g \in L*(u). Then fg \in L(u), and

(98) [fol di <1f1 1g

This is the Schwarz inequality, which we have already encountered for
series and for Riemann integrals. It follows from the inequality

0< | (If] + 2g? du= If? +24 [ fol du+ 221 gl,
X X
which holds for every real A.

11.36 Theorem If fe L*(u) and g \in L*(u), then f + g \in L*(u), and

17+ gl < If1l + lal.
Proof The Schwarz inequality shows that

If +412 = [117+ [fg + [Jo + [1g]?
< 12 +2171 gh + Ig)
= (111 + gl

11.37 Remark If we define the distance between two functions f and g in
Zu) to be ||f - gl, we see that the conditions of Definition 2.15 are satisfied,
except for the fact that ||f- g|| = 0 does not imply that f(x) = g(x) for all x,
but only for almost all x. Thus, if we identify functions which differ only on a
set of measure zero, #2(u) is a metric space.

We now consider #2 on an interval of the real line, with respect to
Lebesgue measure.

11.38 Theorem The continuous functions form a dense subset of £* on [a, b).
THE LEBESGUE THEORY 327

More explicitly, this means that for any fe £2 on [a, b], and any c > 0,
there is a function g, continuous on [a, b], such that

ai =| 1r-or asf" <e

Proof We shall say that fis approximated in £2 by a sequence {g,} if
If = gall »0 as n- co.

Let A be a closed subset of [a, b], and K, its characteristic function.
Put

(x) = inf |x - y| (ye Ad)
and

9,0) = (n=1,2,3,..)%

1
1 + nt(x)
Then g, is continuous on [a, b], g(x) =1 on A, and g,(x) 0 on B,
where B = [a, b] - A. Hence

1/2
lon Kal = [gi x] 0

by Theorem 11.32. Thus characteristic functions of closed sets can be
approximated in #2 by continuous functions.

By (39) the same is true for the characteristic function of any
measurable set, and hence also for simple measurable functions.

If f> 0 and fe £2, let {5,} be a monotonically increasing sequence
of simple nonnegative measurable functions such that s,(x) - f(x).
Since |f-s,|2 <f?, Theorem 11.32 shows that ||f - s,| -0.

The general case follows.

11.39 Definition We say that a sequence of complex functions {c,} is an
orthonormal set of functions on a measurable space X if

[ $B dit = H (n # m),

(n =m).

In particular, we must have c, \in £3(u). If fe £*(u) and if

= [ fade (n=1,23,..),
X

we write

0

f~ L Cans

n=

as in Definition 8.10.
328 PRINCIPLES OF MATHEMATICAL ANALYSIS

The definition of a trigonometric Fourier series is extended in the same
way to #2 (or even to £) on [-n, nn]. Theorems 8.11 and 8.12 (the Bessel
inequality) hold for any fe £*(u). The proofs are the same, word for word.

We can now prove the Parseval theorem.

11.40 Theorem Suppose

99) Sx) ~ Y ce™,
where fe #* on [-n, n]. Let s, be the nth partial sum of (99). Then
(100) lim || f= 5, =0,
(101) Slalt=o [If] dx
er 2nd yp ’

Proof Let c>0 be given. By Theorem 11.38, there is a continuous
function g such that

&
-_ <-.
If = gl <3
Moreover, it is easy to see that we can arrange it so that g(r) = g(-n).
Then g can be extended to a periodic continuous function. By Theorem
8.16, there is a trigonometric polynomial 7, of degree N, say, such that

£
-T| <=.
lg-TI <3

Hence, by Theorem 8.11 (extended to #2), n > N implies
ls, = fll < IT = fll <e,

and (100) follows. Equation (101) is deduced from (100) as in the proof of
Theorem 8.16.

Corollary If fe %* on [-n, nn], and if
[| Swe mdax=0  (n=0,21,%2,..),
then ||f|| = 0.

Thus if two functions in #2 have the same Fourier series, they differ at
most on a set of measure zero.
THE LEBESGUE THEORY 329

11.41 Definition Let f and f, e £2) (n=1,2,3,...). We say that {f,}
converges to fin Zu) if | f, - f]| = 0. We say that {f,} is a Cauchy sequence
in £?(u) if for every c > 0 there is an integer N such that n > N, m > N implies

Ife = full <e.

11.42 Theorem If {f,} is a Cauchy sequence in FL*(u), then there exists a
function fe L(y) such that {f,} converges to f in L*(u).

This says, in other words, that #2(u) is a complete metric space.

Proof Since {f,} is a Cauchy sequence, we can find a sequence {n.},
k=1,23,..., such that

1
I foie = Soe <x (k=123..)

Choose a function g \in #?(u). By the Schwarz inequality,

[Non = on.) die < "51
Ix

Hence
(102) S [190 - ful di < lg.

k=1"X

By Theorem 11.30, we may interchange the summation and integration in
(102). It follows that

(103) 19) 2 ful) = fre (X)| < + 0
almost everywhere on X. Therefore
(104) 3 per) =f) < + 0
k=1

almost everywhere on X. For if the series in (104) were divergent on a
set E of positive measure, we could take g(x) to be nonzero on a subset of
E of positive measure, thus obtaining a contradiction to (103).

Since the kth partial sum of the series

2, Ure) = fol),
which converges almost everywhere on JX, is

Juicer) = Jai),
330 PRINCIPLES OF MATHEMATICAL ANALYSIS

we see that the equation
Sx) = lim Jn(X)
defines f(x) for almost all x \in X, and it does not matter how we define
f(x) at the remaining points of X.
We shall now show that this function f has the desired properties.

Let c > 0 be given, and choose N as indicated in Definition 11.41. If
nm, > N, Fatou’s theorem shows that

If = full lim inf Lf, = fu <

Thus f - f,, \in £*(u), and since f = (f - f,,) + f,,, We see that fe L*(n).
Also, since c is arbitrary,

Jim If = full =0.
Finally, the inequality

(105) If =f < 1f = ful + If = Jil

shows that {f,} converges to f in Z2(u); for if we take n and ny large
enough, each of the two terms on the right of (105) can be made arbi-
trarily small.

11.43 The Riesz-Fischer theorem Let {c,} be orthonormal on X. Suppose
Z|c,|? converges, and put s,=c $y + ++ + c,c,. Then there exists a function
fe L(y) such that {s,} converges to f in L*(u), and such that

f~ y Cnn +
n=1
Proof Forn>m,

[15 = 8mll® = [emer [2+ + leal?,

so that {s,} is a Cauchy sequence in £?(u). By Theorem 11.42, there is
a function f \in £?(u) such that

lim || f-s,| =0.

Now, for n > k,

[ 1. du - c= [ 13 dp - [ 5 du,
THE LEBESGUE THEORY 331

so that

|] Souda < If = sal Iall + 17 = sl.

Letting n - co, we see that

a=] Sb.du (k=1,2,3,..),

and the proof is complete.

11.44 Definition An orthonormal set {c,} is said to be complete if, for
fe £*(u), the equations

[ fEadu=0 (n=1,2,3..)
YX

imply that | f|| =0.

In the Corollary to Theorem 11.40 we deduced the completeness of the
trigonometric system from the Parseval equation (101). Conversely, the Parseval
equation holds for every complete orthonormal set:

11.45 Theorem Let {c,} be a complete orthonormal set. If fe £L*(u) and if

(106) f~ 3 cub.

then

(107) [112 du= 3 lel.
X n=1

Proof By the Bessel inequality, X|c,|? converges. Putting
Sp = C19; +0 + Cus,

the Riesz-Fischer theorem shows that there is a function g \in #?(y) such
that

(108) g~ ICL

and such that |g - s,|| = 0. Hence |s,|| = [lg]. Since
Isall? = leg? += + fecal?

we have

(109) [lal du=¥ |e”
332 PRINCIPLES OF MATHEMATICAL ANALYSIS

Now (106), (108), and the completeness of {c,} show that | f- g| = 0,
so that (109) implies (107).

Combining Theorems 11.43 and 11.45, we arrive at the very interesting
conclusion that every complete orthonormal set induces a 1-1 correspondence
between the functions fe Z*(u) (identifying those which are equal almost
everywhere) on the one hand and the sequences {c,} for which Z|c,|* converges,
on the other. The representation

0

S~ )) Cans

together with the Parseval equation, shows that #?(u) may be regarded as an
infinite-dimensional euclidean space (the so-called “Hilbert space”), in which
the point f has coordinates c,, and the functions c, are the coordinate vectors.

EXERCISES

1. If f>0 and [g fdu = 0, prove that f(x) = 0 almost everywhere on E. Hint: Let E,
be the subset of E on which f(x) > 1/n. Write A = |JE,. Then (4) = 0 if and only
if w(E,) = 0 for every n.

2. If [4 fdu = 0 for every measurable subset A of a measurable set E, then f(x) = 0
almost everywhere on E.

3. If {f,} is a sequence of measurable functions, prove that the set of points x at
which { f,(x)} converges is measurable.

4. If fe L(p) on E and g is bounded and measurable on E, then fg \in Z(u) on E.
5. Put

0 0<x<}),
I= G<x<1,
f(x) = g(x) 0<x<1),
Sas1(x) = g(1 - x) O<x<l).
Show that
lim inf f,(x)=0 0O<x<l),
but

[fi dx = 1.

[Compare with (77).]
THE LEBESGUE THEORY 333

6. Let

fulx) = (|x| <n),

[=

(|x| >n).

Then f.(x) - 0 uniformly on R', but
[7 feax=2 (n=1,2,3,...)

(We write [2 in place of [z;.) Thus uniform convergence does not imply domi-
nated convergence in the sense of Theorem 11.32. However, on sets of finite
measure, uniformly convergent sequences of bounded functions do satisfy Theo-
rem 11.32.

7. Find a necessary and sufficient condition that f \in  Z(«) on [a, b]. Hint: Consider
Example 11.6(b) and Theorem 11.33.

8. If fe # on [a,b] and if F(x)= [3 f(r) dt, prove that F'(x) = f(x) almost every-
where on [a, b].

9. Prove that the function F given by (96) is continuous on [a, b].

10. If u(X) < +c and fe £*(pu) on X, prove that fe #(u) on X. If

WX) = +o,
this is false. For instance, if
1
f(x) = TT

then fe #2 on R', but fc .¥ on R'.
11. If £, g \in L (pn) on X, define the distance between f and g by

[, |f-gl du.

Prove that #(p) is a complete metric space.

12. Suppose
(a [fn <1ifo<x<1,0<y<]I,
(b) for fixed x, f(x, y) is a continuous function of y,
(c) for fixed y, f(x, y) is a continuous function of x.
Put

rl
9) =| fle, ydy  O<x<1).
Is g continuous?
13. Consider the functions

fulx) = sin nx (n=1,2,3,...,-mr<x<m
334 PRINCIPLES OF MATHEMATICAL ANALYSIS

as points of #2, Prove that the set of these points is closed and bounded, but
not compact.

14. Prove that a complex function f is measurable if and only if f~!(V) is measurable
for every open set V in the plane.

15. Let Z be the ring of all elementary subsets of (0, 1]. If 0 <a <b <1, define

$(la, b]) = c(la, b)) = $ ((a, b]) = $((a, b) = b- a,

but define
#((0, b)) = $((0, 6D =1 +b

if 0 <b <1. Show that this gives an additive set function c on Z, which is not
regular and which cannot be extended to a countably additive set function on a
o-ring.

16. Suppose {n,} is an increasing sequence of positive integers and E is the set of all
x \in (-m, m) at which {sin nsx} converges. Prove that m(E)=0. Hint: For every
A<E,

[ sin mx dx - 0,
JA
and

2[ Ginn dx = [ (1 cos 2x) dx md) ask.

17. Suppose E < (-m, wm), m(E) > 0,8 > 0. Use the Bessel inequality to prove that
there are at most finitely many integers » such that sin nx > 6 for all x \in E.
18. Suppose fe L*(p), g \in L*(n). Prove that

[aan] = [1717 du [101 du

if and only if there is a constant c such that g(x) = cf(x) almost everywhere.
(Compare Theorem 11.35.)
BIBLIOGRAPHY

ARTIN, E.: “The Gamma Function,” Holt, Rinehart and Winston, Inc., New York,
1964.

BOAS, R. P.: “A Primer of Real Functions,” Carus Mathematical Monograph No. 13,
John Wiley & Sons, Inc., New York, 1960.

BUCK, R. C. (ed.): “Studies in Modern Analysis,” Prentice-Hall, Inc., Englewood
Cliffs, N.J., 1962.

--: “Advanced Calculus,” 2d ed., McGraw-Hill Book Company, New York,
1965.

BURKILL, J. C.: “The Lebesgue Integral,” Cambridge University Press, New York, 1951.

DIEUDONNE, J.: “Foundations of Modern Analysis,” Academic Press, Inc., New York,
1960.

FLEMING, W. H.: “Functions of Several Variables,” Addison-Wesley Publishing Com-
pany, Inc., Reading, Mass., 1965.

GRAVES, L. M.: “The Theory of Functions of Real Variables,” 2d ed., McGraw-Hill
Book Company, New York, 1956.

HALMOS, P. R.: “Measure Theory,” D. Van Nostrand Company, Inc., Princeton, N.J.,
1950.
336 PRINCIPLES OF MATHEMATICAL ANALYSIS

: “Finite-dimensional Vector Spaces,” 2d ed., D. Van Nostrand Company, Inc.,
Princeton, N.J., 1958.

HARDY, G. H.: “Pure Mathematics,” 9th ed., Cambridge University Press, New York,
1947.

and rRogGosINskI, W.: “Fourier Series,” 2d ed., Cambridge University Press,
New York, 1950.

HERSTEIN, I. N.: “Topics in Algebra,” Blaisdell Publishing Company, New York, 1964,

HEWITT, E., and STROMBERG, K.: “Real and Abstract Analysis,” Springer Publishing
Co., Inc., New York, 1965.

KELLOGG, 0. D.: “Foundations of Potential Theory,” Frederick Ungar Publishing Co.,
New York, 1940.

KNOPP, K.: “Theory and Application of Infinite Series,” Blackie & Son, Ltd.,
Glasgow, 1928.

LANDAU, E. G. H.: “Foundations of Analysis,” Chelsea Publishing Company, New York,
1951.

MCSHANE, E. J.: “Integration,” Princeton University Press, Princeton, N.J., 1944.

NIVEN, I. M.: “Irrational Numbers,” Carus Mathematical Monograph No. 11, John
Wiley & Sons, Inc., New York, 1956.

ROYDEN, H. L.: “Real Analysis,” The Macmillan Company, New York, 1963.

RUDIN, W.: “Real and Complex Analysis,” 2d ed., McGraw-Hill Book Company,
New York, 1974.

SIMMONS, G. F.: “Topology and Modern Analysis,” McGraw-Hill Book Company,
New York, 1963.

SINGER, I. M., and THORPE, J. A.: “Lecture Notes on Elementary Topology and Geom-
etry,” Scott, Foresman and Company, Glenview, 1ll., 1967.

SMITH, K. T.: “Primer of Modern Analysis,” Bogden and Quigley, Tarrytown-on-
Hudson, N.Y., 1971.

SPIVAK, M.: ‘Calculus on Manifolds,” W. A. Benjamin, Inc., New York, 1965.

THURSTON, H. A.: “The Number System,” Blackie & Son, Ltd., London-Glasgow, 1956.

LIST OF SPECIAL SYMBOLS

The symbols listed below are followed by a brief statement of their meaning and by
the number of the page on which they are defined.

 \in  belongsto .................... 3
c doesnotbelongto............. 3
<, © inclusion signs ............ 3
Q rational field ................ 3
<, <, >, > inequality signs.... 3
sup least upper bound. ........... 4
inf greatest lower bound ......... 4
R realfield ..................... 8
too, -oo, winfinities ........ 11, 27
Zz complex conjugate ............. 14
Re (z) realpart.................. 14
Im (z) imaginary part ............ 14
|z| absolute value ............... 14
> summation sign ............ 15, 59
R* euclidean k-space ............. 16
0 nullvector ..........ccovvvnnnn. 16
X'y inner product .............. 16
|x| norm of vector x ............ 16

{x,} sequence.................... 26
Us w union ...oiiiiiin 27
(, Nn intersection ............... 27
(a,b) segment................... 31
[a,b] interval ................... 31
Ec complementof E ............. 32
E’ limitpointsof E.............. 35
E closure of E ......oovvvnnnn. 35
lim limit... 47
-> CONVErgesto .............. 47, 98
lim sup upper limit .............. 56
lim inf lower limit ............... 56
gef composition ................ 86
f(x+) right-hand limit ........... 94
f(x-) left-hand limit ............ 94
f’, f(x) derivatives ........ 103,112

UP, ), UP, f, 0), L(P, f), L(P, f, a)
Riemann sums ........... 121, 122
338 PRINCIPLES OF MATHEMATICAL ANALYSIS

R, R(x) classes of Riemann (Stieltjes)

integrable functions ....... 121, 122
%(X) space of continuous

functions ............. ou... 150

| [Il norm ........... 140, 150, 326

exp exponential function ........ 179
Dy Dirichlet kernel ............. 189
I'(x) gamma function ........... 192
{ei,...,e,} standard basis ....... 205
L(X),L(X, Y) spaces of linear

transformations. ............... 207
[A] matrix..................... 210
D;f partial derivative ........... 215
Vf gradient.................... 217
 \in ',%" classes of differentiable

functions ................ 219, 235
det [4] determinant ............. 232
Ji(x) Jacobian ................. 234
00s) pacobian 234
O(Xy1y ny Xn)

I¥ kecell o.oo 245
Q% k-simplex .................. 247
dx; basic k-form ............... 257
A multiplication symbol ........ 254
d differentiation operator ........ 260
wr transformof w ............. 262
2 boundary operator ............ 269
VXF curl ........oooiiiii. 281
V-F divergence ............... 281
& ring of elementary sets ........ 303
m Lebesgue measure ....... 303, 308
[ MEASUTe ................ 303, 308
Mr, M families of measurable sets 305
{x|P} set with property P........ 310
f*,f~ positive (negative) part

SF AU 312
Ke characteristic function ....... 313
L, Ln), L?, FH py classes of

Lebesgue-integrable

functions ................ 315, 326
Abel, N.H.. 75, 174
Absolute convergence. 71

of integral. 138
Absolute value, 14
Addition (see Sum)
Addition formula. 178
Additivity, 301
Affine chain. 268
Affine mapping. 266
Affine simplex. 266
Algebra. 161

self-adjoint. 165

uniformly closed. 161
Algebraic numbers, 43
Almost everywhere, 317
Alternating series. 71
Analytic function, 172
Anticommutative law, 256
Arc, 136
Area element, 283
Arithmetic means, 80, 199
Artin, E., 192. 195
Associative law, 5, 28. 259
Axioms, §

Baire’s theorem, 46, 82
Ball. 31

Base, 45

Basic form, 257

Basis, 205

Bellman, R., 198

Bessel inequality, 188, 328
Beta function, 193

Binomial series, 201
Bohr-Mollerup theorem, 193
Borel-measurable function, 313

Borel set, 309

Boundary, 269

Bounded convergence. 322
Bounded function, 89
Bounded sequence. 48
Bounded set. 32
Brouwer’s theorem, 203
Buck. R.C., 195

Cantor. G., 21, 30. 186
Cantor set, 41, 81, 138, 168, 309
Cardinal number, 25
Cauchy criterion, 54, 59, 147
Cauchy sequence, 21, 52, 82, 329
Cauchy's condensation test, 61
Cell, 31
c"-equivalence, 280
Chain, 268

affine, 268

differentiable, 270
Chain rule, 105. 214
Change of variables. 132, 252, 262
Characteristic function, 313
Circle of convergence. 69
Closed curve, 136
Closed form. 275
Closed set, 32
Closure. 35

uniform. 151, 161
Collection, 27
Column matrix, 217
Column vector, 210
Common refinement, 123
Commutative law, 5, 28
Compact metric space, 36
Compact set, 36

INDEX

Comparison test. 60
Complement. 32
Complete metric space, 54, 82.
151.329
Complete orthonormal set. 331
Completion, 82
Complex field. 12, 184
Complex number, 12
Complex plane, 17
Component of a function. 87. 215
Composition, 86, 105. 127, 207
Condensation point. 45
Conjugate, 14
Connected set. 42
Constant function, 85
Continuity, 85
uniform. 90
Continuous functions, space of.
150
Continuous mapping. 85
Continuously differentiable curve,
136
Continuously differentiable map-
ping. 219
Contraction. 220
Convergence. 47
absolute, 71
bounded. 322
dominated, 321
of integral, 138
pointwise, 144
radius of. 69. 79
of sequences. 47
of series, 59
uniform, 147
Convex function, 101
Convex set, 31
340 INDEX

Coordinate function, 88
Coordinates. 16, 205
Countable additivity. 301
Countable base. 45
Countable set, 25
Cover. 36
Cunningham. F.. 167
Curl, 281
Curve. 136
closed. 136
continuously differentiable. 136
rectifiable, 136
space-filling. 168
Cut. 17

Davis. P.J.. 192
Decimals. 11
Dedekind. R.. 21
Dense subset. 9. 32
Dependent set. 205
Derivative. 104
directional. 218
of a form. 260
of higher order. 110
of an integral. 133. 236. 324
integration of. 134, 324
partial. 215
of power series, 173
total. 213
of a transformation. 214
of a vector-valued function, 112
Determinant, 232
of an operator. 234
product of. 233
Diagonal process. 30, 157
Diameter. 52
Differentiable function. 104, 212
Differential, 213
Differential equation. 119. 170
Differential form (see Form)
Differentiation (see Derivative)
Dimension. 205
Directional derivative, 218
Dirichlet’s kernel. 189
Discontinuities. 94
Disjoint sets, 27
Distance. 30
Distributive law, 6. 20, 28
Divergence. 281
Divergence theorem. 253.272,
288
Divergent sequence. 47
Divergent series. 59
Domain. 24
Dominated convergence theorem,
155. 167. 321
Double sequence. 144

e, 63

Eberlein. W. F., 184
Elementary set. 303
Empty set. 3
Equicontinuity. 156

Equivalence relation, 25
Euclidean space, 16, 30

Euler's constant. 197

Exact form, 275

Existence theorem. 170
Exponential function, 178
Extended real number system, 11
Extension, 99

Family. 27
Fatou's theorem, 320
Fejér's kernel, 199
Fejér's theorem. 199
Field axioms. §
Fine. N.J.. 100
Finite set, 25
Fixed point. 117
theorems, 117, 203, 220
Fleming. W. H., 280
Flip, 249
Form, 254
basic. 257
of class  \in '.c", 254
closed, 275
derivative of, 260
exact, 275
product of, 258. 260
sum of, 256
Fourier, J. B., 186
Fourier coefficients, 186, 187
Fourier series. 186. 187, 328
Function, 24
absolute value, 88
analytic. 172
Borel-measurable, 313
bounded, 89
characteristic, 313
component of, 87
constant, 85
continuous, 85
from left, 97
from right, 97
continuously differentiable. 219
convex, 101
decreasing, 95
differentiable, 104, 212
exponential. 178
harmonic, 297
increasing. 95
inverse. 90
Lebesgue-integrable, 315
limit, 144
linear, 206
logarithmic, 180
measurable, 310
monotonic, 95
nowhere differentiable continu-
ous, 154
one-to-one, 25
orthogonal, 187
periodic, 183
product of, 85
rational, 88
Riemann-integrable. 121

Function:
simple, 313
sum of, 85
summable, 315
trigonometric, 182
uniformly continuous, 90
uniformly differentiable, 115
vector-valued, 85
Fundamental theorem of calculus,
134, 324

Gamma function, 192

Geometric series, 61

Gradient, 217, 281

Graph, 99

Greatest lower bound, 4

Green's identities, 297

Green's theorem, 253, 255, 272,
282

Half-open interval, 31
Harmonic function, 297
Havin, V.P., 113

Heine-Borel theorem, 39
Helly's selection theorem. 167
Herstein, I. N., 65

Hewitt, E., 21

Higher-order derivative, 110
Hilbert space. 332

Holder's inequality, 139

i 13
Identity operator, 232
Image, 24
Imaginary part, 14
Implicit function theorem, 224
Improper integral, 139
Increasing index, 257
Increasing sequence, 55
Independent set. 205
Index of a curve, 201
Infimum, 4
Infinite series, 59
Infinite set, 25
Infinity, 11
Initial-value problem, 119. 170
Inner product. 16
Integrable functions, spaces of,
315, 326
Integral:
countable additivity of, 316
differentiation of, 133, 236, 324
Lebesgue. 314
lower, 121, 122
Riemann, 121
Stieltjes, 122
upper, 121, 122
Integral test, 139
Integration:
of derivative, 134, 324
by parts, 134, 139, 141
Interior, 43
Interior point, 32

Intermediate value, 93, 100, 108
Intersection, 27

Interval, 31, 302

Into, 24

Inverse function. 90

Inverse function theorem, 221
Inverse image, 24

Inverse of linear operator, 207
Inverse mapping, 90
Invertible transformation, 207
Irrational number, 1, 10, 65
Isolated point, 32

Isometry, 82. 170
Isomorphism, 21

Jacobian, 234

Kellogg, O. D.. 281
Kestelman, H., 167
Knopp. K.. 21, 63

Landau, E.G. H., 21
Laplacian. 297
Least upper bound. 4
property. 4. 18
Lebesgue. H.L.. 186
Lebesgue-integrable function. 315
Lebesgue integral, 314
Lebesgue measure. 308
Lebesgue’s theorem, 155, 167,
318, 321
Left-hand limit, 94
Leibnitz. G.W., 71
Length. 136
L'Hospital's rule. 109, 113
Limit, 47, 83, 144
left-hand, 94
lower, 56
pointwise, 144
right-hand, 94
subsequential. 51
upper, 56
Limit function. 144
Limit point, 32
Line, 17
Line integral, 255
Linear combination. 204
Linear function. 206
Linear mapping, 206
Linear operator, 207
Linear transformation, 206
Local maximum, 107
Localization theorem, 190
Locally one-to-one mapping, 223
Logarithm. 22, 180
Logarithmic function. [80
Lower bound, 3
Lower integral. 121, 122
Lower limit. 56

McShane, E.J.. 313

Mapping. 24

affine, 266

continuous, 85

continuously differentiable, 219

linear, 206

open, 100, 223

primitive, 248

uniformly continuous, 90

(See also Function)
Matrix, 210

product, 211
Maximum, 90
Mean square approximation, 187
Mean value theorem, 108, 235
Measurable function. 310
Measurable set, 305, 310
Measurable space, 310
Measure, 308

outer. 304
Measure space, 310
Measure zero, set of, 309, 317
Mertens, F., 74
Metric space, 30
Minimum, 90
Mobius band, 298
Monotone convergence theorem,

318

Monotonic function, 95, 302
Monotonic sequence. 55
Muitiplication (see Product)

Negative number, 7
Negative orientation, 267
Neighborhood, 32
Newton's method, 118
Nijenhuis, A., 223
Niven, L., 65, 198
Nonnegative number, 60
Norm, 16, 140, 150. 326

of operator, 208
Normal derivative, 297
Normal space, 101
Normal vector, 284
Nowhere differentiable function,

154

Null space, 228
Null vector, 16
Number:

algebraic, 43

cardinal, 25

complex, 12

decimal, 11

finite, 12

irrational, 1. 10, 65

negative, 7

nonnegative, 60

positive, 7, 8

rational, 1

real, 8

One-to-one correspondence, 25
Onto, 24
Open cover, 36

INDEX 341

Open mapping. 100, 223
Open set, 32
Order, 3, 17
lexicographic, 22
Ordered field, 7, 20
k-tuple, 16
pair, 12
set. 3, 18, 22
Oriented simplex, 266
Origin, 16
Orthogonal set of functions, 187
Orthonormal set, 187, 327, 331
Outer measure, 304

Parameter domain, 254
Parameter interval, 136
Parseval's theorem, 191, 198, 328.
331

Partial derivative, 215
Partial sum. 59, 186
Partition, 120

of unity, 251
Perfect set. 32
Periodic function, 183, 190
a, 183
Plane, 17
Poincaré’s lemma, 275. 280
Pointwise bounded sequence, 155
Pointwise convergence, 144
Polynomial, 88

trigonometric, 185
Positive orientation, 267
Power series. 69, 172
Primes. 197
Primitive mapping, 248
Product, §

Cauchy, 73

of complex numbers, 12

of determinants, 233

of field elements, 5

of forms, 258, 260

of functions, 85

inner, 16

of matrices. 211

of real numbers, 19. 20

scalar, 16

of series, 73

of transformations, 207
Projection, 228
Proper subset, 3

Radius, 31. 32

of convergence. 69, 79
Range, 24. 207
Rank, 228
Rank theorem, 229
Ratio test, 66
Rational function, 88
Rational number, 1
Real field, 8
Real line, 17
Real number, 8
Real part, 14
342 INDEX

Rearrangement, 75
Rectifiable curve. 136
Refinement, 123

Reflexive property. 25
Regular set function, 303
Relatively open set, 35
Remainder, 211. 244
Restriction, 99

Riemann, B., 76, 186
Riemann integral, 121
Riemann-Stieltjes integral, 122
Riesz-Fischer theorem, 330
Right-hand limit, 94

Ring, 301

Robison. G. B., 184

Root, 10

Root test. 65

Row matrix, 217

Saddle point. 240
Scalar product, 16
Schoenberg. 1.J.. 168
Schwarz inequality. 15. 139. 326
Segment, 31
Self-adjoint algebra. 165
Separable space, 45
Separated sets, 42
Separation of points, 162
Sequence. 26

bounded. 48

Cauchy. 52. 82. 329

convergent, 47

divergent. 47

double. 144

of functions, 143

increasing, 55

monotonic, 55

pointwise bounded, 155

pointwise convergent. 144

uniformly bounded, 155

uniformly convergent, 157
Series, 59

absolutely convergent, 71

alternating, 71

convergent, 59

divergent. 59

geometric, 61

nonabsolutely convergent. 72

power. 69, 172

product of, 73

trigonometric, 186

uniformly convergent, 157
Set. 3

at most countable, 25

Borel. 309

bounded. 32

bounded above, 3

Cantor, 41, 81, 138. 168, 309

closed, 32

compact. 36

complete orthonormal. 331

connected. 42

convex. 31

countable. 25

Set,
dense. 9, 32
elementary, 303
empty, 3
finite, 25
independent, 205
infinite, 25
measurable, 305, 310
nonempty, 3
open, 32
ordered, 3
perfect, 32, 41
relatively open, 35
uncountable, 25, 30, 41
Set function, 301
o-ring, 301
Simple discontinuity, 94
Simple function, 313
Simplex. 247
affine, 266
differentiable, 269
oriented, 266
Singer, I. M., 280
Solid angle, 294
Space:
compact metric, 36
complete metric, 54
connected, 42
of continuous functions, 150
euclidean, [6
Hilbert, 332
of integrable functions. 315, 326
measurable, 310
measure, 310
metric, 30
normal. 101
separable, 45
Span. 204
Sphere, 272. 277. 294
Spivak, M.. 272, 280
Square root, 2, 81, 118
Standard basis, 205
Standard presentation, 257
Standard simplex, 266
Stark, E. L.. 199
Step function, 129
Stieltjes integral, 122
Stirling’s formula, 194, 200
Stokes’ theorem. 253, 272, 287
Stone-Weierstrass theorem. 162.
190. 246
Stromberg, K., 21
Subadditivity, 304
Subcover, 36
Subfield. 8, 13
Subsequence, 51
Subsequential limit, 51
Subset, 3
dense. 9, 32
proper. 3
Sum, §
of complex numbers, 12
of field elements, 5
of forms, 256
of functions. 85

Sum,
of linear transformations, 207
of oriented simplexes, 268
of real numbers, 18
of series, 59
of vectors, 16
Summation by parts, 70
Support, 246
Supremum, 4
Supremum norm, 150
Surface, 254
Symmetric difference. 305

Tangent plane. 284

Tangent vector, 286

Tangential component, 286

Taylor polynomial, 244

Taylor's theorem, 110. 116, 176, 243

Thorpe, J. A.. 280

Thurston, H. A., 21

Torus, 239-240, 285

Total derivative, 213

Transformation (see Function;
Mapping)

Transitivity. 25

Triangle inequality, 14, 16. 30, 140

Trigonometric functions, 182

Trigonometric polynomial, 185

Trigonometric series. 186

Uncountable set, 25. 30. 41
Uniform boundedness, 155
Uniform closure, 151

Uniform continuity, 90
Uniform convergence, 147
Uniformly closed algebra, 161
Uniformly continuous mapping, 90
Union, 27

Uniqueness theorem. 119, 258
Unit cube, 247

Unit vector, 217

Upper bound, 3

Upper integral, 121, 122
Upper limit, 56

Value, 24

Variable of integration, 122

Vector, 16

Vector field, 281

Vector space, 16, 204

Vector-valued function, 85
derivative of. 112

Volume, 255, 282

Weierstrass test, 148
Weierstrass theorem, 40, 159
Winding number, 201

Zero set, 98, 117
Zeta function, 141
