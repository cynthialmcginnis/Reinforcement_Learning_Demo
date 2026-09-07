# Reinforcement Learning Demos

Interactive, browser-based demos built for **ARIN 310: Introduction to Artificial Intelligence** (University of Maryland Global Campus Asia), Unit 4: Computer/Machine Vision and Reinforcement Learning.

No installation, no login, no data collection. Each file is a standalone HTML page that runs entirely in the browser.

**Live site:** https://cynthialmcginnis.github.io/Reinforcement_Learning_Demo/

## What's here

Run them in order. Each one builds on vocabulary introduced in the last.

| Demo | File | What it teaches |
|---|---|---|
| Grid World | `RL_GridWorld_Demo.html` | An agent with no prior knowledge of a small maze learns the shortest safe path through trial, error, and reward. Introduces state, action, reward, policy, Q-value, and episode. |
| The Slot Machines | `BanditDemo.html` | Four machines, no maze, no movement. Isolates the exploration-versus-exploitation dilemma. |
| Self-Play: Tic-Tac-Toe | `SelfPlayTicTacToe.html` | An agent improves only by playing copies of itself thousands of times, the same core idea behind AlphaGo and AlphaZero, at a scale small enough to fully explore. |
| Deep Scan: Finding the Cloaked Fleet | `DeepScanDemo.html` | A hidden, fixed enemy formation and a scanner that only reports hit or miss. Introduces partial observability. |

`index.html` is the hub page that links to all four.

## Design principle

Every demo exposes the underlying mechanism, not just the output. Students can manipulate inputs (actions, choices, scans) and watch the system respond, rather than just seeing a final trained result.

## Using this in class

Point students to the live site link above. Start with Grid World; it's the on-ramp for the vocabulary the other three assume.

## License / reuse

Built for classroom use in ARIN 310. Reuse in other courses is welcome; please credit the original.
