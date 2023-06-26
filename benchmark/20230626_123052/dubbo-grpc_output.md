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
# Warmup Iteration   1: 4.965 ops/ms
# Warmup Iteration   2: 9.152 ops/ms
# Warmup Iteration   3: 10.123 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.657 ops/ms
Iteration   3: 10.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.516 ±(99.9%) 2.724 ops/ms [Average]
  (min, avg, max) = (10.360, 10.516, 10.657), stdev = 0.149
  CI (99.9%): [7.792, 13.240] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ops/ms
# Warmup Iteration   2: 10.754 ops/ms
# Warmup Iteration   3: 10.817 ops/ms
Iteration   1: 10.964 ops/ms
Iteration   2: 11.099 ops/ms
Iteration   3: 10.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.016 ±(99.9%) 1.328 ops/ms [Average]
  (min, avg, max) = (10.964, 11.016, 11.099), stdev = 0.073
  CI (99.9%): [9.688, 12.344] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.454 ops/ms
# Warmup Iteration   2: 10.078 ops/ms
# Warmup Iteration   3: 10.603 ops/ms
Iteration   1: 10.589 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.499 ±(99.9%) 1.793 ops/ms [Average]
  (min, avg, max) = (10.394, 10.499, 10.589), stdev = 0.098
  CI (99.9%): [8.706, 12.293] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.578 ops/ms
# Warmup Iteration   2: 7.987 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.638 ops/ms
Iteration   3: 8.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.436 ±(99.9%) 3.217 ops/ms [Average]
  (min, avg, max) = (8.313, 8.436, 8.638), stdev = 0.176
  CI (99.9%): [5.219, 11.653] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.006 ±(99.9%) 0.004 ms/op
Iteration   3: 3.030 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (3.006, 3.024, 3.035), stdev = 0.016
  CI (99.9%): [2.739, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 2.938 ±(99.9%) 0.003 ms/op
Iteration   2: 2.969 ±(99.9%) 0.004 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (2.909, 2.939, 2.969), stdev = 0.030
  CI (99.9%): [2.391, 3.487] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.003 ms/op
Iteration   2: 2.988 ±(99.9%) 0.004 ms/op
Iteration   3: 3.028 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.988, 3.008, 3.028), stdev = 0.020
  CI (99.9%): [2.649, 3.368] (assumes normal distribution)


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
# Warmup Iteration   1: 5.549 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.012 ms/op
Iteration   1: 3.926 ±(99.9%) 0.043 ms/op
Iteration   2: 3.939 ±(99.9%) 0.014 ms/op
Iteration   3: 3.874 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.913 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.874, 3.913, 3.939), stdev = 0.035
  CI (99.9%): [3.283, 4.544] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.759 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.378 ms/op
                 createUser·p0.9999: 25.053 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.384 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.729 ms/op
                 createUser·p0.9999: 18.105 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314459
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24678 
    [ 2.500,  5.000) = 288404 
    [ 5.000,  7.500) = 1099 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     22.694 ms/op
     p(99.9990) =     25.353 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.007 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.353 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.168 ms/op
                 existUser·p0.9999: 11.785 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.929 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  5.999 ms/op
                 existUser·p0.9999: 12.766 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   3: 2.937 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.180 ms/op
                 existUser·p0.9999: 25.595 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327101
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31766 
    [ 2.500,  5.000) = 294265 
    [ 5.000,  7.500) = 802 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     14.229 ms/op
     p(99.9990) =     25.747 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.420 ms/op
                 getUser·p0.9999: 12.490 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.546 ms/op
                 getUser·p0.9999: 23.283 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.705 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.017 ms/op
                 getUser·p0.9999: 17.236 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316242
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26139 
    [ 2.500,  5.000) = 288617 
    [ 5.000,  7.500) = 1175 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.467 ms/op
     p(99.9900) =     22.450 ms/op
     p(99.9990) =     23.489 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.769 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.388 ms/op
                 listUser·p0.9999: 19.318 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.362 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 21.687 ms/op
                 listUser·p1.00:   23.462 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 20.803 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247772
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4307 
    [ 2.500,  5.000) = 223924 
    [ 5.000,  7.500) = 18468 
    [ 7.500, 10.000) = 605 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     21.012 ms/op
     p(99.9990) =     23.398 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.516 ± 2.724  ops/ms
ClientGrpc.existUser                       thrpt       3  11.016 ± 1.328  ops/ms
ClientGrpc.getUser                         thrpt       3  10.499 ± 1.793  ops/ms
ClientGrpc.listUser                        thrpt       3   8.436 ± 3.217  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.285   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 0.548   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.359   ms/op
ClientGrpc.listUser                         avgt       3   3.913 ± 0.630   ms/op
ClientGrpc.createUser                     sample  314459   3.051 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.307           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.694           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.494           ms/op
ClientGrpc.existUser                      sample  327101   2.933 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.443           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.229           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  316242   3.035 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.547           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.467           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.450           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.560           ms/op
ClientGrpc.listUser                       sample  247772   3.876 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.362           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.012           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.462           ms/op
