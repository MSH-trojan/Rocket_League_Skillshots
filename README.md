# Rocket_League_Skillshots
Machine learning analysis and modeling of the Rocket League Skillshots dataset using Python and scikit-learn.

## Dataset overview
- The dataset contains multivariate time-series traces of Rocket League mechanics.
- The first line contains the names of the 18 features.
- Sequences are variable-length and are not sampled at regular time intervals.
- The target label is `class_number`.

### Variable format
Each sequence follows this pattern:
- `class_number`
- `BallAcceleration_1, Time_1, ..., jump_1`
- `BallAcceleration_2, Time_2, ..., jump_2`
- `...`
- `BallAcceleration_n, Time_n, ..., jump_n`
- `class_number`

### Class labels
There are 7 classes in total:
- `-1`: noise (failed figures and random moves)
- `1`: ceiling shot
- `2`: power shot
- `3`: waving dash
- `5`: air dribble
- `6`: front flick
- `7`: musty flick

## Citation
R. Mathonat. "Rocket League Skillshots," UCI Machine Learning Repository, 2020. [Online]. Available: https://doi.org/10.24432/C5S035.
