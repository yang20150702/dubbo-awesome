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
# Warmup Iteration   1: 4.734 ops/ms
# Warmup Iteration   2: 9.481 ops/ms
# Warmup Iteration   3: 10.457 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.834 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.804 ±(99.9%) 2.263 ops/ms [Average]
  (min, avg, max) = (10.668, 10.804, 10.911), stdev = 0.124
  CI (99.9%): [8.541, 13.068] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ops/ms
# Warmup Iteration   2: 10.771 ops/ms
# Warmup Iteration   3: 11.269 ops/ms
Iteration   1: 11.210 ops/ms
Iteration   2: 11.345 ops/ms
Iteration   3: 11.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.213 ±(99.9%) 2.394 ops/ms [Average]
  (min, avg, max) = (11.083, 11.213, 11.345), stdev = 0.131
  CI (99.9%): [8.819, 13.607] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.796 ops/ms
# Warmup Iteration   2: 10.673 ops/ms
# Warmup Iteration   3: 10.539 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.648 ±(99.9%) 0.819 ops/ms [Average]
  (min, avg, max) = (10.601, 10.648, 10.691), stdev = 0.045
  CI (99.9%): [9.829, 11.467] (assumes normal distribution)


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
# Warmup Iteration   1: 7.112 ops/ms
# Warmup Iteration   2: 7.845 ops/ms
# Warmup Iteration   3: 8.305 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.693 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.382 ±(99.9%) 4.923 ops/ms [Average]
  (min, avg, max) = (8.207, 8.382, 8.693), stdev = 0.270
  CI (99.9%): [3.458, 13.305] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.002 ms/op
Iteration   1: 2.859 ±(99.9%) 0.003 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.928 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (2.859, 2.928, 2.978), stdev = 0.062
  CI (99.9%): [1.800, 4.055] (assumes normal distribution)


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
# Warmup Iteration   1: 3.809 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.901 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.826 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.009 ms/op
Iteration   2: 2.884 ±(99.9%) 0.004 ms/op
Iteration   3: 2.816 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 1.996 ms/op [Average]
  (min, avg, max) = (2.816, 2.910, 3.030), stdev = 0.109
  CI (99.9%): [0.914, 4.906] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.004 ms/op
Iteration   3: 2.936 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.934 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (2.915, 2.934, 2.953), stdev = 0.019
  CI (99.9%): [2.591, 3.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.007 ms/op
Iteration   1: 3.891 ±(99.9%) 0.050 ms/op
Iteration   2: 3.865 ±(99.9%) 0.031 ms/op
Iteration   3: 3.709 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.821 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (3.709, 3.821, 3.891), stdev = 0.099
  CI (99.9%): [2.023, 5.620] (assumes normal distribution)


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
# Warmup Iteration   1: 3.882 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  6.719 ms/op
                 createUser·p0.9999: 12.570 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  7.734 ms/op
                 createUser·p0.9999: 13.062 ms/op
                 createUser·p1.00:   15.008 ms/op

Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.521 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.750 ms/op
                 createUser·p0.9999: 25.302 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323237
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27806 
    [ 2.500,  5.000) = 293925 
    [ 5.000,  7.500) = 1203 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.330 ms/op
     p(99.9900) =     21.389 ms/op
     p(99.9990) =     25.667 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.885 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.006 ms/op
Iteration   1: 2.835 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.113 ms/op
                 existUser·p0.9999: 11.755 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   2: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.538 ms/op
                 existUser·p0.9999: 13.868 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  11.866 ms/op
                 existUser·p0.9999: 17.499 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334407
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1863 
    [ 1.250,  2.500) = 49484 
    [ 2.500,  3.750) = 272764 
    [ 3.750,  5.000) = 9364 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 175 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.874 ms/op
     p(99.9900) =     16.437 ms/op
     p(99.9990) =     17.585 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  9.238 ms/op
                 getUser·p0.9999: 18.033 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 3.004 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.500 ms/op
                 getUser·p0.9999: 12.611 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.527 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.440 ms/op
                 getUser·p0.9999: 15.339 ms/op
                 getUser·p1.00:   16.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320367
  mean =      2.994 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1108 
    [ 1.250,  2.500) = 16884 
    [ 2.500,  3.750) = 290816 
    [ 3.750,  5.000) = 10143 
    [ 5.000,  6.250) = 747 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.875 ms/op
     p(99.9900) =     15.351 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.673 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.954 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  14.374 ms/op
                 listUser·p0.9999: 18.463 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.576 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251418
  mean =      3.821 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3251 
    [ 2.500,  5.000) = 231268 
    [ 5.000,  7.500) = 15674 
    [ 7.500, 10.000) = 655 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     18.804 ms/op
     p(99.9990) =     20.217 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.804 ± 2.263  ops/ms
ClientGrpc.existUser                       thrpt       3  11.213 ± 2.394  ops/ms
ClientGrpc.getUser                         thrpt       3  10.648 ± 0.819  ops/ms
ClientGrpc.listUser                        thrpt       3   8.382 ± 4.923  ops/ms
ClientGrpc.createUser                       avgt       3   2.928 ± 1.127   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 1.996   ms/op
ClientGrpc.getUser                          avgt       3   2.934 ± 0.343   ms/op
ClientGrpc.listUser                         avgt       3   3.821 ± 1.798   ms/op
ClientGrpc.createUser                     sample  323237   2.971 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.521           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.437           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.330           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.389           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.723           ms/op
ClientGrpc.existUser                      sample  334407   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.874           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.437           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  320367   2.994 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.585           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.978           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.412           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.875           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.351           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.645           ms/op
ClientGrpc.listUser                       sample  251418   3.821 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.673           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.612           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.139           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.316           ms/op
