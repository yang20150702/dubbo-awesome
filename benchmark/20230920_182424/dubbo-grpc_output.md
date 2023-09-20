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
# Warmup Iteration   1: 3.579 ops/ms
# Warmup Iteration   2: 8.217 ops/ms
# Warmup Iteration   3: 9.185 ops/ms
Iteration   1: 9.281 ops/ms
Iteration   2: 9.487 ops/ms
Iteration   3: 9.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.392 ±(99.9%) 1.898 ops/ms [Average]
  (min, avg, max) = (9.281, 9.392, 9.487), stdev = 0.104
  CI (99.9%): [7.494, 11.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.640 ops/ms
# Warmup Iteration   2: 9.526 ops/ms
# Warmup Iteration   3: 9.992 ops/ms
Iteration   1: 9.987 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 10.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.112 ±(99.9%) 2.015 ops/ms [Average]
  (min, avg, max) = (9.987, 10.112, 10.197), stdev = 0.110
  CI (99.9%): [8.096, 12.127] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.860 ops/ms
# Warmup Iteration   2: 9.498 ops/ms
# Warmup Iteration   3: 9.642 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.717 ops/ms
Iteration   3: 9.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.692 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (9.639, 9.692, 9.720), stdev = 0.046
  CI (99.9%): [8.852, 10.531] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.034 ops/ms
# Warmup Iteration   2: 7.066 ops/ms
# Warmup Iteration   3: 7.560 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 7.598 ops/ms
Iteration   3: 7.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.655 ±(99.9%) 1.349 ops/ms [Average]
  (min, avg, max) = (7.598, 7.655, 7.738), stdev = 0.074
  CI (99.9%): [6.305, 9.004] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.094 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.456 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.002 ms/op
Iteration   1: 3.303 ±(99.9%) 0.003 ms/op
Iteration   2: 3.380 ±(99.9%) 0.002 ms/op
Iteration   3: 3.343 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.342 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.303, 3.342, 3.380), stdev = 0.038
  CI (99.9%): [2.643, 4.041] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.380 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.001 ms/op
Iteration   1: 3.243 ±(99.9%) 0.003 ms/op
Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.201 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.173, 3.201, 3.243), stdev = 0.037
  CI (99.9%): [2.517, 3.885] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.003 ms/op
Iteration   1: 3.235 ±(99.9%) 0.002 ms/op
Iteration   2: 3.253 ±(99.9%) 0.003 ms/op
Iteration   3: 3.348 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.279 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.235, 3.279, 3.348), stdev = 0.061
  CI (99.9%): [2.174, 4.384] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.573 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.010 ms/op
Iteration   1: 4.085 ±(99.9%) 0.020 ms/op
Iteration   2: 4.070 ±(99.9%) 0.029 ms/op
Iteration   3: 4.137 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.097 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (4.070, 4.097, 4.137), stdev = 0.035
  CI (99.9%): [3.461, 4.733] (assumes normal distribution)


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.513 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.006 ms/op
Iteration   1: 3.411 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  8.287 ms/op
                 createUser·p0.9999: 21.778 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   2: 3.349 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.898 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.208 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  7.824 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 3.384 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  14.763 ms/op
                 createUser·p0.9999: 23.732 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284065
  mean =      3.381 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3825 
    [ 2.500,  5.000) = 278217 
    [ 5.000,  7.500) = 1511 
    [ 7.500, 10.000) = 268 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      9.273 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.207 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.005 ms/op
Iteration   1: 3.183 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  9.010 ms/op
                 existUser·p0.9999: 13.072 ms/op
                 existUser·p1.00:   13.533 ms/op

Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.138 ms/op
                 existUser·p0.9999: 15.478 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   3: 3.203 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.805 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.971 ms/op
                 existUser·p0.9999: 18.088 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303360
  mean =      3.164 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 385 
    [ 1.250,  2.500) = 8692 
    [ 2.500,  3.750) = 265001 
    [ 3.750,  5.000) = 27440 
    [ 5.000,  6.250) = 1062 
    [ 6.250,  7.500) = 429 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.867 ms/op
     p(99.9900) =     16.094 ms/op
     p(99.9990) =     18.643 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.007 ms/op
Iteration   1: 3.341 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.973 ms/op
                 getUser·p0.999:  9.792 ms/op
                 getUser·p0.9999: 14.013 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 3.383 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  10.158 ms/op
                 getUser·p0.9999: 14.696 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 3.275 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.637 ms/op
                 getUser·p0.9999: 16.060 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 287889
  mean =      3.333 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 6322 
    [ 2.500,  3.750) = 231676 
    [ 3.750,  5.000) = 47525 
    [ 5.000,  6.250) = 1126 
    [ 6.250,  7.500) = 384 
    [ 7.500,  8.750) = 213 
    [ 8.750, 10.000) = 159 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 67 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      9.308 ms/op
     p(99.9900) =     15.306 ms/op
     p(99.9990) =     16.580 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.241 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.146 ±(99.9%) 0.011 ms/op
Iteration   1: 4.105 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 16.280 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 4.102 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.044 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.747 ms/op
                 listUser·p0.9999: 16.519 ms/op
                 listUser·p1.00:   17.039 ms/op

Iteration   3: 4.109 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233785
  mean =      4.105 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1411 
    [ 2.500,  5.000) = 214999 
    [ 5.000,  7.500) = 15834 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     14.471 ms/op
     p(99.9900) =     18.870 ms/op
     p(99.9990) =     20.163 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.392 ± 1.898  ops/ms
ClientGrpc.existUser                       thrpt       3  10.112 ± 2.015  ops/ms
ClientGrpc.getUser                         thrpt       3   9.692 ± 0.839  ops/ms
ClientGrpc.listUser                        thrpt       3   7.655 ± 1.349  ops/ms
ClientGrpc.createUser                       avgt       3   3.342 ± 0.699   ms/op
ClientGrpc.existUser                        avgt       3   3.201 ± 0.684   ms/op
ClientGrpc.getUser                          avgt       3   3.279 ± 1.105   ms/op
ClientGrpc.listUser                         avgt       3   4.097 ± 0.636   ms/op
ClientGrpc.createUser                     sample  284065   3.381 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.898           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.330           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.710           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.273           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.053           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  303360   3.164 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.679           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.109           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.944           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.867           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.094           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  287889   3.333 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.546           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.277           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.965           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.308           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.306           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.236           ms/op
ClientGrpc.listUser                       sample  233785   4.105 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.184           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.994           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.471           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.870           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.251           ms/op
