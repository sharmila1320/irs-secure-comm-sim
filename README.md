#  IRS-Assisted Secure Wireless Communication (6G Simulation)

This simulation demonstrates how an **Intelligent Reflecting Surface (IRS)** can improve the **secrecy capacity** of a wireless system, ensuring secure communication even in the presence of an eavesdropper.

---

##  Problem Setup

* A base station sends signals to a **legitimate user (Bob)**.
* An **eavesdropper (Eve)** tries to intercept the signal.
* An IRS with N elements reflects and steers the signal to **maximize Bob's SNR** and **minimize Eve's**.

---

##  What We Simulate

* The **secrecy capacity**, calculated as:

  $$
  C_s = [\log_2(1 + \text{SNR}_\text{Bob}) - \log_2(1 + \text{SNR}_\text{Eve})]^+
  $$

* Comparison of secrecy performance:

  *  With IRS vs  Without IRS
  *  Across different numbers of IRS elements

---

## Key Concepts

* **Reconfigurable Intelligent Surface (RIS)** = smart wall that reflects wireless signals in desired directions
* **Beamforming** = focusing the signal toward a target
* **SNR (Signal-to-Noise Ratio)** = how clearly the signal is received
* **Secrecy Capacity** = how much better Bob hears than Eve

---

## How to Run

1. Clone the repo
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Launch the notebook:

```bash
jupyter notebook irs_simulation.ipynb
```

---

## 📚 Credits

Created by **Sharmila Rapeti**
ECE'26 Student @ NIT Silchar | Summer Intern @ SERB-CRG | 6G Wireless & RIS Enthusiast
