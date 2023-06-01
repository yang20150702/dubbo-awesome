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
# Warmup Iteration   1: 4.766 ops/ms
# Warmup Iteration   2: 9.177 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.769 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.694 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (10.651, 10.694, 10.769), stdev = 0.065
  CI (99.9%): [9.503, 11.885] (assumes normal distribution)


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
# Warmup Iteration   1: 7.856 ops/ms
# Warmup Iteration   2: 10.859 ops/ms
# Warmup Iteration   3: 11.024 ops/ms
Iteration   1: 11.172 ops/ms
Iteration   2: 11.409 ops/ms
Iteration   3: 11.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.214 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (11.062, 11.214, 11.409), stdev = 0.177
  CI (99.9%): [7.976, 14.453] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 10.390 ops/ms
# Warmup Iteration   3: 10.648 ops/ms
Iteration   1: 10.731 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.787 ±(99.9%) 1.110 ops/ms [Average]
  (min, avg, max) = (10.731, 10.787, 10.851), stdev = 0.061
  CI (99.9%): [9.677, 11.896] (assumes normal distribution)


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
# Warmup Iteration   1: 6.691 ops/ms
# Warmup Iteration   2: 8.208 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.296 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.322 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (8.254, 8.322, 8.417), stdev = 0.085
  CI (99.9%): [6.776, 9.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.101 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.004 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.986 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (2.964, 2.986, 3.011), stdev = 0.024
  CI (99.9%): [2.550, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.934 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.004 ms/op
Iteration   1: 2.931 ±(99.9%) 0.003 ms/op
Iteration   2: 2.870 ±(99.9%) 0.004 ms/op
Iteration   3: 2.845 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (2.845, 2.882, 2.931), stdev = 0.044
  CI (99.9%): [2.080, 3.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.002 ms/op
Iteration   3: 2.966 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (2.966, 2.996, 3.041), stdev = 0.040
  CI (99.9%): [2.273, 3.719] (assumes normal distribution)


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
# Warmup Iteration   1: 4.863 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.025 ms/op
Iteration   1: 3.936 ±(99.9%) 0.025 ms/op
Iteration   2: 3.862 ±(99.9%) 0.017 ms/op
Iteration   3: 3.861 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.861, 3.886, 3.936), stdev = 0.043
  CI (99.9%): [3.105, 4.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.457 ms/op
                 createUser·p0.999:  6.459 ms/op
                 createUser·p0.9999: 14.333 ms/op
                 createUser·p1.00:   15.663 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.474 ms/op
                 createUser·p0.9999: 17.531 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.598 ms/op
                 createUser·p0.9999: 13.871 ms/op
                 createUser·p1.00:   15.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321688
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1900 
    [ 1.250,  2.500) = 27645 
    [ 2.500,  3.750) = 275812 
    [ 3.750,  5.000) = 14974 
    [ 5.000,  6.250) = 795 
    [ 6.250,  7.500) = 154 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      8.260 ms/op
     p(99.9900) =     16.644 ms/op
     p(99.9990) =     17.851 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.005 ms/op
Iteration   1: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.250 ms/op
                 existUser·p0.9999: 12.793 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   2: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  11.551 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.649 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  9.145 ms/op
                 existUser·p0.9999: 15.186 ms/op
                 existUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333523
  mean =      2.877 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2317 
    [ 1.250,  2.500) = 47786 
    [ 2.500,  3.750) = 273173 
    [ 3.750,  5.000) = 9250 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 151 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     13.658 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.211 ms/op
                 getUser·p0.9999: 11.342 ms/op
                 getUser·p1.00:   11.485 ms/op

Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.563 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.185 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.637 ms/op
                 getUser·p0.9999: 15.403 ms/op
                 getUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320642
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25591 
    [ 2.500,  5.000) = 293960 
    [ 5.000,  7.500) = 856 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.991 ms/op
     p(99.9900) =     19.524 ms/op
     p(99.9990) =     20.146 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 5.266 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.681 ms/op
                 listUser·p0.9999: 20.315 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.541 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.564 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.890 ms/op
                 listUser·p0.9999: 24.016 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242688
  mean =      3.953 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2730 
    [ 2.500,  5.000) = 217265 
    [ 5.000,  7.500) = 21613 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.948 ms/op
     p(99.9900) =     23.617 ms/op
     p(99.9990) =     24.370 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.694 ± 1.191  ops/ms
ClientGrpc.existUser                       thrpt       3  11.214 ± 3.238  ops/ms
ClientGrpc.getUser                         thrpt       3  10.787 ± 1.110  ops/ms
ClientGrpc.listUser                        thrpt       3   8.322 ± 1.546  ops/ms
ClientGrpc.createUser                       avgt       3   2.986 ± 0.435   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 0.802   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.723   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.781   ms/op
ClientGrpc.createUser                     sample  321688   2.985 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.675           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.260           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.644           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.924           ms/op
ClientGrpc.existUser                      sample  333523   2.877 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.175           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.658           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.039           ms/op
ClientGrpc.getUser                        sample  320642   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.486           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.991           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.524           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  242688   3.953 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.693           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.948           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.617           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.510           ms/op
