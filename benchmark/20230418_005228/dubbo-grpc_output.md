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
# Warmup Iteration   1: 4.161 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 9.917 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 11.211 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.881 ±(99.9%) 5.217 ops/ms [Average]
  (min, avg, max) = (10.699, 10.881, 11.211), stdev = 0.286
  CI (99.9%): [5.664, 16.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.042 ops/ms
# Warmup Iteration   2: 10.767 ops/ms
# Warmup Iteration   3: 11.160 ops/ms
Iteration   1: 11.330 ops/ms
Iteration   2: 11.125 ops/ms
Iteration   3: 11.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.179 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (11.082, 11.179, 11.330), stdev = 0.133
  CI (99.9%): [8.760, 13.599] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.174 ops/ms
# Warmup Iteration   2: 10.354 ops/ms
# Warmup Iteration   3: 10.494 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 11.129 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.804 ±(99.9%) 5.665 ops/ms [Average]
  (min, avg, max) = (10.510, 10.804, 11.129), stdev = 0.311
  CI (99.9%): [5.138, 16.469] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.170 ops/ms
# Warmup Iteration   2: 7.740 ops/ms
# Warmup Iteration   3: 7.870 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.153 ±(99.9%) 0.701 ops/ms [Average]
  (min, avg, max) = (8.124, 8.153, 8.196), stdev = 0.038
  CI (99.9%): [7.452, 8.854] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.431 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.002 ms/op
Iteration   3: 3.062 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (3.033, 3.045, 3.062), stdev = 0.015
  CI (99.9%): [2.762, 3.327] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.865 ±(99.9%) 0.003 ms/op
Iteration   1: 2.917 ±(99.9%) 0.003 ms/op
Iteration   2: 2.822 ±(99.9%) 0.003 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.872 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (2.822, 2.872, 2.917), stdev = 0.048
  CI (99.9%): [2.000, 3.745] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.004 ms/op
Iteration   1: 3.093 ±(99.9%) 0.001 ms/op
Iteration   2: 3.079 ±(99.9%) 0.003 ms/op
Iteration   3: 2.997 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 0.948 ms/op [Average]
  (min, avg, max) = (2.997, 3.057, 3.093), stdev = 0.052
  CI (99.9%): [2.109, 4.004] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.065 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.015 ms/op
Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
Iteration   2: 3.980 ±(99.9%) 0.027 ms/op
Iteration   3: 3.918 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.943 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.918, 3.943, 3.980), stdev = 0.033
  CI (99.9%): [3.339, 4.546] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.526 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.799 ms/op
                 createUser·p0.9999: 12.750 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   2: 3.037 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.076 ms/op
                 createUser·p0.999:  7.079 ms/op
                 createUser·p0.9999: 16.113 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 3.026 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.307 ms/op
                 createUser·p0.9999: 18.575 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317051
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 16960 
    [ 2.500,  3.750) = 290370 
    [ 3.750,  5.000) = 8382 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 220 
    [ 7.500,  8.750) = 125 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.921 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     18.967 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.005 ms/op
Iteration   1: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.064 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 12.386 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   2: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.595 ms/op
                 existUser·p0.9999: 14.695 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.187 ms/op
                 existUser·p0.9999: 16.457 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332253
  mean =      2.889 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1975 
    [ 1.250,  2.500) = 37885 
    [ 2.500,  3.750) = 284886 
    [ 3.750,  5.000) = 6411 
    [ 5.000,  6.250) = 684 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     15.745 ms/op
     p(99.9990) =     16.832 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.163 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.208 ms/op
                 getUser·p0.9999: 14.075 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.270 ms/op
                 getUser·p0.9999: 16.041 ms/op
                 getUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315891
  mean =      3.037 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 558 
    [ 1.250,  2.500) = 18271 
    [ 2.500,  3.750) = 280617 
    [ 3.750,  5.000) = 14909 
    [ 5.000,  6.250) = 1008 
    [ 6.250,  7.500) = 241 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.382 ms/op
     p(99.9900) =     15.965 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.010 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.565 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 17.098 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   2: 3.896 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.601 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.048 ms/op
                 listUser·p0.999:  15.478 ms/op
                 listUser·p0.9999: 22.905 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.708 ms/op
                 listUser·p0.9999: 22.740 ms/op
                 listUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243130
  mean =      3.947 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3149 
    [ 2.500,  5.000) = 217029 
    [ 5.000,  7.500) = 21548 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.334 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.171 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.881 ± 5.217  ops/ms
ClientGrpc.existUser                       thrpt       3  11.179 ± 2.420  ops/ms
ClientGrpc.getUser                         thrpt       3  10.804 ± 5.665  ops/ms
ClientGrpc.listUser                        thrpt       3   8.153 ± 0.701  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.282   ms/op
ClientGrpc.existUser                        avgt       3   2.872 ± 0.872   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 0.948   ms/op
ClientGrpc.listUser                         avgt       3   3.943 ± 0.604   ms/op
ClientGrpc.createUser                     sample  317051   3.029 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.856           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.921           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.843           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.104           ms/op
ClientGrpc.existUser                      sample  332253   2.889 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.564           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.554           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.745           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.203           ms/op
ClientGrpc.getUser                        sample  315891   3.037 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.382           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.965           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  243130   3.947 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.601           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.334           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.790           ms/op
