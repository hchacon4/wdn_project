## Water Distribution Network Project
Water Distribution Network leak location using sparse sensor grids

### Demo
Access a demo of end-to-end trainable model in the Demo folder and follow README instructions.

### Training Pipeline
Overview: Construct your own training experiments using the following steps.  
1) Run [data simulator](https://github.com/hchacon4/wdn_project/tree/main/Simulators)  
2) [Partition](https://github.com/hchacon4/wdn_project/tree/main/Graph%20Partitions) water network into regions (using graph_partion notebook)  
3) Create training data files  
4) Train the model  
5) Analyze results  

Further details can be found in README files within each folder.

Use the same EPANET INP file throughout an given training pipeline.  If new water network model is desired (i.e. new INP file), start anew from step one.  
