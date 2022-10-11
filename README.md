# Formal-Verification-of-Partition-Refinement-Algorithms

### Principal Goal:  To prove the correctness of bisimulation checking algorithms

In the world of concurrent processes, "bisimulation" is a strong 
notion of process equivalence that characterises processes by their 
external behaviour. It is commonly used to verify concurrent systems, 
where processes are specified in a process algebra, abstraction is 
applied, and bisimulation is checked. 

This last part is the focus of this project. There exist many algorithms, some inefficient but conceptually simple, and some more 
efficient but conceptually difficult, that check bisimulation between 
processes automatically. They work with a technique that is called 
"partition refinement". 

This project proposes to formally prove (in a mechanical proof assistant, determined Lean) that these partition refinement algorithms are correct, starting with the simplest algorithm, and possibly extending to more sophisticated algorithms depending on progress.