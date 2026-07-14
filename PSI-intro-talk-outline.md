# PSI intro talk: outline and narrative plan

**Audience:** incoming PSI master's students — solid physics core (QFT, some string theory exposure, GR), math background uneven. **Length:** 20 minutes ≈ 10 content slides. **Goal:** an honest, attractive account of your research with physics as the entry point; the pitch to work with you stays implicit.

**Anchor threads:** (A) Coulomb branches / 3d mirror symmetry, (B) planar limit of Chern-Simons / knot contact homology. These are a good pair: both instances of one meta-story ("physics predicts, math proves, and proving teaches you new math"), and the Coherent sheaves II paper literally bridges them, so the talk feels like one research program rather than two topics.

**The honesty strategy.** Don't open with a disclaimer slide ("I'm really a mathematician, sorry"). Instead, let the honesty *be* the thesis: your relationship to physics is that QFT is the best conjecture-generating machine mathematics has ever encountered, and your job is to turn its predictions into theorems — which usually requires inventing new mathematics, and sometimes pays the physics back. Said once, clearly, early (slide 2), this is both true and attractive. It also tells students exactly what a project with you looks like without ever saying so: they'd take a physical prediction and learn the math needed to attack a piece of it.

**Timing budget** (sums to 20):

| Segment | Slides | Minutes |
|---|---|---|
| Opening: who I am, the thesis | 1–2 | 3 |
| Thread A: 3d N=4, Higgs/Coulomb, mirror symmetry | 3–6 | 8 |
| Thread B: Chern-Simons at large N, knot contact homology | 7–9 | 7 |
| Close | 10 | 2 |

Rule of thumb you already know: at 2 min/slide, 10 slides is the ceiling. If you build overlays, count each `\only` step as half a slide.

---

## Slide 1 — Title + who I am (1.5 min)



## Slide 2 — The thesis (1.5 min)

One slide, mostly words, stating the relationship honestly:

- Physicists have a machine (path integrals, dualities, string theory) that outputs precise predictions about mathematical objects — predictions mathematics cannot currently derive on its own.
- Dualities especially act as **secret passages** between parts of mathematics with no visible connection (your NSERC framing — it's the best sentence you have; use it verbatim). Many predictions take the form: *two things mathematicians defined independently, for totally different reasons, are secretly the same.*
- My research: take such a prediction, build the mathematics needed to prove it. The proof is never a formality — it usually requires new structures, and those structures often say something back to the physics.

Land the honest caveat here, in one line, with confidence rather than apology: "I won't compute a cross-section for you. But if you want to know what your QFT is *doing* to mathematics, that's my department." This is the only meta-commentary in the talk; everything after is science.

## Slide 3 — Thread A opener: what a topological twist buys you (2 min)

Start from what they know or will learn in the QFT core: 3d N=4 supersymmetric gauge theory (gauge group G, matter representation N). You have this material polished in PI-2026.tex (the "QFT as a big generalization of an algebra" frames).

- Topologically twisted theory → local operators form a commutative algebra; in 3d the secondary product makes it Poisson.
- Physics packaging: this algebra is the ring of functions on the **moduli space of vacua**. Two twists → two spaces: the **Higgs branch** and the **Coulomb branch**.
- Keep the almost-commutative-algebra formalism *out*; that's for a math audience. One displayed statement suffices: twist ⇒ (Poisson algebra, canonical quantization).

Pitfall: PI-2026 spends ~4 frames on filtered algebras and quantization before reaching QFT. For PSI students, invert it — QFT first, algebra as the payoff.

## Slide 4 — Higgs easy, Coulomb hard (2 min)

The asymmetry is the hook of this whole thread:

- Higgs branch: classical, a hyperkähler quotient (Hitchin–Karlhede–Lindström–Roček, 1987). Mathematicians digested this decades ago.
- Coulomb branch: receives quantum corrections; classically it looks like one thing, the true answer is deformed by instantons/monopoles. For ~20 years physicists computed examples while there was *no mathematical definition of the space at all*.
- Braverman–Finkelberg–Nakajima (2016): a rigorous definition, via a convolution algebra in equivariant homology of a monopole moduli space. A genuinely new construction in math, forced into existence by physics — exactly the pattern of slide 2.

Give one example they can hold: G = U(1) with charged matter → Coulomb branch is an A-type singularity ℂ²/Γ; quiver gauge theories → slices in affine Grassmannians / Slodowy slices in type A. One example on the slide, not a zoo.

Optional framing line from the proposal, good for this audience: these branches include the nilcones of semisimple Lie algebras and behave like a **new class of "semisimple Lie algebras," vastly generalizing the Killing classification**. It tells math-curious students the stakes (a new classification-scale theory) in one sentence.

## Slide 5 — 3d mirror symmetry (2 min)

- Physics: pairs of theories T, T^! flowing to the same IR fixed point, with Higgs(T) = Coulomb(T^!) and vice versa (Intriligator–Seiberg 1996). To a physicist, a duality; to a mathematician, an outrageous list of conjectures pairing spaces that have no visible relationship.
- Proposal framing worth reusing: from this viewpoint 3d mirror symmetry **generalizes Langlands duality of semisimple Lie algebras** (and is physically a cousin of ordinary mirror symmetry and the Langlands program). One line, no elaboration — it signals the scale of the story to anyone who's heard either buzzword, and both buzzwords circulate at PI.
- Math shadow: **symplectic duality**. Your theorem (with Braden–Licata–Proudfoot): the categories O of a dual pair are Koszul dual. State it at headline level: "representation theory on one side determines representation theory on the other, in a precise derived sense." Don't define category O — say "a category of representations tailored to the geometry," and move on.
- This is also where you can honestly mark tempo: the math proof of statements a physicist considers obvious took ~200 pages, and the Koszul-duality revision is still on your desk in 2026. Physics is fast; theorems are slow; the theorems are what make the next round of physics predictions checkable.

## Slide 6 — Where this thread is now (2 min)

Compress recent work into one "current frontier" slide, three bullets max, each one sentence:

- **Functoriality** (with collaborators, 2026): gauging/ungauging on the physics side becomes a Hamiltonian-reduction operation *between Coulomb branches* — e.g. proving the BDGHZ conjecture that T*(parabolic base affine space) for SL_n is a Coulomb branch. Frame as: "physical operations on theories become functors on spaces."
- **Coherent sheaves / quantizations** (Coulomb branches II): explicit, quiver-style descriptions of categories of sheaves on resolved Coulomb branches — the categories of boundary conditions, in physics language.
- **The bridge:** these categories are exactly what's needed to make Aganagić's string-theoretic knot homology algebraic — "which brings me to knots." This sentence is the hinge of the talk; the segue should feel inevitable.

If you want one more frontier flavor here (only if pace allows — this slide is the first cut), the NSERC objectives offer physics-legible options: the Costello–Creutzig–Gaiotto proposal that the Coulomb branch is recovered from a **VOA built on the Higgs branch** (the only known Higgs→Coulomb passage not routed through the full QFT), or the quantum **Hikita conjecture** (twisted traces of a quantization of X ↔ quantum cohomology of X^!) tied to your sphere-trace paper with Gaiotto et al. Both name-drop well at PI; neither should get more than a sentence.

## Slide 7 — Thread B opener: Chern-Simons and knots (2 min)

Home turf for physicists:

- Witten (1989): expectation values of Wilson loops in Chern-Simons theory = knot invariants; SU(2) fundamental gives the Jones polynomial. Most will have heard this story; a one-picture reminder (knot + Wilson loop) is enough.
- Coloring by ⋀^m ℂ^N for all m, N packages into the two-variable **HOMFLYPT polynomial**. These invariants satisfy recursion relations in the coloring — the "deformed Â-polynomial."
- Physics question (’t Hooft): what happens at large N? Planar limit: N → ∞, q → 1, with g = q^N fixed. They will recognize the planar limit from large-N gauge theory; that recognition is the point of choosing this thread.

## Slide 8 — The prediction (2 min)

- Gopakumar–Vafa: large-N Chern-Simons on S³ is a topological string on the resolved conifold. Adding a knot adds a brane on the conormal Lagrangian.
- On the string side, the brane has its own invariant: **knot contact homology** and its augmentation variety — defined by symplectic geometers (Ekholm, Ng, …) by counting holomorphic curves, with no reference to Chern-Simons whatsoever.
- Aganagić–Vafa prediction: *the augmentation variety is the classical (planar) limit of the HOMFLYPT recursion relations.* Two objects, two communities, no known map between them — slide 2's pattern, verbatim. Say that out loud.

## Slide 9 — What we proved (3 min — the one technical beat of the talk)

From the Planar-limit paper (with your postdoc; idea credit to conversations with Gaiotto, which is worth saying — it's a concrete "this is what being at PI does" moment):

- Construction: the **HOMFLYPT difference module** — treat the coloring m as a *formal variable*, so the shift m ↦ m−1 becomes an operator λ, with μ = q^m; λμ = qμλ generate a quantum torus acting on a module built from skein theory.
- Show the one honest calculation of the talk: the unknot MOY relation (the displayed equation from the paper's intro — circle labeled m = coefficient × circle labeled m−1), leading in three visible steps to the deformed Â-polynomial of the unknot. It's genuinely followable in ninety seconds and gives students the feeling "I could compute in this world."
- Theorem: at q = 1 the difference module *is* degree-0 abelianized knot contact homology. This doesn't fully prove Aganagić–Vafa but reduces it to sharply stated algebra conjectures (injectivity of the evaluation map). Be precise about this — the honesty reads as strength, and "here is exactly what remains" is the implicit project pitch at its best.
- One sentence on method: purely algebraic, diagram calculus, no holomorphic curves and no path integrals — elementary tools, non-elementary conclusion.

## Slide 10 — Close (2 min)

Return to slide 2 and make the two threads rhyme explicitly:

- Same shape both times: physics predicted an equality between independently defined mathematical objects (Higgs ↔ Coulomb; recursions ↔ augmentation varieties); proving it required inventing structures (BFN construction, symplectic duality; difference modules) that now have lives of their own.
- The mathematics needed is learnable: the planar-limit proof runs on diagrammatic calculus a strong master's student can pick up in weeks, not years. Say this plainly — it is true and it is the most reassuring thing a math-shy physicist can hear.
- If you want a concrete "open frontier" beat before the last line, the knot-homology thread supplies one that stays on-theme: Aganagić also predicts homologies for the superalgebras **gl(m|n)** — N=2 rather than N=4 physics, matrix factorizations rather than coherent sheaves — with *no mathematical construction yet*. One sentence: "and the machine keeps producing predictions faster than we can prove them; here's one nobody has touched." That's the most honest advertisement in the talk.
- Last line, not "join my group" but something like: "There is a lot more where this came from — physics is decades ahead of the proofs, and catching up is a full-time job with room for help." Implicit pitch delivered; stop talking.

---

## Production notes

- **Reusable material:** PI-2026.tex (Berkeley-April-2026 repo) has the QFT-twist frames, the Higgs/Coulomb definitions, mirror-symmetry frames, and the Talking Heads image — slides 3–5 are largely an abridgement of it. Slide 9's calculation is the displayed unknot equation in the intro of Planar-limit/main.tex (tikz code ready to lift). The NSERC proposal's "Recent Progress" section is the source for the secret-passages, Killing-classification, and Langlands lines, and its objectives (VOA/Hikita/2-categories, gl(m|n)) stock the frontier mentions.
- **What the proposal contributes that stays out:** the modular representation theory / RoCK blocks thread (2B), Gelfand-Tsetlin modules, and quantum symmetric pairs. All real, none physics-legible in 20 minutes; they can live in conversations afterward.
- **What to cut if running long:** slide 6 compresses to one sentence appended to slide 5 ("this is now a functorial, categorical story — and those categories connect to knots"). Threads A and B survive independently; the close doesn't.
- **What not to add:** KLRW/categorification thread, category O internals, the BFN convolution definition, anything with the word "Koszul" beyond one appearance. Each is a 20-minute talk by itself.
- **Whiteboard/questions prep:** likely student questions are "what math do I need to know?" (answer: linear algebra done fearlessly + willingness to learn diagram calculus; geometry can be absorbed on the way) and "is this string theory?" (answer for thread B: it proves consequences of string dualities without assuming them).
