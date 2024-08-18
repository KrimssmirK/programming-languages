# Chapter 1 Review Questions

1. Why is it useful for a programmer to have some background in language design, even though he or she may never actually design a programming language?

It gives an idea what programming language is better to use in target domain. It will allow us to learn new programming languages quickly because you aware of universal concept of programming language.

2. How can knowledge of programming language characteristics benefit the whole computing community?

Computing community will be wise of utilizing the programming languages based on their pros and cons and community will be quick to develop more advance algorithm.

3. What programming language has dominated scientific computing over the past 50 years?

FORTRAN - It has more floating point arithmetic operations feature.

4. What programming language has dominated business applications over the past 50 years?

COBOL - COmmon Business Oriented Language

5. What programming language has dominated artificial intelligence over the past 50 years?

LISP - Linked List is used commonly to process symbolic computation.

6. In what language is most of UNIX written?

C - Unix is a secure operating system. It works only on commands and scripts along with read, write , and execute permission for each file.

7. What is the disadvantage of having too many features in a language?

It affects the readability of programming language. Extra features can lead to more verbose code, as developers might use additional features even when simpler constructs would suffice. This can make the codebase harder to read and maintain.

8. How can user-defined operator overloading harm the readability of a program?

The intuition of that operator will be destroyed and it is not easy to read code.

9. What is one example of a lack of orthogonality in the design of C?

Incrementing pointers over the primitive types. Adding one to the pointer means add the size of the type of the data not by one and adding one to the primitive types is just adding one and these are inconsistent for same operation that leads to be lack of orthogonality.

10. What language used orthogonality as a primary design criterion?

Ada

11. What primitive control statement is used to build more complicated control statements in languages that lack them?

In languages that lack more complex control statements, the primitive control statement often used to build more complicated ones is the **"branch"** statement. This typically refers to:

- **"goto"**: A statement that transfers control to a different part of the program, identified by a label. While "goto" can be used to implement complex control flow, it is often criticized for making code harder to understand and maintain.

Another primitive construct that is frequently employed in such languages is:

- **"conditional" or "if-else" statements**: These allow for branching based on conditions and can be combined to create more complex control flows.

In essence, by combining "goto" statements with conditional logic, or by using basic conditional statements, programmers can construct more sophisticated control structures even in languages that don't natively support them.

12. What construct of a programming language provides process abstraction?

functions, classes, objects, modules

13. What does it mean for a program to be reliable?

A program that runs within requirements in any conditions.

14. Why is type checking the parameters of a subprogram important?

to allocate properly the data into memory and avoid running the program into error

15. What is aliasing?

It refers to the name that points to another that has the same context and functionality.

16. What is exception handling?

Catch the expected error to continue run the program and to avoid stop running the program.

17. Why is readability important to writability?

To quickly know where to fix bugs or add more features because of the readability that leads to more maintainable.

18. How is the cost of compilers for a given language related to the design of that language?

Design or hierarchy of processing the language into machine understandable language might have different steps that has more or less steps that affects running time of compiling and to construct the compiler that takes more time to develop.

19. What have been the strongest influences on programming language design over the past 50 years?

Operating System Design and Hardware Constraints

Software Engineering Principles

20. What is the name of the category of programming languages whose structure is dictated by the von Neumann computer architecture?

imperative programming languages

21. What two programming language deficiencies were discovered as a result of the research in software development in the 1970s?

Lack of Modularity and Abstraction (eg C and FORTRAN)

Inadequate Support for Data Abstraction and Type Safety

22. What are the three fundamental features of an object-oriented programming language?

inheritance, polymorphism, encapsulation

23. What language was the first to support the three fundamental features of object-oriented programming?

Simula (for simulation) -> Smalltalk (more popular)

24. What is an example of two language design criteria that are in direct conflict with each other?

Readability and Writability

Efficiency and Ease of Use (traid-off)

eg 

C (it is fast but it is complex) 

Python (it is readable but it is slower than C)

25. What are the three general methods of implementing a programming language?

Compilation (C)

Interpretation (Python, Ruby, Javascript)

Hybrid (Java, C#)

26. Which produces faster program execution, a compiler or a pure interpreter?

a compiler

27. What role does the symbol table play in a compiler?

to refer to the additional information about the token

Storing Symbol Information

Scope Management

Type Checking

Symbol Resolution

Memory Management

Error Detection

28. What does a linker do?

It links other resources like module, library, or external resources.

In essence, the linker is responsible for assembling all the pieces of compiled code into a cohesive and executable program. It resolves symbols, adjusts addresses, integrates library code, and ensures that the final executable is properly configured for execution on the target system.

29. Why is the von Neumann bottleneck important?

to reduce the complexity of the architecture and to further implement programming language efficiently

The von Neumann bottleneck is important because it highlights a fundamental limitation in the design of traditional computer architectures, impacting overall system performance. By understanding and addressing this bottleneck, engineers and architects can develop more efficient systems and design innovations to improve computing performance and resource utilization.

30. What are the advantages in implementing a language with a pure interpreter?

You could detect the error quickly and easy to debug.

Implementing a language with a pure interpreter provides advantages such as immediate execution, ease of implementation, support for dynamic features, platform independence, interactive development, and easier debugging. These benefits make interpreted languages particularly well-suited for scripting, rapid development, and educational purposes. However, it’s important to note that while pure interpreters offer these advantages, they may also lead to performance drawbacks compared to compiled languages.


