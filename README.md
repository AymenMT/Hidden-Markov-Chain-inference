# Hidden Markov chain inference

A robot is moving across a circular corridor. We assume that the possible positions of the robot is **a discrete set with
N locations**.
Given the robot sensors' measurements $Y_i$, $i \in (1..K)$, we aim to modelize the robot's real position (hidden variable $X_i$, $i \in (1..K)$) following the *Hidden Markov chain* model
![alt text](https://raw.githubusercontent.com/AymenMT/Robot-s-position-estimation/master/p2.PNG "*Hidden Markov chain*")

This will allow us to simulate the scenario and to estimate some important distributions such as the robot's current position given the observations so far and the most likely current position of the robot given the observations so far...

