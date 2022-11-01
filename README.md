Circos
Circos plots are a great way to show genomic data and are famous for their ability to show 
several different data types across dozens of chromosomes in a single plot.

1. we build the basic chromosome ideogram and take the deg file that contains log2 fold change values and p values
2. Intersect deg gene name with biomaRT 'hgnc_symbol' gene name.

Packages used:
1. Rcircos
The RCircos package provides a set of graphic functions which implement basic Circos 2D track plot for visualizing similarities and differences of genome
structure and positional relationships between genomic intervals.

2. biomaRT
The package enables retrieval of large amounts of data in a uniform way without the need to know the underlying database schemas or write complex SQL queries.

Interpretation:
1. Axes for the circular plot are normally drawn on the most outside of the circle.
![image](https://user-images.githubusercontent.com/112052476/199175234-446aa286-9b61-49c4-aa17-9643f7fc1bb9.png)


2. Giving color to the axes.
![image](https://user-images.githubusercontent.com/112052476/199177262-802b70c8-a55a-4135-8050-9d6c5399d5c0.png)


3. To see the number of labels for each chromosome.
![image](https://user-images.githubusercontent.com/112052476/199177555-594f3d59-5428-4588-845e-166be5a3789e.png)


4. Final plot.
![image](https://user-images.githubusercontent.com/112052476/199177942-fb30c08f-9dc5-430c-9eb3-2d9bb7da5abf.png)



