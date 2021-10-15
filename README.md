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
