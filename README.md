# LAB3 Computational Intelligence

Evolutionary Algorithm

## Results

### Multiple runs

Mean final fitness of 10 runs, 20,000 evaluations per run. Random is the mean of 200 random circles, greedy is deterministic.

| Algorithm | n = 30 | n = 100 |
|---|---|---|
| random circle | 299.9 | 1002.2 |
| greedy | 410.0 | 1480.0 |
| hill climbing, swap | 406.4 | 1410.0 |
| hill climbing, inversion | 418.0 | 1478.0 |
| evolutionary algorithm (hypermodern) | 416.6 | 1410.8 |

### Single runs (n = 30)

| Algorithm | Fitness | Evaluations |
|---|---|---|
| random circle | 324 | – |
| greedy | 410 | – |
| hill climbing (inversion), stop on stagnation | 418 | 4,918 |
| hill climbing (inversion), full budget | 418 | 20,000 |
| evolutionary algorithm (hypermodern) | 418 | 20,000 |
