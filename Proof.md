## Probability of wining:

*N = number of doors = 3*

### case 1: never switch

 When a guest never switch, whether or not the host open a door doesn't matter.

 So, *P(Win) = 1/N = 1/3*
 
### case 2: always switch

 When a guest always switch, 
 
 If he/she picked out the prize_door at the first place, then
 
 *P(Win | Already at the prize door ) = 0*
 
 *P(Already at the prize door) = 1/N = 1/3*
 
 If he/she didn't picked out the prize_door at the first place, then the host has to open another goats door: 
 
 *P(Win | Not at the prize door ) = 1*
 
 *P(Not at the prize door) = 1 - 1/N = 2/3*
  
 *P(Win) = P(Win | Already at the prize door ) * P(Already at the prize door) + P(Win | Not at the prize door ) * P( Not at the prize door) =
 0 * 1/3 + 1 * 2/3 = 2/3*
 
