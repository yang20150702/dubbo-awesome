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
# Warmup Iteration   1: 5.124 ops/ms
# Warmup Iteration   2: 9.218 ops/ms
# Warmup Iteration   3: 10.327 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 10.489 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.138 ±(99.9%) 6.310 ops/ms [Average]
  (min, avg, max) = (9.798, 10.138, 10.489), stdev = 0.346
  CI (99.9%): [3.828, 16.448] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.137 ops/ms
# Warmup Iteration   2: 10.146 ops/ms
# Warmup Iteration   3: 10.675 ops/ms
Iteration   1: 10.740 ops/ms
Iteration   2: 10.501 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.656 ±(99.9%) 2.445 ops/ms [Average]
  (min, avg, max) = (10.501, 10.656, 10.740), stdev = 0.134
  CI (99.9%): [8.210, 13.101] (assumes normal distribution)


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
# Warmup Iteration   1: 7.649 ops/ms
# Warmup Iteration   2: 10.054 ops/ms
# Warmup Iteration   3: 10.524 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.327 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.326 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (10.308, 10.326, 10.343), stdev = 0.017
  CI (99.9%): [10.008, 10.645] (assumes normal distribution)


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
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 8.124 ops/ms
Iteration   2: 8.110 ops/ms
Iteration   3: 7.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.017 ±(99.9%) 3.144 ops/ms [Average]
  (min, avg, max) = (7.819, 8.017, 8.124), stdev = 0.172
  CI (99.9%): [4.874, 11.161] (assumes normal distribution)


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
# Warmup Iteration   1: 3.910 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.010 ms/op
Iteration   1: 3.121 ±(99.9%) 0.002 ms/op
Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
Iteration   3: 3.208 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.148 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.116, 3.148, 3.208), stdev = 0.052
  CI (99.9%): [2.205, 4.092] (assumes normal distribution)


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
# Warmup Iteration   1: 3.983 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.016 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (3.009, 3.016, 3.030), stdev = 0.012
  CI (99.9%): [2.804, 3.229] (assumes normal distribution)


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
# Warmup Iteration   1: 3.808 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.004 ms/op
Iteration   1: 3.088 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.076 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.687 ms/op [Average]
  (min, avg, max) = (3.076, 3.104, 3.146), stdev = 0.038
  CI (99.9%): [2.416, 3.791] (assumes normal distribution)


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.010 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
Iteration   2: 4.025 ±(99.9%) 0.015 ms/op
Iteration   3: 3.935 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.007 ±(99.9%) 1.188 ms/op [Average]
  (min, avg, max) = (3.935, 4.007, 4.062), stdev = 0.065
  CI (99.9%): [2.819, 5.196] (assumes normal distribution)


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
Iteration   1: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.671 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  8.462 ms/op
                 createUser·p0.9999: 12.497 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  7.903 ms/op
                 createUser·p0.9999: 14.754 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.436 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308069
  mean =      3.116 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27785 
    [ 2.500,  5.000) = 277545 
    [ 5.000,  7.500) = 2260 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      8.028 ms/op
     p(99.9900) =     23.907 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.224 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.365 ms/op
                 existUser·p0.9999: 13.369 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 18.036 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 3.054 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 24.119 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316618
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44909 
    [ 2.500,  5.000) = 269756 
    [ 5.000,  7.500) = 1452 
    [ 7.500, 10.000) = 195 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.224 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.563 ms/op
     p(99.9000) =      9.761 ms/op
     p(99.9900) =     21.977 ms/op
     p(99.9990) =     24.434 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.131 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  8.217 ms/op
                 getUser·p0.9999: 11.946 ms/op
                 getUser·p1.00:   12.501 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  8.249 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.669 ms/op
                 getUser·p0.9999: 22.365 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310436
  mean =      3.091 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27946 
    [ 2.500,  5.000) = 280285 
    [ 5.000,  7.500) = 1814 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     22.669 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.013 ms/op
Iteration   1: 4.081 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  12.134 ms/op
                 listUser·p0.9999: 15.240 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.465 ms/op
                 listUser·p0.9999: 23.458 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.850 ms/op
                 listUser·p0.9999: 24.601 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240617
  mean =      3.990 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5269 
    [ 2.500,  5.000) = 205995 
    [ 5.000,  7.500) = 27841 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     23.853 ms/op
     p(99.9990) =     25.047 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.138 ± 6.310  ops/ms
ClientGrpc.existUser                       thrpt       3  10.656 ± 2.445  ops/ms
ClientGrpc.getUser                         thrpt       3  10.326 ± 0.318  ops/ms
ClientGrpc.listUser                        thrpt       3   8.017 ± 3.144  ops/ms
ClientGrpc.createUser                       avgt       3   3.148 ± 0.943   ms/op
ClientGrpc.existUser                        avgt       3   3.016 ± 0.212   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.687   ms/op
ClientGrpc.listUser                         avgt       3   4.007 ± 1.188   ms/op
ClientGrpc.createUser                     sample  308069   3.116 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.436           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.907           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.854           ms/op
ClientGrpc.existUser                      sample  316618   3.030 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.224           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.563           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.761           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.977           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.510           ms/op
ClientGrpc.getUser                        sample  310436   3.091 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.697           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.957           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.839           ms/op
ClientGrpc.listUser                       sample  240617   3.990 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.825           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.053           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.853           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
