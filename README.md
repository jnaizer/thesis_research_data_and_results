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

All statistical testing results are stored in their respective RNG folder.

#### Results Folder Structure

Each subfolder contains ten subfolders for each of the ten 10Gbit samples of data. Each sample subfolder contains statistical testing output from each test as well as a `time` file that has runtimes for all respective tests.
```bash
{rng_name}/
│
├── {rng_name}_0
│ ├── test_ent.log
│ ├── test_practrand.log
│ ├── ...
│ └── time
├── ...
└── {rng_name}_9
│ ├── test_ent.log
│ ├── test_practrand.log
│ ├── ...
│ └── time
```
