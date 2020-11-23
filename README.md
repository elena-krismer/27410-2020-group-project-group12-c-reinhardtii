[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/27410-2020-group-project-group12-c-reinhardtii/main)

# 27410 - Group assignment - Group 12 - Hydrogen production in C. Reinhardtii

> Dear students, thank you for accepting the group assignment. Please fill in the
> requested information below and above ([12] and [Hydrogen production in Chlamydomonas reinhardtii]) and remove this quoted part before submission (everything prepended with a >).
> Please also replace `[PUT-YOUR-REPOSITORY-HERE]` up in the first line 👆 with the name of your repository here on GitHub.
> That way someone can click on the Binder badge icon and open your project in Jupyter lab to explore it.
> For this to work you will also have to keep `requirements.txt` up to date (by running `pip freeze > requirements.txt`).
> Furthermore, this will only work if you decide to make your repository public (which you can do under Settings -> Options),
> which I would encourage you to do – up to you. A lot of good science happens out in the open these days.
> Good luck!

## Project summary (<300 words)

One of the greatest challenges of this century is finding alternative, sustainable and environmentally friendly energy sources. Looking at the possible current solutions, hydrogen is considered an optimal energy source due to its high output energy per unit of mass and its only combustion product H2O. Currently, the production of hydrogen is neither economically efficient nor sustainable, as a huge part of the produced hydrogen comes from fossil fuels. The green microalgae Chlamydomonas reinhardtii is a promising production organism for sustainable hydrogen production, due to efficient solar energy conversion and easy cultivation. However, due to low biomass concentration and costly downstream processes, the production of hydrogen is not economical.

In our project we are using the genome-scale model iCre1355 provided by Imam et al. (2015) to identify cell factory engineering strategies, which potentially improve hydrogen production rates and maximize growth. The methods we applied are:
 - Phenotypic Phase Plane analysis to identify the optimal conditions (photoautotroph, mixotroph or heterotroph)
 - Changing the medium composition to maximize growth 
 - OptKnock to identify targets for gene knock-outs
 - Simulation of a batch cultivation with dFBA
 - [Flux Scanning based on Enforced Objective Flux to identify targets for gene overexpression](https://github.com/27410/27410-2020-group-project-group12-c-reinhardtii/blob/main/reports/Appendices/4.8.%20Flux%20Scanning%20based%20on%20Enforced%20Objective%20Flux%20%26%20Identification%20of%20Potential%20Target%20Genes.ipynb)



## Project overview
Here you will find our [Report](https://github.com/27410/27410-2020-group-project-group12-c-reinhardtii/blob/main/reports/Report.ipynb).
We still need to put all the results in one the final report file (folder: "reports"). Currently our results are spread between several notebooks (folder:"notebooks") to prevent corruption of the final report notebook. Also, we need to delete unnecessary copies of the model. 

You can still find some left-over notebooks in the folder "other targets", from the time before we chose hydrogen as our target compound.

