
<!-- README.md is generated from README.Rmd. Please edit that file -->

# NewPointsSampling

<!-- badges: start -->
<!-- badges: end -->

The goal of NewPointsSampling is to generate a new ranking of new points
for the next field season, based on points that have already been
sampled, from `220113_MFD_allsoil.csv` in order to do that we will
measure the environmental distance from this dataset to potential new
points.

Currently we have 6,818 sampled points, and we will rank the next 5000
points using by getting the most distant points in environmental space
recursevily
