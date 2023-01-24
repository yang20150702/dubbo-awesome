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
# Warmup Iteration   1: 3.319 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 8.270 ops/ms
Iteration   1: 9.790 ops/ms
Iteration   2: 8.706 ops/ms
Iteration   3: 8.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.107 ±(99.9%) 10.850 ops/ms [Average]
  (min, avg, max) = (8.706, 9.107, 9.790), stdev = 0.595
  CI (99.9%): [≈ 0, 19.957] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.330 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 9.210 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.103 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.154 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (9.079, 9.154, 9.279), stdev = 0.110
  CI (99.9%): [7.154, 11.153] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.057 ops/ms
Iteration   1: 9.110 ops/ms
Iteration   2: 9.264 ops/ms
Iteration   3: 9.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.223 ±(99.9%) 1.812 ops/ms [Average]
  (min, avg, max) = (9.110, 9.223, 9.295), stdev = 0.099
  CI (99.9%): [7.411, 11.034] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.947 ops/ms
# Warmup Iteration   2: 6.603 ops/ms
# Warmup Iteration   3: 6.938 ops/ms
Iteration   1: 6.838 ops/ms
Iteration   2: 7.045 ops/ms
Iteration   3: 6.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.945 ±(99.9%) 1.895 ops/ms [Average]
  (min, avg, max) = (6.838, 6.945, 7.045), stdev = 0.104
  CI (99.9%): [5.050, 8.840] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.974 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.002 ms/op
Iteration   1: 3.534 ±(99.9%) 0.003 ms/op
Iteration   2: 3.530 ±(99.9%) 0.002 ms/op
Iteration   3: 3.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.509 ±(99.9%) 0.711 ms/op [Average]
  (min, avg, max) = (3.464, 3.509, 3.534), stdev = 0.039
  CI (99.9%): [2.798, 4.220] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.005 ms/op
Iteration   1: 3.489 ±(99.9%) 0.002 ms/op
Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
Iteration   3: 3.471 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.451 ±(99.9%) 0.945 ms/op [Average]
  (min, avg, max) = (3.392, 3.451, 3.489), stdev = 0.052
  CI (99.9%): [2.505, 4.396] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.889 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.587 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.004 ms/op
Iteration   1: 3.508 ±(99.9%) 0.007 ms/op
Iteration   2: 3.499 ±(99.9%) 0.002 ms/op
Iteration   3: 3.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.477 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.425, 3.477, 3.508), stdev = 0.045
  CI (99.9%): [2.648, 4.306] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.292 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.006 ms/op
Iteration   1: 4.332 ±(99.9%) 0.007 ms/op
Iteration   2: 4.431 ±(99.9%) 0.005 ms/op
Iteration   3: 4.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.432 ±(99.9%) 1.824 ms/op [Average]
  (min, avg, max) = (4.332, 4.432, 4.532), stdev = 0.100
  CI (99.9%): [2.608, 6.256] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.211 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.008 ms/op
Iteration   1: 3.659 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 18.695 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   2: 3.673 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.307 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.079 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 20.303 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   3: 3.538 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  6.651 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264828
  mean =      3.622 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5567 
    [ 2.500,  5.000) = 256159 
    [ 5.000,  7.500) = 2714 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =      8.864 ms/op
     p(99.9900) =     21.152 ms/op
     p(99.9990) =     22.055 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.572 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.557 ±(99.9%) 0.008 ms/op
Iteration   1: 3.516 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 16.561 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  7.863 ms/op
                 existUser·p0.9999: 22.603 ms/op
                 existUser·p1.00:   23.790 ms/op

Iteration   3: 3.416 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  11.317 ms/op
                 existUser·p0.9999: 23.274 ms/op
                 existUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279923
  mean =      3.428 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17497 
    [ 2.500,  5.000) = 260089 
    [ 5.000,  7.500) = 1979 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =      8.031 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.704 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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
# Warmup Iteration   1: 5.056 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.009 ms/op
Iteration   1: 3.457 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 14.942 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  6.991 ms/op
                 getUser·p0.9999: 15.658 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.685 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  7.740 ms/op
                 getUser·p0.9999: 18.416 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270808
  mean =      3.542 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 9702 
    [ 2.500,  3.750) = 170855 
    [ 3.750,  5.000) = 85853 
    [ 5.000,  6.250) = 3625 
    [ 6.250,  7.500) = 377 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      5.169 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     17.886 ms/op
     p(99.9990) =     18.523 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 6.620 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.623 ±(99.9%) 0.013 ms/op
Iteration   1: 4.539 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  17.103 ms/op
                 listUser·p0.9999: 20.541 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 4.409 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.795 ms/op
                 listUser·p0.9999: 23.872 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.532 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.718 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   7.777 ms/op
                 listUser·p0.999:  17.280 ms/op
                 listUser·p0.9999: 25.419 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213540
  mean =      4.493 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 859 
    [ 2.500,  5.000) = 175608 
    [ 5.000,  7.500) = 34043 
    [ 7.500, 10.000) = 2566 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.365 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     17.022 ms/op
     p(99.9900) =     24.237 ms/op
     p(99.9990) =     25.915 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   9.107 ± 10.850  ops/ms
ClientGrpc.existUser                       thrpt       3   9.154 ±  1.999  ops/ms
ClientGrpc.getUser                         thrpt       3   9.223 ±  1.812  ops/ms
ClientGrpc.listUser                        thrpt       3   6.945 ±  1.895  ops/ms
ClientGrpc.createUser                       avgt       3   3.509 ±  0.711   ms/op
ClientGrpc.existUser                        avgt       3   3.451 ±  0.945   ms/op
ClientGrpc.getUser                          avgt       3   3.477 ±  0.829   ms/op
ClientGrpc.listUser                         avgt       3   4.432 ±  1.824   ms/op
ClientGrpc.createUser                     sample  264828   3.622 ±  0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.307            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.584            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.358            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.579            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.063            ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.864            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.152            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217            ms/op
ClientGrpc.existUser                      sample  279923   3.428 ±  0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.686            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.202            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.432            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.915            ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.031            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.741            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.790            ms/op
ClientGrpc.getUser                        sample  270808   3.542 ±  0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.511            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.490            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.628            ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.169            ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.487            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.886            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.547            ms/op
ClientGrpc.listUser                       sample  213540   4.493 ±  0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.740            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.325            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.636            ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.365            ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.873            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.022            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.237            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.919            ms/op
