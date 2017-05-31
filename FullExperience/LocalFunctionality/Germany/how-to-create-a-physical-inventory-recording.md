---
title: "How to: Create a Physical Inventory Recording"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "physical inventory, recording"
ms.assetid: bc7b0f8a-e48d-4f00-a826-fc99e562012f
caps.latest.revision: 10
ms.author: "edupont"
manager: "terryaus"
translation.priority.ht: 
  - "de-de"
---
# How to: Create a Physical Inventory Recording
After you have created a physical inventory order and its lines you can create a new physical inventory recording for taking the inventory.  
  
 You can create a physical inventory recording manually if it is not necessary to use physical inventory lists or if the physical inventory data will be taken by a scanner. You can also create a physical inventory recording manually even if the related physical recording order does not contain any line. After finishing the physical inventory, the required physical inventory order lines are created automatically. This may be useful, for instance, in the case of a permanent physical inventory.  
  
 However, in most cases, you use a batch job to record inventory. Based on the physical inventory recording, you can print a list for taking the inventory and writing the results down. After that, you can transfer the results from paper to the physical inventory recording lines.  
  
### To create a physical inventory recording  
  
1.  In the **Search** box, enter **Phys. Inventory Order**, and then choose the related link.  
  
2.  Select the physical inventory order that you want to create an inventory recording for, and then, on the **Home** tab, choose **Edit**.  
  
3.  To create a physical inventory recording, on the **Home** tab, in the **Process** group, choose **Make New Recording**.  
  
4.  In the **\($ B\_5005361 Make New Phys. Invt. Recording $\)** window, on the **Options** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**Only Lines Not In Recordings**|Select to generate a new physical inventory recording line only if the data do not exist in any other physical inventory recording line.|  
    |**Recording Without Order Permit**|Select to generate a new physical inventory recording line.|  
  
5.  Choose the **OK** button to start the batch job.  
  
6.  On the **Navigate** tab, choose **Recordings**. The physical inventory recording window appears. Select the new created physical inventory recording.  
  
     You can now print a physical inventory list based on the data on the current physical inventory recording.  
  
7.  On the **Report** tab, choose **Physical Inventory Recording**.  
  
8.  In the **\($ R\_5005353 Phys. Invt. Recording $\)** window, set the appropriate filters, and then choose the **Print** button or choose the **Preview** button.  
  
     Optionally, you can use the [\($ B\_5005363 Copy Phys. Invt. Rec. Line $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Austria/-$-b_5005363-copy-phys.-invt.-rec.-line-$-.md) batch job to record serial numbers or lot numbers.  
  
9. In the **\($ N\_5005354 Phys. Inventory Recording $\)** window, select the physical inventory recording line, choose **Functions**, and then choose **Copy Line**.  
  
10. In the **\($ B\_5005363 Copy Phys. Invt. Rec. Line $\)** window, specify the number of copies to make of the selected line, and then choose the **OK** button.  
  
 You can use the printed physical inventory recording to update the actual quantity of the item available in the specified location. To complete the recording process, the **Recorded** check box must be selected for all physical inventory recording lines.  
  
 To show that you have finished the physical inventory recording, you have to set the **\($ T\_5005352\_11 Status $\)** on the inventory recording header to **Finished**. For more information, see [How to: Finish a Physical Inventory Recording](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/how-to-finish-a-physical-inventory-recording.md).  
  
### To complete a physical inventory recording  
  
1.  In the **Search** box, enter **Phys. Inventory Recording**, and then choose the related link.  
  
2.  Select the physical inventory recording that you want to complete, and then, on the **Home** tab, choose **Edit**.  
  
3.  In the **\($ R\_5005353 Phys. Invt. Recording $\)** window, on the **Lines** FastTab, in the **Quantity** field for each line, enter the actual item quantity.  
  
4.  Select the **Recorded** check box for each line.  
  
5.  On the **General** FastTab, fill in the fields as described in the following table.  
  
    |[!INCLUDE[bp_tablefield](../../ApplicationDesign/includes/bp_tablefield_md.md)]|[!INCLUDE[bp_tabledescription](../../ApplicationDesign/includes/bp_tabledescription_md.md)]|  
    |---------------------------------|---------------------------------------|  
    |**Person Recorded**|The person who recorded the inventory.|  
    |**Date Recorded**|The date on which the physical inventory was recorded.|  
    |**Time Recorded**|The time at which the physical inventory was recorded.|  
  
 You can now finish the physical inventory recording. For more information, see [How to: Finish a Physical Inventory Recording](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/how-to-finish-a-physical-inventory-recording.md).  
  
## See Also  
 [Physical Inventory Recording \- Counting Physical Inventory](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/physical-inventory-recording-counting-physical-inventory.md)   
 [How to: Enter Physical Inventory Orders](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/how-to-enter-physical-inventory-orders.md)   
 [How to: Calculate Quantity On Hand for a Physical Inventory Order](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/how-to-calculate-quantity-on-hand-for-a-physical-inventory-order.md)   
 [How to: Finish a Physical Inventory Recording](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Germany/how-to-finish-a-physical-inventory-recording.md)   
 [\($ B\_5005361 Make New Phys. Invt. Recording $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Austria/-$-b_5005361-make-new-phys.-invt.-recording-$-.md)   
 [\($ R\_5005353 Phys. Invt. Recording $\)](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Austria/-$-r_5005353-phys.-invt.-recording-$-.md)