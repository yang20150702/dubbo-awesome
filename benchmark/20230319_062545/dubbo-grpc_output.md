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
# Warmup Iteration   1: 4.913 ops/ms
# Warmup Iteration   2: 9.741 ops/ms
# Warmup Iteration   3: 10.536 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.735 ±(99.9%) 3.784 ops/ms [Average]
  (min, avg, max) = (10.606, 10.735, 10.974), stdev = 0.207
  CI (99.9%): [6.951, 14.519] (assumes normal distribution)


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
# Warmup Iteration   1: 8.056 ops/ms
# Warmup Iteration   2: 11.218 ops/ms
# Warmup Iteration   3: 11.577 ops/ms
Iteration   1: 11.511 ops/ms
Iteration   2: 11.716 ops/ms
Iteration   3: 11.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.588 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (11.511, 11.588, 11.716), stdev = 0.112
  CI (99.9%): [9.545, 13.631] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.954 ops/ms
# Warmup Iteration   2: 10.581 ops/ms
# Warmup Iteration   3: 10.949 ops/ms
Iteration   1: 11.037 ops/ms
Iteration   2: 11.018 ops/ms
Iteration   3: 10.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.985 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (10.900, 10.985, 11.037), stdev = 0.074
  CI (99.9%): [9.632, 12.337] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.911 ops/ms
# Warmup Iteration   2: 8.210 ops/ms
# Warmup Iteration   3: 8.320 ops/ms
Iteration   1: 8.368 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.370 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (8.311, 8.370, 8.430), stdev = 0.059
  CI (99.9%): [7.287, 9.452] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.926 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.008 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.900 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.927 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (2.900, 2.927, 2.943), stdev = 0.024
  CI (99.9%): [2.497, 3.357] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.837 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.802 ±(99.9%) 0.003 ms/op
Iteration   2: 2.797 ±(99.9%) 0.004 ms/op
Iteration   3: 2.840 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.813 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.797, 2.813, 2.840), stdev = 0.023
  CI (99.9%): [2.388, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.003 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 2.916 ±(99.9%) 0.002 ms/op
Iteration   3: 2.921 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.935 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.916, 2.935, 2.969), stdev = 0.029
  CI (99.9%): [2.409, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.024 ms/op
Iteration   1: 3.692 ±(99.9%) 0.019 ms/op
Iteration   2: 3.728 ±(99.9%) 0.045 ms/op
Iteration   3: 3.681 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.700 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.681, 3.700, 3.728), stdev = 0.025
  CI (99.9%): [3.247, 4.154] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.315 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.204 ms/op
                 createUser·p0.9999: 12.190 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.239 ms/op
                 createUser·p0.50:   2.875 ms/op
                 createUser·p0.90:   3.293 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.382 ms/op
                 createUser·p0.9999: 12.631 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.379 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  11.019 ms/op
                 createUser·p0.9999: 15.352 ms/op
                 createUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 328495
  mean =      2.924 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1915 
    [ 1.250,  2.500) = 32703 
    [ 2.500,  3.750) = 282842 
    [ 3.750,  5.000) = 9518 
    [ 5.000,  6.250) = 829 
    [ 6.250,  7.500) = 319 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 144 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.239 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     13.688 ms/op
     p(99.9990) =     15.626 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.864 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.829 ±(99.9%) 0.006 ms/op
Iteration   1: 2.733 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.479 ms/op
                 existUser·p0.50:   2.765 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.160 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.567 ms/op

Iteration   2: 2.739 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.113 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 2.774 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.197 ms/op
                 existUser·p0.999:  7.250 ms/op
                 existUser·p0.9999: 15.711 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 349075
  mean =      2.749 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70388 
    [ 2.500,  5.000) = 277742 
    [ 5.000,  7.500) = 646 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.479 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.215 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     17.599 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.888 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.194 ms/op
                 getUser·p0.9999: 11.353 ms/op
                 getUser·p1.00:   11.583 ms/op

Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.559 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.701 ms/op
                 getUser·p0.9999: 12.980 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.523 ms/op
                 getUser·p0.99:   4.183 ms/op
                 getUser·p0.999:  8.086 ms/op
                 getUser·p0.9999: 24.736 ms/op
                 getUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 330217
  mean =      2.907 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37343 
    [ 2.500,  5.000) = 291763 
    [ 5.000,  7.500) = 815 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.107 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     25.025 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.721 ±(99.9%) 0.010 ms/op
Iteration   1: 3.811 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.349 ms/op
                 listUser·p0.999:  12.485 ms/op
                 listUser·p0.9999: 16.928 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.798 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.668 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.431 ms/op
                 listUser·p0.999:  14.690 ms/op
                 listUser·p0.9999: 20.728 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 3.840 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.566 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  16.509 ms/op
                 listUser·p0.9999: 22.031 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251760
  mean =      3.816 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6671 
    [ 2.500,  5.000) = 225726 
    [ 5.000,  7.500) = 18506 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     23.199 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.735 ± 3.784  ops/ms
ClientGrpc.existUser                       thrpt       3  11.588 ± 2.043  ops/ms
ClientGrpc.getUser                         thrpt       3  10.985 ± 1.352  ops/ms
ClientGrpc.listUser                        thrpt       3   8.370 ± 1.083  ops/ms
ClientGrpc.createUser                       avgt       3   2.927 ± 0.430   ms/op
ClientGrpc.existUser                        avgt       3   2.813 ± 0.425   ms/op
ClientGrpc.getUser                          avgt       3   2.935 ± 0.527   ms/op
ClientGrpc.listUser                         avgt       3   3.700 ± 0.454   ms/op
ClientGrpc.createUser                     sample  328495   2.924 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.239           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.900           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.585           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.688           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.696           ms/op
ClientGrpc.existUser                      sample  349075   2.749 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.479           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.785           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.215           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.143           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.599           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  330217   2.907 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.565           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.908           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.107           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.763           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.100           ms/op
ClientGrpc.listUser                       sample  251760   3.816 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.566           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.682           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.369           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.709           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.265           ms/op
