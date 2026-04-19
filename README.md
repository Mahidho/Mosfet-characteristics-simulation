# MOSFET Characteristics Simulation

## About
This project models the electrical characteristics of an NMOS MOSFET
using Python. It was completed as part of my personal semiconductor
physics portfolio during my BSc in Physics.

The code simulates three key MOSFET behaviours using simple Python
loops and the basic Shockley MOSFET equations.

---

## Plots Generated

### 1. Transfer Curve (Id vs Vgs)
Shows how drain current changes as gate voltage increases.
The MOSFET stays off below 0.7V and turns on above it.

### 2. Output Curves (Id vs Vds)
Shows drain current vs drain voltage for five different gate voltages.
Each curve shows the linear region and saturation region clearly.

### 3. Channel Length Scaling
Shows how shrinking the channel length increases drive current.
This is the physics behind Moore's Law.

---

## Parameters Used

| Parameter | Value |
|---|---|
| Transconductance (k) | 0.0016 A/V^2 |
| Threshold Voltage (Vth) | 0.7 V |
| Channel lengths tested | 0.25 um, 0.5 um, 1 um, 2 um |
| Gate voltages tested | 1.0V, 1.5V, 2.0V, 2.5V, 3.0V |

---

## Tools Used
- Python 3
- NumPy
- Matplotlib
- Google Colab

---

## Files

| File | Description |
|---|---|
| `MOSFET_Characteristics.ipynb` | Main Python notebook with all code |
| `transfer_curve.png` | Transfer curve plot |
| `output_curves.png` | Output curves plot |
| `channel_scaling.png` | Channel length scaling plot |

---

## Author
**Mahidho** — BSc Physics
GitHub: github.com/Mahidho/Mosfet-characteristics-simulation

## License
MIT License
