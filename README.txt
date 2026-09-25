## Instructions to Use the Notebook

1. **Restrict the number of counts**  
   Ensure that the number of `counts` used in the notebook does **not exceed 9000**.

2. **Input format for reactions**  
   Each reaction must be provided in its **own `.xlsx` file**.  
   One sample file is included in the repository.  
   The **order of inputs must remain exactly as follows**:

   1. Atomic number of projectile  
   2. Atomic number of target  
   3. Atomic mass of projectile  
   4. Atomic mass of target  
   5. Atomic mass of lighter product  
   6. Atomic mass of heavier product  
   7. Atomic number of lighter product  
   8. Density of target (kg/m³)  
   9. Ionisation potential of target (keV)  
   10. Radius of target (m)  
   11. Input energy of projectile (keV)  
   12. Thickness of target (m)

3. **Running two reactions**  
   To run two reactions, **uncomment the block labeled “Reaction 2:”**,  
   update the filename to the correct `.xlsx` file, and execute the notebook.

4. **Running more reactions**  
   For additional reactions:
   - Copy the entire block for **“Reaction 2:”**  
   - Paste it **before the Plotting block**  
   - Update variable names by replacing the trailing `2` with `3`, `4`, etc.  
   - Rename the corresponding DataFrames accordingly.

5. **Plotting**  
   The final plotting cell visualizes the **output energy of the lighter product vs. reaction angle**.  
   Run this cell **after all reaction blocks have been executed**.

