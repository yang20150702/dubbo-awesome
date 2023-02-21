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
# Warmup Iteration   1: 5.226 ops/ms
# Warmup Iteration   2: 9.592 ops/ms
# Warmup Iteration   3: 10.552 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.727 ops/ms
Iteration   3: 10.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.665 ±(99.9%) 1.303 ops/ms [Average]
  (min, avg, max) = (10.587, 10.665, 10.727), stdev = 0.071
  CI (99.9%): [9.363, 11.968] (assumes normal distribution)


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
# Warmup Iteration   1: 8.924 ops/ms
# Warmup Iteration   2: 10.705 ops/ms
# Warmup Iteration   3: 11.132 ops/ms
Iteration   1: 11.216 ops/ms
Iteration   2: 11.416 ops/ms
Iteration   3: 11.420 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.351 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (11.216, 11.351, 11.420), stdev = 0.117
  CI (99.9%): [9.224, 13.478] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.465 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.423 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 9.975 ops/ms
Iteration   3: 10.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.258 ±(99.9%) 4.488 ops/ms [Average]
  (min, avg, max) = (9.975, 10.258, 10.424), stdev = 0.246
  CI (99.9%): [5.770, 14.746] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.765 ops/ms
# Warmup Iteration   2: 7.689 ops/ms
# Warmup Iteration   3: 8.131 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.111 ±(99.9%) 2.190 ops/ms [Average]
  (min, avg, max) = (7.985, 8.111, 8.224), stdev = 0.120
  CI (99.9%): [5.920, 10.301] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 3.166 ±(99.9%) 0.011 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 3.170 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.110 ±(99.9%) 1.826 ms/op [Average]
  (min, avg, max) = (2.995, 3.110, 3.170), stdev = 0.100
  CI (99.9%): [1.284, 4.937] (assumes normal distribution)


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.998 ±(99.9%) 0.001 ms/op
Iteration   2: 2.896 ±(99.9%) 0.005 ms/op
Iteration   3: 2.954 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (2.896, 2.949, 2.998), stdev = 0.051
  CI (99.9%): [2.017, 3.881] (assumes normal distribution)


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.003 ms/op
Iteration   3: 2.995 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (2.977, 3.006, 3.047), stdev = 0.036
  CI (99.9%): [2.344, 3.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.928 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.032 ms/op
Iteration   1: 3.979 ±(99.9%) 0.016 ms/op
Iteration   2: 4.006 ±(99.9%) 0.017 ms/op
Iteration   3: 3.907 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.964 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (3.907, 3.964, 4.006), stdev = 0.051
  CI (99.9%): [3.036, 4.893] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
Iteration   1: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.021 ms/op
                 createUser·p0.9999: 11.567 ms/op
                 createUser·p1.00:   11.960 ms/op

Iteration   2: 3.166 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.366 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.407 ms/op
                 createUser·p0.9999: 14.841 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.135 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.828 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 26.280 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304516
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24603 
    [ 2.500,  5.000) = 278894 
    [ 5.000,  7.500) = 637 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.526 ms/op
     p(99.9900) =     25.202 ms/op
     p(99.9990) =     27.719 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 18.617 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 2.823 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.677 ms/op
                 existUser·p0.9999: 13.506 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   3: 2.917 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.422 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332251
  mean =      2.888 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58298 
    [ 2.500,  5.000) = 273422 
    [ 5.000,  7.500) = 307 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      5.978 ms/op
     p(99.9900) =     19.311 ms/op
     p(99.9990) =     21.999 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.282 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  5.767 ms/op
                 getUser·p0.9999: 12.884 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 16.300 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.190 ms/op
                 getUser·p0.999:  7.142 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322029
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28507 
    [ 2.500,  5.000) = 292659 
    [ 5.000,  7.500) = 553 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.282 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.257 ms/op
     p(99.9900) =     17.518 ms/op
     p(99.9990) =     22.574 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.011 ms/op
Iteration   1: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  12.827 ms/op
                 listUser·p0.9999: 16.287 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.977 ms/op
                 listUser·p0.9999: 23.787 ms/op
                 listUser·p1.00:   25.100 ms/op

Iteration   3: 3.958 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240894
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5596 
    [ 2.500,  5.000) = 204120 
    [ 5.000,  7.500) = 29823 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     23.554 ms/op
     p(99.9990) =     32.545 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.665 ± 1.303  ops/ms
ClientGrpc.existUser                       thrpt       3  11.351 ± 2.127  ops/ms
ClientGrpc.getUser                         thrpt       3  10.258 ± 4.488  ops/ms
ClientGrpc.listUser                        thrpt       3   8.111 ± 2.190  ops/ms
ClientGrpc.createUser                       avgt       3   3.110 ± 1.826   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.932   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.662   ms/op
ClientGrpc.listUser                         avgt       3   3.964 ± 0.929   ms/op
ClientGrpc.createUser                     sample  304516   3.149 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.366           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.526           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.787           ms/op
ClientGrpc.existUser                      sample  332251   2.888 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.462           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.166           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.978           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.311           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.249           ms/op
ClientGrpc.getUser                        sample  322029   2.981 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.282           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.257           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.518           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.938           ms/op
ClientGrpc.listUser                       sample  240894   3.987 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.692           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.554           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.670           ms/op
