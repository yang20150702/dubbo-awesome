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
# Warmup Iteration   1: 4.297 ops/ms
# Warmup Iteration   2: 9.438 ops/ms
# Warmup Iteration   3: 10.212 ops/ms
Iteration   1: 10.832 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.703 ±(99.9%) 2.042 ops/ms [Average]
  (min, avg, max) = (10.635, 10.703, 10.832), stdev = 0.112
  CI (99.9%): [8.660, 12.745] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.097 ops/ms
# Warmup Iteration   2: 10.785 ops/ms
# Warmup Iteration   3: 10.921 ops/ms
Iteration   1: 11.069 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 11.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.100 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (10.974, 11.100, 11.257), stdev = 0.144
  CI (99.9%): [8.472, 13.729] (assumes normal distribution)


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
# Warmup Iteration   1: 8.249 ops/ms
# Warmup Iteration   2: 10.233 ops/ms
# Warmup Iteration   3: 10.820 ops/ms
Iteration   1: 10.733 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.644 ±(99.9%) 1.705 ops/ms [Average]
  (min, avg, max) = (10.547, 10.644, 10.733), stdev = 0.093
  CI (99.9%): [8.939, 12.349] (assumes normal distribution)


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
# Warmup Iteration   1: 6.062 ops/ms
# Warmup Iteration   2: 8.035 ops/ms
# Warmup Iteration   3: 8.312 ops/ms
Iteration   1: 8.365 ops/ms
Iteration   2: 8.360 ops/ms
Iteration   3: 8.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.421 ±(99.9%) 1.865 ops/ms [Average]
  (min, avg, max) = (8.360, 8.421, 8.539), stdev = 0.102
  CI (99.9%): [6.557, 10.286] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.004 ms/op
Iteration   1: 3.001 ±(99.9%) 0.003 ms/op
Iteration   2: 3.022 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (3.001, 3.025, 3.054), stdev = 0.027
  CI (99.9%): [2.534, 3.517] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.928 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.003 ms/op
Iteration   1: 2.899 ±(99.9%) 0.002 ms/op
Iteration   2: 2.752 ±(99.9%) 0.004 ms/op
Iteration   3: 2.875 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.842 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (2.752, 2.842, 2.899), stdev = 0.079
  CI (99.9%): [1.406, 4.277] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.003 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (2.905, 2.956, 3.006), stdev = 0.051
  CI (99.9%): [2.035, 3.878] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.015 ms/op
Iteration   1: 3.825 ±(99.9%) 0.017 ms/op
Iteration   2: 3.766 ±(99.9%) 0.061 ms/op
Iteration   3: 3.887 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.826 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.766, 3.826, 3.887), stdev = 0.061
  CI (99.9%): [2.717, 4.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.948 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.633 ms/op
                 createUser·p0.9999: 14.786 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.571 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.374 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.253 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.142 ms/op
                 createUser·p0.9999: 31.064 ms/op
                 createUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318505
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29135 
    [ 2.500,  5.000) = 287854 
    [ 5.000,  7.500) = 1100 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.253 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     29.108 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.916 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.005 ms/op
Iteration   1: 2.776 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.240 ms/op
                 existUser·p0.9999: 12.770 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.597 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  7.634 ms/op
                 existUser·p0.9999: 14.450 ms/op
                 existUser·p1.00:   14.778 ms/op

Iteration   3: 2.864 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337136
  mean =      2.847 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53582 
    [ 2.500,  5.000) = 282205 
    [ 5.000,  7.500) = 993 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.594 ms/op
     p(99.9900) =     23.570 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 15.327 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   2: 2.899 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.225 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.589 ms/op
                 getUser·p0.9999: 16.416 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.536 ms/op
                 getUser·p0.999:  6.910 ms/op
                 getUser·p0.9999: 20.782 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325663
  mean =      2.946 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36936 
    [ 2.500,  5.000) = 287520 
    [ 5.000,  7.500) = 918 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.225 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.195 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     21.872 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 4.566 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
Iteration   1: 3.727 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.304 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  15.775 ms/op
                 listUser·p0.9999: 20.088 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.214 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.747 ms/op
                 listUser·p0.9999: 22.544 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251210
  mean =      3.823 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5617 
    [ 2.500,  5.000) = 226800 
    [ 5.000,  7.500) = 17719 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      6.700 ms/op
     p(99.9000) =     13.923 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     22.659 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.703 ± 2.042  ops/ms
ClientGrpc.existUser                       thrpt       3  11.100 ± 2.629  ops/ms
ClientGrpc.getUser                         thrpt       3  10.644 ± 1.705  ops/ms
ClientGrpc.listUser                        thrpt       3   8.421 ± 1.865  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.492   ms/op
ClientGrpc.existUser                        avgt       3   2.842 ± 1.436   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.922   ms/op
ClientGrpc.listUser                         avgt       3   3.826 ± 1.109   ms/op
ClientGrpc.createUser                     sample  318505   3.016 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.253           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.108           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.556           ms/op
ClientGrpc.existUser                      sample  337136   2.847 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.597           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.456           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.594           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.570           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.543           ms/op
ClientGrpc.getUser                        sample  325663   2.946 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.225           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.195           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.578           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  251210   3.823 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.813           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.923           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.823           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.675           ms/op
