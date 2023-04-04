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
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 5.683 ops/ms
# Warmup Iteration   3: 7.291 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.586 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.753 ±(99.9%) 3.350 ops/ms [Average]
  (min, avg, max) = (7.586, 7.753, 7.949), stdev = 0.184
  CI (99.9%): [4.403, 11.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.914 ops/ms
# Warmup Iteration   2: 7.796 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.318 ops/ms
Iteration   2: 8.450 ops/ms
Iteration   3: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.374 ±(99.9%) 1.246 ops/ms [Average]
  (min, avg, max) = (8.318, 8.374, 8.450), stdev = 0.068
  CI (99.9%): [7.128, 9.620] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.489 ops/ms
# Warmup Iteration   2: 6.897 ops/ms
# Warmup Iteration   3: 7.604 ops/ms
Iteration   1: 7.448 ops/ms
Iteration   2: 7.947 ops/ms
Iteration   3: 7.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.745 ±(99.9%) 4.790 ops/ms [Average]
  (min, avg, max) = (7.448, 7.745, 7.947), stdev = 0.263
  CI (99.9%): [2.955, 12.536] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ops/ms
# Warmup Iteration   2: 5.598 ops/ms
# Warmup Iteration   3: 5.849 ops/ms
Iteration   1: 6.079 ops/ms
Iteration   2: 5.941 ops/ms
Iteration   3: 6.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.021 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (5.941, 6.021, 6.079), stdev = 0.072
  CI (99.9%): [4.708, 7.335] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.279 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.313 ±(99.9%) 0.006 ms/op
Iteration   1: 4.147 ±(99.9%) 0.004 ms/op
Iteration   2: 4.263 ±(99.9%) 0.003 ms/op
Iteration   3: 4.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.190 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (4.147, 4.190, 4.263), stdev = 0.063
  CI (99.9%): [3.041, 5.340] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.021 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.004 ms/op
Iteration   1: 3.957 ±(99.9%) 0.003 ms/op
Iteration   2: 3.916 ±(99.9%) 0.003 ms/op
Iteration   3: 4.036 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.970 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.916, 3.970, 4.036), stdev = 0.061
  CI (99.9%): [2.858, 5.081] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.201 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.214 ±(99.9%) 0.009 ms/op
Iteration   1: 4.001 ±(99.9%) 0.004 ms/op
Iteration   2: 4.142 ±(99.9%) 0.003 ms/op
Iteration   3: 3.962 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.035 ±(99.9%) 1.728 ms/op [Average]
  (min, avg, max) = (3.962, 4.035, 4.142), stdev = 0.095
  CI (99.9%): [2.307, 5.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.759 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.023 ms/op
Iteration   1: 5.309 ±(99.9%) 0.012 ms/op
Iteration   2: 5.284 ±(99.9%) 0.021 ms/op
Iteration   3: 5.333 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.309 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (5.284, 5.309, 5.333), stdev = 0.025
  CI (99.9%): [4.859, 5.758] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.482 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.014 ms/op
Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.153 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.894 ms/op
                 createUser·p0.999:  10.534 ms/op
                 createUser·p0.9999: 16.228 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 4.185 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.825 ms/op
                 createUser·p0.99:   7.823 ms/op
                 createUser·p0.999:  13.861 ms/op
                 createUser·p0.9999: 19.063 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   3: 4.102 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.455 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   8.258 ms/op
                 createUser·p0.999:  12.958 ms/op
                 createUser·p0.9999: 21.258 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233658
  mean =      4.110 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8374 
    [ 2.500,  5.000) = 193951 
    [ 5.000,  7.500) = 28318 
    [ 7.500, 10.000) = 2300 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     19.145 ms/op
     p(99.9990) =     21.790 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.999 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.012 ms/op
Iteration   1: 3.817 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.447 ms/op
                 existUser·p0.999:  12.272 ms/op
                 existUser·p0.9999: 15.313 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   2: 3.736 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.645 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  10.978 ms/op
                 existUser·p0.9999: 18.481 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.889 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.489 ms/op
                 existUser·p0.99:   8.222 ms/op
                 existUser·p0.999:  13.140 ms/op
                 existUser·p0.9999: 19.763 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251672
  mean =      3.813 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9508 
    [ 2.500,  5.000) = 224596 
    [ 5.000,  7.500) = 15086 
    [ 7.500, 10.000) = 1878 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.473 ms/op
     p(99.9000) =     12.752 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     20.133 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.987 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.013 ms/op
Iteration   1: 4.067 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   7.837 ms/op
                 getUser·p0.999:  12.491 ms/op
                 getUser·p0.9999: 16.758 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.865 ms/op
                 getUser·p0.99:   7.860 ms/op
                 getUser·p0.999:  11.881 ms/op
                 getUser·p0.9999: 19.058 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 4.024 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.660 ms/op
                 getUser·p0.999:  15.951 ms/op
                 getUser·p0.9999: 23.465 ms/op
                 getUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 235045
  mean =      4.082 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12592 
    [ 2.500,  5.000) = 191520 
    [ 5.000,  7.500) = 28131 
    [ 7.500, 10.000) = 2159 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     12.648 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     23.722 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 7.783 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.301 ±(99.9%) 0.019 ms/op
Iteration   1: 5.267 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   7.029 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  14.814 ms/op
                 listUser·p0.9999: 21.034 ms/op
                 listUser·p1.00:   24.052 ms/op

Iteration   2: 5.335 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.053 ms/op
                 listUser·p0.95:   8.167 ms/op
                 listUser·p0.99:   10.797 ms/op
                 listUser·p0.999:  22.184 ms/op
                 listUser·p0.9999: 26.477 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   3: 5.233 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.069 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  19.759 ms/op
                 listUser·p0.9999: 23.586 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181878
  mean =      5.278 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 168 
    [ 2.500,  5.000) = 95173 
    [ 5.000,  7.500) = 72755 
    [ 7.500, 10.000) = 11328 
    [10.000, 12.500) = 1813 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.077 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     25.192 ms/op
     p(99.9990) =     26.789 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.753 ± 3.350  ops/ms
ClientGrpc.existUser                       thrpt       3   8.374 ± 1.246  ops/ms
ClientGrpc.getUser                         thrpt       3   7.745 ± 4.790  ops/ms
ClientGrpc.listUser                        thrpt       3   6.021 ± 1.313  ops/ms
ClientGrpc.createUser                       avgt       3   4.190 ± 1.150   ms/op
ClientGrpc.existUser                        avgt       3   3.970 ± 1.112   ms/op
ClientGrpc.getUser                          avgt       3   4.035 ± 1.728   ms/op
ClientGrpc.listUser                         avgt       3   5.309 ± 0.449   ms/op
ClientGrpc.createUser                     sample  233658   4.110 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.455           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.759           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.979           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.567           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.145           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  251672   3.813 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.870           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.752           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.416           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  235045   4.082 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.648           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.955           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.921           ms/op
ClientGrpc.listUser                       sample  181878   5.278 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.933           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.102           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.464           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.192           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.870           ms/op
