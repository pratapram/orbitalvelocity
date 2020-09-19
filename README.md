# orbitalvelocity - OVAI
AI to play the Orbital Velocity board game

Welcome to the offcial Orbital Velocity AI project. We want Orbital Velocity to be fun way to learn AI. If you are interested in learning about AI, you have come to the right place. We dont expect you to be already in expert in AI, but there the prerequisites to be able to successfully create your own Orbital Velocity AI. You must

* Be aware of the Orbital Velocity board game. Here is official website http://orbitalvelocitygame.com
* Be familiar with github, linux commands
* Be familiar with python language

# What is Orbital Velocity AI (OVAI)
For most of us, the first exposure to AI is science fiction stories and movies. In many movies AI is represented as a talking robot, or an ominous voice, the OVAI is not anything like that. OVAI is much simpler and could be your simple way to learn about AI.  The OVAI agent that we will create, will rapidly play the Orbital Velocity game thousands of times, and start to learn how to play. Once you have trained an agent, you will be able to clearly understand what strategies it uses, and you will learn how to improve the agent to learn better strategies, and ultimately make your own OVAI win against you.


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


## Instructions

In a linux machine run the following commands.

This command will get you the code in this repository:

```
   git clone https://github.com/pratapram/orbitalvelocity.git
```

We will use the OpenSpiel framework for our work:

```
   git clone https://github.com/deepmind/open_spiel.git 
```


Next we will copy the code for OVAI into this and compile

``` 
   cp ../orbitalvelocity/orbital_velocity.* ../openspiel/openspiel/games/
   ./install.sh
   ./open_spiel/scripts/build_and_run_tests.sh # Run this every-time you need to rebuild.
```

You are ready to go. Run the following command to train an AI agent on Orbital Velocity game


```
   ./examples/example --game=tic_tac_toe
```
   
