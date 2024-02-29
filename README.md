# snake
taking harvard's cs50-ai course and in the slides explaining states/agents/actions, i figured out the rules for snake. i saw engineer man (youtube) build it with "curses" library, so i will look through curses and do the same... before taking the woven project


- We start off with some basic terms and labelings. I am going to try to explain them using snake (the game)
    - Snake is a 2d game... Super important
    - agent (THE SNAKE): an entity that can perceive and act on it's environment
    - state (THE GAME): the config of the agent and it's environ
    - initial state: n piece of food, snake with length n, wasd movement, walls
    - actions (choices): wasd, bite tail, 