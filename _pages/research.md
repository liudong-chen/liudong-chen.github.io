---
layout: splash
title: "Research"
permalink: /research/
author_profile: false
---

{% include base_path %}

<h1 class="highlight-title"><span class="highlight-num">Highlight 1</span>Data Center and Power Grid Integration</h1>

<div class="research-item research-item--text">
  <div>
    <h3>Speed to power: off-grid, hybrid, and grid-connected supply for data centers</h3>
    <p>Rapid growth in artificial intelligence is outpacing grid expansion. Interconnection queues for large loads now stretch for years, prompting data center developers to consider building their own off-grid generation as a faster path to power. Yet an islanded data center cannot share reserves or benefit from demand diversity across the grid, which changes how reliability must be provided. We are developing an integrated economic and reliability framework that compares grid-connected, off-grid, and hybrid data center supply under a common reliability requirement, accounting for capacity investment, operation, and the value of earlier access to electricity. The framework examines the infrastructure, economic, and environmental consequences of speed to power for both data center owners and the wider power system, across different market structures. [Working paper]</p>
  </div>
</div>

<h1 class="highlight-title"><span class="highlight-num">Highlight 2</span>Rationalize Decision Behavior under Uncertainty</h1>

<div class="research-item">
  <div class="research-item__figure"><img src="/assets/Prudent_figure.png" alt="Prudent demand response"></div>
  <div>
    <h3>Prudent demand to explain the first principles of risk-averse decision-making</h3>
    <p>We show that risk-aware behaviors in demand response originate from non-quadratic discomfort state cost functions and price uncertainty with skewed distributions. We proposed a novel demand response formulation that combines non-anticipatory multi-stage decision making with non-quadratic cost functions, and showed prudence (the positive third-order derivative of the cost function) is the first principle that causes risk-averse decision behavior despite the formulation having a risk-neutral objective. We further proved that, given a non-quadratic cost function, the change in decision action level due to prudence scales proportionally with the skewness of the price distribution. [<a href="https://arxiv.org/abs/2405.16356">Link</a>]</p>
  </div>
</div>

<div class="research-item">
  <div class="research-item__figure"><img src="/assets/Social_attributes_figure.png" alt="Heterogeneity and uncertainty in consumer decision-making"></div>
  <div>
    <h3>Heterogeneity and uncertainty impact on energy consumers' decision-making</h3>
    <p>Heterogeneity interacts with uncertainty, shaping consumer behavior away from representative rational optimization. We first quantified the predictability of renewable generation patterns in China [<a href="https://www.nature.com/articles/s41467-023-40670-7">Link</a>], revealing the inherent uncertainty faced by renewable consumers. Building on this, we draw on prospect theory from economics, where decision makers tend to be aggressive under losses and conservative under gains, to model boundedly rational consumers' behavior under incentive mechanisms. We show that such rationality redistributes consumers' demand patterns in response to incentives [<a href="../assets/Social_Attributes.pdf">Link</a>]. To capture heterogeneous individual responses more precisely, we integrated social survey data with load metering records and applied a spatio-temporal neural network to learn response behavior and embed it to design behavior-aware pricing mechanisms [<a href="../assets/Data-Driven_Stochastic_Game.pdf">Link</a>].</p>
  </div>
</div>

<h1 class="highlight-title"><span class="highlight-num">Highlight 3</span>Interpret Interactive Behavior under Emerging Mechanisms</h1>

<div class="research-item">
  <div class="research-item__figure"><img src="/assets/agent_number.jpg" alt="Coincident peak shaving game"></div>
  <div>
    <h3>Theoretical game framework for coincident peak demand charge</h3>
    <p>Coincident peak (CP) demand charges customers based on their individual demand at the system's overall peak time. We proposed a novel game-based framework to analyze the CP shaving problem, developing a theoretical model to examine the impact of strategic customer behavior on system efficiency. The game structure exhibits different characteristics depending on the extent to which customers can shift their demand. We derived analytical Nash equilibrium solutions and analyzed the efficiency loss by comparing it to a standardized centralized peak-sharing model. [<a href="https://arxiv.org/abs/2501.02792">Link</a>]</p>
  </div>
</div>

<div class="research-item research-item--text">
  <div>
    <h3>Limitations of proxy bus models in interregional market coordination</h3>
    <p>Interface scheduling between regional electricity markets is coordinated through coordinated transaction scheduling (CTS), which relies on a simplified proxy-bus model. Working with ISO New England, we analyzed the effectiveness of this model from a foundational market economics perspective and showed that no proxy-bus construction can guarantee that market clearing always moves power from lower-cost to higher-cost regions to reduce the regional price spread. The proxy-bus construct can therefore inherently lead to efficiency losses. We discuss improvements such as financial interregional transmission products, or incorporating boundary network information with node-to-node bidding. [<a href="../assets/Proxy_Bus_CTS.pdf">Link</a>]</p>
  </div>
</div>

<div class="research-item research-item--text">
  <div>
    <h3>Interdependence between network structure and strategic consumers</h3>
    <p>In practice, industrial consumers often have multiple network access points. We show that jointly optimizing access point selection and consumption adjustment can reduce energy transactions between the grid and consumers, thereby mitigating the operational impact on the grid [<a href="../assets/Multiple_Sharing_Region.pdf">Link</a>]. Building on this, I developed a methodology that incentivizes consumers to adjust demand patterns while enabling the system operator to adaptively reconfigure the network through switch-position adjustments, improving operational efficiency [<a href="../assets/Dynamic_network_structures.pdf">Link</a>]. Extending this line of research, I designed a voltage regulation approach in which autonomous consumers with solar panels are incentivized to provide voltage support, making use of existing infrastructure to support stable system operation [<a href="../assets/Voltage_Regulation.pdf">Link</a>].</p>
  </div>
</div>

<h1 class="highlight-title"><span class="highlight-num">Highlight 4</span>Sustainable Energy Solutions</h1>

<div class="research-item">
  <div class="research-item__figure"><img src="/assets/vpp_fairness_figure.png" alt="Participation reinforcement in the Norway iFlex experiment"></div>
  <div>
    <h3>Fairness in virtual power plant aggregation</h3>
    <p>Virtual power plant (VPP) aggregators set incentive prices to induce heterogeneous consumers to provide flexibility, and profit-maximizing pricing can generate inequalities in participation and benefits. We developed a fairness-aware pricing framework, modeling the aggregator-consumer interaction as a Stackelberg game, and showed how energy, price, and utility fairness reshape consumer Nash welfare, total consumer utility, and social welfare. Profit-only pricing systematically disadvantages less flexible consumers, price fairness never benefits them, and utility fairness protects them without benefiting more flexible ones [<a href="https://arxiv.org/abs/2604.03559">Link</a>]. Because participation is voluntary and evolves over time, we further showed that fairness can act as an investment: fairer service allocation strengthens consumer engagement, expands future availability, and improves the aggregator's long-run profit, validated with field data from Norway [<a href="https://arxiv.org/abs/2606.02820">Link</a>].</p>
  </div>
</div>

<div class="research-item">
  <div class="research-item__figure"><img src="/assets/equitable_tariff.jpg" alt="Behavior-informed time-varying pricing"></div>
  <div>
    <h3>Behavior-informed time-varying pricing</h3>
    <p>Time-varying pricing tariffs incentivize customers to shift their electricity demand and reduce costs but may increase the energy burden for those with limited response capabilities. We proposed a joint learning-based identification and optimization method to design equitable time-varying tariffs. This method connects learning and optimization by embedding customers' price response behaviors, captured by a learning network structure, into the tariff design optimization. The equitable tariffs protect low-income consumers from price surges while motivating peak reduction and ensuring revenue recovery for utility companies. [<a href="https://arxiv.org/abs/2307.15088">Link</a>]</p>
  </div>
</div>

<div class="research-item research-item--text">
  <div>
    <h3>Socially informed distribution grid investment for urban electrification</h3>
    <p>New York City is projected to experience nearly double its electricity demand over the next two decades due to the <a href="https://www.nyc.gov/site/buildings/codes/ll154-building-electrification.page">electrification plan</a>, requiring a 60% increase in investment in energy infrastructure. A top priority is balancing efficiency and affordability. We first analyze the distribution pattern of the current energy infrastructure and identify the associated socio-technical impact. Then, we propose a demographics-driven metric to prioritize investment at the census tract level, which reveals a role for distributed batteries in urban electrification. This metric offers a novel approach to grid planning and supports an equitable path toward electrification. [Working paper]</p>
  </div>
</div>
