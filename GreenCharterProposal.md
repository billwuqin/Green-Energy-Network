Charter proposal for Green Ready Energy Efficiency Network (GREEN)

Background and Motivation

As the imperative to reduce energy consumption gains momentum, network operators increasingly
focus on understanding power usage across nodes and devices within their networks. 
Green networking encompasses deploying and managing network infrastructures to minimize 
environmental impact. This will involve technologies to monitor power consumption, use control
strategies to lower carbon emissions, and foster sustainability in network operations.

RFC 6988 set out crucial requirements and guidelines for monitoring and managing energy usage in network devices, 
offering both prerequisites and practical implementation scenarios. However, the absence of 
standardized interfaces for measuring, reporting, and controlling energy consumption across 
diverse network setups remains a significant challenge. Therefore, new data models, metrics and methods are
required to optimize energy efficiency across the network.

Improving operational energy efficiency, as part of global sustainability efforts, may also necessitate 
enhancing inventory attributes, thereby contributing to a more sustainable lifecycle for network devices.

As the standardized set of models and metrics is being developed, a transition period will arise where a 
substantial portion of the equipment in the field may not support the new standardized metrics. 
Therefore, it is necessary to implement a framework that can normalize legacy metrics—sourced from 
either dynamic or static data to comply with the newly established standard metrics. 
This framework will enable the incremental deployment of these new metrics and mechanisms.

Tony suggested that metrics are important, but there is more we should
be doing, putting solutions in place. Actions vs Measurements. Rob
pointed out Tony's draft around actions that can help save energy.


Goals and Scope

GREEN WG is chartered to concentrate on short-term deliverables such as:
   - Terms and definitions related to energy metrics. Where possible, terms and definitions existing in prior RFCs 
     will be reused.
   - Reporting energy usage at the component, device and network layers through operational YANG models. 
   - Creating YANG data models that complete metrics for lifecycle assesment, allowing network devices and components to support circular economy strategies.
   - Providing configuration or YANG RPCs to influence and optimize energy usage in network devices, including energy saving capabilities. 
   - A framework that will enable the collection, aggregation and consumption for mentioned metrics and attributes.


Out of Scope
   - Routing protocols and energy aware routing algorithms considering green energy factors are far from mature
and are not in scope for this WG. 
   - Benchmarking methodology for power consumption in networking devices belongs in the BMWG, and is not in scope
for this WG.
   - Specification of green-oriented Network Quality Analysis (NQA) techniques to understand the impact of energy 
efficiency optimization on service quality, such as ICMP extensions for collection of environmental information.
   - Regulatory Reporting, Compliance, and Corporate Responsibility Disclosure 


**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy and sustainability in networking (Q4 2024). 
   - Draft and publish YANG models for operational energy efficiency and lifecycle assessment metrics. While metrics are valuable, they should be leveraged to guide and inspire changes in operational practices to improve energy efficiency and sustainability practices. (Q2 2025)     - Propose and ratify an architectural framework for energy and sustainability reporting (Q3 2025). 
   - Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 


**Work Items**

Terminology 
   - Candidate documents: draft-cparsk-eimpact-sustainability-considerations
Energy metrics collection and aggregation framework.
   - Candidate documents: draft-lindblad-tlm-philatelist-00, draft-kll-yang-label-tsdb, draft-cx-opsawg-green-metrics
Use Cases:
   - Candidate documents: draft-almprs-sustainability-insights
YANG model for energy consumption observability and energy saving management.
   - Candidate documents: draft-li-ivy-power; draft-cwbgp-ivy-energy-saving-management; draft-petra-path-energy-api; draft-opsawg-poweff

**Dependencies and Liaisons**

The GREEN Energy working group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
management, such as IVY, OPSAWG, NETMOD WGs.
   - WGs that might have related work or expertise with defining and standardizing metrics and measurement frameworks (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG, NMRG.
   - The IAB e-impact program to identify and receive short term metrics related work and to propose longer term problems for further study. 
   - Industry stakeholders and regulatory bodies to ensure alignment with current and future regulatory frameworks. 
   - Due to the overlap between IETF and ITU-T SG5/ETSI TCEE, mainly related to benchmarking methodologies, the GREEN
WG will liaise with ITU-T and ETSI for collaboration and consultation,as follows:
      o The European Telecommunications Standards Institute (ETSI), particularly with regard to the TCEE (Technical
     Committee of Environment Engineering).
      o The International Telecommunication Union (ITU), particularly with regard to ITU-T-SG-5.

