1. (relation from concept node) inherit from parent node (with caution; [[field (linear algebra)]]->[[Vector Space]] isn't a complete inheritance, in such case, 2. override inheritance is needed) TODO: specify inheritance rule for concept nodes[[inheritance for concept node]]
2. override inheritance from parent; concept nodes with overridden inheritance will be tagged as "unsafe inheritance" as the axis for the "parent_on_axis" relation


3. (relation to concept node) have element; here element means element type, not the specific limit to what element it can contain (with out specification, the element type are inherited from parent; There should be algorithm to check the root of a tree whether element is implemented -- TODO: [[how to check if element is needed at a node autometically?]])
4. (relation to parameter node -- in the graph view, this is only expanded when concept is zoomed into )have parameter; here parameter means variables (not necessary numbers) that make the concept what it is, instead of all the variables that instantiated object of the concept can have -- how to model those? #IKGD 
5. (relation to potential parameters it can hold, outside of its definition) 
6. have child node on 




7. connect with relations
	1. own concept in relation that isn't a child-parent relation; This is reserved specifically for the relation between a concept and another concept derived from it (which isn't a subset/child of it);
	2. combine through joint wiht another concept (with no deduction) a new concept for 

   