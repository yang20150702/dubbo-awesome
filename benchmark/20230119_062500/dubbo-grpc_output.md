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
# Warmup Iteration   1: 4.092 ops/ms
# Warmup Iteration   2: 9.023 ops/ms
# Warmup Iteration   3: 9.758 ops/ms
Iteration   1: 10.016 ops/ms
Iteration   2: 10.170 ops/ms
Iteration   3: 10.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.103 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (10.016, 10.103, 10.170), stdev = 0.079
  CI (99.9%): [8.655, 11.552] (assumes normal distribution)


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
# Warmup Iteration   1: 7.380 ops/ms
# Warmup Iteration   2: 9.959 ops/ms
# Warmup Iteration   3: 10.699 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.519 ±(99.9%) 2.729 ops/ms [Average]
  (min, avg, max) = (10.368, 10.519, 10.667), stdev = 0.150
  CI (99.9%): [7.790, 13.249] (assumes normal distribution)


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
# Warmup Iteration   1: 6.344 ops/ms
# Warmup Iteration   2: 9.874 ops/ms
# Warmup Iteration   3: 9.870 ops/ms
Iteration   1: 9.944 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 10.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.085 ±(99.9%) 2.237 ops/ms [Average]
  (min, avg, max) = (9.944, 10.085, 10.164), stdev = 0.123
  CI (99.9%): [7.848, 12.322] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.410 ops/ms
# Warmup Iteration   2: 7.499 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.734 ops/ms
Iteration   3: 7.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.787 ±(99.9%) 1.533 ops/ms [Average]
  (min, avg, max) = (7.734, 7.787, 7.884), stdev = 0.084
  CI (99.9%): [6.253, 9.320] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.004 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
Iteration   3: 3.200 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.185 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.158, 3.185, 3.200), stdev = 0.023
  CI (99.9%): [2.762, 3.608] (assumes normal distribution)


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 3.022 ±(99.9%) 0.002 ms/op
Iteration   2: 2.934 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.989 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (2.934, 2.989, 3.022), stdev = 0.048
  CI (99.9%): [2.107, 3.872] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.004 ms/op
Iteration   1: 3.158 ±(99.9%) 0.003 ms/op
Iteration   2: 3.211 ±(99.9%) 0.001 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.179 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.158, 3.179, 3.211), stdev = 0.028
  CI (99.9%): [2.671, 3.687] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.737 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.019 ms/op
Iteration   1: 4.163 ±(99.9%) 0.008 ms/op
Iteration   2: 3.999 ±(99.9%) 0.006 ms/op
Iteration   3: 4.018 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.060 ±(99.9%) 1.637 ms/op [Average]
  (min, avg, max) = (3.999, 4.060, 4.163), stdev = 0.090
  CI (99.9%): [2.423, 5.697] (assumes normal distribution)


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
# Warmup Iteration   1: 4.330 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.006 ms/op
Iteration   1: 3.268 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  7.226 ms/op
                 createUser·p0.9999: 13.209 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.290 ms/op
                 createUser·p0.9999: 14.509 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   3: 3.252 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  15.663 ms/op
                 createUser·p0.9999: 29.852 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298284
  mean =      3.217 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21555 
    [ 2.500,  5.000) = 275540 
    [ 5.000,  7.500) = 723 
    [ 7.500, 10.000) = 191 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.514 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.128 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  5.464 ms/op
                 existUser·p0.9999: 13.518 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.130 ms/op
                 existUser·p0.9999: 22.637 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  8.683 ms/op
                 existUser·p0.9999: 18.468 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 306132
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34952 
    [ 2.500,  5.000) = 270032 
    [ 5.000,  7.500) = 846 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.460 ms/op
     p(99.9900) =     21.882 ms/op
     p(99.9990) =     22.837 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.837 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.056 ms/op
                 getUser·p0.9999: 13.762 ms/op
                 getUser·p1.00:   14.107 ms/op

Iteration   2: 3.152 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.963 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.652 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.899 ms/op
                 getUser·p0.9999: 17.700 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300320
  mean =      3.197 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 360 
    [ 1.250,  2.500) = 19078 
    [ 2.500,  3.750) = 238081 
    [ 3.750,  5.000) = 41453 
    [ 5.000,  6.250) = 550 
    [ 6.250,  7.500) = 298 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      9.699 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     17.989 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 5.053 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.169 ±(99.9%) 0.012 ms/op
Iteration   1: 4.186 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.284 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 17.717 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.180 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.419 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  15.615 ms/op
                 listUser·p0.9999: 24.096 ms/op
                 listUser·p1.00:   25.133 ms/op

Iteration   3: 4.222 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  17.329 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228878
  mean =      4.196 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1910 
    [ 2.500,  5.000) = 194774 
    [ 5.000,  7.500) = 30496 
    [ 7.500, 10.000) = 1235 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     23.629 ms/op
     p(99.9990) =     25.296 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.103 ± 1.449  ops/ms
ClientGrpc.existUser                       thrpt       3  10.519 ± 2.729  ops/ms
ClientGrpc.getUser                         thrpt       3  10.085 ± 2.237  ops/ms
ClientGrpc.listUser                        thrpt       3   7.787 ± 1.533  ops/ms
ClientGrpc.createUser                       avgt       3   3.185 ± 0.423   ms/op
ClientGrpc.existUser                        avgt       3   2.989 ± 0.883   ms/op
ClientGrpc.getUser                          avgt       3   3.179 ± 0.508   ms/op
ClientGrpc.listUser                         avgt       3   4.060 ± 1.637   ms/op
ClientGrpc.createUser                     sample  298284   3.217 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.514           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.393           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.212           ms/op
ClientGrpc.existUser                      sample  306132   3.135 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.121           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.854           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.460           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.882           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  300320   3.197 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.652           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.699           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.465           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.022           ms/op
ClientGrpc.listUser                       sample  228878   4.196 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.857           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.014           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.221           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.629           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.477           ms/op
