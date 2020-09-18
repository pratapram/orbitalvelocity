# orbitalvelocity - OVAI
AI to play the Orbital Velocity board game

Welcome to the offcial Orbital Velocity AI project. We want Orbital Velocity to be fun way to learn AI. If you are interested in learning about AI, you have come to the right place. We dont expect you to be already in expert in AI, but there the prerequisites to be able to successfully create your own Orbital Velocity AI. You must

* Be aware of the Orbital Velocity board game. Here is official website http://orbitalvelocitygame.com
* Be familiar with github, linux commands
* Be familiar with python language

# What is Orbital Velocity AI (OVAI)
For most of us, the first exposure to AI is science fiction stories and movies. In many movies AI is represented as a talking robot, or an ominous voice, the OVAI is not anything like that. OVAI is much simpler and could be your simple way to learn about AI.  The OVAI agent that we will create, will rapidly play the Orbital Velocity game thousands of times, and start to learn how to play. Once you have trained an agent, you will be able to clearly understand what strategies it uses, and you will learn how to improve the agent to learn better strategies, and ultimately make your own OVAI win against you.


## Open Speil framework
We will be utilizing Openspeil for this project. This is an AI framework that is designed for board games. This type of AI used here is called Reinforcement Learning. In our case, since we will have multiple players, it is a special class called multi-agent reinforcement learning algorithm.

## Problem statement

For OVAI we will cannot use the full Orbital Velocity game that you love to play because it is too complex. We will use a simplified ruleset and play only for one orbit. Here are the rules

* The cards will be the same as the board game
* Only one orbit (LEO), target is 39
* One rocket only
* Two players

Game termination condition
The game ends when one of these things happen
* Someone move the rocket to 39
* Rocket is lost



