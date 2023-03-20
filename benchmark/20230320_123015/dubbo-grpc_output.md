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
# Warmup Iteration   1: 4.640 ops/ms
# Warmup Iteration   2: 9.554 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.762 ops/ms
Iteration   2: 10.609 ops/ms
Iteration   3: 10.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.743 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (10.609, 10.743, 10.857), stdev = 0.125
  CI (99.9%): [8.458, 13.028] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ops/ms
# Warmup Iteration   2: 10.898 ops/ms
# Warmup Iteration   3: 11.088 ops/ms
Iteration   1: 11.317 ops/ms
Iteration   2: 11.163 ops/ms
Iteration   3: 11.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.269 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (11.163, 11.269, 11.325), stdev = 0.091
  CI (99.9%): [9.604, 12.934] (assumes normal distribution)


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
# Warmup Iteration   1: 8.337 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.922 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.807 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (10.740, 10.807, 10.879), stdev = 0.070
  CI (99.9%): [9.531, 12.083] (assumes normal distribution)


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
# Warmup Iteration   1: 6.544 ops/ms
# Warmup Iteration   2: 7.935 ops/ms
# Warmup Iteration   3: 8.440 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.269 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.310 ±(99.9%) 3.095 ops/ms [Average]
  (min, avg, max) = (8.164, 8.310, 8.496), stdev = 0.170
  CI (99.9%): [5.215, 11.405] (assumes normal distribution)


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.010 ms/op
Iteration   1: 2.973 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.949 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.919, 2.949, 2.973), stdev = 0.027
  CI (99.9%): [2.448, 3.449] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.925 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.872 ±(99.9%) 0.003 ms/op
Iteration   1: 2.815 ±(99.9%) 0.004 ms/op
Iteration   2: 2.797 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.837 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (2.797, 2.837, 2.899), stdev = 0.054
  CI (99.9%): [1.845, 3.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.915 ±(99.9%) 0.003 ms/op
Iteration   2: 2.982 ±(99.9%) 0.003 ms/op
Iteration   3: 2.952 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.950 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.915, 2.950, 2.982), stdev = 0.034
  CI (99.9%): [2.338, 3.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.014 ms/op
Iteration   1: 3.825 ±(99.9%) 0.011 ms/op
Iteration   2: 3.808 ±(99.9%) 0.015 ms/op
Iteration   3: 3.810 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.814 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (3.808, 3.814, 3.825), stdev = 0.009
  CI (99.9%): [3.646, 3.982] (assumes normal distribution)


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.197 ms/op
                 createUser·p0.9999: 10.945 ms/op
                 createUser·p1.00:   11.239 ms/op

Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 12.619 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.393 ms/op
                 createUser·p0.9999: 20.972 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325418
  mean =      2.949 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27256 
    [ 2.500,  5.000) = 296908 
    [ 5.000,  7.500) = 901 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.415 ms/op
     p(99.9900) =     16.399 ms/op
     p(99.9990) =     21.741 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.005 ms/op
Iteration   1: 2.829 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.399 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.404 ms/op
                 existUser·p0.9999: 16.997 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.779 ms/op
                 existUser·p0.9999: 11.844 ms/op
                 existUser·p1.00:   11.993 ms/op

Iteration   3: 2.841 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.138 ms/op
                 existUser·p0.9999: 13.704 ms/op
                 existUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336146
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1768 
    [ 1.250,  2.500) = 47934 
    [ 2.500,  3.750) = 278397 
    [ 3.750,  5.000) = 6976 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.028 ms/op
     p(99.9900) =     13.955 ms/op
     p(99.9990) =     17.343 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.320 ms/op
                 getUser·p0.9999: 11.900 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 14.931 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   3: 2.943 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.678 ms/op
                 getUser·p0.9999: 22.422 ms/op
                 getUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324098
  mean =      2.961 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35383 
    [ 2.500,  5.000) = 287706 
    [ 5.000,  7.500) = 719 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.364 ms/op
     p(99.9900) =     19.881 ms/op
     p(99.9990) =     22.966 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 4.933 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.021 ms/op
Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  13.106 ms/op
                 listUser·p0.9999: 14.983 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 3.839 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.784 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  16.232 ms/op
                 listUser·p0.9999: 27.011 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   3: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.537 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.670 ms/op
                 listUser·p0.9999: 22.929 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249054
  mean =      3.855 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4803 
    [ 2.500,  5.000) = 224999 
    [ 5.000,  7.500) = 18174 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.597 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.198 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.743 ± 2.285  ops/ms
ClientGrpc.existUser                       thrpt       3  11.269 ± 1.665  ops/ms
ClientGrpc.getUser                         thrpt       3  10.807 ± 1.276  ops/ms
ClientGrpc.listUser                        thrpt       3   8.310 ± 3.095  ops/ms
ClientGrpc.createUser                       avgt       3   2.949 ± 0.500   ms/op
ClientGrpc.existUser                        avgt       3   2.837 ± 0.992   ms/op
ClientGrpc.getUser                          avgt       3   2.950 ± 0.611   ms/op
ClientGrpc.listUser                         avgt       3   3.814 ± 0.168   ms/op
ClientGrpc.createUser                     sample  325418   2.949 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.415           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  336146   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.399           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.028           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.955           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  324098   2.961 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.638           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.364           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.881           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  249054   3.855 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.537           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.597           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
