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
# Warmup Iteration   1: 3.945 ops/ms
# Warmup Iteration   2: 8.703 ops/ms
# Warmup Iteration   3: 9.778 ops/ms
Iteration   1: 10.181 ops/ms
Iteration   2: 10.305 ops/ms
Iteration   3: 10.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.218 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (10.167, 10.218, 10.305), stdev = 0.076
  CI (99.9%): [8.829, 11.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 9.943 ops/ms
# Warmup Iteration   3: 10.857 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 10.878 ops/ms
Iteration   3: 10.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.882 ±(99.9%) 0.448 ops/ms [Average]
  (min, avg, max) = (10.860, 10.882, 10.909), stdev = 0.025
  CI (99.9%): [10.435, 11.330] (assumes normal distribution)


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
# Warmup Iteration   1: 7.204 ops/ms
# Warmup Iteration   2: 9.981 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.396 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.369 ±(99.9%) 0.465 ops/ms [Average]
  (min, avg, max) = (10.345, 10.369, 10.396), stdev = 0.025
  CI (99.9%): [9.904, 10.834] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.148 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.029 ops/ms
Iteration   3: 7.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.086 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (7.973, 8.086, 8.256), stdev = 0.150
  CI (99.9%): [5.351, 10.820] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.192 ±(99.9%) 0.004 ms/op
Iteration   1: 3.124 ±(99.9%) 0.003 ms/op
Iteration   2: 3.081 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.081, 3.101, 3.124), stdev = 0.022
  CI (99.9%): [2.700, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.003 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 2.910 ±(99.9%) 0.003 ms/op
Iteration   3: 2.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (2.848, 2.900, 2.943), stdev = 0.048
  CI (99.9%): [2.022, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.002 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.023 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.023, 3.064, 3.098), stdev = 0.038
  CI (99.9%): [2.369, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.009 ms/op
Iteration   1: 3.985 ±(99.9%) 0.014 ms/op
Iteration   2: 4.020 ±(99.9%) 0.018 ms/op
Iteration   3: 3.903 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.903, 3.969, 4.020), stdev = 0.060
  CI (99.9%): [2.882, 5.057] (assumes normal distribution)


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
# Warmup Iteration   1: 4.372 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.419 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.595 ms/op
                 createUser·p0.9999: 17.283 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.117 ms/op
                 createUser·p0.9999: 17.581 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.727 ms/op
                 createUser·p0.999:  8.542 ms/op
                 createUser·p0.9999: 20.099 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316921
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26332 
    [ 2.500,  5.000) = 288341 
    [ 5.000,  7.500) = 1721 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     19.540 ms/op
     p(99.9990) =     20.491 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.904 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  11.434 ms/op
                 existUser·p0.9999: 16.629 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   2: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.763 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.269 ms/op
                 existUser·p0.9999: 20.026 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.598 ms/op
                 existUser·p0.9999: 16.140 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328723
  mean =      2.917 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46375 
    [ 2.500,  5.000) = 279964 
    [ 5.000,  7.500) = 1829 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      9.606 ms/op
     p(99.9900) =     17.080 ms/op
     p(99.9990) =     20.592 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  7.732 ms/op
                 getUser·p0.9999: 13.950 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  7.607 ms/op
                 getUser·p0.9999: 15.040 ms/op
                 getUser·p1.00:   15.974 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 25.559 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313903
  mean =      3.057 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25164 
    [ 2.500,  5.000) = 285972 
    [ 5.000,  7.500) = 2393 
    [ 7.500, 10.000) = 181 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     24.989 ms/op
     p(99.9990) =     26.791 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.013 ms/op
Iteration   1: 4.066 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.554 ms/op
                 listUser·p0.999:  14.405 ms/op
                 listUser·p0.9999: 21.180 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   2: 4.010 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  18.055 ms/op
                 listUser·p0.9999: 28.936 ms/op
                 listUser·p1.00:   31.359 ms/op

Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239287
  mean =      4.012 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3430 
    [ 2.500,  5.000) = 206060 
    [ 5.000,  7.500) = 27707 
    [ 7.500, 10.000) = 1540 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.809 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.341 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     28.939 ms/op
     p(99.9990) =     30.698 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.218 ± 1.389  ops/ms
ClientGrpc.existUser                       thrpt       3  10.882 ± 0.448  ops/ms
ClientGrpc.getUser                         thrpt       3  10.369 ± 0.465  ops/ms
ClientGrpc.listUser                        thrpt       3   8.086 ± 2.734  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.401   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.879   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.695   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 1.088   ms/op
ClientGrpc.createUser                     sample  316921   3.028 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.419           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.669           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.487           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.540           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.644           ms/op
ClientGrpc.existUser                      sample  328723   2.917 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.630           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.606           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.080           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.709           ms/op
ClientGrpc.getUser                        sample  313903   3.057 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.989           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.968           ms/op
ClientGrpc.listUser                       sample  239287   4.012 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.809           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.341           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.367           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.939           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
