# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 10.023 ops/ms
Iteration   1: 10.502 ops/ms
Iteration   2: 10.399 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.492 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.399, 10.492, 10.576), stdev = 0.089
  CI (99.9%): [8.867, 12.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.485 ops/ms
# Warmup Iteration   2: 10.611 ops/ms
# Warmup Iteration   3: 11.052 ops/ms
Iteration   1: 11.002 ops/ms
Iteration   2: 11.133 ops/ms
Iteration   3: 11.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (11.002, 11.095, 11.150), stdev = 0.081
  CI (99.9%): [9.615, 12.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.812 ops/ms
# Warmup Iteration   2: 9.977 ops/ms
# Warmup Iteration   3: 10.546 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.562 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (10.484, 10.562, 10.691), stdev = 0.112
  CI (99.9%): [8.517, 12.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.855 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 7.998 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.976 ±(99.9%) 0.816 ops/ms [Average]
  (min, avg, max) = (7.925, 7.976, 8.006), stdev = 0.045
  CI (99.9%): [7.161, 8.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.002 ms/op
Iteration   1: 3.048 ±(99.9%) 0.003 ms/op
Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.005, 3.040, 3.066), stdev = 0.031
  CI (99.9%): [2.466, 3.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.178 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.012 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.936 ±(99.9%) 0.003 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.930 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.925, 2.930, 2.936), stdev = 0.005
  CI (99.9%): [2.836, 3.024] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.001 ms/op
Iteration   2: 3.091 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.083 ±(99.9%) 0.566 ms/op [Average]
  (min, avg, max) = (3.049, 3.083, 3.110), stdev = 0.031
  CI (99.9%): [2.517, 3.650] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.930 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.032 ms/op
Iteration   1: 4.049 ±(99.9%) 0.023 ms/op
Iteration   2: 4.038 ±(99.9%) 0.013 ms/op
Iteration   3: 3.952 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.013 ±(99.9%) 0.974 ms/op [Average]
  (min, avg, max) = (3.952, 4.013, 4.049), stdev = 0.053
  CI (99.9%): [3.039, 4.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.563 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.714 ms/op
                 createUser·p0.999:  8.305 ms/op
                 createUser·p0.9999: 17.619 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.698 ms/op
                 createUser·p0.9999: 15.561 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  6.961 ms/op
                 createUser·p0.9999: 15.992 ms/op
                 createUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312032
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 20691 
    [ 2.500,  3.750) = 268250 
    [ 3.750,  5.000) = 20940 
    [ 5.000,  6.250) = 985 
    [ 6.250,  7.500) = 328 
    [ 7.500,  8.750) = 98 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     16.148 ms/op
     p(99.9990) =     17.887 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.901 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.005 ms/op
Iteration   1: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.508 ms/op
                 existUser·p0.9999: 11.601 ms/op
                 existUser·p1.00:   11.829 ms/op

Iteration   2: 2.933 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   3.973 ms/op
                 existUser·p0.999:  6.438 ms/op
                 existUser·p0.9999: 13.879 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.651 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.524 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  9.457 ms/op
                 existUser·p0.9999: 16.120 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327490
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1234 
    [ 1.250,  2.500) = 31853 
    [ 2.500,  3.750) = 285287 
    [ 3.750,  5.000) = 8321 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     15.131 ms/op
     p(99.9990) =     16.598 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.070 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.197 ms/op
                 getUser·p0.9999: 12.931 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.275 ms/op
                 getUser·p0.9999: 21.563 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.029 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.343 ms/op
                 getUser·p0.9999: 27.390 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314533
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20769 
    [ 2.500,  5.000) = 292220 
    [ 5.000,  7.500) = 1286 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     26.322 ms/op
     p(99.9990) =     27.670 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.631 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.010 ms/op
Iteration   1: 4.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.783 ms/op
                 listUser·p0.9999: 14.107 ms/op
                 listUser·p1.00:   14.402 ms/op

Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.816 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.251 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239090
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1716 
    [ 2.500,  5.000) = 218088 
    [ 5.000,  7.500) = 18262 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     19.762 ms/op
     p(99.9990) =     21.969 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.492 ± 1.625  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 1.479  ops/ms
ClientGrpc.getUser                         thrpt       3  10.562 ± 2.045  ops/ms
ClientGrpc.listUser                        thrpt       3   7.976 ± 0.816  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.574   ms/op
ClientGrpc.existUser                        avgt       3   2.930 ± 0.094   ms/op
ClientGrpc.getUser                          avgt       3   3.083 ± 0.566   ms/op
ClientGrpc.listUser                         avgt       3   4.013 ± 0.974   ms/op
ClientGrpc.createUser                     sample  312032   3.075 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.563           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.645           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.148           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.990           ms/op
ClientGrpc.existUser                      sample  327490   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.651           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.129           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.131           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.695           ms/op
ClientGrpc.getUser                        sample  314533   3.051 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.616           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.037           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.322           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.803           ms/op
ClientGrpc.listUser                       sample  239090   4.015 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.762           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
