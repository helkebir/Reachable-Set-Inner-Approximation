# Online Reachable Set Inner Approximation

A small demo for simple reachable set inner approximation in the case of degraded control authority.

## Installation

This demo should work on Python 3.6 or greater, with the same dependencies as outlined in [requirements.txt](requirements.txt):
- numpy
- scipy
- shapely
- matplotlib

In addition, the [exampleDuffingReach.m](exampleDuffingReach.m) script requires MATLAB (or GNU Octave, though only tested on MATLAB R2019b) to run, with [CORA Toolbox](https://tumcps.github.io/CORA/) R2020 installed.

## Usage

You can simply run the [example.py](example.py) file to run a demo that uses the provided `example*.txt` files to show the theory in action. Both the inner approximation and the off-nominal reachable set are plotted.

Further instructions on how to use the functions provided can be found in the internal documentation.

## Further Reading

The theoretical underpinnings for this work are currently under submission under the title 'Online Inner Approximation of the Reachable Set of Nonlinear Systems with Diminished Control Authority.' A preprint version will soon be made available.

<!-- <img title="|f(t, x + xb, u + ub) - f(t, x, u)| <= a(t) * w(|xb|, |ub|) +  b(t)" src="https://render.githubusercontent.com/render/math?math=\Vert f(t, x %2B \bar{x}, u %2B \bar{u}) - f(t, x, u) \Vert \leq a(t) w(\Vert \bar{x} \Vert,\Vert \bar{u} \Vert) %2B b(t)"> -->

## License
[MIT](https://choosealicense.com/licenses/mit/)