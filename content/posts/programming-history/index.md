---
title: "The History of Programming Languages"
date: 2023-07-29
draft: false
---

The word computer was in use from the early 17th century. Originally, a computer was a job, a person who performed calculations.

The first programmable [computer](https://en.wikipedia.org/wiki/Computer?useskin=vector#firstHeading) was invented by [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage) in 1822, called the [Difference Engine](https://en.wikipedia.org/wiki/Difference_engine?useskin=vector). Which was designed to tabulate [polynomial](https://en.wikipedia.org/wiki/Polynomial) functions. Charles would go on to design many more computers before his death in 1871, sadly he was never able to complete construction of his machines due to conflicts with his chief engineer and inadequate funding.

One of these was the '[Babbage's Analytical Engine](https://en.wikipedia.org/wiki/Analytical_engine?useskin=vector)'. First described in 1837 as the successor to the [Difference Engine](https://en.wikipedia.org/wiki/Difference_engine?useskin=vector). The design used an arithmetic logic unit, if/else, loops, and integrated memory. Making it the first design for a general-purpose, Turing complete, computer.

[Ada Lovelace](https://en.wikipedia.org/wiki/Ada_Lovelace?useskin=vector) is often credited as the first computer programmer. She worked closely with [Charles](https://en.wikipedia.org/wiki/Charles_Babbage) and was the first to recognize that the machine had applications outside of calculation. She wrote the first published computer program, for use to compute [Bernoulli numbers](https://en.wikipedia.org/wiki/Bernoulli_number).

Another influential figure in this field was [Alan Turing](https://en.wikipedia.org/w/index.php?title=Alan_Turing&useskin=vector). Known for his decryption of the cipher used in the [Enigma machine](https://en.wikipedia.org/wiki/Enigma_machine?useskin=vector), helping the Allies to defeat the Axis powers, and win World War 2. He also wrote [Turing's proof](https://en.wikipedia.org/wiki/Turing%27s_proof?useskin=vector), proving that there are some mathematical problems that can never be solved with computers. He came up with the concept of a [Turing machine](https://en.wikipedia.org/wiki/Turing_machine?useskin=vector), the [Turing test](https://en.wikipedia.org/wiki/Turing_test?useskin=vector) (a way of testing the ability of a computer to exhibit intelligent behaviour), and more.

However, it wasn't until the mid-20th century that the first true programming languages were developed. The first one we will be looking at is Fortran.

## [Fortran](https://en.wikipedia.org/wiki/Fortran?useskin=vector)

Fortran was originally developed by [IBM](https://en.wikipedia.org/wiki/IBM "IBM") in the 1950s, made as a more practical alternative to assembly. Fortran got its name from 'formula translation', and dominated scientific computing. It is popular for high performance computing, and has been in use for decades in areas such as weather, fluid dynamics, geophysics, and more.

The [Fortran syntax](https://ourcodingclub.github.io/tutorials/fortran-intro/#basics) seems very alien compared to modern, dynamic languages like Python and R. You have to explicitly start and end the program, and optionally give it a name. Then you (usually) write implicit none, as without it, by default, all variables starting with i, j, k, l, m, and m are assumed to be integers and the others 'real' arguments.

Variables are typically declared at the top of the program, with `INTEGER`, for whole numbers, `REAL`, for non integer numbers, and `LOGICAL` for boolean values. You declare strings with the character keyword, but have to define the length in characters. Although t's worth noting that modern Fortran also supports concise and flexible variable declarations.

The syntax for if statements is quite similar to that of VBA, as you have to write `THEN`, and `END IF`. Fortran uses `READ`, to get input from the keyboard, and `WRITE` to print to the screen. It's mainly designed for mathematical operations, and has many built-in functions for this, like `+, -, *, /` and `SQRT()`, as well as an extensive library of functions, and routines for more complex calculations. This is one of its main strengths in scientific computing.

Fortran is known for its '[array](https://en.wikipedia.org/wiki/Array_(data_structure)?useskin=vector) operations', or the ability to perform operations on entire arrays at once, without needing to use a loop. These are highly efficient and useful for scientific computing and working with large data sets. Another popular feature is its native [parallel computing](https://en.wikipedia.org/wiki/Parallel_computing?useskin=vector) capabilities. Parallel computing, which is a method of computing tasks by breaking them down into smaller chunks that can be processed simultaneously on different units, significantly improving performance.

Fortran 2003 and later introduced modern programming features such as [object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming?useskin=vector), based on the concepts of objects that can contain data and code. Modern Fortran also has good [interoperability](https://en.wikipedia.org/wiki/Fortran?useskin=vector#:~:text=Interoperability%20with%20the%20C%20programming%20language) with other programming languages. Making it easier to integrate Fortran code with [C](https://en.wikipedia.org/wiki/C_(programming_language)?useskin=vector), [C++](https://en.wikipedia.org/wiki/C%2B%2B?useskin=vector), and others.

Fortran's influence in the history of programming has been substantial, indirectly inspiring the development of later languages such as [BASIC](https://en.wikipedia.org/wiki/BASIC) & [C](https://en.wikipedia.org/wiki/C_(programming_language)?useskin=vector). It is being updated to this day, with the latest stable release (at time of recording) being in 2018. Its extensive usage in legacy systems and its specialized features for scientific and high-performance computing mean that Fortran will likely continue to be used by scientists and engineers for decades to come.

## [COBOL](https://en.wikipedia.org/wiki/COBOL?useskin=vector)

In the late 1950s, programming was obscenely expensive. A survey found that with a data processing instillation, the programming alone cost $800,000 on average. Someone **HAD** to do something. It was getting out of hand. Luckily, it also found that—thank God—if a business-oriented language were used, it would be much cheaper and faster. Hooray!

On the 8th of April 1959, [Mary Hawes](https://en.wikipedia.org/wiki/Mary_Hawes), called a meeting, to organize a formal meeting on 'common business languages'. At the meeting, the group asked the [Department of Defence](https://en.wikipedia.org/wiki/United_States_Department_of_Defense) to sponsor the creation of what would become [COBOL](https://en.wikipedia.org/wiki/COBOL?useskin=vector), they agreed.

Grace Hopper is often referred to as 'The Mother of COBOL', and for good reason. She served as a technical consultant to the committee that decided on the creation of COBOL. COBOL was even based on her language, FLOW-MATIC, extending it with ideas from the IBM equivalent, [COMORAN](https://en.wikipedia.org/wiki/COMTRAN "COMTRAN"). Not only did FLOW-MATIC shape the development of COBOL, it was also the **first** English-like data processing language, whatever that means.

A COBOL program is structured into four essential [divisions](https://www.tutorialspoint.com/cobol/cobol_program_structure.htm#:~:text=Divisions), each serving a specific purpose in organizing the code.

The first and only mandatory division is the `IDENTIFICATION DIVISION`, used by the compiler and readers to identify the program. You **must** set a `PROGRAM-ID`, providing a name for your COBOL program.

The next division is the `ENVIRONMENT DIVISION`, where you specify information about the system on which the program was compiled and the system on which it will be executed. Additionally, it allows you to define external data sets and files used by the program. This provides the necessary context for the program's environment.

After that, the `DATA DIVISION`, arguably one of the most crucial sections of a COBOL program. In this division, you describe the data structures used by the program, including the layout and characteristics of data files, working storage variables, and records. COBOL's strength lies in its ability to handle vast amounts of data, making the `DATA DIVISION` integral to handling large-scale business processes.

Finally, we have the `PROCEDURE DIVISION`, which contains the actual logic of the COBOL program. Here, you'll write the logic for the program, such as calculations, input/output operations, and if/else statements. You can use statements, including `DISPLAY` to print output to the screen, or `IF`, `ELSE`, and `END-IF` to make decisions.

## Sources
- [The History of Computers](https://www.bricsys.com/en-gb/blog/who-invented-computers) - Bricsys
- [Computer](https://en.wikipedia.org/wiki/Computer) – Wikipedia
- [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage) – Wikipedia
- [Difference Engine](https://en.wikipedia.org/wiki/Difference_engine) – Wikipedia
- [Polynomial](https://en.wikipedia.org/wiki/Polynomial) – Wikipedia
- [Fortran](https://en.wikipedia.org/wiki/Fortran) – Wikipedia
- [Introduction to Fortran](https://ourcodingclub.github.io/tutorials/fortran-intro/) – Our Coding Club
- [Implicit None Statement in Fortran](https://www.bottomscience.com/implicit-none-statement-how-to-use-it-fortran/) – Bottom Science
- [Introduction to COBOL](https://www.mainframestechhelp.com/tutorials/cobol/introduction.htm) – Mainframes Tech Help
- [Beginner's Guide to COBOL Made Easy](https://scribe.rip/modern-mainframe/beginners-guide-cobol-made-easy-introduction-ecf2f611ac76) – Scribe
- [COBOL Tutorial](https://www.tutorialspoint.com/cobol/index.htm) – TutorialsPoint
- [COBOL](https://en.wikipedia.org/wiki/COBOL?useskin=vector#History_and_specification) – Wikipedia
- [Parallel computing](https://en.wikipedia.org/wiki/Parallel_computing?useskin=vector) – Wikipedia
- [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming?useskin=vector) – Wikipedia
- [COBOL Docs](https://www.ibm.com/docs/en/cobol-zos) – IBM
- [Analytical Engine](https://en.wikipedia.org/wiki/Analytical_engine?useskin=vector) – Wikipedia
- [Ada Lovelace](https://en.wikipedia.org/wiki/Ada_Lovelace?useskin=vector) – Wikipedia
- [Bernoulli numbers](https://en.wikipedia.org/wiki/Bernoulli_number) – Wikipedia
- [Turing Test](https://en.wikipedia.org/wiki/Turing_test?useskin=vector) – Wikipedia
- [Turing Machine](https://en.wikipedia.org/wiki/Turing_machine?useskin=vector) – Wikipedia
- [Alan Turing](https://en.wikipedia.org/w/index.php?title=Alan_Turing&useskin=vector) – Wikipedia
- [Enigma machine](https://en.wikipedia.org/wiki/Enigma_machine?useskin=vector) – Wikipedia
- [Turing's proof](https://en.wikipedia.org/wiki/Turing%27s_proof?useskin=vector) – Wikipedia
- [Turing test](https://en.wikipedia.org/wiki/Turing_test?useskin=vector) – Wikipedia
- [Grace Hopper](https://en.wikipedia.org/wiki/Grace_Hopper?useskin=vector) – Wikipedia
- [Computer (occupation)](https://en.wikipedia.org/w/index.php?title=Computer_%28occupation%29&useskin=vector)  – Wikipedia
- [Basic](https://en.wikipedia.org/wiki/BASIC?useskin=vector) – Wikipedia

# THIS IS NOT FINISHED
it's set as not a draft so i can show it to people, im working on BASIC rn
