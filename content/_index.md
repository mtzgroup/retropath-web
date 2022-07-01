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

## WATOC 2022 Abstract:
Chemical reaction data is needed for reaction outcome and retrosynthesis predictions. The commonly used database is the USPTO database parsed by Dereck Lowe in 2016. However, the parsed data is not categorized and contains many errors. Herein, we categorize the parsed data using a template-based subgraph isomorphism procedure and an extensive library of templates [1]. We have successfully categorized ~600,000 parsed reactions. The categorization is highly informative about what types of reactions are most popular and useful and we have the associated reaction data including the conditions, sequences, and possible side reactions. Furthermore, the reactions that are found are a refined subset because there appears to be no missing atoms or inexplicable chemistry (our calculation is stoichiometric and is pattern matched against known reactions). Lastly, analysis of the reaction networks calculated for the parsed USPTO data provides information on the reliability of templates for molecule generation. The templates that successfully lead to the expected USPTO product more often than they fail are more reliable for molecule generation than those that rarely lead to an expected product but apply many times. Using this strategy, we have generated millions of new molecules one synthetic step from purchasable. Overall, the reaction classifications, associated data and pool of new molecules is highly valuable for computer aided synthesis planning.  Future work will seek to leverage this data in machine learning and high-throughput data applications.
