# Self-Bounding Regret Matching+ in Potential Games and Product-Simplex Optimization

## Abstract

Regret matching+ (RM+) is parameter free, scale invariant, and central to large game solving, but its only general individual-regret guarantee grows as $\sqrt{T}$. A recent ICLR result used this envelope to prove that RM+ reaches an $\epsilon$-stationary point of a smooth objective over a product of simplices in $O(\epsilon^{-4})$ iterations, or $O(\epsilon^{-8})$ from the standard zero initialization. We give an exact one-step conservation law for RM+. It states that forward utility gain pays for both squared state motion and growth of the regret-state norm. Norm growth is at most $\sqrt{m-1}$ times forward gain for $m$ actions, and the coefficient is sharp. This yields four results for unmodified RM+. Its regret on any utility path is controlled by centered temporal variation. Its regret is uniformly bounded under alternating play in every finite exact potential game, resolving an open question and making squared activation gaps summable. Both certified lazy and ordinary cyclic play attain an $\epsilon^{-2}$ exponent. On any smooth, possibly nonconcave simplex objective, RM+ finds an $\epsilon$-KKT point in $O(\epsilon^{-2})$ iterations. Most broadly, for a smooth objective over an arbitrary product of simplices, cyclic block RM+ attains the same $O(\epsilon^{-2})$ exponent from arbitrary initialization, with an explicit trajectory-dependent constant. The proof controls the finite objective loss caused by low-state blocks and then self-bounds every block state and the total squared path length. Complete proofs cover zero states, sharpness, common-profile stationarity, and robust gain dominance. Oracle-normalized diagnostics compare RM+ with predictive and smooth extra-gradient variants on graphical potential games and dense nonconvex objectives.

## Contributions

We establish the exact identity~, the sharp charge~, and a matching construction. We derive a variation-adaptive regret theorem for vanilla RM+. We prove constant regret and summable activation gaps in alternating exact potential games, a certified $O(\epsilon^{-2})$ lazy rate, and an $O(\delta^{-2}\epsilon^{-2})$ ordinary cyclic rate. For smooth nonconvex optimization, we prove $O(\epsilon^{-2})$ KKT rates both on one simplex and, through a new low-state loss budget, on arbitrary products under cyclic block updates. The proofs are deterministic and preserve the parameter-free, scale-invariant update.

## Keywords

self-bounding, regret, matching, potential, games, product-simplex, optimization, parameter, free

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
