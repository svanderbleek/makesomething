# makesomething

Games that expose math. The closest approach to ours is Xylem [29, 28], a game where players are botanists trying to identify patterns in the numbers of growing plants. Like INVGAME, Xylem relies on players finding candidate invari- ants from run-time data. However, due to its focus on casual gaming, Xylem explores a different point in the design space than ours. Xylem is a touch-based game that uses a graphics- rich UI with many on-screen abstractions, including plants, flowers, and petals. Since these abstractions use space, Xylem is limited in the amount of data it can show onscreen, which in turn might hinder the ability of players to see patterns. For example, Xylem players can only see 2 data rows at a time, having to scroll to see other rows. In contrast, INVGAME tries to increase the ability of humans to spot patterns by: (1) show- ing the data matrix all at once (2) re-ordering columns. Xylem
also restricts some aspects of predicate building, such as not allowing arbitrary numeric constants. In contrast, INVGAME has an unrestricted way for players to enter predicates, and provides immediate feedback on which rows are true/false, for quick refinement. Finally, although Xylem was played by many users, there is no systematic evaluation on a known benchmark set, or comparison to state-of-the-art tools.
Monster Proof [12] is another verification game that exposes math symbols to the player. However, Monster Proof is much closer in concept to a proof assistant [38, 2, 3], where the user is constructing a detailed proof using rules to manipulate expressions. In contrast, INVGAME uses humans to recog- nize candidate invariants, and automated solvers to perform much of the manipulations done by players in Monster Proof. Also, the published results on Monster Proof do not provide a systematic evaluation against state-of-the-art tools.
Games that conceal math. In Binary Fission [16], players build preconditions by composing primitive predicates gener- ated by Daikon. The user is never exposed to the predicates and instead builds a decision tree out of black-box filters. Our benchmarks involve predicates that Daikon cannot infer, which makes them difficult to solve by Binary Fission. Binary Fis- sion was also evaluated only on loop-free programs, whereas the goal of our work is to verify loops, which are one of the biggest challenges in program verification.
In Circuit Bot [12], Dynamaker [12] and Pipe-Jam/Flow- Jam/Paradox [13, 12] players resolves conflicts in con- straints graphs derived from type/information flows. In Ghost Space [12] and Hyper Space [12] players manipulate an ab- stracted control-flow graph to perform counterexample-guided abstraction refinement under the hood. In StormBound [12] players build program predicates without seeing mathematical symbols or numbers. These games rely more on the player’s visual and spatial recognition skills, rather than mathematical pattern recognition skills.

Bounov, D. 2018. Toward Gamification and Crowdsourcing of Software Verification. Ph.D. Dissertation, University of California San Diego, USA.

Gamification of Loop-Invariant Discovery from Code
Andrew T. Walter, Benjamin Boskin, Seth Cooper, Panagiotis Manolios

A Reasoning Engine for the Gamification of Loop-Invariant Discovery
Andrew Walter, Seth Cooper, and Panagiotis Manolios

https://cseweb.ucsd.edu/~lerner/pg.html

https://jdublu10.github.io/assets/thesis.pdf

NaDeA: A Natural Deduction Assistant with a Formalization in Isabelle
Jørgen Villadsen, Alexander Birch Jensen & Anders Schlichtkrull
IFCoLog Journal of Logics and their Applications 4(1) p. 55-82 2017
http://www.collegepublications.co.uk/journals/ifcolog/
A preliminary version appeared in Proceedings of 4th International Conference on Tools for Teaching Logic, Rennes, France, p. 253-262 2015
http://arxiv.org/abs/1507.04002
ProofJudge: Automated Proof Judging Tool for Learning Mathematical Logic
Jørgen Villadsen
Proceedings of the Exploring Teaching for Active Learning in Engineering Education Conference, Copenhagen, Denmark, p. 39-44 2015
http://etalee2015.etalee.dk/
Natural Deduction and the Isabelle Proof Assistant
Jørgen Villadsen, Andreas Halkjær From & Anders Schlichtkrull
Post-proceedings of the 6th International Workshop on Theorem proving components for Educational software (ThEdu'17)
http://eptcs.org/content.cgi?ThEdu17
Natural Deduction Assistant (NaDeA)
Jørgen Villadsen, Andreas Halkjær From & Anders Schlichtkrull
Post-proceedings of the 7th International Workshop on Theorem proving components for Educational software (ThEdu'18)
http://eptcs.org/content.cgi?thedu18
Teaching a Formalized Logical Calculus
Asta Halkjær From, Alexander Birch Jensen, Anders Schlichtkrull & Jørgen Villadsen
Post-proceedings of the 8th International Workshop on Theorem proving components for Educational software (ThEdu'19)
http://eptcs.org/content.cgi?ThEdu19
A Concise Sequent Calculus for Teaching First-Order Logic
Asta Halkjær From & Jørgen Villadsen
Isabelle Workshop 2020
https://sketis.net/isabelle/isabelle-workshop-2020

http://www.cs.cmu.edu/~aldrich/sasylf/

A Computer Environment for Writing Ordinary Mathematical Proofs
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.88.3730&rep=rep1&type=pdf

Student proof exercises using MathsTiles and isabelle/HOL in an intelligent book
https://rune.une.edu.au/web/bitstream/1959.11/22401/3/open/SOURCE02.pdf

https://functional-algorithms-verified.org



g-hol: A graphical user interface for the HOL proof assistant
F Arshad, H Mehmood, F Raza, O Hasan

Developing a Web-Based Hoare Logic Proof Assistant
F Goldener
