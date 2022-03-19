This repository implements the fast and exact structural graph clustering algorithm proposed in our ICDE 2016 paper. If you are using the code, please cite our paper.
<pre>
Lijun Chang, Wei Li, Xuemin Lin, Lu Qin, and Wenjie Zhang,.
<a href="https://lijunchang.github.io/pdf/2016-pscan-icde.pdf">pSCAN: Fast and exact structural graph clustering.</a>
ICDE'16, 2016
</pre>

## Compile the code
```sh
$ make clean
$ make
```

## Run the code
```sh
$ ./pscan {graph_directory} {epsilon} {mu} output[optional]
```

For example,
```sh
$ ./pscan datasets/CA-GrQc 0.2 3 output
```
Note that, the output is stored as ${graph_directory}/result-${epsilon}-${mu}.txt

## Data format
Each graph is represented by two binary files, b_adj.bin and b_degree.bin (e.g. datasets/CA-GrQc/b_adj.bin and datasets/CA-GrQc/b_degree.bin). More details of the data format can be found in [https://lijunchang.github.io/Cohesive_subgraph_book/datasets](https://lijunchang.github.io/Cohesive_subgraph_book/datasets)
