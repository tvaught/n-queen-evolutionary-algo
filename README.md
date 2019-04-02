# N Queen Problem through Evolutionary Algorithm(EA)
## Problem
In the 8-queen problem we are given a regular chess board (8 by 8) and eight queens that must be placed on the board in such a way that no two queens can check each other. This problem can be naturally generalized, yielding the N-queens problem. Many classical AI approaches to this problem work in a constructive, or incremental, fashion: one starts with placing one queen and after having placed n queens, one attempts to place the (n + 1)th on a feasible position, i.e., a position where the new queen does not check any others. Typically some sort of backtracking mechanisms is applied: if there is no feasible position for the (n+1)th queen, the nth is moved to another position. An evolutionary approach to this problem is drastically different in that it is not incremental. Our candidate solutions are complete, rather than partial, board configurations where all eight queens are placed.


## How to use Evolutionary Algorithm:
There are many methods in solving the N-Queen Problem but try to solve it using EA. The basic principles of EA are based around Darwin's Theory of Evolution by natural selection. 

### This is how it would look like in Pseudocode
Begin 
      Initialize population with random member solutions
      Evaluate Fitness each member
      Repeat until TERMINATE_CONDITION is true DO
              SELECT parents from popluation
              RECOMBINE pairs of parents 
              MUTATE the result offspring
              Evaluate new candidates
              SELECT members for new generation
      OD
END

### Sources to look into:
* AI 101: Intro to Evolutionary Algorithms - https://www.cs.vu.nl/~gusz/ecbook/Eiben-Smith-Intro2EC-Ch2.pdf
* What is an Evolutionary Algorithm? - https://www.cs.vu.nl/~gusz/ecbook/Eiben-Smith-Intro2EC-Ch2.pdf


## Instructions on uploading Solutions
* Clone this repo.
* Create a file/folder with ever language or program you want. If your soltuion is text or mathatmatical based add those too!
* Commit those changes and push them up to master
* IF you are playing around with other peopls code, try not to commit those changes but just your work files.
