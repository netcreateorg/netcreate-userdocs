---
title: Filtering Data
layout: default
parent: Guide to Network Analysis in Net.Create
nav_order: 1
---

# Filtering Data

Net.Create allows users to manipulate how their data is displayed within the network by using a variety of filters. These filters allow data to be highlighted according to the following parameters:

-	**ID:** Filters based on the ID values of the nodes & edges assigned to them in the order they are created. (e.g. filters all nodes created before node #30)
-	**Label:** Filters based on the names of the node/edge.
-	**Type:** Filters based on the nodes/edges' assigned Type.
-	**Notes:** Filters based on the content of the nodes/edges' Notes field.
-	**Provenance:** Filters based on which user created the nodes/edges.
-	**Comments:** Filters based on the content of the nodes/edges' Comments field. 
-	**Degrees (Node Only):** Filters nodes based on the number of connections they have to other nodes. 
-	**Source (Edge Only):** Filters edges according to the node from which they begin. 
-	**Target (Edge Only):** Filters edges according to the node to which they are directed. 
-	**Date (Edge Only):** Filters edges according to the contents of their Date field. 
-	**Weight (Edge Only):** Filters edges according to their assigned Weight value. 
-	**Citation (Edge Only):** Filters edges according to the contents of their Citation field. (e.g. hide all edge connections which occur after Chapter 22) 


# Using the Filters

From the "Views" tab in the top right, you can select one of the following three filters: 

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/viewsTab.png)

## Highlighting Particular Data Relationships: The Fade Filter 

If you want to highlight particular points of interest within the network, the "Fade" tab will increase the transparency of nodes & edges, highlighting data that matches the filters.

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/fadeExample.png)

## Decluttering the Network: The Reduce Filter 

If you are working in a network with a large number of nodes and edges, the "Reduce" tab will remove the nodes & edges matching the filters.

![]({{site.url}}{{site.baseurl}}{{site.imageurl}}/reduceExample.png)

## Refining Your View: The Focus Filter 

If you want to view nodes with a specified number of edges within the network, the "Focus" tab will allow you to select a node, and view only the nodes connected by the chosen number of edges. 

![]({{site.url}}{{site.baseurl}}{{site.gifurl}}/focusExample.gif)

*	All of these tabs can be renamed and adjusted in the [Edit Template menu.]({{site.url}}{{site.baseurl}}/docs/ManagerGuide/managing.html#editing-filter-names)

