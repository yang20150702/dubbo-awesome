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
# Warmup Iteration   1: 4.453 ops/ms
# Warmup Iteration   2: 9.984 ops/ms
# Warmup Iteration   3: 10.568 ops/ms
Iteration   1: 11.174 ops/ms
Iteration   2: 11.026 ops/ms
Iteration   3: 10.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  11.056 ±(99.9%) 1.951 ops/ms [Average]
  (min, avg, max) = (10.967, 11.056, 11.174), stdev = 0.107
  CI (99.9%): [9.104, 13.007] (assumes normal distribution)


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
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 11.007 ops/ms
# Warmup Iteration   3: 11.693 ops/ms
Iteration   1: 11.712 ops/ms
Iteration   2: 11.383 ops/ms
Iteration   3: 11.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.605 ±(99.9%) 3.511 ops/ms [Average]
  (min, avg, max) = (11.383, 11.605, 11.721), stdev = 0.192
  CI (99.9%): [8.094, 15.117] (assumes normal distribution)


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
# Warmup Iteration   1: 7.426 ops/ms
# Warmup Iteration   2: 10.677 ops/ms
# Warmup Iteration   3: 11.098 ops/ms
Iteration   1: 11.022 ops/ms
Iteration   2: 10.994 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.934 ±(99.9%) 2.357 ops/ms [Average]
  (min, avg, max) = (10.785, 10.934, 11.022), stdev = 0.129
  CI (99.9%): [8.577, 13.291] (assumes normal distribution)


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
# Warmup Iteration   1: 6.354 ops/ms
# Warmup Iteration   2: 8.186 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.346 ops/ms
Iteration   2: 8.535 ops/ms
Iteration   3: 8.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.436 ±(99.9%) 1.729 ops/ms [Average]
  (min, avg, max) = (8.346, 8.436, 8.535), stdev = 0.095
  CI (99.9%): [6.707, 10.165] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.007 ms/op
Iteration   1: 2.894 ±(99.9%) 0.003 ms/op
Iteration   2: 2.851 ±(99.9%) 0.003 ms/op
Iteration   3: 2.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.865 ±(99.9%) 0.465 ms/op [Average]
  (min, avg, max) = (2.849, 2.865, 2.894), stdev = 0.026
  CI (99.9%): [2.399, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.852 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.004 ms/op
Iteration   1: 2.819 ±(99.9%) 0.004 ms/op
Iteration   2: 2.780 ±(99.9%) 0.003 ms/op
Iteration   3: 2.782 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.794 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.780, 2.794, 2.819), stdev = 0.022
  CI (99.9%): [2.396, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.002 ms/op
Iteration   1: 2.907 ±(99.9%) 0.002 ms/op
Iteration   2: 2.862 ±(99.9%) 0.002 ms/op
Iteration   3: 2.904 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.891 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (2.862, 2.891, 2.907), stdev = 0.025
  CI (99.9%): [2.427, 3.355] (assumes normal distribution)


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.021 ms/op
Iteration   1: 3.788 ±(99.9%) 0.005 ms/op
Iteration   2: 3.766 ±(99.9%) 0.013 ms/op
Iteration   3: 3.722 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.758 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.722, 3.758, 3.788), stdev = 0.034
  CI (99.9%): [3.144, 4.372] (assumes normal distribution)


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.005 ms/op
Iteration   1: 2.857 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.568 ms/op
                 createUser·p0.99:   4.133 ms/op
                 createUser·p0.999:  5.964 ms/op
                 createUser·p0.9999: 11.154 ms/op
                 createUser·p1.00:   11.387 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  7.018 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   3: 2.904 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   2.892 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  12.360 ms/op
                 createUser·p0.9999: 15.696 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 331794
  mean =      2.893 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46283 
    [ 2.500,  5.000) = 284319 
    [ 5.000,  7.500) = 879 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.252 ms/op
     p(99.9900) =     18.874 ms/op
     p(99.9990) =     20.230 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.831 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.693 ±(99.9%) 0.006 ms/op
Iteration   1: 2.794 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.781 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   3.991 ms/op
                 existUser·p0.999:  6.607 ms/op
                 existUser·p0.9999: 11.305 ms/op
                 existUser·p1.00:   11.518 ms/op

Iteration   2: 2.802 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   2.773 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.455 ms/op
                 existUser·p0.9999: 23.138 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 2.751 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.769 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 13.949 ms/op
                 existUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 345259
  mean =      2.782 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64928 
    [ 2.500,  5.000) = 279630 
    [ 5.000,  7.500) = 467 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.203 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.412 ms/op
     p(99.9900) =     16.080 ms/op
     p(99.9990) =     24.211 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.845 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.269 ms/op
                 getUser·p0.95:   3.473 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  6.860 ms/op
                 getUser·p0.9999: 22.667 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 2.826 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.843 ms/op
                 getUser·p0.90:   3.301 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  7.255 ms/op
                 getUser·p0.9999: 13.451 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  7.229 ms/op
                 getUser·p0.9999: 26.147 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 336490
  mean =      2.855 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48490 
    [ 2.500,  5.000) = 287023 
    [ 5.000,  7.500) = 745 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.334 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     22.928 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
Iteration   1: 3.816 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.517 ms/op
                 listUser·p0.999:  12.518 ms/op
                 listUser·p0.9999: 13.829 ms/op
                 listUser·p1.00:   14.893 ms/op

Iteration   2: 3.779 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.930 ms/op
                 listUser·p0.9999: 19.336 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.833 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.762 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  17.554 ms/op
                 listUser·p0.9999: 21.485 ms/op
                 listUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251965
  mean =      3.809 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4640 
    [ 2.500,  5.000) = 230278 
    [ 5.000,  7.500) = 15990 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     21.129 ms/op
     p(99.9990) =     22.771 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  11.056 ± 1.951  ops/ms
ClientGrpc.existUser                       thrpt       3  11.605 ± 3.511  ops/ms
ClientGrpc.getUser                         thrpt       3  10.934 ± 2.357  ops/ms
ClientGrpc.listUser                        thrpt       3   8.436 ± 1.729  ops/ms
ClientGrpc.createUser                       avgt       3   2.865 ± 0.465   ms/op
ClientGrpc.existUser                        avgt       3   2.794 ± 0.398   ms/op
ClientGrpc.getUser                          avgt       3   2.891 ± 0.464   ms/op
ClientGrpc.listUser                         avgt       3   3.758 ± 0.614   ms/op
ClientGrpc.createUser                     sample  331794   2.893 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.598           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.884           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.391           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.252           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.874           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  345259   2.782 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.773           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.203           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.412           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.080           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.773           ms/op
ClientGrpc.getUser                        sample  336490   2.855 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.580           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.859           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.334           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.104           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.053           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.928           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.378           ms/op
ClientGrpc.listUser                       sample  251965   3.809 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.762           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.674           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.517           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.129           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.069           ms/op
