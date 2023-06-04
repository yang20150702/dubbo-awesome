# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 10.035 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 1.216 ops/ms [Average]
  (min, avg, max) = (10.390, 10.435, 10.512), stdev = 0.067
  CI (99.9%): [9.219, 11.652] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.656 ops/ms
# Warmup Iteration   2: 10.646 ops/ms
# Warmup Iteration   3: 11.070 ops/ms
Iteration   1: 11.162 ops/ms
Iteration   2: 10.968 ops/ms
Iteration   3: 10.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.009 ±(99.9%) 2.498 ops/ms [Average]
  (min, avg, max) = (10.897, 11.009, 11.162), stdev = 0.137
  CI (99.9%): [8.511, 13.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.259 ops/ms
# Warmup Iteration   2: 10.238 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.629 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.570 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (10.417, 10.570, 10.663), stdev = 0.133
  CI (99.9%): [8.136, 13.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.623 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 7.971 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.044 ±(99.9%) 1.008 ops/ms [Average]
  (min, avg, max) = (7.987, 8.044, 8.098), stdev = 0.055
  CI (99.9%): [7.036, 9.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.086 ±(99.9%) 0.003 ms/op
Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
Iteration   3: 3.074 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.042, 3.068, 3.086), stdev = 0.023
  CI (99.9%): [2.646, 3.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.004 ms/op
Iteration   1: 2.849 ±(99.9%) 0.004 ms/op
Iteration   2: 2.867 ±(99.9%) 0.004 ms/op
Iteration   3: 2.877 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.865 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.849, 2.865, 2.877), stdev = 0.014
  CI (99.9%): [2.607, 3.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.003 ms/op
Iteration   2: 3.084 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.046 ±(99.9%) 0.770 ms/op [Average]
  (min, avg, max) = (3.001, 3.046, 3.084), stdev = 0.042
  CI (99.9%): [2.276, 3.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.035 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.031 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
Iteration   2: 3.946 ±(99.9%) 0.015 ms/op
Iteration   3: 3.899 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.898 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.851, 3.898, 3.946), stdev = 0.048
  CI (99.9%): [3.026, 4.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.833 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.241 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  10.082 ms/op
                 createUser·p0.9999: 15.156 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.852 ms/op
                 createUser·p0.9999: 14.526 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.246 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  10.805 ms/op
                 createUser·p0.9999: 18.079 ms/op
                 createUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313312
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 737 
    [ 1.250,  2.500) = 21209 
    [ 2.500,  3.750) = 272910 
    [ 3.750,  5.000) = 16833 
    [ 5.000,  6.250) = 886 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 89 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.246 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      9.613 ms/op
     p(99.9900) =     15.390 ms/op
     p(99.9990) =     19.394 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.091 ms/op

Iteration   2: 2.941 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.792 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  9.095 ms/op
                 existUser·p0.9999: 17.043 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.927 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.012 ms/op
                 existUser·p0.9999: 23.364 ms/op
                 existUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328338
  mean =      2.923 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42365 
    [ 2.500,  5.000) = 284256 
    [ 5.000,  7.500) = 1207 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      9.464 ms/op
     p(99.9900) =     18.353 ms/op
     p(99.9990) =     23.607 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.087 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.588 ms/op
                 getUser·p0.999:  9.768 ms/op
                 getUser·p0.9999: 17.899 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.466 ms/op
                 getUser·p0.9999: 15.598 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  5.893 ms/op
                 getUser·p0.9999: 17.871 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316637
  mean =      3.031 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18612 
    [ 2.500,  5.000) = 296899 
    [ 5.000,  7.500) = 792 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.652 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.904 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.011 ms/op
Iteration   1: 3.971 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.895 ms/op
                 listUser·p0.999:  12.403 ms/op
                 listUser·p0.9999: 18.673 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.044 ms/op
                 listUser·p0.9999: 17.755 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.555 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241340
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 3237 
    [ 2.500,  3.750) = 93085 
    [ 3.750,  5.000) = 124245 
    [ 5.000,  6.250) = 14868 
    [ 6.250,  7.500) = 4746 
    [ 7.500,  8.750) = 632 
    [ 8.750, 10.000) = 119 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.669 ms/op
     p(99.9900) =     18.304 ms/op
     p(99.9990) =     19.017 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 1.216  ops/ms
ClientGrpc.existUser                       thrpt       3  11.009 ± 2.498  ops/ms
ClientGrpc.getUser                         thrpt       3  10.570 ± 2.434  ops/ms
ClientGrpc.listUser                        thrpt       3   8.044 ± 1.008  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 0.422   ms/op
ClientGrpc.existUser                        avgt       3   2.865 ± 0.257   ms/op
ClientGrpc.getUser                          avgt       3   3.046 ± 0.770   ms/op
ClientGrpc.listUser                         avgt       3   3.898 ± 0.873   ms/op
ClientGrpc.createUser                     sample  313312   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.246           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.613           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.390           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.431           ms/op
ClientGrpc.existUser                      sample  328338   2.923 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.432           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.464           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.353           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.805           ms/op
ClientGrpc.getUser                        sample  316637   3.031 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.535           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.695           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.675           ms/op
ClientGrpc.listUser                       sample  241340   3.978 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.555           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.669           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.304           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.202           ms/op
