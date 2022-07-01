---
title: 🧪 Retropath-Web
---


[named_reactions](notes/named_reactions.md) 

[▶️ Check out our work here ▶️](https://youtu.be/L-8zXFInrOc)


Project Team Members:
 - Alessio Valentini
 - Cody Aldaz
 - Samuel Pavelites
 - Keiran Thompson
 - Todd Martinez

WATOC 2022 Abstract:
Chemical reaction data is needed for reaction outcome and retrosynthesis predictions. Unfortunately, reaction data is often proprietary, and ignores minor products and intermediates that may be important under different conditions or otherwise poison the synthesis. Herein, we utilize a template-based procedure to simulate chemical reaction networks and products. Unlike previous template-based approaches the reaction network generated is directed and has no self-loops which allows the application to converge automatically. We evaluated the strategy against 1.9 M USPTO reactions; ~50% successfully lead to expected products. In many of the remaining cases, we find that the USPTO database fails to report needed reagents (and thus the reaction prediction system is working properly, but the input data is incomplete). The reactions that are found are an interesting subset because there appears to be no missing atoms (our calculation is stoichiometric), we know the conditions, and we have the associated reaction network, with reaction names. Reaction outcome prediction tasks may find this set more reliable and the associated data more fine-grained and informative. Finally, we generated millions of new molecules that are one synthetic step from purchasable molecules. This data is useful as a source of new molecules and for retrosynthesis algorithms. At present, our predicted reaction network does not include rate and yield considerations, so its predictions are a superset of the expected reaction products. This implies that some predicted products might be formed in negligible yield and the predicted reaction networks can be much larger than necessary. Future work will address these issues to increase the efficiency and accuracy of reaction prediction. 


