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
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 9.146 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.536 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 10.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.215 ±(99.9%) 5.088 ops/ms [Average]
  (min, avg, max) = (10.039, 10.215, 10.536), stdev = 0.279
  CI (99.9%): [5.127, 15.303] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 9.012 ops/ms
# Warmup Iteration   2: 10.217 ops/ms
# Warmup Iteration   3: 10.862 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.804 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.634 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (10.440, 10.634, 10.804), stdev = 0.183
  CI (99.9%): [7.290, 13.978] (assumes normal distribution)


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
# Warmup Iteration   1: 7.646 ops/ms
# Warmup Iteration   2: 10.225 ops/ms
# Warmup Iteration   3: 10.356 ops/ms
Iteration   1: 10.637 ops/ms
Iteration   2: 10.132 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.452 ±(99.9%) 5.082 ops/ms [Average]
  (min, avg, max) = (10.132, 10.452, 10.637), stdev = 0.279
  CI (99.9%): [5.370, 15.534] (assumes normal distribution)


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
# Warmup Iteration   1: 5.458 ops/ms
# Warmup Iteration   2: 7.748 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 7.755 ops/ms
Iteration   2: 7.627 ops/ms
Iteration   3: 7.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.655 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (7.582, 7.655, 7.755), stdev = 0.090
  CI (99.9%): [6.010, 9.300] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.167 ±(99.9%) 0.002 ms/op
Iteration   2: 3.101 ±(99.9%) 0.001 ms/op
Iteration   3: 3.017 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.095 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (3.017, 3.095, 3.167), stdev = 0.075
  CI (99.9%): [1.719, 4.471] (assumes normal distribution)


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 3.001 ±(99.9%) 0.002 ms/op
Iteration   2: 2.924 ±(99.9%) 0.004 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (2.924, 2.978, 3.008), stdev = 0.046
  CI (99.9%): [2.131, 3.825] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.003 ms/op
Iteration   1: 3.103 ±(99.9%) 0.002 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.084 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.040, 3.084, 3.109), stdev = 0.038
  CI (99.9%): [2.384, 3.783] (assumes normal distribution)


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
# Warmup Iteration   1: 5.039 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
Iteration   1: 4.128 ±(99.9%) 0.035 ms/op
Iteration   2: 3.991 ±(99.9%) 0.015 ms/op
Iteration   3: 4.062 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.060 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (3.991, 4.060, 4.128), stdev = 0.069
  CI (99.9%): [2.809, 5.311] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.062 ms/op
                 createUser·p0.9999: 11.106 ms/op
                 createUser·p1.00:   11.469 ms/op

Iteration   2: 3.200 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.652 ms/op
                 createUser·p0.9999: 14.353 ms/op
                 createUser·p1.00:   15.172 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.731 ms/op
                 createUser·p0.9999: 16.302 ms/op
                 createUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304146
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1088 
    [ 1.250,  2.500) = 18173 
    [ 2.500,  3.750) = 248348 
    [ 3.750,  5.000) = 35368 
    [ 5.000,  6.250) = 550 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.116 ms/op
     p(99.9900) =     15.804 ms/op
     p(99.9990) =     16.560 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  6.014 ms/op
                 existUser·p0.9999: 11.210 ms/op
                 existUser·p1.00:   12.141 ms/op

Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.777 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.927 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  8.059 ms/op
                 existUser·p0.9999: 23.955 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324644
  mean =      2.957 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42856 
    [ 2.500,  5.000) = 280625 
    [ 5.000,  7.500) = 897 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     19.919 ms/op
     p(99.9990) =     24.191 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.295 ms/op
                 getUser·p0.999:  7.870 ms/op
                 getUser·p0.9999: 11.868 ms/op
                 getUser·p1.00:   12.108 ms/op

Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.259 ms/op
                 getUser·p0.9999: 16.749 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.164 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.496 ms/op
                 getUser·p0.9999: 26.745 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307893
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23773 
    [ 2.500,  5.000) = 283067 
    [ 5.000,  7.500) = 789 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.046 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     27.288 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


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
# Warmup Iteration   1: 5.471 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.010 ms/op
Iteration   1: 4.192 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.290 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  12.742 ms/op
                 listUser·p0.9999: 17.674 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   2: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  13.522 ms/op
                 listUser·p0.9999: 16.238 ms/op
                 listUser·p1.00:   16.695 ms/op

Iteration   3: 4.045 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.416 ms/op
                 listUser·p0.9999: 28.091 ms/op
                 listUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235077
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4781 
    [ 2.500,  5.000) = 192768 
    [ 5.000,  7.500) = 36367 
    [ 7.500, 10.000) = 778 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     13.597 ms/op
     p(99.9900) =     27.640 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.215 ± 5.088  ops/ms
ClientGrpc.existUser                       thrpt       3  10.634 ± 3.344  ops/ms
ClientGrpc.getUser                         thrpt       3  10.452 ± 5.082  ops/ms
ClientGrpc.listUser                        thrpt       3   7.655 ± 1.645  ops/ms
ClientGrpc.createUser                       avgt       3   3.095 ± 1.376   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.847   ms/op
ClientGrpc.getUser                          avgt       3   3.084 ± 0.699   ms/op
ClientGrpc.listUser                         avgt       3   4.060 ± 1.251   ms/op
ClientGrpc.createUser                     sample  304146   3.155 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.580           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.116           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.804           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.761           ms/op
ClientGrpc.existUser                      sample  324644   2.957 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.919           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.347           ms/op
ClientGrpc.getUser                        sample  307893   3.115 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.631           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.046           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.838           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.427           ms/op
ClientGrpc.listUser                       sample  235077   4.082 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.290           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.597           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.640           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.410           ms/op
