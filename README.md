# Network Parameters &mdash; S, Z and Y

Deck 01 of the [Matrix Methods in Engineering](https://github.com/BrendanJamesLynskey/Mathematics#linear-algebra) pair.

**Live presentation:** https://brendanjameslynskey.github.io/Matrix_Methods_Network_Parameters/

One linear operator, three coordinate systems. Drive an $N$-port with currents and
read voltages and you have $\mathbf{Z}$; drive with voltages and read currents and
you have $\mathbf{Y}$; work with the travelling waves a transmission line carries and
you have $\mathbf{S}$. The deck follows the matrix structure that decides whether a
measured network is reciprocal, passive, lossless &mdash; and safe to hand to a
time-domain simulator.

## What's inside

- One network, three descriptions &mdash; $\mathbf{Z}$, $\mathbf{Y}$, $\mathbf{S}$ and what each one measures
- $\mathbf{Z}$ and $\mathbf{Y}$ on the bench; reciprocity as transpose symmetry
- Passivity as positive semidefiniteness of the Hermitian part
- Why travelling waves are the natural variables &mdash; the transmission-line argument, not the "opens are hard" one
- What an S-parameter actually is: $S_{ij} = b_i/a_j$, with $S_{21}$ and $S_{11}$ spelled out
- What a scattering measurement *cannot* tell you &mdash; dissipated versus radiated loss
- Lossless is unitary, passive is a contraction
- **Interactive:** two-port scattering explorer &mdash; even and odd eigenmodes of a series resistor
- Why one frequency and a full sweep are the same idea, not two
- Frequency response and impulse response &mdash; the pair that really is two views
- **Interactive:** pole&ndash;zero explorer with live $s$-plane, magnitude and ringing
- Causality and the Kramers&ndash;Kronig relations
- Passivity enforcement and the Hamiltonian all-frequency test
- Conversions between $\mathbf{Z}$, $\mathbf{Y}$ and $\mathbf{S}$; the Smith chart as a M&ouml;bius map
- **Interactive:** the bilinear map $\Gamma = (z-1)/(z+1)$ with VSWR and return loss
- Applications in RF and high-speed digital, plus a checklist for lab data

## Long-form companion

The same material as a written report:
[Matrix_Methods_Network_Parameters.pdf](Matrix_Methods_Network_Parameters.pdf) (14 pp).

## Companion deck

[Matrix Concepts in Digital Filter Design](https://github.com/BrendanJamesLynskey/Matrix_Concepts_Digital_Filters)
&mdash; the same three matrix structures in discrete time.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
