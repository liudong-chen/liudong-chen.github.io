---
layout: splash
permalink: /research/
author_profile: false
---

{% include base_path %}
# Highlight 1: Rationalize Decision Behavior under Uncertainty

## Prudent demand to explain the first principles of risk-averse decision-making
<img style="float: left;  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 45px;
  margin-left: 0px;" src="/assets/Prudent_figure.png" width="300px" >
<br />
We show that risk-aware behaviors in demand response originate from non-quadratic discomfort state cost functions and price uncertainty with skewed distributions. We proposed a novel demand response formulation that combines non-anticipatory multi-stage decision making with non-quadratic cost functions, and showed prudence (the positive third-order derivative of the cost function) is the first principle that causes risk-averse decision behavior despite the formulation having a risk-neutral objective. We further proved that, given a non-quadratic cost function, the change in decision action level due to prudence scales proportionally with the skewness of the price distribution. [[Link](https://arxiv.org/abs/2405.16356)]

## Modeling customers' irrational behavior on energy trading
<img style="float: left;  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 45px;
  margin-left: 0px;" src="/assets/Social_attributes_figure.png" width="450px" >
<br />
Irrationality interacts with uncertainty, shaping consumer behavior away from rational profit maximization. We first quantified the predictability of renewable generation patterns in China [[Link](https://www.nature.com/articles/s41467-023-40670-7)], revealing the inherent uncertainty faced by renewable consumers. Building on this, we draw on prospect theory from economics--where decision makers tend to be aggressive under losses and conservative under gains--to model irrational consumer behavior under incentive mechanisms. We show that such irrationality redistributes consumers’ demand patterns in response to incentives [[Link](../assets/Social_Attributes.pdf)]. To capture heterogeneous individual responses more precisely, we integrated social survey data with load metering records and applied a spatio-temporal neural network to learn response behavior and embed it to design behavior-aware pricing mechanisms [[Link](../assets/Data-Driven_Stochastic_Game.pdf)].

<br />
<br />
<br />
<br />

# Highlight 2: Interpret Interactive Behavior under Emerging Mechanisms

## Theoretical game framework for coincident peak demand charge
<img style="float: left;  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 45px;
  margin-left: 0px;" src="/assets/agent_number.jpg" width="450px" >
<br />
Coincident peak (CP) demand charges customers based on their individual demand at the system's overall peak time. We proposed a novel game-based framework to analyze the CP shaving problem, developing a theoretical model to examine the impact of strategic customer behavior on system efficiency. The game structure exhibits different characteristics depending on the extent to which customers can shift their demand. We derived analytical Nash equilibrium solutions and analyzed the efficiency loss by comparing it to a standardized centralized peak-sharing model. [[Link](https://arxiv.org/abs/2501.02792)]

## Interdependence between network structure and strategic consumers
In practice, industrial consumers often have multiple network access points. We show that jointly optimizing access point selection and consumption adjustment can reduce energy transactions between the grid and consumers, thereby mitigating the operational impact on the grid [[Link](../assets/Multiple_Sharing_Region.pdf)]. Building on this, I developed a methodology that incentivizes consumers to adjust demand patterns while enabling the system operator to adaptively reconfigure the network through switch-position adjustments, improving operational efficiency [[Link](../assets/Dynamic_network_structures.pdf)]. Extending this line of research, I designed a voltage regulation approach in which autonomous consumers with solar panels are incentivized to provide voltage support, making use of existing infrastructure to support stable system operation [[Link](../assets/Voltage_Regulation.pdf)].

% Distributed energy resources (DER) shift customers' roles from consumers to prosumers, facilitating their participation in the energy market, where their subjective behavior impacts market operations. We modeled subjective prosumers in energy trading using prospect theory and stochastic game models, and we developed a solution algorithm that combines fitting, Markovian processes, and heuristic methods. [[Link](../assets/Social_Attributes.pdf)]. Using a behavior trial dataset from Ireland, we implemented a learning-based method to understand decision-making behavior and then embedded this behavior into the subsequent energy trading game model. [[Link](../assets/Data-Driven_Stochastic_Game.pdf)]
<br />


<br />
<br />

# Highlight 3: Sustainable energy solutions

## Social-economic dependency of electrification potentials in New York City (ongoing work)

New York City is projected to experience nearly double its electricity demand over the next two decades due to the [electrification plan](https://www.nyc.gov/site/buildings/codes/ll154-building-electrification.page), requiring a 60% increase in investment in energy infrastructure. A top priority is balancing efficiency and affordability. We first analyze the distribution pattern of the current energy infrastructure and identify the associated socio-technical impact. Then, we proposed a demographics-driven metric to prioritize investment at the census tract level. This metric offers a novel approach to grid planning and supports an equitable path toward electrification. 

## Behavior-Informed Time-Varying Pricing 
<img style="float: left;  margin-top: 10px;
  margin-bottom: 10px;
  margin-right: 45px;
  margin-left: 0px;" src="/assets/equitable_tariff.jpg" width="300px" >
<br />
Time-varying pricing tariffs incentivize customers to shift their electricity demand and reduce costs but may increase the energy burden for those with limited response capabilities. We proposed a joint learning-based identification and optimization method to design equitable time-varying tariffs. This method connects learning and optimization by embedding customers' price response behaviors, captured by a learning network structure, into the tariff design optimization. The equitable tariffs protect low-income consumers from price surges while motivating peak reduction and ensuring revenue recovery for utility companies. [[Link](https://arxiv.org/abs/2307.15088)]



