---
title: "How to: Reserve Item-Tracked Items"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "reserving items, item-tracked items"
  - "item tracking, reserving"
ms.assetid: 962c5f1a-c37b-4c58-9fa9-6ef46d554779
caps.latest.revision: 7
ms.author: "sgroespe"
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
# How to: Reserve Item-Tracked Items
From outbound documents for item\-tracked items, such as sales orders or production component lists, you can reserve specific serial or lot numbers. This may be relevant, for example, if you need production components from a specific lot to ensure consistency with earlier production batches, or because a customer has requested a specific serial number.  
  
 This is referred to as a specific reservation, because you reserve from the quantity of  Item X that belongs to Lot X. If you simply reserve from quantities of Item X, then it is a normal, non\-specific, reservation. For more information, see [How to: Reserve Items for Sales Lines](../Sales/how-to-reserve-items-for-sales-lines.md).  
  
 The following procedure is based on a sales order.  
  
### To reserve a specific serial or lot number  
  
1.  In the **Search** box, enter **Sales Orders**, and then select the related link.  
  
2.  Create a sales order line for an item\-tracked item.  
  
     Proceed to assign serial and lot numbers to the sales order line.  
  
3.  On the **Lines** FastTab, choose **Line**, and then choose **Item Tracking Lines**.  
  
4.  In the **Serial No.** field, enter **SN1**, in the **Lot No.** field, enter **LOT1**, and then enter **1** in the **Quantity \(Base\)** field.  
  
5.  Close the **\($ N\_6507 Item Tracking List $\)** window.  
  
6.  On the sales order, on the **Lines** FastTab, choose **Functions**, and then choose **Reserve**.  
  
7.  Choose the **Yes** button to reserve specific serial or lot numbers.  
  
8.  In the   **\($ N\_6507 Item Tracking List $\)** window, select the serial and lot number combination that you have just assigned.  
  
9. Choose the **OK** button to open the **\($ N\_498 Reservation $\)** window showing only supply with the specified item tracking number. If there are any non\-specific reservations on any of the item tracking numbers that you have specified for this line, you are informed of the quantity that has already been reserved.  
  
10. On the **Actions** tab, in the **Functions** group, choose either **Auto Reserve** or **Reserve from Current Line** to create the reservation on the specific item tracking numbers.  
  
## See Also  
 [How to: Reserve Items for Sales Lines](../Sales/how-to-reserve-items-for-sales-lines.md)   
 [How to: Reserve Items for Production Components](../OperationsPlanning/how-to-reserve-items-for-production-components.md)   
 [How to: Reserve Items for Production Order Lines](../Production/how-to-reserve-items-for-production-order-lines.md)   
 [How to: Cancel Reservations](../Sales/how-to-cancel-reservations.md)   
 [How to: Change Reservations](../Sales/how-to-change-reservations.md)