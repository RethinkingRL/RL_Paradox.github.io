# The Paradox of Outcome Optimization

This repository hosts the project page for the paper **"The Paradox of Outcome Optimization: A Causal Information-Theoretic Bound on Reasoning Shortcuts in LLMs."**

## Overview

This paper studies a core failure mode of large language models trained with outcome-based reinforcement learning: models can achieve strong in-distribution performance while still relying on shortcut features that fail to generalize under distribution shift.

To explain this phenomenon, the paper builds a theoretical framework connecting:

- Structural Causal Models
- The Information Bottleneck principle
- Shortcut learning in outcome-based optimization
- Process supervision and Process Reward Models

## Main Ideas

- **Reward-Induced Manifold Collapse:** outcome-based training can prefer shortcut-dominated representations when shortcut features are easier to optimize than causal reasoning features.
- **Semantic Coverage Bound:** out-of-distribution error depends on semantic coverage rather than dataset size alone, so scaling homogeneous data is not enough to ensure robust reasoning.
- **PRM as Topological Filter:** process supervision changes the structure of the solution space by filtering out shortcut trajectories and favoring causally consistent reasoning paths.

## Project Page Contents

The website includes:

- an overview figure of the paper's causal framework
- a concise abstract
- theorem summary cards
- rendered theorem snapshots
- selected experimental results
- a poster placeholder for future updates

## Files

- [index.html](./index.html): main project page
- [index_new.html](./index_new.html): alternate working page
- [static](./static): images, styles, scripts, and PDF assets

## License

This page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), which was adopted from the [Nerfies](https://nerfies.github.io/) project page.
