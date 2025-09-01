# Cross-Environment Cooperation Human Experiment Code

This repository contains the code for running the human experiments for the paper [Cross-environment Cooperation Enables Zero-shot Multi-agent Coordination](https://kjha02.github.io/publication/cross-env-coop).

## Setup

Make sure you have UV installed. Then run the following

```
uv init
source .venv/bin/activate
uv python install 3.12
git clone https://github.com/KJha02/crossEnvCooperation.git
uv pip install -e crossEnvCooperation/
uv pip install git+https://github.com/wcarvalho/nicewebrl
```

Refer to [NiceWebRL](https://github.com/wcarvalho/nicewebrl/tree/main#) for instructions on installing the dependencies and running the human experiments.

We've included model checkpoints for both the Dual Destination problem and Overcooked in the corresponding `dual_destination-CEC` and `overcooked-CEC` folders. Each of these folders additionally contains the `web_app.py` code for running the human experiments.

## Running the experiments

To run the experiments, run the `web_app.py` file in each of the corresponding folders after installing the dependencies.

