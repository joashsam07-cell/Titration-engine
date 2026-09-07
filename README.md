# 🧪 Universal Dynamic Titration Calculator & Simulation Engine

An advanced, interactive web-based analytical chemistry engine and titration simulation tool designed for precise chemical calculations, assay testing, and pharmaceutical analysis.

* **Author:** Joash Sam  
* **Application Category:** Scientific / Educational Web Tool  
* **Target Environment:** Client-side web browser (HTML5 / CSS3 / Vanilla JavaScript)

---

## ✨ Key Features

* **Interactive SVG Titration Simulator:** Real-time visual representation of a burette and conical flask setup complete with drop animations and color transition indicators near the endpoint.
* **Comprehensive Chemical Databases:** Built-in properties (Molecular Weights, Equivalent Weights, Melting/Boiling points, Aqueous Solubilities, Physical States, and Reaction Equations) for a wide range of titrants and titrands:
  * *Burettes:* NaOH, HCl, $\text{KMnO}_4$, $\text{Na}_2\text{S}_2\text{O}_3$, $\text{I}_2$, $\text{HClO}_4$, Ceric Ammonium Sulphate, Disodium EDTA.
  * *Flasks:* Oxalic Acid, KHP, $\text{Na}_2\text{CO}_3$, Benzoic Acid, Salicylic Acid, Aspirin, $\text{NaHCO}_3$, $\text{NH}_4\text{Cl}$, Acetic Acid, $\text{H}_2\text{O}_2$, $\text{FeSO}_4$, Sodium Benzoate, Boric Acid.
* **Flexible Flask Input Modes:** 
  * By Normality & Pipetted Volume ($V_1$)
  * By Mass (g) & Total Volume Made Up ($mL$)
  * Unknown Sample Mode (pauses simulation for manual laboratory input)
* **Dynamic Titration Readings Table:** Multi-trial support with automatic titer volume computation, support for adding custom trial rows, and selection algorithms for **Mean (Average)** or **Concordant** readings.
* **Multi-Target Calculation Engine:**
  * Find Normality of Burette Titrant (Standardization)
  * Find Normality of Flask Titrand
  * Calculate Assay / Percentage Purity ($\% \text{ w/v}$)
  * Calculate Solubility ($\text{g}/100\text{ mL}$ and $\text{g/L}$)
* **Cloud Sync Integration:** Automatically transmits experimental trial parameters and calculated outputs directly to a connected Google Apps Script / Google Sheets backend.

---

## 🚀 Getting Started & Usage

1. **Open the Application:*
2. **Configure Burette:** Select your titrant reagent from the dropdown and check its physicochemical properties using the info button (💡).
3. **Configure Flask:** Choose your sample chemical and select your input mode (Normality, Mass, or Unknown).
4. **Run Simulation or Input Readings:** 
   * Use the interactive simulation panel buttons (`+1.0 mL`, `+0.1 mL (Drop)`) to simulate liquid dispensing and observe color changes.
   * Alternatively, expand the **Feed Burette Readings** table to manually enter your experimental initial and final burette readings across multiple trials.
5. **Calculate Results:** Choose your target calculation in Section 5 to instantly view computed normalities, purities, or solubilities alongside standard volumetric factor equations.

---

## 🛠️ Technical Stack

* **Markup & Styling:** HTML5, CSS3 (Custom properties/variables, responsive flexbox/grid layouts)
* **Scripting:** Vanilla JavaScript (ES6+, DOM manipulation, Fetch API)
* **Graphics:** Inline Scalable Vector Graphics (SVG) for the laboratory apparatus simulation viewport.
