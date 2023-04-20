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
# Warmup Iteration   1: 4.234 ops/ms
# Warmup Iteration   2: 9.122 ops/ms
# Warmup Iteration   3: 9.917 ops/ms
Iteration   1: 10.115 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 10.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.219 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (10.115, 10.219, 10.276), stdev = 0.091
  CI (99.9%): [8.567, 11.871] (assumes normal distribution)


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
# Warmup Iteration   1: 7.712 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 10.805 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.712 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (10.659, 10.712, 10.805), stdev = 0.081
  CI (99.9%): [9.240, 12.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ops/ms
# Warmup Iteration   2: 10.144 ops/ms
# Warmup Iteration   3: 10.321 ops/ms
Iteration   1: 10.387 ops/ms
Iteration   2: 10.776 ops/ms
Iteration   3: 10.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.568 ±(99.9%) 3.577 ops/ms [Average]
  (min, avg, max) = (10.387, 10.568, 10.776), stdev = 0.196
  CI (99.9%): [6.991, 14.145] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.553 ops/ms
# Warmup Iteration   2: 7.690 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 8.438 ops/ms
Iteration   3: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.298 ±(99.9%) 2.557 ops/ms [Average]
  (min, avg, max) = (8.158, 8.298, 8.438), stdev = 0.140
  CI (99.9%): [5.741, 10.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.415 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.024 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.004 ms/op
Iteration   3: 3.021 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (3.021, 3.028, 3.040), stdev = 0.011
  CI (99.9%): [2.834, 3.223] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.002 ms/op
Iteration   1: 2.888 ±(99.9%) 0.003 ms/op
Iteration   2: 2.831 ±(99.9%) 0.003 ms/op
Iteration   3: 2.886 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.587 ms/op [Average]
  (min, avg, max) = (2.831, 2.868, 2.888), stdev = 0.032
  CI (99.9%): [2.282, 3.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 3.020 ±(99.9%) 0.004 ms/op
Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.018 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.993, 3.018, 3.041), stdev = 0.024
  CI (99.9%): [2.579, 3.457] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.434 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.017 ms/op
Iteration   1: 3.971 ±(99.9%) 0.039 ms/op
Iteration   2: 3.951 ±(99.9%) 0.021 ms/op
Iteration   3: 3.967 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.963 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (3.951, 3.963, 3.971), stdev = 0.011
  CI (99.9%): [3.768, 4.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.008 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.487 ms/op
                 createUser·p0.9999: 17.256 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.164 ms/op
                 createUser·p0.9999: 19.128 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.319 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  7.785 ms/op
                 createUser·p0.9999: 17.844 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310776
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 367 
    [ 1.250,  2.500) = 18587 
    [ 2.500,  3.750) = 268696 
    [ 3.750,  5.000) = 21514 
    [ 5.000,  6.250) = 908 
    [ 6.250,  7.500) = 394 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.319 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.499 ms/op
     p(99.9900) =     17.889 ms/op
     p(99.9990) =     19.559 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
Iteration   1: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.355 ms/op
                 existUser·p0.9999: 21.654 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 2.891 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.293 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.225 ms/op
                 existUser·p0.999:  5.614 ms/op
                 existUser·p0.9999: 14.335 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   3: 2.900 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.256 ms/op
                 existUser·p0.9999: 16.007 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332675
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44598 
    [ 2.500,  5.000) = 287170 
    [ 5.000,  7.500) = 651 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.761 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 4.282 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.809 ms/op
                 getUser·p0.9999: 12.916 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 13.574 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  5.845 ms/op
                 getUser·p0.9999: 15.397 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318367
  mean =      3.016 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 402 
    [ 1.250,  2.500) = 18421 
    [ 2.500,  3.750) = 286242 
    [ 3.750,  5.000) = 11719 
    [ 5.000,  6.250) = 1010 
    [ 6.250,  7.500) = 280 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.208 ms/op
     p(99.9900) =     14.291 ms/op
     p(99.9990) =     16.611 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
Iteration   1: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.659 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  12.431 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.856 ms/op

Iteration   2: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.590 ms/op
                 listUser·p0.9999: 18.702 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.631 ms/op
                 listUser·p0.9999: 18.901 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242259
  mean =      3.962 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2270 
    [ 2.500,  5.000) = 218608 
    [ 5.000,  7.500) = 20201 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     20.473 ms/op
     p(99.9990) =     21.716 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.219 ± 1.652  ops/ms
ClientGrpc.existUser                       thrpt       3  10.712 ± 1.473  ops/ms
ClientGrpc.getUser                         thrpt       3  10.568 ± 3.577  ops/ms
ClientGrpc.listUser                        thrpt       3   8.298 ± 2.557  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.194   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.587   ms/op
ClientGrpc.getUser                          avgt       3   3.018 ± 0.439   ms/op
ClientGrpc.listUser                         avgt       3   3.963 ± 0.195   ms/op
ClientGrpc.createUser                     sample  310776   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.319           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.499           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.889           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  332675   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.293           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.761           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.810           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  318367   3.016 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.449           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.291           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  242259   3.962 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.904           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.204           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.473           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.856           ms/op
