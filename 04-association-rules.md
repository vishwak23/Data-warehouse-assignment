# Assignment 4: Association Rules using Apriori

*Note: This requires installing the "Orange3-Associate" add-on via Options -> Add-ons.*

**Objective:** Generate frequent itemsets and association rules.

**Orange Workflow:**
1. **File Widget:** Load a transactional dataset (e.g., `market-basket.tab` or `groceries`).
2. **Frequent Itemsets Widget:** Connect the File widget here. 
   - Set the Minimum Support threshold (e.g., 5% or 10%).
3. **Association Rules Widget:** Connect Frequent Itemsets to Association Rules.
   - Set the Minimum Confidence threshold (e.g., 50%).
   - View the generated rules, Support, Confidence, and Lift.
