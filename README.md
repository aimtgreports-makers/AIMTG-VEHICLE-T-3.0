# 🚗 VEHICLE-T 3.0

**A Relational Dynamical System with a Measurable Global Tension Signal**

---

## 🔷 What is this?

VEHICLE-T 3.0 transforms the VEHICLE framework into a **measurable system**.

Instead of only simulating dynamics, it introduces:

> **A normalized observable of structural tension (GTS)**

This allows:

- direct measurement of system tension  
- comparison across different systems  
- detection of structural regimes  

---

## 🔷 Core Idea

\[
GTS(t) = \frac{T(X(t))}{T(X(0))}
\]

VEHICLE-T shifts the paradigm from:

> **simulation → measurement**

---

## 🔷 Why it matters

This framework enables the study of:

- complex systems  
- competitive environments  
- geopolitical dynamics  
- structural stability  

under a unified mathematical structure.

---

---

Where:

T(X) is the global tension functional defined in the VEHICLE framework
X(t) is the system state at time t

🔶 Interpretation
GTS(0) = 1 → initial condition
0 < GTS(t) < 1 → tension dissipation
GTS(t) → 0 → strong structural relaxation
GTS(t) ≈ 1 → persistence / plateau
GTS(t) > 1 → tension amplification

🔶 Key Properties
Non-negative
Normalized
Comparable across experiments
Monotonic under dissipative dynamics

# 🔷 Architecture of VEHICLE-T 3.0

The framework is organized into three layers:

### 🔹 Layer I — Core Dynamics
- State evolution  
- Global tension functional \(T(X)\)

### 🔹 Layer II — Observables
- Global Tension Signal (GTS)  
- Temporal derivatives  
- Structural indicators  

### 🔹 Layer III — Multi-Agent Evaluation (future extension)
- Actor Tensor analysis  
- Structural contribution analysis  
- Temporal dynamics analysis  
- Critical audit layer  
Actor Tensor analysis
Structural contribution analysis
Temporal dynamics analysis
Critical audit layer
# 🔷 Experiments

## Experiment 1 — Base Dynamics
Initial validation of global tension dissipation.

```bash
python experiments/exp1_base_dynamics.py

## Experiment 2 — Coupling Comparison

Comparison between systems with and without internal coupling (λ=0 vs λ>0).

python experiments/exp2_coupling_comparison.py

## Experiment 3 — Lambda Sweep

Systematic analysis of behavior under varying internal coupling strengths.

python experiments/exp3_lambda_sweep.py

## Experiment 4 — Global Tension Signal (GTS)

Introduction of the primary observable of VEHICLE-T 3.0.

This experiment computes:

- raw tension
T(X(t))
- normalized signal
GTS(t)
- temporal variation
ΔGTS(t)
- comparison across different coupling regimes

python experiments/exp4_gts_observable.py

🔷 Repository Structure
vehicle_dynamics_lab/
│
├── vehicle/

│   ├── __init__.py

│   ├── tension.py

│   ├── observables.py

│   ├── dynamics.py

│   ├── systems.py

│   └── plotting.py
│
├── experiments/

│   ├── exp1_base_dynamics.py

│   ├── exp2_coupling_comparison.py

│   ├── exp3_lambda_sweep.py

│   └── exp4_gts_observable.py

│
├── tests/

│   ├── test_tension.py

│   └── test_observables.py

│
└── README.md


🔷 Requirements

Python 3
numpy
matplotlib

Install dependencies:

pip install numpy matplotlib
🔷 Scientific Positioning

VEHICLE-T 3.0 shifts the framework from:

trajectory observation → measurable structural signal

The introduction of GTS enables:

rigorous comparison between systems
detection of structural regimes (dissipation, plateau, amplification)
integration with higher-level analytical layers
🔷 Future Work
Multi-agent critical evaluation layer (4 IA system)
Structural decomposition of tension
Real-world domain instantiations:
geopolitical systems
corporate competition
technological rivalry networks
🔷 Author

Roberto Borda Milan
AIMTG — International Agency for Global Tension Measurement

🔷 Closing Statement

Structure precedes equilibrium.
Compatibility precedes consensus.
Measurement precedes interpretation.
