# Workshop 2023 tutorial

## Outline

In this tutorial, you will solve the order-picking path minimization problem, by detecting communities in a graph.
#### Notebook
https://colab.research.google.com/github/margaritavit/min_order_picking_path/blob/main/workshop__order_picking_opt.ipynb

#### Instructions
1. Download csv files from 'data' folder.
2. Open notebook in colab
3. Load files in colab
4. Run notebook
5. Optional: Try different values in node/edge removal thresholds and resolution parameter of louvain_communities function. 

### Part 1: Generate and visualize network of parts
  - Nodes of parts network
  - Edges of parts network
  - Visualize parts network

### Part 2: Explore network properties
  - Degree distribution
  - Node strength distribution

### Part 3: Find network connected components
  - Connected components
  - Component Size, Average Clustering Coefficient, Density
  - Visualize connected components

### Part 4: Community detection in the largest connected component of the network
  - Louvain algorithm for community detection (modularity maximization)

### Part 5: Evaluate partition of the largest connected component
  - Measures of network partition quality: Modularity, Coverage, Performance
  - Community size, Average Clustering Coefficient, Density, Intra-community edge strength ratio, Intra-community edge number ratio
    
### Part 6: Graph of communities
  - Similarity between communities
  - Visualize graph of communities

## References
https://math.bme.hu/~gabor/oktatas/SztoM/Newman_Networks.pdf
https://www.sciencedirect.com/science/article/abs/pii/S0370157309002841
https://arxiv.org/abs/0803.0476

## License

Designed for education purposes. Please do not distribute without permission.   
Write at m.vitoropoulou@aegeanair.com, christos.grigoras@aegeanair.com if you have any questions.

MIT License

Copyright (c) 2023 Margarita Vitoropoulou, Christos Grigoras

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



