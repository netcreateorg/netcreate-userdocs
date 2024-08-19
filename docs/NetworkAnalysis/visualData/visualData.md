---
title: Visualizing Data
layout: default
parent: Guide to Network Analysis in Net.Create
nav_order: 2
---

# Finding the Data

Before putting data into a map, it is important to consider what kind of data you are interested in tracking and how to gather it.

## Questions to Consider

When it comes to contructing and interpreting nodes and edges, the following questions can help you get started:

### For Nodes

1.	Are you looking at individuals, collectives, or both? 
	- Consider using the Nodes Table to sort according to Degrees or Type. 
	- Consider using the Fade or Reduce filters. 
	
1.	What kinds of categories of those individuals/groups are you interested in tracking? (e.g. Does it matter whether a node is just a Person or a specific type of person?) 
	- Consider creating or having your administrator create additional [Node Types]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/createNodeTypes/nodeTypes.html#how-to-create-a-new-node-type) to reflect relevant differences. 
	- If you are unsure, err on the side of fewer types; you can always edit the nodes later. 
	
1.	Where is this data coming from and how do you want to reference it? (Book, Letter, Ledger, etc.)
	- Think about citation conventions for your subject matter, if relevant, (e.g. Citing Plato according to Stephanus pages), and use the Nodes Table to check that all the nodes follow a standard citation method. 

1.	What contextual information is relevant? (Non-Type Characteristics, Relatives, etc.) 
	- Utilize the Node's Notes field to include this information.
	- You can use the appropriate [Filter]({{site.url}}{{site.baseurl}}/docs/NetworkAnalysis/filteringData/filteringData.html#node--edge-filters) to filter your nodes according to data in this field. 

1.	Is there other information about this data point that is relevant to others working on this network? 
	- Include this information in a [Meta-Comment]({{site.url}}{{site.baseurl}}/docs/UserGuide/dataEntry.html#meta-comments) for your colleagues, or if you notice an issue with another node, add a comment to it from either its Node Edit UI or the Nodes Table. 

### For Edges

1.	Do you want to track every type of relationship or only certain ones? 
	- Consider creating or having your administrator create additional [Edge Types]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/createEdgeTypes/edgeTypes.html#how-to-create-a-new-edge-type) to reflect relevant differences.
	- Keep in mind that Net.Create allows you to track data in ways other than Edges (e.g. Notes, Comments, etc.)
	
1.	Are the relationships quantifiable (e.g. monetary, iterative, etc.)? 
	- Be sure that your Edge Weights are accurate and use the Edges Table or the appropriate Filter to view the relevant edges. 

1.	How descriptive do you want your connections to be? Does it matter whether the interactions are positive or negative? 
	- If all that matters is that two nodes interact with one another, consider using simpler descriptions of their relationship (e.g. "interacts with")
	- Alternatively, if you are interested in tracking the types of interactions, more specific edge types will be better suited. 
	- If you are unsure, err on the side of fewer types; you can always edit existing edges later. 

1.	Does the direction of the relationship matter? 
	- By default, Net.Create's edges have a direction from their Source node to their Target node. The Edges Table enables you to filter according to both. 

1.	How do you want to track the time when the relationship occurs? 
	- Net.Create supports a Date field when creating edges. Both the Edges Table and the Filters enable you to organize data according to this. 

## Using the Interface 

The tables at the top of the interface allow you to view and sort nodes & edges according to their [attributes]({{site.url}}{{site.baseurl}}/docs/UserGuide/dataEntry.html).

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/nodeTable.png)

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/edgeTable.png)

