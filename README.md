# Machine Learning-Assisted Design of Flow Fields for Redox Flow Batteries 
**Shuaibin Wan**<sup>a,1</sup>, **Haoran Jiang**<sup>b,e,1</sup>, **Zixiao Guo**<sup>a</sup>, **Changxiang He**<sup>a</sup>, **Xiongwei Liang**<sup>a</sup>, **Ned Djilali**<sup>c,d,\*</sup>, **Tianshou Zhao**<sup>a,\*</sup> <br/>

<sup>a</sup> Department of Mechanical and Aerospace Engineering, The Hong Kong University of Science and Technology, Clear Water Bay, Kowloon, Hong Kong SAR, China <br/>
<sup>b</sup> Key Laboratory of Efficient Utilization of Low and Medium Grade Energy (MOE), Tianjin University, Tianjin, China <br/>
<sup>c</sup> Department of Mechanical Engineering, University of Victoria, Victoria, BC, Canada <br/>
<sup>d</sup> Institute for Integrated Energy Systems, University of Victoria, Victoria, BC, Canada <br/>
<sup>e</sup> Institute for Advanced Study, The Hong Kong University of Science and Technology, Clear Water Bay, Kowloon, Hong Kong SAR, China <br/>
<sup>\*</sup> Corresponding author: [Prof. T.S. Zhao](https://scholar.google.com/citations?user=0mUWHUQAAAAJ&hl=en), [Prof. N. Djilali](https://scholar.google.ca/citations?user=TcpC3GgAAAAJ&hl=en) <br/>
<sup>1</sup> These authors contributed equally to this work. <br/>

## Abstract
Flow fields are a crucial component of redox flow batteries (RFBs). Conventional flow fields, designed by trial-and-error approaches and limited human intuition, are difficult to optimize, thus limiting the performance of RFBs. Here, we develop an end-to-end approach to the design of flow fields by combining machine learning and experimental methods. A library of 11 564 flow fields is generated using a custom-made path generation algorithm, in which flow fields are elegantly encoded by two-dimensional binary images. To accelerate the discovery process, we train convolutional neural networks with low test errors for predicting the uniformity factor and pressure drop of flow fields (0.59% and 1.37%, respectively). Through a collaborative screening process, eight promising candidates are successfully identified. Experimental validation shows that the battery with the flow fields designed with this approach yields higher electrolyte utilization and exhibits about a 22% increase in limiting current density and up to 11% improvement in energy efficiency compared to the conventional serpentine flow field. Furthermore, statistical analysis suggests that the promising candidates have a saved channel length of 1490 ± 100 and a torque integral of 20.1 ± 1.8, revealing the quantitative design rules of flow fields for the first time.

## Workflow
As illustrated in ​Figure 1​, we first develop an end-to-end approach to designing flow fields, encompassing library generation, multi-physics simulation, machine learning, and experimental validation. After exploring 11 564 flow fields, the data-driven search process identifies eight promising candidates. Three of these are fabricated and tested, and experimental results show that the battery with the newly designed flow fields yields exhibits about a 22% increase in limiting current density and up to 11% improvement in energy efficiency compared to the conventional serpentine flow field. The statistical analysis of geometric properties shows that the promising candidates have the saved channel length of 1490 ± 100 and the torque integral of 20.1 ± 1.8, revealing the design rules of flow fields on a quantitative level for the first time. <br/>

![workflow](/docs/workflow.png)
**Figure 1:** Framework of the machine learning-assisted design of flow fields for redox flow batteries.

## Data availability
80 promising candidates selected from the first-round screening can be found via [this link](https://github.com/HarryBinary/RFB_Flow_Field_Design/tree/main/result/promising_candidates_80) <br/>

## Cite as
S. Wan, H. Jiang, Z. Guo, C. He, X. Liang, N. Djilali, and T. Zhao. Energy & Environmental Science, 2022. [[Paper Link](https://doi.org/10.1039/D1EE03224K)] <br/>