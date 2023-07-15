
## Single qubit gates
$R^C(\theta, \phi) = exp(i\theta/2(e^{i\phi}\sigma_+ + e^{-i\phi}\sigma_-)) = Icos\theta/2 + i(\sigma_xcos\phi-\sigma_ysin\phi)sin\theta/2$

Often single-qubit operations are visualized by use of the so-called Bloch sphere. We identify the north pole of the Bloch
sphere with logical |0⟩ (the energetically higher state) and the south pole with |1⟩ (see Fig. 7). 

In the Bloch picture, the angle
$\phi$ specifies the axis of rotation in the equatorial plane and $\theta$ the rotation angle (pulse area), 

and thus **any linear combination
of $\sigma_x$ and $\sigma_y$ operations can be implemented with laser pulses**.

Rotations around the z axis can be decomposed into rotations around the x and the y axis. 

Alternatively, all following
rotations on that qubit can be shifted by $-\Delta \phi$ to achieve effectively a rotation about the z axis by $\Delta \phi$. 

Finally, a far detuned
laser beam can shift the relative energy $\Delta E$ of the eigenstates due to an AC-Stark effect by $\Delta E = \Omega^2/2\Delta$ (c.f. Eq. (8)). Thus,
after a time $t = \hbar \Delta\phi/\Delta E$ the desired phase shift is acquired.


In ion traps, single-qubit manipulations are routinely carried out with fidelities exceeding 0.99 (Knill et al., 2008).
Single-qubit-gate fidelities **are usually limited by laser intensity fluctuations** and in the case of single photon transitions
by the **finite temperature of the ion crystal** and in the case of Raman transitions also by **spontaneous emission** from the
intermediate level. In the Lamb–Dicke limit (i.e. the **extension of the ground-state wave function is much smaller than
the projection of wavelength of the light onto the motion**), the effective Rabi frequency Ωeff of the transition is given by
(Wineland et al., 1998)
$\begin{equation}\Omega_{eff} \approx \Omega\prod_{i}(1-n_i\eta_i^2) \end{equation}$

$i:$ motional modes; $n_i:$ vibrational quantum number $\eta_i:$ corresponding Lamb-Dicke factor.


## Two-qubit gates
test