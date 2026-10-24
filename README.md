# Shifted primes in arithmetic progressions to large moduli with linear sieve remainder weights

Ruiyi Zhang

For Iwaniec's upper and lower linear-sieve remainder weights `w_N^±(q)` (the complete coefficients,
keeping the smooth-divisor and prime-tuple factors), the manuscript proves a signed mean-value
estimate for primes `p` in `(N/(log N)^B, (1-eps)N)` in residue classes `a mod q`:

    sum_q w_N^±(q) { pi(q, a) - pi / phi(q) }  <<  N (log N)^(-A)

for every fixed `A > 0`, with sieve level `D = N^theta` and `z = N^u`, uniformly for the admissible
shifts `a` in `[N, N log N / 3]` (those coprime to every modulus in the support; `a = N` is one).

- Theorem 1.2: any fixed `0 < u <= 1/500` and `1/2 < theta < Theta(u) = (5 - 7/32 - 3u)/8`;
  the complete modulus support lies below `N^Theta(u)`.
- Theorem 1.1: the case `u = 1/500`, with `Theta = 19101/32000`.
- Corollary 1.3: the same estimate with the logarithmic-integral comparison term.

The proof combines the dispersion method with a Heath-Brown decomposition, estimating the
boundary, Type-I and Type-II terms separately, with Deshouillers-Iwaniec bounds for sums of
Kloosterman sums and the Kim-Sarnak exponent `7/64`. The implied constants are ineffective
(Siegel-Walfisz).

## Contents

- `main.pdf` (75 pages)
- `source/` - LaTeX source: `main.tex` and the chapter files it includes
- `SHA256SUMS`

## Build

    cd source
    pdflatex main.tex
    pdflatex main.tex
    pdflatex main.tex
