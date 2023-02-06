<h2 align="center">
  MIT 18.06, Spring 2023<br />
  Linear Algebra
</h2> 

Welcome to MIT 18.06: Linear Algebra! The Spring 2023 course information, materials, and links are recorded below. Course materials for previous semesters are archived in the [other branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/viewing-branches-in-your-repository) of this repository. You can dive in right away by reading this [introduction](https://github.com/mitmath/1806/blob/master/notes/Introduction%20to%20Linear%20Algebra%206th%20edition%20and%20A%20%3D%20CR_04.pdf) to the course by Professor Strang.

NOTICE OF VIDEO RECORDING: The Spring 2023 lectures for 18.06 will be recorded for [OCW](https://ocw.mit.edu/). See the [notice of recording](https://github.com/mitmath/1806/blob/master/notes/Notice%20of%20Video%20Recording%2018_06%20S23.docx) for more information.

Catalog Description: *Basic subject on matrix theory and linear algebra, emphasizing topics useful in other disciplines, including systems of equations, vector spaces, determinants, eigenvalues, singular value decomposition, and positive definite matrices. Applications to least-squares approximations, stability of differential equations, networks, Fourier transforms, and Markov processes. Uses linear algebra software. Compared with 18.700, more emphasis on matrix algorithms and many applications.*

## Syllabus

**Lectures**: Monday, Wednesday, and Friday at 11am in 26-100.

**Instructors**: [Prof. Gilbert Strang](https://math.mit.edu/~gs/) and [Dr. Andrew Horning](https://math.mit.edu/directory/profile.html?pid=2334).  

**Textbook**: [Introduction to Linear Algebra: 6th Edition](http://eduapps.mit.edu/textbook/books.html?Term=2023SP&Subject=18.06). Professor Strang will explain more about this new 6th edition in class (it is not yet on Amazon). It now ends with two chapters on deep learning. Professor Strang plans to make the textbook available for students to purchase at a discount. Here again is a link to the [preface and contents](https://github.com/mitmath/1806/blob/master/notes/Introduction%20to%20Linear%20Algebra%206th%20edition%20and%20A%20%3D%20CR_04.pdf).

**Recitations**: Tuesday at the following times and locations.

* Tuesday 9am: R1 Mo Chen (2-132)
* Tuesday 10am: R2 Mo Chen (2-132), R3 V. Krylov  (2-136)
* Tuesday 11am: R4 V. Krylov (2-136), R5 D. Kluiev (4-159)
* Tuesday 12pm: R6 M. Harris (4-159), R7 D. Kluiev (2-136), R9 I. Ganguly (2-105)
* Tuesday 1pm: R8 M. Harris (2-136),  R10 I. Ganguly (2-132), R11 Z. Chen (2-135)
* Tuesday 2pm: R12 Z. Chen (2-132), R13 K. Vashaw (2-136)
* Tuesday 3pm: R14 K. Vashaw (2-136)

**Exams**: We will have 3 exams during the semester: February 22, March 20, April 19. Final Exam TBD In May.

**Homework:** Due weekly on Sunday at midnight. Upload a .pdf of your clearly written or typed solutions on [Gradescope](https://www.gradescope.com/).

**Resources**: In addition to this repository, we will use the following online resources.

* [Canvas](https://web.mit.edu/canvas/) - course announcements will be posted on Canvas.
* [Gradescope](https://www.gradescope.com/) - submit Psets and check grades through Gradescope.
* [Piazza](https://piazza.com/mit/spring2023/1806/home) - ask questions in the course discussion forum.


MIT also has excellent study resources: [math learning center](https://math.mit.edu/learningcenter/), [TSR^2 study/resource room](https://ome.mit.edu/programs/talented-scholars-resource-room-tsr2), [pset partners](https://psetpartners.mit.edu/).

## Problem sets

* [Pset 1](https://github.com/mitmath/1806/blob/master/psets/pset_1/hw1a.pdf) is due on Sunday February 12 at 11:59pm.

## Exams

## Lecture Material and Summaries

### Lecture 1 (February 6)

Two ways to do matrix-vector multiplication are the "row way" and the "column way."
* "Row way" = dot products between rows of matrix and the vector.
* "Column way" = linear combination of columns in the matrix. The coefficients in the linear combination are the entries of the vector.

The column way leads to the _column space_ of a matrix, the space of all possible linear combinations of the columns. Does the column space of a 3 x 3 matrix form a line, a plane, or fill the whole space? It depends on how many _linearly independent_ columns there are. The geometric picture of a matrix's column space is the first key idea of linear algebra.

The dot product tells us how to do matrix-vector multiplication the "row way." The remarkable _cosine formula_ for the dot product also shows how to use it to measure the length of vectors and the angles between them. In particular, perpendicular vectors have dot product = 0. Two useful inequalities follow quickly from the cosine formula: the _Cauchy-Schwarz_ and _triangle_ inequalities. Beyond matrix multiplication, the dot product reveals the geometry of vectors and their linear combinations.

**Further Reading:** Textbook, chapter 1.1 and 1.2.
