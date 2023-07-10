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
# Warmup Iteration   1: 4.537 ops/ms
# Warmup Iteration   2: 9.613 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.471 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.628 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (10.471, 10.628, 10.735), stdev = 0.138
  CI (99.9%): [8.101, 13.154] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.672 ops/ms
# Warmup Iteration   2: 10.880 ops/ms
# Warmup Iteration   3: 11.231 ops/ms
Iteration   1: 11.322 ops/ms
Iteration   2: 11.626 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.339 ±(99.9%) 5.075 ops/ms [Average]
  (min, avg, max) = (11.070, 11.339, 11.626), stdev = 0.278
  CI (99.9%): [6.264, 16.414] (assumes normal distribution)


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
# Warmup Iteration   1: 7.704 ops/ms
# Warmup Iteration   2: 10.147 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.585 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.641 ±(99.9%) 1.841 ops/ms [Average]
  (min, avg, max) = (10.581, 10.641, 10.758), stdev = 0.101
  CI (99.9%): [8.800, 12.483] (assumes normal distribution)


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
# Warmup Iteration   1: 5.786 ops/ms
# Warmup Iteration   2: 8.068 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.166 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 0.886 ops/ms [Average]
  (min, avg, max) = (8.088, 8.144, 8.177), stdev = 0.049
  CI (99.9%): [7.257, 9.030] (assumes normal distribution)


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.961 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (2.956, 2.961, 2.967), stdev = 0.005
  CI (99.9%): [2.864, 3.058] (assumes normal distribution)


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
# Warmup Iteration   1: 3.645 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.004 ms/op
Iteration   1: 2.892 ±(99.9%) 0.003 ms/op
Iteration   2: 2.871 ±(99.9%) 0.005 ms/op
Iteration   3: 2.945 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (2.871, 2.902, 2.945), stdev = 0.038
  CI (99.9%): [2.210, 3.595] (assumes normal distribution)


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 2.965 ±(99.9%) 0.002 ms/op
Iteration   2: 3.025 ±(99.9%) 0.002 ms/op
Iteration   3: 3.024 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.628 ms/op [Average]
  (min, avg, max) = (2.965, 3.005, 3.025), stdev = 0.034
  CI (99.9%): [2.377, 3.633] (assumes normal distribution)


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
# Warmup Iteration   1: 5.147 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.951 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.008 ms/op
Iteration   1: 3.875 ±(99.9%) 0.010 ms/op
Iteration   2: 3.900 ±(99.9%) 0.043 ms/op
Iteration   3: 3.926 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.875, 3.900, 3.926), stdev = 0.025
  CI (99.9%): [3.441, 4.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.970 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.005 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.685 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.135 ms/op
                 createUser·p0.9999: 11.375 ms/op
                 createUser·p1.00:   11.583 ms/op

Iteration   2: 3.025 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.923 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.352 ms/op
                 createUser·p0.9999: 28.059 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320549
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29682 
    [ 2.500,  5.000) = 289654 
    [ 5.000,  7.500) = 889 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.887 ms/op
     p(99.9900) =     26.749 ms/op
     p(99.9990) =     28.338 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.007 ms/op
Iteration   1: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 19.066 ms/op
                 existUser·p1.00:   19.497 ms/op

Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.587 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 11.860 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.817 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  7.264 ms/op
                 existUser·p0.9999: 15.852 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335087
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3299 
    [ 1.250,  2.500) = 38917 
    [ 2.500,  3.750) = 282584 
    [ 3.750,  5.000) = 9062 
    [ 5.000,  6.250) = 721 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.158 ms/op
     p(99.9900) =     18.284 ms/op
     p(99.9990) =     19.387 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.178 ms/op
                 getUser·p0.9999: 21.877 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.292 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   3: 2.990 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 17.677 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318564
  mean =      3.013 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31649 
    [ 2.500,  5.000) = 285116 
    [ 5.000,  7.500) = 1506 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.340 ms/op
     p(99.9900) =     21.084 ms/op
     p(99.9990) =     22.911 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.010 ms/op
Iteration   1: 3.908 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  12.602 ms/op
                 listUser·p0.9999: 13.908 ms/op
                 listUser·p1.00:   14.795 ms/op

Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.665 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.333 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.188 ms/op
                 listUser·p0.9999: 16.497 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.872 ms/op
                 listUser·p0.9999: 22.278 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243297
  mean =      3.946 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3956 
    [ 2.500,  5.000) = 217225 
    [ 5.000,  7.500) = 20671 
    [ 7.500, 10.000) = 868 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.823 ms/op
     p(99.9900) =     20.764 ms/op
     p(99.9990) =     22.764 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.628 ± 2.526  ops/ms
ClientGrpc.existUser                       thrpt       3  11.339 ± 5.075  ops/ms
ClientGrpc.getUser                         thrpt       3  10.641 ± 1.841  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 0.886  ops/ms
ClientGrpc.createUser                       avgt       3   2.961 ± 0.097   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.693   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.628   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 0.459   ms/op
ClientGrpc.createUser                     sample  320549   2.997 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.375           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.887           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.749           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.508           ms/op
ClientGrpc.existUser                      sample  335087   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.590           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.391           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.284           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.497           ms/op
ClientGrpc.getUser                        sample  318564   3.013 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.575           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.340           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.084           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  243297   3.946 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.665           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.823           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.764           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
