# Computational-Modeling-Accuracy-in-Malate-Dehydrogenase-Structure-Predictions-and-Interactions
CUI B.S. Senior Thesis

## Overview
### Objective

The purpose of this project was to determine the accuracy of computational modeling applied to Malate Dehydrogenase structure predictions and interactions. The goal was to streamline the efficiency of enzyme modeling and overcome typical limitations of laboratory methods (time, cost, etc.). The current lack of evidential success with computational methods demands comparing in-silico results with wet-lab data to validate the efficacy of computational pipelines. Then, simulations can serve as a supplement to enhance wet-lab procedures with predictive foresight before intensive procedures are implemented. By comparing wild-type modeling results to current laboratory data, we can benchmark the pipeline and apply the mutation to predict results. This study focuses on the effects of the R153C mutation.

### Methodology

1. **Protein Structure Prediction**:
   - **AlphaFold**: AI system utilized for high-accuracy structure predictions of both wild-type and mutant MDH in Microsoft Azure VM. 
   - **Rosetta**: Monte Carlo Method- based program for ab initio structure predictions concurrently queried in Ubuntu VM Linux screens. 

2. **Structure Visualization**:
   - **PyMol**: Used to visualize .pdb models generated from structure prediction programs. Compared to RCSB PDB crystal structure.
   - 
3. **Docking Simulations**:
   - **AutoDock Vina**: Conducted docking simulations to assess binding interactions of different MDH structures (wt vs. mutant) with oxaloacetate at three arginine residues. 

### Results

- **AlphaFold**: Successfully predicted MDH structures with high accuracy, demonstrating its robustness in structural prediction.
- **Rosetta**: Encountered difficulties in generating viable models, highlighting the limitations of this approach.
- **Docking Simulations**: Revealed increased affinity of the mutant MDH for oxaloacetate, with significant structural deviations from the optimal binding formation.

### Conclusion

The study presents the potential and limitations of current computational modeling tools. While AlphaFold provided accurate structural predictions, Rosetta's challenges suggest the need for further refinement or tailoring. AutoDock simulations offered valuable insights into the mutation's impact on substrate interactions, emphasizing the importance of experimental validation to confirm computational findings.

## Files

- **MDH Senior Thesis Paper.pdf**: The final version of the thesis paper detailing the entire study, including background, methodology, results, and conclusions.
- **MDH Research Notebook.pdf**: The research notebook documenting the experimental setup, procedures, data collection, and intermediate analyses conducted during the study.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
