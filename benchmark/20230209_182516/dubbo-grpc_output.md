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
# Warmup Iteration   1: 4.868 ops/ms
# Warmup Iteration   2: 9.538 ops/ms
# Warmup Iteration   3: 10.076 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.227 ops/ms
Iteration   3: 10.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.403 ±(99.9%) 3.042 ops/ms [Average]
  (min, avg, max) = (10.227, 10.403, 10.558), stdev = 0.167
  CI (99.9%): [7.361, 13.445] (assumes normal distribution)


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
# Warmup Iteration   1: 8.310 ops/ms
# Warmup Iteration   2: 10.524 ops/ms
# Warmup Iteration   3: 10.907 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 10.810 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.859 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (10.810, 10.859, 10.913), stdev = 0.051
  CI (99.9%): [9.922, 11.796] (assumes normal distribution)


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
# Warmup Iteration   1: 6.955 ops/ms
# Warmup Iteration   2: 10.162 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.376 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.332 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (10.254, 10.332, 10.376), stdev = 0.068
  CI (99.9%): [9.094, 11.570] (assumes normal distribution)


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
# Warmup Iteration   1: 5.787 ops/ms
# Warmup Iteration   2: 8.094 ops/ms
# Warmup Iteration   3: 8.144 ops/ms
Iteration   1: 8.236 ops/ms
Iteration   2: 8.388 ops/ms
Iteration   3: 8.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.287 ±(99.9%) 1.589 ops/ms [Average]
  (min, avg, max) = (8.236, 8.287, 8.388), stdev = 0.087
  CI (99.9%): [6.698, 9.877] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.002 ms/op
Iteration   1: 3.091 ±(99.9%) 0.004 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.198 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.148 ±(99.9%) 0.981 ms/op [Average]
  (min, avg, max) = (3.091, 3.148, 3.198), stdev = 0.054
  CI (99.9%): [2.167, 4.130] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.936 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 2.820 ±(99.9%) 0.004 ms/op
Iteration   2: 2.853 ±(99.9%) 0.005 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (2.820, 2.894, 3.009), stdev = 0.101
  CI (99.9%): [1.054, 4.733] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.003 ms/op
Iteration   1: 3.089 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.037, 3.080, 3.115), stdev = 0.040
  CI (99.9%): [2.359, 3.802] (assumes normal distribution)


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
# Warmup Iteration   1: 4.436 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.006 ms/op
Iteration   1: 3.943 ±(99.9%) 0.023 ms/op
Iteration   2: 3.895 ±(99.9%) 0.080 ms/op
Iteration   3: 4.046 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (3.895, 3.961, 4.046), stdev = 0.077
  CI (99.9%): [2.558, 5.365] (assumes normal distribution)


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.356 ms/op
                 createUser·p0.9999: 16.594 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.521 ms/op
                 createUser·p0.9999: 14.250 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 14.771 ms/op
                 createUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308532
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1223 
    [ 1.250,  2.500) = 24957 
    [ 2.500,  3.750) = 250755 
    [ 3.750,  5.000) = 30495 
    [ 5.000,  6.250) = 540 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.272 ms/op
     p(99.9900) =     16.269 ms/op
     p(99.9990) =     16.840 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.606 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.275 ms/op
                 existUser·p0.9999: 12.943 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   2: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.997 ms/op
                 existUser·p0.9999: 14.909 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  8.663 ms/op
                 existUser·p0.9999: 15.870 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331713
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3183 
    [ 1.250,  2.500) = 49258 
    [ 2.500,  3.750) = 266361 
    [ 3.750,  5.000) = 12082 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 123 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.400 ms/op
     p(99.9900) =     15.021 ms/op
     p(99.9990) =     16.173 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.323 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.112 ms/op
                 getUser·p0.9999: 11.900 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.495 ms/op
                 getUser·p0.9999: 22.760 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  5.893 ms/op
                 getUser·p0.9999: 16.203 ms/op
                 getUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320742
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34893 
    [ 2.500,  5.000) = 284958 
    [ 5.000,  7.500) = 656 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.414 ms/op
     p(99.9900) =     20.648 ms/op
     p(99.9990) =     23.062 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.010 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.137 ms/op
                 listUser·p0.9999: 16.038 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.931 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.772 ms/op
                 listUser·p0.9999: 22.264 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 3.881 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.439 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 21.004 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245981
  mean =      3.901 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3900 
    [ 2.500,  5.000) = 220503 
    [ 5.000,  7.500) = 20524 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     21.280 ms/op
     p(99.9990) =     22.499 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.403 ± 3.042  ops/ms
ClientGrpc.existUser                       thrpt       3  10.859 ± 0.937  ops/ms
ClientGrpc.getUser                         thrpt       3  10.332 ± 1.238  ops/ms
ClientGrpc.listUser                        thrpt       3   8.287 ± 1.589  ops/ms
ClientGrpc.createUser                       avgt       3   3.148 ± 0.981   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 1.840   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.722   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 1.404   ms/op
ClientGrpc.createUser                     sample  308532   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.677           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.269           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.547           ms/op
ClientGrpc.existUser                      sample  331713   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.400           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  320742   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.323           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.414           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.648           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.134           ms/op
ClientGrpc.listUser                       sample  245981   3.901 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.969           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.611           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.730           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.280           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
