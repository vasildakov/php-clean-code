# Anti Patterns


## Code Smells
(Def) Code smells are similar to anti-patterns, but not quite as formal. If code smells, then that smell can be o.k. 
(like some cheese) or it can be bad, possibly indicating a deeper problem. Kent Beck introduced the idea in 
the late 1990s and Martin Fowler made it popular in his book Refactoring. Improving the Design of Existing Code.[10] 
You can use tools, such as FindBugs, Checkstyle or PMD to find bad smells. Usually refactoring is used to remove 
the offending odor. Martin Fowler and Joshua Kerievsky, among others, provide the appropriate refactorings.

(Def) Code smells are usually not bugs; they are not technically incorrect and do not prevent the program from 
functioning. Instead, they indicate weaknesses in design that may slow down development or increase the risk of bugs 
or failures in the future. Bad code smells can be an indicator of factors that contribute to technical debt. 
Robert C. Martin calls a list of code smells a "value system" for software craftsmanship.

### Duplicate Code
This smell is very similar to the Copy and Paste anti-pattern. You can use the PMD Tool Copy/Paste Detector to find the 
problematic areas.



## Software Peter principle
The Software Peter principle is used in software engineering to describe a dying project which has become too complex 
to be understood even by its own developers. It is well known in the industry as a silent killer of projects, but by 
the time the symptoms arise it is often too late to do anything about it. Good managers can avoid this disaster by 
establishing clear coding practices where unnecessarily complicated code and design is avoided.

### Causes
#### Loss of conceptual integrity
Conceptual integrity is achieved when the software’s design proceeds from a small number of agreeing individuals. 
For software to maintain conceptual integrity, the design must be controlled by a single, small group of people who 
understand the code (including the nature of how all the subroutines and variables interact) in depth.

In projects without a strong software architecture team, the task of design is often combined with the task of 
implementation and is implicitly delegated among the individual software developers. Under these circumstances, 
developers are less likely to sacrifice personal interests in favor of the interests of the product. The complexity 
of the product grows as a result of developers adding new designs and altering earlier ones to reflect changes in 
fashion and individual taste.
Programmer incompetence

#### Programmer incompetence
Good software developers understand the importance of communicating with people over communicating with the computer, 
according to Code Complete. Studies showed that programmers spends more than 50% of their time communicating with 
people, while the actual programming may only take up as little as 15% to 10%, depending on the level of seniority.

Maintenance programmers spend 50 to 60 percent of their time trying to understand the code they have to maintain and a 
software program will have, on average, 10 generations of maintenance programmers in its lifetime.

#### Programmer inexperience
Programmers sometimes make implementation choices that work but have unintended negative consequences. The most common 
of these mistakes are cataloged and referred to as smells in the book Refactoring. Over time, many such 
implementation choices degrade the software’s design, making it increasingly difficult to understand.

## Further Reading

- Laplante, Phillip A. (2005). Antipatterns: Identification, Refactoring and Management. Auerbach Publications. ISBN 0-8493-2994-9.
- Brown, William J. (2000). Anti-Patterns in Project Management. John Wiley & Sons, ltd. ISBN 0-471-36366-9.
- Brown, William J. (1998). AntiPatterns: Refactoring Software, Architectures, and Projects in Crisis. John Wiley & Sons, ltd. ISBN 0471197130. 
- Kerievsky, Joshua (2004). Refactoring to Patterns. Addison-Wesley Professional. ISBN 0321213351.
- Feathers, Michael (2004). Working Effectively with Legacy Code. Prentice Hall. ISBN 0131177052.

## Links
- https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering/Architecture/Anti-Patterns
- 