![System Architecture Framework](../../diagrams/Banner_SAF.png)
# SAF Development Documentation : **P8_PLOM** Physical Logical Mapping Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Physical](../../domains.md#Domain-Physical)|[Traceability & Mapping](../../aspects.md#Aspect-Traceability-&-Mapping)|![Released](../../diagrams/Symbol_confirmed.png )[released](../../using-saf/maturity.md#released)|
## Example
![Physical-Logical-Mapping-Viewpoint-primary-example.svg](../../diagrams/vp-examples/Physical-Logical-Mapping-Viewpoint-primary-example.svg)
## Purpose
The Physical Logical Mapping Viewpoint  supports the definition of the assignment of conceptual logical system elements to physical system elements comprising the SOI.

Following the identification of physical system elements capable of performing the system functions of logical elements, the Physical Logical Mapping Viewpoint provides feedback to the System Architecture Definition process to consolidate or confirm the allocation, partitioning, and alignment of logical elements to physical elements that comprise the SOI.
## Applicability
The Physical Logical Mapping Viewpoint supports the “Design Definition Process” activities of the INCOSE SYSTEMS ENGINEERING HANDBOOK 2023 [§2.3.5.5] and contributes to the artifact "Traceability Mapping".

Furthermore, the Physical Logical Mapping Viewpoint supports the "Allocation and Partitioning of Logical Entities to Physical Entities" activities of the INCOSE SYSTEMS ENGINEERING HANDBOOK 2015 [§4.4.2.7].
## Presentation
A assignment matrix featuring
* Logical Element Breakdown Structure showing Logical Element Roles and Logical Elements
* Physical Element Breakdown Structure showing physical element roles and physical elements
* Allocation relationship from logical system element roles to physical system element roles

## Stakeholder
* [Hardware Developer](../../stakeholders.md#Hardware-Developer)
* [IV&V Engineer](../../stakeholders.md#IV&V-Engineer)
* [Mechanic Developer](../../stakeholders.md#Mechanic-Developer)
* [Software Developer](../../stakeholders.md#Software-Developer)
* [System Architect](../../stakeholders.md#System-Architect)
## Concern
* [Which logical elements are allocated to which physical elements?](../../concerns.md#_2021x_2_8710274_1698399385413_529894_33129)
## Profile Model Reference
The following Stereotypes / Model Elements are used in the Viewpoint:
|Stereotype | realized Concept|
|---|---|
|Allocate [SysML Profile]|[LERspecifyingGPR](../concept/concepts.md#LERspecifyingGPR)|
|Attribute "logical_element" of SAF_PhysicalItem referencing SAF_LogicalElement|[LETspecifyingAPE](../concept/concepts.md#LETspecifyingAPE)|
|[SAF_LogicalElement](../../stereotypes.md#saf_logicalelement)|[Logical Element](../concept/concepts.md#Logical-Element)|
|SAF_LogicalInternalRole contained in SAF_LogicalElement|[Logical Element Role](../concept/concepts.md#Logical-Element-Role)|
|[SAF_P8_PLOM_Matrix](../../stereotypes.md#saf_p8_plom_matrix)|[Physical Logical Mapping Viewpoint](../concept/concepts.md#Physical-Logical-Mapping-Viewpoint)|
|[SAF_PhysicalElement](../../stereotypes.md#saf_physicalelement)|[Physical Element](../concept/concepts.md#Physical-Element)|
|[SAF_PhysicalHardwareElement](../../stereotypes.md#saf_physicalhardwareelement)|[Hardware Element](../concept/concepts.md#Hardware-Element)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[General Physical Role](../concept/concepts.md#General-Physical-Role)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[Hardware Element Role](../concept/concepts.md#Hardware-Element-Role)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[Physical Element Role](../concept/concepts.md#Physical-Element-Role)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[Physical Hardware Role](../concept/concepts.md#Physical-Hardware-Role)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[Physical Software Role](../concept/concepts.md#Physical-Software-Role)|
|[SAF_PhysicalInternalRole](../../stereotypes.md#saf_physicalinternalrole)|[Software Element Role](../concept/concepts.md#Software-Element-Role)|
|[SAF_PhysicalSoftwareElement](../../stereotypes.md#saf_physicalsoftwareelement)|[Software Element](../concept/concepts.md#Software-Element)|
## Input from other Viewpoints
### Required Viewpoints
* [Logical Structure Definition Viewpoint](Logical-Structure-Definition-Viewpoint.md)
* [Physical Structure Definition Viewpoint](Physical-Structure-Definition-Viewpoint.md)
* [Logical Functional Mapping Viewpoint](Logical-Functional-Mapping-Viewpoint.md)
### Recommended Viewpoints
* [System Functional Breakdown Structure Viewpoint](System-Functional-Breakdown-Structure-Viewpoint.md)
# Viewpoint Concept and Profile Diagrams
## Concept
![Physical Logical Mapping Concept](diagrams/Physical-Logical-Mapping-Concept.svg)
## Profile
![Physical Logical Mapping Profile](diagrams/Physical-Logical-Mapping-Profile.svg)
