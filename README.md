# W19D2: Q-Learning Improvements with GitHub Workflow

Welcome to W19D2! Tonight you'll practice open-source collaboration while improving your Q-Learning agent.

## Getting Started

1. **Clone this repository** (if you haven't already):
   ```bash
   git clone <your-classroom-repo-url>
   cd w19d2-qlearning
   ```

2. **Open the guide**: Open `index.html` in your browser for step-by-step instructions.

3. **Switch to your team branch**:
   ```bash
   git checkout team-a  # Replace with your team name
   ```

4. **Create your feature branch**:
   ```bash
   git checkout -b feature/<your-improvement>
   ```
   Branch names:
   - `feature/learning-rate`
   - `feature/exploration`
   - `feature/state-bins`
   - `feature/reward-shaping`

## Repository Structure

```
W19D2/
├── index.html                    # Main hub page (start here!)
├── w19d2_starter.py             # Q-Learning starter code (modify this!)
├── github-workflow.html         # Git/GitHub tutorial
├── research-topics.html         # 4 improvement research areas
├── team-roles.html              # Team role assignments
├── cartpole-explainer.html      # CartPole environment reference
├── hyperparameters-explainer.html  # Hyperparameter tuning guide
└── README.md                    # This file
```

## Tonight's Workflow

1. **Team Setup** (5 min) - Assign roles and pick improvement areas
2. **Research** (15 min) - Read about your improvement topic
3. **Git Setup** (10 min) - Clone, branch, set up your workspace
4. **Implementation** (30 min) - Modify `w19d2_starter.py`
5. **Evaluation & Commit** (10 min) - Test, commit, push
6. **Pull Request** (10 min) - Create PR with results
7. **Code Review** (5 min) - Review a teammate's PR

## Running the Code

```bash
# Train your agent (auto-creates venv, shows live graph)
python w19d2_starter.py

# Train without graph (for remote/SSH)
python w19d2_starter.py --no-plot

# Evaluate only (after training)
python w19d2_starter.py --evaluate
```

Results are saved to `results/report.html`.

## What to Modify

Open `w19d2_starter.py` and find your section:

| Improvement Area | Function to Modify | Look for |
|------------------|-------------------|----------|
| Learning Rate | `get_learning_rate()` | `# ========== MODIFY HERE: LEARNING RATE STRATEGY ==========` |
| Exploration | `select_action()` | `# ========== MODIFY HERE: EXPLORATION STRATEGY ==========` |
| State Bins | `create_bins()` | `# ========== MODIFY HERE: BINNING STRATEGY ==========` |
| Reward Shaping | `shape_reward()` | `# ========== MODIFY HERE: REWARD SHAPING ==========` |

## Requirements

- Python 3.8+
- Git
- The script auto-installs: gymnasium, numpy, matplotlib

## Help

- Check `index.html` for detailed instructions
- Refer to `research-topics.html` for code hints
- Ask your teammates first, then raise your hand for instructor help!
