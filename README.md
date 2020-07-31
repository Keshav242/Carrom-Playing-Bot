# Carrom-Playing-Bot
## Abstract
- Carrom is a cool game to play with hand,but on other hand designing a machine to play it is pretty challenging. We have made a bot that can put the coins in the holes by first detecting them through image processing and then deciding which coin to be put in hole i.e most easy to put (by a sophisticated algorithm).
- After the decision is made the mechanical model controlled through aurdino is used to flick the striker.This mechaical model was on a lead screw arrangement for lateral movement along egde of board and the flicker was attached to a stepper motor to shoot the striker.
## Limitations
- If we define 4 regions on the board formed by intersection of two lines joining opposite pockets. If the coin is present in one of the 4 regions farthest from striking position
,straight head on shot will fail.
- Uniform power for all coordinates can lead to unstable movement of coin.
- Rebound shots not taken.
- The radius of the coin is not considered so if a coin is considerably near to the path of the shot it may even obstruct the shot and the result will not be achievable.
## Future Improvement
- The current Bot takes shots so as to have head on collision between the striker and coin. If it takes into account the radii of coins and striker it can manage to play oblique shots.
- A further optimization of the current bot is to take rebound shots effictively on the carrom board.
- We can futher include the relation between length and power of shots.
- There is a good possibility of introduction of supervised Machine learning. So the bot improves itself with time.
## Team Members
- Akash Deep
- Ayush
- Deovil Vimal Dubey
- Inzamam
- Keshav Dixit
- Ravi Chandra Burra
## Mentors
- Yawan 
- Dhruv
