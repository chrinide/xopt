
# XOPT - an eXternal OPTimizer

## Purpose
The goal is to proving a robust optimizer for quantum chemical and semi-empirical method
that is suitable for large and complex molecules.

## Manual
Online documentation is unfinished. Check `Manual.pdf` for a somewhat recent version. Execute `xopt -h` for command line options.
[![Documentation Status](https://readthedocs.org/projects/xopt/badge/?version=latest)](http://xopt.readthedocs.io/en/latest/?badge=latest)

## customatization
getgrad.f90 contains most of the system calls which might need adaption to your work environment.
Most system calls can also be set in `$HOME/.xoptrc`. 

## Notes/Versions
The current version (2.0 beta) is under continuous development and no warranty for correctness can be given.

The legacy version (v1.0.1) is published in H. Kruse, J. Sponer PCCP, 2015,17, 1399-1410. 

## Capabilities

Coordinate systems:
- approx. normal coordinates
- cartesian "
- internal primitive "

Hessian Updates:
- modified SG1-BFGS
- ...

Step determination:
- RFO
- SI-RFO
- conj. gradient (cg)
- RFO-cg mixture

Interfaces:
- Turbomole
- ORCA
- Amber
- mopac
- 

Constraints/Restraints:
- cartesian space constraints
- restrained primititves (form: U(x)=k(x)^2, x=bond/angle/torsion deviation)





