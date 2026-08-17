

# Statistical mechanics + Thermodynamics = POWER !!!

- Chemical thermodynamics
- Chemical kinetics
- Colloid and Surface Chemistry
- Materials Science and Solid-State Chemistry
- Quantum Chemistry and Molecular Modeling
- Enzymatic Catalysis
- Protein Thermodynamics
- Biomolecular Thermodynamics in the Cell
- Membrane Biophysics
- ...


---

# Statistical mechanics

:::matrix {cols="80/20"}
[[0,0]]
- assumes molecular (classical or quantum) composition of matter microstates
- uses probability distributions to cope with huge number equations of motion
- calculates measurable parameters as statistical / quantum mechanical averages

**Maxwell–Boltzmann distribution:**
$$
f(\mathbf{v}) \equiv \left[ \frac{2\pi k_{\text{B}} T}{m} \right]^{-3/2} \exp\left(-\frac{1}{2} \frac{m\mathbf{v}^2}{k_{\text{B}}T}\right).
$$
$$
\mathbb{E}[v] = \sqrt{\frac{8k_B T}{\pi m}} \qquad \mathbb{E}[v^2] = \frac{3k_B T}{m}
$$

**Brownian motion:**
$$
\rho(x,t) = \frac{N}{\sqrt{4\pi Dt}} \exp\left(-\frac{x^2}{4Dt}\right).
$$
$$
\mathbb{E}[x^2] = 2Dt.
$$
**Other results**: blackbody radiation, Fermi-Dirac statistics, Bose-Einstein statistics, Debye-Einstein heat capacity, etc.
[[0,1]]
![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_3_img_1.png)
![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_3_img_2.png) {width="70%"}
![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_3_img_4.png) {width="70%"}
:::

---

# Thermodynamics

* largely phenomenological branch of science that ignores molecular (classical or quantum) composition of matter
* macrostates (thermodynamic states)
* uses state functions aka potentials - quantities that depend on the macrostate and independent on the path
* uses calculus to establish useful relations between the thermodynamic functions
* key concepts: isolated system, thermodynamic equilibrium, quasistatic process, reversible process

## 3 Laws of Thermodynamics

**Zeroth law:** If two systems are each in thermal equilibrium with a third, they are also in thermal equilibrium with each other.
$$
T \text{ is a state variable}
$$

**First law:** In a process without transfer of matter, the change in internal energy, $\Delta U$ of a thermodynamic system is equal to the energy gained as heat, Q minus the thermodynamic work A, done by the system on its surroundings.
$$
\Delta U = \Delta Q - A
$$

**Second law:** Heat does not spontaneously flow from a colder body to a hotter body.
$$
\text{For a reversible process:} \qquad dS = \frac{\delta Q}{T}
$$

**Third law:** As the temperature of a system approaches absolute zero, all processes cease and the entropy of the system approaches a minimum value.
$$
S(T = 0 \text{ K}) = 0
$$

---

# State variables / state functions
## (macro coordinates of the system / properties that don’t depend on the path)

:::matrix {cols="33/33/33"}
[[0,1::3]]
![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_5_img_13.png)
[[0,0:2]]
- $\mathbf{P}$, $\mathbf{T}$, $\mathbf{V}$ --- pressure, temperature, volume
- $\mathbf{U}$ --- internal energy
- $\mathbf{S}$ --- entropy
- $\mathbf{H}$ --- enthalpy
- $\mathbf{G}$ --- Gibbs free energy
- $\mathbf{F}$ --- Helmholtz free energy

$ \color{red}{\xcancel{\color{black}{Q}}}$ Heat is not a state function (no *heat fluid*)
[[1,0:3]]
You don’t need all of them: for a homogeneous system in thermodynamic equilibrium you can pick any 2 of them (the rest are called state functions dependent on the chosen state variables).

When property is **extensive** (proportional to the size of the homogeneous system) we can define specific or molar quantity. 
[[2,0:2]]
Ex:<br>
* **specific enthalpy** $h = H/m$<br>
* **standard molar enthalpy** $H^\circ = H/n$ at $p = 1 \text{ atm}$

$\mathbf{V, U, S, H, G, F}$ - extensive properties $\rightarrow$ $\mathbf{V^\circ, U^\circ, S^\circ, H^\circ, G^\circ, F^\circ}$
[[2,2]]
**Standard conditions** for Gibbs free energy are a temperature of $25^\circ$ C ($298$ K) and a pressure of $1$ atm (or $100$ kPa) for gases, with $1$ M concentration for all aqueous solutions. Designated with $^\circ$.

:::
---

# Explanation of Thermodynamic Quantities: $\Delta G^\circ = \Delta H^\circ - T\Delta S^\circ$

| Term | Name | Explanation |
| :--- | :--- | :--- |
| $\color{#279B61}{\Delta G^\circ}$ | <span style="color: #279B61; font-weight: bold;">Gibbs free-energy change</span> | Represents the difference in energy between products and reactants. A negative $\Delta G^\circ$ indicates an **exergonic** reaction that proceeds spontaneously with a favorable equilibrium constant. Conversely, a positive $\Delta G^\circ$ denotes an **endergonic** reaction, which is nonspontaneous and has an unfavorable equilibrium constant. |
| $\color{#D91E76}{\Delta H^\circ}$ | <span style="color: #D91E76; font-weight: bold;">Enthalpy change</span> | The overall heat associated with a reaction, reflecting the net difference in bond strengths between newly formed bonds and those broken. A negative $\Delta H^\circ$ signifies an **exothermic** process where heat is released. A positive $\Delta H^\circ$ signifies an **endothermic** process where heat is absorbed. |
| $\color{#2B8CBE}{\Delta S^\circ}$ | <span style="color: #2B8CBE; font-weight: bold;">Entropy change</span> | The shift in the system's molecular disorder or randomness resulting from a reaction. A negative $\Delta S^\circ$ means the system becomes less random; a positive $\Delta S^\circ$ indicates an increase in molecular randomness. |

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 47.44%; top: 0.00%; width: 13.47%; height: 16.51%;">

**Enthalpy (H)**

</div>

<div style="position: absolute; left: 20.58%; top: 17.97%; width: 70.50%; height: 27.29%;">

*H = U + pV*
If the system is under constant pressure, dp = 0 the increase in enthalpy of the system is equal to the heat added

</div>

<div style="position: absolute; left: 43.41%; top: 12.84%; width: 37.93%; height: 13.47%;">

*work that would be required to "make room" for the system if the pressure of the environment remained constant.*

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_7_img_15.png) {left=33.12 top=46.72 width=45.42 height=38.61}

<div style="position: absolute; left: 21.66%; top: 88.32%; width: 65.90%; height: 6.59%;">

We have an analog of “heat fluid” but at **constant pressure only**

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 14.50%; top: 33.49%; width: 83.76%; height: 16.51%;">

There are a lot of “different” enthalpies that refer to the enthalpy change in various processes:

</div>

<div style="position: absolute; left: 19.38%; top: 48.74%; width: 38.54%; height: 70.49%;">

mean bond enthalpy
enthalpy of reaction
enthalpy of formation
enthalpy of combustion
enthalpy of neutralisation
enthalpy of fusion 
enthalpy of vaporisation 
enthalpy of sublimation
enthalpy of solution

</div>

<div style="position: absolute; left: 15.25%; top: 0.00%; width: 70.50%; height: 27.29%;">

∆H < 0 **endothermic **reaction

∆H > 0 **exothermic **reaction

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_8_img_16.png) {left=65.94 top=10.22 width=23.94 height=27.29}

<div style="position: absolute; left: 52.00%; top: 55.37%; width: 38.62%; height: 29.85%;">

enthalpy of hydration
enthalpy of atomisation
lattice formation enthalpy
lattice dissociation enthalpy
first ionisation energy
second ionisation energy

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_8_img_17.png) {left=42.09 top=46.77 width=24.46 height=4.92}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_8_img_18.png) {left=52.38 top=4.28 width=24.46 height=5.30}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_8_img_19.png) {left=77.97 top=3.46 width=15.05 height=5.70}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 16.51%;">

**Strong endothermic reaction**

</div>

![youtube](kb6-xzFr4nk) {left=17.89 top=15.36 width=76.72 height=76.72}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_10_img_20.png) {left=18.76 top=54.78 width=37.60 height=20.78}

<div style="position: absolute; left: 48.23%; top: -4.23%; width: 13.47%; height: 16.51%;">

**Hess’s law**

</div>

<div style="position: absolute; left: 14.67%; top: 7.55%; width: 83.29%; height: 40.10%;">

if a reaction is carried out in a series of steps, ∆H for the overall reaction equals the **sum **of the enthalpy changes for the **individual steps**. The overall enthalpy change for the process is independent of the number of steps and independent of the path by which the reaction is carried out.

This law is a consequence of the fact that enthalpy is a state function. We can therefore calculate ∆H for any process as long as we find a route for which ∆H is known for each step. This means that a relatively small number of experimental measurements can be used to calculate ∆H for a vast number of reactions.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_10_img_21.png) {left=59.18 top=53.50 width=16.57 height=23.34}

<div style="position: absolute; left: 14.67%; top: 46.11%; width: 5.61%; height: 7.78%;">

Ex.

</div>

<div style="position: absolute; left: 14.67%; top: 84.20%; width: 80.59%; height: 11.37%;">

Hess’s law provides a useful means of **calculating **energy changes that are difficult to **measure **directly.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_10_img_22.png) {left=78.57 top=55.07 width=14.35 height=21.70}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 16.51%;">

The formation of CO2(g) from its elements can be thought of as occurring in two steps, which sum to the overall reaction, as described by Hess’s law. The horizontal blue lines represent enthalpies. For an exothermic process, the products are at lower enthalpy than are the reactants.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_11_img_23.png) {left=17.63 top=23.94 width=80.18 height=73.76}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_12_img_24.png) {left=42.76 top=0.00 width=56.35 height=71.17}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_12_img_25.png) {left=18.20 top=76.46 width=81.80 height=23.76}

<div style="position: absolute; left: 18.81%; top: 3.52%; width: 23.95%; height: 67.65%;">

Part of the explanation for this trend lies in the electron-releasing effect of alkyl
groups, an effect that satisfies the electron-withdrawing properties of the
sp2-hybridized carbon atoms of the double bond.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 17.70%; top: 3.85%; width: 80.75%; height: 11.22%;">

Using Hess’s Law find enthalpy of Chlorine monofluoride reacting with fluorine to form chlorine trifluoride:

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_13_img_26.png) {left=30.63 top=15.07 width=54.90 height=11.11}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_13_img_27.png) {left=20.10 top=26.18 width=79.90 height=33.97}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_13_img_28.png) {left=35.80 top=60.15 width=62.66 height=33.92}

<div style="position: absolute; left: 19.37%; top: 69.86%; width: 14.48%; height: 15.51%;">

**solution:**

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 48.73%; top: -1.07%; width: 13.47%; height: 16.51%;">

**Entropy (S)**

</div>

<div style="position: absolute; left: 18.47%; top: 6.49%; width: 70.50%; height: 54.03%;">

state function that is the measure of the number of possible microscopic arrangements or states of individual atoms and molecules of a system that comply with the macroscopic condition of the system.
Thermodynamics (for reversible process! ‘>’ for irreversible):

Statist. mechanics:

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_14_img_29.png) {left=12.01 top=53.00 width=62.33 height=44.50}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_14_img_30.png) {left=43.64 top=31.56 width=10.56 height=6.81}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_14_img_31.png) {left=43.90 top=41.37 width=11.39 height=5.57}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_14_img_32.png) {left=75.87 top=68.54 width=22.05 height=31.46}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_14_img_33.png) {left=79.11 top=34.38 width=16.17 height=28.80}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_34.png) {left=27.49 top=3.33 width=38.29 height=7.75}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_35.png) {left=80.66 top=1.21 width=18.18 height=50.18}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_36.png) {left=15.97 top=16.64 width=27.91 height=6.92}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_37.png) {left=15.97 top=24.41 width=60.71 height=14.40}

<div style="position: absolute; left: 15.62%; top: 9.10%; width: 26.67%; height: 8.08%;">

Example:

</div>

<div style="position: absolute; left: 15.84%; top: 44.48%; width: 26.67%; height: 8.08%;">

Example:

</div>

<div style="position: absolute; left: 15.72%; top: 48.94%; width: 45.14%; height: 9.27%;">

Consider 1 mol of ice melting at T = 310K.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_38.png) {left=16.81 top=58.22 width=36.49 height=9.81}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_39.png) {left=58.33 top=58.63 width=36.61 height=8.08}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_40.png) {left=17.16 top=70.93 width=45.14 height=4.94}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_41.png) {left=35.44 top=42.77 width=21.77 height=4.94}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_15_img_42.png) {left=34.70 top=80.10 width=36.49 height=11.36}

<div style="position: absolute; left: 17.16%; top: 91.45%; width: 79.77%; height: 7.18%;">

**The entropy of the universe increases in any spontaneous process.**

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 24.14%; top: 36.17%; width: 70.99%; height: 16.51%;">

The sign of G tells us whether the reaction is spontaneous at constant** pressure **and **temperature:**

</div>

<div style="position: absolute; left: 45.60%; top: 0.00%; width: 35.62%; height: 16.51%;">

**Gibbs free energy (G)**

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_16_img_43.png) {left=39.53 top=48.68 width=38.46 height=21.94}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_16_img_44.png) {left=24.14 top=75.66 width=70.62 height=20.86}

<div style="position: absolute; left: 23.73%; top: 17.31%; width: 70.99%; height: 16.51%;">

G = H - TS
The change in free energy for a process, ∆G, equals the maximum useful work that can be done by the system on its surroundings in a spontaneous process occurring at constant temperature and pressure.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 15.53%; top: 59.73%; width: 76.66%; height: 7.78%;">

For a mix of ideal gases of reactants and products:

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_17_img_45.png) {left=20.61 top=71.83 width=48.14 height=23.17}

<div style="position: absolute; left: 73.58%; top: 71.83%; width: 24.32%; height: 7.78%;">

‘mol’ - per 1 mole

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_17_img_46.png) {left=16.98 top=2.96 width=74.34 height=53.80}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_18_img_47.png) {left=68.38 top=-0.00 width=30.55 height=46.53}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_18_img_48.png) {left=19.59 top=7.50 width=19.57 height=12.21}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_18_img_49.png) {left=19.06 top=19.71 width=14.77 height=15.91}

<div style="position: absolute; left: 13.35%; top: 36.72%; width: 51.98%; height: 14.37%;">

In determining the value of Q, the concentrations of gases are always expressed as **partial pressures** in atmospheres and solutes are expressed as their concentrations in **molarities**.

</div>

<div style="position: absolute; left: 43.87%; top: 5.04%; width: 16.15%; height: 11.82%;">

reaction quotient

</div>

<div style="position: absolute; left: 47.37%; top: 58.03%; width: 21.48%; height: 11.82%;">

activities

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_18_img_50.png) {left=21.06 top=56.33 width=24.93 height=15.91}

<div style="position: absolute; left: 44.20%; top: 12.28%; width: 21.48%; height: 11.82%;">

equilibrium constant

</div>

<div style="position: absolute; left: 10.93%; top: 74.85%; width: 54.82%; height: 15.14%;">

If **Q < K**, then the reaction will **move to the right**.
If **Q > K**, then the reaction will **move to the left**.
If **Q = K**, then the reaction is at equilibrium

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_18_img_51.png) {left=71.96 top=46.70 width=24.39 height=55.32}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 13.67%; top: 26.68%; width: 58.52%; height: 32.92%;">

**Dynamic equilibrium** is the microscopic realization of thermodynamic equilibrium: opposing processes occur simultaneously at equal rates, so that no net macroscopic change takes place.
Examples: 
evaporation ↔ condensation, 
dissolution ↔  recrystallization,
dissociation ↔ recombination,
reversible chemical  reactions, 
etc

</div>

<div style="position: absolute; left: 9.03%; top: 13.66%; width: 63.79%; height: 16.76%;">

**Thermodynamic equilibrium** is the state of a system in which all macroscopic flows of energy and matter cease, all types of equilibrium (mechanical, thermal, and chemical) are satisfied, and the system’s macroscopic properties remain constant in time.

</div>

<div style="position: absolute; left: 13.61%; top: 56.94%; width: 79.14%; height: 6.88%;">

**Relation:** Dynamic equilibrium is the **microscopic mechanism **that sustains thermodynamic equilibrium.

</div>

<div style="position: absolute; left: 74.36%; top: 16.07%; width: 27.79%; height: 10.17%;">

**WHAT HAPPENS**
**Perspective of thermodynamics**

</div>

<div style="position: absolute; left: 74.36%; top: 27.76%; width: 32.81%; height: 10.17%;">

**HOW IT HAPPENS**
**Perspective of Stat.mechanics**

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_19_img_52.png) {left=18.71 top=67.59 width=19.00 height=30.84}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_19_img_53.png) {left=50.00 top=69.45 width=32.42 height=27.12}

<div style="position: absolute; left: 6.96%; top: 61.50%; width: 34.00%; height: 6.88%;">

**evaporation ↔ condensation**

</div>

<div style="position: absolute; left: 45.30%; top: 62.57%; width: 34.00%; height: 6.88%;">

**reversible chemical reactions**

</div>

<div style="position: absolute; left: 41.64%; top: 0.00%; width: 41.43%; height: 6.88%;">

Generalization of mechanical equilibrium

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_19_img_54.png) {left=77.48 top=-0.00 width=12.66 height=16.07}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 9.94%;">

**Dynamic equilibrium model**

</div>

![youtube](bDtkv8q-YGQ) {left=17.82 top=18.22 width=80.35 height=80.35}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_21_img_55.png) {left=16.80 top=3.29 width=83.20 height=28.56}

<div style="position: absolute; left: 17.52%; top: 34.94%; width: 82.48%; height: 11.97%;">

∆H and ∆S often change little with temperature. The value of T directly affects the magnitude of -T∆S.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_21_img_56.png) {left=36.08 top=55.48 width=30.79 height=7.78}

<div style="position: absolute; left: 17.52%; top: 50.00%; width: 82.48%; height: 7.78%;">

Example:

</div>

<div style="position: absolute; left: 17.52%; top: 65.12%; width: 38.15%; height: 7.78%;">

How ∆G changes with temperature?

</div>

<div style="position: absolute; left: 17.52%; top: 72.90%; width: 73.84%; height: 20.35%;">

We expect ∆S for this reaction to be negative because the number of molecules of
gas is smaller in the products. As a result, ∆G becomes less negative (or more positive) with increasing temperature. Thus, the driving force for the production of NH3 becomes smaller with increasing temperature.

</div>

<div style="position: absolute; left: 71.26%; top: 55.48%; width: 16.24%; height: 11.97%;">

Haber process

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 37.20%; top: 1.44%; width: 58.48%; height: 8.91%;">

Le Châtelier’s principle
(Le Chatelier–Braun principle, equilibrium law)

</div>

<div style="position: absolute; left: 14.92%; top: 13.15%; width: 55.52%; height: 17.95%;">

If the equilibrium of a system is disturbed by a change in one or more of the determining factors (as temperature, pressure, or concentration) the system tends to adjust itself to a new equilibrium by **counteracting **as far as possible the effect of the change.

</div>

<div style="position: absolute; left: 14.28%; top: 34.69%; width: 55.52%; height: 10.77%;">

Discovered in 1884 by extending the reasoning from the **Van ‘t Hoff relation**:

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_22_img_57.png) {left=28.58 top=43.60 width=41.86 height=51.87}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_22_img_58.png) {left=72.26 top=11.38 width=27.74 height=30.72}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_23_img_59.png) {left=30.89 top=45.16 width=48.42 height=54.84}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_23_img_60.png) {left=19.61 top=13.78 width=72.73 height=23.50}

<div style="position: absolute; left: 34.89%; top: 3.65%; width: 58.48%; height: 8.91%;">

Concentration and Le Châtelier’s principle.

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 16.51%;">

Removing products and Le Châtelier’s principle.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_24_img_61.png) {left=24.65 top=23.60 width=63.19 height=73.76}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_25_img_62.png) {left=33.90 top=37.59 width=50.01 height=62.41}

<div style="position: absolute; left: 32.27%; top: 1.73%; width: 58.48%; height: 8.91%;">

Temperature and Le Châtelier’s principle.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_25_img_63.png) {left=19.08 top=10.64 width=73.23 height=25.22}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_26_img_64.png) {left=19.21 top=16.91 width=75.27 height=77.27}

<div style="position: absolute; left: 21.24%; top: 2.91%; width: 58.48%; height: 8.91%;">

Previously, in Lecture 3:

</div>

<div style="position: absolute; left: 73.46%; top: 5.03%; width: 18.61%; height: 8.91%;">

Le Châtelier’s principle

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 29.20%; top: 2.11%; width: 80.35%; height: 10.60%;">

**Temperature and Le Châtelier’s principle.**

</div>

![youtube](z_iLK7gm_fo) {left=15.14 top=12.72 width=80.35 height=80.35}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 32.87%; top: -0.00%; width: 80.35%; height: 16.51%;">

Pressure and Le Châtelier’s principle.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_28_img_65.png) {left=19.35 top=31.81 width=80.35 height=68.19}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_28_img_66.png) {left=11.72 top=13.92 width=86.20 height=17.89}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 16.07%; top: 3.81%; width: 80.35%; height: 16.51%;">

Intermediates and transition states

</div>

<div style="position: absolute; left: 16.07%; top: 24.12%; width: 80.35%; height: 62.89%;">

A **transition state** represents an energy maximum—any small displacement leads to a more stable product. An **intermediate**, on the other hand, is a molecule or ion that represents a localized energy minimum—an energy barrier must be overcome before the intermediate forms something more stable. Because of this energy barrier, it is even possible to isolate these reactive intermediates (RCO+) and study their spectra.

When considering kinetics **the highest transition state** is what matters.

The step leading to the highest transition state is called **the rate-determining step**

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_30_img_67.png) {left=19.18 top=18.37 width=80.82 height=65.13}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_31_img_68.png) {left=62.81 top=0.00 width=37.19 height=46.67}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_31_img_69.png) {left=17.67 top=55.93 width=82.33 height=44.07}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_31_img_70.png) {left=17.67 top=43.23 width=53.12 height=13.53}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_31_img_71.png) {left=20.95 top=18.69 width=41.86 height=13.53}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_32_img_72.png) {left=16.52 top=1.98 width=36.64 height=15.62}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_32_img_73.png) {left=15.12 top=29.09 width=37.51 height=68.87}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_32_img_74.png) {left=55.37 top=6.60 width=44.63 height=12.49}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_32_img_75.png) {left=56.15 top=32.93 width=43.07 height=65.04}

<div style="position: absolute; left: 16.52%; top: 19.64%; width: 34.71%; height: 9.45%;">

rate = k[MeCOCl][RO–]

</div>

<div style="position: absolute; left: 57.24%; top: 19.36%; width: 40.66%; height: 9.45%;">

rate = k[R1COCl]

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_33_img_76.png) {left=54.38 top=26.94 width=45.62 height=73.06}

<div style="position: absolute; left: 16.77%; top: 3.19%; width: 37.60%; height: 94.07%;">

The reaction in the **aprotic solvent **(no hydrogen bonds)** **proceeds fastest because the activation energy for this reaction is smallest due to the energy of the starting material has been raised. The energy of the transition state is not stabilized to the same extent as the starting material because the charge is spread over a number of atoms in the transition state and so it is not solvated to the same extent as the starting material, which has its negative charge localized on the one atom. This is an important point since, if the transition
state were stabilized by the same amount as the starting materials, then the reaction would proceed just as quickly in the different solvents since they would then have the same activation energy barriers.

</div>

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_33_img_77.png) {left=56.63 top=-0.00 width=43.37 height=23.17}

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_34_img_78.png) {left=49.31 top=20.35 width=50.69 height=76.69}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_34_img_79.png) {left=50.73 top=9.20 width=25.70 height=11.15}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_34_img_80.png) {left=70.14 top=0.00 width=24.64 height=9.31}

<div style="position: absolute; left: 18.63%; top: 17.05%; width: 29.33%; height: 79.98%;">

**Points to notice:**

• The thermodynamic product has a lower energy than the kinetic product
• The highest transition state to the right is higher than the highest to the left
• Initially the reaction will go to the left
• At low temperatures direct addition is favoured, but conjugate addition is favoured at high temperatures

</div>

<div style="position: absolute; left: 18.25%; top: 3.19%; width: 47.15%; height: 9.31%;">

**Kinetic vs thermodynamic control**

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_35_img_81.png) {left=34.15 top=25.12 width=65.85 height=74.88}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_35_img_82.png) {left=18.62 top=9.90 width=46.02 height=13.97}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_35_img_83.png) {left=53.98 top=5.83 width=38.13 height=13.97}

![](./lecture_05_reaction_coordinate_and_catalysis/images/slide_35_img_84.png) {left=0.00 top=63.59 width=34.51 height=36.41}

<div style="position: absolute; left: 16.40%; top: 25.12%; width: 14.85%; height: 38.47%;">

The E-alkene is formed faster and is known as the **kinetic **product; the Z-alkene is
more stable and is known as **the thermodynamic **product

</div>

</div>

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 27.39%; top: 36.48%; width: 55.28%; height: 16.51%;">

Kinetics of reaction mechanisms

</div>

</div>

