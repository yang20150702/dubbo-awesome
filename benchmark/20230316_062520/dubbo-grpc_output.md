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
# Warmup Iteration   1: 4.780 ops/ms
# Warmup Iteration   2: 9.462 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.869 ops/ms
Iteration   2: 10.946 ops/ms
Iteration   3: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.932 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (10.869, 10.932, 10.981), stdev = 0.058
  CI (99.9%): [9.883, 11.982] (assumes normal distribution)


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
# Warmup Iteration   1: 8.096 ops/ms
# Warmup Iteration   2: 10.773 ops/ms
# Warmup Iteration   3: 11.298 ops/ms
Iteration   1: 11.704 ops/ms
Iteration   2: 11.587 ops/ms
Iteration   3: 11.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.515 ±(99.9%) 4.245 ops/ms [Average]
  (min, avg, max) = (11.255, 11.515, 11.704), stdev = 0.233
  CI (99.9%): [7.270, 15.760] (assumes normal distribution)


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
# Warmup Iteration   1: 8.518 ops/ms
# Warmup Iteration   2: 10.615 ops/ms
# Warmup Iteration   3: 10.826 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.943 ±(99.9%) 1.981 ops/ms [Average]
  (min, avg, max) = (10.837, 10.943, 11.054), stdev = 0.109
  CI (99.9%): [8.961, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 5.764 ops/ms
# Warmup Iteration   2: 8.218 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 8.535 ops/ms
Iteration   2: 8.548 ops/ms
Iteration   3: 8.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.609 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (8.535, 8.609, 8.744), stdev = 0.117
  CI (99.9%): [6.481, 10.737] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.919 ±(99.9%) 0.003 ms/op
Iteration   2: 2.861 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.899 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.861, 2.899, 2.919), stdev = 0.033
  CI (99.9%): [2.302, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.877 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.710 ±(99.9%) 0.003 ms/op
Iteration   1: 2.807 ±(99.9%) 0.003 ms/op
Iteration   2: 2.776 ±(99.9%) 0.003 ms/op
Iteration   3: 2.773 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.785 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (2.773, 2.785, 2.807), stdev = 0.019
  CI (99.9%): [2.442, 3.128] (assumes normal distribution)


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
# Warmup Iteration   1: 3.768 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.004 ms/op
Iteration   3: 2.926 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.935 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (2.918, 2.935, 2.962), stdev = 0.024
  CI (99.9%): [2.506, 3.365] (assumes normal distribution)


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.008 ms/op
Iteration   1: 3.767 ±(99.9%) 0.013 ms/op
Iteration   2: 3.775 ±(99.9%) 0.031 ms/op
Iteration   3: 3.818 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.787 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.767, 3.787, 3.818), stdev = 0.027
  CI (99.9%): [3.293, 4.280] (assumes normal distribution)


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.007 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.416 ms/op
                 createUser·p0.99:   3.949 ms/op
                 createUser·p0.999:  7.520 ms/op
                 createUser·p0.9999: 17.500 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 2.934 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.600 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.715 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.242 ms/op
                 createUser·p0.50:   2.896 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.470 ms/op
                 createUser·p0.9999: 19.757 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 329951
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36540 
    [ 2.500,  5.000) = 292331 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.242 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.870 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.005 ms/op
Iteration   1: 2.786 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.499 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  9.747 ms/op
                 existUser·p0.9999: 12.525 ms/op
                 existUser·p1.00:   13.042 ms/op

Iteration   2: 2.927 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 24.546 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 2.831 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.371 ms/op
                 existUser·p0.999:  5.998 ms/op
                 existUser·p0.9999: 13.671 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337220
  mean =      2.847 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57130 
    [ 2.500,  5.000) = 277340 
    [ 5.000,  7.500) = 2336 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =      9.181 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     24.781 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 2.946 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  10.568 ms/op
                 getUser·p0.9999: 14.046 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.876 ms/op
                 getUser·p0.9999: 14.975 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 2.923 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.165 ms/op
                 getUser·p0.9999: 16.665 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327155
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2559 
    [ 1.250,  2.500) = 39490 
    [ 2.500,  3.750) = 270692 
    [ 3.750,  5.000) = 12972 
    [ 5.000,  6.250) = 926 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.065 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.966 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.009 ms/op
Iteration   1: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  12.612 ms/op
                 listUser·p0.9999: 16.439 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.864 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 21.159 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.861 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.318 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.469 ms/op
                 listUser·p0.9999: 21.621 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249066
  mean =      3.856 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3859 
    [ 2.500,  5.000) = 226725 
    [ 5.000,  7.500) = 17444 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.434 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     21.906 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.932 ± 1.050  ops/ms
ClientGrpc.existUser                       thrpt       3  11.515 ± 4.245  ops/ms
ClientGrpc.getUser                         thrpt       3  10.943 ± 1.981  ops/ms
ClientGrpc.listUser                        thrpt       3   8.609 ± 2.128  ops/ms
ClientGrpc.createUser                       avgt       3   2.899 ± 0.597   ms/op
ClientGrpc.existUser                        avgt       3   2.785 ± 0.343   ms/op
ClientGrpc.getUser                          avgt       3   2.935 ± 0.429   ms/op
ClientGrpc.listUser                         avgt       3   3.787 ± 0.493   ms/op
ClientGrpc.createUser                     sample  329951   2.911 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.242           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.904           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.338           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.365           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.660           ms/op
ClientGrpc.existUser                      sample  337220   2.847 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.494           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.181           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.779           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.541           ms/op
ClientGrpc.getUser                        sample  327155   2.933 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.929           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.065           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.008           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.072           ms/op
ClientGrpc.listUser                       sample  249066   3.856 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.807           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
