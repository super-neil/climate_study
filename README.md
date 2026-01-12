# 🌍 Climate Monitor & Future Simulator

![Language](https://img.shields.io/badge/language-Python-blue.svg)
![Libraries](https://img.shields.io/badge/libraries-Pandas%20%7C%20Matplotlib%20%7C%20SciPy-orange.svg)
![Data Source](https://img.shields.io/badge/data-NASA%20%7C%20NOAA%20%7C%20EPA-green.svg)
![Status](https://img.shields.io/badge/status-Live%20Telemetry-red.svg)

**A data science project that aggregates real-time environmental telemetry from US Government servers to visualize the state of the Earth's climate.**

Unlike static reports, this tool fetches the latest available data every time it runs, providing an up-to-the-minute health check of the planet. It moves beyond simple observation to include **predictive modeling**, **ecological simulations**, and **policy sensitivity analysis**.

---

## 📉 The Scientific Narrative

This notebook is structured as a forensic investigation into planetary health, connecting distinct datasets to prove causality:

1.  **The Signal:** Visualizing the Global Temperature Anomaly (NASA GISTEMP).
2.  **The Cause:** Tracking Atmospheric CO₂ via the "Keeling Curve" (NOAA).
3.  **The Proof:** A dual-axis correlation study ($R \approx 0.9$) and a Solar Activity analysis that statistically disproves the "It's the Sun" hypothesis.
4.  **The Symptoms:**
    * **Arctic Sea Ice:** Tracking the decline of the September Minimum (NSIDC).
    * **Sea Level Rise:** Combining historical tide gauges with modern satellite altimetry (EPA/NOAA).
5.  **The Context:** The "Hockey Stick" graph, contrasting modern CO₂ against 800,000 years of Ice Core data.

---

## 🔮 Simulations & Modeling

Beyond observation, this project includes advanced simulation cells to model potential futures:

* **🐺 Trophic Cascades (The Wolf Effect):** A Lotka-Volterra ecosystem simulation demonstrating how reintroducing predators can restore carbon-sequestering forests.
* **🌳 Re-wilding Impact:** A projection model estimating the CO₂ drawdown potential of 0.9 billion hectares of new forest vs. current emission rates.
* **🏭 Policy Sensitivity Analysis:** A "What If" model simulating the atmospheric impact of the US withdrawing from climate treaties and increasing production.
* **🫁 The "Earth's Breath":** A seasonal decomposition analysis isolating the biosphere's natural carbon absorption (Summer) vs. release (Winter).

---

## 🏛️ Live Data Sources

All data is fetched programmatically from official government repositories:

| Metric | Source | Description |
| :--- | :--- | :--- |
| **Temperature** | [NASA GISS](https://data.giss.nasa.gov/gistemp/) | Global Land-Ocean Temperature Index |
| **CO₂** | [NOAA GML](https://gml.noaa.gov/ccgg/trends/) | Mauna Loa Observatory Monthly Mean |
| **Sea Ice** | [NSIDC](https://nsidc.org/data/seaice_index) | Arctic Sea Ice Extent (Satellite) |
| **Sea Level** | [EPA / NOAA](https://www.epa.gov/climate-indicators) | Tide Gauge & Satellite Altimetry |
| **Solar Activity** | [SILSO](https://www.sidc.be/SILSO/) | Sunspot Number (Royal Observatory of Belgium) |
| **Ozone** | [NASA Ozone Watch](https://ozonewatch.gsfc.nasa.gov/) | Antarctic Ozone Hole Area |
| **Paleoclimatology** | [NOAA NCEI](https://www.ncei.noaa.gov/products/paleoclimatology) | EPICA Dome C Ice Core Data (800k years) |

---

## 🚀 Installation & Usage

### 1. Prerequisites
Ensure you have Python 3.x and the following scientific libraries installed:

```bash
pip install pandas matplotlib numpy scipy