## Overview

This repository contains the results for my M.S. in Computer Science Thesis. All results were collected via usage of the CLI tool, `cryptoguard`, that I developed as a part of my Thesis. This tool can be found [here](https://github.com/jnaizer/cryptoguard).

## Results
The statistical testing suites used are:

1. **ENT**
2. **PractRand**
3. **SmallCrush (TestU01)**
4. **Crush (TestU01)**
5. **Alphabit (TestU01)**
6. **Rabbit (TestU01)**
7. **Dieharder**
8. **NIST STS**

All statistical testing results are stored in the `results` folder.

#### Results Folder Structure

The `results` folder contains three subfolders, one for each RNG. Each subfolder contains ten subfolders for each of the ten 10Gbit samples of data. Each sample subfolder contains statistical testing output from each test as well as a `time` file that has runtimes for all tests.
```bash
results/
│
├── secrets_rng_results/
│ ├── secrets_0
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
│ ├── ...
│ └── secrets_9
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
│
├── wolfram_rng_results/
│ ├── wolfram_0
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
│ ├── ...
│ └── wolfram_9
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
│
└── sparse_rng_results/
│ ├── sparse_0
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
│ ├── ...
│ └── sparse_9
│ │ ├── test_ent.log
│ │ ├── test_practrand.log
│ │ ├── ...
│ │ └── time
```
