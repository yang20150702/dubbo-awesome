# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.332 ops/ms
# Warmup Iteration   2: 5.918 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 9.194 ops/ms
Iteration   2: 9.121 ops/ms
Iteration   3: 9.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.263 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (9.121, 9.263, 9.475), stdev = 0.187
  CI (99.9%): [5.859, 12.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.964 ops/ms
# Warmup Iteration   2: 8.530 ops/ms
# Warmup Iteration   3: 9.319 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.460 ops/ms
Iteration   3: 9.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.479 ±(99.9%) 4.408 ops/ms [Average]
  (min, avg, max) = (9.248, 9.479, 9.730), stdev = 0.242
  CI (99.9%): [5.071, 13.888] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.986 ops/ms
# Warmup Iteration   2: 8.437 ops/ms
# Warmup Iteration   3: 9.066 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.522 ops/ms
Iteration   3: 9.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.300 ±(99.9%) 4.840 ops/ms [Average]
  (min, avg, max) = (9.006, 9.300, 9.522), stdev = 0.265
  CI (99.9%): [4.460, 14.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.782 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.760 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 7.994 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.987 ±(99.9%) 0.181 ops/ms [Average]
  (min, avg, max) = (7.976, 7.987, 7.994), stdev = 0.010
  CI (99.9%): [7.806, 8.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.949 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.761 ±(99.9%) 0.007 ms/op
Iteration   1: 3.457 ±(99.9%) 0.007 ms/op
Iteration   2: 3.512 ±(99.9%) 0.005 ms/op
Iteration   3: 3.630 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.533 ±(99.9%) 1.607 ms/op [Average]
  (min, avg, max) = (3.457, 3.533, 3.630), stdev = 0.088
  CI (99.9%): [1.926, 5.139] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.432 ±(99.9%) 0.005 ms/op
Iteration   1: 3.311 ±(99.9%) 0.004 ms/op
Iteration   2: 3.312 ±(99.9%) 0.003 ms/op
Iteration   3: 3.413 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.345 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.311, 3.345, 3.413), stdev = 0.058
  CI (99.9%): [2.283, 4.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.291 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.004 ms/op
Iteration   1: 3.473 ±(99.9%) 0.007 ms/op
Iteration   2: 3.451 ±(99.9%) 0.006 ms/op
Iteration   3: 3.371 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.431 ±(99.9%) 0.976 ms/op [Average]
  (min, avg, max) = (3.371, 3.431, 3.473), stdev = 0.054
  CI (99.9%): [2.455, 4.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.094 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.008 ms/op
Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
Iteration   2: 3.908 ±(99.9%) 0.007 ms/op
Iteration   3: 4.001 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.960 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.908, 3.960, 4.001), stdev = 0.047
  CI (99.9%): [3.096, 4.825] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.330 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.011 ms/op
Iteration   1: 3.454 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 23.953 ms/op
                 createUser·p1.00:   24.904 ms/op

Iteration   2: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  23.689 ms/op
                 createUser·p0.9999: 26.957 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.219 ms/op
                 createUser·p0.9999: 27.779 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278241
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5770 
    [ 2.500,  5.000) = 265739 
    [ 5.000,  7.500) = 5644 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 115 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     19.456 ms/op
     p(99.9900) =     27.236 ms/op
     p(99.9990) =     27.958 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.732 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
Iteration   1: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  20.051 ms/op
                 existUser·p0.9999: 23.333 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.500 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  13.527 ms/op
                 existUser·p0.9999: 25.948 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   3: 3.348 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  23.460 ms/op
                 existUser·p0.9999: 31.275 ms/op
                 existUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281495
  mean =      3.408 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2328 
    [ 2.500,  5.000) = 271879 
    [ 5.000,  7.500) = 6020 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     32.233 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.777 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.014 ms/op
Iteration   1: 3.708 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.417 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  21.029 ms/op
                 getUser·p0.9999: 24.064 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.493 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  23.851 ms/op
                 getUser·p0.9999: 26.201 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.351 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 28.957 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273461
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5678 
    [ 2.500,  5.000) = 259535 
    [ 5.000,  7.500) = 7150 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     20.205 ms/op
     p(99.9900) =     27.656 ms/op
     p(99.9990) =     29.720 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.745 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.621 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.014 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  20.866 ms/op
                 listUser·p0.9999: 25.138 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 4.045 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 20.417 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.069 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.152 ms/op
                 listUser·p0.9999: 16.024 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236878
  mean =      4.050 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 227900 
    [ 5.000,  7.500) = 6856 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.294 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.009 ms/op
     p(99.9900) =     23.308 ms/op
     p(99.9990) =     25.285 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.263 ± 3.404  ops/ms
ClientPb.existUser                       thrpt       3   9.479 ± 4.408  ops/ms
ClientPb.getUser                         thrpt       3   9.300 ± 4.840  ops/ms
ClientPb.listUser                        thrpt       3   7.987 ± 0.181  ops/ms
ClientPb.createUser                       avgt       3   3.533 ± 1.607   ms/op
ClientPb.existUser                        avgt       3   3.345 ± 1.062   ms/op
ClientPb.getUser                          avgt       3   3.431 ± 0.976   ms/op
ClientPb.listUser                         avgt       3   3.960 ± 0.865   ms/op
ClientPb.createUser                     sample  278241   3.447 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.025           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.456           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  281495   3.408 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.977           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.252           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.434           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.295           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.506           ms/op
ClientPb.getUser                        sample  273461   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.351           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.656           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  236878   4.050 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.294           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.225           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.009           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.308           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
