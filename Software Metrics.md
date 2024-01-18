# Software Metrics

## Code coverage
In software engineering, code coverage is a percentage measure of the degree to which the source code of a program is 
executed when a particular test suite is run. A program with high test coverage has more of its source code executed 
during testing, which suggests it has a lower chance of containing undetected software bugs compared to a program with 
low test coverage.

## Cohesion
In computer programming, cohesion refers to the degree to which the elements inside a module belong together.[1] In one sense, it is a measure of the strength of relationship between the methods and data of a class and some unifying purpose or concept served by that class. In another sense, it is a measure of the strength of relationship between the class's methods and data themselves.

Cohesion is an ordinal type of measurement and is usually described as “high cohesion” or “low cohesion”. Modules with high cohesion tend to be preferable, because high cohesion is associated with several desirable traits of software including robustness, reliability, reusability, and understandability. In contrast, low cohesion is associated with undesirable traits such as being difficult to maintain, test, reuse, or even understand.

Cohesion is often contrasted with coupling. High cohesion often correlates with loose coupling, and vice versa.[2] The software metrics of coupling and cohesion were invented by Larry Constantine in the late 1960s as part of Structured Design, based on characteristics of “good” programming practices that reduced maintenance and modification costs. Structured Design, cohesion and coupling were published in the article Stevens, Myers & Constantine (1974)[3] and the book Yourdon & Constantine (1979);[1] the latter two subsequently became standard terms in software engineering.

## Coupling
In software engineering, coupling is the degree of interdependence between software modules; a measure of how closely 
connected two routines or modules are;[1] the strength of the relationships between modules.

Coupling is usually contrasted with cohesion. Low coupling often correlates with high cohesion, and vice versa. 
Low coupling is often thought to be a sign of a well-structured computer system and a good design, and when combined 
with high cohesion, supports the general goals of high readability and maintainability.

## Cyclomatic complexity

Cyclomatic complexity is a software metric used to indicate the complexity of a program. It is a quantitative measure of the number of linearly independent paths through a program's source code. It was developed by Thomas J. McCabe, Sr. in 1976.

Cyclomatic complexity is computed using the control-flow graph of the program: the nodes of the graph correspond to indivisible groups of commands of a program, and a directed edge connects two nodes if the second command might be executed immediately after the first command. Cyclomatic complexity may also be applied to individual functions, modules, methods or classes within a program.

One testing strategy, called basis path testing by McCabe who first proposed it, is to test each linearly independent path through the program; in this case, the number of test cases will equal the cyclomatic complexity of the program.[1]

## Source lines of code
Source lines of code (SLOC), also known as lines of code (LOC), is a software metric used to measure the size of a 
computer program by counting the number of lines in the text of the program's source code. SLOC is typically used to 
predict the amount of effort that will be required to develop a program, as well as to estimate programming 
productivity or maintainability once the software is produced.
