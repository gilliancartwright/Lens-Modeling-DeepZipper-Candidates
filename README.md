# Summer 2022 Undergraduate Research Project - Lens Modeling of Strongly Lensed Supernovae Candidates
Using `lenstronomy` to find lens models for two of the three strongly lensed supernovae candidates found by `ZipperNet` (see [DeepZipper II: Searching for Lensed Supernovae in Dark Energy Survey Data with Deep Learning](https://arxiv.org/abs/2204.05924)) (Morgan et al. 2022).

![](https://github.com/gilliancartwright/summerproject/blob/main/Interactive/interactiveLensModel.gif)

*Selection Tool Demonstration*

## Example Notebooks & Procedure:
* [Procedure:](https://github.com/gilliancartwright/summerproject/tree/main/Lens%20Modeling/Lens%20Modeling%20Procedure)
  * [Step 1: Measurements](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%201%2C%20Measurements.ipynb)
  * [Step 2: Simulating Data](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%202%2C%20Simulating%20Data.ipynb)
  * [Step 3: Make the Model](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%203%2C%20Make%20the%20Model.ipynb)
  * [Step 4: Test the Model](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%204%2C%20Test%20the%20Model.ipynb)
  * [Step 5: Modeling Real Data](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%205%2C%20Modeling%20Real%20Data.ipynb)
  * [Step 6: Troubleshooting](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/Lens%20Modeling%20Procedure/Step%206%2C%20Troubleshooting%20Your%20Model.ipynb)
* [Background Root Mean Square Calculator](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/background_rms.ipynb)
* [Flux Ratio Simulation and Model](https://github.com/gilliancartwright/summerproject/blob/main/Flux%20Ratio%20Fitting/Flux%20Ratio%20Simulation.ipynb)


## Interactive Tools & GIFs:
![](https://github.com/gilliancartwright/summerproject/blob/main/GIFs/Moving_Source.gif)

* [Movable-Source Simulation](https://github.com/gilliancartwright/summerproject/blob/main/Interactive/Click_to_move_source_lenstronomy_simulation.ipynb): A tool for visualizing different geometries of strongly lensed systems using the singular isothermal ellipse mass model. Click on either the simulated image or the lens model plot to move the source position and see how the image positions change.
* [Selection Tool & Lens Model](https://github.com/gilliancartwright/summerproject/blob/main/Interactive/Interactive_Lenstronomy_Lens_Modeling.ipynb): This tool allows you to select everything you need for lens modeling of point sources in an interactive image of your data. Selector tools include: background selector, lens position selector, up to four image position selectors, and up to two mask selectors. Press 't' to save your selections, and you are set to run your lens model!
* [Lenstronomy Simulation GIF Creator](https://github.com/gilliancartwright/summerproject/blob/main/GIFs/Create%20GIF%20(move%20source%20position).ipynb): Create GIFs using simulations. This specific example creates a GIF to show what happens to the images as the source position moves through the caustics.


## Results:
***Final results are still in progress.***

Current results can be found [here](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/DES_Candidates_Model_FINAL.ipynb) for the single lens models or [here](https://github.com/gilliancartwright/summerproject/blob/main/Lens%20Modeling/DES_Candidates_Multiple_lenses.ipynb) for the double lens models.

## Acknowledgements & Packages
Thank you to Jimena González (@JimenaGonzalez) and Professor Keith Bechtol at the University of Wisconsin -- Madison for all of your support in this project. Also, thank you to Simon Birrer (@sibirrer) and Anowar Shajib (@ajshajib) for your expertise and guidance in the lens modeling process.

Thank you to Robert Morgan (@rmorgan10) for finding the strongly lensed supernovae candidates and providing the data. See [DeepZipper: A Novel Deep Learning Architecture for Lensed Supernovae Identification](https://arxiv.org/abs/2112.01541) (Morgan et al. 2022) and [DeepZipperII: Searching for Lensed Supernovae in Dark Energy Survey Data with Deep Learning](https://arxiv.org/abs/2204.05924) (Morgan et al. 2021).

***Packages:***
* `lenstronomy`: "`lenstronomy` is a multi-purpose software package to model strong gravitational lenses." -- [read the docs here](https://lenstronomy.readthedocs.io/en/latest/index.html)
