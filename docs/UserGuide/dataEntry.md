---
title: User Data Entry Guide
layout: default
nav_order: 3
has_children: true
---

# User Data Entry Guide

Entering Nodes & Edges in Net.Create allows the user to create data networks such as the following: 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/sampleNetwork2.png)

## Node Data

At their simplest, nodes are the individual data points (e.g. people, places, things) within the network. 

Every node contains 4 basic attributes: 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/nodeExample.png)

- **Type:** Denotes which of the created [Node Types]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/createNodeTypes/nodeTypes.html) the data point is. 
- **Notes:** Contains information drawn directly from the source about the node.
- **Comments:** Contains information the data-entry team can use to understand how the node, its notes, and its related edges were entered.
- **Degrees:** Denotes the number of connections the selected node has to other nodes in the network.
	
Nodes may have additional optional attributes which can be configured in the [Template Settings]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/managing.html).

## Edge Data

Edges reflect the relationships and interactions between nodes, such as "loves, "hates," "buys," "sells," etc. 

Every edge contains 6 attributes: 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/edgeExample.png)

- **Type:** Denotes which of the created [Edge Types]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/createEdgeTypes/edgeTypes.html) is connecting two nodes. 
- **Notes:** Includes information relevant to the connection.
- **Date:** Indicates the time when the connection occurred. 
- **Weight:** Denotes how close of a linkage the edge is. (Default: 1)
- **Comments:** Includes information relevant to others who work on the network.
- **Citation:** References to the raw data as to where the connection comes from (Book Chapter, Stephanus Page, etc.)


## Additional Fields

### Provenance

Every node & edge has a "provenance" field which contains information about who created it, when it was created/last updated, and how many times it has been edited.

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/nodeProvenance.png)

### Meta-Comments

In addition to the particular fields for nodes & edges, any node or edge can receive a meta-comment: 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/commentButton.png)

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/commentUI.png)

These comments allow users to communicate with one another about the data of the nodes & edges. (e.g. Point out where citations are missing, where edges directions are incorrect, etc.)

The menu in the top right allows you to see these meta-comments and notifies you when someone responds to a comment you've left. 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/commentNotify.png)



[Link to existing Net.Create Documentation][Net.Create User Guide]


[Net.Create User Guide]: https://netcreate.org/userguide/