:::titlepage
[[title]]
ATOM
[[subcaption]]
Building Block of the Chemicals
:::

---
# Hydrogen Atom Model

:::matrix{cols=50/50}
[[0,0]] 
**Time-dependent Schrödinger Equation**
$$
i \hbar\frac{d}{dt}|\Psi(t)\rangle = \hat{H}|\Psi(t)\rangle
$$
**The principal quantum number, $n$**
Different values for $n$ divide orbitals into groups of similar energies called shells. Numerical values for $n$ are used in ordinary speech.
![](./lecture_01_this_quantum_world/images/slide_27_img_24.png){width=78}
[[0,1]] 
![](./lecture_01_this_quantum_world/images/slide_26_img_21.png){width=75}
![](./lecture_01_this_quantum_world/images/slide_26_img_23.png){width=85}
:::

---
# Spectra are manifestation of $n$ in real life

:::matrix{cols=50/50}
[[0,0]] ![](./lecture_01_this_quantum_world/images/slide_28_img_26.png)
[[1,0]] ![](./lecture_01_this_quantum_world/images/slide_28_img_27.png)
[[0:2,1]] ![](./lecture_01_this_quantum_world/images/slide_28_img_25.png)
:::

---
# Other Quantum Numbers

The **orbital angular momentum** quantum number, $l$, dictates an orbital's shape and the angular momentum of an electron within it. The available values for $l$ are **restricted** by the **principal quantum number** $n$, ranging from $0$ up to $n - 1$. These values correspond to specific orbital designations: s, p, d, and f.

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| Value of $n$ | 1 | 2 | 3 | 4 |
| Possible values of $l$ | 0 | 0, 1 | 0, 1, 2 | 0, 1, 2, 3 |
| Name | 1s | 2s, 2p | 3s, 3p, 3d | 4s, 4p, 4d, 4f |

The **magnetic quantum number**, $m_l$, defines the spatial orientation of that angular momentum. The **permitted values** are dictated by $l$ and include all integers from $-l$ to $+l$. Distinct values of $m_l$ are typically represented by adding subscripts to the orbital letters.

| | | | |
| --- | --- | --- | --- |
| Value of $n$ | 1 | 2 | 2 |
| Value of $l$ | 0 | 0 | 1 |
| Name | 1s | 2s | 2p |
| Possible values of $m_l$ | 0 | 0 | $+1, 0, -1$ |
| Name | 1s | 2s | $2p_x, 2p_y, 2p_z$ |

> **Note:** Organic chemistry primarily focuses on **s** and **p** orbitals.

---
# Atomic Orbitals

:::matrix{cols=50/50}
[[0,0]]
<iframe src="./lecture_01_this_quantum_world/demos/orbitals.html" width="100%" height="430px" style="border:1px solid #ccc; border-radius: 8px;"></iframe>
![](./lecture_01_this_quantum_world/images/slide_30_img_31.png)
[[0,1]]
![](./lecture_01_this_quantum_world/images/slide_30_img_30.png)
![](./lecture_01_this_quantum_world/images/slide_30_img_32.png)
:::

---
# How Orbitals Are Filled Up

## Aufbau principle / Madelung rule
The lowest-energy orbitals fill up first, according to the order 1s -> 2s -> 2p ->
3s -> 3p -> 4s -> 3d. Note that the 4s orbital lies between the 3p and 3d orbitals in energy. 
> **Note:** energy grows with $n+l$ and with $n$ if $n+l$ are equal, e.g. $3s = 3+0=3$ and $2p=2+1=3$, but 2p is lower because $2<3$

## Pauli exclusion principle
Only two electrons can occupy an orbital, and they must be of opposite spin.

## Hund’s rule
If two or more empty orbitals of equal energy are available, one electron occu-
pies each with spins parallel until all orbitals are half-full

![](./lecture_01_this_quantum_world/images/slide_31_img_33.png){width=80}

---
# Examples

:::matrix{cols=50/50}
[[0,0]]
![](./lecture_01_this_quantum_world/images/slide_32_img_34.png){width=90}
[[1,0]]{text-align: center;}
**Hydrogen (1)**
[[2,0]]
![](./lecture_01_this_quantum_world/images/slide_32_img_35.png){width=60}
[[3,0]]{text-align: center;}
**Boron (5)**
[[0,1]]
![](./lecture_01_this_quantum_world/images/slide_32_img_36.png){width=55}
[[1,1]]{text-align: center;}
**Nitrogen (7) and Oxygen (8)**
[[2,1]]
![](./lecture_01_this_quantum_world/images/slide_32_img_37.png){width=50}
[[3,1]]{text-align: center;}
**Carbon (6)**
:::

---

<div style="position: relative; width: 100%; aspect-ratio: 16 / 9; margin: 0 auto;">

<div style="position: absolute; left: 21.30%; top: 4.70%; width: 62.78%; height: 85.81%;">

<iframe src="./lecture_01_this_quantum_world/demos/periodic_table.html" width="100%" height="550px" style="border:1px solid #ccc; border-radius: 8px;"></iframe>


**Valence electrons** are electrons in the outermost shell of an atom, and that can participate in the formation of a chemical bond if the outermost shell is not closed.

</div>

</div>

