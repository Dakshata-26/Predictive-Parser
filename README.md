# Predictive-Parser

The objective of this project is to implement an efficient and robust LL(1) parser using a high level programming language, that is capable of correctly parsing any input fed to it. LL(1) Parser is a Predictive parser. 

The LL(1) Parser is a Top-Down Parser that does not require any back-tracking. It is also called a Non-Recursive Parser.

Here the 1st L represents that the scanning of the Input will be done from Left to Right manner and the second L shows that in this parsing technique we are going to use Left most Derivation Tree. And finally, the 1 indicates that the grammar uses a look ahead of one source symbol- that is the prediction to be made is determined by the next source symbol.

The project includes a set of predefined grammar which is evaluated by LL(1) parser program and the parsing table is created and displayed. The implementation is pretty straightforward and simple. Then it would take any input string belonging to the grammar language and would find the FIRST and FOLLOW sets of the grammar.
