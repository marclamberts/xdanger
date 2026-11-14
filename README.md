# xDanger

A short, visual explanation of **xDanger**: one ecosystem for shot models, possession value and ratings, built on IMPECT event data.

Live page: https://marclamberts.github.io/xdanger/

- Nine probability models in five families (shot, possession, conceding, pass, rating), each answering one yes/no question about the next moments of a match.
- Possession and conceding labels are built from out-of-fold xG; team and attack totals use attack-level counting, 1 − ∏(1 − p).
- Trained on 71 IMPECT league-seasons, tested on held-out 2026–27 matches. Examples: Bundesliga 2026–27.

Full write-up: https://medium.com/p/a00f51663a1d · Papers: [`papers/`](papers/)

Models, charts and text: Marc Lamberts, Waltzing Analytics. Data: IMPECT. This repository contains the explainer page only, no data or model files.
