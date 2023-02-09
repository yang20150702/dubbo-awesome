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
# Warmup Iteration   1: 4.276 ops/ms
# Warmup Iteration   2: 9.240 ops/ms
# Warmup Iteration   3: 9.792 ops/ms
Iteration   1: 10.303 ops/ms
Iteration   2: 10.112 ops/ms
Iteration   3: 10.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.182 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (10.112, 10.182, 10.303), stdev = 0.106
  CI (99.9%): [8.250, 12.114] (assumes normal distribution)


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
# Warmup Iteration   1: 7.572 ops/ms
# Warmup Iteration   2: 10.238 ops/ms
# Warmup Iteration   3: 10.286 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.516 ops/ms
Iteration   3: 10.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.447 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (10.348, 10.447, 10.516), stdev = 0.088
  CI (99.9%): [8.849, 12.046] (assumes normal distribution)


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
# Warmup Iteration   1: 6.551 ops/ms
# Warmup Iteration   2: 10.032 ops/ms
# Warmup Iteration   3: 10.040 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 10.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.152 ±(99.9%) 4.835 ops/ms [Average]
  (min, avg, max) = (9.945, 10.152, 10.450), stdev = 0.265
  CI (99.9%): [5.317, 14.987] (assumes normal distribution)


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
# Warmup Iteration   1: 5.680 ops/ms
# Warmup Iteration   2: 7.436 ops/ms
# Warmup Iteration   3: 7.791 ops/ms
Iteration   1: 7.852 ops/ms
Iteration   2: 8.297 ops/ms
Iteration   3: 7.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.045 ±(99.9%) 4.168 ops/ms [Average]
  (min, avg, max) = (7.852, 8.045, 8.297), stdev = 0.228
  CI (99.9%): [3.877, 12.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.003 ms/op
Iteration   1: 3.241 ±(99.9%) 0.005 ms/op
Iteration   2: 3.240 ±(99.9%) 0.002 ms/op
Iteration   3: 3.243 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.241 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (3.240, 3.241, 3.243), stdev = 0.002
  CI (99.9%): [3.207, 3.276] (assumes normal distribution)


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
# Warmup Iteration   1: 4.143 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.002 ms/op
Iteration   1: 3.000 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.039 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.000, 3.039, 3.082), stdev = 0.042
  CI (99.9%): [2.279, 3.798] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.003 ms/op
Iteration   1: 3.289 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.256 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.250 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.206, 3.250, 3.289), stdev = 0.042
  CI (99.9%): [2.484, 4.017] (assumes normal distribution)


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
# Warmup Iteration   1: 5.225 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.017 ms/op
Iteration   1: 4.061 ±(99.9%) 0.006 ms/op
Iteration   2: 4.010 ±(99.9%) 0.007 ms/op
Iteration   3: 4.092 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.054 ±(99.9%) 0.751 ms/op [Average]
  (min, avg, max) = (4.010, 4.054, 4.092), stdev = 0.041
  CI (99.9%): [3.304, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.698 ms/op
                 createUser·p0.9999: 12.891 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   2: 3.294 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  9.006 ms/op
                 createUser·p0.9999: 18.336 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.490 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295992
  mean =      3.242 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19830 
    [ 2.500,  5.000) = 274889 
    [ 5.000,  7.500) = 783 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     22.623 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.175 ms/op
                 existUser·p0.9999: 12.706 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   2: 2.990 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.782 ms/op
                 existUser·p0.9999: 16.440 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.027 ms/op
                 existUser·p0.9999: 16.429 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314541
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1683 
    [ 1.250,  2.500) = 42529 
    [ 2.500,  3.750) = 232916 
    [ 3.750,  5.000) = 36672 
    [ 5.000,  6.250) = 416 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.295 ms/op
     p(99.9900) =     16.132 ms/op
     p(99.9990) =     17.095 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.007 ms/op
Iteration   1: 3.213 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.226 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.324 ms/op
                 getUser·p0.9999: 21.302 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300333
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24025 
    [ 2.500,  5.000) = 275227 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.832 ms/op
     p(99.9900) =     19.560 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 5.868 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.011 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  13.344 ms/op
                 listUser·p0.9999: 17.464 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   2: 4.079 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.962 ms/op
                 listUser·p0.9999: 28.388 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   3: 4.102 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  17.268 ms/op
                 listUser·p0.9999: 27.204 ms/op
                 listUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236889
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1477 
    [ 2.500,  5.000) = 208112 
    [ 5.000,  7.500) = 25992 
    [ 7.500, 10.000) = 836 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     15.108 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.628 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.182 ± 1.932  ops/ms
ClientGrpc.existUser                       thrpt       3  10.447 ± 1.599  ops/ms
ClientGrpc.getUser                         thrpt       3  10.152 ± 4.835  ops/ms
ClientGrpc.listUser                        thrpt       3   8.045 ± 4.168  ops/ms
ClientGrpc.createUser                       avgt       3   3.241 ± 0.035   ms/op
ClientGrpc.existUser                        avgt       3   3.039 ± 0.759   ms/op
ClientGrpc.getUser                          avgt       3   3.250 ± 0.767   ms/op
ClientGrpc.listUser                         avgt       3   4.054 ± 0.751   ms/op
ClientGrpc.createUser                     sample  295992   3.242 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.771           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.215           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.623           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.314           ms/op
ClientGrpc.existUser                      sample  314541   3.052 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.731           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.295           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.132           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  300333   3.195 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.778           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.832           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.560           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.791           ms/op
ClientGrpc.listUser                       sample  236889   4.050 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.081           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.108           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.460           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.474           ms/op
