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
# Warmup Iteration   1: 3.949 ops/ms
# Warmup Iteration   2: 8.682 ops/ms
# Warmup Iteration   3: 9.678 ops/ms
Iteration   1: 10.022 ops/ms
Iteration   2: 10.172 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.138 ±(99.9%) 1.875 ops/ms [Average]
  (min, avg, max) = (10.022, 10.138, 10.219), stdev = 0.103
  CI (99.9%): [8.262, 12.013] (assumes normal distribution)


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
# Warmup Iteration   1: 7.345 ops/ms
# Warmup Iteration   2: 9.920 ops/ms
# Warmup Iteration   3: 10.384 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.458 ops/ms
Iteration   3: 10.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.498 ±(99.9%) 2.401 ops/ms [Average]
  (min, avg, max) = (10.390, 10.498, 10.645), stdev = 0.132
  CI (99.9%): [8.097, 12.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.452 ops/ms
# Warmup Iteration   2: 9.879 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.013 ops/ms
Iteration   2: 10.065 ops/ms
Iteration   3: 10.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.039 ±(99.9%) 0.468 ops/ms [Average]
  (min, avg, max) = (10.013, 10.039, 10.065), stdev = 0.026
  CI (99.9%): [9.571, 10.507] (assumes normal distribution)


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
# Warmup Iteration   1: 5.719 ops/ms
# Warmup Iteration   2: 7.483 ops/ms
# Warmup Iteration   3: 7.902 ops/ms
Iteration   1: 8.053 ops/ms
Iteration   2: 8.058 ops/ms
Iteration   3: 8.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.048 ±(99.9%) 0.219 ops/ms [Average]
  (min, avg, max) = (8.035, 8.048, 8.058), stdev = 0.012
  CI (99.9%): [7.830, 8.267] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.183 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.161 ±(99.9%) 1.128 ms/op [Average]
  (min, avg, max) = (3.091, 3.161, 3.209), stdev = 0.062
  CI (99.9%): [2.033, 4.289] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.001 ms/op
Iteration   3: 3.100 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.036 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (2.982, 3.036, 3.100), stdev = 0.060
  CI (99.9%): [1.948, 4.125] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.242 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 3.174 ±(99.9%) 0.003 ms/op
Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
Iteration   3: 3.163 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.162 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.150, 3.162, 3.174), stdev = 0.012
  CI (99.9%): [2.940, 3.385] (assumes normal distribution)


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
# Warmup Iteration   1: 5.491 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.039 ms/op
Iteration   1: 3.997 ±(99.9%) 0.025 ms/op
Iteration   2: 3.915 ±(99.9%) 0.010 ms/op
Iteration   3: 3.972 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.915, 3.961, 3.997), stdev = 0.042
  CI (99.9%): [3.190, 4.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.295 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.006 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.687 ms/op
                 createUser·p0.9999: 13.173 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  9.300 ms/op
                 createUser·p0.9999: 14.858 ms/op
                 createUser·p1.00:   15.024 ms/op

Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.764 ms/op
                 createUser·p0.9999: 35.127 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302299
  mean =      3.178 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24278 
    [ 2.500,  5.000) = 276923 
    [ 5.000,  7.500) = 732 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     34.170 ms/op
     p(99.9990) =     36.347 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 4.349 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.006 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.494 ms/op
                 existUser·p0.9999: 14.640 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 18.080 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.580 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311022
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 34868 
    [ 2.500,  3.750) = 244083 
    [ 3.750,  5.000) = 30284 
    [ 5.000,  6.250) = 623 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.979 ms/op
     p(99.9900) =     17.491 ms/op
     p(99.9990) =     18.445 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
Iteration   1: 3.210 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.529 ms/op
                 getUser·p0.999:  8.821 ms/op
                 getUser·p0.9999: 13.108 ms/op
                 getUser·p1.00:   13.402 ms/op

Iteration   2: 3.197 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  6.824 ms/op
                 getUser·p0.9999: 14.893 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.197 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.826 ms/op
                 getUser·p0.9999: 18.055 ms/op
                 getUser·p1.00:   18.252 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299928
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 442 
    [ 1.250,  2.500) = 18958 
    [ 2.500,  3.750) = 234505 
    [ 3.750,  5.000) = 44511 
    [ 5.000,  6.250) = 815 
    [ 6.250,  7.500) = 370 
    [ 7.500,  8.750) = 107 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      7.718 ms/op
     p(99.9900) =     16.401 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 5.710 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  16.995 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   2: 4.011 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.729 ms/op
                 listUser·p0.9999: 20.907 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  16.758 ms/op
                 listUser·p0.9999: 28.705 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237096
  mean =      4.047 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1429 
    [ 2.500,  5.000) = 207332 
    [ 5.000,  7.500) = 27016 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     16.836 ms/op
     p(99.9900) =     27.666 ms/op
     p(99.9990) =     29.041 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.138 ± 1.875  ops/ms
ClientGrpc.existUser                       thrpt       3  10.498 ± 2.401  ops/ms
ClientGrpc.getUser                         thrpt       3  10.039 ± 0.468  ops/ms
ClientGrpc.listUser                        thrpt       3   8.048 ± 0.219  ops/ms
ClientGrpc.createUser                       avgt       3   3.161 ± 1.128   ms/op
ClientGrpc.existUser                        avgt       3   3.036 ± 1.088   ms/op
ClientGrpc.getUser                          avgt       3   3.162 ± 0.222   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.771   ms/op
ClientGrpc.createUser                     sample  302299   3.178 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.746           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.170           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.635           ms/op
ClientGrpc.existUser                      sample  311022   3.085 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.765           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.979           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.491           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  299928   3.201 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.718           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.401           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  237096   4.047 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.836           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.666           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.164           ms/op
