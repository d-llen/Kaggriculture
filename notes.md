[www.kaggle.com/code/sidhaarthshree/the-complete-getting-started-guide](https://www.kaggle.com/code/sidhaarthshree/the-complete-getting-started-guide) -> Town fixed at 1/day now

[www.kaggle.com/code/sidhaarthshree/a-reactive-agent-with-optimal-task#%F0%9F%8C%BE-Kaggriculture:-A-Reactive-Agent-with-Optimal-Task-Assignment](https://www.kaggle.com/code/sidhaarthshree/a-reactive-agent-with-optimal-task#%F0%9F%8C%BE-Kaggriculture:-A-Reactive-Agent-with-Optimal-Task-Assignment)

[www.kaggle.com/competitions/orbit-wars/discussion?sort=recent-comments](https://www.kaggle.com/competitions/orbit-wars/discussion?sort=recent-comments) -< similar comp

### Notes for writeup

13.08.26

* Learnt the competition rules
* Reading guide for helpful tips . Consider crop economics, best to sell? glut and scarcity curves. Animals and which sell for most, again consider glut and scarcity curves of produce and how much is produced. Animals effectively cost two tiles, require wheat for feeding. Care highest value action?
* Town demand to consider town effect on product IO, random so must adapt. Labour costs and hands -> up to 16-18 is profitable. Scales due to income
* Animals/Farms yield on production day must be collected that day
* Consider resources: unit-turns, tiles and money (buy/sell prices are adaptive)
* With 16 hands can service ~70 animals or ~40 + 30 crop tiles. May not need 4th quadrant ?
* Cluster around shed. Only collect fert if using melons.
* 100 item shed cap. Items put via place or end of day drop. If harvesting over 100 units a day DROP and SELL during the day.
* Taken open-source starter agent and testing harness from notebook

14.08.26

* Read through starter agent to understand code
* possible improvements:
  * adapt hire amount to days
  * prioritise wheat
  * improve selling logic to consider market state
  * consider use of animals? cows prolly
  * need to get rid of weeds faster, maybe dedicate hands to that?

6
