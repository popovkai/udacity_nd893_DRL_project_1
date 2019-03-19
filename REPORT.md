#  Project Report

This project only uses very simple NN from the [original DQN paper](https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf)

NN info:

- FC - input: 37 (# of states) / output: 128
- FC - input: 128 / output 64
- FC - input: 64 / output: 4 (# of actions)

Parameters used in DQN algorithm:

- Maximum steps per episode: 1000
- Starting epsilion: 1.0
- Ending epsilion: 0.01
- Epsilion decay rate: 0.999

## Result

```
Episode 100	Average Score: 0.12
Episode 200	Average Score: 0.42
Episode 300	Average Score: 1.29
Episode 400	Average Score: 1.66
Episode 500	Average Score: 3.01
Episode 600	Average Score: 4.37
Episode 700	Average Score: 4.79
Episode 800	Average Score: 6.28
Episode 900	Average Score: 7.25
Episode 1000	Average Score: 8.10
Episode 1100	Average Score: 8.42
Episode 1200	Average Score: 8.65
Episode 1300	Average Score: 9.90
Episode 1400	Average Score: 10.08
Episode 1500	Average Score: 9.636
Episode 1600	Average Score: 10.76
Episode 1700	Average Score: 11.02
Episode 1800	Average Score: 11.44
Episode 1900	Average Score: 11.59
Episode 2000	Average Score: 11.94
Episode 2100	Average Score: 12.09
Episode 2200	Average Score: 11.41
Episode 2300	Average Score: 12.33
Episode 2400	Average Score: 12.38
Episode 2500	Average Score: 12.33
Episode 2584	Average Score: 13.01
Environment solved in 2484 episodes!	Average Score: 13.01
```

## Future Works

1. Get my machine running !! I still don't like coding at Notebook. I like vi.
2. Different hyperparameters (LR, different optimziers, epsilon)
3. Different NN configurations - current NN is not deep at all
4. [DDQN](https://arxiv.org/abs/1509.06461)
5. Priority Replay
6. [Dueling](https://arxiv.org/abs/1511.06581)
