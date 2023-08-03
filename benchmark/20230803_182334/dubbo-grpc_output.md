# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ops/ms
# Warmup Iteration   2: 9.069 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.534 ops/ms
Iteration   2: 10.462 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.495 ±(99.9%) 0.662 ops/ms [Average]
  (min, avg, max) = (10.462, 10.495, 10.534), stdev = 0.036
  CI (99.9%): [9.833, 11.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.703 ops/ms
# Warmup Iteration   2: 10.792 ops/ms
# Warmup Iteration   3: 11.130 ops/ms
Iteration   1: 11.245 ops/ms
Iteration   2: 11.056 ops/ms
Iteration   3: 11.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.115 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (11.042, 11.115, 11.245), stdev = 0.113
  CI (99.9%): [9.051, 13.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.065 ops/ms
# Warmup Iteration   2: 10.208 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.548 ±(99.9%) 0.104 ops/ms [Average]
  (min, avg, max) = (10.544, 10.548, 10.555), stdev = 0.006
  CI (99.9%): [10.444, 10.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.706 ops/ms
# Warmup Iteration   2: 8.037 ops/ms
# Warmup Iteration   3: 8.169 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.215 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (8.149, 8.215, 8.293), stdev = 0.073
  CI (99.9%): [6.886, 9.544] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.063 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.060 ±(99.9%) 0.004 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.018 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.018, 3.037, 3.060), stdev = 0.021
  CI (99.9%): [2.648, 3.426] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.009 ms/op
Iteration   1: 2.898 ±(99.9%) 0.003 ms/op
Iteration   2: 2.871 ±(99.9%) 0.004 ms/op
Iteration   3: 2.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (2.871, 2.907, 2.951), stdev = 0.041
  CI (99.9%): [2.162, 3.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.905 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.016 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.028 ±(99.9%) 0.253 ms/op [Average]
  (min, avg, max) = (3.016, 3.028, 3.043), stdev = 0.014
  CI (99.9%): [2.775, 3.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.635 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.010 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
Iteration   2: 3.902 ±(99.9%) 0.025 ms/op
Iteration   3: 3.935 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.916 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (3.902, 3.916, 3.935), stdev = 0.017
  CI (99.9%): [3.604, 4.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.681 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.474 ms/op
                 createUser·p0.999:  8.774 ms/op
                 createUser·p0.9999: 17.986 ms/op
                 createUser·p1.00:   18.350 ms/op

Iteration   2: 3.040 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.213 ms/op
                 createUser·p0.9999: 13.050 ms/op
                 createUser·p1.00:   13.206 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  10.165 ms/op
                 createUser·p0.9999: 16.923 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316223
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1345 
    [ 1.250,  2.500) = 18692 
    [ 2.500,  3.750) = 281294 
    [ 3.750,  5.000) = 12799 
    [ 5.000,  6.250) = 967 
    [ 6.250,  7.500) = 567 
    [ 7.500,  8.750) = 222 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.089 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.274 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 12.027 ms/op
                 existUser·p1.00:   12.337 ms/op

Iteration   2: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.148 ms/op
                 existUser·p0.9999: 22.282 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 2.916 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.954 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328442
  mean =      2.922 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33290 
    [ 2.500,  5.000) = 293505 
    [ 5.000,  7.500) = 1231 
    [ 7.500, 10.000) = 192 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.746 ms/op
     p(99.9900) =     24.454 ms/op
     p(99.9990) =     25.582 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 17.940 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.177 ms/op
                 getUser·p0.999:  8.066 ms/op
                 getUser·p0.9999: 15.490 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.435 ms/op
                 getUser·p0.9999: 16.867 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313145
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1807 
    [ 1.250,  2.500) = 22844 
    [ 2.500,  3.750) = 265766 
    [ 3.750,  5.000) = 19995 
    [ 5.000,  6.250) = 1600 
    [ 6.250,  7.500) = 675 
    [ 7.500,  8.750) = 243 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.304 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.329 ms/op
                 listUser·p0.9999: 18.589 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.473 ms/op
                 listUser·p0.9999: 18.083 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.718 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245125
  mean =      3.914 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3708 
    [ 2.500,  5.000) = 218921 
    [ 5.000,  7.500) = 20873 
    [ 7.500, 10.000) = 1117 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.036 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.924 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.495 ± 0.662  ops/ms
ClientGrpc.existUser                       thrpt       3  11.115 ± 2.064  ops/ms
ClientGrpc.getUser                         thrpt       3  10.548 ± 0.104  ops/ms
ClientGrpc.listUser                        thrpt       3   8.215 ± 1.329  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.389   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 0.745   ms/op
ClientGrpc.getUser                          avgt       3   3.028 ± 0.253   ms/op
ClientGrpc.listUser                         avgt       3   3.916 ± 0.312   ms/op
ClientGrpc.createUser                     sample  316223   3.037 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.089           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.350           ms/op
ClientGrpc.existUser                      sample  328442   2.922 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.552           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.746           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.454           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.625           ms/op
ClientGrpc.getUser                        sample  313145   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.383           ms/op
ClientGrpc.listUser                       sample  245125   3.914 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.718           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.752           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.036           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.774           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
