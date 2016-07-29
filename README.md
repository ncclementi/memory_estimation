# memory_estimation
Estimation on memory needs on GPU to run bigger problems on pygbe.
It was based in memory profiling done with nvprof. The memory profiling option in nvprof is turn off by default, to turn it on and keep track of the gpu trace you have to add the flags: `--unified-memory-profiling off` and `--print-gpu-trace`. 


