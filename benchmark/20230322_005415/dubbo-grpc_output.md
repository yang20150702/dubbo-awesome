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
# Warmup Iteration   1: 3.274 ops/ms
# Warmup Iteration   2: 7.184 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.617 ops/ms
Iteration   2: 8.644 ops/ms
Iteration   3: 8.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.726 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (8.617, 8.726, 8.918), stdev = 0.167
  CI (99.9%): [5.687, 11.766] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.871 ops/ms
# Warmup Iteration   2: 8.775 ops/ms
# Warmup Iteration   3: 9.204 ops/ms
Iteration   1: 9.149 ops/ms
Iteration   2: 9.129 ops/ms
Iteration   3: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.182 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (9.129, 9.182, 9.268), stdev = 0.075
  CI (99.9%): [7.805, 10.559] (assumes normal distribution)


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
# Warmup Iteration   1: 5.462 ops/ms
# Warmup Iteration   2: 7.850 ops/ms
# Warmup Iteration   3: 8.643 ops/ms
Iteration   1: 8.720 ops/ms
Iteration   2: 8.711 ops/ms
Iteration   3: 8.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.727 ±(99.9%) 0.358 ops/ms [Average]
  (min, avg, max) = (8.711, 8.727, 8.749), stdev = 0.020
  CI (99.9%): [8.368, 9.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.575 ops/ms
# Warmup Iteration   2: 6.223 ops/ms
# Warmup Iteration   3: 7.001 ops/ms
Iteration   1: 6.731 ops/ms
Iteration   2: 6.593 ops/ms
Iteration   3: 6.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.725 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (6.593, 6.725, 6.850), stdev = 0.129
  CI (99.9%): [4.374, 9.075] (assumes normal distribution)


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
# Warmup Iteration   1: 5.672 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.014 ms/op
Iteration   1: 3.709 ±(99.9%) 0.003 ms/op
Iteration   2: 3.703 ±(99.9%) 0.002 ms/op
Iteration   3: 3.622 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.678 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.622, 3.678, 3.709), stdev = 0.048
  CI (99.9%): [2.794, 4.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.002 ms/op
Iteration   1: 3.534 ±(99.9%) 0.003 ms/op
Iteration   2: 3.439 ±(99.9%) 0.002 ms/op
Iteration   3: 3.404 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.459 ±(99.9%) 1.229 ms/op [Average]
  (min, avg, max) = (3.404, 3.459, 3.534), stdev = 0.067
  CI (99.9%): [2.230, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 5.347 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.005 ms/op
Iteration   1: 3.654 ±(99.9%) 0.003 ms/op
Iteration   2: 3.672 ±(99.9%) 0.003 ms/op
Iteration   3: 3.552 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.626 ±(99.9%) 1.180 ms/op [Average]
  (min, avg, max) = (3.552, 3.626, 3.672), stdev = 0.065
  CI (99.9%): [2.446, 4.807] (assumes normal distribution)


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
# Warmup Iteration   1: 6.965 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.025 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.838 ±(99.9%) 0.012 ms/op
Iteration   1: 4.550 ±(99.9%) 0.023 ms/op
Iteration   2: 4.684 ±(99.9%) 0.015 ms/op
Iteration   3: 4.562 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.599 ±(99.9%) 1.348 ms/op [Average]
  (min, avg, max) = (4.550, 4.599, 4.684), stdev = 0.074
  CI (99.9%): [3.250, 5.947] (assumes normal distribution)


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
# Warmup Iteration   1: 5.272 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.008 ms/op
Iteration   1: 3.700 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.859 ms/op
                 createUser·p0.999:  13.542 ms/op
                 createUser·p0.9999: 15.888 ms/op
                 createUser·p1.00:   16.974 ms/op

Iteration   2: 3.663 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.398 ms/op
                 createUser·p0.999:  9.820 ms/op
                 createUser·p0.9999: 15.527 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 3.646 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  12.304 ms/op
                 createUser·p0.9999: 20.920 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261600
  mean =      3.670 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10137 
    [ 2.500,  5.000) = 241349 
    [ 5.000,  7.500) = 8545 
    [ 7.500, 10.000) = 1257 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     18.798 ms/op
     p(99.9990) =     21.987 ms/op
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
# Warmup Iteration   1: 4.905 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.011 ms/op
Iteration   1: 3.543 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  10.034 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   2: 3.545 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.882 ms/op
                 existUser·p0.999:  15.483 ms/op
                 existUser·p0.9999: 31.325 ms/op
                 existUser·p1.00:   38.011 ms/op

Iteration   3: 3.449 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.408 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  10.228 ms/op
                 existUser·p0.9999: 18.276 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 273337
  mean =      3.512 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10641 
    [ 2.500,  5.000) = 256048 
    [ 5.000,  7.500) = 5576 
    [ 7.500, 10.000) = 704 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     12.266 ms/op
     p(99.9900) =     29.961 ms/op
     p(99.9990) =     31.335 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.597 ±(99.9%) 0.009 ms/op
Iteration   1: 3.676 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.318 ms/op
                 getUser·p0.999:  10.876 ms/op
                 getUser·p0.9999: 14.169 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 3.524 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  8.352 ms/op
                 getUser·p0.9999: 16.663 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.567 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.510 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  8.432 ms/op
                 getUser·p0.9999: 29.395 ms/op
                 getUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267638
  mean =      3.588 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6214 
    [ 2.500,  5.000) = 255382 
    [ 5.000,  7.500) = 5321 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.263 ms/op
     p(99.9900) =     27.836 ms/op
     p(99.9990) =     29.687 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 6.280 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.125 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.016 ms/op
Iteration   1: 4.783 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.980 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  15.073 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   2: 4.649 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.430 ms/op
                 listUser·p0.50:   4.432 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  15.404 ms/op
                 listUser·p0.9999: 26.045 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   3: 4.888 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.193 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  21.405 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201200
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 533 
    [ 2.500,  5.000) = 146117 
    [ 5.000,  7.500) = 48592 
    [ 7.500, 10.000) = 5170 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     15.712 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.508 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.726 ± 3.040  ops/ms
ClientGrpc.existUser                       thrpt       3   9.182 ± 1.377  ops/ms
ClientGrpc.getUser                         thrpt       3   8.727 ± 0.358  ops/ms
ClientGrpc.listUser                        thrpt       3   6.725 ± 2.351  ops/ms
ClientGrpc.createUser                       avgt       3   3.678 ± 0.884   ms/op
ClientGrpc.existUser                        avgt       3   3.459 ± 1.229   ms/op
ClientGrpc.getUser                          avgt       3   3.626 ± 1.180   ms/op
ClientGrpc.listUser                         avgt       3   4.599 ± 1.348   ms/op
ClientGrpc.createUser                     sample  261600   3.670 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.666           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.652           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.304           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.798           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  273337   3.512 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.788           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.906           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.961           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.011           ms/op
ClientGrpc.getUser                        sample  267638   3.588 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.263           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.836           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.786           ms/op
ClientGrpc.listUser                       sample  201200   4.771 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.430           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.815           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.712           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.395           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.608           ms/op
