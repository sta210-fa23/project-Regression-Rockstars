# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, codebook, etc.

The codebook for your data file(s) using the following format.

## Name of data file

| Variable  | Description               |
|:----------|:--------------------------|
| imdb | Score on IMDB (NULL if recently aired) |
| engagement | Number of reviews on IMDB (NULL if very recently aired) |
| run_time | Run time in min |
| network       | Network the TV series takes place in, if it is a movie will use similar grouping as series.name variable |
| monster_amount | The number of monster in the episode |
| caught_character | A categorical variable that takes the value Fred, Daphnie, Velma, Shaggy, and Scooby for the character who caught the villain |
| unmask_character | A categorical variable that takes the value Fred, Daphnie, Velma, Shaggy, and Scooby for the character who unmask the villain |
| capture_character | A categorical variable that takes the value Fred, Daphnie, Velma, Shaggy, and Scooby for the character who captures the villain |
