# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ops/ms
# Warmup Iteration   2: 9.194 ops/ms
# Warmup Iteration   3: 10.277 ops/ms
Iteration   1: 10.470 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.551 ±(99.9%) 1.292 ops/ms [Average]
  (min, avg, max) = (10.470, 10.551, 10.598), stdev = 0.071
  CI (99.9%): [9.259, 11.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.947 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 11.251 ops/ms
Iteration   1: 11.264 ops/ms
Iteration   2: 11.201 ops/ms
Iteration   3: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.199 ±(99.9%) 1.211 ops/ms [Average]
  (min, avg, max) = (11.131, 11.199, 11.264), stdev = 0.066
  CI (99.9%): [9.988, 12.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.570 ops/ms
# Warmup Iteration   2: 10.113 ops/ms
# Warmup Iteration   3: 10.564 ops/ms
Iteration   1: 10.726 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.682 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (10.631, 10.682, 10.726), stdev = 0.048
  CI (99.9%): [9.810, 11.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.192 ops/ms
# Warmup Iteration   2: 7.886 ops/ms
# Warmup Iteration   3: 8.123 ops/ms
Iteration   1: 8.112 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.147 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (8.104, 8.147, 8.223), stdev = 0.066
  CI (99.9%): [6.937, 9.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.003 ms/op
Iteration   2: 2.992 ±(99.9%) 0.017 ms/op
Iteration   3: 3.028 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.012 ±(99.9%) 0.336 ms/op [Average]
  (min, avg, max) = (2.992, 3.012, 3.028), stdev = 0.018
  CI (99.9%): [2.677, 3.348] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.003 ms/op
Iteration   1: 2.898 ±(99.9%) 0.003 ms/op
Iteration   2: 2.836 ±(99.9%) 0.003 ms/op
Iteration   3: 2.836 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.857 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (2.836, 2.857, 2.898), stdev = 0.036
  CI (99.9%): [2.202, 3.511] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 3.003 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.991, 3.008, 3.031), stdev = 0.021
  CI (99.9%): [2.633, 3.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.017 ms/op
Iteration   1: 3.979 ±(99.9%) 0.068 ms/op
Iteration   2: 3.957 ±(99.9%) 0.012 ms/op
Iteration   3: 3.834 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.923 ±(99.9%) 1.434 ms/op [Average]
  (min, avg, max) = (3.834, 3.923, 3.979), stdev = 0.079
  CI (99.9%): [2.489, 5.358] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  10.399 ms/op
                 createUser·p0.9999: 17.386 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  10.705 ms/op
                 createUser·p0.9999: 15.754 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  8.572 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312450
  mean =      3.071 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22171 
    [ 2.500,  5.000) = 288041 
    [ 5.000,  7.500) = 1546 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.324 ms/op
     p(99.9900) =     25.560 ms/op
     p(99.9990) =     26.931 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.685 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.139 ms/op
                 existUser·p0.9999: 15.217 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  7.619 ms/op
                 existUser·p0.9999: 13.518 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   3: 2.955 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.605 ms/op
                 existUser·p0.9999: 26.521 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325177
  mean =      2.952 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36461 
    [ 2.500,  5.000) = 286630 
    [ 5.000,  7.500) = 1702 
    [ 7.500, 10.000) = 224 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.748 ms/op
     p(99.9900) =     21.495 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.005 ms/op
Iteration   1: 3.031 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.403 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  9.879 ms/op
                 getUser·p0.9999: 14.620 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.812 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.670 ms/op
                 getUser·p0.9999: 16.646 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315362
  mean =      3.043 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1057 
    [ 1.250,  2.500) = 22696 
    [ 2.500,  3.750) = 272724 
    [ 3.750,  5.000) = 16926 
    [ 5.000,  6.250) = 918 
    [ 6.250,  7.500) = 543 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.263 ms/op
     p(99.9900) =     15.923 ms/op
     p(99.9990) =     18.252 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.555 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.441 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.333 ms/op

Iteration   2: 3.978 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.020 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 22.936 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 3.936 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.578 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.826 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 22.831 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241090
  mean =      3.983 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4991 
    [ 2.500,  5.000) = 210354 
    [ 5.000,  7.500) = 24238 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     22.832 ms/op
     p(99.9990) =     23.416 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.551 ± 1.292  ops/ms
ClientGrpc.existUser                       thrpt       3  11.199 ± 1.211  ops/ms
ClientGrpc.getUser                         thrpt       3  10.682 ± 0.872  ops/ms
ClientGrpc.listUser                        thrpt       3   8.147 ± 1.210  ops/ms
ClientGrpc.createUser                       avgt       3   3.012 ± 0.336   ms/op
ClientGrpc.existUser                        avgt       3   2.857 ± 0.655   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.375   ms/op
ClientGrpc.listUser                         avgt       3   3.923 ± 1.434   ms/op
ClientGrpc.createUser                     sample  312450   3.071 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.693           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.324           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.560           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  325177   2.952 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.555           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.748           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.495           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.001           ms/op
ClientGrpc.getUser                        sample  315362   3.043 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.403           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.263           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.923           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.317           ms/op
ClientGrpc.listUser                       sample  241090   3.983 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.578           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.155           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.832           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
