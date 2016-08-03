# SchumakerSpline
A Julia package to create a shape preserving spline. This is guaranteed to be monotonic and concave or convex if the data is monotonic and concave or convex. It does not use any optimisation and is therefore quick and smoothly converges to a fixed point in economic dynamics problems including value function iteration. It also automatically gives the first two derivatives 
of the spline and options for determining behaviour when evaluated outside the interpolation domain.

This package has the same functionality as the R package called [schumaker](https://cran.r-project.org/web/packages/schumaker/index.html).