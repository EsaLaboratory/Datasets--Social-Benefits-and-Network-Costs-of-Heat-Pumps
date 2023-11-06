# Social-Benefits-and-Network-Costs-of-Heat-Pumps 

This repo contains the case study outputs for our paper "Evaluating the Social Benefits and Network Costs of Heat-Pumps as an Energy Crisis Intervention". 

All these results are stored in "all_paper_outputs.csv".

This file has 41 rows, corresponding to the 32 Scotland LAs and 9 England government regions studied here. The columns include the following: 
1. fp\_2019(\%): the estimated fuel poverty rate over the pre-crisis period.
2. fp\_2022(\%): the estimated fuel poverty rate over the crisis period.
3. fp\_2019\_HP\_plus\_upfront(\%): the estimated fuel poverty rate over the pre-crisis period after replacing off-gas heating with HPs. The HP upfront cost is included through the amortisation with a 7\% interest rate.
4. fp\_2022\_HP\_plus\_upfront(\%): the estimated fuel poverty rate over the crisis period after replacing off-gas heating with HPs. The HP upfront cost is included through the amortisation with a 7\% interest rate.
5. fp\_2019\_HP\_plus\_upfront\_plus\_network(\%): the estimated fuel poverty rate over the pre-crisis period after replacing off-gas heating with HPs. The HP upfront cost is included through the amortisation with a 7\% interest rate. The additional repayment towards the network upgrade costs is also included.
6. fp\_2022\_HP\_plus\_upfront\_plus\_network(\%): the estimated fuel poverty rate over the crisis period after replacing off-gas heating with HPs. The HP upfront cost is included through the amortisation with a 7\% interest rate. The additional repayment towards the network upgrade costs is also included.
7. off\_gas\_GHG\_emission(kgCO2e): the total GreenHouse Gas (GHG) emission by residential heating in the off-gas sector.
8. off\_gas\_GHG\_emission\_HP(kgCO2e): the total GHG emission by residential heating in the off-gas sector after the HP rollout.
9. off\_gas\_GHG\_reduction\_rate(\%): the proportion of reduction of GHG emission by residential heating in the off-gas sector after the HP rollout.
10. network\_upgrade\_cost(M£): the total distribution network upgrade cost for a region, scaled from the Primary Substation (PS) upgrade costs.
11. network\_upgrade\_cost\_per\_PS(M£): the distribution network upgrade cost for a region averaged by the number of PSs in the region.
12. number\_of\_PS: the number of PSs in the region.

Please reach our paper for more details and the methodology behind.

Please cite the following paper for using this dataset: 

Evaluating the Social Benefits and Network Costs of Heat-Pumps as an Energy Crisis Intervention, Yihong Zhou, Chaimaa Essayeh, Sarah Darby, Thomas Morstyn, 2023
