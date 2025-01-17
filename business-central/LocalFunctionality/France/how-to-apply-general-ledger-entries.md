---
title: Apply General Ledger Entries [FR]
description: You apply general ledger entries to justify ledger balances on asset and liability accounts.
author: brentholtorf
ms.topic: conceptual
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords:
ms.search.form: 16, 10842
ms.date: 06/18/2021
ms.author: bholtorf

---
# Apply General Ledger Entries in the French Version

> [!NOTE]
> Businesses in all countries can benefit from the ability to review general ledger entries before posting them. In a future release, we'll deprecate the country-specific feature and replace it with one that's available in all country versions. After the feature is deprecated, you can use it to access previous reviews, but not to do new reviews. We'll archive your data according to local requirements. To learn more about the deprecation, go to [Deprecated Features in the Base App](/dynamics365/business-central/dev-itpro/upgrade/deprecated-features-w1). To learn about the replacement feature, go to [Review Amounts in General Ledger Accounts](../../finance-review-accounts.md).

You apply general ledger entries to justify ledger balances on asset and liability accounts. For example, you can apply transactions on the bill of exchange accounts to get a clear picture of which bills make up the balance of the account.  

## To apply general ledger entries  

1. Choose the ![Lightbulb that opens the Tell Me feature.](../../media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Chart of Accounts**, and then choose the related link.  
2. On the **Chart of Accounts** page, select the account that you want to apply entries for, and then choose the **Apply Entries** action.  
3. On the **Apply G/L Entries** page, select the ledger entries that you want to apply.  
4. Choose the **Set Applies-to ID** action to populate the **Applies-to ID** field with the user ID of the current user.  
5. Choose the **Post Application** action.  

This effectuates the application by setting the **Letter** and **Letter Date** fields.  

> [!NOTE]  
> Applied entries can be identified by having the same three-letter combination and the same date.

## See Also  

[Unapply General Ledger Entries](how-to-unapply-general-ledger-entries.md)  
[Apply Vendor Payments Manually](../../payables-how-apply-purchase-transactions-manually.md)

[!INCLUDE[footer-include](../../includes/footer-banner.md)]