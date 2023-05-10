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
# Warmup Iteration   1: 4.689 ops/ms
# Warmup Iteration   2: 9.193 ops/ms
# Warmup Iteration   3: 10.047 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.523 ±(99.9%) 0.614 ops/ms [Average]
  (min, avg, max) = (10.487, 10.523, 10.554), stdev = 0.034
  CI (99.9%): [9.909, 11.137] (assumes normal distribution)


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
# Warmup Iteration   1: 7.775 ops/ms
# Warmup Iteration   2: 10.722 ops/ms
# Warmup Iteration   3: 11.159 ops/ms
Iteration   1: 11.122 ops/ms
Iteration   2: 11.113 ops/ms
Iteration   3: 11.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.154 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (11.113, 11.154, 11.226), stdev = 0.063
  CI (99.9%): [10.002, 12.305] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.663 ops/ms
Iteration   1: 10.583 ops/ms
Iteration   2: 10.742 ops/ms
Iteration   3: 10.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.705 ±(99.9%) 1.987 ops/ms [Average]
  (min, avg, max) = (10.583, 10.705, 10.792), stdev = 0.109
  CI (99.9%): [8.718, 12.693] (assumes normal distribution)


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
# Warmup Iteration   1: 6.286 ops/ms
# Warmup Iteration   2: 8.152 ops/ms
# Warmup Iteration   3: 8.450 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.354 ops/ms
Iteration   3: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.340 ±(99.9%) 1.174 ops/ms [Average]
  (min, avg, max) = (8.270, 8.340, 8.396), stdev = 0.064
  CI (99.9%): [7.166, 9.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.006 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.947 ±(99.9%) 0.002 ms/op
Iteration   3: 2.923 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.939 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.923, 2.939, 2.948), stdev = 0.014
  CI (99.9%): [2.675, 3.204] (assumes normal distribution)


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
# Warmup Iteration   1: 3.679 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.870 ±(99.9%) 0.002 ms/op
Iteration   1: 2.869 ±(99.9%) 0.002 ms/op
Iteration   2: 2.799 ±(99.9%) 0.004 ms/op
Iteration   3: 2.793 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.820 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (2.793, 2.820, 2.869), stdev = 0.042
  CI (99.9%): [2.049, 3.591] (assumes normal distribution)


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.003 ms/op
Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
Iteration   3: 2.929 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.959 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (2.929, 2.959, 2.984), stdev = 0.028
  CI (99.9%): [2.456, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 4.940 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.004 ms/op
Iteration   1: 3.861 ±(99.9%) 0.019 ms/op
Iteration   2: 3.671 ±(99.9%) 0.023 ms/op
Iteration   3: 3.754 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.762 ±(99.9%) 1.741 ms/op [Average]
  (min, avg, max) = (3.671, 3.762, 3.861), stdev = 0.095
  CI (99.9%): [2.021, 5.503] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  7.868 ms/op
                 createUser·p0.9999: 12.359 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 22.562 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  13.255 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   31.687 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321042
  mean =      2.989 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34275 
    [ 2.500,  5.000) = 284598 
    [ 5.000,  7.500) = 1664 
    [ 7.500, 10.000) = 157 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =     10.518 ms/op
     p(99.9900) =     22.832 ms/op
     p(99.9990) =     31.687 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.006 ms/op
Iteration   1: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  6.603 ms/op
                 existUser·p0.9999: 11.420 ms/op
                 existUser·p1.00:   11.665 ms/op

Iteration   2: 2.848 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.885 ms/op
                 existUser·p0.9999: 14.542 ms/op
                 existUser·p1.00:   14.877 ms/op

Iteration   3: 2.888 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 15.505 ms/op
                 existUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334103
  mean =      2.872 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2075 
    [ 1.250,  2.500) = 47400 
    [ 2.500,  3.750) = 273971 
    [ 3.750,  5.000) = 9670 
    [ 5.000,  6.250) = 594 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.423 ms/op
     p(99.9900) =     15.041 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


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
# Warmup Iteration   1: 3.855 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  11.602 ms/op
                 getUser·p0.9999: 15.474 ms/op
                 getUser·p1.00:   16.024 ms/op

Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  8.177 ms/op
                 getUser·p0.9999: 28.776 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 2.951 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.139 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322012
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32632 
    [ 2.500,  5.000) = 287708 
    [ 5.000,  7.500) = 1163 
    [ 7.500, 10.000) = 270 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     26.808 ms/op
     p(99.9990) =     28.967 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.010 ms/op
Iteration   1: 3.838 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.552 ms/op
                 listUser·p0.9999: 18.011 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 3.828 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.295 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  16.078 ms/op
                 listUser·p0.9999: 24.433 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.418 ms/op
                 listUser·p0.9999: 17.420 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250912
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5851 
    [ 2.500,  5.000) = 223949 
    [ 5.000,  7.500) = 19912 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.295 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     24.723 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.523 ± 0.614  ops/ms
ClientGrpc.existUser                       thrpt       3  11.154 ± 1.151  ops/ms
ClientGrpc.getUser                         thrpt       3  10.705 ± 1.987  ops/ms
ClientGrpc.listUser                        thrpt       3   8.340 ± 1.174  ops/ms
ClientGrpc.createUser                       avgt       3   2.939 ± 0.265   ms/op
ClientGrpc.existUser                        avgt       3   2.820 ± 0.771   ms/op
ClientGrpc.getUser                          avgt       3   2.959 ± 0.503   ms/op
ClientGrpc.listUser                         avgt       3   3.762 ± 1.741   ms/op
ClientGrpc.createUser                     sample  321042   2.989 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.573           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.518           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.832           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.687           ms/op
ClientGrpc.existUser                      sample  334103   2.872 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.658           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.423           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.991           ms/op
ClientGrpc.getUser                        sample  322012   2.980 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.648           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.405           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.808           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.032           ms/op
ClientGrpc.listUser                       sample  250912   3.828 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.295           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.682           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.512           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.773           ms/op
