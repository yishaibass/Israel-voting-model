# Israel voting model

[Open the simulator](https://yishaibass.github.io/Israel-voting-model/).

The site publishes the maintained six-group ecological model. One constrained turnout/coalition model design is used for K21–K26; each election has its own estimates. The default stays the K21–K25 (2019–2022) average. The last tab compares 2026 estimates with the past five-election average, using whole percentages and one-decimal SD changes. Eligible-voter shares are a 2026 projection from the K25/2022 Census base; their percentage-point changes use that base. Add `#2026` to the URL to open the table directly. Detailed diagnostics remain in the model analysis outputs.

The June 2026 static publication retained earlier turnout estimates during a demographic upgrade. This export synchronizes the site to the maintained model; the historical version revision is distinct from changes in 2026 voting estimates. The previous publication remains in Git history.

The [maintained source and methodology](https://github.com/yishaibass/Israel-demographic-dashboards/tree/main/products/coalition_simulator) own this model. Generate the English page using `scripts/build_html.py` in the configured voting project and copy `outputs/dashboard/index_v3.html` to this repository's `index.html`.

The November 3, 2026 count snapshot comes from a normalized secondary CEC mirror; direct primary retrieval and legal certification have not been independently verified. Individual ballots are unobserved. Group estimates carry 2022 locality composition forward; historical SD is descriptive variation, not statistical significance. Seat outputs remain scenarios. Raw ballots and Census microdata are excluded. Final model runs and checks used Python 3.15.2.
