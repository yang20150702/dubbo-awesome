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
# Warmup Iteration   1: 4.599 ops/ms
# Warmup Iteration   2: 9.235 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.469 ±(99.9%) 4.776 ops/ms [Average]
  (min, avg, max) = (10.227, 10.469, 10.747), stdev = 0.262
  CI (99.9%): [5.693, 15.245] (assumes normal distribution)


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
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 10.498 ops/ms
# Warmup Iteration   3: 11.031 ops/ms
Iteration   1: 10.968 ops/ms
Iteration   2: 11.096 ops/ms
Iteration   3: 11.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.058 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (10.968, 11.058, 11.109), stdev = 0.078
  CI (99.9%): [9.642, 12.473] (assumes normal distribution)


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
# Warmup Iteration   1: 6.614 ops/ms
# Warmup Iteration   2: 9.909 ops/ms
# Warmup Iteration   3: 10.397 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.594 ops/ms
Iteration   3: 10.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.439 ±(99.9%) 2.540 ops/ms [Average]
  (min, avg, max) = (10.323, 10.439, 10.594), stdev = 0.139
  CI (99.9%): [7.900, 12.979] (assumes normal distribution)


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
# Warmup Iteration   1: 5.675 ops/ms
# Warmup Iteration   2: 7.797 ops/ms
# Warmup Iteration   3: 7.908 ops/ms
Iteration   1: 8.061 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 8.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.181 ±(99.9%) 4.332 ops/ms [Average]
  (min, avg, max) = (8.027, 8.181, 8.454), stdev = 0.237
  CI (99.9%): [3.849, 12.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.036 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.996 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (2.929, 2.996, 3.036), stdev = 0.058
  CI (99.9%): [1.938, 4.053] (assumes normal distribution)


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.003 ms/op
Iteration   1: 2.894 ±(99.9%) 0.002 ms/op
Iteration   2: 2.956 ±(99.9%) 0.002 ms/op
Iteration   3: 2.884 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.911 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (2.884, 2.911, 2.956), stdev = 0.039
  CI (99.9%): [2.203, 3.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (3.036, 3.058, 3.070), stdev = 0.019
  CI (99.9%): [2.720, 3.396] (assumes normal distribution)


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.160 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.016 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
Iteration   2: 3.961 ±(99.9%) 0.016 ms/op
Iteration   3: 3.940 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.959 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (3.940, 3.959, 3.976), stdev = 0.018
  CI (99.9%): [3.626, 4.292] (assumes normal distribution)


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 24.653 ms/op
                 createUser·p1.00:   30.474 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.894 ms/op
                 createUser·p0.9999: 14.590 ms/op
                 createUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316526
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22410 
    [ 2.500,  5.000) = 292614 
    [ 5.000,  7.500) = 1086 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.642 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     24.865 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.040 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  5.459 ms/op
                 existUser·p0.9999: 11.817 ms/op
                 existUser·p1.00:   12.042 ms/op

Iteration   2: 2.800 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.472 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.000 ms/op
                 existUser·p0.9999: 14.214 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.776 ms/op
                 existUser·p0.9999: 26.677 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330415
  mean =      2.906 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38766 
    [ 2.500,  5.000) = 290581 
    [ 5.000,  7.500) = 867 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.472 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.439 ms/op
     p(99.9900) =     16.826 ms/op
     p(99.9990) =     26.915 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.250 ms/op
                 getUser·p0.9999: 19.091 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.873 ms/op
                 getUser·p0.9999: 14.107 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 17.315 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313520
  mean =      3.060 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 961 
    [ 1.250,  2.500) = 17570 
    [ 2.500,  3.750) = 278158 
    [ 3.750,  5.000) = 14988 
    [ 5.000,  6.250) = 1178 
    [ 6.250,  7.500) = 380 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.291 ms/op
     p(99.9900) =     18.568 ms/op
     p(99.9990) =     19.259 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 5.750 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.913 ms/op
                 listUser·p0.999:  14.421 ms/op
                 listUser·p0.9999: 19.625 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.456 ms/op
                 listUser·p0.9999: 21.137 ms/op
                 listUser·p1.00:   21.463 ms/op

Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 18.758 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242478
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2637 
    [ 2.500,  5.000) = 217836 
    [ 5.000,  7.500) = 20735 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     21.402 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.469 ± 4.776  ops/ms
ClientGrpc.existUser                       thrpt       3  11.058 ± 1.416  ops/ms
ClientGrpc.getUser                         thrpt       3  10.439 ± 2.540  ops/ms
ClientGrpc.listUser                        thrpt       3   8.181 ± 4.332  ops/ms
ClientGrpc.createUser                       avgt       3   2.996 ± 1.057   ms/op
ClientGrpc.existUser                        avgt       3   2.911 ± 0.708   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   3.959 ± 0.333   ms/op
ClientGrpc.createUser                     sample  316526   3.035 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.642           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.495           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.474           ms/op
ClientGrpc.existUser                      sample  330415   2.906 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.472           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.826           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.001           ms/op
ClientGrpc.getUser                        sample  313520   3.060 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.729           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.291           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.568           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  242478   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.463           ms/op
