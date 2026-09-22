# Week 8 exercises

**[`power-analysis.ipynb`](power-analysis.ipynb)** — a worked example, already run with
its outputs saved (open it in VS Code or Jupyter to see the results without
re-running anything, or run it yourself cell by cell). It covers:

- Computing power analytically for a two-arm experiment (`statsmodels`)
- Solving backward for the sample size needed for 80% power
- Power curves across effect sizes
- Confirming the analytic result by simulation (run thousands of fake
  experiments, count how often you detect a real effect)

It ends with a **"Your turn"** section: a real exercise (unequal group
sizes/`ratio`) with a blank code cell for you to fill in — no solution
provided, see `PLAN.md`'s open question on where solutions should live.

Setup: `pip install -r requirements.txt` (repo root), then open the notebook
in VS Code with the Jupyter/Python extensions, or run `jupyter lab`.

An R equivalent (using `pwr`) would work just as well — not built out yet,
contributions welcome.

Not every week needs code — some are discussion/design-only (see notes.md).
