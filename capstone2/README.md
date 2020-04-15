# networkscience

This is a repository for my CS 7280 (Network science, taught by Konstantine Dovrolis at Georgia Tech) 
project as well as lecture notes and other class materials. 

The general to-do list and goals of my project.

To-Do/ Checklist




0. Choose network data to work with [X]
1. Data exploration using NetworkX []
1. Write parsing and wrapper code for DeepWalk: representation
learning algorithm. [X](it's all cmd line)
2. Write parsing and wrapper code for either Perseus or GUDHI persistent homology algorithm. [X]
3. Parse[X], visualize[X], analyse persistent homology data. 
4. Interpret persistent homology data in the context of learned representation and original network.

Questions to be answered:

Can this be used to detect communities? partition the network? 
find minimal subgraph that preserves structure? Find the necessary criteria for power law scaling?

Vietoris-Rips complex adds edges between nodes in the representation space; can this be used to reorganize the network?
I.e. 

Nodes & Edges -> Representation space -> Vietoris-Rips -> New set of edges? 
Pruned nodes?  New structure (higher dimension) structure detection?

(If time or not too hard, choose different simplicial complexes as well)

Main comparisons:

A. Perform same calculations on random networks as a null hypothesis
B. Calculate community structure with networkX and compare.
C. Performance comparisons?

Goal that is likely harder than it seems:
Finding subgraphs which correspond to most persistent Betti number events.
What happens to the network when all but the most persistent components are pruned?


Reminders:

The code is likely not going to be the prettiest because they're not my algorithms 
and I have many other projects (PhD thesis, 
Data science training workshop and projects, etc.) to work on. Trying to utilize
the already implemented code as much as possible; will try to write pythonic
PEP-8 compliant code when possible. 
