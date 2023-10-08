# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ops/ms
# Warmup Iteration   2: 8.687 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.318 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.168 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (10.054, 10.168, 10.318), stdev = 0.136
  CI (99.9%): [7.684, 12.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.251 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.836 ops/ms
Iteration   2: 11.112 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.841 ±(99.9%) 4.881 ops/ms [Average]
  (min, avg, max) = (10.577, 10.841, 11.112), stdev = 0.268
  CI (99.9%): [5.961, 15.722] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.864 ops/ms
# Warmup Iteration   2: 9.947 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.294 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.448 ±(99.9%) 2.992 ops/ms [Average]
  (min, avg, max) = (10.294, 10.448, 10.620), stdev = 0.164
  CI (99.9%): [7.456, 13.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.063 ops/ms
# Warmup Iteration   2: 7.866 ops/ms
# Warmup Iteration   3: 7.994 ops/ms
Iteration   1: 8.096 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.096 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (8.036, 8.096, 8.156), stdev = 0.060
  CI (99.9%): [7.004, 9.188] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.283 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.005 ms/op
Iteration   1: 3.082 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.074, 3.094, 3.128), stdev = 0.030
  CI (99.9%): [2.556, 3.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.001 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.998 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (2.971, 2.998, 3.019), stdev = 0.024
  CI (99.9%): [2.556, 3.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.325 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.002 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.036 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (3.036, 3.081, 3.109), stdev = 0.039
  CI (99.9%): [2.366, 3.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.500 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.030 ms/op
Iteration   1: 3.957 ±(99.9%) 0.044 ms/op
Iteration   2: 3.831 ±(99.9%) 0.023 ms/op
Iteration   3: 3.923 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.904 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.831, 3.904, 3.957), stdev = 0.065
  CI (99.9%): [2.716, 5.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.363 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.008 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.916 ms/op
                 createUser·p0.9999: 19.488 ms/op
                 createUser·p1.00:   19.956 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.753 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  9.739 ms/op
                 createUser·p0.9999: 21.917 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.370 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 26.352 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308251
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12754 
    [ 2.500,  5.000) = 293867 
    [ 5.000,  7.500) = 1211 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     24.477 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.625 ms/op
                 existUser·p0.9999: 12.965 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.885 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.898 ms/op
                 existUser·p0.9999: 21.424 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.143 ms/op
                 existUser·p0.9999: 17.080 ms/op
                 existUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325210
  mean =      2.951 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29091 
    [ 2.500,  5.000) = 294965 
    [ 5.000,  7.500) = 894 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.116 ms/op
     p(99.9000) =      7.174 ms/op
     p(99.9900) =     19.584 ms/op
     p(99.9990) =     21.782 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.139 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.225 ms/op
                 getUser·p0.999:  8.575 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 18.658 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.889 ms/op
                 getUser·p0.9999: 19.276 ms/op
                 getUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307778
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12541 
    [ 2.500,  5.000) = 292889 
    [ 5.000,  7.500) = 1992 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     21.095 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.010 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.833 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 26.729 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   2: 3.952 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.360 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.763 ms/op
                 listUser·p0.999:  14.486 ms/op
                 listUser·p0.9999: 15.678 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.173 ms/op
                 listUser·p0.9999: 19.105 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241080
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2353 
    [ 2.500,  5.000) = 222727 
    [ 5.000,  7.500) = 14772 
    [ 7.500, 10.000) = 755 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     19.029 ms/op
     p(99.9990) =     27.751 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.168 ± 2.484  ops/ms
ClientGrpc.existUser                       thrpt       3  10.841 ± 4.881  ops/ms
ClientGrpc.getUser                         thrpt       3  10.448 ± 2.992  ops/ms
ClientGrpc.listUser                        thrpt       3   8.096 ± 1.092  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.539   ms/op
ClientGrpc.existUser                        avgt       3   2.998 ± 0.442   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.715   ms/op
ClientGrpc.listUser                         avgt       3   3.904 ± 1.188   ms/op
ClientGrpc.createUser                     sample  308251   3.112 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.649           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.469           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.477           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  325210   2.951 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.174           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.584           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  307778   3.118 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.690           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.840           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.266           ms/op
ClientGrpc.listUser                       sample  241080   3.981 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.360           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.497           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.029           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
