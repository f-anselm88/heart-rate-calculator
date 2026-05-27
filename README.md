# ❤️ Heart Rate Calculator

A Python command-line tool that calculates personalized heart rate training zones using the Karvonen formula, helping users identify the optimal intensity for aerobic, anaerobic, and maximum effort workouts.

---

## Features

- ✅ Calculates target heart rate zones using the Karvonen formula
- ✅ Accepts age and resting heart rate as inputs
- ✅ Displays zones for multiple training intensities (50% – 95%)
- ✅ Clean, formatted output table

---

## Demo

```
=== Heart Rate Zone Calculator ===

Enter your age: 26
Enter your resting heart rate (bpm): 62

--- Your Training Zones ---
Max Heart Rate: 194 bpm

Zone        Intensity   Target Range
------------------------------------------
Recovery      50%       128 – 136 bpm
Aerobic Base  60%       136 – 145 bpm
Aerobic       70%       145 – 153 bpm
Threshold     80%       153 – 162 bpm
Anaerobic     90%       162 – 170 bpm
Max Effort    95%       170 – 194 bpm
```

---

## How to Run

**Requirements:** Python 3.x

```bash
# Clone the repository
git clone https://github.com/f-anselm88/heart-rate-calculator.git

# Navigate into the project
cd heart-rate-calculator

# Run the program
python heart_rate.py
```

---

## The Formula

This calculator uses the **Karvonen Formula**:

```
Target HR = ((Max HR - Resting HR) × Intensity%) + Resting HR

Where:
  Max HR = 220 - Age
```

This method accounts for individual fitness level via resting heart rate, making it more accurate than age-only formulas.

---

## What I Learned

- Applying real-world health science formulas in Python
- Using f-strings to produce clean, aligned tabular output
- Handling user input and computing multiple derived values from a single data set

---

## Author

**Anselm Munango**
[f-anselm88.github.io](https://f-anselm88.github.io) · [GitHub](https://github.com/f-anselm88) · [LinkedIn](https://linkedin.com/in/anselm-munango-bs) · [anselm.mu@gmail.com](mailto:anselm.mu@gmail.com)
