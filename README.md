#PredatorPrey
=============

This project was inspired by several episodes of
[NUMB3RS](http://en.wikipedia.org/wiki/Numb3rs) where Charlie describes the
use of [pursuit-evasion](http://en.wikipedia.org/wiki/Pursuit-evasion) curves
in order to identify the likely trajectory of a fleeing criminal.

Predator Prey is a game where a number of players form a team of predators,
whose goal is to chase down one or more prey before the prey reaches some
objective.  Typically, the predators will not always know where the prey are,
and the predators may not even be aware of the type of terrain they are
travelling in.  The interesting part of this research project is in
collaborative AI, how the team of predators, or prey, communicate and work
together to navigate the region and accomplish their objectives.

##Real World Applications

Predator Prey is very similar to cops and robbers.  Robbers enter a building
to steal certain valuables, which triggers an alarm and cops arrive on the scene.
The cops do not necessarily know how to navigate the hallways of the building, or
where all the exits are.  They must deploy a number of officers in order to capture
the robbers before they can reach the valuables and their escape route.

Replace building with city streets, desert, etc.

##Research Questions

* How many cops will it take to be able to capture n prey?
* Given the current location of the predators, p, what is the optimal way
  to split up the team of predators to capture the prey?  What is the optimal
  route to use to intercept a prey?
* Using some assumptions about the prey and the path they have taken so far,
  can we identify their target?
* What is the likely escape path of the prey given the last known location and
  probabilistic models of their target?
 
##Seen in NUMB3RS
* [Season 3 Episode 01](http://en.wikipedia.org/wiki/Spree_\(Numb3rs\))

##The Pacman Project
The pacman project is an instructional toolkit for teaching introductory AI developed
by John DeNero and Dan Klein from Berkeley.  The framework for the project includes
the classic Pacman game, which is a great test bed for pathfinding algorithms.
This framework is open for personal use as long as no solutions to class projects
are posted online.  See the original project
[here](http://www-inst.eecs.berkeley.edu/~cs188/pacman/pacman.html)
