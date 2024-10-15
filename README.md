3D Force-Directed Correlation Graph Visualization
This repository contains a Python script that generates an interactive 3D force-directed graph to visualize correlations between different columns in a DataFrame. The central node represents the target column, and surrounding nodes represent other variables, with the edge thickness indicating the strength of the correlation between them.

Features
3D Force-Directed Layout: The graph layout is dynamically computed using a force-directed algorithm in three dimensions, creating a visually intuitive representation of correlations.
Edge Thickness: The thickness of edges varies depending on the correlation strength between the nodes, with thicker lines indicating stronger correlations.
Node Customization: The central node is highlighted with a larger size and custom color (orange by default), while surrounding nodes are colored sky blue. Node sizes also vary based on their correlation with the central node.
Interactive Visualization: The visualization is rendered using Plotly, making it fully interactive. You can rotate, zoom, and explore the graph.
No Background/Axis: The plot is designed for a clean aesthetic with no axis labels, background grid, or ticks, focusing purely on the data relationships.
