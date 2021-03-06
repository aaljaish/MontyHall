# Monty Hall
The Monty Hall problem is a famoous probability puzzle. The problems is posed like this:

You are on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say Door 1, and the host, who knows what's behind the doors, opens Door 3, which has a goat. The host then says, "Do you want to stay with your original door or switch to Door 2?" Is it to your advantage to switch your choice?

However, we can use Python to simulate 100,000 games to solve the game show problem. The code below requires the use of the NumPy library <https://numpy.org/install/>. The simulation plays 100,000 iteration of the games. For each game, it records whether the car is behind the selected door or behind the other unopened door. The simulation then outputs the average chance of winning the car if you always stayed with your selection versus if you switch doors.

I used the time module to time the duration of the simulation. On my PC, it took less than 3 seconds to run 100,000 iterations of the Monty Hall problem.
