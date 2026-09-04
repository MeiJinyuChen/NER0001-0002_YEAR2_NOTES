
# Section A
## **Voltage Clamp Analysis**
### **a) Description and Explanation of the Current Trace**
The observed current trace (right panel) represents the membrane's response to a rapid hyperpolarizing step. It can be decomposed into three distinct electrical and biological components:
**1. Capacitive Currents ($I_c$)** At $t = 110\text{ ms}$ and $t = 112\text{ ms}$, sharp vertical spikes appear. These are not ionic currents but "physical" currents required to charge the membrane capacitance.
- **At 110 ms:** An inward (downward) spike occurs as the voltage clamp removes positive charge from the intracellular side to reach $-120\text{ mV}$.
- **At 112 ms:** An outward (upward) spike occurs as the clamp adds positive charge to return the potential to $-40\text{ mV}$.
**2. Leak Current** During the 2 ms interval at $-120\text{ mV}$, a small, steady inward current is maintained. Since active channels are largely closed at this potential, this represents the "leak" through the membrane's background resistance ($R_m$). It is close to 0 because all Potassium leak channels are blocked by 100 mM TEA.
**3. Sodium Tail Current** The most significant biological feature is the transient inward current immediately following the return to $-40\text{ mV}$. This is a **sodium tail current**, explained by the kinetics of the $Na^+$ channel gates (the $m$ and $h$ gates):
- **De-inactivation:** At the holding potential of $-40\text{ mV}$, $Na^+$ channels are mostly inactivated ($h$-gate closed). The 2 ms step to $-120\text{ mV}$ hyperpolarizes the membrane sufficiently to "reset" or de-inactivate the channels, swinging the $h$-gates open.
- **The Tail:** Upon returning to $-40\text{ mV}$, the $m$-gates (activation) are briefly open due to the depolarisation, while the $h$-gates have not yet re-closed. This "open window," combined with a massive driving force $(V_m - E_{Na})$, allows a sudden influx of $Na^+$.
- **Decay:** The current decays as the $h$-gates quickly return to the inactivated state at $-40\text{ mV}$.
### **b) Effect of Stepping to +60 mV**
If the potential were stepped to $+60\text{ mV}$ instead of $-40\text{ mV}$, two major changes would occur:
- **Elimination of the Tail Current:** $+60\text{ mV}$ is typically the Equilibrium Potential for Sodium ($E_{Na}$). According to Ohm’s Law for membranes ($I_{Na} = g_{Na} \cdot (V_m - E_{Na})$), the driving force becomes zero. Consequently, even if the $Na^+$ channels are open, no net ionic current will flow.
- **Inversion of Direction:** If the step exceeded $E_{Na}$, the tail current would reverse direction and become **outward**, as the electrical gradient would push $Na^+$ out of the cell.
### **c) Recording in 1 $\mu$M TTX (Without 100 mM TEA)**
If the experiment were repeated with TTX (a $Na^+$ channel blocker) and without TEA (a $K^+$ channel blocker), the trace would be fundamentally altered:
**1. Abolition of the Tail:** The inward $Na^+$ tail current would be entirely absent because TTX binds to the extracellular pore of $Na^+$ channels, preventing ion permeation regardless of gating states.
**2. Activation of Outward Potassium Current:** Upon returning to $-40\text{ mV}$ (or higher), a large, sustained **outward current** would be observed.
- **Mechanism:** Without TEA, voltage-gated $K^+$ channels ($n$-gates) are free to open in response to the relatively depolarized $-40\text{ mV}$ potential.
- **Direction:** Since $E_K$ is approximately $-90\text{ mV}$, the driving force $(V_m - E_K)$ at $-40\text{ mV}$ is positive ($+50\text{ mV}$), causing $K^+$ to exit the cell. Unlike $Na^+$ channels, $K^+$ channels do not rapidly inactivate, resulting in a sustained plateau of outward current.



-----

# Section B

## **Question 2: Characterization of a Novel Ion Channel**
To determine if a newly cloned protein is a functional ion channel and to characterize its biophysical properties, I would implement the following experimental workflow:
### **a) Verification of Ion Channel Function**
The primary requirement is to demonstrate that the protein facilitates the passive movement of ions across a membrane.
- **Method:** I would use **Heterologous Expression** in _Xenopus_ oocytes or HEK293 cells.
- **Evidence:** Using **Patch-Clamp recording** (cell-attached or whole-cell), I would look for "quantized" current steps. The presence of discrete on/off current levels in response to a stimulus—which are absent in non-transfected control cells—provides definitive evidence of a pore-forming ion channel.
### **b) Ion Selectivity**
- **Method:** I would determine the **Reversal Potential ($E_{rev}$)** by generating I-V (Current-Voltage) curves.
- **Experiment:** By systematically varying the extracellular ionic composition (e.g., replacing $Na^+$ with $K^+$ or $Cs^+$), I would measure the resulting shift in $E_{rev}$.
- **Logic:** Using the **Nernst Equation** or the **Goldman-Hodgkin-Katz (GHK) equation**, a shift in $E_{rev}$ that tracks the equilibrium potential of a specific ion identifies the channel's selectivity. For example, if $E_{rev}$ follows changes in $[K^+]_o$, the protein is a $K^+$ channel.
### **c) Voltage-Dependence**
- **Method:** I would apply a series of **Voltage Steps** from a fixed holding potential to various test potentials.
- **Analysis:** I would calculate the conductance ($G$) at each voltage using $G = I / (V_m - E_{rev})$ and plot a **G-V curve**.
- **Logic:** A sigmoidal G-V curve indicates that the open probability ($P_{open}$) is voltage-dependent, suggesting the presence of a voltage-sensor domain (typically $S4$ segments) within the protein structure.
### **d) Modulation by $Ca^{2+}$ or cAMP**
- **Intracellular $Ca^{2+}$:** I would use the **Inside-Out Patch** configuration to expose the intracellular C-terminus to varying $[Ca^{2+}]_i$. If current increases with $[Ca^{2+}]_i$, the channel is $Ca^{2+}$-activated.
- **cAMP Modulation:** I would apply cAMP analogs (e.g., 8-bromo-cAMP) or stimulate adenylyl cyclase with Forskolin while recording in whole-cell mode. This determines if the channel is regulated via direct binding (like HCN channels) or phosphorylation by Protein Kinase A (PKA).

## **Question 3: Regulation of Intracellular $Zn^{2+}$**
Zinc ($Zn^{2+}$) regulation is critical for enzymatic function, yet toxic at high levels. Evolution likely adapted mechanisms similar to $Ca^{2+}$ homeostasis to maintain low cytosolic $[Zn^{2+}]_i$.
### **Mechanisms of Intracellular Regulation**
1. **Active Efflux (Primary Active Transport):** Similar to the PMCA for calcium, cells likely utilize **Zn-ATPases** to pump $Zn^{2+}$ out against its electrochemical gradient.
2. **Secondary Active Transport:** Evolution may have produced **$Zn^{2+}/Na^+$ exchangers** (analogous to the NCX), using the sodium gradient to drive $Zn^{2+}$ efflux.
3. **Sequestration:** Just as the Sarco-Endoplasmic Reticulum (SER) stores $Ca^{2+}$, specialized transporters (such as **ZnT transporters**) likely move $Zn^{2+}$ into intracellular organelles (mitochondria or "zincosomes").
4. **Buffering:** Cytoplasmic proteins, such as **Metallothioneins**, likely act as "sponges" to bind free $Zn^{2+}$, effectively lowering the concentration of bioactive free ions.
### **The Impact of Metabolic Insult (Stroke)**
During a stroke, the loss of blood flow results in a failure of ATP production.
- **Failure of Pumps:** Without ATP, $Zn^{2+}$-ATPases and $Na^+/K^+$-ATPases fail. The loss of the $Na^+$ gradient subsequently halts $Zn^{2+}/Na^+$ exchange.
- **Release from Stores:** Low ATP levels disrupt the membrane integrity of intracellular organelles, causing sequestered $Zn^{2+}$ to leak into the cytoplasm.
- **Excitotoxicity:** In stroke, massive glutamate release activates NMDA receptors, which are permeable to $Zn^{2+}$.
- **Prediction:** I predict a **massive rise in intracellular $[Zn^{2+}]_i$**, contributing to oxidative stress and neuronal death.

## **Question 4: Calcium Signaling and Compound YM023**
This experiment distinguishes between extracellular $Ca^{2+}$ influx and intracellular $Ca^{2+}$ release.
### **1. High $K^+$ Response: Extracellular Influx**
- **Mechanism:** Increasing extracellular $[K^+]$ shifts the equilibrium potential for $K^+$ ($E_K$) to a more positive value, depolarizing the neuron.
- **Observation:** This depolarization activates **Voltage-Gated Calcium Channels (VGCCs)**.
- **Evidence:** The failure of this response in "zero $Ca^{2+}$ + EGTA" medium proves that the initial increase was entirely dependent on $Ca^{2+}$ influx from the extracellular space.
### **2. YM023 Response: Intracellular Release**
- **Observation:** YM023 evokes a $Ca^{2+}$ increase even when extracellular $Ca^{2+}$ is buffered by EGTA.
- **Logic:** Because there is no $Ca^{2+}$ outside the cell, the increase must come from **intracellular stores**, such as the Endoplasmic Reticulum (ER).
- **Potential Molecular Mechanisms:**
    - **$IP_3$ Receptor Agonist:** YM023 may mimic $IP_3$ or activate Phospholipase C (PLC), leading to the opening of $IP_3$ receptors on the ER.
    - **Ryanodine Receptor Activator:** It could act as an agonist for Ryanodine receptors, triggering "Calcium-Induced Calcium Release" (CICR).
    - **Thapsigargin-like effect:** It might inhibit the SERCA pump, preventing $Ca^{2+}$ re-uptake and allowing constitutive leak to raise cytosolic levels.
### **Conclusion**
The results suggest that while $K^+$-induced depolarization relies on **VGCCs** for influx, the compound YM023 bypasses the plasma membrane to mobilize **internal $Ca^{2+}$ stores**.