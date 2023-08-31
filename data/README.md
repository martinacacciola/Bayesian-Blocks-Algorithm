The algorithm employs a "Piecewise Constant Model": it consists in dividing the range of the independent variable (i.e. time) into `blocks` of variable size, gapless and non-overlapping. A block holds 1 to N data points, with the sum of block contents equaling N. The intensity is modeled as constant within each block, containing consecutive data elements satisfying some well-defined criterion. The optimal segmentation maximizes a quantitative expression of this criterion.

Three main data types are considered:

1. **Events (TTE)**: Time of measurements.
2. **Binned Events**: Event counts in time bins.
3. **Point Measurements**: Continuous observations at sequential time points.

