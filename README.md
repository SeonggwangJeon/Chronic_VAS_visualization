D Force-Directed Correlation Graph Visualization
This repository contains a Python script that generates an interactive 3D force-directed graph to visualize correlations between different columns in a DataFrame. The central node represents the target column, and surrounding nodes represent other variables, with the edge thickness indicating the strength of the correlation between them.

Features
3D Force-Directed Layout: The graph layout is dynamically computed using a force-directed algorithm in three dimensions, creating a visually intuitive representation of correlations.
Edge Thickness: The thickness of edges varies depending on the correlation strength between the nodes, with thicker lines indicating stronger correlations.
Node Customization: The central node is highlighted with a larger size and custom color (orange by default), while surrounding nodes are colored sky blue. Node sizes also vary based on their correlation with the central node.
Interactive Visualization: The visualization is rendered using Plotly, making it fully interactive. You can rotate, zoom, and explore the graph.
No Background/Axis: The plot is designed for a clean aesthetic with no axis labels, background grid, or ticks, focusing purely on the data relationships.
How It Works
The script constructs a graph using the NetworkX library, with nodes representing columns in the DataFrame. Edges are added between the central node and other nodes based on the correlation coefficient, as well as between all other surrounding nodes. Positions for nodes are computed in 3D space using the spring_layout function, and adjustments are made to scale and fine-tune the graph's appearance.

The visualization is created using Plotly's Scatter3d class, with customizable parameters like node color, size, and edge width based on correlation strength.
