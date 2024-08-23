# DBO-MAB: Dynamic Bayesian Optimisation for Multi-Arm Bandits
## 🚀 Overview

DBO-MAB is a novel algorithm that dynamically adapts hyperparameters of multi-arm bandit (MAB) algorithms using incremental Bayesian optimisation. It addresses the challenge of tuning MAB algorithms in uncertain and dynamic environments, for applications like web server optimisation.

### Key Features

- **Dynamic Hyperparameter Tuning**: Automatically adjusts MAB hyperparameters at runtime
- **Adaptive Range Adjustment**: Uses interquartile mean (IQM) to focus on promising regions
- **Adaptable**: Performs well in both static and dynamic environments

## How It Works

1. **Initialization**: Starts with a set of initial hyperparameter values
2. **Continuous Learning**: Uses Bayesian optimisation to refine hyperparameters based on observed rewards
3. **Dynamic Adaptation**: Adjusts search space using IQM of observed rewards
4. **Incremental Updates**: Maintains fixed pillar points and recent observations for efficient learning

## Performance Highlights

- Reduces average response time by around 55% compared to state-of-the-art algorithms
- Consistently adapts to environmental changes in dynamic settings

## Applications

- Web server configuration optimisation
- Recommendation systems
- Any decision-making process under uncertainty with changing conditions



