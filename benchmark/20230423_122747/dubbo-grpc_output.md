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
# Warmup Iteration   1: 4.132 ops/ms
# Warmup Iteration   2: 9.269 ops/ms
# Warmup Iteration   3: 9.996 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.444 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.512 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (10.444, 10.512, 10.556), stdev = 0.060
  CI (99.9%): [9.421, 11.604] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ops/ms
# Warmup Iteration   2: 10.337 ops/ms
# Warmup Iteration   3: 11.032 ops/ms
Iteration   1: 11.162 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.931 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (10.738, 10.931, 11.162), stdev = 0.215
  CI (99.9%): [7.009, 14.852] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.910 ops/ms
# Warmup Iteration   2: 10.011 ops/ms
# Warmup Iteration   3: 10.558 ops/ms
Iteration   1: 10.677 ops/ms
Iteration   2: 10.505 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.578 ±(99.9%) 1.614 ops/ms [Average]
  (min, avg, max) = (10.505, 10.578, 10.677), stdev = 0.088
  CI (99.9%): [8.964, 12.193] (assumes normal distribution)


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
# Warmup Iteration   1: 5.540 ops/ms
# Warmup Iteration   2: 7.704 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.333 ±(99.9%) 2.670 ops/ms [Average]
  (min, avg, max) = (8.180, 8.333, 8.471), stdev = 0.146
  CI (99.9%): [5.663, 11.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.004 ms/op
Iteration   1: 2.994 ±(99.9%) 0.004 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.994, 3.004, 3.020), stdev = 0.014
  CI (99.9%): [2.740, 3.267] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.896 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.002 ms/op
Iteration   2: 2.853 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (2.853, 2.907, 2.952), stdev = 0.050
  CI (99.9%): [1.986, 3.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.003 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.008 ±(99.9%) 0.058 ms/op [Average]
  (min, avg, max) = (3.006, 3.008, 3.012), stdev = 0.003
  CI (99.9%): [2.950, 3.067] (assumes normal distribution)


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
# Warmup Iteration   1: 4.573 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.026 ms/op
Iteration   1: 3.963 ±(99.9%) 0.012 ms/op
Iteration   2: 3.884 ±(99.9%) 0.009 ms/op
Iteration   3: 3.938 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 0.740 ms/op [Average]
  (min, avg, max) = (3.884, 3.928, 3.963), stdev = 0.041
  CI (99.9%): [3.188, 4.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.237 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.599 ms/op
                 createUser·p0.9999: 13.700 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.731 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.542 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.303 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 19.581 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314657
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22026 
    [ 2.500,  5.000) = 291453 
    [ 5.000,  7.500) = 805 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.722 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.864 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.070 ms/op
                 existUser·p0.9999: 13.005 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.936 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.726 ms/op
                 existUser·p0.9999: 14.634 ms/op
                 existUser·p1.00:   15.106 ms/op

Iteration   3: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  9.961 ms/op
                 existUser·p0.9999: 21.929 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326544
  mean =      2.941 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36111 
    [ 2.500,  5.000) = 289109 
    [ 5.000,  7.500) = 1031 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     17.777 ms/op
     p(99.9990) =     22.506 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.453 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 16.166 ms/op
                 getUser·p1.00:   16.810 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.330 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  8.379 ms/op
                 getUser·p0.9999: 21.738 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319879
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25589 
    [ 2.500,  5.000) = 293146 
    [ 5.000,  7.500) = 790 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.767 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.974 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.315 ms/op
                 listUser·p0.9999: 19.358 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.910 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 3.886 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.782 ms/op
                 listUser·p0.999:  17.250 ms/op
                 listUser·p0.9999: 26.010 ms/op
                 listUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246544
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3831 
    [ 2.500,  5.000) = 223549 
    [ 5.000,  7.500) = 18032 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     16.612 ms/op
     p(99.9900) =     24.948 ms/op
     p(99.9990) =     26.413 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.512 ± 1.092  ops/ms
ClientGrpc.existUser                       thrpt       3  10.931 ± 3.922  ops/ms
ClientGrpc.getUser                         thrpt       3  10.578 ± 1.614  ops/ms
ClientGrpc.listUser                        thrpt       3   8.333 ± 2.670  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.263   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.921   ms/op
ClientGrpc.getUser                          avgt       3   3.008 ± 0.058   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 0.740   ms/op
ClientGrpc.createUser                     sample  314657   3.054 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.504           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.722           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.628           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.939           ms/op
ClientGrpc.existUser                      sample  326544   2.941 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.537           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.777           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  319879   2.999 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.453           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.767           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.988           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.151           ms/op
ClientGrpc.listUser                       sample  246544   3.892 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.943           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.612           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.948           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.542           ms/op
