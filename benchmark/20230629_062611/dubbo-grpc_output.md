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
# Warmup Iteration   1: 5.045 ops/ms
# Warmup Iteration   2: 9.504 ops/ms
# Warmup Iteration   3: 10.461 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.817 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (10.764, 10.817, 10.920), stdev = 0.089
  CI (99.9%): [9.190, 12.443] (assumes normal distribution)


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
# Warmup Iteration   1: 7.837 ops/ms
# Warmup Iteration   2: 10.829 ops/ms
# Warmup Iteration   3: 11.320 ops/ms
Iteration   1: 11.403 ops/ms
Iteration   2: 11.428 ops/ms
Iteration   3: 11.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.438 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (11.403, 11.438, 11.481), stdev = 0.040
  CI (99.9%): [10.710, 12.165] (assumes normal distribution)


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
# Warmup Iteration   1: 7.345 ops/ms
# Warmup Iteration   2: 10.379 ops/ms
# Warmup Iteration   3: 10.579 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.921 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.740 ±(99.9%) 3.016 ops/ms [Average]
  (min, avg, max) = (10.596, 10.740, 10.921), stdev = 0.165
  CI (99.9%): [7.724, 13.757] (assumes normal distribution)


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
# Warmup Iteration   1: 6.175 ops/ms
# Warmup Iteration   2: 7.954 ops/ms
# Warmup Iteration   3: 8.430 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.330 ops/ms
Iteration   3: 8.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.430 ±(99.9%) 2.244 ops/ms [Average]
  (min, avg, max) = (8.330, 8.430, 8.567), stdev = 0.123
  CI (99.9%): [6.187, 10.674] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.004 ms/op
Iteration   1: 2.975 ±(99.9%) 0.003 ms/op
Iteration   2: 2.974 ±(99.9%) 0.004 ms/op
Iteration   3: 2.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.968 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.955, 2.968, 2.975), stdev = 0.011
  CI (99.9%): [2.766, 3.170] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.705 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.948 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.825 ±(99.9%) 0.004 ms/op
Iteration   1: 2.843 ±(99.9%) 0.003 ms/op
Iteration   2: 2.803 ±(99.9%) 0.004 ms/op
Iteration   3: 2.822 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.823 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.803, 2.823, 2.843), stdev = 0.020
  CI (99.9%): [2.461, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.004 ms/op
Iteration   1: 2.944 ±(99.9%) 0.004 ms/op
Iteration   2: 2.920 ±(99.9%) 0.003 ms/op
Iteration   3: 2.929 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.931 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.920, 2.931, 2.944), stdev = 0.012
  CI (99.9%): [2.712, 3.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.898 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.008 ms/op
Iteration   1: 3.757 ±(99.9%) 0.013 ms/op
Iteration   2: 3.636 ±(99.9%) 0.009 ms/op
Iteration   3: 3.813 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.735 ±(99.9%) 1.654 ms/op [Average]
  (min, avg, max) = (3.636, 3.735, 3.813), stdev = 0.091
  CI (99.9%): [2.081, 5.390] (assumes normal distribution)


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.627 ms/op
                 createUser·p0.9999: 11.939 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.162 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.496 ms/op
                 createUser·p0.9999: 26.918 ms/op
                 createUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318881
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31445 
    [ 2.500,  5.000) = 286145 
    [ 5.000,  7.500) = 843 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.737 ms/op
     p(99.9900) =     25.727 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.804 ±(99.9%) 0.007 ms/op
Iteration   1: 2.840 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.346 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  7.628 ms/op
                 existUser·p0.9999: 13.721 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.576 ms/op
                 existUser·p0.9999: 12.617 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.365 ms/op
                 existUser·p0.999:  10.376 ms/op
                 existUser·p0.9999: 15.688 ms/op
                 existUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336054
  mean =      2.855 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2240 
    [ 1.250,  2.500) = 43590 
    [ 2.500,  3.750) = 282368 
    [ 3.750,  5.000) = 6987 
    [ 5.000,  6.250) = 334 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.206 ms/op
     p(99.9000) =      9.056 ms/op
     p(99.9900) =     14.267 ms/op
     p(99.9990) =     16.039 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.622 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 12.994 ms/op
                 getUser·p1.00:   13.091 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.346 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.055 ms/op
                 getUser·p0.999:  5.743 ms/op
                 getUser·p0.9999: 17.433 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   3: 2.968 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.193 ms/op
                 getUser·p0.9999: 16.133 ms/op
                 getUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326167
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2104 
    [ 1.250,  2.500) = 29570 
    [ 2.500,  3.750) = 282003 
    [ 3.750,  5.000) = 11375 
    [ 5.000,  6.250) = 780 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 52 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.300 ms/op
     p(99.9900) =     17.110 ms/op
     p(99.9990) =     17.621 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.010 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  11.881 ms/op
                 listUser·p0.9999: 14.455 ms/op
                 listUser·p1.00:   14.909 ms/op

Iteration   2: 3.822 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.012 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.091 ms/op
                 listUser·p0.9999: 20.304 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 3.837 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.960 ms/op
                 listUser·p0.9999: 21.855 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250905
  mean =      3.826 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5387 
    [ 2.500,  5.000) = 223936 
    [ 5.000,  7.500) = 20516 
    [ 7.500, 10.000) = 578 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     20.608 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.817 ± 1.626  ops/ms
ClientGrpc.existUser                       thrpt       3  11.438 ± 0.728  ops/ms
ClientGrpc.getUser                         thrpt       3  10.740 ± 3.016  ops/ms
ClientGrpc.listUser                        thrpt       3   8.430 ± 2.244  ops/ms
ClientGrpc.createUser                       avgt       3   2.968 ± 0.202   ms/op
ClientGrpc.existUser                        avgt       3   2.823 ± 0.361   ms/op
ClientGrpc.getUser                          avgt       3   2.931 ± 0.219   ms/op
ClientGrpc.listUser                         avgt       3   3.735 ± 1.654   ms/op
ClientGrpc.createUser                     sample  318881   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.530           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.737           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.727           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.820           ms/op
ClientGrpc.existUser                      sample  336054   2.855 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.466           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.843           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.206           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.056           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.267           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.155           ms/op
ClientGrpc.getUser                        sample  326167   2.943 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.537           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.428           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.300           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.110           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  250905   3.826 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.841           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.550           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.608           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
