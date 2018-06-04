# pmsi_problems

The hypothesis spaces learned by PMSI for the language domain:

DQN #4 (lowest level)
1. years to after
2. after to before
3. because to before
4. in-back-of to in-front-of
5. in-front-of to before
6. chain before

DQN #3
1. in-front-of to before, chain before
2. because to before, chain before
3. after to before, chain before
4. years to after
5. in-back-of to in-front-of

DQN# 2
1. in-back-of to in-front-of, in-front-of to before, chain before
2. chain before, because to before, chain before
3. after to before, chain before
4. years to after

DQN# 1
1. in-back-of to in-front-of, in-front-of to before, chain before
2. chain before, because to before, chain before
3. years to after, after to before, chain before


The hypothesis spaces learned by PMSI for the equation solving domain:

DQN #2 (lowest level)
1. add like terms
2. simplify fractions
3. simplify products
4. apply quadratic formula
5. divide both sides by relevant multiple
6. check if solution is explicit

DQN #1
1. divide both sides by relevant multiple, check if solution is explicit
2. apply quadratic formula, check if solution is explicit
3. simplify fractions, simplify products
4. add like terms


The hypothesis spaces learned by PMSI for the robot planning domain:

DQN #4 (lowest level)
1. attempt to place x on y
2. unstack an item that is above x to reach x
3. unstack an item that is above y to make room for x
4. check world

DQN #3
1. unstack an item that is above x to reach x, attempt to place x on y
2. unstack an item that is above y to make room for x, attempt to place x on y
3. unstack an item that is above y to make room for x, unstack an item that is above x to reach x
4. check world

DQN #2
1. unstack an item that is above y to make room for x, unstack an item that is above x to reach x, unstack an item that is above y to make room for x, attempt to place x on y
2. unstack an item that is above y to make room for x, unstack an item that is above x to reach x, unstack an item that is above x to reach x, attempt to place x on y
3. check world

DQN #1
1. unstack an item that is above y to make room for x, unstack an item that is above x to reach x, unstack an item that is above y to make room for x, attempt to place x on y, unstack an item that is above y to make room for x, unstack an item that is above x to reach x
2. unstack an item that is above y to make room for x, unstack an item that is above x to reach x, unstack an item that is above x to reach x, attempt to place x on y
3. check world
