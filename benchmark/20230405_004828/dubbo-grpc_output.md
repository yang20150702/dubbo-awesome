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
# Warmup Iteration   1: 4.736 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.752 ops/ms
Iteration   3: 10.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.668 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (10.532, 10.668, 10.752), stdev = 0.119
  CI (99.9%): [8.497, 12.839] (assumes normal distribution)


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
# Warmup Iteration   1: 7.711 ops/ms
# Warmup Iteration   2: 10.651 ops/ms
# Warmup Iteration   3: 11.109 ops/ms
Iteration   1: 11.224 ops/ms
Iteration   2: 11.182 ops/ms
Iteration   3: 11.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.163 ±(99.9%) 1.311 ops/ms [Average]
  (min, avg, max) = (11.084, 11.163, 11.224), stdev = 0.072
  CI (99.9%): [9.852, 12.474] (assumes normal distribution)


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
# Warmup Iteration   1: 7.753 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.644 ops/ms
Iteration   1: 10.562 ops/ms
Iteration   2: 10.396 ops/ms
Iteration   3: 10.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.543 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (10.396, 10.543, 10.670), stdev = 0.138
  CI (99.9%): [8.025, 13.061] (assumes normal distribution)


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
# Warmup Iteration   1: 5.668 ops/ms
# Warmup Iteration   2: 8.129 ops/ms
# Warmup Iteration   3: 8.222 ops/ms
Iteration   1: 8.245 ops/ms
Iteration   2: 8.260 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.212 ±(99.9%) 1.285 ops/ms [Average]
  (min, avg, max) = (8.131, 8.212, 8.260), stdev = 0.070
  CI (99.9%): [6.927, 9.497] (assumes normal distribution)


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.004 ms/op
Iteration   3: 3.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.008 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (2.971, 3.008, 3.052), stdev = 0.041
  CI (99.9%): [2.256, 3.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.002 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.793 ±(99.9%) 0.002 ms/op
Iteration   3: 2.880 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.880 ±(99.9%) 1.587 ms/op [Average]
  (min, avg, max) = (2.793, 2.880, 2.967), stdev = 0.087
  CI (99.9%): [1.293, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.003 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.014 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (2.998, 3.014, 3.042), stdev = 0.025
  CI (99.9%): [2.567, 3.462] (assumes normal distribution)


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
# Warmup Iteration   1: 5.222 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.014 ms/op
Iteration   1: 3.922 ±(99.9%) 0.021 ms/op
Iteration   2: 3.853 ±(99.9%) 0.022 ms/op
Iteration   3: 3.884 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.886 ±(99.9%) 0.630 ms/op [Average]
  (min, avg, max) = (3.853, 3.886, 3.922), stdev = 0.035
  CI (99.9%): [3.256, 4.517] (assumes normal distribution)


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
# Warmup Iteration   1: 4.195 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.970 ms/op
                 createUser·p0.9999: 12.597 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.344 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  7.227 ms/op
                 createUser·p0.9999: 14.495 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.454 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.709 ms/op
                 createUser·p0.9999: 17.000 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317666
  mean =      3.024 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 468 
    [ 1.250,  2.500) = 22124 
    [ 2.500,  3.750) = 279547 
    [ 3.750,  5.000) = 14137 
    [ 5.000,  6.250) = 879 
    [ 6.250,  7.500) = 202 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.441 ms/op
     p(99.9900) =     16.301 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.005 ms/op
Iteration   1: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.098 ms/op
                 existUser·p0.999:  5.810 ms/op
                 existUser·p0.9999: 12.133 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   3.933 ms/op
                 existUser·p0.999:  6.244 ms/op
                 existUser·p0.9999: 19.065 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.206 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333799
  mean =      2.875 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47476 
    [ 2.500,  5.000) = 285501 
    [ 5.000,  7.500) = 629 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.472 ms/op
     p(99.9900) =     16.322 ms/op
     p(99.9990) =     20.527 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
Iteration   1: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 18.653 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.737 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 14.771 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.310 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.752 ms/op
                 getUser·p0.9999: 16.985 ms/op
                 getUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321339
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 899 
    [ 1.250,  2.500) = 22923 
    [ 2.500,  3.750) = 283892 
    [ 3.750,  5.000) = 12037 
    [ 5.000,  6.250) = 952 
    [ 6.250,  7.500) = 265 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.911 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.867 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.010 ms/op
Iteration   1: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.638 ms/op
                 listUser·p0.999:  13.662 ms/op
                 listUser·p0.9999: 20.377 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   2: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.611 ms/op
                 listUser·p0.9999: 21.015 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.292 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245424
  mean =      3.913 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3586 
    [ 2.500,  5.000) = 221130 
    [ 5.000,  7.500) = 19632 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.476 ms/op
     p(99.9900) =     20.117 ms/op
     p(99.9990) =     21.466 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.668 ± 2.171  ops/ms
ClientGrpc.existUser                       thrpt       3  11.163 ± 1.311  ops/ms
ClientGrpc.getUser                         thrpt       3  10.543 ± 2.518  ops/ms
ClientGrpc.listUser                        thrpt       3   8.212 ± 1.285  ops/ms
ClientGrpc.createUser                       avgt       3   3.008 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3   2.880 ± 1.587   ms/op
ClientGrpc.getUser                          avgt       3   3.014 ± 0.448   ms/op
ClientGrpc.listUser                         avgt       3   3.886 ± 0.630   ms/op
ClientGrpc.createUser                     sample  317666   3.024 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.344           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.441           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.301           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.186           ms/op
ClientGrpc.existUser                      sample  333799   2.875 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.322           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  321339   2.987 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.310           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.437           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  245424   3.913 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.476           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.117           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.594           ms/op
