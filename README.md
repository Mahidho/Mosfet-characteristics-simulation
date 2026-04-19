# MOSFET Characteristics Simulation

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Model](https://img.shields.io/badge/Model-Long--Channel%20MOSFET-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview
Mathematical modelling and visualisation of NMOS MOSFET I-V characteristics
using the long-channel Shockley MOSFET model in Python. Simulates transfer
curves, output curves, and analyses the effect of channel length scaling
on device performance.

## Device Parameters
| Parameter | Value |
|---|---|
| Type | NMOS (N-channel MOSFET) |
| Electron Mobility (μn) | 450 cm²/Vs |
| Oxide Capacitance (Cox) | 3.45 mF/m² |
| Channel Width (W) | 10 µm |
| Channel Length (L) | 1 µm (baseline) |
| Threshold Voltage (Vth) | 0.7 V |

## Results

### Transfer Curve (Id vs Vgs)
![Transfer Curve](MOSFET_Transfer_Curve.png)

### Output Curves (Id vs Vds)
![Output Curves](MOSFET_Output_Curves.png)

### Channel Length Scaling
![Channel Scaling](MOSFET_Channel_Length_Scaling.png)

## Key Findings
- MOSFET switches ON at threshold voltage Vth = 0.7V
- Drain current saturates beyond Vds = Vgs - Vth (saturation boundary)
- Higher gate voltage = higher saturation current
- Smaller channel length = significantly higher drive current
- Results directly demonstrate the principle behind Moore's Law

## Tools Used
- **Python** — modelling and visualisation
- **NumPy** — numerical computation
- **Matplotlib** — plotting

## Files
| File | Description |
|---|---|
| `MOSFET_Characteristics.ipynb` | Main Python notebook |
| `MOSFET_Transfer_Curve.png` | Id vs Vgs transfer curve |
| `MOSFET_Output_Curves.png` | Id vs Vds family of curves |
| `MOSFET_Channel_Length_Scaling.png` | Channel length scaling comparison |

## Author
**Mahidho** — BSc Physics
Exploring semiconductor device physics and VLSI design

## License
MIT License
