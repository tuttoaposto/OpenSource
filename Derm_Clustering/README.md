---
title: "Dermatology - PCA and Clustering"
date: 2020-06-26
---

* Aim at understanding the features of different types of dermatology diseases

- Techniques include PCA and K-Means clustering

  1. Screen plot to check importance of principal components, and how much information will be thrown away if use only first 2 -3 PCs to visualize data ![Scree](Results/Derm_ScreePlot.png)

  2. Underlying features for the PC -- are they mostly clinical or histopathological? ![Features](Results/Derm_PC1_Features.png)

  3. 3D scatter plot for K-Means clustering of the first three PCs to entertain human eyes ![3d](Results/Derm_3D_KMeans.png)

  4. Are there better ways to cluster this data? Looks like K-Means is the winner.![compare clustering](Results/Derm_Compare_Clustering.png)

