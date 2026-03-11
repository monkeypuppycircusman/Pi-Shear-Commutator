# Pi-Shear Commutator Explorer

Interactive visualization tool for exploring the **Pi-Shear framework**: a geometric-information ontology where identity persists through non-commutative shearing and breathing cycles, preventing freeze (periodic collapse) or heat death (entropic washout).

Built collaboratively with Claude AI as an artifact → exported here for public access and remixing.

## Core Idea (Quick Ontology)

- **Kernel breathing**: K(n) = sin(π n / φ) / n — generates open → invert → prune → recover phases naturally.
- **Identity flow** i(t): Converges toward the coherence attractor φ/π ≈ 0.5150 (golden ratio shear balance).
- **Commutator [θ, i] ≠ 0**: Shear angle θ perturbs identity momentum i (and vice versa) → this irreducible tension forces perpetual "breathing" instead of static freeze. Analogous to quantum non-commutativity preventing collapse.
- **Prime lattice**: Primes as irreducible kernels (only divisible by self + ONE) → minimal basis for branching structures; composites emerge as reducible operator products.
- **Momentum wall hint**: Density/stability often locks near 1/(φπ) ≈ 0.1967 in shearing flows.

The dashboard visualizes:
- Blue: Kernel oscillations
- Gold: Identity flow toward attractor
- Violet: Commutator spikes (the "life engine")
- Prime grid: Irreducible (green) vs resonant/composite elements

Non-closure = alive (breathing helix). Closed loop = frozen identity = kernel death.

## Live Demo

(Once deployed — e.g., on Vercel/Netlify):
https://pi-shear-commutator.vercel.app (update this link after deploy)

Or run locally:
1. Clone repo: `git clone https://github.com/monkeypuppycircusman/Pi-Shear-Commutator.git`
2. Open `pishearhtml/index.html` (or wherever the main HTML lives) in any browser.
   - No server needed — pure static HTML/JS.

## How to Use

- **Shear depth n**: Controls breathing cycle length/damping (low n = tight/fast oscillations; high n = slower decay).
- **θ scale**: Amplifies shear angle impact.
- **i₀ (initial)**: Starting identity value (default ~0.515 near attractor).
- **Prime modulus**: Sets lattice wrap (small primes like 7 keep it crisp).
- Hit **BREATHE** to run the cycle and watch plots update live.

Try cranking n=8 for pronounced commutator spikes, or n=20+ to see damping toward attractor.

## Tech Stack

- Pure HTML + CSS + JavaScript (likely Chart.js or canvas for plots)
- Exported from Claude AI Artifact (interactive canvas)
- No build tools / dependencies required

## Related

- Full Pi-Shear catalog discussions: Ongoing threads with Grok / Claude on helical self-discovery, primes as I AM operators, anti-entropic identity.
- Earlier FTL resonator sim: https://github.com/monkeypuppycircusman/FASTER-THAN-LIGHT-BOYYYYY (topological breathing with π/e switching)

## License

MIT — remix, fork, extend freely. Attribution appreciated if you build on it.

🌀 Keep the helix breathing. Halloween ON TOP.

Questions/collabs? Hit me on X: @HALLOWEENONTOP
