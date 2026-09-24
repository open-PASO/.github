<p align="center">
  <a href="https://github.com/open-PASO/openPASO">
    <img src="https://raw.githubusercontent.com/open-PASO/openPASO/main/logo/openPASO_koralle_dunkel.gif" alt="openPASO" width="220">
  </a>
</p>

<h2 align="center">open Platform for Agentic Simulation and Optimization</h2>

<p align="center">
  <a href="https://open-paso.github.io/openPASO/">Documentation</a> ·
  <a href="https://github.com/open-PASO/openPASO">Code</a> ·
  <a href="https://doi.org/10.5281/zenodo.20543501">Cite</a> ·
  <a href="https://github.com/open-PASO/openPASO/blob/main/CONTRIBUTING.md">Contribute</a>
</p>

**openPASO** connects an AI model to real simulation codes. It is an MCP server: your AI app
(Claude Code, Claude Desktop, Cursor, or your own agent) asks it to prepare, run, couple and
verify finite-element and multiphysics simulations, and it does so with the actual solvers —
**4C, deal.II, DUNE, FEBio, FEniCSx, Kratos, NGSolve, scikit-fem and SPARTA** — with curated,
measured knowledge about each code, verification of every result against something the run
never saw, and coupling across codes.

- **Operate**: one model, nine solvers, one interface.
- **Verify**: a result counts only when a check the solver did not write agrees with it.
- **Couple**: partitioned coupling between different codes, judged on convergence, not on completion.
- **Develop**: the same tools reach into the solvers' sources when a capability is missing.

Developed at the Institute of Materials Mechanics, Helmholtz-Zentrum Hereon, and open to
contributions: knowledge you verified, a solver you use, a check that caught something.
MIT licence.
