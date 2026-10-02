# Ocean mixing δ18O explorer

Open `index.html` in a browser. The app is self-contained and does not require an internet connection or a build step.

The model treats ADW and EASW as the two input waters. NASW is calculated by evaporation followed by percentage mixing with a conceptual freshwater endmember (δ18O = −9.5‰ VSMOW, salinity = 0), NADW inherits NASW, PDW and IDW are adjustable mixtures of ADW and NADW, ASW inherits NASW before an optional freezing effect, and WIS mixes EASW with ASW before applying its own evaporation, percentage freshwater mixing, and fixed −1‰ non-ice-sheet δ18O offset. Chart x- and y-axis limits can be adjusted with paired sliders and numeric inputs.

Salinity responses are intentionally simple linked teaching assumptions rather than a calibrated oceanographic model. For freezing, the app uses ΔS = Δδ18O ÷ 0.1.
