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
# Warmup Iteration   1: 2.176 ops/ms
# Warmup Iteration   2: 5.941 ops/ms
# Warmup Iteration   3: 7.626 ops/ms
Iteration   1: 8.102 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.073 ±(99.9%) 0.846 ops/ms [Average]
  (min, avg, max) = (8.019, 8.073, 8.102), stdev = 0.046
  CI (99.9%): [7.226, 8.919] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 7.808 ops/ms
# Warmup Iteration   3: 8.465 ops/ms
Iteration   1: 8.562 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.595 ±(99.9%) 4.085 ops/ms [Average]
  (min, avg, max) = (8.390, 8.595, 8.834), stdev = 0.224
  CI (99.9%): [4.510, 12.680] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.581 ops/ms
Iteration   1: 7.543 ops/ms
Iteration   2: 7.253 ops/ms
Iteration   3: 7.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.323 ±(99.9%) 3.548 ops/ms [Average]
  (min, avg, max) = (7.173, 7.323, 7.543), stdev = 0.194
  CI (99.9%): [3.775, 10.871] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.296 ops/ms
# Warmup Iteration   2: 5.013 ops/ms
# Warmup Iteration   3: 5.903 ops/ms
Iteration   1: 6.073 ops/ms
Iteration   2: 6.235 ops/ms
Iteration   3: 6.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.107 ±(99.9%) 2.098 ops/ms [Average]
  (min, avg, max) = (6.013, 6.107, 6.235), stdev = 0.115
  CI (99.9%): [4.009, 8.206] (assumes normal distribution)


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
# Warmup Iteration   1: 5.862 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.010 ms/op
Iteration   1: 4.087 ±(99.9%) 0.002 ms/op
Iteration   2: 3.890 ±(99.9%) 0.003 ms/op
Iteration   3: 3.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.980 ±(99.9%) 1.811 ms/op [Average]
  (min, avg, max) = (3.890, 3.980, 4.087), stdev = 0.099
  CI (99.9%): [2.169, 5.790] (assumes normal distribution)


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
# Warmup Iteration   1: 5.374 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.002 ms/op
Iteration   1: 3.770 ±(99.9%) 0.002 ms/op
Iteration   2: 3.919 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.847 ±(99.9%) 1.358 ms/op [Average]
  (min, avg, max) = (3.770, 3.847, 3.919), stdev = 0.074
  CI (99.9%): [2.489, 5.205] (assumes normal distribution)


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
# Warmup Iteration   1: 6.312 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.002 ms/op
Iteration   1: 4.343 ±(99.9%) 0.005 ms/op
Iteration   2: 4.473 ±(99.9%) 0.004 ms/op
Iteration   3: 4.430 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.415 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (4.343, 4.415, 4.473), stdev = 0.066
  CI (99.9%): [3.208, 5.622] (assumes normal distribution)


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
# Warmup Iteration   1: 7.493 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 6.098 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.277 ±(99.9%) 0.013 ms/op
Iteration   1: 5.310 ±(99.9%) 0.016 ms/op
Iteration   2: 5.409 ±(99.9%) 0.023 ms/op
Iteration   3: 5.290 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.336 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (5.290, 5.336, 5.409), stdev = 0.064
  CI (99.9%): [4.172, 6.501] (assumes normal distribution)


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
# Warmup Iteration   1: 6.526 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.013 ms/op
Iteration   1: 4.007 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  14.949 ms/op
                 createUser·p0.9999: 33.751 ms/op
                 createUser·p1.00:   33.817 ms/op

Iteration   2: 4.108 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  11.447 ms/op
                 createUser·p0.9999: 24.649 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 4.096 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  12.189 ms/op
                 createUser·p0.9999: 27.125 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235759
  mean =      4.070 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4932 
    [ 2.500,  5.000) = 201186 
    [ 5.000,  7.500) = 28036 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     13.143 ms/op
     p(99.9900) =     32.496 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 5.303 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
Iteration   1: 3.758 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.662 ms/op
                 existUser·p0.999:  10.510 ms/op
                 existUser·p0.9999: 16.742 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   2: 3.788 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.998 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  11.953 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   3: 3.757 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  11.008 ms/op
                 existUser·p0.9999: 23.503 ms/op
                 existUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254756
  mean =      3.767 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5814 
    [ 2.500,  5.000) = 231170 
    [ 5.000,  7.500) = 16523 
    [ 7.500, 10.000) = 875 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     11.428 ms/op
     p(99.9900) =     22.299 ms/op
     p(99.9990) =     24.212 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 5.820 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.011 ms/op
Iteration   1: 4.351 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   4.235 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   7.348 ms/op
                 getUser·p0.999:  11.084 ms/op
                 getUser·p0.9999: 16.885 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   2: 4.263 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.808 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  11.894 ms/op
                 getUser·p0.9999: 21.823 ms/op
                 getUser·p1.00:   21.955 ms/op

Iteration   3: 4.342 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.513 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  18.290 ms/op
                 getUser·p0.9999: 28.332 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222133
  mean =      4.318 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4161 
    [ 2.500,  5.000) = 176054 
    [ 5.000,  7.500) = 40043 
    [ 7.500, 10.000) = 1419 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.456 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     13.346 ms/op
     p(99.9900) =     27.839 ms/op
     p(99.9990) =     29.193 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 8.464 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.862 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.017 ms/op
Iteration   1: 5.160 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.479 ms/op
                 listUser·p0.99:   9.568 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 21.955 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 5.256 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   4.973 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   9.698 ms/op
                 listUser·p0.999:  18.353 ms/op
                 listUser·p0.9999: 23.289 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 5.566 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   10.600 ms/op
                 listUser·p0.999:  19.988 ms/op
                 listUser·p0.9999: 22.265 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180455
  mean =      5.322 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 163 
    [ 2.500,  5.000) = 85740 
    [ 5.000,  7.500) = 82922 
    [ 7.500, 10.000) = 9852 
    [10.000, 12.500) = 1194 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     18.317 ms/op
     p(99.9900) =     22.248 ms/op
     p(99.9990) =     23.690 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.073 ± 0.846  ops/ms
ClientGrpc.existUser                       thrpt       3   8.595 ± 4.085  ops/ms
ClientGrpc.getUser                         thrpt       3   7.323 ± 3.548  ops/ms
ClientGrpc.listUser                        thrpt       3   6.107 ± 2.098  ops/ms
ClientGrpc.createUser                       avgt       3   3.980 ± 1.811   ms/op
ClientGrpc.existUser                        avgt       3   3.847 ± 1.358   ms/op
ClientGrpc.getUser                          avgt       3   4.415 ± 1.207   ms/op
ClientGrpc.listUser                         avgt       3   5.336 ± 1.165   ms/op
ClientGrpc.createUser                     sample  235759   4.070 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.825           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.949           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.955           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.143           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.817           ms/op
ClientGrpc.existUser                      sample  254756   3.767 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.736           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.701           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.428           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.299           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.478           ms/op
ClientGrpc.getUser                        sample  222133   4.318 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.931           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.346           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.839           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.360           ms/op
ClientGrpc.listUser                       sample  180455   5.322 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.276           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.317           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.248           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
