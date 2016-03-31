# DISMATH Portfolio - patrickarevalo
dismathportfolio-patrickarevalo created by Classroom for GitHub

##Week 1:
-Discrete Mathematics (DISMATH), a strange but fascinating course, was introduced to us by Dr. Melvin Cabatuan
####This week I learned that:

* There are many different kinds of truths such as Legal Truth, Authoritative Truth, Scientific Truth, Probable Truth, and Philosophical truth but in DISMATH, we only
deal in *Mathematical Truths*
* **Propositions** are declarative statements that are either True of False but **never** both
* Propositions have a Truth Value of TRUE(1) if tit is true and FALSE(0) if it is false
* Propositions can be expressed in letters such as p, q, r and are called **Propostitional Variables**
* **Compound Propositions** are propositions that are constructed by combining one or more propositions using *Logical Operators*
* **Logical Operators** are used to combine propositions

|Symbol|Logical Operator|Usage   |Logical Expression  |Formula                             |
|:----:|:--------------:|:------:|:------------------:|:----------------------------------:|
|¬     |Negation        |not     |¬p                  |val(¬p) = -val(p)                   |                
|∨     |Disjunction     |or      |p∨q                 |val(p∨q) = max(val(p), val(q))      |
|∧     |Conjunction     |and     |p∧q                 |val(p∧q) = min(val(p), val(q))      |
|⊕     |Exclusive Or    |xor     |p⊕q ≡ (¬p∧q)∨(p∧¬q) |if val(p) ≠ val(q) = 1 , otherwise 0|
|→     |Conditional     |if..then|p→q ≡ ¬q → ¬p ≡ ¬p∨q|if val(p) ≤ val(q) = 1 , otherwise 0|
|↔     |Bi-Conditional  |iff     |p↔q                 |if val(p) = val(q) = 1 , otherwise 0|
 
* **Truth Table** is a table displaying all possible truth values of propositions
* Truth Table is the first tool for proving
* The rows of the truth Table is determined by 2^n, where n is the number of variable used
* Truth Table for Logical Operators:

|p  |q  |¬p |p∨q|p∧q|p⊕q|p→q|p↔q| 
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|F  |T  |T  |T  |F  |T  |T  |F  |
|F  |F  |T  |F  |F  |F  |T  |T  |
|T  |T  |F  |T  |T  |F  |T  |T  |
|T  |F  |F  |T  |F  |T  |F  |F  |

* Be careful in using the Truth Table especially when solving grouped propositions!!!

-The First Week of DISMATH was quite tricky since it was the my first time to encounter those symbols.


##Week 2:
####This week I learned that:
* **Logical Equivalences** are compund propositions that give a definite value 
* Logical Equivalences is the second tool for proving
* Logical Equivalences are somewhat like algebraic laws
* The Logical Equivalences include:

|Name |Equivalence |
|:---:|:-----:|
|Identity Law|p∧T ≡ p  <br>  p∨F ≡ p|
|Domination Law|p∧F ≡ p  <br>  p∨T ≡ T|
|Idempotent Law|p∧p ≡ p  <br>  p∨p ≡ p|
|Double Negation Law|¬(¬p) ≡ p|
|Commutative Law|p∨q ≡ q∨p  <br>  p∧q ≡ q∧p|
|Associative Law|(p∨q)∨r ≡ p∨(q∨r)  <br>  (p∧q)∧r ≡ p∧(q∧r)|
|Distributive Law|p∨(q∧r) ≡ (p∨q)∧(p∨r)  <br>  p∧(q∨r) ≡ (p∧q)∨(p∧r)|
|De Morgan's Law|¬(p∧q) ≡ ¬p∨¬q  <br>  ¬(p∨q) ≡ ¬p∧¬q|
|Absorption Law|p∨(p∧q) ≡ p  <br>  p∧(p∨q) ≡ p|
|Negation Law|p∧¬p ≡ F  <br>  p∨¬p ≡ T|

* Logical Equivalences was already introduced the previous week but was discussed in more detail in week 2 :)


##Week 3:
####This week I learned that:
* __Quantifiers__
	- **Existential Quantifiers** ∃x P(x) the proposition is true as long as there exist a value of x that is true
	- **Universal Quantifiers** ∀xP(x) the proposition is true as long as all values of x are true
* **Tautology** is a statement that is *always* true


##Week 4:
####This week I learned that:
* An **Argument** is a sequence of premises that lead to a conclusion
* An argument is **Valid** if the premises as well as the conclusion are all true
* If an argument is invalid then it is considered at **Fallacy**
* **Rules of Inference** is used to prove arguments that may be tiresome to prove using the Truth Table
* Rules of Inference is the third tool in proving
* The Rules of Inference are shown below:

|Rule of Inference       |Tautology            |Name                  |
|:----------------------:|:-------------------:|:--------------------:|
|p <br> p→q <br> ∴ q     |(p∧(p→q))→q          |Modus Ponens          |
|¬q <br> p→q <br> ∴ ¬p   |(¬q∧(p→q))→¬p        |Modus Tollens         |
|p→q <br> q→r <br> ∴ p→r |((p→q)∧(q →r))→(p→r) |Hypothetical Syllogism|
|p∨q <br> ¬p <br> ∴ q    |((p∨q)∧¬p) → q       |Disjunctive Syllogism |
|p <br> ∴ p∨q            |p→(p∨q)              |Addition              |
|p∧q <br> ∴ p            |(p∧q)→p              |Simplification        |
|p <br> q <br> ∴ p∧q     |((p)∧(q))→(p∧q)      |Conjunction           |
|p∨q <br> ¬p∨r <br> ∴ q∨r|((p∨q)∧(¬p∨r))→(q∨r)|Resolution             |



##Week  5:
####This week I learned that:
* There are 6 **Methods of Proof**
	* Direct Proof
	* Proof by Contraposition (Indirect)
	* Vacuous and Trivial Proof
	* Proof by Contradiction (Indirect)
	* Proof by Equivalence

1. Direct Proof (Steps)
	* Assume p is TRUE
	* Show that q is also TRUE based on step 1 <br>
	◆ *Use Direct proof if first term is simpler than second term!*
	
2. Proof by Contraposition(Indirect) (Steps)
	* Assume ¬q ≡ T
	* Show that ¬p is also TRUE based on step 1 <br>
	◆ *Use Proof by Contraposition if second term is simpler than first term!*

3. Vacuous Proof
	* If ¬p is FALSE then p→q must be TRUE <br>
	¬p <br>
	∴p→q

4. Trivial Proof
	* If q is TRUE then p→q must also be TRUE <br>
	q <br>
	∴p→q

5. Proof by Contradiction
	* Assume that the Premise is NOT TRUE
	* Show that step 1 will end up in a Contradiction

6. Proof by Equivalence (Biconditionals)
	* p ↔ q ≡ (p → q) → (q → p)
	
* if proving ends up in a fraction or a √ then you are using the wrong method!
* Proving was the most challenging topic in DISMATH so far
* It was tricky especially when it comes to assuming and using theorems.


##Week  6:
####This week I learned that:
* **Mathematical Induction** has two parts:
	* Basis: 
	 	* Show P(n) to be true
	* Direct Proof:
	 	* Assume P(k) ≡ T
	 	* Show P(k +) ≡ T 
* Mathematical Induction was new for me since I haven't taken up ENGALG2 yet.


##Week 7:
####This week I learned that:
* **Recursive Algorithm** is an algorithm that solves a problem by reducing it to an instance of the same problem with a smaller input.
* Set is introduced
* **Set** is an unordered collection of distinct objects, which may be anything (including other sets).
	* *Examples*:
	* {A, B, C, D} ≡ {D, C, B, A}
	* {X, Y} ≡ {X, Y, Y, X}
* **Set Identities**
* **Subsets**
* **Cardinality** of a set is the number of elements it contains.
	* If S is a set, we denote its cardinality by writing |S|.
* **Functions**
	* Let A and B be sets. A function f from A to B is an assignment of exactly one element of B to each element of A.
	* "Mappings" or "Transformations"
* **Types of Functions**
	* One-to-one Function (Injective) never assigns the same value to two different domain elements
	* Onto Function (Surjective) have equal range and codomain.
	* One-to-one Correspondence (Bijection) is both one-to-one and onto.


##Week 8:
####This week I learned that:
* **Algorithm** is a finite set of precise instructions for performing a computation or for solving a problem.
	* *Properties*
		* input
		* output
		* definiteness
		* correctness
		* finiteness
		* generality
* **Pseudocode** is a high-level description of an algorithm that uses the structural conventions of a programming language, but is intended for human reading.
* *Preconditions* are statements that describe valid input
* *Postconditions* are conditions that the output should satisfy


##Week 9:
####This week I learned that:
* **Searching Algorithms** -- the problem of locating an element in an ordered list
* There are two types of **Searching Algorithms**
	* *Linear Search Algorithm*
	* *Binary Search Algortihm*
* **Sorting Algorithms** -- the problem of assorting elements into increasing order
* There are two types of **Sorting Algorithms**
	* *Bubble Sort*
	* *Insertion Sort*
* **Greedy Algorithm** selects the best choice at each step, instead ofconsidering all sequences of steps that may leadto an optimal solution.


##Week 11:
####This week I learned that:
* **Graphs** are consisted of vertices (nodes) and edges (bridges)
* **Handshake Theorem** is used to determine the number of edges in a graph
	* 2e = Σdeg(v)
* **Euler Circuit**
	* Passes through every edge of the graph only ONCE
	* Starts and ends on the same Node
	* All nodes have even degrees
* **Euler Path**
 	* Passes through every edge of the graph only ONCE
	* Does not start and end on the same point
	* Exactly 2 nodes have even degress
* **Hamilton Circuit**
 	* Passes through all nodes only ONCE
 	* Starts and ends on the same node
 * **Hamilton Path**
 	* Passes through all nodes only ONCE
 	* DOes not start and end on the same node
* **Adjacency Matrix**
	* relationship between the nodes
* **Incidence Matrix**
	* relationship between the edges
* **Isomorphism**
	* relationship between graphs
	* "Rubber Band"
* **Planar** is beong able to put a graph into a plane without intersecting edges or nodes
* **Euler's Fromula** 
	* r = e - v + 2

