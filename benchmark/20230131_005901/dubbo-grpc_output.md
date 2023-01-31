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
# Warmup Iteration   1: 4.759 ops/ms
# Warmup Iteration   2: 9.014 ops/ms
# Warmup Iteration   3: 10.299 ops/ms
Iteration   1: 10.675 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.331 ±(99.9%) 5.451 ops/ms [Average]
  (min, avg, max) = (10.140, 10.331, 10.675), stdev = 0.299
  CI (99.9%): [4.880, 15.781] (assumes normal distribution)


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
# Warmup Iteration   1: 8.034 ops/ms
# Warmup Iteration   2: 10.696 ops/ms
# Warmup Iteration   3: 10.591 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 3.734 ops/ms [Average]
  (min, avg, max) = (10.812, 10.976, 11.205), stdev = 0.205
  CI (99.9%): [7.241, 14.710] (assumes normal distribution)


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
# Warmup Iteration   1: 8.151 ops/ms
# Warmup Iteration   2: 10.428 ops/ms
# Warmup Iteration   3: 10.420 ops/ms
Iteration   1: 10.116 ops/ms
Iteration   2: 10.381 ops/ms
Iteration   3: 10.313 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.270 ±(99.9%) 2.506 ops/ms [Average]
  (min, avg, max) = (10.116, 10.270, 10.381), stdev = 0.137
  CI (99.9%): [7.764, 12.776] (assumes normal distribution)


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
# Warmup Iteration   1: 5.933 ops/ms
# Warmup Iteration   2: 7.672 ops/ms
# Warmup Iteration   3: 7.764 ops/ms
Iteration   1: 7.836 ops/ms
Iteration   2: 7.850 ops/ms
Iteration   3: 7.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.800 ±(99.9%) 1.348 ops/ms [Average]
  (min, avg, max) = (7.715, 7.800, 7.850), stdev = 0.074
  CI (99.9%): [6.452, 9.149] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.177 ±(99.9%) 0.001 ms/op
Iteration   2: 3.113 ±(99.9%) 0.002 ms/op
Iteration   3: 3.198 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.163 ±(99.9%) 0.812 ms/op [Average]
  (min, avg, max) = (3.113, 3.163, 3.198), stdev = 0.045
  CI (99.9%): [2.350, 3.975] (assumes normal distribution)


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
# Warmup Iteration   1: 3.786 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.002 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.998 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (2.983, 2.998, 3.028), stdev = 0.026
  CI (99.9%): [2.526, 3.471] (assumes normal distribution)


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.058 ±(99.9%) 0.502 ms/op [Average]
  (min, avg, max) = (3.026, 3.058, 3.079), stdev = 0.028
  CI (99.9%): [2.555, 3.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.166 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.007 ms/op
Iteration   1: 4.010 ±(99.9%) 0.010 ms/op
Iteration   2: 4.134 ±(99.9%) 0.063 ms/op
Iteration   3: 4.010 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.052 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (4.010, 4.052, 4.134), stdev = 0.072
  CI (99.9%): [2.745, 5.358] (assumes normal distribution)


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.338 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.572 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.971 ms/op
                 createUser·p0.9999: 22.853 ms/op
                 createUser·p1.00:   23.069 ms/op

Iteration   2: 3.134 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.297 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  8.315 ms/op
                 createUser·p0.9999: 16.102 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.201 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.223 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 19.132 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307786
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19789 
    [ 2.500,  5.000) = 287136 
    [ 5.000,  7.500) = 456 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.223 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.723 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.001 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 11.359 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.723 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.603 ms/op
                 existUser·p0.9999: 12.777 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.903 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.356 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322912
  mean =      2.971 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4377 
    [ 1.250,  2.500) = 39918 
    [ 2.500,  3.750) = 258719 
    [ 3.750,  5.000) = 19044 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      6.292 ms/op
     p(99.9900) =     15.157 ms/op
     p(99.9990) =     17.803 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.668 ms/op
                 getUser·p0.9999: 11.248 ms/op
                 getUser·p1.00:   11.567 ms/op

Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  7.831 ms/op
                 getUser·p0.9999: 12.822 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.785 ms/op
                 getUser·p0.9999: 14.088 ms/op
                 getUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314855
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1880 
    [ 1.250,  2.500) = 24768 
    [ 2.500,  3.750) = 266744 
    [ 3.750,  5.000) = 20339 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     13.363 ms/op
     p(99.9990) =     14.441 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.937 ms/op
                 listUser·p0.9999: 16.354 ms/op
                 listUser·p1.00:   16.761 ms/op

Iteration   2: 3.977 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.586 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.449 ms/op
                 listUser·p0.9999: 22.969 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.615 ms/op
                 listUser·p0.99:   6.916 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 20.255 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239317
  mean =      4.014 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2364 
    [ 2.500,  5.000) = 212087 
    [ 5.000,  7.500) = 23461 
    [ 7.500, 10.000) = 868 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.609 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.416 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.331 ± 5.451  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 3.734  ops/ms
ClientGrpc.getUser                         thrpt       3  10.270 ± 2.506  ops/ms
ClientGrpc.listUser                        thrpt       3   7.800 ± 1.348  ops/ms
ClientGrpc.createUser                       avgt       3   3.163 ± 0.812   ms/op
ClientGrpc.existUser                        avgt       3   2.998 ± 0.473   ms/op
ClientGrpc.getUser                          avgt       3   3.058 ± 0.502   ms/op
ClientGrpc.listUser                         avgt       3   4.052 ± 1.307   ms/op
ClientGrpc.createUser                     sample  307786   3.118 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.223           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.723           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.381           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.069           ms/op
ClientGrpc.existUser                      sample  322912   2.971 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.521           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.292           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.157           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.186           ms/op
ClientGrpc.getUser                        sample  314855   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.615           ms/op
ClientGrpc.listUser                       sample  239317   4.014 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.586           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.609           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
