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
# Warmup Iteration   1: 2.001 ops/ms
# Warmup Iteration   2: 5.024 ops/ms
# Warmup Iteration   3: 6.573 ops/ms
Iteration   1: 6.532 ops/ms
Iteration   2: 6.799 ops/ms
Iteration   3: 7.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.860 ±(99.9%) 6.610 ops/ms [Average]
  (min, avg, max) = (6.532, 6.860, 7.249), stdev = 0.362
  CI (99.9%): [0.250, 13.470] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ops/ms
# Warmup Iteration   2: 6.760 ops/ms
# Warmup Iteration   3: 7.677 ops/ms
Iteration   1: 7.516 ops/ms
Iteration   2: 7.779 ops/ms
Iteration   3: 7.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.688 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (7.516, 7.688, 7.779), stdev = 0.149
  CI (99.9%): [4.967, 10.408] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.917 ops/ms
# Warmup Iteration   2: 6.427 ops/ms
# Warmup Iteration   3: 6.945 ops/ms
Iteration   1: 7.142 ops/ms
Iteration   2: 7.149 ops/ms
Iteration   3: 7.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.135 ±(99.9%) 0.354 ops/ms [Average]
  (min, avg, max) = (7.113, 7.135, 7.149), stdev = 0.019
  CI (99.9%): [6.781, 7.489] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.381 ops/ms
# Warmup Iteration   2: 5.103 ops/ms
# Warmup Iteration   3: 5.533 ops/ms
Iteration   1: 5.630 ops/ms
Iteration   2: 5.578 ops/ms
Iteration   3: 5.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.620 ±(99.9%) 0.691 ops/ms [Average]
  (min, avg, max) = (5.578, 5.620, 5.652), stdev = 0.038
  CI (99.9%): [4.928, 6.311] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.792 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.613 ±(99.9%) 0.005 ms/op
Iteration   1: 4.585 ±(99.9%) 0.004 ms/op
Iteration   2: 4.558 ±(99.9%) 0.003 ms/op
Iteration   3: 4.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.546 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (4.495, 4.546, 4.585), stdev = 0.046
  CI (99.9%): [3.701, 5.391] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.786 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.589 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.003 ms/op
Iteration   1: 4.401 ±(99.9%) 0.004 ms/op
Iteration   2: 4.456 ±(99.9%) 0.005 ms/op
Iteration   3: 4.403 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.420 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (4.401, 4.420, 4.456), stdev = 0.031
  CI (99.9%): [3.852, 4.989] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.940 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.921 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.007 ms/op
Iteration   1: 4.586 ±(99.9%) 0.005 ms/op
Iteration   2: 4.620 ±(99.9%) 0.004 ms/op
Iteration   3: 4.545 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.584 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (4.545, 4.584, 4.620), stdev = 0.038
  CI (99.9%): [3.897, 5.271] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.020 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.989 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.984 ±(99.9%) 0.020 ms/op
Iteration   1: 5.966 ±(99.9%) 0.015 ms/op
Iteration   2: 5.898 ±(99.9%) 0.019 ms/op
Iteration   3: 5.798 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.887 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (5.798, 5.887, 5.966), stdev = 0.085
  CI (99.9%): [4.338, 7.437] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 6.575 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.481 ±(99.9%) 0.014 ms/op
Iteration   1: 4.336 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  12.720 ms/op
                 createUser·p0.9999: 18.489 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   2: 4.522 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.848 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.045 ms/op
                 createUser·p0.999:  11.457 ms/op
                 createUser·p0.9999: 33.058 ms/op
                 createUser·p1.00:   35.652 ms/op

Iteration   3: 4.456 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.078 ms/op
                 createUser·p0.99:   7.678 ms/op
                 createUser·p0.999:  11.096 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216319
  mean =      4.436 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6456 
    [ 2.500,  5.000) = 161942 
    [ 5.000,  7.500) = 44985 
    [ 7.500, 10.000) = 2397 
    [10.000, 12.500) = 370 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     11.890 ms/op
     p(99.9900) =     31.437 ms/op
     p(99.9990) =     33.538 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.327 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.013 ms/op
Iteration   1: 4.169 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.267 ms/op
                 existUser·p0.95:   5.939 ms/op
                 existUser·p0.99:   8.053 ms/op
                 existUser·p0.999:  10.806 ms/op
                 existUser·p0.9999: 18.317 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 18.482 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 4.142 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   4.043 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  17.498 ms/op
                 existUser·p0.9999: 22.226 ms/op
                 existUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 233794
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6099 
    [ 2.500,  5.000) = 201438 
    [ 5.000,  7.500) = 24057 
    [ 7.500, 10.000) = 1746 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.742 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.398 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     20.533 ms/op
     p(99.9990) =     22.609 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.842 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.014 ms/op
Iteration   1: 4.407 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.472 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  11.933 ms/op
                 getUser·p0.9999: 16.752 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 4.396 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 22.666 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   3: 4.477 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.497 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.608 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 22.900 ms/op
                 getUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 216954
  mean =      4.427 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2384 
    [ 2.500,  5.000) = 173008 
    [ 5.000,  7.500) = 39585 
    [ 7.500, 10.000) = 1527 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.415 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     11.190 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.422 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 6.558 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.053 ±(99.9%) 0.024 ms/op
Iteration   1: 6.061 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  21.151 ms/op
                 listUser·p0.9999: 25.508 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 5.777 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   5.489 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   11.108 ms/op
                 listUser·p0.999:  20.316 ms/op
                 listUser·p0.9999: 26.983 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   3: 6.029 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.761 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   8.036 ms/op
                 listUser·p0.95:   9.060 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  22.413 ms/op
                 listUser·p0.9999: 26.920 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161194
  mean =      5.953 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 41768 
    [ 5.000,  7.500) = 97455 
    [ 7.500, 10.000) = 17625 
    [10.000, 12.500) = 3212 
    [12.500, 15.000) = 540 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      8.020 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     21.378 ms/op
     p(99.9900) =     26.858 ms/op
     p(99.9990) =     28.516 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.860 ± 6.610  ops/ms
ClientGrpc.existUser                       thrpt       3   7.688 ± 2.720  ops/ms
ClientGrpc.getUser                         thrpt       3   7.135 ± 0.354  ops/ms
ClientGrpc.listUser                        thrpt       3   5.620 ± 0.691  ops/ms
ClientGrpc.createUser                       avgt       3   4.546 ± 0.845   ms/op
ClientGrpc.existUser                        avgt       3   4.420 ± 0.569   ms/op
ClientGrpc.getUser                          avgt       3   4.584 ± 0.687   ms/op
ClientGrpc.listUser                         avgt       3   5.887 ± 1.549   ms/op
ClientGrpc.createUser                     sample  216319   4.436 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.848           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.078           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.979           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.890           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.437           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.652           ms/op
ClientGrpc.existUser                      sample  233794   4.107 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.742           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.398           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.419           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.774           ms/op
ClientGrpc.getUser                        sample  216954   4.427 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.188           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.190           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.298           ms/op
ClientGrpc.listUser                       sample  161194   5.953 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.938           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.020           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.077           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.600           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.378           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.858           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.441           ms/op
