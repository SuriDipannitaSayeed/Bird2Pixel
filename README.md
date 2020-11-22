# Bird2Pixel

![alt text](https://github.com/SuriDipannitaSayeed/Bird2Pixel/blob/main/plot.png)

Running instructions:
1. run the first 2 cells in Bird2pixel.ipynb file

2.After creating the directories unzip the anchor.zip and candidate.zip files  put the sample anchor and candidate files in respective directories.
3. run the cell 3 and 4 to get the clusters.
4. after getting the clusters manually scrutinize the number of false positives and false negatives to calculate this values.
precision =TP/TP +FP , recall =TP/TP +FN, F_1 = 2∗(Recall∗Precision)/(Recall+Precision)
5.run cell 5 to see the k means result.
6. For updateing: The given example is for 8 cluster on 40 samples. Any number of samples and clusters can be generated just need to create the cluste rdirectories in colab environment and add the anchor candidate files in respective folders finally add the additianla cluster infor mation in cell 3.
