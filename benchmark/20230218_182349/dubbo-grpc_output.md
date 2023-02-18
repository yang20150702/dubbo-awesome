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
# Warmup Iteration   1: 4.998 ops/ms
# Warmup Iteration   2: 9.917 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.679 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.428 ±(99.9%) 4.091 ops/ms [Average]
  (min, avg, max) = (10.247, 10.428, 10.679), stdev = 0.224
  CI (99.9%): [6.337, 14.520] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 10.852 ops/ms
# Warmup Iteration   3: 11.208 ops/ms
Iteration   1: 11.541 ops/ms
Iteration   2: 10.971 ops/ms
Iteration   3: 11.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.234 ±(99.9%) 5.246 ops/ms [Average]
  (min, avg, max) = (10.971, 11.234, 11.541), stdev = 0.288
  CI (99.9%): [5.988, 16.480] (assumes normal distribution)


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
# Warmup Iteration   1: 7.476 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.529 ops/ms
Iteration   1: 10.639 ops/ms
Iteration   2: 10.379 ops/ms
Iteration   3: 10.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.525 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (10.379, 10.525, 10.639), stdev = 0.133
  CI (99.9%): [8.098, 12.951] (assumes normal distribution)


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
# Warmup Iteration   1: 6.052 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.994 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (7.904, 7.994, 8.066), stdev = 0.083
  CI (99.9%): [6.488, 9.499] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.788 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 2.996 ±(99.9%) 0.002 ms/op
Iteration   3: 3.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.035 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (2.996, 3.035, 3.081), stdev = 0.043
  CI (99.9%): [2.250, 3.819] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.856 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.003 ms/op
Iteration   3: 2.920 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (2.893, 2.923, 2.956), stdev = 0.031
  CI (99.9%): [2.354, 3.492] (assumes normal distribution)


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
# Warmup Iteration   1: 3.939 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.002 ms/op
Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
Iteration   3: 2.938 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (2.938, 2.980, 3.021), stdev = 0.042
  CI (99.9%): [2.220, 3.740] (assumes normal distribution)


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
# Warmup Iteration   1: 4.295 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.016 ms/op
Iteration   1: 3.886 ±(99.9%) 0.005 ms/op
Iteration   2: 3.987 ±(99.9%) 0.016 ms/op
Iteration   3: 3.897 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (3.886, 3.924, 3.987), stdev = 0.055
  CI (99.9%): [2.912, 4.936] (assumes normal distribution)


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.335 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  7.424 ms/op
                 createUser·p0.9999: 15.007 ms/op
                 createUser·p1.00:   15.532 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  14.387 ms/op
                 createUser·p0.9999: 20.185 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.318 ms/op
                 createUser·p0.9999: 18.088 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310989
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24885 
    [ 2.500,  5.000) = 285001 
    [ 5.000,  7.500) = 687 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.335 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     18.540 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.351 ms/op
                 existUser·p0.999:  6.686 ms/op
                 existUser·p0.9999: 11.150 ms/op
                 existUser·p1.00:   11.534 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.274 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.367 ms/op
                 existUser·p0.9999: 15.342 ms/op
                 existUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323186
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1937 
    [ 1.250,  2.500) = 49651 
    [ 2.500,  3.750) = 249197 
    [ 3.750,  5.000) = 21462 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 128 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.822 ms/op
     p(99.9900) =     15.856 ms/op
     p(99.9990) =     17.065 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.707 ms/op
                 getUser·p0.9999: 11.429 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.862 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.787 ms/op
                 getUser·p0.9999: 13.214 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  9.086 ms/op
                 getUser·p0.9999: 14.362 ms/op
                 getUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314076
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1311 
    [ 1.250,  2.500) = 27192 
    [ 2.500,  3.750) = 261891 
    [ 3.750,  5.000) = 22805 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     13.854 ms/op
     p(99.9990) =     15.740 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.010 ms/op
Iteration   1: 4.046 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.599 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  12.336 ms/op
                 listUser·p0.9999: 14.421 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 21.878 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 4.050 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.292 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.039 ms/op
                 listUser·p0.9999: 19.605 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239701
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3473 
    [ 2.500,  5.000) = 204855 
    [ 5.000,  7.500) = 30082 
    [ 7.500, 10.000) = 768 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     21.464 ms/op
     p(99.9990) =     22.761 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.428 ± 4.091  ops/ms
ClientGrpc.existUser                       thrpt       3  11.234 ± 5.246  ops/ms
ClientGrpc.getUser                         thrpt       3  10.525 ± 2.427  ops/ms
ClientGrpc.listUser                        thrpt       3   7.994 ± 1.505  ops/ms
ClientGrpc.createUser                       avgt       3   3.035 ± 0.785   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.569   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.760   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 1.012   ms/op
ClientGrpc.createUser                     sample  310989   3.085 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.335           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.540           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  323186   2.970 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.596           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.822           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.856           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  314076   3.054 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.691           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.305           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.854           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.827           ms/op
ClientGrpc.listUser                       sample  239701   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.292           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.464           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.774           ms/op
