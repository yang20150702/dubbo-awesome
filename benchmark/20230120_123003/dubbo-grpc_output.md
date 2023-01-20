# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.320 ops/ms
# Warmup Iteration   2: 9.198 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.204 ops/ms
Iteration   2: 9.921 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.108 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (9.921, 10.108, 10.204), stdev = 0.161
  CI (99.9%): [7.165, 13.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.074 ops/ms
# Warmup Iteration   2: 10.130 ops/ms
# Warmup Iteration   3: 10.403 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.334 ops/ms
Iteration   3: 10.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.576 ±(99.9%) 3.820 ops/ms [Average]
  (min, avg, max) = (10.334, 10.576, 10.701), stdev = 0.209
  CI (99.9%): [6.756, 14.396] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.027 ops/ms
# Warmup Iteration   2: 9.810 ops/ms
# Warmup Iteration   3: 9.976 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 9.987 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.092 ±(99.9%) 4.283 ops/ms [Average]
  (min, avg, max) = (9.927, 10.092, 10.360), stdev = 0.235
  CI (99.9%): [5.809, 14.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.300 ops/ms
# Warmup Iteration   2: 7.782 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 7.799 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.909 ±(99.9%) 2.070 ops/ms [Average]
  (min, avg, max) = (7.799, 7.909, 8.026), stdev = 0.113
  CI (99.9%): [5.839, 9.979] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.003 ms/op
Iteration   1: 3.230 ±(99.9%) 0.001 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.207 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.200 ±(99.9%) 0.644 ms/op [Average]
  (min, avg, max) = (3.161, 3.200, 3.230), stdev = 0.035
  CI (99.9%): [2.556, 3.844] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.002 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.045 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.019, 3.045, 3.077), stdev = 0.029
  CI (99.9%): [2.510, 3.580] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.244 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.004 ms/op
Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
Iteration   3: 3.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.145 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (3.111, 3.145, 3.204), stdev = 0.052
  CI (99.9%): [2.198, 4.091] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.010 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
Iteration   1: 3.883 ±(99.9%) 0.004 ms/op
Iteration   2: 3.971 ±(99.9%) 0.006 ms/op
Iteration   3: 4.095 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 1.943 ms/op [Average]
  (min, avg, max) = (3.883, 3.983, 4.095), stdev = 0.107
  CI (99.9%): [2.040, 5.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.783 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.901 ms/op
                 createUser·p0.9999: 16.186 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.966 ms/op
                 createUser·p0.9999: 15.060 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.165 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.628 ms/op
                 createUser·p0.9999: 29.619 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300825
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23881 
    [ 2.500,  5.000) = 275712 
    [ 5.000,  7.500) = 888 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.867 ms/op
     p(99.9900) =     29.030 ms/op
     p(99.9990) =     30.113 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.149 ms/op
                 existUser·p0.9999: 14.108 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  5.731 ms/op
                 existUser·p0.9999: 19.405 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  6.412 ms/op
                 existUser·p0.9999: 17.498 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314188
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 667 
    [ 1.250,  2.500) = 38302 
    [ 2.500,  3.750) = 247533 
    [ 3.750,  5.000) = 27003 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.185 ms/op
     p(99.9900) =     17.831 ms/op
     p(99.9990) =     19.778 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.321 ms/op
                 getUser·p0.999:  6.701 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 15.975 ms/op
                 getUser·p1.00:   16.482 ms/op

Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.842 ms/op
                 getUser·p0.9999: 16.342 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304945
  mean =      3.146 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 20920 
    [ 2.500,  3.750) = 247378 
    [ 3.750,  5.000) = 35308 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 216 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     18.187 ms/op
     p(99.9990) =     19.459 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.751 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.011 ms/op
Iteration   1: 3.965 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 17.854 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  13.468 ms/op
                 listUser·p0.9999: 23.868 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  15.714 ms/op
                 listUser·p0.9999: 26.180 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239675
  mean =      4.004 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1532 
    [ 2.500,  5.000) = 212731 
    [ 5.000,  7.500) = 24339 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     13.670 ms/op
     p(99.9900) =     24.806 ms/op
     p(99.9990) =     26.464 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.108 ± 2.943  ops/ms
ClientGrpc.existUser                       thrpt       3  10.576 ± 3.820  ops/ms
ClientGrpc.getUser                         thrpt       3  10.092 ± 4.283  ops/ms
ClientGrpc.listUser                        thrpt       3   7.909 ± 2.070  ops/ms
ClientGrpc.createUser                       avgt       3   3.200 ± 0.644   ms/op
ClientGrpc.existUser                        avgt       3   3.045 ± 0.535   ms/op
ClientGrpc.getUser                          avgt       3   3.145 ± 0.946   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 1.943   ms/op
ClientGrpc.createUser                     sample  300825   3.188 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.162           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.867           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.030           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.179           ms/op
ClientGrpc.existUser                      sample  314188   3.056 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.778           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.185           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.831           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.923           ms/op
ClientGrpc.getUser                        sample  304945   3.146 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.720           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.117           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.187           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  239675   4.004 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.055           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.670           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.806           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
