There are 2 types of conditions.

# Condition: simple

The condition is composed of:

* *Asset type*: Select the type of asset
* *Property name*: Name of property of the *asset type* selected
* *Condition operator*: Condition operator (=, >, >=, <, <=, like)
* *value*: Value of the condition. For *condition operator* **like**, you can use %
* *Child*: *no child* mean you will get element of *asset type* defined / 
*direct child (first level)* mean you will get asset parent of this *asset type*

# Condition: group

You can add many sub-(simple conditions)

# Operator: intersection

Intersection operator will return only elements verify all conditions.
See on [WikipediA](http://en.wikipedia.org/wiki/Set_(mathematics)#Intersections)

# Operator: union

Union operator will return all elements verify at least one of the conditions.
See on [WikipediA](http://en.wikipedia.org/wiki/Set_(mathematics)#Unions)

# Operator: difference

Difference operator will return only elements verify at least one condition 
but not all conditions.
See on [WikipediA](http://en.wikipedia.org/wiki/Symmetric_difference)
