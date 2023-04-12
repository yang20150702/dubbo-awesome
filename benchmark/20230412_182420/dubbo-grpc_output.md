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
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 6.204 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 8.051 ops/ms
Iteration   2: 8.186 ops/ms
Iteration   3: 8.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.152 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (8.051, 8.152, 8.220), stdev = 0.090
  CI (99.9%): [6.519, 9.786] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.196 ops/ms
# Warmup Iteration   2: 8.336 ops/ms
# Warmup Iteration   3: 8.621 ops/ms
Iteration   1: 8.711 ops/ms
Iteration   2: 8.778 ops/ms
Iteration   3: 8.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.790 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (8.711, 8.790, 8.883), stdev = 0.087
  CI (99.9%): [7.204, 10.377] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ops/ms
# Warmup Iteration   2: 7.538 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 8.012 ops/ms
Iteration   2: 7.896 ops/ms
Iteration   3: 8.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.017 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (7.896, 8.017, 8.143), stdev = 0.124
  CI (99.9%): [5.760, 10.274] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ops/ms
# Warmup Iteration   2: 5.835 ops/ms
# Warmup Iteration   3: 6.105 ops/ms
Iteration   1: 6.297 ops/ms
Iteration   2: 6.133 ops/ms
Iteration   3: 6.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.249 ±(99.9%) 1.848 ops/ms [Average]
  (min, avg, max) = (6.133, 6.249, 6.317), stdev = 0.101
  CI (99.9%): [4.401, 8.097] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.249 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.007 ms/op
Iteration   1: 3.949 ±(99.9%) 0.003 ms/op
Iteration   2: 3.953 ±(99.9%) 0.002 ms/op
Iteration   3: 4.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.974 ±(99.9%) 0.710 ms/op [Average]
  (min, avg, max) = (3.949, 3.974, 4.019), stdev = 0.039
  CI (99.9%): [3.264, 4.684] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.940 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.003 ms/op
Iteration   1: 3.545 ±(99.9%) 0.002 ms/op
Iteration   2: 3.562 ±(99.9%) 0.003 ms/op
Iteration   3: 3.512 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.539 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.512, 3.539, 3.562), stdev = 0.025
  CI (99.9%): [3.080, 3.999] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.841 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.004 ms/op
Iteration   1: 3.842 ±(99.9%) 0.003 ms/op
Iteration   2: 3.887 ±(99.9%) 0.004 ms/op
Iteration   3: 3.920 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.883 ±(99.9%) 0.720 ms/op [Average]
  (min, avg, max) = (3.842, 3.883, 3.920), stdev = 0.039
  CI (99.9%): [3.163, 4.603] (assumes normal distribution)


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
# Warmup Iteration   1: 6.827 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.397 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.129 ±(99.9%) 0.022 ms/op
Iteration   1: 5.141 ±(99.9%) 0.014 ms/op
Iteration   2: 5.178 ±(99.9%) 0.010 ms/op
Iteration   3: 5.002 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.107 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (5.002, 5.107, 5.178), stdev = 0.092
  CI (99.9%): [3.421, 6.793] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.900 ms/op
                 createUser·p0.999:  11.757 ms/op
                 createUser·p0.9999: 15.578 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   2: 4.086 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.276 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  13.279 ms/op
                 createUser·p0.9999: 17.242 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.940 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  12.106 ms/op
                 createUser·p0.9999: 26.789 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 238414
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4113 
    [ 2.500,  5.000) = 214510 
    [ 5.000,  7.500) = 18484 
    [ 7.500, 10.000) = 778 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     12.864 ms/op
     p(99.9900) =     25.930 ms/op
     p(99.9990) =     27.487 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 5.926 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.010 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   5.831 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 22.957 ms/op
                 existUser·p1.00:   23.495 ms/op

Iteration   2: 3.623 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  9.414 ms/op
                 existUser·p0.9999: 19.475 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.706 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  10.172 ms/op
                 existUser·p0.9999: 18.591 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261794
  mean =      3.670 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6913 
    [ 2.500,  5.000) = 246601 
    [ 5.000,  7.500) = 7349 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     21.910 ms/op
     p(99.9990) =     23.389 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 5.976 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.010 ms/op
Iteration   1: 4.067 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  12.278 ms/op
                 getUser·p0.9999: 16.417 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   2: 3.976 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 18.613 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 4.050 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  9.946 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 238095
  mean =      4.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2644 
    [ 2.500,  3.750) = 85318 
    [ 3.750,  5.000) = 133214 
    [ 5.000,  6.250) = 14350 
    [ 6.250,  7.500) = 1482 
    [ 7.500,  8.750) = 518 
    [ 8.750, 10.000) = 259 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     10.596 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     19.386 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 7.825 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.549 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.219 ±(99.9%) 0.016 ms/op
Iteration   1: 5.124 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 21.283 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 5.211 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   6.660 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   9.623 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 19.320 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 5.215 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   5.022 ms/op
                 listUser·p0.90:   6.554 ms/op
                 listUser·p0.95:   7.430 ms/op
                 listUser·p0.99:   9.535 ms/op
                 listUser·p0.999:  20.441 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185172
  mean =      5.183 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 95185 
    [ 5.000,  7.500) = 80795 
    [ 7.500, 10.000) = 7665 
    [10.000, 12.500) = 733 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      4.973 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =      9.437 ms/op
     p(99.9000) =     17.296 ms/op
     p(99.9900) =     22.790 ms/op
     p(99.9990) =     23.617 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.152 ± 1.633  ops/ms
ClientGrpc.existUser                       thrpt       3   8.790 ± 1.587  ops/ms
ClientGrpc.getUser                         thrpt       3   8.017 ± 2.257  ops/ms
ClientGrpc.listUser                        thrpt       3   6.249 ± 1.848  ops/ms
ClientGrpc.createUser                       avgt       3   3.974 ± 0.710   ms/op
ClientGrpc.existUser                        avgt       3   3.539 ± 0.460   ms/op
ClientGrpc.getUser                          avgt       3   3.883 ± 0.720   ms/op
ClientGrpc.listUser                         avgt       3   5.107 ± 1.686   ms/op
ClientGrpc.createUser                     sample  238414   4.027 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.863           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.251           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.496           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.864           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.930           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.591           ms/op
ClientGrpc.existUser                      sample  261794   3.670 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.751           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.939           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.093           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.910           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.495           ms/op
ClientGrpc.getUser                        sample  238095   4.030 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.176           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.169           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.316           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.596           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.464           ms/op
ClientGrpc.listUser                       sample  185172   5.183 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.288           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.463           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.437           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.296           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.790           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
