---
title: "Contract Trendscape Overview"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "service contracts, trendscape"
  - "contracts (service), trendscape"
  - "trendscape, contracts"
ms.assetid: f31b79a8-1d3c-4192-9755-cb884cb47d13
caps.latest.revision: 5
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# Contract Trendscape Overview
The **Contract Trendscape** window gives a financial overview of the service contract using the data from its service ledger entries. This overview is generated for a specific time period that you set in the **Period** field.  
  
 To use the trendscape, from the **Service Contracts** window, select a service contract. On the **Navigate** tab, in the **Contract** group, point to **Statistics**, and then choose **Trendscape**.  
  
 When you scroll up and down, the amounts \(in LCY\) are calculated according to the time interval you have set in the **Contract Trendscape** window.  
  
 You can specify which service contract is included in the trendscape by setting a filter in the **Contract No.** field on the **General** FastTab.  
  
 The **Period Start** and **Period Name** fields contain a series of dates that are determined by the time interval you have selected. You can change the time interval in the **View by** field.  
  
 The following table describes the other fields on the **Lines** FastTab.  
  
|[!INCLUDE[bp_tablefield](../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
|---------------------------------|---------------------------------------|  
|**Prepaid Income**|The total income \(in LCY\) that has been posted to the prepaid account for the service contract in the periods specified in the **Period Start** field.|  
|**Posted Income**|The total income \(in LCY\) that has been posted to the general ledger for the service contract in the periods specified in the **Period Start** field.|  
|**Posted Cost**|The cost of the service contract based on its service usage in the periods specified in the **Period Start** field.|  
|**Discount Amount**|The amount of discount \(in LCY\) that applies to the service contract in the periods specified in the **Period Start** field.|  
|**Profit**|The profit \(posted income minus posted cost in LCY\) for the service contract in the periods specified in the **Period Start** field.|  
|**Profit %**|The profit percentage for the service contract in the periods specified in the **Period Start** field.|  
  
 All amounts are calculated from service ledger entries, that is, entries that are created when you post service orders or service invoices related to the service contracts.  
  
> [!NOTE]  
>  If you have set the time interval to **Day** and you want to scroll over a long period, you can do it faster by shifting to a larger interval such as **Quarter**. When you have found the desired period, you can shift back to the original interval to see the data in more detail.