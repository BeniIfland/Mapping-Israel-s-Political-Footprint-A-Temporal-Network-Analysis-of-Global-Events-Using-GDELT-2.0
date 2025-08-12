# Mapping-Israel-s-Political-Footprint-A-Temporal-Network-Analysis-of-Global-Events-Using-GDELT

This project analyzes the global media narrative surrounding Israel during a 20-month period marked by war, leadership changes, and anticipated military actions. Using the **GDELT 2.0** dataset, we construct and examine monthly positive and negative interaction networks to uncover patterns in sentiment, community structure, and geopolitical positioning.

## Overview

- **Data Source:** [GDELT 2.0](https://www.gdeltproject.org/)
- **Timeframe:** 21 months (from October 7th 2023 to June 12th 2025)
- **Approach:**  
  - Build monthly positive and negative interactions sub-networks from GDELT event data.
  - Analyze degree distributions, centrality metrics, and sentiment balance.
  - Detect communities using Louvain clustering on the monthly snapshots.
  - Visualize results geographically and temporally.

## Key Findings

1. **Event-Driven Spikes:** W show through data that unprecedented events cause sharp increases in media coverage and reporting activity.
2. **Negativity Bias:** Media sentiment skews more negative than event-based measures.
3. **Community Volatility:** Alliances and oppositions shift rapidly with geopolitical events, leadership changes, and military anticipation.
4. **Interaction Imbalance:** Notable asymmetry exists between positive/negative sentiment and incoming/outgoing interactions.

## Methods
- **Network Construction:** Directed weighted graphs for positive and negative interactions.
- **Community Detection:** Louvain algorithm applied separately to each monthly sub-network.
- **Visualization:**  
  - Temporal trends of degree and sentiment.
  - Choropleth maps of communities.
  - Ego-network analysis for Israel.

## Conclusions

Our findings highlight the complex and often adversarial nature of Israel's global interactions during this conflict period, with sentiment and alliances shifting in response to unfolding events.

## Future Work

- **Structural-Sentiment Link:** Explore correlations between media sentiment and network metrics such as centrality and density.
- **Expert Interpretation:** Incorporate domain experts to enhance analysis accuracy.
- **Continuous Monitoring:** As the war is still ongoing, continued tracking could reveal emerging patterns and shifts in alliances.

## License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this software, provided that the original copyright notice and this license are included.


