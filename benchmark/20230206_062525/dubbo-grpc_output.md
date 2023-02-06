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
# Warmup Iteration   1: 4.300 ops/ms
# Warmup Iteration   2: 9.316 ops/ms
# Warmup Iteration   3: 10.704 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.289 ±(99.9%) 1.908 ops/ms [Average]
  (min, avg, max) = (10.179, 10.289, 10.387), stdev = 0.105
  CI (99.9%): [8.380, 12.197] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.136 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 11.019 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.990 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.755 ±(99.9%) 3.855 ops/ms [Average]
  (min, avg, max) = (10.581, 10.755, 10.990), stdev = 0.211
  CI (99.9%): [6.900, 14.610] (assumes normal distribution)


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
# Warmup Iteration   1: 7.353 ops/ms
# Warmup Iteration   2: 10.254 ops/ms
# Warmup Iteration   3: 10.170 ops/ms
Iteration   1: 10.467 ops/ms
Iteration   2: 10.332 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.258 ±(99.9%) 4.624 ops/ms [Average]
  (min, avg, max) = (9.976, 10.258, 10.467), stdev = 0.253
  CI (99.9%): [5.634, 14.882] (assumes normal distribution)


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
# Warmup Iteration   1: 6.459 ops/ms
# Warmup Iteration   2: 7.839 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 7.984 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.881 ±(99.9%) 1.629 ops/ms [Average]
  (min, avg, max) = (7.827, 7.881, 7.984), stdev = 0.089
  CI (99.9%): [6.252, 9.509] (assumes normal distribution)


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
# Warmup Iteration   1: 4.197 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.010 ms/op
Iteration   1: 3.090 ±(99.9%) 0.002 ms/op
Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
Iteration   3: 3.205 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.155 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.090, 3.155, 3.205), stdev = 0.059
  CI (99.9%): [2.077, 4.234] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.881 ±(99.9%) 0.004 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
Iteration   2: 2.894 ±(99.9%) 0.004 ms/op
Iteration   3: 2.812 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.880 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (2.812, 2.880, 2.934), stdev = 0.062
  CI (99.9%): [1.743, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.144 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (3.077, 3.144, 3.179), stdev = 0.059
  CI (99.9%): [2.074, 4.214] (assumes normal distribution)


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
# Warmup Iteration   1: 5.372 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.043 ms/op
Iteration   1: 3.874 ±(99.9%) 0.009 ms/op
Iteration   2: 4.139 ±(99.9%) 0.016 ms/op
Iteration   3: 4.077 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.030 ±(99.9%) 2.523 ms/op [Average]
  (min, avg, max) = (3.874, 4.030, 4.139), stdev = 0.138
  CI (99.9%): [1.507, 6.553] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.437 ms/op
                 createUser·p0.999:  10.226 ms/op
                 createUser·p0.9999: 12.434 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.389 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.655 ms/op
                 createUser·p0.9999: 11.846 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 22.905 ms/op
                 createUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306199
  mean =      3.133 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21359 
    [ 2.500,  5.000) = 283527 
    [ 5.000,  7.500) = 687 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.220 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
Iteration   1: 2.996 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.439 ms/op
                 existUser·p0.9999: 20.949 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.422 ms/op
                 existUser·p0.9999: 20.293 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  9.665 ms/op
                 existUser·p0.9999: 15.773 ms/op
                 existUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320957
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35791 
    [ 2.500,  5.000) = 283779 
    [ 5.000,  7.500) = 1122 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.889 ms/op
     p(99.9900) =     20.346 ms/op
     p(99.9990) =     21.161 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.076 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.080 ms/op
                 getUser·p0.9999: 11.465 ms/op
                 getUser·p1.00:   11.862 ms/op

Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.565 ms/op
                 getUser·p0.9999: 12.976 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.256 ms/op
                 getUser·p0.9999: 27.511 ms/op
                 getUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306902
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24192 
    [ 2.500,  5.000) = 281781 
    [ 5.000,  7.500) = 716 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     26.605 ms/op
     p(99.9990) =     27.818 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.868 ms/op
                 listUser·p0.999:  12.808 ms/op
                 listUser·p0.9999: 19.758 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 4.066 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  12.530 ms/op
                 listUser·p0.9999: 17.699 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.855 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  18.024 ms/op
                 listUser·p0.9999: 22.066 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241826
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5913 
    [ 2.500,  5.000) = 206139 
    [ 5.000,  7.500) = 28527 
    [ 7.500, 10.000) = 784 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.269 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.289 ± 1.908  ops/ms
ClientGrpc.existUser                       thrpt       3  10.755 ± 3.855  ops/ms
ClientGrpc.getUser                         thrpt       3  10.258 ± 4.624  ops/ms
ClientGrpc.listUser                        thrpt       3   7.881 ± 1.629  ops/ms
ClientGrpc.createUser                       avgt       3   3.155 ± 1.079   ms/op
ClientGrpc.existUser                        avgt       3   2.880 ± 1.137   ms/op
ClientGrpc.getUser                          avgt       3   3.144 ± 1.070   ms/op
ClientGrpc.listUser                         avgt       3   4.030 ± 2.523   ms/op
ClientGrpc.createUser                     sample  306199   3.133 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.389           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.220           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.644           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.429           ms/op
ClientGrpc.existUser                      sample  320957   2.992 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.629           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.889           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.346           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  306902   3.127 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.541           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.969           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.685           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.605           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.918           ms/op
ClientGrpc.listUser                       sample  241826   3.969 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.702           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.135           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.348           ms/op
