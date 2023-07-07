## keypoints from slides
1. 2维电子气：2DEG GaAs --- AlxGa(1-x)As Si0.7Ge0.3 --- 28si
2. Donor spin qubit: 31P in Si, Bohr radius ~ 2.5nm
3. Occupation diagram: 
    + level splitting: inter-dot capacitance, 
    + tilted diagram: crosstalk
4. Initialization: low temperature, high $B_0$
5. Drive method:
    + ESR: pass current through wire
    + EDSR: voltage on a gate, use spin-orbit interaction easier local addressing, all-electrical control possible
6. Single-shot spin readout: 
    + Main limitations: detection bandwidth and spin relaxation

7. Hyperfine interaction with nuclear spins
    + Overhauser field $B_N \approx 5mT$ 
    





1. Spin qubits in GaAs benefit from remarkably long energy re-
laxation times T1, the time it takes a qubit to change from a
high-energy state to the ground state. For single-spin qubits, T1
can exceed **1 second** at low temperature (100 mK or lower) in
a 1T field. That’s three orders of magnitude longer than the
longest T1 in superconducting qubits.
2. By comparison, **T2\*** , the time it takes the qubit phase to ran-
domize, is just **tens of nanoseconds** in GaAs dots.The phase
of the electron’s spin is randomized through hyperfine coupling to the roughly 1 million nuclear spins of atoms in the quantum dot, with which the electron wavefunction overlaps.
The interaction is impossible to avoid because every Ga and As
isotope carries a nuclear spin of 3/2.
![](../images/2qubitlogicgate.png)
3. Moreover, despite the low temperatures and strong mag-
netic fields used with typical spin-qubit measurements, the nu-
clear spins point in nearly random orientations. The result is a
statistically fluctuating and slowly varying collective effect on
the electron spin known as the random nuclear or Overhauser
field. Although the randomness of the nuclear field can be sig-
nificantly reduced for singlet–triplet qubits by using sophisticated pulse schemes, the random nuclear field has signifi-
cantly slowed the progress of GaAs-based spin qubits
4.  In the
first, pioneered by one of us (Eriksson) and colleagues at the
University of Wisconsin–Madison, **electrons are confined in Si
quantum wells by silicon germanium barriers above and
below the well.** In the second, developed by Andrew Dzurak
and colleagues at the University of New South Wales (UNSW)
in Sydney, **electrons are confined against a Si-SiO2 interface—
as in n-doped metal oxide semiconductor technology.** In both
cases, gate electrodes on the surface are used to accumulate
electrons in quantum dots and to form tunnel barriers between
the dots.
5. The randomization time T 2* is significantly longer in Si than
in GaAs, with T 2* reaching 1 μs in natural Si and up to 100 μs
in purified 28 Si.
6. Furthermore,
given that the nuclear-spin bath evolves slowly on the time
scale of the electron-spin dynamics, it is possible to extend the
coherence times to tens of milliseconds9 using dynamic decou-
pling techniques, extensions of the Hahn spin-echo concept.
7. Even longer electron-spin coherence times are obtained for
electrons bound to phosphorus-31 dopants in 28 Si-enriched ma-
terial. The positively charged 31 P donor provides the confining
potential for the electron. The system is convenient because it
avoids the need for bandgap engineering, though actual de-
vices do contain gate electrodes to manipulate the confining
potential in time. The group of Andrea Morello at UNSW has
shown that individual 31P nuclear spins can provide a nuclear-
spin qubit with an exceedingly long T2* of 0.6 s.
8. 