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
# Warmup Iteration   1: 4.382 ops/ms
# Warmup Iteration   2: 8.924 ops/ms
# Warmup Iteration   3: 9.709 ops/ms
Iteration   1: 9.966 ops/ms
Iteration   2: 10.200 ops/ms
Iteration   3: 9.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.011 ±(99.9%) 3.128 ops/ms [Average]
  (min, avg, max) = (9.866, 10.011, 10.200), stdev = 0.171
  CI (99.9%): [6.883, 13.139] (assumes normal distribution)


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
# Warmup Iteration   1: 7.191 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.565 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.518 ±(99.9%) 2.369 ops/ms [Average]
  (min, avg, max) = (10.371, 10.518, 10.617), stdev = 0.130
  CI (99.9%): [8.149, 12.887] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.842 ops/ms
# Warmup Iteration   2: 9.919 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.375 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 10.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.226 ±(99.9%) 2.358 ops/ms [Average]
  (min, avg, max) = (10.149, 10.226, 10.375), stdev = 0.129
  CI (99.9%): [7.868, 12.584] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ops/ms
# Warmup Iteration   2: 7.351 ops/ms
# Warmup Iteration   3: 7.870 ops/ms
Iteration   1: 7.972 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 7.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.979 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (7.964, 7.979, 8.001), stdev = 0.019
  CI (99.9%): [7.626, 8.333] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.333 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.003 ms/op
Iteration   1: 3.161 ±(99.9%) 0.001 ms/op
Iteration   2: 3.149 ±(99.9%) 0.002 ms/op
Iteration   3: 3.219 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.149, 3.176, 3.219), stdev = 0.037
  CI (99.9%): [2.496, 3.856] (assumes normal distribution)


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.003 ms/op
Iteration   1: 2.950 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.019 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (2.950, 3.019, 3.071), stdev = 0.063
  CI (99.9%): [1.876, 4.162] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.003 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.108 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.083, 3.108, 3.143), stdev = 0.031
  CI (99.9%): [2.534, 3.682] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.536 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.026 ms/op
Iteration   1: 4.024 ±(99.9%) 0.013 ms/op
Iteration   2: 4.016 ±(99.9%) 0.052 ms/op
Iteration   3: 4.080 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.040 ±(99.9%) 0.634 ms/op [Average]
  (min, avg, max) = (4.016, 4.040, 4.080), stdev = 0.035
  CI (99.9%): [3.406, 4.674] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  10.917 ms/op
                 createUser·p0.9999: 13.923 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.956 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   4.517 ms/op
                 createUser·p0.999:  10.143 ms/op
                 createUser·p0.9999: 18.317 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302129
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1117 
    [ 1.250,  2.500) = 15880 
    [ 2.500,  3.750) = 245911 
    [ 3.750,  5.000) = 37753 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.748 ms/op
     p(99.9900) =     19.057 ms/op
     p(99.9990) =     19.693 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
Iteration   1: 3.106 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  5.522 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  6.767 ms/op
                 existUser·p0.9999: 13.328 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.842 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 16.064 ms/op
                 existUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320755
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5793 
    [ 1.250,  2.500) = 37837 
    [ 2.500,  3.750) = 249141 
    [ 3.750,  5.000) = 27044 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      6.212 ms/op
     p(99.9900) =     15.250 ms/op
     p(99.9990) =     16.263 ms/op
     p(99.9999) =     16.466 ms/op
    p(100.0000) =     16.466 ms/op


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.005 ms/op
Iteration   1: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  7.891 ms/op
                 getUser·p0.9999: 17.915 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 3.077 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.716 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.242 ms/op
                 getUser·p0.9999: 16.653 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.170 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.266 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 14.168 ms/op
                 getUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307531
  mean =      3.121 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2084 
    [ 1.250,  2.500) = 19970 
    [ 2.500,  3.750) = 257592 
    [ 3.750,  5.000) = 26033 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 447 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.266 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.208 ms/op
     p(99.9900) =     16.990 ms/op
     p(99.9990) =     18.366 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.115 ±(99.9%) 0.012 ms/op
Iteration   1: 4.287 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.652 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.496 ms/op
                 listUser·p0.999:  14.684 ms/op
                 listUser·p0.9999: 19.288 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 4.353 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.588 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  19.314 ms/op
                 listUser·p0.9999: 24.508 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 226287
  mean =      4.244 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2995 
    [ 2.500,  5.000) = 176388 
    [ 5.000,  7.500) = 44611 
    [ 7.500, 10.000) = 1783 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     16.751 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     25.238 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.011 ± 3.128  ops/ms
ClientGrpc.existUser                       thrpt       3  10.518 ± 2.369  ops/ms
ClientGrpc.getUser                         thrpt       3  10.226 ± 2.358  ops/ms
ClientGrpc.listUser                        thrpt       3   7.979 ± 0.353  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.680   ms/op
ClientGrpc.existUser                        avgt       3   3.019 ± 1.143   ms/op
ClientGrpc.getUser                          avgt       3   3.108 ± 0.574   ms/op
ClientGrpc.listUser                         avgt       3   4.040 ± 0.634   ms/op
ClientGrpc.createUser                     sample  302129   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.562           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.039           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.748           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.057           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  320755   2.992 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.547           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.212           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.250           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.466           ms/op
ClientGrpc.getUser                        sample  307531   3.121 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.266           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.208           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.990           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  226287   4.244 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.588           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.990           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.512           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.751           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.362           ms/op
