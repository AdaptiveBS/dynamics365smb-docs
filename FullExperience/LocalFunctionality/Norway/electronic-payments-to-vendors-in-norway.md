---
title: "Electronic Payments to Vendors in Norway"
ms.custom: na
ms.date: "06-05-2016"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "electronic payments, to vendors"
ms.assetid: a3e66937-ba08-41ee-9432-33b3265e3a13
caps.latest.revision: 2
ms.author: "edupont"
translation.priority.ht: 
  - "nb-no"
---
# Electronic Payments to Vendors in Norway
[!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] includes Norwegian enhancements for automatically making payments to vendors. This reduces errors that occur from manual data entry. You can use this functionality to perform the following operations:  
  
-   Search invoices that are due based on different conditions.  
  
-   Send payments to the bank.  
  
-   Receive messages from the bank on the status of payments.  
  
-   Receive paid transaction information to be posted.  
  
 You can make electronic payments using the following formats:  
  
-   TelePay  
  
-   Remittance payment  
  
## Electronic Payment Process  
 The following steps show how electronic payments are processed:  
  
1.  The payment proposal is run in the electronic payments feature and transferred to the bank by using the bank’s software.  
  
2.  The bank's software receives the payments and transfers payments to the bank.  
  
3.  The bank receives the payments and sends the first\-time return receipt to [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] using the bank's software.  
  
4.  The bank executes the payments and sends the settlement return \(second\-time return receipt\) to [!INCLUDE[navnow](../../ApplicationDesign/includes/navnow_md.md)] using the bank's software where the payments are posted.  
  
## Vendor Payment Requirements  
 If the payment transactions do not fulfill the requirements, an error message appears and you cannot create a payment file for transfers to the bank. The following criteria must be met when you process payments to vendors:  
  
-   The payment transaction must be positive or zero. A payment transaction must transfer a positive amount \(or zero\) to the payment receiver. This means that deducting a credit memo requires an invoice with the same or higher amount in the same payment transaction. Money cannot be deducted from the vendor's account.  
  
-   A credit memo must be applied with the invoice. Generally a credit memo does not contain a Kunde ID \(KID\). You cannot pay a credit memo in a payment transaction with invoices that contain a KID. This is because payments are usually split into transactions with or without a KID. This means that if a credit memo without a KID is paid with an invoice in the same payment transaction, the invoice must be paid without a KID, and the recipient reference number must be used instead.  
  
-   If the invoice and credit memo are paid in the same payment transaction, the payment must occur on the same date using the same currency and exchange rate.  
  
## See Also  
 [Norway Local Functionality](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/norway-local-functionality.md)   
 [How to: Set Up Remittance Agreements](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-remittance-agreements.md)   
 [How to: Create Remittance Accounts](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-create-remittance-accounts.md)   
 [How to: Set Up Vendors for Remittance](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-vendors-for-remittance.md)   
 [Recipient Reference Codes](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/recipient-reference-codes.md)   
 [How to: Create Remittance Suggestions](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-create-remittance-suggestions.md)   
 [How to: Create Manual Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-create-manual-remittance-payments.md)   
 [How to: Set Up Payment Line Information](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-set-up-payment-line-information.md)   
 [How to: Test Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-test-remittance-payments.md)   
 [How to: Export Remittance Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-export-remittance-payments.md)   
 [Types of Payment Returns Files](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/types-of-payment-returns-files.md)   
 [How to: Import Payment Return Data](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-import-payment-return-data.md)   
 [How to: Delete Remittance Payment Orders](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-delete-remittance-payment-orders.md)   
 [Remittance Errors](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/remittance-errors.md)   
 [How to: View Remittance Error Codes](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-view-remittance-error-codes.md)   
 [How to: Cancel Payments](../../LocalFunctionalityForMicrosoftDynamicsNav2016/Norway/how-to-cancel-payments.md)