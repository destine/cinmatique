# Cinématique

## Group members

cs184-ad Jonathan Ting
cs184-cn Destine Lee

## Supported Platforms

Mac OS X 10.9.5

## Instructions for Execution

$ make
$ ./as4 <file>

We provided a sample input file which can be run using "./as4 input.txt".

## Input Format:

### Flags
- -arm [joint/]length ... (joint types, pm for prismatic, pn for pin, ba for ball)
    Note: prismatic and pin joints are unimplemented.
- -path a b (where a and b are coefficients defining the surface described by equation z = ax^3 + by^3)
- -cir r (where r is the radius of the cross-section of a vertical cylinder centered at the origin)
- -ell a b (where 

The resulting path is the intersection of the cubic surface and the volume specified by the cir or ell flags.
