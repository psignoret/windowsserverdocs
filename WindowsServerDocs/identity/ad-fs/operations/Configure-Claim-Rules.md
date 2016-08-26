---
title: Configure Claims Rules
description:
author: billmath
manager: femila
ms.date: 08/23/2016
ms.topic: article
ms.prod: windows-server-threshold
ms.service: active-directory
ms.technology: active-directory-federation-services
---

# Configure Claim Rules

>Applies To: Windows Server 2016, Windows Server 2012 R2

In a claims\-based identity model, the function of Active Directory Federation Services \(AD FS\) as federation services is to issue a token that contains a set of claims. Claims rules govern the decisions with regard to claims that AD FS issues. Claim rules and all server configuration data are stored in the AD FS configuration database.  
  
AD FS makes issuance decisions that are based on identity information that is provided to it in the form of claims and other contextual information. At a high level, AD FS operates as a rules processor by taking one set of claims as input, performs a number of transformations, and then returns a different set of claims as output. 

The following topics will assist you in creating the rules that AD FS will process: 
  
-   [Create a Rule to Pass Through or Filter an Incoming Claim](Create-a-Rule-to-Pass-Through-or-Filter-an-Incoming-Claim.md)  
  
-   [Create a Rule to Permit All Users](Create-a-Rule-to-Permit-All-Users.md)  
  
-   [Create a Rule to Permit or Deny Users Based on an Incoming Claim](Create-a-Rule-to-Permit-or-Deny-Users-Based-on-an-Incoming-Claim.md)  
  
-   [Create a Rule to Send LDAP Attributes as Claims](Create-a-Rule-to-Send-LDAP-Attributes-as-Claims.md)  
  
-   [Create a Rule to Send Group Membership as a Claim](Create-a-Rule-to-Send-Group-Membership-as-a-Claim.md)  
  
-   [Create a Rule to Transform an Incoming Claim](Create-a-Rule-to-Transform-an-Incoming-Claim.md)  
  
-   [Create a Rule to Send an Authentication Method Claim](Create-a-Rule-to-Send-an-Authentication-Method-Claim.md) 
-   [Create a Rule to Send an AD FS 1.x Compatible Claim](Create-a-Rule-to-Send-an-AD-FS-1x-Compatible-Claim.md) 
  
-   [Create a Rule to Send Claims Using a Custom Rule](Create-a-Rule-to-Send-Claims-Using-a-Custom-Rule.md)  

## See Also  
[AD FS Operations](../../ad-fs/AD-FS-2016-Operations.md) 