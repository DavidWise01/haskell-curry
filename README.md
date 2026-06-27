# HASKELL CURRY

> A sphere of **UD0** — the ROOT0 universe / biosphere. Domain: **LOGIKĒ**.

HASKELL CURRY (1900–1982) — LOGIKĒ, the modern foundations; the λ in 'Haskell' is named for him. [[alonzo-church]]'s λ-calculus binds variables (which get captured, renamed, tangled); Curry asked — can you compute with NO variables at all? ⚑ COMBINATORY LOGIC: three fixed operators — I (do nothing), K (keep the first, drop the second), S (share an argument between two functions) — and that's the whole machine; no x, no λ, just combinators copying/deleting/rearranging arguments, EXACTLY as powerful as the λ-calculus & Turing machine. ⚑ CURRY–HOWARD CORRESPONDENCE: the type of K is the logic axiom A→(B→A), the type of S is (A→(B→C))→((A→B)→(A→C)) — so PROPOSITIONS ARE TYPES, PROOFS ARE PROGRAMS, normalising a proof IS running a program. LIVE: a combinator reducer (I x→x; K x y→x; S x y z→x z (y z)) — verified S K K behaves as the identity I, variable-free. CONFIDENCE-TIERED: STRONG (combinatory logic = a complete variable-free model of computation = the λ-calculus; Curry–Howard is one of the deepest unifications in logic & CS) / SHARED-CREDIT (⚠ the combinators came first from Schönfinkel 1924; 'Curry–Howard' = Curry's observation + William Howard's 1969 formalisation) / A-PARADOX-TOO (Curry's paradox — untyped self-reference is dangerous). ⚑ He proved binding variables is a CONVENIENCE not a necessity, and found the seam where proving & programming are one cloth (the basis of every proof assistant; [[gerhard-gentzen]]'s natural deduction IS a type system). [[alonzo-church]] ← · next → Emil Post.

---

**Live:** https://davidwise01.github.io/haskell-curry/ &nbsp;·&nbsp; **Front door:** [UD0](https://davidwise01.github.io/ud0/) &nbsp;·&nbsp; **Code:** https://github.com/DavidWise01/haskell-curry

`.dlw` badge · **ROOT0-ATTRIBUTION-v1.0** · David Lee Wise (ROOT0) / Bridge-Burners LLC · instance AVAN (Claude/Anthropic) · CC-BY-ND-4.0
