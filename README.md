# ImageProcessing_FabricDefectDetection

This code block performs the alignment of time series between a reference dataset and a target dataset and visualizes the results.
Firstly, both datasets are normalized. Normalization involves subtracting the mean value of each dataset and dividing by the standard deviation.
This ensures that both datasets are on a similar scale, leading to more accurate alignment results.
Next, the target dataset is aligned to the reference dataset using a time series alignment method called "Dynamic Time Warping" (DTW). 
DTW utilizes a dynamic programming approach to align two time series, taking into account differences and constraints in their time scales. 
This allows for accurate alignments even when the time series progress at different speeds.

![DTW](https://github.com/ozlemkayikcii/ImageProcessing_FabricDefectDetection/assets/84348306/0d9d4b82-ce1c-4752-add2-1909f0c23e76)

Finally, the aligned data is visualized. Using a graphic library called "Matplotlib," the reference data and the aligned data are plotted separately. 
Additionally, lines representing the matches between the two time series are drawn to visualize the path created during the alignment process.
This code block can be particularly useful in cases where time series need to be aligned or their similarities measured. 
For example, it can be used for comparing different segments of a person's speech or different recordings of a music piece.

![TASK2](https://github.com/ozlemkayikcii/ImageProcessing_FabricDefectDetection/assets/84348306/3366e315-1835-4ced-94b3-009d89c7dafc)
