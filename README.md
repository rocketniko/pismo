# π, s'il vous plaît

3.141592653589793238462643383279... Keep calm and π on!

## Overview
This is a collection of algorithms for calculating approximations of the number π.

Implementation is in Rust/Python and published to PyPI.

## Installation

The library is installable through PyPI.

````
pip install pisvp
````
However, this is a source release and requires cargo/rustc to be on your PATH.

## Usage 
````
% pisvp --help
usage: pisvp [-h] [--pi64] [--mc] [--arctan]

A collection of algorithms for calculating the number π

options:
  -h, --help  show this help message and exit

Floating-point computation:
  --pi64      builtin f64 value
  --mc        naive Monte Carlo
  --arctan    Taylor series for arctan

Keep calm and π on!
````
