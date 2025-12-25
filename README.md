# Marketing-Mix-Modelling-MMM-Case-Study
From Measurement to Decision: Optimising Programme Registrations with Meridian MMM

# Executive Summary
This case study applies Marketing Mix Modeling (MMM) using Google’s Meridian framework to evaluate the incremental impact of paid media on registrations and inform budget optimisation decisions. The analysis covered a ~$1.2M marketing budget across Social, Content, Search, Video, Display, and OOH across 2 years.

The model revealed that a significant portion of registrations was driven by baseline demand rather than paid media, reinforcing the need to assess performance based on incrementality rather than attributed volume. Among paid channels, Social emerged as the most efficient driver of registrations, delivering the highest ROI (~0.10) and lowest CPIK ($17.72), while showing early signs of saturation at higher spend levels. Video demonstrated the strongest marginal returns, indicating under-investment and incremental scaling potential. OOH was identified as inefficient for performance outcomes due to diminishing returns relative to spend.

A constrained optimisation scenario reallocated budget within a fixed spend and improved efficiency, generating approximately +308 incremental registrations and reducing CPIK from $20.36 to $20.27 without increasing total budget. Overall, the study demonstrates how MMM can be used not only to measure performance, but to guide pragmatic, data-driven media planning decisions under real-world constraints.


# Overview
This project applies Marketing Mix Modeling (MMM) using Google’s Meridian framework to evaluate paid media effectiveness and inform budget allocation decisions for programme registration growth. The focus of the analysis is not only on measuring channel performance, but on translating model outputs into concrete planning actions under realistic constraints.

# Business Context
The National Library Board introduces programmes catering across different ages and segments to enrich Singaporeans, and the marketing team's role is to market these programmes to secure registration. Annually, NLB invested approximately $600k a year across different paid channels—Social, Content, Search, Video, Display, and OOH—to drive registrations. While campaign-level performance suggested strong performance across several channels, there was limited understanding of how much demand was incremental, where diminishing returns were occurring, and how spend should be reallocated to improve efficiency without increasing budget.

MMM was introduced to provide a channel-level view of performance and to support data-driven optimisation decisions.

# Data & Methodology
Registrations were modeled as a function of paid media activity and an explicit baseline representing non-marketing demand. Weekly spend and exposure data from Jan 2023 to Jan 2025 were used across six paid channels. The model was implemented using Meridian’s Bayesian MMM framework, allowing for diminishing returns via channel response curves and uncertainty-aware estimates.

Model quality was assessed using R-squared (0.15) and wMAPE (19%). While the model explains a modest share of total variation, performance was sufficient for directional planning, particularly given the exclusion of owned channels such as Email and CRM.


# Key Insights: Demand Structure
A substantial portion of registrations was attributed to baseline demand rather than paid media. This indicates that while marketing meaningfully supports growth, it does not fully explain fluctuations in registrations. In practice, this means paid media performance must be evaluated based on incremental contribution rather than total volume, and that non-paid levers likely play a significant role in sustaining demand.

# Key Insights: Channel Effectiveness and Efficiency
Social and Content emerged as the primary drivers of incremental registrations. Social, in particular, delivered the strongest performance, combining the highest ROI (~0.10) with the lowest CPIK ($17.72). Its contribution was consistently strong across time, reinforcing its role as the core performance channel.

However, response curve behavior showed that incremental gains from Social begin to taper at higher spend levels. Although overall returns remain favorable, additional investment yields smaller marginal improvements compared to some lower-spend channels.

Video, while accounting for a smaller share of total spend, exhibited the highest marginal ROI (~0.03). Its response curve suggests that the channel remains in an elastic phase, indicating potential for incremental scaling before diminishing returns set in.

OOH, by contrast, contributed less incremental impact relative to its share of spend. Higher CPIK and weaker response at current investment levels suggest that the channel is saturated from a performance perspective.

# Key Insights: Budget Optimisation Outcomes
A constrained optimisation scenario was run using a fixed $1.2M budget and channel-level bounds of ±30%. Even within these tight constraints, the optimised allocation generated approximately 308 additional incremental registrations and improved CPIK from $20.36 to $20.27.

The optimisation primarily shifted spend away from OOH and toward Social, Content, and Video. Social and Content received modest increases, reflecting their strong but maturing performance, while Video saw a proportional increase aligned with its higher marginal returns. Search and Display remained broadly stable, indicating limited efficiency gains from reallocation.

# Recommendations
Based on the model outputs and optimisation results:

Social should remain the primary performance channel, with emphasis placed on creative, audience, and frequency optimisation to mitigate diminishing returns.

Video presents a clear opportunity for incremental investment and should be prioritised for controlled scaling and experimentation.

OOH spend should be reduced or repositioned toward upper-funnel objectives rather than performance-driven registration growth.

Budget optimisation should be treated as an ongoing process, supported by periodic model refreshes and incremental testing.

# Limitations and Future Improvements
The analysis does not include owned channels such as Email or CRM, likely inflating baseline contribution and understating total marketing impact. Channel-level aggregation also limits granularity in optimisation decisions, and external demand drivers such as promotions or product changes were not explicitly modeled.

Future iterations would benefit from incorporating owned media, adding creative- or audience-level splits, and pairing MMM outputs with incrementality experiments. Extending the KPI to longer-term value metrics such as LTV would further improve strategic relevance.

# Why This Case Study Matters
This project demonstrates how MMM can be used beyond reporting—to inform real budget decisions, manage saturation risk, and improve efficiency under fixed spend. It highlights a structured analytical approach that connects measurement to action, rather than treating model outputs as endpoints.
