# Data

No data is stored in this repository.

## Boston

Included in the `MASS` R package. `boston.R` loads it with `data(Boston)`, so you don't need to download anything.

## Communities and Crime

1. Download `communities.data` from the UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/183/communities+and+crime
2. Put it in this folder, so the path is `data/communities.data`

The file has no header row and uses `?` for missing values. It has 1,994 rows and 128 columns: 5 identifiers, 122 socioeconomic and policing variables, and the response `ViolentCrimesPerPop` in the last column. All numeric values are already scaled to the range 0 to 1.

Dataset by Michael Redmond, licensed under CC BY 4.0.
