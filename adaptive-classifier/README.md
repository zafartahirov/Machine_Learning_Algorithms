# Adaptive Classifier

This is an algorithm designed specifically with low-power electronics in mind, in particular mobile and embedded systes. Note that the current implementation is just a simulation of the real algorithm -- in reality it is supposed to be implemented in pure hardware (ASIC or FPGA).

## Abstract
Adaptive classifier leverages the wide variability in data complexity to enable energy-efficient data classification operations for mobile systems. It takes advantage of varying classification “hardness” across data to dynamically allocate resources and improve energy efficiency. 

[Paper](http://people.bu.edu/joshi/files/Takhirov-ISLPED-2016.pdf)

## Demo
To demo just run

```bash
$ ./adaptivec.py
```

## Notes

- The change in utilization is only supported in LinearSVC and Linear Regression in the current version

## TODO:

- Utilization support for other classifiers
- Demo needs to be more visual
- Reporting of the scores


## Collaborators

- Marcia S. Louis
- Joseph Wang
- Venkatesh Saligrama
- Ajay Joshi
