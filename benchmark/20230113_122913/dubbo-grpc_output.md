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
# Warmup Iteration   1: 4.932 ops/ms
# Warmup Iteration   2: 9.379 ops/ms
# Warmup Iteration   3: 10.408 ops/ms
Iteration   1: 10.681 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.726 ±(99.9%) 0.924 ops/ms [Average]
  (min, avg, max) = (10.681, 10.726, 10.781), stdev = 0.051
  CI (99.9%): [9.801, 11.650] (assumes normal distribution)


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
# Warmup Iteration   1: 8.232 ops/ms
# Warmup Iteration   2: 10.694 ops/ms
# Warmup Iteration   3: 10.909 ops/ms
Iteration   1: 11.170 ops/ms
Iteration   2: 10.833 ops/ms
Iteration   3: 11.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.061 ±(99.9%) 3.591 ops/ms [Average]
  (min, avg, max) = (10.833, 11.061, 11.179), stdev = 0.197
  CI (99.9%): [7.469, 14.652] (assumes normal distribution)


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
# Warmup Iteration   1: 9.299 ops/ms
# Warmup Iteration   2: 10.363 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.545 ±(99.9%) 2.997 ops/ms [Average]
  (min, avg, max) = (10.447, 10.545, 10.735), stdev = 0.164
  CI (99.9%): [7.547, 13.542] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.640 ops/ms
# Warmup Iteration   2: 8.109 ops/ms
# Warmup Iteration   3: 7.925 ops/ms
Iteration   1: 8.022 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 8.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.057 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (8.015, 8.057, 8.134), stdev = 0.067
  CI (99.9%): [6.842, 9.273] (assumes normal distribution)


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.031 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.018, 3.068, 3.154), stdev = 0.075
  CI (99.9%): [1.705, 4.431] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
Iteration   3: 2.860 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.917 ±(99.9%) 0.905 ms/op [Average]
  (min, avg, max) = (2.860, 2.917, 2.948), stdev = 0.050
  CI (99.9%): [2.011, 3.822] (assumes normal distribution)


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
# Warmup Iteration   1: 3.943 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.048 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.008, 3.048, 3.112), stdev = 0.056
  CI (99.9%): [2.022, 4.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.094 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.016 ms/op
Iteration   1: 4.062 ±(99.9%) 0.015 ms/op
Iteration   2: 3.921 ±(99.9%) 0.041 ms/op
Iteration   3: 4.071 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.018 ±(99.9%) 1.538 ms/op [Average]
  (min, avg, max) = (3.921, 4.018, 4.071), stdev = 0.084
  CI (99.9%): [2.480, 5.556] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.480 ms/op
                 createUser·p0.9999: 15.120 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   2: 2.924 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.326 ms/op
                 createUser·p0.95:   3.453 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.439 ms/op
                 createUser·p0.9999: 16.057 ms/op
                 createUser·p1.00:   16.384 ms/op

Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.215 ms/op
                 createUser·p0.9999: 18.168 ms/op
                 createUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319106
  mean =      3.009 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2195 
    [ 1.250,  2.500) = 28508 
    [ 2.500,  3.750) = 269050 
    [ 3.750,  5.000) = 18148 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 206 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 79 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.708 ms/op
     p(99.9900) =     17.441 ms/op
     p(99.9990) =     19.708 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.625 ms/op
                 existUser·p0.9999: 11.439 ms/op
                 existUser·p1.00:   11.796 ms/op

Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.764 ms/op
                 existUser·p0.9999: 25.264 ms/op
                 existUser·p1.00:   25.952 ms/op

Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  5.259 ms/op
                 existUser·p0.9999: 14.511 ms/op
                 existUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326903
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49296 
    [ 2.500,  5.000) = 276624 
    [ 5.000,  7.500) = 703 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     20.530 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.634 ms/op
                 getUser·p0.9999: 15.882 ms/op
                 getUser·p1.00:   16.187 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.155 ms/op
                 getUser·p0.9999: 16.910 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.381 ms/op
                 getUser·p0.9999: 15.050 ms/op
                 getUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309787
  mean =      3.098 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1105 
    [ 1.250,  2.500) = 18393 
    [ 2.500,  3.750) = 264133 
    [ 3.750,  5.000) = 25294 
    [ 5.000,  6.250) = 508 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 59 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.514 ms/op
     p(99.9900) =     15.876 ms/op
     p(99.9990) =     18.439 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.166 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.012 ms/op
Iteration   1: 4.112 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.280 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  12.230 ms/op
                 listUser·p0.9999: 16.732 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 17.407 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 22.749 ms/op
                 listUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236450
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4126 
    [ 2.500,  5.000) = 196754 
    [ 5.000,  7.500) = 34349 
    [ 7.500, 10.000) = 817 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.280 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     21.245 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.726 ± 0.924  ops/ms
ClientGrpc.existUser                       thrpt       3  11.061 ± 3.591  ops/ms
ClientGrpc.getUser                         thrpt       3  10.545 ± 2.997  ops/ms
ClientGrpc.listUser                        thrpt       3   8.057 ± 1.216  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 1.363   ms/op
ClientGrpc.existUser                        avgt       3   2.917 ± 0.905   ms/op
ClientGrpc.getUser                          avgt       3   3.048 ± 1.026   ms/op
ClientGrpc.listUser                         avgt       3   4.018 ± 1.538   ms/op
ClientGrpc.createUser                     sample  319106   3.009 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.523           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.708           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.441           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.857           ms/op
ClientGrpc.existUser                      sample  326903   2.934 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.685           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.530           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.952           ms/op
ClientGrpc.getUser                        sample  309787   3.098 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.517           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.514           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.876           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.579           ms/op
ClientGrpc.listUser                       sample  236450   4.058 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.280           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.898           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.631           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.245           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
