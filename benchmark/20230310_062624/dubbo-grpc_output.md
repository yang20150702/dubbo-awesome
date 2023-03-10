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
# Warmup Iteration   1: 4.865 ops/ms
# Warmup Iteration   2: 9.760 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.852 ops/ms
Iteration   3: 11.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.832 ±(99.9%) 3.689 ops/ms [Average]
  (min, avg, max) = (10.621, 10.832, 11.024), stdev = 0.202
  CI (99.9%): [7.143, 14.521] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.003 ops/ms
# Warmup Iteration   2: 10.959 ops/ms
# Warmup Iteration   3: 11.469 ops/ms
Iteration   1: 11.348 ops/ms
Iteration   2: 11.267 ops/ms
Iteration   3: 11.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.335 ±(99.9%) 1.138 ops/ms [Average]
  (min, avg, max) = (11.267, 11.335, 11.390), stdev = 0.062
  CI (99.9%): [10.197, 12.473] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.236 ops/ms
# Warmup Iteration   2: 10.428 ops/ms
# Warmup Iteration   3: 10.825 ops/ms
Iteration   1: 10.908 ops/ms
Iteration   2: 10.942 ops/ms
Iteration   3: 10.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.931 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (10.908, 10.931, 10.942), stdev = 0.019
  CI (99.9%): [10.578, 11.284] (assumes normal distribution)


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
# Warmup Iteration   1: 7.627 ops/ms
# Warmup Iteration   2: 7.571 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.543 ops/ms
Iteration   3: 8.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.341 ±(99.9%) 3.239 ops/ms [Average]
  (min, avg, max) = (8.210, 8.341, 8.543), stdev = 0.178
  CI (99.9%): [5.102, 11.580] (assumes normal distribution)


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.004 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.002 ms/op
Iteration   3: 2.882 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.916 ±(99.9%) 0.739 ms/op [Average]
  (min, avg, max) = (2.882, 2.916, 2.960), stdev = 0.041
  CI (99.9%): [2.176, 3.655] (assumes normal distribution)


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
# Warmup Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.869 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.833 ±(99.9%) 0.003 ms/op
Iteration   1: 2.795 ±(99.9%) 0.004 ms/op
Iteration   2: 2.838 ±(99.9%) 0.003 ms/op
Iteration   3: 2.847 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.827 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.795, 2.827, 2.847), stdev = 0.028
  CI (99.9%): [2.317, 3.336] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.004 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.957 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (2.937, 2.957, 2.987), stdev = 0.027
  CI (99.9%): [2.472, 3.442] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.774 ±(99.9%) 0.006 ms/op
Iteration   1: 3.904 ±(99.9%) 0.008 ms/op
Iteration   2: 3.830 ±(99.9%) 0.008 ms/op
Iteration   3: 3.966 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.830, 3.900, 3.966), stdev = 0.068
  CI (99.9%): [2.664, 5.136] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.951 ±(99.9%) 0.007 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.391 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.436 ms/op
                 createUser·p0.9999: 21.663 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 21.826 ms/op
                 createUser·p1.00:   22.118 ms/op

Iteration   3: 2.935 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.890 ms/op
                 createUser·p0.9999: 19.828 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326333
  mean =      2.942 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32342 
    [ 2.500,  5.000) = 292949 
    [ 5.000,  7.500) = 701 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.788 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.265 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.813 ±(99.9%) 0.006 ms/op
Iteration   1: 2.828 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 11.305 ms/op
                 existUser·p1.00:   11.649 ms/op

Iteration   2: 2.772 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.488 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.314 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.149 ms/op
                 existUser·p0.9999: 12.541 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   3: 2.831 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.483 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.759 ms/op
                 existUser·p0.9999: 26.345 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341600
  mean =      2.810 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62504 
    [ 2.500,  5.000) = 278289 
    [ 5.000,  7.500) = 590 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.498 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.046 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     27.168 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.711 ms/op
                 getUser·p0.9999: 11.463 ms/op
                 getUser·p1.00:   11.747 ms/op

Iteration   2: 2.871 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.900 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.478 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  6.641 ms/op
                 getUser·p0.9999: 19.919 ms/op
                 getUser·p1.00:   20.316 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.892 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.160 ms/op
                 getUser·p0.999:  6.469 ms/op
                 getUser·p0.9999: 14.596 ms/op
                 getUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 330279
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42767 
    [ 2.500,  5.000) = 286557 
    [ 5.000,  7.500) = 706 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     15.071 ms/op
     p(99.9990) =     20.231 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
Iteration   1: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  11.839 ms/op
                 listUser·p0.9999: 19.057 ms/op
                 listUser·p1.00:   19.759 ms/op

Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.957 ms/op
                 listUser·p0.9999: 14.315 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.644 ms/op
                 listUser·p0.9999: 20.696 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246883
  mean =      3.888 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4454 
    [ 2.500,  5.000) = 221700 
    [ 5.000,  7.500) = 19568 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     19.737 ms/op
     p(99.9990) =     21.238 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.832 ± 3.689  ops/ms
ClientGrpc.existUser                       thrpt       3  11.335 ± 1.138  ops/ms
ClientGrpc.getUser                         thrpt       3  10.931 ± 0.353  ops/ms
ClientGrpc.listUser                        thrpt       3   8.341 ± 3.239  ops/ms
ClientGrpc.createUser                       avgt       3   2.916 ± 0.739   ms/op
ClientGrpc.existUser                        avgt       3   2.827 ± 0.510   ms/op
ClientGrpc.getUser                          avgt       3   2.957 ± 0.485   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 1.236   ms/op
ClientGrpc.createUser                     sample  326333   2.942 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.502           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.400           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.788           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.561           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.446           ms/op
ClientGrpc.existUser                      sample  341600   2.810 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.483           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.806           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.046           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.451           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.361           ms/op
ClientGrpc.getUser                        sample  330279   2.904 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.912           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.636           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.316           ms/op
ClientGrpc.listUser                       sample  246883   3.888 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.954           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.599           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.737           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.365           ms/op
