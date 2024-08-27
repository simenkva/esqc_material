#esqc

# A mathematical roadmap for quantum chemistry

We here (link to map: [[Mathematics Map.canvas|Mathematics Map]]) try to outline, graphically, a set of mathematical topics, and how they are relevant for the study of quantum chemistry. The subdivision of mathematical topics is largely artificial and biased as there there is no rigorous way to do such a thing. 

Each box contains one field, or topic, and they are connected to other boxes with the arrow indicating the direction from "more general" to "less general and more special".

In a second visualization ([[Quantum Chemistry Map.canvas|link to canvas]]) we try to organize the various topics of theoretical and quantum chemistry in relation to the mathematical map.

Of course, many more arrows could be drawn, and many more boxes could be added. In order to make the graph not too cluttered and confusing, we keep only main links.

**NOTE:** Topics marked with a  $\heartsuit$ are considered of prime importance to any quantum chemist, regardless of their specialization.



## Logic and Set Theory


Logic is the branch of mathematics and philosophy that deals with reasoning, the principles of valid inference, and the structure of propositions, i.e., mathematical statements. It provides the formal framework used to analyze and construct mathematical proofs, ensuring that conclusions follow from premises in a valid and systematic way.

Set theory is the branch of mathematics that studies sets, which are collections of objects. In set theory, everything is a set. It forms the foundation for much (all?) of modern mathematics, providing the language and basic concepts used to describe and analyze mathematical structures. Set theory forms the foundation in the sense that every other mathematical theory can be formalized in the language of set theory.

Most mathematicians are aware of formal set theory, but the "version" used in most contexts is "naive set theory", which in a more informal manner defines mathematical sets compared to the rigorous axiom based constructions. As Russel's Paradox shows us, naive set theory has some pitfalls. Most mathematicians simply avoid these pitfalls and stick to naive set theory.

Although formal set theory is unlikely to be applied in the study of quantum chemistry, the basic notation is widely-used and an important language tool when specifying computational methods and their implementation. 

Recommended reading:
- "Set Theory for the Working Mathematician" by - Krzysztof Ciesielski, Cambridge University Press (1997) https://doi.org/10.1017/CBO9781139173131
- 

## Category Theory

Category theory is a branch of mathematics that provides a high-level, abstract framework for describing and analyzing mathematical structures and their relationships. It was developed in the 1940s by Samuel Eilenberg and Saunders Mac Lane, and has found applications across nearly all areas of mathematics, as well as in computer science, logic, and theoretical physics.

One of the useful aspects of category theory is that it gives a rigorous language for comparing different mathematical concepts and structures, such as groups and vector spaces.

Although direct use of category theory in quantum chemistry is rare, it is mentioned here as an important branch of modern mathematics.

Recommended reading:
- ...

## Abstract Algebra

In abstract algebra, sets are given *mathematical structure* in the form of binary operations and various axioms that define what it is to be, e.g., a *group*. Thus, a group is defined in terms of its essential features, and not its concrete realizations. For example, the group $\mathbb{Z}_4 = \{0, 1, 2, 3\}$ with group operation of addition modulo 4, compared to the matrix group consisting of powers of the matrix $[[0, 1], [-1, 0]]$.

Important algebraic constructions include groups, semigroups, rings, modules, vector spaces, and algebras.

Abstract algebra is important for quantum chemistry, since it lays the foundation for linear algebra, one of the most important tools of the scientist, and the study of molecular symmetries and groups.



Recommended reading:
- ...

## $\heartsuit$ Group Theory

Group theory is the study of abstract groups and their representations. Lie groups are groups that are also differentiable manifolds (see Differential Geometry). Group theory permeates theoretical physics and chemistry, giving an axiomatic treatment of symmetry. Representation theory studies groups represented as linear operators or matrices acting on vector spaces.

In chemistry, molecular symmetries and point groups are useful for understanding molecular behavior and also eases interpretation of spectroscopic experiments. Spectroscopic notation is a consequence of conservation of angular momentum. Representation theory is applied to explain the symmetries of molecular orbitals. Having a grasp of group theory is _absolutely essential_ for the quantum chemist.

Recommended reading:
- ... 


## Number systems

The axiomatic definition of the natural numbers using set theory is one of the simplest examples of how set theory serves as foundation for mathematics. The natural numbers are again used to define the integers, rational numbers, real numbers, and complex numbers. These sets are of course among the most important mathematical objects in the sciences. The number systems are again examples of algebraic structures: the integers form a group under addition, the real and complex numbers form fields.

Clearly, understanding numbers is essential to any scientific study. On the other hand, for most purposes, intuitive notions about integers, reals, and complex numbers will be sufficient.

Recommended reading:
* - 



## Topology

Topology is the study of open and closed sets, and the concept of continuity. A topological space is a set together with a collection of subsets called open subsets, and axioms that these have to obey. From this, topological spaces are generated, allowing us to talk about "closeness" of elements in the set. For example, a metric is an example of a structure that gives rise to a particular kind of topology, that formalizes the notion of distance between points.

In topology the notion of sequences and their convergence is made abstract, including the notion of continuous functions. Topological arguments are indispensable for mathematical analysis of partial differential equations.

For quantum chemists, being aware of the various notions of topology is useful to navigate the literature. For example, the convergence of the pseudocontinuum of the FCI method can be formalized with topological notions. As another example, in density-functional theory, what does it mean that two electronic densities are close together? Being able to distinguish different notions of "closeness of densities" is imperative for understanding, say, modes of convergence of SCF iterations.


Recommended reading:
- ...

## Measure and integration

Measure theory develops abstract notions of length, area, volume, etc., and allows to speak about such notions in potentially very abstract spaces. For example, the Dirac delta function is rigorously defined using measure theory. 

The Lebesgue integral is based on the notion of a Borel measure, and generalizes the Riemann integral. With the Lebesgue integral we can integrate many more functions compared to the Riemann integral,  and operations like exchanging limits and integrals or integration variables obey well-defined and simple theorems. The Lebesgue integral is also necessary to define the $L^2$ Hilbert space of quantum mechanics. 

A passing knowledge if measure theory is very useful for the quantum chemist, since much of the language used in mathematical physics relies on these concepts. That being said, detailed theorems are rarely used, except in borderline cases, where apparent paradoxes may arise. In those cases, these paradoxes are resolved by checking the conditions for, say, interchange of limits and integration.

Recommended reading:
- ...

## Distribution theory

With distribution theory one extends the concept of functions to include objects, known as _distributions_ or _generalized functions_, which can be used to rigorously define operations like differentiation even for functions that are not classically differentiable. This theory is particularly useful in handling singularities or discontinuities, such as the Dirac delta function, which models an infinitely concentrated point of mass or charge. Distribution theory provides a powerful framework for solving partial differential equations, e.g., using Green's functions.

A rudimentary knowledge of distribution theory is very useful in the study of quantum mechanics. The standard informal view is that "the Dirac delta is a function which is infinite everywhere except at a single point where it is infinity", similarly that "the Green's function is the response of the system to a Dirac delta function", is very useful, but will only take one so far.

Useful in (for example):
- Response theory
- Manybody Green's function theory
- Electromagnetism

Recommended reading:
- ...


## $\heartsuit$ Linear Algebra

In linear algebra, one studies linear vector spaces and linear functions between such spaces. Typical, and indeed archetypal, examples are $\mathbb{R}^n$ and $\mathbb{C}^n$, and $n\times m$ matrices with complex or real entries. It is no exaggeration that linear algebra is perhaps the most important tool in science, being at the heart of everything from quantum mechanics, data analysis, and numerical methods for the solution of partial differential equations.

Having a good command of linear algebra is _absolutely essential_ to any theoretical chemist, from the LCAO approach to molecular orbitals, via practical realizations of Kohn--Sham density functional theory, to the numerical solution of, say, the coupled-cluster method.

Recommended reading:

> [!book]  "Linear Algebra Done Right" by Sheldon Axler
> ![[Linear Algebra Done Right.png|300]]
> 
> A highly regarded undergraduate text in linear algebra, considered a very fine piece of didacic writing. Open access. Available for free on the Author's web page: https://linear.axler.net/
> 
  




## Multilinear algebra

In multilinear algebra, linear maps between vector spaces are generalized to maps over several vector spaces to several vector spaces at once, i.e., tensors. Multilinear algebra is rarely taught together with linear algebra, but could well be a subtopic in an advanced course, especially considering it is an important part of modern machine learning methodology. Multilinear algebra finds important use cases in differential geometry, as well as appearing naturally in calculus of several variables. Tensors are also integral to manybody methods like coupled-cluster theory or configuration-interaction theort.

Multilinear algebra is among the more useful topics for quantum chemists.

Recommended reading:
* ...



## $\heartsuit$ Calculus

Calculus is the branch of mathematics that studies continuous change and is divided into two main areas: differential calculus and integral calculus. Differential calculus focuses on the concept of the derivative, rates of change. Integral calculus, on the other hand, deals with the concept of the integral.

Multivariate calculus extends to functions of several variables, encompassing the study of partial derivatives, multiple integrals, and vector calculus. 

Calculus, together with linear algebra, forms the foundation for much of modern science. It is _absolutely essential_ to have a good grasp of calculus and multivariate calculus for theoretical chemists.

Recommended reading:
- ...

## Complex analysis

Complex analysis studies the calculus of functions of complex variables. For complex functions, being differentiable is a much more restricting requirement than for real functions, leading to surprising and very strong results of great use in physics and chemistry. Since real functions often are special cases of complex functions, complex analysis is very useful even if complex numbers do not show up at all in a theory.

Useful in: Response theory, quantum dynamics, integral evaluation, perturbation theory, to name a few.

Complex analysis is among the more useful topics for quantum chemists.

Recommended reading:
- ....

## Differential Geometry

Differential geometry studies curves, surfaces, and higher-dimensional analogues from an abstract perspective, called differentiable manifolds. These are characterized by the fact that they somehow are smooth, and that locally, i.e., in for sufficiently small neighborhoods of points (if one zooms in on any point), they look like flat space, i.e., $\RR^n$ (or $\CC^n$ for complex manifolds). Thus, differential geometry combines multivariate calculus and linear algebra. One has infinite dimensional versions of the theory, as well, where the modelling spaces are infinite dimensional Banach or Hilbert spaces.

Differential geometry is very useful for abstract understanding of manybody wavefunction methods. For example, the concept of orbital invariance in CASSCF, or the manifold structure of the Hartree-Fock or coupled-cluster methods. See also lie group theory.

Differential geometry is also the foundation for general relativity, and, to a lesser extent, special relativity.

Differential geometry is among the more useful branches of mathematics for quantum chemistry students.

Recommended reading:
- ...




## Convex Analysis

Convex analysis deals with convex sets and functions. It is an important branch of mathematics, since many optimization problems in science enjoy the property of convexity. Convex analysis introduces a duality transformation, the Legendre-Fenchel transformation, which in many ways are analogous to the Fourier transform.

Convex analysis plays a prominent role in the mathematical foundation of DFT, as pioneered by E.H. Lieb. The Legendre-Fenchel transformation is also important in thermodynamics.

Convex analysis is a useful topic, especially if one wants to study DFT.

Recommended reading:
- ...


## Functional Analysis



Functional analysis can be viewed as infinite dimensional linear algebra. Here, complete normed spaces (Banach spaces) and complete inner product spaces (Hilbert spaces) are studied, along with linear operators between such spaces. Functional analysis is the foundation of quantum mechanics, as done by J. von Neumann. In a way, one can say that the development of functional analysis in the early 20th century was motivated by placing quantum mechanics on rigorous ground.

Functional analysis also provides the mathematical language for abstract treatment of PDEs such as the Schrödinger equation, the Kohn--Sham approach to DFT, Maxwell's equations, and so on.

Functional analysis is a very useful topic for quantum chemists, especially when you want to navigate the more mathematics heavy literature.

Recommended reading:
- ...


## Calculus of Variations

Calculus of variations deals with the optimization of nonlinear functionals, functions that map _functions_ to scalars. Calculus of variations generalizes vector calculus to infinite dimensions, and as such could also be called "nonlinear functional analysis". Calculus of variations is the correct framework for variational formulations of the laws of nature, from quantum field theory and QED to Hamilton's equations of motion. Moreover, nonlinear approximations to the molecular Schrödinger equation such as Hartree-Fock is naturally formulated in this language.

To have a basic grasp of calculus of variations is almost essential to quantum chemists. A basic knowledge does not require advanced functional analysis, even if the above paragraph gives such an expression.

Calculus of variations is thus an exceedingly important topic in quantum chemistry.

Recommended reading:
- Goldstein, Safko and Poole, "Classical Mechanics"
- Zeidler, "Nonlinear functional analysis"
- ...

## $\heartsuit$ Ordinary differential equations

Ordinary differential equations (ODEs) describe initial value and boundary value problems of scalar quantities, or coupled such equations. From classical mechanics to rate equations, ODEs permeate theoretical chemistry, and having a basic understanding of essential mathematical results is absolutely essential.

Recommended reading:
* ...

## Partial differential equations

Partial differential equations (PDEs) generalize ODEs to infinite dimensions, i.e., initial and boundary value problems where the unknown is no longer a scalar or a vector, but an element in a function space. Laws such as Einstein's gravitation theory, transport of heat, chemical reaction-diffusion systems, Maxwell's equations, the various Schrödinger equations, are all PDEs.

PDEs are very important for quantum chemistry.

Recommended reading:
* ...
* ...

## Operator algebra

In operator algebra, one studies algebras of operators over linear spaces, often Hilbert spaces. The algebras are often given structures inspired by quantum mechanics, such as canonical anticommutator or canonical commutator relations, e.g. the CAR and CCR algebras. It is a highly abstract branch of pure mathematics, and understanding the basic notions and results may be very useful for the study of manybody theory and quantum field theories.

Recommended reading:
- ...
- ...






## Numerical analysis

Most equations in quantum chemistry cannot be solved analytically, and must be approximated in finite precision arithmetic on computers. This is the area of numerical analysis. Here, numerical methods for differential equations are studied, as well as numerical linear algebra and eigenvalue finding algorithms, to name some topics.

Numerical analysis is very important for developing and understanding computer implementations of quantum chemistry algorithms.

Recommended reading:
* ...

## Optimization and root finding

Optimization, really a subfield of numerical analysis, deals with finding local or global extremal points of functions of several variables, as well as finding roots of systems of nonlinear equations. There are a multitude of algorithms, such as the method of steepest descent, Newton, and quasi-Newton methods. A very important topic for students of quantum chemistry, as many computational problems end up as an optimization problem.

Recommended reading:
- ...
- 