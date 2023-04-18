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
# Warmup Iteration   1: 4.546 ops/ms
# Warmup Iteration   2: 9.074 ops/ms
# Warmup Iteration   3: 10.123 ops/ms
Iteration   1: 10.462 ops/ms
Iteration   2: 10.887 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.652 ±(99.9%) 3.943 ops/ms [Average]
  (min, avg, max) = (10.462, 10.652, 10.887), stdev = 0.216
  CI (99.9%): [6.709, 14.595] (assumes normal distribution)


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
# Warmup Iteration   1: 7.649 ops/ms
# Warmup Iteration   2: 10.819 ops/ms
# Warmup Iteration   3: 11.052 ops/ms
Iteration   1: 10.976 ops/ms
Iteration   2: 11.220 ops/ms
Iteration   3: 11.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.199 ±(99.9%) 3.880 ops/ms [Average]
  (min, avg, max) = (10.976, 11.199, 11.400), stdev = 0.213
  CI (99.9%): [7.319, 15.079] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.884 ops/ms
# Warmup Iteration   2: 10.253 ops/ms
# Warmup Iteration   3: 10.799 ops/ms
Iteration   1: 10.823 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.749 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (10.712, 10.749, 10.823), stdev = 0.064
  CI (99.9%): [9.590, 11.908] (assumes normal distribution)


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
# Warmup Iteration   1: 5.417 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.046 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.153 ±(99.9%) 1.718 ops/ms [Average]
  (min, avg, max) = (8.046, 8.153, 8.223), stdev = 0.094
  CI (99.9%): [6.436, 9.871] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.007 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (2.945, 2.975, 2.995), stdev = 0.026
  CI (99.9%): [2.496, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.906 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.003 ms/op
Iteration   1: 2.795 ±(99.9%) 0.003 ms/op
Iteration   2: 2.761 ±(99.9%) 0.003 ms/op
Iteration   3: 2.792 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.783 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.761, 2.783, 2.795), stdev = 0.019
  CI (99.9%): [2.442, 3.124] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.813 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.002 ms/op
Iteration   2: 2.929 ±(99.9%) 0.003 ms/op
Iteration   3: 2.943 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.942 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (2.929, 2.942, 2.952), stdev = 0.012
  CI (99.9%): [2.731, 3.153] (assumes normal distribution)


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
# Warmup Iteration   1: 5.268 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.024 ms/op
Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
Iteration   2: 3.859 ±(99.9%) 0.055 ms/op
Iteration   3: 3.858 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.849 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (3.829, 3.849, 3.859), stdev = 0.017
  CI (99.9%): [3.543, 4.155] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.561 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.195 ms/op
                 createUser·p0.9999: 17.282 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 2.938 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.355 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  6.038 ms/op
                 createUser·p0.9999: 12.568 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 22.161 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323619
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19730 
    [ 2.500,  5.000) = 302845 
    [ 5.000,  7.500) = 676 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      7.819 ms/op
     p(99.9900) =     20.074 ms/op
     p(99.9990) =     25.364 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.929 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.882 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 16.655 ms/op
                 existUser·p1.00:   17.039 ms/op

Iteration   2: 2.806 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.463 ms/op
                 existUser·p0.9999: 12.118 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   3: 2.837 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.625 ms/op
                 existUser·p0.9999: 14.405 ms/op
                 existUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338996
  mean =      2.831 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2982 
    [ 1.250,  2.500) = 41006 
    [ 2.500,  3.750) = 286773 
    [ 3.750,  5.000) = 7349 
    [ 5.000,  6.250) = 415 
    [ 6.250,  7.500) = 193 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.404 ms/op
     p(99.0000) =      4.244 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     14.767 ms/op
     p(99.9990) =     16.961 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 3.630 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.005 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.342 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  10.665 ms/op
                 getUser·p0.9999: 15.296 ms/op
                 getUser·p1.00:   15.598 ms/op

Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 17.866 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.515 ms/op
                 getUser·p0.9999: 14.631 ms/op
                 getUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321538
  mean =      2.985 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2082 
    [ 1.250,  2.500) = 22852 
    [ 2.500,  3.750) = 281515 
    [ 3.750,  5.000) = 13511 
    [ 5.000,  6.250) = 812 
    [ 6.250,  7.500) = 337 
    [ 7.500,  8.750) = 131 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.282 ms/op
     p(99.9900) =     16.984 ms/op
     p(99.9990) =     18.172 ms/op
     p(99.9999) =     18.252 ms/op
    p(100.0000) =     18.252 ms/op


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
# Warmup Iteration   1: 4.727 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.847 ms/op
                 listUser·p0.9999: 17.826 ms/op
                 listUser·p1.00:   18.121 ms/op

Iteration   2: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.564 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.711 ms/op
                 listUser·p0.9999: 17.620 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 18.331 ms/op
                 listUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248447
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5236 
    [ 2.500,  5.000) = 223403 
    [ 5.000,  7.500) = 18639 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.935 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.652 ± 3.943  ops/ms
ClientGrpc.existUser                       thrpt       3  11.199 ± 3.880  ops/ms
ClientGrpc.getUser                         thrpt       3  10.749 ± 1.159  ops/ms
ClientGrpc.listUser                        thrpt       3   8.153 ± 1.718  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.479   ms/op
ClientGrpc.existUser                        avgt       3   2.783 ± 0.341   ms/op
ClientGrpc.getUser                          avgt       3   2.942 ± 0.211   ms/op
ClientGrpc.listUser                         avgt       3   3.849 ± 0.306   ms/op
ClientGrpc.createUser                     sample  323619   2.965 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.561           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.359           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.819           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.074           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.952           ms/op
ClientGrpc.existUser                      sample  338996   2.831 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.207           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.244           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.767           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.039           ms/op
ClientGrpc.getUser                        sample  321538   2.985 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.574           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.282           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.984           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.252           ms/op
ClientGrpc.listUser                       sample  248447   3.863 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.564           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.776           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.935           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.891           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.218           ms/op
