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
# Warmup Iteration   1: 4.162 ops/ms
# Warmup Iteration   2: 8.573 ops/ms
# Warmup Iteration   3: 9.920 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 11.120 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.719 ±(99.9%) 6.481 ops/ms [Average]
  (min, avg, max) = (10.442, 10.719, 11.120), stdev = 0.355
  CI (99.9%): [4.238, 17.200] (assumes normal distribution)


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
# Warmup Iteration   1: 7.132 ops/ms
# Warmup Iteration   2: 10.431 ops/ms
# Warmup Iteration   3: 10.941 ops/ms
Iteration   1: 11.069 ops/ms
Iteration   2: 11.234 ops/ms
Iteration   3: 10.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.079 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (10.933, 11.079, 11.234), stdev = 0.151
  CI (99.9%): [8.332, 13.825] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.297 ops/ms
# Warmup Iteration   2: 9.811 ops/ms
# Warmup Iteration   3: 10.329 ops/ms
Iteration   1: 10.437 ops/ms
Iteration   2: 10.433 ops/ms
Iteration   3: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.442 ±(99.9%) 0.226 ops/ms [Average]
  (min, avg, max) = (10.433, 10.442, 10.456), stdev = 0.012
  CI (99.9%): [10.216, 10.668] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ops/ms
# Warmup Iteration   2: 7.687 ops/ms
# Warmup Iteration   3: 7.791 ops/ms
Iteration   1: 7.856 ops/ms
Iteration   2: 7.903 ops/ms
Iteration   3: 7.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.869 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (7.848, 7.869, 7.903), stdev = 0.030
  CI (99.9%): [7.325, 8.413] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
Iteration   2: 3.052 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.032, 3.061, 3.100), stdev = 0.035
  CI (99.9%): [2.418, 3.704] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.842 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.915 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (2.842, 2.915, 2.955), stdev = 0.063
  CI (99.9%): [1.758, 4.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.449 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.005 ms/op
Iteration   1: 3.130 ±(99.9%) 0.004 ms/op
Iteration   2: 3.062 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.096 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.062, 3.096, 3.130), stdev = 0.034
  CI (99.9%): [2.477, 3.715] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.025 ms/op
Iteration   1: 4.036 ±(99.9%) 0.018 ms/op
Iteration   2: 4.143 ±(99.9%) 0.016 ms/op
Iteration   3: 4.030 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.070 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (4.030, 4.070, 4.143), stdev = 0.064
  CI (99.9%): [2.907, 5.233] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.007 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.201 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.094 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 19.446 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 3.055 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.167 ms/op
                 createUser·p0.9999: 22.087 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316231
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12020 
    [ 2.500,  5.000) = 303001 
    [ 5.000,  7.500) = 654 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      9.806 ms/op
     p(99.9900) =     21.312 ms/op
     p(99.9990) =     22.403 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
Iteration   1: 2.927 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.412 ms/op
                 existUser·p0.99:   3.899 ms/op
                 existUser·p0.999:  6.966 ms/op
                 existUser·p0.9999: 19.305 ms/op
                 existUser·p1.00:   19.661 ms/op

Iteration   2: 2.950 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.480 ms/op
                 existUser·p0.9999: 15.991 ms/op
                 existUser·p1.00:   16.220 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  10.472 ms/op
                 existUser·p0.9999: 16.650 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325648
  mean =      2.947 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 629 
    [ 1.250,  2.500) = 19772 
    [ 2.500,  3.750) = 298277 
    [ 3.750,  5.000) = 5991 
    [ 5.000,  6.250) = 500 
    [ 6.250,  7.500) = 223 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 71 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      6.821 ms/op
     p(99.9900) =     17.758 ms/op
     p(99.9990) =     19.587 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.206 ms/op
                 getUser·p0.9999: 16.495 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.460 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.220 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311692
  mean =      3.080 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 726 
    [ 1.250,  2.500) = 17109 
    [ 2.500,  3.750) = 276612 
    [ 3.750,  5.000) = 15968 
    [ 5.000,  6.250) = 778 
    [ 6.250,  7.500) = 270 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 54 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.998 ms/op
     p(99.9900) =     17.329 ms/op
     p(99.9990) =     18.117 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.739 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.227 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.011 ms/op
Iteration   1: 4.119 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.297 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 16.827 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   2: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.477 ms/op
                 listUser·p0.9999: 23.403 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  17.654 ms/op
                 listUser·p0.9999: 25.052 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233744
  mean =      4.106 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2312 
    [ 2.500,  5.000) = 205952 
    [ 5.000,  7.500) = 23841 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     16.224 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.591 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.719 ± 6.481  ops/ms
ClientGrpc.existUser                       thrpt       3  11.079 ± 2.746  ops/ms
ClientGrpc.getUser                         thrpt       3  10.442 ± 0.226  ops/ms
ClientGrpc.listUser                        thrpt       3   7.869 ± 0.544  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 0.643   ms/op
ClientGrpc.existUser                        avgt       3   2.915 ± 1.157   ms/op
ClientGrpc.getUser                          avgt       3   3.096 ± 0.619   ms/op
ClientGrpc.listUser                         avgt       3   4.070 ± 1.163   ms/op
ClientGrpc.createUser                     sample  316231   3.034 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.420           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.806           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.312           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  325648   2.947 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.601           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.010           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.821           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.758           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  311692   3.080 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.998           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.329           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  233744   4.106 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.219           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.224           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.691           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
