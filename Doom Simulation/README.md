# Reinforcement Learning on VizDoom: Health Gathering Supreme

This repository contains an implementation of a reinforcement learning (RL) agent trained to play the **Health Gathering Supreme** scenario from [VizDoom], a Doom-based environment for research in visual-based RL.
This project demonstrates how RL techniques can be applied to complex, partially observable 3D environments using first-person vision.

## Environment
- **Game**: Doom (via VizDoom)
- **Scenario**: Health Gathering Supreme (agent must navigate the map and collect health packs while avoiding acid damage)
- **Observation**: RGB frames (first-person camera)
- **Action Space**: Discrete (movement, turning, strafing)

![RL Agent Playing Doom](./Doom Simulation/media/replay-gif.gif)
