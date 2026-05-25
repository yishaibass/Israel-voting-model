# Israel-voting-model
Interactive scenario explorer for Israeli Knesset elections — demographic voting model built on ecological inference across ballot-box data from five elections (2019–2022).

An ecological inference model of Israeli Knesset election dynamics, estimating voting behaviour by demographic group across five elections (2019–2022).
→ Open the interactive dashboard
What it shows
For six demographic groups (Haredi, Dati Leumi, Masorti, Hiloni, Arab, Druze), the model estimates the probability of voting for the current governing coalition and the group's turnout rate — derived from ballot-box level data across ~1,150 Israeli localities.
The dashboard lets you adjust key assumptions (Arab turnout, Hiloni direction, Dati direction, Haredi turnout, threshold effects) and see the implied Knesset seat distribution update live.
Data sources

Central Elections Committee ballot-box results, K21–K25 (2019–2022)
CBS 2022 Census demographic composition by statistical area

Methodology
Constrained weighted least-squares ecological inference. Full methodology, code, and data documentation will be added to this repository.
Limitations
Group-level probability estimates — the ecological fallacy applies. Seat projection is indicative. See the "How it works" tab in the dashboard for details.
