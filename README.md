# DecisionTreeRuleExplained
Decision Tree: 
Decision Tree are based on rules that can be easily understood by humans and can be easily implemented into the databases to identify certain set of records. 
Decision Tree are predective model based on branching of several Boolean Tests. 

It can be used for both: 
                         1.Regression. 
                         2.Classification. 
                         
                         
Decision Trees extract the hidden patterns, functional, operational and Demographic Data.

There are different type of deceision trees that can be used in Machine Learning algorithms.

If the target varaible is categorical then the decision tree is used as a Classification approach.
If the target variable is to predict a numerical value we go with the Regression approach.

Deceison Tree is a rule. Each branch connects nodes with "and " and multiple nodes are connected using "or".

The most common Decision Tree algorithms tthat are used are:

C5.0 (gives rules and numbers as well)
- Multi split
- Information Gain (Selecting parent Node)
- Rule based pruning.

CART
- Binary split
- Gini Index
- Tree Based Pruning.

#Decision Tree Rules
In order to filter out the variables we need to check for thiis rules

- Support: How frequently the item-set appears in database. It's is considered only when the suuport value is greater than 20%. 
- Confidence: It is the indication of how often the rule has been found to be true. Considered when the value is greater than 80%.
- Lift: Ratio of support to that expected if Xand Y are independent.
