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
# Warmup Iteration   1: 4.173 ops/ms
# Warmup Iteration   2: 9.187 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 10.322 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.230 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (10.031, 10.230, 10.338), stdev = 0.173
  CI (99.9%): [7.073, 13.388] (assumes normal distribution)


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
# Warmup Iteration   1: 7.388 ops/ms
# Warmup Iteration   2: 10.205 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.541 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.586 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (10.541, 10.586, 10.617), stdev = 0.040
  CI (99.9%): [9.849, 11.324] (assumes normal distribution)


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
# Warmup Iteration   1: 6.941 ops/ms
# Warmup Iteration   2: 9.616 ops/ms
# Warmup Iteration   3: 9.837 ops/ms
Iteration   1: 9.943 ops/ms
Iteration   2: 10.055 ops/ms
Iteration   3: 10.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.010 ±(99.9%) 1.084 ops/ms [Average]
  (min, avg, max) = (9.943, 10.010, 10.055), stdev = 0.059
  CI (99.9%): [8.926, 11.094] (assumes normal distribution)


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
# Warmup Iteration   1: 5.104 ops/ms
# Warmup Iteration   2: 7.826 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 8.033 ops/ms
Iteration   2: 8.053 ops/ms
Iteration   3: 8.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.053 ±(99.9%) 0.367 ops/ms [Average]
  (min, avg, max) = (8.033, 8.053, 8.073), stdev = 0.020
  CI (99.9%): [7.686, 8.419] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.002 ms/op
Iteration   1: 3.186 ±(99.9%) 0.010 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.217 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (3.125, 3.176, 3.217), stdev = 0.047
  CI (99.9%): [2.318, 4.034] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 3.051 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (2.984, 3.011, 3.051), stdev = 0.035
  CI (99.9%): [2.375, 3.648] (assumes normal distribution)


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
# Warmup Iteration   1: 4.192 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.004 ms/op
Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.155 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.134, 3.155, 3.172), stdev = 0.019
  CI (99.9%): [2.808, 3.502] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.017 ms/op
Iteration   1: 4.045 ±(99.9%) 0.005 ms/op
Iteration   2: 3.942 ±(99.9%) 0.012 ms/op
Iteration   3: 3.974 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.987 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.942, 3.987, 4.045), stdev = 0.052
  CI (99.9%): [3.030, 4.944] (assumes normal distribution)


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.271 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.520 ms/op
                 createUser·p0.9999: 13.017 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   2: 3.243 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  9.581 ms/op
                 createUser·p0.9999: 14.652 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  10.025 ms/op
                 createUser·p0.9999: 26.221 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301771
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24133 
    [ 2.500,  5.000) = 276454 
    [ 5.000,  7.500) = 743 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      9.064 ms/op
     p(99.9900) =     24.880 ms/op
     p(99.9990) =     26.443 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.887 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 11.809 ms/op
                 existUser·p1.00:   12.026 ms/op

Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.744 ms/op
                 existUser·p0.9999: 22.364 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.024 ms/op
                 existUser·p0.9999: 15.974 ms/op
                 existUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317874
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41295 
    [ 2.500,  5.000) = 275735 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.768 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.006 ms/op
Iteration   1: 3.194 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.956 ms/op
                 getUser·p0.9999: 13.516 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.028 ms/op
                 getUser·p0.9999: 15.219 ms/op
                 getUser·p1.00:   15.548 ms/op

Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.110 ms/op
                 getUser·p0.9999: 17.529 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299858
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 423 
    [ 1.250,  2.500) = 20152 
    [ 2.500,  3.750) = 232134 
    [ 3.750,  5.000) = 46086 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 305 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.620 ms/op
     p(99.9900) =     16.400 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 5.445 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
Iteration   1: 4.045 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.629 ms/op
                 listUser·p0.9999: 19.274 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.890 ms/op
                 listUser·p0.999:  14.469 ms/op
                 listUser·p0.9999: 19.167 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   3: 3.885 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.736 ms/op
                 listUser·p0.999:  17.155 ms/op
                 listUser·p0.9999: 30.376 ms/op
                 listUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241821
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3518 
    [ 2.500,  5.000) = 213250 
    [ 5.000,  7.500) = 23888 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     14.541 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.230 ± 3.157  ops/ms
ClientGrpc.existUser                       thrpt       3  10.586 ± 0.738  ops/ms
ClientGrpc.getUser                         thrpt       3  10.010 ± 1.084  ops/ms
ClientGrpc.listUser                        thrpt       3   8.053 ± 0.367  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.858   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.637   ms/op
ClientGrpc.getUser                          avgt       3   3.155 ± 0.347   ms/op
ClientGrpc.listUser                         avgt       3   3.987 ± 0.957   ms/op
ClientGrpc.createUser                     sample  301771   3.182 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.696           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.064           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.880           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  317874   3.022 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.905           ms/op
ClientGrpc.getUser                        sample  299858   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.440           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.170           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.096           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.620           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.400           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  241821   3.969 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.541           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.671           ms/op
