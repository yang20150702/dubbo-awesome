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
# Warmup Iteration   1: 4.846 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 10.254 ops/ms
Iteration   1: 9.771 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.083 ±(99.9%) 5.463 ops/ms [Average]
  (min, avg, max) = (9.771, 10.083, 10.368), stdev = 0.299
  CI (99.9%): [4.620, 15.547] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.877 ops/ms
# Warmup Iteration   2: 10.784 ops/ms
# Warmup Iteration   3: 11.184 ops/ms
Iteration   1: 11.156 ops/ms
Iteration   2: 11.277 ops/ms
Iteration   3: 11.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.162 ±(99.9%) 2.057 ops/ms [Average]
  (min, avg, max) = (11.052, 11.162, 11.277), stdev = 0.113
  CI (99.9%): [9.105, 13.218] (assumes normal distribution)


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
# Warmup Iteration   1: 7.025 ops/ms
# Warmup Iteration   2: 9.980 ops/ms
# Warmup Iteration   3: 10.034 ops/ms
Iteration   1: 10.251 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 10.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.196 ±(99.9%) 3.819 ops/ms [Average]
  (min, avg, max) = (9.965, 10.196, 10.372), stdev = 0.209
  CI (99.9%): [6.376, 14.015] (assumes normal distribution)


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
# Warmup Iteration   1: 5.548 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 7.817 ops/ms
Iteration   2: 7.881 ops/ms
Iteration   3: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.901 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (7.817, 7.901, 8.006), stdev = 0.096
  CI (99.9%): [6.149, 9.654] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.025 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 3.241 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.002 ms/op
Iteration   3: 3.165 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.195 ±(99.9%) 0.731 ms/op [Average]
  (min, avg, max) = (3.165, 3.195, 3.241), stdev = 0.040
  CI (99.9%): [2.464, 3.927] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.003 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 2.938 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.955 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.938, 2.955, 2.980), stdev = 0.022
  CI (99.9%): [2.547, 3.363] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (2.990, 3.074, 3.199), stdev = 0.111
  CI (99.9%): [1.053, 5.095] (assumes normal distribution)


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.018 ms/op
Iteration   1: 4.085 ±(99.9%) 0.021 ms/op
Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
Iteration   3: 4.236 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.152 ±(99.9%) 1.404 ms/op [Average]
  (min, avg, max) = (4.085, 4.152, 4.236), stdev = 0.077
  CI (99.9%): [2.748, 5.557] (assumes normal distribution)


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
# Warmup Iteration   1: 3.972 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.197 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.511 ms/op
                 createUser·p0.9999: 12.484 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   2: 3.184 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.806 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  8.082 ms/op
                 createUser·p0.9999: 14.598 ms/op
                 createUser·p1.00:   14.975 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 15.597 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300762
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 736 
    [ 1.250,  2.500) = 17785 
    [ 2.500,  3.750) = 240008 
    [ 3.750,  5.000) = 40899 
    [ 5.000,  6.250) = 521 
    [ 6.250,  7.500) = 397 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     10.391 ms/op
     p(99.9900) =     15.270 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.050 ms/op
                 existUser·p0.9999: 16.102 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  10.524 ms/op
                 existUser·p0.9999: 17.549 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317433
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2982 
    [ 1.250,  2.500) = 36069 
    [ 2.500,  3.750) = 250005 
    [ 3.750,  5.000) = 27236 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 256 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.423 ms/op
     p(99.9900) =     16.339 ms/op
     p(99.9990) =     17.951 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.685 ms/op
                 getUser·p0.9999: 11.707 ms/op
                 getUser·p1.00:   14.041 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.222 ms/op
                 getUser·p0.9999: 24.824 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.526 ms/op
                 getUser·p0.9999: 28.599 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311044
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27696 
    [ 2.500,  5.000) = 282121 
    [ 5.000,  7.500) = 938 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     26.408 ms/op
     p(99.9990) =     28.927 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.898 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.959 ms/op
                 listUser·p0.9999: 15.630 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   2: 3.995 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.893 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   3: 3.924 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  17.645 ms/op
                 listUser·p0.9999: 21.687 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243547
  mean =      3.939 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5039 
    [ 2.500,  5.000) = 211830 
    [ 5.000,  7.500) = 25574 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.983 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.936 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.083 ± 5.463  ops/ms
ClientGrpc.existUser                       thrpt       3  11.162 ± 2.057  ops/ms
ClientGrpc.getUser                         thrpt       3  10.196 ± 3.819  ops/ms
ClientGrpc.listUser                        thrpt       3   7.901 ± 1.753  ops/ms
ClientGrpc.createUser                       avgt       3   3.195 ± 0.731   ms/op
ClientGrpc.existUser                        avgt       3   2.955 ± 0.408   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 2.021   ms/op
ClientGrpc.listUser                         avgt       3   4.152 ± 1.404   ms/op
ClientGrpc.createUser                     sample  300762   3.192 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.468           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.391           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.391           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.270           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.089           ms/op
ClientGrpc.existUser                      sample  317433   3.024 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.601           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.423           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.339           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.055           ms/op
ClientGrpc.getUser                        sample  311044   3.084 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.620           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.299           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.408           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.065           ms/op
ClientGrpc.listUser                       sample  243547   3.939 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.979           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.983           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.496           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.757           ms/op
