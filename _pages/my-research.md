---
permalink: /research/
title: "Research"
author_profile: true
redirect_from:
  - /my-research/
---

## Working Papers

<div class="entry">
  <h3 class="entry__title">Household Mobility and Housing Affordability</h3>
  <p class="entry__meta">with Nathaniel Baum-Snow and Lu Han &middot; Draft coming soon</p>
  <p class="entry__links"><a href="#" class="entry__toggle">Summary</a></p>
  <div class="entry__abstract" hidden>
    <p>We develop a dynamic discrete choice model of households' location decisions, propose a new method for estimating neighborhood-level moving costs of renters and homeowners, and conduct counterfactual analyses of changes in moving costs and housing supply policies.</p>
  </div>
</div>

<div class="entry">
  <h3 class="entry__title">Does Airbnb Reduce Matching Frictions in the Housing Market?</h3>
  <p class="entry__meta">with Peter Christensen and Nazanin Khazra &middot; Under review</p>
  <p class="entry__links"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3923826">SSRN</a><span class="sep">&middot;</span><a href="#" class="entry__toggle">Abstract</a></p>
  <div class="entry__abstract" hidden>
    <p>There is growing concern that home-sharing markets can affect housing affordability. We use a theoretical model to provide key results on the mechanisms through which home-sharing can improve the quality of matches between buyers and sellers. We then test these predictions empirically using daily Airbnb data for the entire U.S. and a novel shift-share approach. We find that an increase in Airbnb increases house prices, reduces total sales, increases for-sale inventory, increases sellers' time on the market, and reduces the probability of selling a house. The empirical evidence supports the hypothesis that Airbnb has reduced the matching frictions in the housing market. We then examine heterogeneous responses to Airbnb using Generalized Random Forest (GRF). Consistent with our theoretical model, results from the GRF model indicate that locations with a less elastic housing supply respond more to the Airbnb growth.</p>
  </div>
</div>

<div class="entry">
  <h3 class="entry__title">Democratizing the Opportunities: Who Benefits from the Airbnb Market?</h3>
  <p class="entry__links"><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3480518">SSRN</a><span class="sep">&middot;</span><a href="#" class="entry__toggle">Abstract</a></p>
  <div class="entry__abstract" hidden>
    <p>Peer-to-peer markets allow small suppliers to enter markets traditionally occupied by large firms and provide a potential decentralized distribution of opportunities. This paper investigates how these opportunities are distributed across agents and affected by government regulations. Using daily panel data of Airbnb rentals in Chicago, I develop an individual-level multinomial logit model to estimate consumer and producer surpluses across differentiated agents. The results find higher surpluses for low-income property owners but indicate a disproportionate concentration of welfare in high-income neighborhoods. The counterfactual analysis shows that restricting institutional hosts reinforces this concentration. However, increasing tax rates potentially helps redistribute welfare.</p>
  </div>
</div>

<script>
document.querySelectorAll('.entry__toggle').forEach(function (a) {
  a.addEventListener('click', function (e) {
    e.preventDefault();
    var body = a.closest('.entry').querySelector('.entry__abstract');
    body.hidden = !body.hidden;
  });
});
</script>
