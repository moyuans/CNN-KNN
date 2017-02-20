# CNN-KNN
for cell counting using CNN with KNN

1. cnn_knn_iteration_optimization contains the program for CNN-KNN model
    1.1 run cnn_knn_iteration.py to see results

2. cnn_knn_da contains the program for common data augmentation methods, along with CNN-KNN model.
    2.1 run cnn_augmentation.py to get common data augmentation methods result compared to CNN     only
    2.2 run cnn_knn_iteration.py to get CNN-KNN for balanced number (need to change some parameters for input size to make it work)
    2.3 run run.py to get CNN-KNN with *10 for confident set (not work well)

3. original_jpeg contains ground-truth frames

4. wells contains boundary of wells from ground-truth frames

5. coordinate contains cell coordinate in ground-truth frame

6. u_jpeg contains unlabelled frames

7. n_wells contain boundary of wells in unlabelled frames
