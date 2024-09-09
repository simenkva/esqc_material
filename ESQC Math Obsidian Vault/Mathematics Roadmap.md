# A mathematical roadmap for quantum chemistry

This text accompanies the [[Mathematics.canvas|Mathematics]] canvas. 

Each box contains one field, or topic, and they are connected to other boxes with the arrow indicating the direction from "more general" to "less general and more special". Click headings in this canvas to go to relevant sections in this note.

Of course, many more arrows could be drawn, and many more boxes could be added. In order to make the graph not too cluttered and confusing, we keep only main links.

**NOTE:** Topics marked with a ❤️ are considered of prime importance to any quantum chemist, regardless of their specialization.



## Logic and Set Theory


Logic is a branch of mathematics and philosophy that deals with reasoning, the principles of valid inference, and the structure of propositions, including but not limited to mathematical statements. It is usually subdivided into propositional logic, dealing with statements that are true or false but not both, and predicate logic, which add the ability of logic to express properties of objects and relationships between them. For example the argument "If P then Q. Q is not true. Then P is not true" uses propositional logic. The statement "there exists an x such that Joke(x) and Funny(x)" is an existential statement from predicate logic.

Logic provides the formal framework used to analyze and construct mathematical proofs, ensuring that conclusions follow from premises in a valid and systematic way.

Set theory is the branch of mathematics that studies sets, which are collections of objects. It forms the foundation for much (all?) of modern mathematics, providing the language and basic concepts used to describe and analyze mathematical structures. Set theory forms the foundation in the sense that every other mathematical theory can be formalized in the language of set theory. Indeed, in set theory, every object is a set.

Most mathematicians are aware of formal set theory, but the "version" used in most contexts is "naive set theory", which in a more informal manner defines mathematical sets compared to the rigorous axiom based constructions. As Russel's Paradox shows us, naive set theory has some pitfalls. Thus, in mathematics, one must resort to formal set theory in situations that can be described as "borderline".

Although formal set theory is unlikely to be applied in the study of quantum chemistry, the basic notation is widely-used and an important language tool when specifying computational methods and their implementation. 

Recommended reading:

>[!book] Matematisk Fundament by Snoore H. Christiansen
>![[Pasted image 20240909064616.png|300]]
>This book is unfortunately only available in Norwegian. It is a textbook aimed at undergraduate students. One of the components of this book is an introduction to mathematical logic. Highly recommended for those that can read Norwegian.



>[!book] An Introduction to Proofs with Set Theory by Ashlock and Lee
>![[Pasted image 20240829092150.png|300]]
>Springer (2020)
>https://link.springer.com/book/10.1007/978-3-031-02426-9
>
>A in introduction to logic, set theory, and mathematical proofs for the undergraduate student. Highly recommended!
>
>A link to the set theory chapter available online: https://www.math.uh.edu/~dlabate/settheory_Ashlock.pdf

>[!book] "Set Theory for the Working Mathematician" by Krzysztof Ciesielski
> ![[Ciesielski-frontpage.png|300]]
> A more advanced text.
> 
> Cambridge University Press (1997) https://doi.org/10.1017/CBO9781139173131



## Category Theory

Category theory is a branch of mathematics that provides a high-level, abstract framework for describing and analyzing mathematical structures and their relationships. It was initially developed in the 1940s by Samuel Eilenberg and Saunders Mac Lane, in the context of algebraic topology, but has since evolved into a more universal framework. It has has found applications across nearly all areas of mathematics, as well as in computer science, logic, and theoretical physics.

One of the useful aspects of category theory is that it gives a rigorous language for comparing different mathematical concepts such as groups and vector spaces through concepts such as _functors_ and _natural transformations_. Seemingly different areas of mathematics can then be brought together and explored in a unified manner.

Although direct use of category theory in quantum chemistry is rare, it is mentioned here as an important branch of modern mathematics.

Recommended reading:
>[!book] A Gentle Introduction to Category Theory by Maarten Fokkinga
>A set of lecture notes. Link to PDF on the author's web site:
>https://maartenfokkinga.github.io/utwente/mmf92b.pdf



## Discrete Mathematics

Where calculus focuses on the mathematics of continuously varying objects, in _discrete mathematics_ the focus is on discrete objects, having a finite or countable aspect to them. It is foundational in computer science and information science.

Set theory and logic is often included under the umbrella "discrete mathematics". 

Graph theory studies the properties of collections of nodes connected with links or edges, and has a natural relevance for chemistry, as molecules are often visualized as graphs.

Combinatorics is the mathematics of counting and arrangements of finite sets of objects. Closely related is the topic of discrete probability, where the space of outcomes is finite. These topics appear naturally in statistical mechanics, for example.

Further topics include number theory and algorithms.


Recommended reading:
>[!book] Concrete Mathematics by Donald Knuth
>![[Pasted image 20240829093357.png]]
>Addison-Wesley (1994)
>
>A classic textbook. Does not cover graph theory.
>
>https://en.wikipedia.org/wiki/Concrete_Mathematics
>https://web.archive.org/web/20201106232418/http://www-cs-faculty.stanford.edu/~knuth/gkp.html
>
>

>[!book] Introduction to Graph Theory by Douglas B. West
>![[Pasted image 20240829094014.png|300]]
>
>Link to full book (only for preview): https://daiwz.net/course/disc_math/2023/West_Intro_Graph_Theory_en.pdf
>


## Abstract Algebra

In abstract algebra, sets are given *mathematical structure* in the form of binary operations and various axioms that define what it is to be, e.g., a *group*. Thus, a group is defined in terms of its essential features, and not its concrete realizations. For example, the group $\mathbb{Z}_4 = \{0, 1, 2, 3\}$ with group operation of addition modulo 4, and the group of of powers of the matrix $[[0, 1], [-1, 0]]$ are the same from the point of view of algebra.

Important algebraic constructions include groups, semigroups, rings, modules, vector spaces, and algebras.

Abstract algebra is important for quantum chemistry, since it lays the foundation for linear algebra, one of the most important tools of the scientist, and the study of molecular symmetries and groups.

Recommended reading:
>[!book] A First Course in Abstract Algebra by John B. Fraleigh
>Seventh Edition, Pearson (2003)
>![[Screenshot 2024-08-29 at 09.49.31.png|300]]
>Archived book: https://archive.org/details/firstcourseinabs07edfral


## ❤️ Group Theory


Group theory is the study of abstract groups and their representations. Lie groups are groups that are also differentiable manifolds (see Differential Geometry). Group theory permeates theoretical physics and chemistry, giving an axiomatic treatment of symmetry. Representation theory studies groups represented as linear operators or matrices acting on vector spaces.

In chemistry, molecular symmetries and point groups are useful for understanding molecular behavior and also eases interpretation of spectroscopic experiments. Spectroscopic notation is a consequence of conservation of angular momentum. Representation theory is applied to explain the symmetries of molecular orbitals. Having a grasp of group theory is _absolutely essential_ for the quantum chemist.

Recommended reading:

>[!book] Group Theory and Chemistry by David M. Bishop
>![[Pasted image 20240829095053.png|300]]
>Dover (1973)
>
>A classic textbook, very useful.
>
>Link to PDF for preview:  https://library.navoiy-uni.uz/files/david%20m.%20bishop%20-%20group%20theory%20and%20chemistry%20(revised%20edition)(1993)(294s).pdf
>


## Number systems

The axiomatic definition of the natural numbers using set theory due to John von Neumann is one of the simplest examples of how set theory serves as foundation for mathematics. The natural numbers are again used to define the integers, rational numbers, real numbers, and complex numbers. These sets are of course among the most important mathematical objects in the sciences. The number systems are again examples of algebraic structures: the integers form a group under addition, the real and complex numbers form fields.

Clearly, understanding numbers is essential to any scientific study. On the other hand, for most purposes, intuitive notions about integers, reals, and complex numbers will be sufficient.

Recommended reading:
* See [[#Logic and Set Theory]]



## Topology

Topology is the study of open sets and the abstract concept of continuity. A topological space consists of a set and a collection of subsets, called open sets, which satisfy certain axioms. This framework allows us to talk about properties such as continuity, convergence, and neighborhood relations without necessarily involving a specific notion of distance. For example, a metric induces a topology by defining open sets in terms of distance, giving rise to a particular kind of topological space known as a metric space.

For quantum chemists, being aware of the various notions of topology is useful to navigate the literature. For example, the convergence of the pseudocontinuum of the FCI method can be formalized with topological notions. As another example, in density-functional theory, what does it mean that two electronic densities are close together? Being able to distinguish different notions of "closeness of densities" is imperative for understanding, say, modes of convergence of SCF iterations.

Having an understanding of topology is very useful when studying and using infinite dimensional vector spaces, since various measures of distance (norm, metric) are typically more subtle in infinite dimensions than finite dimensions. For example, in finite dimensions, every norm gives the same notion of continuity.


Recommended reading:
>[!book] Topology by James R. Munkres
>![[Munkres.png|300]]
>
>Pearson (2014)
>
>This is a classic textbook.
>
>Link to PDF (for preview): https://people.math.ethz.ch/~dkosanovic/24-FS/Munkres-Topology.pdf
>

## Measure and integration

Measure theory develops abstract notions of length, area, volume, etc., and allows to speak about such notions in potentially very abstract spaces, such as function spaces. Measure theory is also the foundation for probability theory, helping to define objects like probability distributions. 

The Lebesgue integral is based on the notion of a Borel measure, and generalizes the Riemann integral. There are, for example, functions with infinitely many discontinuities that can be integrated with this intagral, something the Riemann integral fails to do. With the Lebesgue integral we can integrate many more functions compared to the Riemann integral,  and operations like exchanging limits and integrals or integration variables obey well-defined and simple theorems such as the Dominated Convergence Theorem and the Monotone Convergence Theorem. The Lebesgue integral is also necessary to define the $L^2$ Hilbert space of quantum mechanics. 

A passing knowledge if measure theory is very useful for the quantum chemist, since much of the language used in mathematical physics relies on these concepts. The theory becomes critical in edge cases, especially when dealing with limits, infinite sums, or cases where rigorous integration techniques are required to avoid paradoxes or inconsistencies. In those cases, these paradoxes are resolved by checking the conditions for, say, interchange of limits and integration.

Recommended reading:
>[!book] The Elements of Integration and Lebesgue Measure by Robert G. Bartle
>![[Bartle.png|300]]
>Wiley Classics, 1995
>
>A slim yet classic textbook on measure and integration.


## Distribution theory

With distribution theory one extends the concept of functions to include objects, known as _distributions_ or _generalized functions_, which can be used to rigorously define operations like differentiation even for functions that are not classically differentiable. For example, the derivative of the Heaviside step function id the Dirac delta function, a bona fide distribution. 

The theory is particularly useful in handling singularities or discontinuities, such as the Dirac delta function, which models an infinitely concentrated point of mass or charge. Distribution theory provides a powerful framework for solving partial differential equations, e.g., using Green's functions.

A rudimentary knowledge of distribution theory is very useful in the study of quantum mechanics. The standard informal view is that "the Dirac delta is a function which is infinite everywhere except at a single point where it is infinity", similarly that "the Green's function is the response of the system to a Dirac delta function", is very useful, but will only take one so far. Similarly, in the language of (tempered) distributions, the Fourier transform becomes particularly elegant and powerful. For example, the Fourier transform of the Dirac delta is a plane wave.

Useful in (for example):
- Response theory
- Manybody Green's function theory
- Electromagnetism
- Quantum Field Theory

Recommended reading:

> [!book] "Mathematical Methods in Physics" by Philippe Blanchard and Erwin Brüning
> 
> ![[Blanchard and Bruening.png|300]]

>[!book] See also the book by [[Recommended General Mathematics Reading#"Mathematical Physics" by Butkov|Butkov]]



## ❤️ Linear Algebra


In linear algebra, one studies linear vector spaces and linear transformations between such spaces. Typical, and indeed archetypal, examples are $\mathbb{R}^n$ and $\mathbb{C}^n$, and $n\times m$ matrices with complex or real entries. It is no exaggeration that linear algebra is perhaps the most important tool in science, being at the heart of everything from quantum mechanics, data analysis, and numerical methods for the solution of partial differential equations.

Having a good command of linear algebra is _absolutely essential_ to any theoretical chemist, from the LCAO approach to molecular orbitals, via practical realizations of Kohn--Sham density functional theory, to the numerical solution of, say, the coupled-cluster method.

Recommended reading:

> [!book]  "Linear Algebra Done Right" by Sheldon Axler
> ![[Linear Algebra Done Right.png|300]]
> 
> A highly regarded undergraduate text in linear algebra, considered a very fine piece of didacic writing. Open access. Available for free on the Author's web page: https://linear.axler.net/
> 
  

>[!book] "Introduction to Linear Algebra" by Gilbert Strang
>![[Strang.png|300]]
> A great book by one of the all time greats in linear algebra. See also the [[Recommended YouTube channels]].  
> 
> https://bookstore.ams.org/view?ProductCode=STRANG/5
> 
>

>[!book] A first course in linear algebra by Robert Beezer
>![[Beezer_frontpage.png|300]]
>
>

>[!book] Finite-dimensional vector spaces by Paul R. Halmos
>![[Halmos_finite_frontpage.jpg|300]]
>
>Paul Halmos' textbook is very comprehensive, perhaps rather advanced, but covers a lot of material not commonly treated in introductory text.
## Multilinear algebra

In multilinear algebra, linear maps between vector spaces are generalized to maps that take several vector spaces as inputs and outputs, i.e., tensors. While rarely taught alongside linear algebra, multilinear algebra could be included in advanced courses, especially considering its growing importance in modern machine learning methodology. Multilinear algebra also plays an important role in differential geometry and naturally appears in the calculus of several variables. Tensors are essential in many-body methods like coupled-cluster theory and configuration-interaction theory, making multilinear algebra highly relevant to quantum chemists.

Recommended reading:

>[!book] "Multilinear Algebra" by Werner Greub
>A springer book on multilinear algebra that I have seen recommended. I have no experience with this book myself.
>
>Springer Verlag.
>Weblink: https://link.springer.com/book/10.1007/978-1-4613-9425-9
>![[Greub.png|300]]


>[!book] "Multilinear Algebra and its Applications"
>Lecture notes: https://www2.math.ethz.ch/education/bachelor/lectures/fs2016/other/mla/ma.pdf 
>
>Course web page at ETH: https://www2.math.ethz.ch/education/bachelor/lectures/fs2016/other/mla.html
>
>The author's name is not disclosed, but the professor that taught the course in 2016 was [Prof. Dr. Özlem Imamoḡlu](https://people.math.ethz.ch/~oezlemi/)


## ❤️ Calculus

Calculus is the branch of mathematics that studies continuous change and is divided into two main areas: differential calculus and integral calculus. Differential calculus focuses on the concept of the derivative, rates of change. Integral calculus, on the other hand, deals with the concept of the integral. Moreover, calculus studies the notion of series, including power series and Taylor series, and their convergence.

Multivariate calculus extends to functions of several variables, encompassing the study of partial derivatives, multiple integrals, and vector calculus. 

Calculus, together with linear algebra, forms the foundation for much of modern science. It is _absolutely essential_ to have a good grasp of calculus and multivariate calculus for theoretical chemists. Topics such as reaction rates, quantum mechanical wavefunctions, and thermodynamic quantities all heavily rely on calculus.

Recommended reading:
>[!book] Vector Calculus by Jerrold E. Marsden and Anthony Tromba
>![[Marsden_frontpage.png|300]]
>

## Complex analysis

Complex analysis studies the calculus of functions of complex variables. For complex functions, being differentiable is a much more restricting requirement than for real functions, leading to surprising and very strong results of great use in physics and chemistry, such as the Residue Theorem. Since real functions often are special cases of complex functions, complex analysis is very useful even if complex numbers do not show up at all in a theory.

Useful in: Response theory, quantum dynamics, integral evaluation, perturbation theory, to name a few.

Complex analysis is among the more useful topics for quantum chemists.

Recommended reading:
>[!book] The book by [[Recommended General Mathematics Reading#"Mathematical Physics" by Butkov]] is useful.

>[!book] Complex Analysis by Theodore Gamelin
>![[Pasted image 20240829095847.png|300]]
>Springer (2001).
>
>A very pedagogical textbook.

>[!book] Complex Analysis by Eberhard Freitag and Rolf Busam
>![[Busam_Freitag-frontpage.png|300]]
>Springer
>
>This is an excellent and modern textbook in complex analysis.

## Differential Geometry

Differential geometry studies curves, surfaces, and higher-dimensional analogues from an abstract perspective, and are called differentiable manifolds. These are characterized by the fact that they somehow are smooth, and that locally, i.e., in for sufficiently small neighborhoods of points (if one zooms in on any point), they look like flat space, i.e., $\mathbb{R}^n$ (or $\mathbb{C}^n$ for complex manifolds). Thus, one can say that differential geometry combines multivariate calculus and linear algebra. One has infinite dimensional versions of the theory, as well, where the modelling spaces are infinite dimensional Banach or Hilbert spaces.

Differential geometry is very useful for abstract understanding of manybody wavefunction methods. For example, the concept of orbital invariance in CASSCF, or the manifold structure of the Hartree-Fock or coupled-cluster methods. See also lie group theory.

Differential geometry is also the foundation for general relativity, and, perhaps to a lesser extent, special relativity.

Differential geometry is among the more useful branches of mathematics for quantum chemistry students.

Recommended reading (quite a few here):
>[!book] Geometry of Physics by Theodore Frankel
>![[Pasted image 20240829100049.png]]
>Third Edition, Cambridge University Press (2011)
>A fantastic book.
>Weblink: https://www.cambridge.org/core/books/the-geometry-of-physics/94894F70DB22055BD7BC2B84C135ABAF?pageNum=2&searchWithinIds=94894F70DB22055BD7BC2B84C135ABAF&productType=BOOK_PART&searchWithinIds=94894F70DB22055BD7BC2B84C135ABAF&productType=BOOK_PART&sort=mtdMetadata.bookPartMeta._mtdPositionSortable%3Aasc&pageSize=30&template=cambridge-core%2Fbook%2Fcontents%2Flistings&ignoreExclusions=true

>[!book] Fundamentals of Differential Geometry by Serge Lang
>![[Pasted image 20240829100530.png|300]]
>Springer (1999)
>A classic texbook.
>https://link.springer.com/book/10.1007/978-1-4612-0541-8
>

>[!book]  Differential Geometry of Curves and Surfaces by Manfredo do Carmo
>![[Pasted image 20240829100909.png|300]]
>Prentice-Hall (1976)
>
>A gentle introduction to differential geometry, mostly sticking to familiar Euclidean space.
>
>Link to PDF (for preview): http://www2.ing.unipi.it/griff/files/dC.pdf
>
>do Carmo also has a more advanced book, "Riemannian Geometry"
>![[Pasted image 20240829101030.png|300]]
>Birkhäuser (1992)
>
>Weblink: https://link.springer.com/book/9780817634902
>
>I have used this book sometimes, and it is quite good.
>

>[!book] Manifolds, Tensor Analysis, and Applications by Ralph Abraham, Jerrold E. Marsden, and Tudor Ratiu
>![[Pasted image 20240829164212.png|300]]
>Springer (1988)
>Weblink: https://link.springer.com/book/10.1007/978-1-4612-1029-0
>Archived book: https://archive.org/details/manifoldstensora00abra_0



## Convex Analysis

Convex analysis deals with convex sets and functions. It is an important branch of mathematics, since many optimization problems in science enjoy the property of convexity. Convex analysis introduces a duality transformation, the Legendre-Fenchel transformation, which in many ways are analogous to the Fourier transform.

Convex analysis plays a prominent role in the mathematical foundation of DFT, as pioneered by E.H. Lieb. The Legendre-Fenchel transformation is also important in thermodynamics.

Convex analysis is a useful topic, especially if one wants to study DFT.

Recommended reading:
>[!book] Convex Analysis - An Introductory Text by Jan van Tiel
>![[cover.jpg|300]]
>Wiley (1984)
>
>This is a slim book but highly readable!




## Functional Analysis

Functional analysis can be viewed as infinite dimensional linear algebra. Here, complete normed spaces (Banach spaces) and complete inner product spaces (Hilbert spaces) are studied, along with linear transformations between such spaces. Functional analysis is the foundation of quantum mechanics. It is not entirely inaccurate to say that the development of functional analysis in the early 20th century was motivated by placing quantum mechanics on rigorous ground.

Functional analysis also provides the mathematical language for abstract treatment of PDEs such as the Schrödinger equation, the Kohn--Sham approach to DFT, Maxwell's equations, and so on.

Functional analysis is overall a very useful topic for quantum chemists.

Recommended reading:
>[!book] Introductory Functional Analysis with Applications by Erwin Kreyszig
>
> ![[Screenshot 2024-08-29 at 10.15.24.png|300]]

>[!book] Applied Functional Analysis by Eberhard Zeidler
>![[Zeidler-frontpage.png|300]]
>Springer (1995)
>
>Like Kreyszig, Zeidler has an approach to functional analysis geared towards physics applications, in particular quantum mechanics. Zeidler's text is accessible and comprehensive at the same time.


## ❤️ Calculus of Variations

Calculus of variations deals with the optimization of nonlinear functionals, functions that map _functions_ to scalars. The basic idea is that a functional is stationary if small perturbations of the variables produce zero variations in the functional (to first order in the variation of the variable). Calculus of variations generalizes vector calculus to infinite dimensions, and central are concept like the Euler-Lagrange equations. Calculus of variations is the correct framework for variational formulations of the laws of nature, from quantum field theory and QED to Hamilton's equations of motion. In particular, the Rayleigh-Ritz variational principle is an example central to quantum chemistry. Thus, nonlinear approximations to the molecular Schrödinger equation such as Hartree-Fock theory or approximate Kohn-Sham theory is naturally formulated in this language.

To have a basic grasp of calculus of variations is almost essential to quantum chemists. A basic knowledge does not require advanced functional analysis, even if the above paragraph gives such an impression.


Recommended reading:
>[!book] Classical Mechanics by Goldstein, Safko, and Poole
>![[Screenshot 2024-09-09 at 09.37.11.png|300]]
>This is a classic textbook, with a very good exposition of the calculus of variations intended for the physics student. See also the book by Gelfand and Fomin, which takes a more rigorous approach.

>[!book] Calculus of Variations by Gelfand and Fomin
> ![[Screenshot 2024-09-09 at 09.33.16.png|300]]
> Dover (2000)
> This is a standard texbook in the calculus of variations that strikes a balance between the physics-oriented approach of Goldstain, Safko, and Poole, yet retaining mathematical rigor.



## ❤️ Ordinary differential equations

Ordinary differential equations (ODEs) describe initial value and boundary value problems of scalar quantities, or coupled such equations. From classical mechanics to rate equations, ODEs permeate theoretical chemistry, and having a basic understanding of essential mathematical results is absolutely essential.

Recommended reading:
> [!book] Solving Ordinary Differential Equations I: Nonstiff Problems by Hairer, Nørsett, and Wanner
> ![[Pasted image 20240909094228.png|300]]
> Springer (1993)
> 
> A classic textbook in the numerical solution of ODEs. The introductory chapters deal with the classical theory of ODEs.



## Partial differential equations

Partial differential equations (PDEs) generalize ODEs to infinite dimensions, i.e., initial and boundary value problems where the unknown is no longer a scalar or a vector, but an element in a function space. Laws such as Einstein's gravitation theory, transport of heat, chemical reaction-diffusion systems, Maxwell's equations, the various Schrödinger equations, are all PDEs.

PDEs are very important for quantum chemistry.

Recommended reading:
>[!book] Partial Differential Equations by Lawrence C. Evans
> ![[Evans-frontpage.png|300]]
> Second Edition, American Mathematical Society (2010)
> A popular textbook in PDEs.
> Link to PDF (for preview): http://home.ustc.edu.cn/~wclw8181/wffc.files/Partial%20Differential%20Equations.Evans.pdf

>[!book] Introduction to Partial Differential Equations by Aslak Tveito and Ragnar Winther
>![[Pasted image 20240909094419.png|300]]
>Springer (2005)
>
>This book was the curriculum at a graduate course i numerical methods for PDE at the University of Oslo for a while in the 2000s. The book strikes a good balance between the mathematical formulation of PDEs and their numerical solution. It is therefore ideal at building intuition and a language for describing PDEs for students. 




>[!book] Functional Analysis, Sobolev Spaces, and Partial Differential Equations by Haim Brezis
>
> ![[Screenshot 2024-08-29 at 16.29.30.png|300]]
>Springer (2011)
> A highly readable book focusing on an abstract framework for PDEs.
> Weblink: https://link.springer.com/book/10.1007/978-0-387-70914-7
  
 

## Operator Algebra

In operator algebra, one studies algebras of operators over linear spaces, often Hilbert spaces. The algebras are often given structures inspired by quantum mechanics, such as canonical anticommutator or canonical commutator relations, e.g. the CAR and CCR algebras. It is a highly abstract branch of pure mathematics, and understanding the basic notions and results may be very useful for the study of manybody theory and quantum field theories.

Recommended reading:

>[!book] Operator Algebras and Quantum Statistical Mechanics by Ola Bratteli and Derek W. Robinson
>![[Pasted image 20240829163631.png|300]]
>Springer (1987)
>A classic textbook, but quite dense, in my opinion.
>Weblink: https://link.springer.com/book/10.1007/978-3-662-02520-8


>[!book] A Course in Operator Theory by John B. Conway
>![[Screenshot 2024-08-30 at 08.41.32.png|300]]
>American Mathematical Society (1999)
>Link: https://bookstore.ams.org/GSM/21
>"This is an excellent course in operator theory and operator algebras ... leads the reader to deep new results and modern research topics ... the author has done more than just write a good book—he has managed to reveal the unspeakable charm of the subject, which is indeed the ‘source of happiness’ for operator theorists."  - _Mathematical Reviews_

>[!book] A list of books for students studying operator algebras
>Link: https://math.vanderbilt.edu/peters10/students.html
>

- See also [[Recommended General Mathematics Reading#"Mathematical Methods in Physics" by Blanchard and Brüning]]







## Numerical analysis

Most equations in quantum chemistry cannot be solved analytically, and must be approximated in finite precision arithmetic on computers. This is the area of numerical analysis. Here, numerical methods for differential equations are studied, as well as numerical linear algebra and eigenvalue finding algorithms, to name some topics.

Numerical analysis is very important for developing and understanding computer implementations of quantum chemistry algorithms.

Recommended reading:
>[!book] Numerical Analysis by Francis B. Hildebrand
>![[Pasted image 20240830084959.png|300]]
>Dover (1956)
>Archived version: https://archive.org/details/introduction_to_numerical_analysis_hildebrand
>
> A classic textbook.

>[!book] Fundamentals of Numerical Computation by Tobin A. Driscoll and Richard J. Braun
>![[Pasted image 20240830085921.png|300]]
>SIAM
>
>A modern textbook of very high quality also available completely for free online. Python, MATLAB, and Julia versions.
>Link: https://tobydriscoll.net/book/fnc/index.html
>Complete book: https://tobydriscoll.net/fnc-julia/frontmatter.html
>


## ❤️ Optimization and root finding

Optimization, really a subfield of numerical analysis, deals with finding local or global extremal points of functions of several variables, as well as finding roots of systems of nonlinear equations. There are a multitude of algorithms, such as the method of steepest descent, Newton, and quasi-Newton methods. A very important topic for students of quantum chemistry, as many computational problems end up as an optimization problem.

Recommended reading:
>[!book] Numerical Optimization by Jorge Nocedal and Stephen J. Wright
>![[Screenshot 2024-08-30 at 08.46.35.png|300]]
>Springer (2006)
>Link to PDF (for preview): https://www.math.uci.edu/~qnie/Publications/NumericalOptimization.pdf
>Link: https://link.springer.com/book/10.1007/978-0-387-40065-5
>
> This is an excellent book which I have used a lot.
> 