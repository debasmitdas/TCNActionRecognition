# Res-TCN for NTURGBD Skeletons dataset
Skeleton based action recognition models with TCN variants for learning interpretable representation.

## Articles
The original BNMW CVPR2017 submission: https://128.84.21.199/abs/1704.04516v1

## Code
- train.py: Contains the keras training routine.
- Models.py: Contains different variants of Res-TCN
- process_skeleton.py: Contains routines for reading in NTURGBD skeleton dataset. This reads in the raw files and creates train/test LMDB files.

