# Goal: simulation of the CNS paper 
[Gardner, A., & Conlon, J. P. (2013). Cosmological natural selection and the purpose of the universe. *Complexity*, 18(6), 48-56. doi:10.1002/cplx.21446](https://onlinelibrary.wiley.com/doi/10.1002/cplx.21446#cplx21446-bib-0016)


1. **Define Universe Properties**: Determine the set of characteristics (or 'characters') for each universe that influence its ability to produce black holes. These could include parameters linked to fundamental physical constants, matter distribution, and other factors relevant to black hole formation.

2. **Create the Initial Generation of Universes**: Start with a diverse range of universes having different character values. These values could be initialized randomly or based on a set of predefined distributions.

3. **Black Hole Production Function**: Implement a function (similar to $ B(t\_i) $ in the paper) that calculates the number of black holes a universe can produce based on its characteristics. This function represents the universe's 'fitness' and is key to the simulation.

4. **Simulate Evolutionary Dynamics**:
   - **Selection**: Calculate the 'fitness' of each universe in terms of its black hole production.
   - **Transmission**: Determine how characteristics are passed from one generation of universes to the next. This could include variations or 'mutations' in the character values, simulating natural selection and genetic drift.

5. **Optimization Algorithm**: Implement an optimization algorithm that iteratively adjusts the character values to maximize black hole production. This could be based on evolutionary algorithms, gradient ascent, or other optimization techniques.

6. **Generation Progression**: After evaluating and selecting the fittest universes in one generation (those producing the most black holes), use their characteristics as a basis for creating the next generation of universes. This simulates the reproductive aspect of the CNS model.

7. **Data Collection and Analysis**: Throughout the simulation, collect data on the character values, number of black holes produced, and other relevant metrics. This data will help in analyzing the evolutionary trends of the universes over successive generations.

8. **Visualization Tools**: Implement visualization tools to effectively display the evolutionary progress of the universes over time. This could include graphs, heatmaps, or 3D visualizations showing the trajectory of universe evolution in the character space.

9. **Testing and Refinement**: Test the model for different initial conditions and parameters to see how robust the evolutionary process is to changes in the setup. Refine the model based on the outcomes to better understand the dynamics at play.