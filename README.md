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
Different algorithms can be invoked by executing "pscan".
```sh
$ ./pscan {graph_directory} {epsilon} {mu} output[optional]
```
