prefacio.rst
============

A_Practical_Approach_Dynamical_Systems_Engineers_Patricia_PREF

A Practical
Approach to
Dynamical Systems
for Engineers
PATRICIA MELLODGE

PREFACE

Dynamical systems are an important topic in engineering. Applications are prevalent within mechanical, electrical, and biomedical engineering 
and can be found within robotic, automotive, aerospace, and human systems, among others. The purpose of this book is to present dynamical 
systems topics in a way that is relevant for practicing engineers. It is intended for engineers who need to understand both the background 
theory and how to apply it. As such, there is an attempt to create a bridge between the theory and the application. Every abstract concept is 
discussed in depth, described in a readable and down-to-earth manner, and illustrated using practical examples. The intended audience is 
engineers who are working in industry, graduate students who are taking courses or doing research related to dynamical systems, and 
undergraduate students who are taking courses in control systems. This is not a textbook, and there are no end-of-chapter problems. Rather, it 
should be considered an application guide for those in the trenches of working with and learning about dynamical systems.
—-----------------------------------------------------
Los sistemas dinámicos son un tema importante en ingeniería. Las aplicaciones prevalecen en la ingeniería mecánica, eléctrica y biomédica y se 
pueden encontrar en sistemas robóticos, automotrices, aeroespaciales y humanos, entre otros. El propósito de este libro es presentar temas de 
sistemas dinámicos de una manera que sea relevante para los ingenieros en ejercicio. Está dirigido a ingenieros que necesitan comprender tanto 
la teoría básica como cómo aplicarla. Como tal, hay un intento de crear un puente entre la teoría y la aplicación. Cada concepto abstracto se 
discute en profundidad, se describe de manera legible y práctica, y se ilustra con ejemplos prácticos. El público objetivo son ingenieros que 
trabajan en la industria, estudiantes de posgrado que toman cursos o realizan investigaciones relacionadas con sistemas dinámicos y estudiantes 
de pregrado que toman cursos en sistemas de control. Este no es un libro de texto y no hay problemas al final del capítulo. Más bien, debe 
considerarse una guía de aplicación para aquellos que están en las trincheras de trabajar y aprender sobre sistemas dinámicos.
—-----------------------------------------------------


It is assumed that readers have a solid mathematical foundation in calculus, differential equations, and matrix theory. In presenting the 
material, the emphasis is on applying the theory, so there are relatively few theorems and no proofs. However, there is a lot of mathematics. 
Much mathematical detail is given that is missing from other texts on these topics. The reason for this level of detail is to help readers 
understand the complete application in real-world systems. The focus is on depth and not breadth. In covering the selected topics at this level 
of detail, unfortunately, the number of topics had to be limited. As such, this is not a complete and comprehensive presentation of all topics 
in dynamical systems. However, this book attempts to cover many relevant topics that an engineer in the field would encounter and provide a 
foundational understanding for further study.

—-----------------------------------------------------

Se supone que los lectores tienen una base matemática sólida en cálculo, ecuaciones diferenciales y teoría de matrices. Al presentar el 
material, el énfasis está en la aplicación de la teoría, por lo que hay relativamente pocos teoremas y ninguna prueba. Sin embargo, hay muchas 
matemáticas. Se dan muchos detalles matemáticos que faltan en otros textos sobre estos temas. El motivo de este nivel de detalle es ayudar a los 
lectores a comprender la aplicación completa en los sistemas del mundo real. El foco está en la profundidad y no en la amplitud. Al cubrir los 
temas seleccionados con este nivel de detalle, lamentablemente, el número de temas tuvo que ser limitado. Como tal, esta no es una presentación 
completa y comprensiva de todos los temas en sistemas dinámicos. Sin embargo, este libro intenta cubrir muchos temas relevantes que un ingeniero 
en el campo encontraría y proporciona una comprensión fundamental para un estudio posterior.
—-----------------------------------------------------

It is also assumed that the reader has some understanding of MATLAB and Simulink, although expertise is not required. Many of the concepts are 
demonstrated using real-world examples in MATLAB or Simulink. For the earlier chapters, the MATLAB code is explained line by line to show how 
various concepts are implemented. These explanations are gradually decreased throughout the book.
—-----------------------------------------------------

También se supone que el lector tiene algún conocimiento de MATLAB y Simulink, aunque no se requiere experiencia. Muchos de los conceptos se 
demuestran mediante ejemplos del mundo real en MATLAB o Simulink. En los capítulos anteriores, el código de MATLAB se explica línea por línea 
para mostrar cómo se implementan varios conceptos. Estas explicaciones se reducen gradualmente a lo largo del libro.
—-----------------------------------------------------


The book transitions from topics commonly found at the undergraduate level in engineering, to those covered in graduate courses, to those that 
engineers may never see in a course. As such, the coverage changes in its approach and assumptions about what the reader knows. The layout of 
the topics is as follows. Chapter 1 introduces dynamical systems, provides motivation for why it’s important to study them, and discusses 
different types of systems. This material should be familiar from undergraduate engineering courses in linear systems and control theory. There 
is high-level discussion of this material, but the mathematics starts early with definitions of the different classes of systems.
—-----------------------------------------------------

El libro hace una transición de los temas que se encuentran comúnmente en el nivel de pregrado en ingeniería, a los que se cubren en los cursos 
de posgrado, a los que los ingenieros nunca verán en un curso. Como tal, la cobertura cambia en su enfoque y supuestos sobre lo que sabe el 
lector. La disposición de los temas es la siguiente. El Capítulo 1 presenta los sistemas dinámicos, proporciona motivación sobre por qué es 
importante estudiarlos y analiza los diferentes tipos de sistemas. Este material debe ser familiar de los cursos de ingeniería de pregrado en 
sistemas lineales y teoría de control. Hay una discusión de alto nivel sobre este material, pero las matemáticas comienzan temprano con 
definiciones de las diferentes clases de sistemas.
—-----------------------------------------------------


Chapter 2 discusses modeling and covers differential and difference equations, transfer functions, state-space models, eigenvalues, 
eigenvectors, and singular value decomposition. Although many of these topics are familiar from courses in differential equations, control 
systems, and linear algebra, the emphasis is on putting them in the context of dynamical systems. There is also an emphasis on working through 
examples in MATLAB and giving details of the implementation, which may not be covered in those courses.

—-----------------------------------------------------
El Capítulo 2 analiza el modelado y cubre ecuaciones diferenciales y en diferencias, funciones de transferencia, modelos de espacio de estado, 
valores propios, vectores propios y descomposición de valores singulares. Aunque muchos de estos temas son familiares de los cursos de 
ecuaciones diferenciales, sistemas de control y álgebra lineal, el énfasis está en ponerlos en el contexto de los sistemas dinámicos. También se 
hace hincapié en trabajar con ejemplos en MATLAB y dar detalles de la implementación, que pueden no estar cubiertos en esos cursos.
—-----------------------------------------------------

Chapter 3 focuses on solutions of dynamical equations, equilibrium points, and stability. These concepts are often encountered in introductory 
graduate-level courses in dynamical systems and control theory. Again, the emphasis is not on deriving the results but applying them. As such, 
several of the relevant theorems are presented and applied.
—-----------------------------------------------------

El Capítulo 3 se enfoca en soluciones de ecuaciones dinámicas, puntos de equilibrio y estabilidad. Estos conceptos se encuentran a menudo en 
cursos introductorios de posgrado en sistemas dinámicos y teoría de control. Una vez más, el énfasis no está en derivar los resultados sino en 
aplicarlos. Como tal, se presentan y aplican varios de los teoremas relevantes.
—-----------------------------------------------------

Chapter 4 discusses nonlinear systems and some rich behavior that is only found in them such as limit cycles, bifurcations, chaos, and 
linearization. These are topics typically found in graduate-level engineering courses. There is a minimal amount of theoretical coverage, and 
the behaviors are described through examples.
—-----------------------------------------------------
El Capítulo 4 analiza los sistemas no lineales y algunos comportamientos ricos que solo se encuentran en ellos, como los ciclos límite, las 
bifurcaciones, el caos y la linealización. Estos son temas que normalmente se encuentran en los cursos de ingeniería de nivel de posgrado. Hay 
una cantidad mínima de cobertura teórica y los comportamientos se describen a través de ejemplos.

—-----------------------------------------------------

Finally, Chapter 5 introduces Hamiltonian systems, which typically fall in the realm of physicists. However, undamped vibrational systems and 
their equivalent are an important class of Hamiltonian systems, and there is much rich theory in this area. As with Chapter 4, there is minimal 
theoretical coverage, and the focus is placed more on the introduction of the
concepts through examples.
—-----------------------------------------------------
Finalmente, el Capítulo 5 presenta los sistemas hamiltonianos, que normalmente caen en el ámbito de los físicos. Sin embargo, los sistemas 
vibracionales no amortiguados y sus equivalentes son una clase importante de sistemas hamiltonianos, y existe una teoría muy rica en esta área. 
Al igual que con el Capítulo 4, hay una cobertura teórica mínima y el enfoque se pone más en la introducción de los conceptos a través de 
ejemplos.
—-----------------------------------------------------


Many people contributed to the creation of the book. Acknowledgement
goes out to colleagues and students at the University of Hartford,
particularly Lee Townsend and Iman Salehi for their supportive ideas and
engaging discussion; colleagues in the van Rooy Center for Complexity
and Conflict Analysis for the productive biweekly meetings; Harriet
Clayton and Glyn Jones at Elsevier for the support and feedback; and Joe
Romagnano for his editorial skills.

—-----------------------------------------------------








