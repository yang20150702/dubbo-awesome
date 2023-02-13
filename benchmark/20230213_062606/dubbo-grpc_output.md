# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 10.284 ops/ms
Iteration   1: 10.382 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (10.294, 10.389, 10.492), stdev = 0.099
  CI (99.9%): [8.575, 12.204] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.748 ops/ms
# Warmup Iteration   2: 10.546 ops/ms
# Warmup Iteration   3: 10.605 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.740 ±(99.9%) 2.144 ops/ms [Average]
  (min, avg, max) = (10.605, 10.740, 10.818), stdev = 0.118
  CI (99.9%): [8.596, 12.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.449 ops/ms
# Warmup Iteration   2: 10.164 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.597 ±(99.9%) 3.427 ops/ms [Average]
  (min, avg, max) = (10.381, 10.597, 10.727), stdev = 0.188
  CI (99.9%): [7.170, 14.023] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.074 ops/ms
# Warmup Iteration   2: 7.591 ops/ms
# Warmup Iteration   3: 7.853 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.984 ±(99.9%) 0.507 ops/ms [Average]
  (min, avg, max) = (7.953, 7.984, 8.003), stdev = 0.028
  CI (99.9%): [7.477, 8.491] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.109 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.002 ms/op
Iteration   1: 3.226 ±(99.9%) 0.012 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.145 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.146 ±(99.9%) 1.437 ms/op [Average]
  (min, avg, max) = (3.068, 3.146, 3.226), stdev = 0.079
  CI (99.9%): [1.709, 4.583] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.780 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.002 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 2.994 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.990 ±(99.9%) 0.061 ms/op [Average]
  (min, avg, max) = (2.987, 2.990, 2.994), stdev = 0.003
  CI (99.9%): [2.929, 3.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 3.090 ±(99.9%) 0.001 ms/op
Iteration   3: 3.071 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.046, 3.069, 3.090), stdev = 0.022
  CI (99.9%): [2.667, 3.471] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.275 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.033 ms/op
Iteration   1: 4.085 ±(99.9%) 0.034 ms/op
Iteration   2: 4.057 ±(99.9%) 0.020 ms/op
Iteration   3: 4.006 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.049 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (4.006, 4.049, 4.085), stdev = 0.040
  CI (99.9%): [3.321, 4.778] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.997 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.030 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.524 ms/op
                 createUser·p0.9999: 20.047 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.367 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.971 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  11.341 ms/op
                 createUser·p0.9999: 22.572 ms/op
                 createUser·p1.00:   23.822 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307513
  mean =      3.123 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22422 
    [ 2.500,  5.000) = 284123 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.836 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     23.299 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.150 ms/op
                 existUser·p0.9999: 11.201 ms/op
                 existUser·p1.00:   11.436 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.213 ms/op
                 existUser·p0.9999: 17.673 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  5.936 ms/op
                 existUser·p0.9999: 15.868 ms/op
                 existUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318490
  mean =      3.012 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1934 
    [ 1.250,  2.500) = 35148 
    [ 2.500,  3.750) = 258806 
    [ 3.750,  5.000) = 21526 
    [ 5.000,  6.250) = 569 
    [ 6.250,  7.500) = 163 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.655 ms/op
     p(99.9900) =     17.016 ms/op
     p(99.9990) =     18.174 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.745 ms/op
                 getUser·p0.9999: 12.038 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.384 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.645 ms/op
                 getUser·p0.9999: 26.425 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312058
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22555 
    [ 2.500,  5.000) = 288628 
    [ 5.000,  7.500) = 613 
    [ 7.500, 10.000) = 25 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.979 ms/op
     p(99.9900) =     23.953 ms/op
     p(99.9990) =     26.829 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.012 ms/op
Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.730 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.801 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 3.865 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  20.615 ms/op
                 listUser·p0.9999: 28.981 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   3: 4.023 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.501 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  15.409 ms/op
                 listUser·p0.9999: 21.597 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241997
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3930 
    [ 2.500,  5.000) = 213935 
    [ 5.000,  7.500) = 22875 
    [ 7.500, 10.000) = 793 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     29.647 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 1.814  ops/ms
ClientGrpc.existUser                       thrpt       3  10.740 ± 2.144  ops/ms
ClientGrpc.getUser                         thrpt       3  10.597 ± 3.427  ops/ms
ClientGrpc.listUser                        thrpt       3   7.984 ± 0.507  ops/ms
ClientGrpc.createUser                       avgt       3   3.146 ± 1.437   ms/op
ClientGrpc.existUser                        avgt       3   2.990 ± 0.061   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.402   ms/op
ClientGrpc.listUser                         avgt       3   4.049 ± 0.729   ms/op
ClientGrpc.createUser                     sample  307513   3.123 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.367           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.836           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.299           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.822           ms/op
ClientGrpc.existUser                      sample  318490   3.012 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.688           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.990           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.655           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.016           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  312058   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.953           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.935           ms/op
ClientGrpc.listUser                       sample  241997   3.967 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.501           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.688           ms/op
