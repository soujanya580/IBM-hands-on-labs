
# TORCS Lab Results

## Task 1 – Baseline AI Driver
Successfully launched TORCS and connected the Python AI driver using `torcs_jm_par.py`.

Observation:
The car was able to drive autonomously around the track without manual input.

---

## Experiment 1 – Increased Target Speed

Changed:
TARGET_SPEED = 100 → 150

Observation:
The vehicle moved faster on straight sections but became less stable during corners and occasionally went off-track.

---

## Experiment 2 – Steering and Braking Adjustments

Changed:
- STEER_GAIN
- BRAKE_THRESHOLD

Observation:
Earlier braking improved stability during turns. Steering sensitivity affected how aggressively the car reacted to curves.

---

## What I Learned

This lab helped me understand how autonomous driving systems use sensor-based control loops for steering, acceleration, and braking decisions.

Small parameter changes significantly impacted vehicle behavior, demonstrating the importance of balancing speed and stability in AI-driven systems.

---

## Future Improvements

- Experiment with additional control parameters
- Try different tracks
- Explore reinforcement learning approaches in TORCS
  ## Screenshots

### TORCS Simulator Running

<img width="1920" height="1080" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/87679293-3914-40a6-91ec-87d8cf8b92f4" />
<img width="1920" height="1080" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/11186437-9fcf-4b85-88d2-2e41ea858cc9" />
<img width="1105" height="627" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/2e8f6bba-ddca-4ac0-b48f-b9b49f40b77a" />

### AI Driver Connected
<img width="1103" height="633" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/61d11711-c8df-4347-a924-95dfb6c225e2" />
