## This is the landing page of the TAPI working group of LF ONMI Project.

### TAPI Main Facts:

- TAPI standardizes a single core technology agnostic specification that abstracts common transport network functions.
  + Decoupling from technology specific functions.

- TAPI model decouples service and resource oriented constructs.
  + This allows recursive application along management architecture, in a multi-carrier environment.

- TAPI model decouples functional/logical and physical oriented constructs.
  + This minimizes impacts due to technology optimization and evolution, without losing power of description.

- TAPI is defined in open-source environment.

### The Ecosystem:

- TAPI and TMF
  + Leveraging 20 years of experience in developing standard management interfaces, mainly in TMF for MTNM/MTOSI (aka TMF 814)

- TAPI and ONF Core IM
  + TAPI model is a formal pruning/refactoring of the generic ONF Core IM to customize for transfer over specific interface and make the terminology more familiar to users with experience in transport network modeling.

- TAPI and ITU-T
  + TAPI Technology Specific Models are derived from ITU-T (Ethernet, Digital OTN, Photonic)

- TAPI and MEF
  + TAPI has been extended by all MEF Network Resource Models
  + TAPI has been enhanced by MEF feedbacks
- TAPI and OIF
  + TAPI has been successfully adopted by 2016, 2018 and 2020 OIF Interops
- TAPI and [Telecom Infra Project (TIP)](https://telecominfraproject.com/oopt/)
  + TAPI is developed in conjunction with TIP, collaborating on requirements setting and use case focus.

### The Federation of Standard Models in Open-Source Environment:

![](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Activities/blob/main/ContributionsForDiscussions/TAPI-Intro_slide1.jpg)

The Transport API (TAPI) abstracts a common set of control plane functions such as Network, Topology, Connectivity Requests, Path Computation, OAM, and Network Virtualization to a set of Service interfaces. It also includes support for the following technology-specific interface profiles for Carrier Ethernet (L2), Optical Transport Network (OTN) framework (L1-ODU) and Photonic Media (L0-WDM).

![](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Activities/blob/main/ContributionsForDiscussions/TAPI-Intro_slide3.jpg)

### The TAPI releases:

![](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Activities/blob/main/ContributionsForDiscussions/TAPI-Intro_slide2.jpg)

## The TAPI Repositories
### [The code](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI)
- The TAPI code is composed by:
  + UML modules, managed through Eclipse/Papyrus
  + YANG modules, the schema semi-automatically generated from UML modules
  + OAS/Swagger modules, the API semi-automatically generated from YANG modules
- Latest release: [TAPI v2.6.0](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/releases/tag/v2.6.0)
- Target release recommended by TIP: [TAPI v2.5.0](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/releases/tag/v2.5.0)
- Main release in production and initial release recommended by TIP: [TAPI v2.1.3](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/releases/tag/v2.1.3)
- Release in progress: [TAPI develop](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/tree/develop)

### [The documentation](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation)
- The TAPI documentation is composed by:
  + TR-547 and TR-548 Reference Implementation Agreements (RIAs)
  + From TR-547 intro: _This document provides a set of requirements, guidelines and recommendations for a standard use of the TAPI models in combination with the RESTCONF protocol for the implementation of the interface between network systems in charge of the control/management of networks based on WDM/OTN technologies. This document can be used in conjunction with TR-548 which is the Reference Implementation Agreement for TAPI Streaming._
  + TAPI RIAs Ancillary Documents
    - TAPI Alarm TCA List
    - TAPI Notification and Streaming Sequences
  + TAPI Delta Document, to document the differences wrt previous release
  + TAPI Gendoc Templates, to generate MS-Word docs from UML modules
  + TAPI Tooling Guidelines, to describe the process to generate YANG and OAS modules
- [TAPI 2.6.0 Documentation](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/releases/tag/v2.6.0)
- [TAPI 2.5.0 / 2.5.1 Documentation](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/releases/tag/v2.5.0)
- [TAPI 2.1.3 Documentation](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation/releases/tag/v2.1.3)
- [TAPI Documentation in progress](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Documentation)
### [The current activities](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Activities)
- [Contributions for Discussions](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/tree/tapi-team-activities/TAPI-TEAM-ACTIVITIES/Contributions)
- [Meeting minutes and items under discussion](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI-Activities/wiki)
- [Plan](https://github.com/Open-Network-Models-and-Interfaces-ONMI/TAPI/wiki/TAPI-Plan)

### Participate!

To get involved in the project please join the mailing list and attend meetings:
- Mailing list: onmi-tapi@googlegroups.com 
- Meetings: Tuesday 9:00 AM US Eastern (Daylight) Time. Duration two hours.
  + [Zoom]( https://zoom-lfx.platform.linuxfoundation.org/meetings/onmi-project)
- Co-leaders: [Kishore Kumar](kishor.k_g@nokia.com), [Brian Johnson](bjohnson@ciena.com)
