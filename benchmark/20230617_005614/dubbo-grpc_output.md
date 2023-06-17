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
# Warmup Iteration   1: 4.987 ops/ms
# Warmup Iteration   2: 9.142 ops/ms
# Warmup Iteration   3: 10.393 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.806 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.758 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (10.672, 10.758, 10.806), stdev = 0.075
  CI (99.9%): [9.391, 12.126] (assumes normal distribution)


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
# Warmup Iteration   1: 7.948 ops/ms
# Warmup Iteration   2: 10.964 ops/ms
# Warmup Iteration   3: 11.420 ops/ms
Iteration   1: 11.481 ops/ms
Iteration   2: 11.235 ops/ms
Iteration   3: 11.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.327 ±(99.9%) 2.452 ops/ms [Average]
  (min, avg, max) = (11.235, 11.327, 11.481), stdev = 0.134
  CI (99.9%): [8.875, 13.779] (assumes normal distribution)


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
# Warmup Iteration   1: 7.590 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 10.761 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 11.007 ops/ms
Iteration   3: 11.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.998 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (10.944, 10.998, 11.043), stdev = 0.050
  CI (99.9%): [10.089, 11.907] (assumes normal distribution)


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
# Warmup Iteration   1: 5.704 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 8.192 ops/ms
Iteration   1: 8.215 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.277 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (8.191, 8.277, 8.426), stdev = 0.129
  CI (99.9%): [5.921, 10.634] (assumes normal distribution)


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.005 ms/op
Iteration   1: 2.956 ±(99.9%) 0.006 ms/op
Iteration   2: 2.943 ±(99.9%) 0.004 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.966 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (2.943, 2.966, 2.998), stdev = 0.028
  CI (99.9%): [2.447, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.002 ms/op
Iteration   1: 2.826 ±(99.9%) 0.003 ms/op
Iteration   2: 2.835 ±(99.9%) 0.004 ms/op
Iteration   3: 2.858 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.840 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.826, 2.840, 2.858), stdev = 0.017
  CI (99.9%): [2.533, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.002 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
Iteration   3: 2.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.965 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.960, 2.965, 2.971), stdev = 0.005
  CI (99.9%): [2.868, 3.061] (assumes normal distribution)


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.016 ms/op
Iteration   1: 3.869 ±(99.9%) 0.018 ms/op
Iteration   2: 3.841 ±(99.9%) 0.008 ms/op
Iteration   3: 3.872 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (3.841, 3.861, 3.872), stdev = 0.017
  CI (99.9%): [3.556, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.567 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 17.828 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   2.904 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.373 ms/op
                 createUser·p0.9999: 16.284 ms/op
                 createUser·p1.00:   16.728 ms/op

Iteration   3: 3.005 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  13.994 ms/op
                 createUser·p0.9999: 31.043 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326101
  mean =      2.943 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43726 
    [ 2.500,  5.000) = 281067 
    [ 5.000,  7.500) = 889 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.321 ms/op
     p(99.9900) =     29.956 ms/op
     p(99.9990) =     31.481 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.907 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.831 ±(99.9%) 0.006 ms/op
Iteration   1: 2.879 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  7.263 ms/op
                 existUser·p0.9999: 11.764 ms/op
                 existUser·p1.00:   12.124 ms/op

Iteration   2: 2.828 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 22.000 ms/op
                 existUser·p1.00:   22.381 ms/op

Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.399 ms/op
                 existUser·p0.9999: 16.399 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335157
  mean =      2.863 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54066 
    [ 2.500,  5.000) = 280014 
    [ 5.000,  7.500) = 810 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     16.842 ms/op
     p(99.9990) =     22.292 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 2.919 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 12.649 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.105 ms/op
                 getUser·p0.9999: 24.692 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 2.961 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.051 ms/op
                 getUser·p0.999:  6.749 ms/op
                 getUser·p0.9999: 13.299 ms/op
                 getUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326484
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32285 
    [ 2.500,  5.000) = 293069 
    [ 5.000,  7.500) = 813 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.394 ms/op
     p(99.9900) =     18.471 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.009 ms/op
Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.000 ms/op
                 listUser·p0.9999: 17.919 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.848 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.635 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.823 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.555 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  15.636 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248452
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6544 
    [ 2.500,  5.000) = 219661 
    [ 5.000,  7.500) = 20913 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 133 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     20.883 ms/op
     p(99.9990) =     21.546 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.758 ± 1.368  ops/ms
ClientGrpc.existUser                       thrpt       3  11.327 ± 2.452  ops/ms
ClientGrpc.getUser                         thrpt       3  10.998 ± 0.909  ops/ms
ClientGrpc.listUser                        thrpt       3   8.277 ± 2.357  ops/ms
ClientGrpc.createUser                       avgt       3   2.966 ± 0.519   ms/op
ClientGrpc.existUser                        avgt       3   2.840 ± 0.306   ms/op
ClientGrpc.getUser                          avgt       3   2.965 ± 0.096   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 0.305   ms/op
ClientGrpc.createUser                     sample  326101   2.943 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.515           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.956           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.556           ms/op
ClientGrpc.existUser                      sample  335157   2.863 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.842           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.381           ms/op
ClientGrpc.getUser                        sample  326484   2.942 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.440           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.394           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.471           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.362           ms/op
ClientGrpc.listUser                       sample  248452   3.863 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.555           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.172           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.883           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.660           ms/op
