# MNIST_GDVB benchmark

This benchmark is collected from [VeriStable](https://github.com/veristable/veristable) paper which is accepted to publish at FSE'24. 

## Motivation

To gain insights into the performance improvements of DNN verification tools we require benchmarks that force the algorithm to search a non-trivial portion of the space of activation patterns. 
It is well-known that SAT problems can be very easy to solve regardless of their size or whether they are satisfiable or unsatisfiable. 
The same is true for DNN verification problems.
The organizers of the first three DNN verifier competitions remark on the need for benchmarks that are "not so easy that every tool can solve all of them" in order to assess verifier performance.

To achieve this we leverage a systematic DNN verification problem generator [GDVB](https://github.com/edwardxu0/GDVB). 
GDVB takes a seed neural network as input and systematically varies a number of architectural parameters, e.g., number of layers, and neurons per layer, to produce a set of DNNs. 
In this experiment, we begin with a single MNIST network with `3` layers, each with `1024` neurons and generate `38` different DNNs that cover combinations of parameter variations. 
We leverage the fact that local robustness properties are a pseudo-canonical form for pre-post condition specifications and use GDVB to generate 16 properties with varying radii and center points. 
Next we run two state-of-the-art verifiers: $\alpha\beta$-CROWN and MN-BaB, for each of the `38 * 16 = 608` combinations of DNN and property with a small timeout of `200` seconds. 
Any problem that could be solved within that timeout was removed from the benchmark as "too easy". 
This resulted in `90` verification problems that not only are more computationally challenging than benchmarks used in other studies, but also exhibit significant architectural diversity. 

## :page_with_curl: Publication

Hai Duong, Dong Xu, ThanhVu Nguyen, Matthew Dwyer. [**Harnessing Neuron Stability to Improve DNN Verification**](https://arxiv.org/pdf/2401.14412.pdf), Foundations of Software Engineering (FSE), 18 pages (to appear), 2024.
```
@misc{duong2024harnessing,
      title={Harnessing Neuron Stability to Improve DNN Verification}, 
      author={Hai Duong and Dong Xu and ThanhVu Nguyen and Matthew B. Dwyer},
      year={2024},
      eprint={2401.14412},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```