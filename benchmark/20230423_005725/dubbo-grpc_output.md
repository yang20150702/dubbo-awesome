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
# Warmup Iteration   1: 4.548 ops/ms
# Warmup Iteration   2: 9.370 ops/ms
# Warmup Iteration   3: 10.115 ops/ms
Iteration   1: 10.538 ops/ms
Iteration   2: 10.694 ops/ms
Iteration   3: 10.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.628 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.538, 10.628, 10.694), stdev = 0.081
  CI (99.9%): [9.156, 12.101] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.713 ops/ms
# Warmup Iteration   2: 10.906 ops/ms
# Warmup Iteration   3: 11.000 ops/ms
Iteration   1: 11.461 ops/ms
Iteration   2: 11.032 ops/ms
Iteration   3: 11.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.255 ±(99.9%) 3.927 ops/ms [Average]
  (min, avg, max) = (11.032, 11.255, 11.461), stdev = 0.215
  CI (99.9%): [7.328, 15.182] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 10.527 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.665 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.715 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (10.665, 10.715, 10.796), stdev = 0.071
  CI (99.9%): [9.425, 12.004] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.516 ops/ms
# Warmup Iteration   2: 7.918 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.149 ops/ms
Iteration   2: 8.202 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.219 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (8.149, 8.219, 8.308), stdev = 0.081
  CI (99.9%): [6.744, 9.695] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.273 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.991 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (2.984, 2.991, 2.999), stdev = 0.008
  CI (99.9%): [2.854, 3.129] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.004 ms/op
Iteration   1: 2.850 ±(99.9%) 0.004 ms/op
Iteration   2: 2.845 ±(99.9%) 0.003 ms/op
Iteration   3: 2.871 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.855 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.845, 2.855, 2.871), stdev = 0.014
  CI (99.9%): [2.604, 3.107] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.025 ±(99.9%) 0.002 ms/op
Iteration   2: 2.965 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.573 ms/op [Average]
  (min, avg, max) = (2.965, 2.991, 3.025), stdev = 0.031
  CI (99.9%): [2.418, 3.563] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.011 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.981 ±(99.9%) 0.024 ms/op
Iteration   1: 3.922 ±(99.9%) 0.028 ms/op
Iteration   2: 3.904 ±(99.9%) 0.020 ms/op
Iteration   3: 3.856 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.894 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (3.856, 3.894, 3.922), stdev = 0.034
  CI (99.9%): [3.270, 4.518] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  6.767 ms/op
                 createUser·p0.9999: 11.201 ms/op
                 createUser·p1.00:   11.551 ms/op

Iteration   2: 2.990 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  8.003 ms/op
                 createUser·p0.9999: 14.352 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.954 ms/op
                 createUser·p0.9999: 15.254 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319586
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1734 
    [ 1.250,  2.500) = 21157 
    [ 2.500,  3.750) = 282003 
    [ 3.750,  5.000) = 13438 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 278 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.350 ms/op
     p(99.9900) =     14.403 ms/op
     p(99.9990) =     16.764 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.768 ±(99.9%) 0.007 ms/op
Iteration   1: 2.862 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.259 ms/op
                 existUser·p0.9999: 16.930 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  5.661 ms/op
                 existUser·p0.9999: 13.793 ms/op
                 existUser·p1.00:   14.107 ms/op

Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 15.548 ms/op
                 existUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333501
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2460 
    [ 1.250,  2.500) = 41676 
    [ 2.500,  3.750) = 278979 
    [ 3.750,  5.000) = 9457 
    [ 5.000,  6.250) = 628 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     16.083 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.757 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.799 ms/op
                 getUser·p0.9999: 18.687 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.524 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.350 ms/op
                 getUser·p0.9999: 18.427 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320356
  mean =      2.995 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28904 
    [ 2.500,  5.000) = 290178 
    [ 5.000,  7.500) = 946 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.613 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.615 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.089 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.008 ms/op
Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.727 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.371 ms/op
                 listUser·p0.9999: 16.807 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.360 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.556 ms/op
                 listUser·p0.9999: 15.030 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.339 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243661
  mean =      3.935 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3353 
    [ 2.500,  5.000) = 219257 
    [ 5.000,  7.500) = 19888 
    [ 7.500, 10.000) = 731 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.145 ms/op
     p(99.9900) =     22.225 ms/op
     p(99.9990) =     23.339 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.628 ± 1.473  ops/ms
ClientGrpc.existUser                       thrpt       3  11.255 ± 3.927  ops/ms
ClientGrpc.getUser                         thrpt       3  10.715 ± 1.290  ops/ms
ClientGrpc.listUser                        thrpt       3   8.219 ± 1.476  ops/ms
ClientGrpc.createUser                       avgt       3   2.991 ± 0.138   ms/op
ClientGrpc.existUser                        avgt       3   2.855 ± 0.252   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.573   ms/op
ClientGrpc.listUser                         avgt       3   3.894 ± 0.624   ms/op
ClientGrpc.createUser                     sample  319586   3.004 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.350           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.403           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.596           ms/op
ClientGrpc.existUser                      sample  333501   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.587           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.111           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.083           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.302           ms/op
ClientGrpc.getUser                        sample  320356   2.995 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.524           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.613           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.005           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.218           ms/op
ClientGrpc.listUser                       sample  243661   3.935 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.727           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.145           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.225           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
