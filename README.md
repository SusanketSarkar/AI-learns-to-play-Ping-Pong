<h1 align='center'> AI learns to play Ping Pong </h1>
<h3 align='center'> A pingpong game played by AI using NEAT (Neuroevolution of Augmenting Topologies)</h3>

<p align="center">
  <img width="460" height="300" src="https://github.com/SusanketSarkar/AI-learns-to-play-Ping-Pong/blob/main/images/example01.gif">
</p>
Every generation starts with the population of 200 bars. Every bar has it's own corressponding ball. The aim is to protect the ball from falling down. Once all the bars are dead, next generation is generated. For every 200 individuals of next generation 2 parents are selected from the previous genertion. The selected two parents are crossovered, followed by some percentage of mutation(generally low %).
<br>

<br>

This project was built using:
- Python 3.9.6
- Pygame

To run this project you can 
  - clone it using ```$ git clone https://github.com/SusanketSarkar/AI-learns-to-play-Ping-Pong.git ```
  - run ```main.py``` from root: ```$ py main.py ```
