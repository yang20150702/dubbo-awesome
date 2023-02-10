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
# Warmup Iteration   1: 4.679 ops/ms
# Warmup Iteration   2: 9.319 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.730 ops/ms
Iteration   2: 9.915 ops/ms
Iteration   3: 9.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.197 ±(99.9%) 8.418 ops/ms [Average]
  (min, avg, max) = (9.915, 10.197, 10.730), stdev = 0.461
  CI (99.9%): [1.779, 18.615] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 10.945 ops/ms
# Warmup Iteration   3: 10.981 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.098 ops/ms
Iteration   3: 11.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.072 ±(99.9%) 0.415 ops/ms [Average]
  (min, avg, max) = (11.054, 11.072, 11.098), stdev = 0.023
  CI (99.9%): [10.657, 11.488] (assumes normal distribution)


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
# Warmup Iteration   1: 7.633 ops/ms
# Warmup Iteration   2: 10.729 ops/ms
# Warmup Iteration   3: 10.651 ops/ms
Iteration   1: 10.012 ops/ms
Iteration   2: 10.004 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.075 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (10.004, 10.075, 10.208), stdev = 0.116
  CI (99.9%): [7.959, 12.190] (assumes normal distribution)


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
# Warmup Iteration   1: 6.566 ops/ms
# Warmup Iteration   2: 7.309 ops/ms
# Warmup Iteration   3: 7.657 ops/ms
Iteration   1: 7.768 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 8.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.958 ±(99.9%) 4.256 ops/ms [Average]
  (min, avg, max) = (7.768, 7.958, 8.218), stdev = 0.233
  CI (99.9%): [3.702, 12.214] (assumes normal distribution)


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.001 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
Iteration   2: 3.092 ±(99.9%) 0.003 ms/op
Iteration   3: 3.187 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.141 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (3.092, 3.141, 3.187), stdev = 0.048
  CI (99.9%): [2.270, 4.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.001 ms/op
Iteration   3: 3.035 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.023 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.012, 3.023, 3.035), stdev = 0.011
  CI (99.9%): [2.818, 3.228] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.001 ms/op
Iteration   2: 3.020 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.032 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.017, 3.032, 3.059), stdev = 0.023
  CI (99.9%): [2.608, 3.456] (assumes normal distribution)


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
# Warmup Iteration   1: 5.681 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.012 ms/op
Iteration   1: 3.976 ±(99.9%) 0.040 ms/op
Iteration   2: 4.133 ±(99.9%) 0.009 ms/op
Iteration   3: 4.040 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.050 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.976, 4.050, 4.133), stdev = 0.079
  CI (99.9%): [2.612, 5.488] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.270 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.889 ms/op
                 createUser·p0.9999: 13.725 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  9.265 ms/op
                 createUser·p0.9999: 15.936 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   2.888 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.627 ms/op
                 createUser·p0.9999: 16.581 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315840
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 590 
    [ 1.250,  2.500) = 40697 
    [ 2.500,  3.750) = 248566 
    [ 3.750,  5.000) = 24974 
    [ 5.000,  6.250) = 314 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.270 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     16.135 ms/op
     p(99.9990) =     18.046 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.869 ms/op
                 existUser·p0.9999: 14.500 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  12.321 ms/op
                 existUser·p0.9999: 15.012 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  11.116 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322540
  mean =      2.977 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1754 
    [ 1.250,  2.500) = 56742 
    [ 2.500,  3.750) = 238918 
    [ 3.750,  5.000) = 23831 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 225 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 61 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     10.428 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     17.257 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.850 ±(99.9%) 0.007 ms/op
Iteration   1: 2.863 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.834 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  7.137 ms/op
                 getUser·p0.9999: 18.574 ms/op
                 getUser·p1.00:   19.104 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.888 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.060 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.827 ms/op
                 getUser·p0.9999: 35.491 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325311
  mean =      2.950 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 59831 
    [ 2.500,  5.000) = 264622 
    [ 5.000,  7.500) = 580 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.182 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     36.094 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.657 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.648 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 21.066 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.808 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  15.385 ms/op
                 listUser·p0.9999: 21.024 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.906 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  14.289 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249593
  mean =      3.844 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3566 
    [ 2.500,  5.000) = 221936 
    [ 5.000,  7.500) = 22972 
    [ 7.500, 10.000) = 651 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.605 ms/op
     p(99.9900) =     26.444 ms/op
     p(99.9990) =     30.459 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.197 ± 8.418  ops/ms
ClientGrpc.existUser                       thrpt       3  11.072 ± 0.415  ops/ms
ClientGrpc.getUser                         thrpt       3  10.075 ± 2.116  ops/ms
ClientGrpc.listUser                        thrpt       3   7.958 ± 4.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.141 ± 0.871   ms/op
ClientGrpc.existUser                        avgt       3   3.023 ± 0.205   ms/op
ClientGrpc.getUser                          avgt       3   3.032 ± 0.424   ms/op
ClientGrpc.listUser                         avgt       3   4.050 ± 1.438   ms/op
ClientGrpc.createUser                     sample  315840   3.040 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.270           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.102           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.135           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.416           ms/op
ClientGrpc.existUser                      sample  322540   2.977 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.428           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.778           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  325311   2.950 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.904           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.182           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.734           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.635           ms/op
ClientGrpc.listUser                       sample  249593   3.844 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.658           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.605           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.444           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.900           ms/op
