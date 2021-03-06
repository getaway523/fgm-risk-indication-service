---
title: Priority Capabilities for FGM Service
keywords: usecases
tags: [development]
sidebar: overview_sidebar
toc: false
permalink: overview_priority_capabilities.html
summary: A brief introduction to the priority FGM Service capabilities.
---

FGM Service is initially focussing on delivering two main interoperability capabilities:

<!--
![GP Connect Priority Capabilities](images/overview/priority_capabilities.png)
-->

# FGM View Only Capability #

A ‘view only’ capability within local NHS systems and Spine Mini Service Providers (SMSP). This will allow fully integrated query and response access to national FGM risk information from local NHS systems and SMSP’s.

## Query for patient FGM status ##

The FGM client will construct a FHIR FGM query message and send it to the SPINE:

Assuming successful transport, there are three possible outcomes:

- SPINE rejects the query due to business rules around the query construct
- SPINE executes the query and there is an FGM risk entry for the patient
- SPINE executes the query and there is no FGM risk entry for the patient

## FGM RIS Query and Response functionality ##

This activity diagram below illustrates interactive FGM RIS Query and Response functionality.

![stuff](images/fgm/FGMQueryResponseActivityDiagramv0.2.png)

<!-- [Access Record HTML Views](accessrecord_view_summary.html)

*Coming Soon...*

[Access Record Structured Data](accessrecord_structured_data_summary.html)  -->

# FGM Update Capability #

An ‘update’ capability within local NHS systems. Enabling additional create and delete capability for local NHS systems integration to the FGM RIS.

This functionality is only applicable to local NHS IT systems that are Spine compliant and use National Role Based Access Control (RBAC). The FGM RIS can only be updated by authorised healthcare professionals using Smartcards with the correct RBAC activity codes. 



## Create patient FGM flag

The FGM client will construct a FHIR create FGM flag message and send it to the SPINE

Assuming successful transport, there are two possible outcomes:

- SPINE rejects the create flag request due to business rules around the message construct
- SPINE executes the create flag request and there is an FGM risk entry created for the patient on Spine

<!-- [Appointment Management Capability](appointments.html) -->

## Delete patient FGM flag

The FGM client will construct a FHIR delete FGM flag request message and send it to the SPINE

Assuming successful transport, there are two possible outcomes:

- SPINE rejects the delete flag request due to business rules around the message construct
- SPINE executes the delete flag request and the FGM risk entry is deleted for the patient on Spine

## FGM RIS Update and Delete functionality ##

This activity diagram below illustrates interactive FGM RIS create and delete functionality TBA.


<!-- [Task Management Capability](tasks.html) -->

