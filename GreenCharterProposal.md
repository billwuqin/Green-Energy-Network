Charter proposal for Energy Metric for Energy Efficiency Network (GREEN)

Background and Motivation

As the imperative to improve energy efficiency gains momentum (e.g., ITU-T SG5 has been tasked with development 
of energy efficiency metrics, KPI, ETSI TCEE works on environmental efficiency related standards covering 
server, data storage, network equipments), network operators increasingly
focus on understanding energy consumption usage across links,nodes and devices within their networks. 
Green networking encompasses deploying and managing network infrastructures to reduce energy consumption,
minimize environmental impact. This will involve technologies to monitor energy consumption, evaluate the
effectiveness of energy saving polices, use control strategies to improve energy efficiency, and foster 
sustainability in network operations.

RFC 6988 provides some requirements and guidelines for monitoring and managing energy usage in network devices. The GREEN working group will examine that work with a view to re-using it where possible, and developing new requirements according to current use cases and applications. More recently, RFC 9547 highlighted the need 
of further work on metrics, measurements, ability to slow down and sleep devices or part of them, etc. However, 
there is no consistent view in the industry for terminologies to categorize various type of metrics and measurements.
In addition, the absence of standardized interfaces for measuring, reporting, and controlling energy consumption across diverse network setups remains a significant challenge. Therefore, new data models, metrics and methods are required to optimize energy efficiency across the network.

Improving operational energy efficiency, as part of global sustainability efforts, may also necessitate 
enhancing inventory attributes, thereby contributing to a more sustainable lifecycle for network devices.
It should also be about actually putting in place technology that improves our energy efficiency and 
sustainability.

As the standardized set of models and metrics is being developed, a transition period will arise where a 
substantial portion of the equipment in the field may not support the new standardized metrics. 
Therefore, it is necessary to implement a framework that can normalize legacy metrics—sourced from 
either dynamic or static data to comply with the newly established standard metrics. 
This framework will enable the incremental deployment of these new metrics and mechanisms.


Goals and Scope

GREEN WG is chartered to concentrate on short-term deliverables such as:
   - Terms and definitions related to energy metrics. Where possible, terms and definitions existing in prior RFCs 
     will be reused.
   - Reporting energy usage at the component, device and network layers through operational YANG models. 
   - Creating YANG data models that complete metrics for lifecycle assesment, allowing network devices and components to support circular economy strategies.
   - Providing configuration or YANG RPCs to influence and optimize energy usage in network devices, including energy saving capabilities. 
   - A framework that will enable the collection, aggregation and consumption for mentioned metrics and attributes.

The work builds upon YANG models developed in the IVY WG, hardware YANG model developed in NETMOD WG, as well as other work 
in the NMRG. The GREEN WG, will combine all these concrete approaches systematically so as to evolve energy 
efficiency in a clear and coherent manner.

The GREEN WG will prioritize definitions of the following factors:

   - port transceiver power information (optical power, status, etc.)
   
   - port group power information (power, status, etc.)
   
   - board power information (Volt, Ampere, Watt, temperature, status, etc.)
   
   - chassis power information (available volume, Watt, status, etc.)
   
   - power supply information (type, status, redundancy manner, quantities, etc.)
   
   - fan information (status, speed, tuning manner, etc.)
   
   - energy consumption levels (basic, standard, deep, etc.)
   
   - energy efficiency ratios (device, network, etc.)

Out of Scope
   - At this time, routing protocols and energy aware routing algorithms considering green energy factors are far from mature
and are not in scope for this WG. 
   - Benchmarking methodology for power consumption in networking devices belongs in the BMWG, and is not in scope
for this WG.
   - Specification of green-oriented Network Quality Analysis (NQA) techniques to understand the impact of energy 
efficiency optimization on service quality, such as ICMP extensions for collection of environmental information.
   - Regulatory Reporting, Compliance, and Corporate Responsibility Disclosure 


**Milestones:** 

   - Develop and agree upon a standardized set of terminologies and definitions related to energy efficiency and sustainability in networking (Q4 2024).

   - Draft and publish YANG models for operational energy efficiency related metrics. While metrics are valuable, they should be leveraged to guide and inspire changes in operational practices to improve energy efficiency and sustainability practices. (Q2 2025)

   - Propose and ratify an architectural framework for energy and sustainability reporting (Q3 2025).

   - Demonstrate initial implementations and use cases of the YANG models in network devices (Q4 2025). 


**Work Items**

Terminology and Metric Definitions.

YANG model for energy consumption observability and energy saving management.
   - Candidate documents: draft-li-ivy-power; draft-cwbgp-ivy-energy-saving-management; draft-petra-path-energy-api;
draft-opsawg-poweff

Energy metrics collection and aggregation framework.
   - Candidate documents: draft-lindblad-tlm-philatelist, draft-kll-yang-label-tsdb, draft-cx-opsawg-green-metrics

Use Cases:
   - Candidate documents: draft-almprs-sustainability-insights

**Dependencies and Liaisons**

The GREEN Energy working group will closely collaborate with:

   - Other IETF Working Groups that address topics related to power consumption observability and energy efficiency
management, such as IVY, OPSAWG, NETMOD WGs.
   - WGs that might have related work or expertise with defining and standardizing metrics and measurement frameworks (e.g., IPPM and BMWG). 
   - Other IRTF Research Groups that provide research inputs and reviews, including PANRG, NMRG.
   - The IAB e-impact program to identify and receive short term metrics related work and to propose longer term problems for further study. 
   - Industry stakeholders and regulatory bodies to ensure alignment with current and future regulatory frameworks. 

The GREEN WG will liaise with ITU-T and ETSI on benchmarking methodologies for collaboration and consultation,as follows:

   - The European Telecommunications Standards Institute (ETSI), particularly with regard to the TCEE (Technical
     Committee of Environment Engineering).
     
   - The International Telecommunication Union (ITU), particularly with regard to ITU-T-SG-5.

