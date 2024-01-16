# Network Analysis Project

## Overview

This project involves social network analysis using the karate dataset available in the R igraphdata package. The dataset represents the social network among members of a karate club in a university, showcasing interactions and relationships.

## Dataset Description

Zachary’s karate club dataset is an undirected network with 34 vertices (members) and 78 edges. Two factions within the club are led by John A and Mr. Hi. The club later splits, and members choose new clubs based on their faction. The dataset includes attributes such as name, label, and faction for each vertex, and the edges have a weight representing common activities.

## Key Attributes

1. **Name**: Member's name.
2. **Label**: Shortened form of the name.
3. **Faction**: Faction membership (1 for Mr. Hi, 2 for John A).
4. **Weight**: Number of common activities.

## Methods

The analysis utilizes the igraph library for graphing network data and ggplot for plotting network statistics. Various network plots are created, emphasizing different vertex and edge attributes to highlight the nature of connections between nodes.

## Tools Used

- igraph
- igraphdata
- dplyr
- tidyverse


## Project Output

The results are compiled into the `network.html` file, offering a comprehensive view of the network analysis. Explore the visualizations and analysis to gain insights into the dynamics of the karate club.

Feel free to refer to the code files for a detailed understanding of the analysis process.