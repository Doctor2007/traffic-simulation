# Computational Essay: Intelligent Driver Model (IDM)

This repository contains a short computational essay exploring car-following behaviour using the **Intelligent Driver Model (IDM)**.

The main notebook simulates a two-car, no-overtaking scenario and studies how the follower’s velocity evolves over time for different initial gaps.

## Contents

- `essay.ipynb` — main essay notebook (IDM model + simulations + plots)
- `requirements.txt` — minimal Python dependencies

## Setup

### Use a virtual environment (recommended)

From the repository root:

```bash
python -m venv .venv
source venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Notes
- Units and modelling assumptions (e.g., speed limit, safe time headway, minimum gap) are documented directly in `essay.ipynb`.

## Reproducibility tips

- Use a fresh environment and install from `requirements.txt`.
- If plots look different across machines, check your Matplotlib version.
