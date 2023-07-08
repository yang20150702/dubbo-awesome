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
# Warmup Iteration   1: 4.151 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 10.002 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.550 ±(99.9%) 2.489 ops/ms [Average]
  (min, avg, max) = (10.452, 10.550, 10.706), stdev = 0.136
  CI (99.9%): [8.062, 13.039] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.910 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.923 ops/ms
Iteration   1: 10.822 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 11.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.932 ±(99.9%) 3.119 ops/ms [Average]
  (min, avg, max) = (10.822, 10.932, 11.129), stdev = 0.171
  CI (99.9%): [7.813, 14.052] (assumes normal distribution)


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
# Warmup Iteration   1: 6.776 ops/ms
# Warmup Iteration   2: 10.188 ops/ms
# Warmup Iteration   3: 10.475 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.555 ops/ms
Iteration   3: 10.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 0.777 ops/ms [Average]
  (min, avg, max) = (10.486, 10.535, 10.564), stdev = 0.043
  CI (99.9%): [9.758, 11.312] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ops/ms
# Warmup Iteration   2: 7.733 ops/ms
# Warmup Iteration   3: 8.010 ops/ms
Iteration   1: 7.932 ops/ms
Iteration   2: 8.137 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.114 ±(99.9%) 3.135 ops/ms [Average]
  (min, avg, max) = (7.932, 8.114, 8.273), stdev = 0.172
  CI (99.9%): [4.979, 11.249] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.605 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.019 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.033 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.005, 3.033, 3.077), stdev = 0.038
  CI (99.9%): [2.338, 3.729] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.002 ms/op
Iteration   1: 2.907 ±(99.9%) 0.003 ms/op
Iteration   2: 2.856 ±(99.9%) 0.003 ms/op
Iteration   3: 2.901 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.888 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (2.856, 2.888, 2.907), stdev = 0.028
  CI (99.9%): [2.379, 3.397] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.053 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.045, 3.053, 3.067), stdev = 0.012
  CI (99.9%): [2.838, 3.269] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.471 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.037 ms/op
Iteration   1: 3.867 ±(99.9%) 0.011 ms/op
Iteration   2: 3.857 ±(99.9%) 0.009 ms/op
Iteration   3: 3.817 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.847 ±(99.9%) 0.480 ms/op [Average]
  (min, avg, max) = (3.817, 3.847, 3.867), stdev = 0.026
  CI (99.9%): [3.367, 4.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.250 ms/op
                 createUser·p0.9999: 17.170 ms/op
                 createUser·p1.00:   17.793 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.313 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.830 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.452 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.477 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 21.522 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317514
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22069 
    [ 2.500,  5.000) = 293860 
    [ 5.000,  7.500) = 1227 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.313 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.700 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.975 ms/op
     p(99.9900) =     21.045 ms/op
     p(99.9990) =     21.878 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.951 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 13.358 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  6.988 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   3: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  10.150 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329027
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 990 
    [ 1.250,  2.500) = 30328 
    [ 2.500,  3.750) = 289020 
    [ 3.750,  5.000) = 7387 
    [ 5.000,  6.250) = 782 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     16.126 ms/op
     p(99.9990) =     17.063 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.006 ms/op
Iteration   1: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 14.905 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  7.765 ms/op
                 getUser·p0.9999: 15.619 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   3: 3.072 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.674 ms/op
                 getUser·p0.9999: 16.980 ms/op
                 getUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310475
  mean =      3.093 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 421 
    [ 1.250,  2.500) = 17420 
    [ 2.500,  3.750) = 270195 
    [ 3.750,  5.000) = 20899 
    [ 5.000,  6.250) = 994 
    [ 6.250,  7.500) = 208 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.705 ms/op
     p(99.9900) =     16.430 ms/op
     p(99.9990) =     18.555 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 5.186 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
Iteration   1: 4.051 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.798 ms/op
                 listUser·p0.9999: 26.742 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 19.400 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   3: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.764 ms/op
                 listUser·p0.99:   7.130 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 23.724 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238851
  mean =      4.019 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2414 
    [ 2.500,  5.000) = 213193 
    [ 5.000,  7.500) = 21681 
    [ 7.500, 10.000) = 1117 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 180 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     25.432 ms/op
     p(99.9990) =     27.245 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.550 ± 2.489  ops/ms
ClientGrpc.existUser                       thrpt       3  10.932 ± 3.119  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 0.777  ops/ms
ClientGrpc.listUser                        thrpt       3   8.114 ± 3.135  ops/ms
ClientGrpc.createUser                       avgt       3   3.033 ± 0.695   ms/op
ClientGrpc.existUser                        avgt       3   2.888 ± 0.509   ms/op
ClientGrpc.getUser                          avgt       3   3.053 ± 0.215   ms/op
ClientGrpc.listUser                         avgt       3   3.847 ± 0.480   ms/op
ClientGrpc.createUser                     sample  317514   3.024 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.313           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.700           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.975           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.045           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.053           ms/op
ClientGrpc.existUser                      sample  329027   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.963           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.126           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  310475   3.093 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.733           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.705           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.430           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.874           ms/op
ClientGrpc.listUser                       sample  238851   4.019 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.432           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.394           ms/op
