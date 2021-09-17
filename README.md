#  iGibson: Asking for help 

This is a fork of the iGibson repository.
This project upgrades iGibson with "asking for help" functionality.
Under this paradigm, a robot that is navigating in an environment is provided with the additional ability to ask an external agent for help when completing it's task. This agent may be a human or another learning agent.
The purpose of this project is to ascertain whether agents can learn to "ask for help" so as to achieve their goal states in reasonable amounts of time.Some examples of when asking for help is the correct course of action:
- the robot needs a door opened before it can navigate to a new room.
- the robot's perception has failed and its needs help identifying it's surroundings.
- the robot is operating on a "stale" understanding of the environment and is asked to complete an action that will lead to a collision.
