+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

# Order that this section will appear in.
weight = 20

+++
## L0Learn: A Fast Toolkit for Best Subset Selection

L0Learn fits regularization paths for L0-regularized regression. Specifically, it can solve the following class of problems for $q \in \\{1,2 \\}$: $$ \\min_{\beta} \frac{1}{2} || y - X \beta ||^2 + \lambda ||\beta||\_0 + \gamma||\beta||\_q^q,$$ over a grid of $\lambda$ and $\gamma$ values. Path-wise optimization can be done using either cyclic coordinate descent or local combinatorial search. The core of the toolkit is implemented in C++ and employs many computational tricks and heuristics, leading to very competitive running times compared to popular solvers for the Lasso.

We provide an easy-to-use R interface for L0Learn. For more information on installation and usage, please check [L0Learn's Vignette](http://www.mit.edu/~hazimeh/L0Learn-vignette.html).
