NCAA Women's Basketball — Pink Totals & Spreads Predictor

Deploy this directory as the root of a GitHub repository connected to Netlify.
The required paths are index.html, netlify.toml, and netlify/functions/basketball.mjs.
The serverless endpoint is /api/basketball?mode=games&date=YYYY-MM-DD.

Uses ESPN women's college basketball scoreboard data. No DraftKings, odds API or API key.
Schedule rank badges come from ESPN and are not guaranteed to match the AP Top 25.
Historical results are requested for the 25 days before the selected date; early-season
teams may have fewer than four completed games. ESPN API availability is not guaranteed.

Women's model: defensive blend, optional margin cap to limit blowout impact, editable
recency weighting, manual home-court adjustment, and four-game variability indicator.
The margin cap is a heuristic, not opponent-strength adjustment; pace/possessions,
injury, and efficiency stats are not available. Not validated for predictive accuracy.

Use a separate Netlify site/repository from the men's app to keep both available.
