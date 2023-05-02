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
# Warmup Iteration   1: 3.643 ops/ms
# Warmup Iteration   2: 7.606 ops/ms
# Warmup Iteration   3: 8.643 ops/ms
Iteration   1: 8.922 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.162 ±(99.9%) 3.815 ops/ms [Average]
  (min, avg, max) = (8.922, 9.162, 9.299), stdev = 0.209
  CI (99.9%): [5.348, 12.977] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 9.498 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.371 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (9.151, 9.371, 9.641), stdev = 0.249
  CI (99.9%): [4.830, 13.912] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.809 ops/ms
# Warmup Iteration   2: 8.730 ops/ms
# Warmup Iteration   3: 8.920 ops/ms
Iteration   1: 9.240 ops/ms
Iteration   2: 9.065 ops/ms
Iteration   3: 9.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.151 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (9.065, 9.151, 9.240), stdev = 0.088
  CI (99.9%): [7.548, 10.753] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ops/ms
# Warmup Iteration   2: 6.756 ops/ms
# Warmup Iteration   3: 7.191 ops/ms
Iteration   1: 7.305 ops/ms
Iteration   2: 7.106 ops/ms
Iteration   3: 7.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.214 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (7.106, 7.214, 7.305), stdev = 0.101
  CI (99.9%): [5.371, 9.058] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.218 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.778 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.005 ms/op
Iteration   1: 3.651 ±(99.9%) 0.006 ms/op
Iteration   2: 3.516 ±(99.9%) 0.002 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.540 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (3.453, 3.540, 3.651), stdev = 0.101
  CI (99.9%): [1.694, 5.385] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.566 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.003 ms/op
Iteration   1: 3.470 ±(99.9%) 0.003 ms/op
Iteration   2: 3.440 ±(99.9%) 0.002 ms/op
Iteration   3: 3.382 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.431 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.382, 3.431, 3.470), stdev = 0.044
  CI (99.9%): [2.620, 4.241] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.907 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.003 ms/op
Iteration   1: 3.420 ±(99.9%) 0.005 ms/op
Iteration   2: 3.486 ±(99.9%) 0.002 ms/op
Iteration   3: 3.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.471 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.420, 3.471, 3.507), stdev = 0.046
  CI (99.9%): [2.640, 4.302] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.899 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.555 ±(99.9%) 0.024 ms/op
Iteration   1: 4.552 ±(99.9%) 0.013 ms/op
Iteration   2: 4.524 ±(99.9%) 0.014 ms/op
Iteration   3: 4.500 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.525 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (4.500, 4.525, 4.552), stdev = 0.026
  CI (99.9%): [4.053, 4.998] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.009 ms/op
Iteration   1: 3.480 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  10.078 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 3.522 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  8.948 ms/op
                 createUser·p0.9999: 16.235 ms/op
                 createUser·p1.00:   16.679 ms/op

Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.905 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   4.907 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 31.178 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278058
  mean =      3.454 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12556 
    [ 2.500,  5.000) = 260665 
    [ 5.000,  7.500) = 4178 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     30.874 ms/op
     p(99.9990) =     31.596 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.633 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.007 ms/op
Iteration   1: 3.444 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.980 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.961 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  8.477 ms/op
                 existUser·p0.9999: 27.382 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.331 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  10.653 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282486
  mean =      3.397 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8932 
    [ 2.500,  5.000) = 268604 
    [ 5.000,  7.500) = 4231 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =      9.602 ms/op
     p(99.9900) =     26.329 ms/op
     p(99.9990) =     27.635 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.152 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.010 ms/op
Iteration   1: 3.388 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.284 ms/op
                 getUser·p0.999:  8.680 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.377 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.166 ms/op
                 getUser·p0.99:   5.104 ms/op
                 getUser·p0.999:  9.464 ms/op
                 getUser·p0.9999: 19.645 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.528 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  8.515 ms/op
                 getUser·p0.9999: 23.394 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 279772
  mean =      3.429 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9477 
    [ 2.500,  5.000) = 265216 
    [ 5.000,  7.500) = 4639 
    [ 7.500, 10.000) = 231 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     23.004 ms/op
     p(99.9990) =     23.593 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 5.711 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.014 ms/op
Iteration   1: 4.501 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  13.380 ms/op
                 listUser·p0.9999: 17.851 ms/op
                 listUser·p1.00:   18.186 ms/op

Iteration   2: 4.517 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.666 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  20.037 ms/op
                 listUser·p0.9999: 24.787 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 210480
  mean =      4.560 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 588 
    [ 2.500,  5.000) = 171085 
    [ 5.000,  7.500) = 34791 
    [ 7.500, 10.000) = 3442 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.661 ms/op
     p(95.0000) =      6.554 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     16.278 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     25.057 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.162 ± 3.815  ops/ms
ClientGrpc.existUser                       thrpt       3   9.371 ± 4.541  ops/ms
ClientGrpc.getUser                         thrpt       3   9.151 ± 1.602  ops/ms
ClientGrpc.listUser                        thrpt       3   7.214 ± 1.843  ops/ms
ClientGrpc.createUser                       avgt       3   3.540 ± 1.846   ms/op
ClientGrpc.existUser                        avgt       3   3.431 ± 0.810   ms/op
ClientGrpc.getUser                          avgt       3   3.471 ± 0.831   ms/op
ClientGrpc.listUser                         avgt       3   4.525 ± 0.473   ms/op
ClientGrpc.createUser                     sample  278058   3.454 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.874           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.687           ms/op
ClientGrpc.existUser                      sample  282486   3.397 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.329           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.722           ms/op
ClientGrpc.getUser                        sample  279772   3.429 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.908           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.379           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.573           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.004           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  210480   4.560 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.741           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.278           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.364           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.133           ms/op
