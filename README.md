g++ -Wall -std=c++14 benchmark_example.cpp -pthread -lbenchmark -DMEMORY_PROFILER
./a.out --benchmark_format=json
