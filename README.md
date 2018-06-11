# Puzzle
In this lab, we develop a program to validate potential solutions to a classic puzzle1 recast as Mama's puzzle of the baby, crab, and cone. As the story goes, Mama headed o to the ice cream shop on a hot summer day with her delightful baby and pet crab. On the way she crossed a river with the aid of a ferry boat that, rowed by herself, could carry one other. A little thought demonstrates that this was no minor obstacle|it required three trips in the ferry to get everyone across (the crab it seems, was no great swimmer). By the time she got to the shop, she was clearly ready to make a purchase. Having purchased the largest cone possible, Mama set back toward home with all in tow: baby, crab, and cone. At the river, however, she faced a dilemma: in what order should she row everyone across in the ferry? The diffculty was that since only one of the baby, crab, or cone could be ferried across (it must have been a huge cone), two must be left behind. Unfortunately, if the baby was left unattended with the crab, violence of some form would surely ensue. If the baby was left with the cone, it would overindulge. Thus, each trip of the ferry had to be made with care, making sure that the baby was never left with either of the other two on same shore. To facilitate Mama's journey, you are to write a planning program of sorts, that allows the harmless simulation of the various possibilities. We have in mind a program with output similar to the following: 

```
  Welcome to the Puzzle of the Baby, the Crab, and the Cone.
  One hot summer day, Mama crossed the river to the left
  bank take a break from programming and buy an ice cream.
  She brought her baby and her pet crab. On the return
  she came to the river and was faced with a dilemma: how
  could they all cross without disaster? The ferry holds
  
  Mama and just one other item. The problem is that
  * if the baby is left with the cone, it spoils its dinner.
  * if the baby is left with the crab, the crab bites the baby.
  Please help Mama make her journey across the river!
  ```
  
  As you can tell, the program keeps track of the location of each of the parties, perhaps by a boolean. After describing the state of the situation, the facilitator is asked to determine who rides in the ferry with Mama. As Mama leaves shore, the various lethal conditions are checked for and the simulation is potentially terminated. If, however, everyone eventually makes it to the destination (here, the \right bank"), the puzzle is solved.
