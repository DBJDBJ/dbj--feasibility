
<h1> IT LANDSCAPE GOVERNANCE </h1>

&copy; 2020 by DBJ, Licence: LICENCE_DBJ

Contents

- [1. Physical Partitioning](#1-physical-partitioning)
- [2. Units of Governance](#2-units-of-governance)
    - [2.0.1. Cost Management Expenditure terminology](#201-cost-management-expenditure-terminology)

> **TERMINOLOGY -- Common Project Vocabulary**

Pragmatic, simple and robust, IT Landscape delivery and governance in an organization based on Information Technology.

# 1. Physical Partitioning

Each IT Landscape has three 3 layers (sometime called "tiers") :

- #### Layer 1 -- front end software 
     - Example: Web sites, Web Applications, Mobile App's, etc.
- #### Layer 2 -- system software 
     - Examples: Azure cloud services, OS (Windows, etc...), Database clusters, Load Balancers, etc...
- #### Layer 3 -- Infrastructure 
     - Examples: Azure platform setup, config and ongoing admin
     
> **Ubiquitous Governance Taxonomy is critical for collaboration.**

Governance of IT Landscape can have up to 5 parts aka "stages". It Landscape is divided in 3 layers. Each stage is decoupled and encapsulated. 

| A           | B                       | C                     | D          | E       | F                 |
| ----------- | ----------------------- | --------------------- | ---------- | ------- | ----------------- |
| DEVELOPMENT | User Acceptance Testing | Operational Integrity | Production |         | Recovery Position |
| Layer 1     |                         |                       |            |         |                   |
| Layer 2     |                         |                       |            |         |                   |
| Layer 3     |                         |                       |            | (EXTNL) |                   |
	
Organization should follow that as an high level taxonomy of IT Landscape.

IT Landscape Governance requires 5 distinctive streams. Coordinated and giving information to each other. 	

Each Stream is implemented as one, two or three teams. 
One per layer, one for all layers, etc. It largely depends on the IT Landscape scope.

For example. Sometimes IT landscape of an organization is just about Front End in the form of a Web Sites. In that case there is just "Layer1". Delivered and governed in up to 5 independent stages.

IT Landscape Staged Partitioning is both physical and logical
	
- A DEVELOPMENT 
   - Encapsulating on-going Process of developing new releases of the system.
- B User Acceptance Testing (UAT)
   - Encapsulating on going process of formal testing by the selected group of end users, partners, businesses and such.
- C Operational Integrity (OI)
   - Encapsulating on going independent and isolated process for testing the suitability of the system to work in the production environment
- D Production
   - Encapsulating on going Maintenance, Monitoring, Configuration and the System running live. This is isolated machinery, running 24x7 in several locations around the globe. In the cloud, on premises or in a hybrid configuration. NOTE: This is from where data has to be pro-actively stored in a GDPR compliant manner, regarding the data age, not just the content.
- E+F -- Disaster and Recovery
  - Encapsulating Backup position of the System production stage. this is where Disaster procedures are documented, planned and pro-actively maintained. "Recovery Position" is separate machinery "kicking into action" if and  when disaster strikes. In the context of "DBJ.Systems" system this is largely maintained by Azure services. But it has to be maintained by an appointed Team.
			 

Governance Stages are living independent life. For example UAT sometimes might need just a few testers, or at other times dozens or more. It depends what is being tested, major release or some small extension.

Obviously some parts of the IT Landscape need more human resource vs the others.

Process flow is not one way, from left to right. It is cyclical.
For example A (Development) delivers to B (UAT). B gives feed back to A.

Phase (E) or "External Infrastructure" (WAN, Mobile G5, etc...)
Very large IT projects are mapped one-to-one to the cells above.
From A:1 to F:3.

# 2. Units of Governance

5 stages, divided vertically into 3 layers are making 15 units of governance. Each of these 15 units also means resources and expenses management.

###  2.0.1. Cost Management Expenditure terminology

- **CAPEX** -- CAPital EXpenses , upfront payments, (software licence, laptops, offices, etc.)
- **OPEX** -- OPErational EXpenses (labour costs, Azure Cloud, travel)
- **REVEX** -- REVenue EXpenses (repairs, immediate expenses) -- FYI only

> NOTE: In an ideal theoretical situation Cloud Computing allows for 100% OPEX.

Logically, no organization can ignore any of the governance units above. Even if it currently does not exist. It has to be planned for. Realistically, some units will require small or very small expenditure.
But none can be ignored.

CVP, Conceptual, Logical and Physical stages will (also) help define the existence of governance units and thus develop the scope for the "Final Investment Decision" gate.

---
Contact: dbj at dbj dot org