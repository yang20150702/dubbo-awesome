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
# Warmup Iteration   1: 4.803 ops/ms
# Warmup Iteration   2: 9.203 ops/ms
# Warmup Iteration   3: 9.800 ops/ms
Iteration   1: 10.460 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.499 ±(99.9%) 2.321 ops/ms [Average]
  (min, avg, max) = (10.396, 10.499, 10.641), stdev = 0.127
  CI (99.9%): [8.179, 12.820] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ops/ms
# Warmup Iteration   2: 10.720 ops/ms
# Warmup Iteration   3: 10.927 ops/ms
Iteration   1: 11.208 ops/ms
Iteration   2: 10.892 ops/ms
Iteration   3: 11.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.089 ±(99.9%) 3.131 ops/ms [Average]
  (min, avg, max) = (10.892, 11.089, 11.208), stdev = 0.172
  CI (99.9%): [7.958, 14.219] (assumes normal distribution)


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
# Warmup Iteration   1: 7.403 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.691 ±(99.9%) 0.658 ops/ms [Average]
  (min, avg, max) = (10.663, 10.691, 10.732), stdev = 0.036
  CI (99.9%): [10.033, 11.349] (assumes normal distribution)


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
# Warmup Iteration   1: 5.979 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.138 ops/ms
Iteration   1: 8.147 ops/ms
Iteration   2: 8.335 ops/ms
Iteration   3: 8.193 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.225 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (8.147, 8.225, 8.335), stdev = 0.098
  CI (99.9%): [6.438, 10.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.002 ms/op
Iteration   1: 2.995 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 3.048 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (2.995, 3.016, 3.048), stdev = 0.028
  CI (99.9%): [2.504, 3.527] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.840 ±(99.9%) 0.004 ms/op
Iteration   1: 2.894 ±(99.9%) 0.002 ms/op
Iteration   2: 2.867 ±(99.9%) 0.003 ms/op
Iteration   3: 2.877 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 0.250 ms/op [Average]
  (min, avg, max) = (2.867, 2.879, 2.894), stdev = 0.014
  CI (99.9%): [2.629, 3.130] (assumes normal distribution)


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
Iteration   1: 2.992 ±(99.9%) 0.002 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.981 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (2.945, 2.981, 3.006), stdev = 0.032
  CI (99.9%): [2.403, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.015 ms/op
Iteration   1: 3.901 ±(99.9%) 0.006 ms/op
Iteration   2: 3.842 ±(99.9%) 0.016 ms/op
Iteration   3: 3.882 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.875 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.842, 3.875, 3.901), stdev = 0.030
  CI (99.9%): [3.323, 4.427] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.020 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  6.755 ms/op
                 createUser·p0.9999: 21.640 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 28.115 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.430 ms/op
                 createUser·p0.9999: 24.587 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319341
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26564 
    [ 2.500,  5.000) = 291209 
    [ 5.000,  7.500) = 1216 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     27.335 ms/op
     p(99.9990) =     28.555 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 3.639 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.115 ms/op
                 existUser·p0.9999: 15.125 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   2: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 15.498 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   3: 2.867 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 35.116 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332576
  mean =      2.887 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39202 
    [ 2.500,  5.000) = 292200 
    [ 5.000,  7.500) = 761 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      9.018 ms/op
     p(99.9900) =     17.391 ms/op
     p(99.9990) =     35.717 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.758 ms/op
                 getUser·p0.9999: 13.507 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.709 ms/op
                 getUser·p0.9999: 15.924 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.240 ms/op
                 getUser·p0.9999: 30.073 ms/op
                 getUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317991
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17603 
    [ 2.500,  5.000) = 299143 
    [ 5.000,  7.500) = 1014 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     28.580 ms/op
     p(99.9990) =     30.376 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.695 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.870 ±(99.9%) 0.009 ms/op
Iteration   1: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.536 ms/op
                 listUser·p0.9999: 18.896 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.499 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.813 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.902 ms/op
                 listUser·p0.999:  14.846 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248550
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 4829 
    [ 2.500,  3.750) = 124803 
    [ 3.750,  5.000) = 97115 
    [ 5.000,  6.250) = 16438 
    [ 6.250,  7.500) = 3986 
    [ 7.500,  8.750) = 679 
    [ 8.750, 10.000) = 156 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 115 
    [15.000, 16.250) = 109 
    [16.250, 17.500) = 46 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     19.252 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.499 ± 2.321  ops/ms
ClientGrpc.existUser                       thrpt       3  11.089 ± 3.131  ops/ms
ClientGrpc.getUser                         thrpt       3  10.691 ± 0.658  ops/ms
ClientGrpc.listUser                        thrpt       3   8.225 ± 1.787  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.511   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 0.250   ms/op
ClientGrpc.getUser                          avgt       3   2.981 ± 0.578   ms/op
ClientGrpc.listUser                         avgt       3   3.875 ± 0.552   ms/op
ClientGrpc.createUser                     sample  319341   3.005 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.815           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.335           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.606           ms/op
ClientGrpc.existUser                      sample  332576   2.887 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.421           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.018           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.391           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.717           ms/op
ClientGrpc.getUser                        sample  317991   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.590           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.580           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.474           ms/op
ClientGrpc.listUser                       sample  248550   3.862 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.719           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.727           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.383           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.366           ms/op
