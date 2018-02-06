## [Ultimatum Game](https://en.wikipedia.org/wiki/Ultimatum_game)
In this game players are paired up and one player is given the role of 'Proposer' and the other is given the role of 'Responder'. The Proposer takes a sum of points and divides it among themselves and their partner. The Responder can choose to Accept the proposed allocation in which case the players get the allocated points or Reject the proposal in which case neither player gets any points.

This game includes a custom aiBehavior closure to allow AI proposers to pick a random point allocation, to add AI players using this behavior run ```g.addAI(a, 20, aiBehavior)``` in the Script dialog. This custom closure is defined in `InitStep.groovy`.

---
More information about breadboard can be found at [breadboard.yale.edu](https://breadboard.yale.edu) and documentation can be found [here](https://github.com/human-nature-lab/breadboard/wiki).