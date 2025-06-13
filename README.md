

````markdown
# 🧠 NeuroSim: Neural Response Simulation to Deep Brain Stimulation (DBS)

This project simulates the membrane potential response of neural axons to Deep Brain Stimulation (DBS) using mathematical models and visualizations. It includes both simple and realistic approximations of neural responses, measuring key parameters such as peak potential, response persistence, and latency.

---

## 📌 Features

- 📊 **Simulation of membrane potential** in response to varying input currents  
- ⏱️ **Latency & persistence analysis** of neural signals  
- 📈 **Matplotlib-based visualizations** with legends and annotated tables  
- ⚡ Realistic and adjustable **Gaussian modeling** of signal responses  

---

## 🧪 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SG7504/NeuroSim-Project.git
   cd NeuroSim-Project
````

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Running the Code

You can run individual simulation scripts from the `code/` folder:

```bash
python code/code_3_analysis_metrics.py
```

(Or `.txt` versions, but `.py` is preferred for direct execution.)

Ensure you have:

* `numpy`
* `matplotlib`
* (Optional) `neuron` package (install with `pip install neuron`)

---

## 📊 Outputs

Each simulation produces:

* A line plot showing membrane potential over time for varying currents
* A table summarizing:

  * Current intensity (mA)
  * Peak potential (mV)
  * Persistence duration (ms)
  * Latency to activation (ms)

---

## 🧠 Scientific Context

Deep Brain Stimulation (DBS) is a neurosurgical technique used to manage disorders such as Parkinson’s disease. This simulation helps explore how axons respond to such stimulation at a computational level, aiding in:

* Electrode design
* Stimulation optimization
* Research in neuroprosthetics

---

## 📄 License

This project is open-source under the **MIT License**. Feel free to use, adapt, and share with attribution.

---

## 👨‍💻 Author

**Sparsh Guha**
GitHub: [@SG7504](https://github.com/SG7504)
AI/ML

````

---

### ✅ Final Tip

Convert your `.txt` files (e.g. `code_3_analysis_metrics.txt`) to `.py` files. It'll improve usability and clarity:

```powershell
rename code_3_analysis_metrics.txt code_3_analysis_metrics.py
````

Let me know if you'd like to add images, GitHub badges, or a short usage video/gif in the README.
