---
title: Introduction to FGM Service
keywords: homepage
tags: [getting_started]
sidebar: home_sidebar
permalink: index.html
toc: false
summary: A brief introduction to getting started with the FGM Service FHIR&reg; Messaging API.
---

{% include important.html content="This site is under active development by NHS Digital and is intended to provide all the technical resources you need to successfully develop the FGM Service FHIR Mesaging API. Some areas are being formulated and iterative updates to content will be added on a regular basis." %}


# Background to FGM Risk Indication System #

Female Genital Mutilation (FGM) is an illegal, extremely harmful practice and a form of child abuse and violence against women and girls. The Government is committed to preventing and ending this harmful practice which violates the rights of girls and women. 

The Department of Health (DH) in partnership with NHS England has launched a FGM Prevention Programme which aims to improve the NHS’ response to FGM, increase levels of safeguarding for girls at risk of FGM and provide better subsequent support and care for those that have undergone FGM. 


As part of the FGM Prevention Programme, a national FGM Risk Indication System (FGM RIS) has been developed. This is a national IT service and forms part of the national Spine architecture. It allows FGM risk information for girls under 18 to be stored and shared with relevant NHS healthcare professionals across departmental, organisational and geographical boundaries within England, supporting effective early intervention and ongoing safeguarding of girls potentially at risk of FGM. 

The system was delivered in two stages:

**Stage 1: Delivery of the ‘Core Service’ -** the FGM RIS forms part of the national Spine architecture. From August 2015, the Summary Care Record application (SCRa) will include new functionality to allow authorised healthcare professionals to record, remove and view potential risk of FGM for girls under the age of 18.   

<!-- **Stage 2: Delivery of ‘View Only Integration Capabilities’ -** to make information held within the Core Service more widely available to healthcare staff by allowing integration of a ‘view only’ capability within local NHS systems. This will allow fully integrated query and response access to national FGM risk information from local NHS systems. 

**Stage 3: Delivery of ‘Update Integration Capabilities’ -** to develop additional creation and deletion capability for local systems integration to the FGM RIS. 

In addition, to update existing reporting capability to include transactions for adding, removing and viewing FGM RIS data from local systems via messaging.This will allow fully integrated query and response access to national FGM risk information from local NHS systems.  -->



**Stage 2: Delivery of ‘Integration Capabilities’ -** to make information held within the Core Service more widely available to healthcare staff by allowing integration of:

 - A ‘view only’ capability within local NHS systems and Spine Mini Service Providers (SMSP). This will allow fully integrated query and response access to national FGM risk information from local NHS systems and SMSP's. 
 - An ‘update’ capability within local NHS systems. Enabling additional create and delete capability for local NHS systems integration to the FGM RIS. This functionality is only applicable to local NHS IT systems that are Spine compliant and use National Role Based Access Control (RBAC). The FGM RIS can only be updated by authorised healthcare professionals using Smartcards with the correct RBAC activity codes. 


{% include important.html content="This Implementation Guide is only concerned with FGM RIS **Stage 2: Delivery of ‘Integration Capabilities’**." %}


# The FGM Vision #

The FGM Risk Indication System provides the ability to identify (flag) and share an identifier of vulnerable girls and women at risk of FGM (Female Genital Mutilation).

The FGM Risk Indication Service supports the wider Female Genital Mutilation Prevention (FGMP) Programme which is in place to protect, prevent and care for girls and vulnerable women who are at risk of FGM or who have been subjected to it. This service will allow Healthcare professionals and other government organisations (with an appropriate relationship), to flag girls and vulnerable women who are at risk of FGM. This information will be available in the following settings: Spine 2, GP systems, Child Health Systems and other government agencies.

Find out more on the NHS Digital [Female Genital Mutilation Risk Indication System (FGM RIS)](http://content.digital.nhs.uk/fgmris) homepage.



