[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# [Platoon Optimization based on Truck Pairs](https://doi.org/10.1287/ijoc.2020.0302)

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper 
'Platoon Optimization based on Truck Pairs' (https://doi.org/10.1287/ijoc.2020.0302) by A. K. Bhoopalam, N. Agatz, and R. Zuidwijk.
 
## Cite

To cite the contents of this repository, please cite both the paper and this repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2020.0302

https://doi.org/10.1287/ijoc.2020.0302.cd

Below is the BibTex for citing this snapshot of the respoitory.

```
@article{bhoopalam2023platooning,
  author =        {Bhoopalam, Anirudh Kishore and Agatz, Niels and Zuidwijk, Rob},
  publisher =     {INFORMS Journal on Computing},
  title =         {{Platoon Optimization based on Truck Pairs}},
  year =          {2023},
  doi =           {10.1287/ijoc.2020.0302.cd},
  url =           {https://github.com/INFORMSJoC/2020.0302},
}  
```

## Description

Truck platooning technology allows trucks to drive at short headways to save fuel and associated emissions. However, fuel savings from platooning are relatively small so forming platoons should be convenient and associated with minimum detours and delays. In this paper, we focus on developing optimization technology to form truck platoons. We formulate a mathematical program for the platoon routing problem with time windows (PRP-TW) based on a time-space network. We provide polynomial time algorithms to solve special cases of PRP-TW with two-truck platoons. Based on these special cases, we build several fast heuristics. An extensive set of numerical experiments show that our heuristics perform well. Moreover, we show that simple two-truck platoons already capture most of the potential savings of platooning. 

This repository contains the data and results.

## Data
The data folder contains the raw data used for generating the results. 

The city list and link list csv files include data on the Dutch network

The three subfolders correspond to the three sets of instances used. Each folder has two types of .npy (python numpy) files. deptimes_x_y.npy contains the departure times of the x trucks in instance number y. ODdata_x_y.npy contains the origins and destinations of the x trucks in instance number y. The origins and destinations are labelled based on the node id (see city list and link list csv files)

## Results

The results folder contains all results and figures presented in the paper. 
