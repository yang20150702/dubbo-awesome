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
# Warmup Iteration   1: 4.255 ops/ms
# Warmup Iteration   2: 8.900 ops/ms
# Warmup Iteration   3: 10.025 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.402 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.490 ±(99.9%) 2.176 ops/ms [Average]
  (min, avg, max) = (10.402, 10.490, 10.626), stdev = 0.119
  CI (99.9%): [8.314, 12.666] (assumes normal distribution)


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
# Warmup Iteration   1: 7.343 ops/ms
# Warmup Iteration   2: 10.489 ops/ms
# Warmup Iteration   3: 10.855 ops/ms
Iteration   1: 10.875 ops/ms
Iteration   2: 10.803 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.821 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (10.785, 10.821, 10.875), stdev = 0.048
  CI (99.9%): [9.948, 11.694] (assumes normal distribution)


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
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 9.845 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.601 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (10.566, 10.601, 10.669), stdev = 0.059
  CI (99.9%): [9.516, 11.685] (assumes normal distribution)


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
# Warmup Iteration   1: 5.624 ops/ms
# Warmup Iteration   2: 7.821 ops/ms
# Warmup Iteration   3: 7.985 ops/ms
Iteration   1: 8.171 ops/ms
Iteration   2: 8.578 ops/ms
Iteration   3: 8.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.257 ±(99.9%) 5.264 ops/ms [Average]
  (min, avg, max) = (8.021, 8.257, 8.578), stdev = 0.289
  CI (99.9%): [2.993, 13.521] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.002 ms/op
Iteration   2: 3.024 ±(99.9%) 0.002 ms/op
Iteration   3: 3.051 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (3.024, 3.040, 3.051), stdev = 0.014
  CI (99.9%): [2.784, 3.296] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.951 ±(99.9%) 0.002 ms/op
Iteration   2: 2.838 ±(99.9%) 0.004 ms/op
Iteration   3: 2.905 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (2.838, 2.898, 2.951), stdev = 0.057
  CI (99.9%): [1.863, 3.933] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.003 ms/op
Iteration   1: 3.073 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.040 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.007, 3.040, 3.073), stdev = 0.033
  CI (99.9%): [2.442, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.008 ms/op
Iteration   1: 3.952 ±(99.9%) 0.024 ms/op
Iteration   2: 3.733 ±(99.9%) 0.007 ms/op
Iteration   3: 4.037 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 2.864 ms/op [Average]
  (min, avg, max) = (3.733, 3.908, 4.037), stdev = 0.157
  CI (99.9%): [1.043, 6.772] (assumes normal distribution)


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
# Warmup Iteration   1: 4.344 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.963 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  6.732 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   15.942 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.540 ms/op
                 createUser·p0.999:  8.383 ms/op
                 createUser·p0.9999: 19.498 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313770
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20676 
    [ 2.500,  5.000) = 291524 
    [ 5.000,  7.500) = 1195 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     21.103 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.562 ms/op
                 existUser·p0.9999: 11.994 ms/op
                 existUser·p1.00:   12.337 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.611 ms/op
                 existUser·p0.9999: 13.303 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.254 ms/op
                 existUser·p0.9999: 15.269 ms/op
                 existUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329592
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3540 
    [ 1.250,  2.500) = 35208 
    [ 2.500,  3.750) = 278728 
    [ 3.750,  5.000) = 11200 
    [ 5.000,  6.250) = 544 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.495 ms/op
     p(99.9900) =     14.959 ms/op
     p(99.9990) =     18.144 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.133 ms/op
                 getUser·p0.9999: 12.255 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.177 ms/op
                 getUser·p0.9999: 21.135 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.506 ms/op
                 getUser·p0.9999: 14.738 ms/op
                 getUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314430
  mean =      3.051 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18671 
    [ 2.500,  5.000) = 294378 
    [ 5.000,  7.500) = 1126 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     20.353 ms/op
     p(99.9990) =     21.426 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 5.463 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.129 ms/op
                 listUser·p0.9999: 19.229 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.895 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.749 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  16.658 ms/op
                 listUser·p0.9999: 26.306 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  14.454 ms/op
                 listUser·p0.9999: 17.686 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243922
  mean =      3.933 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4949 
    [ 2.500,  5.000) = 216188 
    [ 5.000,  7.500) = 21553 
    [ 7.500, 10.000) = 811 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.844 ms/op
     p(99.9900) =     25.022 ms/op
     p(99.9990) =     27.052 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.490 ± 2.176  ops/ms
ClientGrpc.existUser                       thrpt       3  10.821 ± 0.873  ops/ms
ClientGrpc.getUser                         thrpt       3  10.601 ± 1.084  ops/ms
ClientGrpc.listUser                        thrpt       3   8.257 ± 5.264  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.256   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 1.035   ms/op
ClientGrpc.getUser                          avgt       3   3.040 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 2.864   ms/op
ClientGrpc.createUser                     sample  313770   3.058 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.602           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.094           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.103           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.364           ms/op
ClientGrpc.existUser                      sample  329592   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.495           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.959           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.890           ms/op
ClientGrpc.getUser                        sample  314430   3.051 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.664           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.062           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.353           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.561           ms/op
ClientGrpc.listUser                       sample  243922   3.933 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.749           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.844           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.022           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
