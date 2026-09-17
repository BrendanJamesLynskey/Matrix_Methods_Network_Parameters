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

## Companion decks

[Matrix Concepts in Digital Filter Design](https://github.com/BrendanJamesLynskey/Matrix_Concepts_Digital_Filters)
&mdash; the same three matrix structures in discrete time.

[Equalisation in High-Speed Serial Links](https://github.com/BrendanJamesLynskey/SerDes_Equalisation)
&mdash; where this algebra is put to work on one real 28 GBd backplane channel.

## Where this is used

The S-, Z- and Y-parameter machinery here underpins the eleven-deck
[Signal Integrity &amp; High-Speed Digital Design](https://github.com/BrendanJamesLynskey/Signal_Integrity) series, in which every channel is
built as a cascade of the two-ports defined in this deck. Deck 10 of that series applies
the passivity, reciprocity and causality conditions set out here as practical quality
checks on measured data, and deck 05 uses the mixed-mode decomposition to compute how
intra-pair skew converts differential signal into common mode.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
