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
# Warmup Iteration   1: 4.137 ops/ms
# Warmup Iteration   2: 8.612 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 10.253 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.329 ±(99.9%) 1.828 ops/ms [Average]
  (min, avg, max) = (10.253, 10.329, 10.442), stdev = 0.100
  CI (99.9%): [8.501, 12.157] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.722 ±(99.9%) 0.707 ops/ms [Average]
  (min, avg, max) = (10.688, 10.722, 10.764), stdev = 0.039
  CI (99.9%): [10.015, 11.429] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.162 ops/ms
# Warmup Iteration   2: 9.648 ops/ms
# Warmup Iteration   3: 9.960 ops/ms
Iteration   1: 9.832 ops/ms
Iteration   2: 9.777 ops/ms
Iteration   3: 9.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.855 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (9.777, 9.855, 9.955), stdev = 0.091
  CI (99.9%): [8.189, 11.520] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.135 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.687 ops/ms
Iteration   1: 7.845 ops/ms
Iteration   2: 7.873 ops/ms
Iteration   3: 7.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.818 ±(99.9%) 1.339 ops/ms [Average]
  (min, avg, max) = (7.735, 7.818, 7.873), stdev = 0.073
  CI (99.9%): [6.479, 9.156] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.470 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.109 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (3.084, 3.109, 3.157), stdev = 0.042
  CI (99.9%): [2.349, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.953 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.972 ±(99.9%) 0.302 ms/op [Average]
  (min, avg, max) = (2.953, 2.972, 2.983), stdev = 0.017
  CI (99.9%): [2.670, 3.274] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.002 ms/op
Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 0.722 ms/op [Average]
  (min, avg, max) = (3.078, 3.118, 3.157), stdev = 0.040
  CI (99.9%): [2.396, 3.839] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.963 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.025 ms/op
Iteration   1: 4.059 ±(99.9%) 0.030 ms/op
Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
Iteration   3: 4.027 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.016 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.961, 4.016, 4.059), stdev = 0.050
  CI (99.9%): [3.109, 4.922] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 12.871 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.594 ms/op
                 createUser·p0.999:  7.957 ms/op
                 createUser·p0.9999: 15.450 ms/op
                 createUser·p1.00:   15.614 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.590 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  16.325 ms/op
                 createUser·p0.9999: 17.955 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304659
  mean =      3.150 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 14559 
    [ 2.500,  3.750) = 260995 
    [ 3.750,  5.000) = 25920 
    [ 5.000,  6.250) = 1549 
    [ 6.250,  7.500) = 718 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 65 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     17.581 ms/op
     p(99.9990) =     18.052 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  8.975 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   15.516 ms/op

Iteration   2: 2.985 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  10.345 ms/op
                 existUser·p0.9999: 28.475 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  9.864 ms/op
                 existUser·p0.9999: 16.824 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319172
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24889 
    [ 2.500,  5.000) = 291473 
    [ 5.000,  7.500) = 2295 
    [ 7.500, 10.000) = 223 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     27.694 ms/op
     p(99.9990) =     28.600 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 4.461 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
Iteration   1: 3.130 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.605 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.845 ms/op
                 getUser·p0.9999: 27.125 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   2: 3.116 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  12.459 ms/op
                 getUser·p0.9999: 35.568 ms/op
                 getUser·p1.00:   36.045 ms/op

Iteration   3: 3.145 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  9.776 ms/op
                 getUser·p0.9999: 27.683 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306708
  mean =      3.130 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16465 
    [ 2.500,  5.000) = 287629 
    [ 5.000,  7.500) = 2084 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     34.690 ms/op
     p(99.9990) =     35.975 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 5.078 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.012 ms/op
Iteration   1: 4.110 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.841 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.068 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.277 ms/op
                 listUser·p0.999:  17.854 ms/op
                 listUser·p0.9999: 20.223 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  17.524 ms/op
                 listUser·p0.9999: 26.366 ms/op
                 listUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233613
  mean =      4.106 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1608 
    [ 2.500,  5.000) = 207631 
    [ 5.000,  7.500) = 22323 
    [ 7.500, 10.000) = 1603 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.721 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.329 ± 1.828  ops/ms
ClientGrpc.existUser                       thrpt       3  10.722 ± 0.707  ops/ms
ClientGrpc.getUser                         thrpt       3   9.855 ± 1.666  ops/ms
ClientGrpc.listUser                        thrpt       3   7.818 ± 1.339  ops/ms
ClientGrpc.createUser                       avgt       3   3.109 ± 0.760   ms/op
ClientGrpc.existUser                        avgt       3   2.972 ± 0.302   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 0.722   ms/op
ClientGrpc.listUser                         avgt       3   4.016 ± 0.907   ms/op
ClientGrpc.createUser                     sample  304659   3.150 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.590           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.940           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.601           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.581           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  319172   3.008 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.678           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.519           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.694           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.327           ms/op
ClientGrpc.getUser                        sample  306708   3.130 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.605           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.011           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.690           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.045           ms/op
ClientGrpc.listUser                       sample  233613   4.106 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.841           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.526           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.886           ms/op
