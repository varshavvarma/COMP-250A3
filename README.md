# COMP251A3:
Created a Game board with a randomly generated board that contains 4 sub-blocks, each with its own 4 sub-blocks. There is a maximum depth for how many sub-blocks within sub-blocks may exist.
Each  player  is  randomly  assigned  their  own  goal  to  work  towards:   either  to  create  the  largest connected  ”blob”  of  a  given  color  or  to  put  as  much  of  a  given color  on  the  outer  perimeter  as possible.
The player can either rotate a block, reflect the block horizontally or vertically, and smash a block (making four randomly generated sub-blocks)
After each move, the player's score is updated depending on how well they have achieved their goal.The game continues for a certain number of turns. The player with the highest score at the endis the winner.
Restrictions: smashing the top-level block is not allowed, since that would be creating a whole new game. Smashing a unit cell is also not allowed, since it’s already at the maximum allowed depth. The moves can be applied to any level.
