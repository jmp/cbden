# cbden

This is a clustering software that implements a density-based
modification of the random swap algorithm. It is a centroid-based
clustering algorithm that calculates weights for each centroid
based on densities of the clusters. The distances from centroids
to vectors are then calculated as weighted distances.

## Requirements

The CB modules package (http://cs.uef.fi/sipu/soft/modules.zip)
is required for the program to be compiled. See the makefile for
further details.

## Usage

Run the program without parameters, and it will show all the
command-line options. The datasets and possible ground truth
centroids must be given in codebook format (.ts, .cb).
