![System Architecture Framework](../../diagrams/Logo_SAF.png)
# SAF Development Documentation : Physical Structure Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Physical](../../domains.md#Domain-Physical)|[Taxonomy & Structure](../../aspects.md#Aspect-Taxonomy-&-Structure)|![Proposed](../../diagrams/Under_construction_icon-red.svg )[proposed](../../using-saf/maturity.md#proposed)|
## Example
*none*
## Purpose
The Physical Structure Viewpoint is used to model the internal structure of the SOI and to identify the internal system elements making up the SOI. The SOI breakdown structure identifies system elements and finally on implementation level hardware, software, mechanics. The SOI breakdown structure determines items that are reused and make or buy (COTS) items. The Physical Structure Viewpoint is elaborated for each candidate physical SOI architecture. It provides the basis for further assessment of the architecture candidates by identifying the system elements in each candidate solution.
Note: It may be pointed out, that the physical architecture shall consider reuse, organizational, management and logistics support aspects. Hence, the physical architecture usually does not match the logical or the functional structure.
## Applicability
The Physical Structure Viewpoint supports the "Allocation and Partitioning of Logical Entities to Physical Entities" activities of the INCOSE SYSTEMS ENGINEERING HANDBOOK 2015 [§ 4.4.2.7]. The Physical Structure Viewpoint presents the product breakdown structure of a technical solution for the SOI providing all the identified external interface(s), a structure capable to implement the functionality identified in the logical Viewpoint(s).
## Stakeholder
* [Acquirer](../../stakeholders.md#Acquirer)
* [Project Manager](../../stakeholders.md#Project-Manager)
* [Security Expert](../../stakeholders.md#Security-Expert)
* [System Architect](../../stakeholders.md#System-Architect)
## Concern
* What are the HW components to be provided?
* What are the SW components to be provided?
* What are the configuration items in the physical architecture?
* What are the major system elements?
* What are the physical components?
* What is the physical breakdown of the system?
* What physical items are used building up the system?
* Which physical items the SOI is built of?
* what is the decomposition hierarchy of the system/logical elements
## Presentation
## Profile Model Reference
The following Stereotypes / Model Elements are used in the Viewpoint:
|Stereotype | realized Concept|
|---|---|
## Input from other Viewpoints
### Required Viewpoints
*none*
### Recommended Viewpoints
*none*
# Viewpoint Concept and Profile Diagrams
## Concept
![Physical Structure Concept](diagrams/Physical-Structure-Concept.svg)
## Profile
![Physical Structure Profile](diagrams/Physical-Structure-Profile.svg)