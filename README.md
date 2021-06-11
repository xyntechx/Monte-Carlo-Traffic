# Monte Carlo Simulation for Traffic

This notebook won 1st Prize in the 2021 SUTD Virtual Research Hackathon. It leverages Monte Carlo methods to simulate traffic and propose solutions to traffic congestions.

## Aim

This notebook aims to compare the congestion in:
- Scenario 1: 1 straight road
- Scenario 2: 1 straight road + 1 side road
- Scenario 3: 1 straight road + 1 side road + traffic lights

## Results

From Scenarios 1 to 3:

- The average time taken for cars to move from the entry point to the exit point decreases
- The maximum number of cars halted decreases

From these results, it can be concluded that side roads and traffic lights are effective in reducing traffic congestions, and they are most effective when used simultaneously.

## Areas of Improvement

To better simulate real-world traffic, some areas of improvement can be implemented.

- Introduce "bad drivers" by varying the normal speed of each car
- Make traffic lights a function of the number of cars waiting behind them such that the more cars waiting, the longer the specific traffic light stays on
- Cars on straight roads should have a higher probability of moving (faster speed) because straight roads are often expressways with higher speed limits

## Takeaways from Event

From the 2021 SUTD Virtual Research Hackathon, I learnt many new things:

- How to utilise Monte Carlo methods such that randomness can be used to solve problems
- A new programming language, Julia
- How to program under strict time constraints

Thank you to the presenters, mentors, organisers, and all who were involved in the hackathon!
