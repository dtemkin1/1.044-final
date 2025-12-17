# Integrating Equity into Bus Network Redesign

1.144 Final Project, by Diego Temkin and Jade Personna

## Project Introduction

Our project aims to leverage category theory to design bus networks to be more equitable. Bus networks hold a unique advantage over other public transportation networks in that the routes buses take can be modified to meet different needs (Ceder et. al, 1986). Despite this, many optimization frameworks consider only adjustments to scheduling of routes, and not the actual paths taken. When shifts in the routes are considered, the quality of the new routes are usually quantified using metrics such as travel time and transfer times, which are meant to capture the effects on passenger and operator outcomes (Ceder et. al, 1986). However, there are opportunities to optimize networks using different metrics. The motivation for this project is to optimize routes for equity. Currently, the Lorenz curve and the Gini Coefficient are the most commonly used metrics to quantify equity. However, these metrics have been criticized for accounting for an equal distribution of resources, rather than an equitable distribution that considers socioeconomic statuses (Karner et. al, 2024). For the design of equitable bus networks, more robust models of equity are necessary to ensure positive outcomes for all users. Our project proposes the use of co-design to serve this purpose. Past work by Zardini et. al used co-design to assess the effects of autonomous vehicles in transportation networks. The study creates a design problem to generate feasible configurations of multi-modal networks by setting desired functionalities or requirements. In this study, networks are assessed by factors such as cost, travel time, and emissions (Zardini et. al, 2022).

Our project similarly uses category theory to generate transportation networks, with the goal of minimizing accessibility poverty across different subgroups, such as race, ethnicity, and populations with limited English proficiency. We began with a toy network with arbitrary fleet and size characteristics, choosing a small coverage area and fleet size to reduce complexity. We are in the process of integrating an applied category theory approach with a mixed-integer linear program (MILP) to add constraints to network generation. Future work on this project would include generalizing to larger fleet sizes and existing bus networks, and considering equity across other subgroups such as age and ability. Future work could also make use of data from the FTA’s National Transit Database to determine available assets and the Census/ACS database to determine demographic information.

## Sources

Ceder, A., & Wilson, N. H. M. (1986). Bus network design. Transportation Research Part B: Methodological, 20(4), 331–344. <https://doi.org/10.1016/0191-2615(86)90047-0>

Karner, A., Pereira, R. H. M., & Farber, S. (2024). Advances and pitfalls in measuring transportation equity. Transportation, 52, 1399–1427. <https://doi.org/10.1007/s11116-023-10460-7>

Zardini, G., Lanzetti, N., Censi, A., Frazzoli, E., & Pavone, M. (2022, February 21). Co-Design to enable user-friendly tools to assess the impact of future mobility solutions. <https://doi.org/10.3929/ethz-b-000533613>
