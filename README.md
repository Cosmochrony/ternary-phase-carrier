# TPC — Ternary Phase Carrier: Colour Confinement, Generation Splitting, and Koide Dispersion

J. Beau, Independent Researcher, France

## Status

Working paper, v1.2. Concept DOI: [10.5281/zenodo.21115977](https://doi.org/10.5281/zenodo.21115977)

Speculative bridge (reconnaissance): it proposes a unifying carrier hypothesis; it is **not** a derivation and
does not fix the Standard-Model quantum numbers or the masses.

## Abstract

One complex three-phase carrier

$$ z_g = S + A\,e^{i(\delta + 2\pi g/3)}, \qquad g = 0,1,2 $$

read two ways relates three otherwise separate facts. Its pure-phase part sums to zero
($1 + \omega + \omega^2 = 0$), a colour-neutral class identified with the confined colour triplet; its real part
$S + A\cos(\delta + 2\pi g/3)$ is the square-root mass profile of the unit-dispersion note (KUD). The singlet
amplitude $S$ is the master dial:

- $S = 0$: pure-phase, sum-zero regime (colour, confined);
- $S \neq 0$: real-offset regime (positive masses);
- $A = \sqrt2\,S$: singlet–doublet equipartition (Koide, $\mathrm{CV} = 1$, angle $45^\circ$);
- $\delta$ near a node: the hierarchy (light electron).

## Content

A candidate admissibility filter is proposed — a discrete capacity balance
$\lVert r_{\mathrm{dbl}}\rVert \le \lVert r_{\mathrm{sing}}\rVert$ saturated at $\mathrm{CV} = 1$ — distinct from
positivity (which gives the wrong boundary $\mathrm{CV} \le 1/\sqrt2$ for the continuous envelope). The note lists
a construction charge sheet any realisation must discharge (exact colour singlet, three discernible generations
after neutralisation, electroweak quantum numbers, anomaly cancellation, quark/lepton selection rule). The
colour-to-generation breaking it would require along the neutralisation route is the one already closed in the
corpus by the exact colour degeneracy and the forgetful colour projection.

## Position in the programme

Fermionic matter sub-programme. It combines the confined colour triplet of the non-injective colour projection
(ENI, O31/O32) with the square-root mass profile of the unit-dispersion note (KUD), proposing them as two
regimes of one three-phase carrier. Kept separate from the clean unit-dispersion result because it is broader
and speculative.

## Build

```bash
cd tex
pdflatex -output-directory=../out TernaryPhaseCarrier.tex
cd ../out && bibtex TernaryPhaseCarrier && cd ../tex
pdflatex -output-directory=../out TernaryPhaseCarrier.tex
pdflatex -output-directory=../out TernaryPhaseCarrier.tex
```
