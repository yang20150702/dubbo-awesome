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
# Warmup Iteration   1: 4.130 ops/ms
# Warmup Iteration   2: 8.804 ops/ms
# Warmup Iteration   3: 9.508 ops/ms
Iteration   1: 10.325 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.388 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (10.325, 10.388, 10.493), stdev = 0.091
  CI (99.9%): [8.726, 12.051] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ops/ms
# Warmup Iteration   2: 10.694 ops/ms
# Warmup Iteration   3: 11.125 ops/ms
Iteration   1: 11.033 ops/ms
Iteration   2: 11.329 ops/ms
Iteration   3: 10.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.074 ±(99.9%) 4.324 ops/ms [Average]
  (min, avg, max) = (10.860, 11.074, 11.329), stdev = 0.237
  CI (99.9%): [6.750, 15.398] (assumes normal distribution)


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
# Warmup Iteration   1: 7.069 ops/ms
# Warmup Iteration   2: 10.023 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.615 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.591 ±(99.9%) 1.897 ops/ms [Average]
  (min, avg, max) = (10.477, 10.591, 10.681), stdev = 0.104
  CI (99.9%): [8.694, 12.488] (assumes normal distribution)


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
# Warmup Iteration   1: 5.831 ops/ms
# Warmup Iteration   2: 7.777 ops/ms
# Warmup Iteration   3: 7.938 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 8.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.016 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (7.955, 8.016, 8.087), stdev = 0.066
  CI (99.9%): [6.805, 9.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (3.024, 3.040, 3.059), stdev = 0.018
  CI (99.9%): [2.716, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.003 ms/op
Iteration   1: 2.892 ±(99.9%) 0.002 ms/op
Iteration   2: 2.867 ±(99.9%) 0.002 ms/op
Iteration   3: 2.886 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.882 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.867, 2.882, 2.892), stdev = 0.013
  CI (99.9%): [2.642, 3.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.302 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 3.048 ±(99.9%) 0.003 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.934 ms/op [Average]
  (min, avg, max) = (2.968, 3.027, 3.064), stdev = 0.051
  CI (99.9%): [2.092, 3.961] (assumes normal distribution)


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
# Warmup Iteration   1: 5.824 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.016 ms/op
Iteration   2: 4.005 ±(99.9%) 0.007 ms/op
Iteration   3: 3.983 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.008 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.983, 4.008, 4.037), stdev = 0.028
  CI (99.9%): [3.506, 4.511] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.645 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.557 ms/op
                 createUser·p0.9999: 12.837 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.524 ms/op
                 createUser·p0.95:   3.714 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.528 ms/op
                 createUser·p0.9999: 14.082 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   3: 3.005 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.216 ms/op
                 createUser·p0.9999: 25.549 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316028
  mean =      3.037 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23889 
    [ 2.500,  5.000) = 290784 
    [ 5.000,  7.500) = 985 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     24.818 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.804 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  6.930 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  5.603 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   3: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 22.540 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330545
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42832 
    [ 2.500,  5.000) = 286856 
    [ 5.000,  7.500) = 648 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      6.918 ms/op
     p(99.9900) =     20.116 ms/op
     p(99.9990) =     23.316 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 4.563 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  7.910 ms/op
                 getUser·p0.9999: 12.774 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.374 ms/op
                 getUser·p0.999:  7.266 ms/op
                 getUser·p0.9999: 14.085 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.388 ms/op
                 getUser·p0.9999: 16.212 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315257
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 595 
    [ 1.250,  2.500) = 23785 
    [ 2.500,  3.750) = 271743 
    [ 3.750,  5.000) = 17651 
    [ 5.000,  6.250) = 831 
    [ 6.250,  7.500) = 329 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.561 ms/op
     p(99.9900) =     15.605 ms/op
     p(99.9990) =     17.455 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.329 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
Iteration   1: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.552 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.958 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.505 ms/op
                 listUser·p0.9999: 20.183 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241032
  mean =      3.979 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2881 
    [ 2.500,  5.000) = 215890 
    [ 5.000,  7.500) = 20918 
    [ 7.500, 10.000) = 925 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     16.153 ms/op
     p(99.9900) =     25.251 ms/op
     p(99.9990) =     30.177 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.388 ± 1.662  ops/ms
ClientGrpc.existUser                       thrpt       3  11.074 ± 4.324  ops/ms
ClientGrpc.getUser                         thrpt       3  10.591 ± 1.897  ops/ms
ClientGrpc.listUser                        thrpt       3   8.016 ± 1.210  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.324   ms/op
ClientGrpc.existUser                        avgt       3   2.882 ± 0.240   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.934   ms/op
ClientGrpc.listUser                         avgt       3   4.008 ± 0.502   ms/op
ClientGrpc.createUser                     sample  316028   3.037 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.644           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.818           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.051           ms/op
ClientGrpc.existUser                      sample  330545   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.804           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.918           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.116           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.691           ms/op
ClientGrpc.getUser                        sample  315257   3.045 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.582           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.561           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.605           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  241032   3.979 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.958           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.153           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.251           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.292           ms/op
