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
# Warmup Iteration   1: 4.616 ops/ms
# Warmup Iteration   2: 9.389 ops/ms
# Warmup Iteration   3: 10.142 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.555 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (10.458, 10.555, 10.695), stdev = 0.124
  CI (99.9%): [8.293, 12.817] (assumes normal distribution)


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
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 11.018 ops/ms
# Warmup Iteration   3: 10.980 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.297 ops/ms
Iteration   3: 11.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.201 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (11.101, 11.201, 11.297), stdev = 0.098
  CI (99.9%): [9.415, 12.987] (assumes normal distribution)


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
# Warmup Iteration   1: 7.305 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.670 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.627 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (10.470, 10.627, 10.797), stdev = 0.164
  CI (99.9%): [7.640, 13.614] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.746 ops/ms
# Warmup Iteration   2: 7.894 ops/ms
# Warmup Iteration   3: 8.183 ops/ms
Iteration   1: 8.339 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.237 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (8.142, 8.237, 8.339), stdev = 0.099
  CI (99.9%): [6.433, 10.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.119 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.992, 3.014, 3.025), stdev = 0.018
  CI (99.9%): [2.678, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.003 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.845 ±(99.9%) 0.003 ms/op
Iteration   3: 2.875 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (2.845, 2.886, 2.937), stdev = 0.047
  CI (99.9%): [2.027, 3.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.943 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.937, 2.943, 2.953), stdev = 0.009
  CI (99.9%): [2.784, 3.101] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.033 ms/op
Iteration   1: 3.909 ±(99.9%) 0.008 ms/op
Iteration   2: 3.813 ±(99.9%) 0.029 ms/op
Iteration   3: 3.862 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 0.875 ms/op [Average]
  (min, avg, max) = (3.813, 3.861, 3.909), stdev = 0.048
  CI (99.9%): [2.986, 4.737] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.216 ms/op
                 createUser·p0.999:  7.127 ms/op
                 createUser·p0.9999: 13.833 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.968 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.931 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.525 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321638
  mean =      2.984 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1733 
    [ 1.250,  2.500) = 20160 
    [ 2.500,  3.750) = 286691 
    [ 3.750,  5.000) = 11714 
    [ 5.000,  6.250) = 656 
    [ 6.250,  7.500) = 314 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.998 ms/op
     p(99.9900) =     15.513 ms/op
     p(99.9990) =     17.266 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.005 ms/op
Iteration   1: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.446 ms/op
                 existUser·p0.999:  9.570 ms/op
                 existUser·p0.9999: 11.466 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   2: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  5.984 ms/op
                 existUser·p0.9999: 12.564 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.891 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333066
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3810 
    [ 1.250,  2.500) = 37691 
    [ 2.500,  3.750) = 282069 
    [ 3.750,  5.000) = 7826 
    [ 5.000,  6.250) = 868 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.874 ms/op
     p(99.9900) =     16.729 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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
# Warmup Iteration   1: 3.980 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.535 ms/op
                 getUser·p0.9999: 11.507 ms/op
                 getUser·p1.00:   11.698 ms/op

Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.128 ms/op
                 getUser·p0.9999: 15.159 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.760 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.326 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  5.612 ms/op
                 getUser·p0.9999: 25.925 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322888
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26399 
    [ 2.500,  5.000) = 295626 
    [ 5.000,  7.500) = 653 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.562 ms/op
     p(99.9900) =     22.588 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
Iteration   1: 3.957 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.223 ms/op
                 listUser·p0.9999: 17.561 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.836 ms/op
                 listUser·p0.9999: 20.858 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  15.192 ms/op
                 listUser·p0.9999: 22.689 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243257
  mean =      3.944 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5727 
    [ 2.500,  5.000) = 210789 
    [ 5.000,  7.500) = 25567 
    [ 7.500, 10.000) = 732 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     23.434 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.555 ± 2.262  ops/ms
ClientGrpc.existUser                       thrpt       3  11.201 ± 1.786  ops/ms
ClientGrpc.getUser                         thrpt       3  10.627 ± 2.987  ops/ms
ClientGrpc.listUser                        thrpt       3   8.237 ± 1.804  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.335   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.859   ms/op
ClientGrpc.getUser                          avgt       3   2.943 ± 0.159   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 0.875   ms/op
ClientGrpc.createUser                     sample  321638   2.984 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.545           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.998           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.513           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.186           ms/op
ClientGrpc.existUser                      sample  333066   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.874           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.729           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.433           ms/op
ClientGrpc.getUser                        sample  322888   2.973 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.688           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.562           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.588           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.460           ms/op
ClientGrpc.listUser                       sample  243257   3.944 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.754           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.987           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
