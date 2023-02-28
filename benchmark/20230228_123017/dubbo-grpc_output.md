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
# Warmup Iteration   1: 4.747 ops/ms
# Warmup Iteration   2: 9.337 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 10.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.173 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (10.005, 10.173, 10.302), stdev = 0.152
  CI (99.9%): [7.395, 12.950] (assumes normal distribution)


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
# Warmup Iteration   1: 7.912 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.485 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.638 ±(99.9%) 2.681 ops/ms [Average]
  (min, avg, max) = (10.485, 10.638, 10.778), stdev = 0.147
  CI (99.9%): [7.957, 13.319] (assumes normal distribution)


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
# Warmup Iteration   1: 7.034 ops/ms
# Warmup Iteration   2: 9.955 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.340 ±(99.9%) 3.922 ops/ms [Average]
  (min, avg, max) = (10.098, 10.340, 10.507), stdev = 0.215
  CI (99.9%): [6.418, 14.263] (assumes normal distribution)


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
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 7.159 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.787 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.928 ±(99.9%) 3.048 ops/ms [Average]
  (min, avg, max) = (7.787, 7.928, 8.113), stdev = 0.167
  CI (99.9%): [4.880, 10.976] (assumes normal distribution)


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
# Warmup Iteration   1: 4.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.003 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.135 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.039, 3.135, 3.189), stdev = 0.083
  CI (99.9%): [1.616, 4.654] (assumes normal distribution)


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.945 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (2.945, 3.005, 3.042), stdev = 0.052
  CI (99.9%): [2.059, 3.951] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.125 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.112 ±(99.9%) 0.380 ms/op [Average]
  (min, avg, max) = (3.088, 3.112, 3.125), stdev = 0.021
  CI (99.9%): [2.733, 3.492] (assumes normal distribution)


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.165 ±(99.9%) 0.028 ms/op
Iteration   1: 4.099 ±(99.9%) 0.026 ms/op
Iteration   2: 4.004 ±(99.9%) 0.025 ms/op
Iteration   3: 4.153 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.085 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (4.004, 4.085, 4.153), stdev = 0.075
  CI (99.9%): [2.716, 5.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.098 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.407 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  9.965 ms/op
                 createUser·p0.9999: 11.796 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  7.807 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   13.107 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.792 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.484 ms/op
                 createUser·p0.999:  13.025 ms/op
                 createUser·p0.9999: 16.131 ms/op
                 createUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309598
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1927 
    [ 1.250,  2.500) = 23442 
    [ 2.500,  3.750) = 254310 
    [ 3.750,  5.000) = 26990 
    [ 5.000,  6.250) = 1511 
    [ 6.250,  7.500) = 848 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     10.197 ms/op
     p(99.9900) =     14.075 ms/op
     p(99.9990) =     16.400 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.006 ms/op
Iteration   1: 3.063 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.047 ms/op
                 existUser·p0.9999: 12.116 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.947 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.400 ms/op
                 existUser·p0.9999: 14.977 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.021 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.414 ms/op
                 existUser·p0.999:  6.702 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318948
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41356 
    [ 2.500,  5.000) = 276383 
    [ 5.000,  7.500) = 958 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     23.193 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.260 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  9.144 ms/op
                 getUser·p0.9999: 12.501 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.715 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.149 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.856 ms/op
                 getUser·p0.9999: 17.168 ms/op
                 getUser·p1.00:   19.235 ms/op

Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.511 ms/op
                 getUser·p0.999:  7.281 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301385
  mean =      3.186 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22616 
    [ 2.500,  5.000) = 276918 
    [ 5.000,  7.500) = 1482 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     21.286 ms/op
     p(99.9990) =     23.461 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 5.278 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.013 ms/op
Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.307 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  15.348 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 4.150 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  16.069 ms/op
                 listUser·p0.9999: 23.504 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.131 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 24.003 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231100
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4846 
    [ 2.500,  5.000) = 187709 
    [ 5.000,  7.500) = 36141 
    [ 7.500, 10.000) = 1790 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.431 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     16.071 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     26.631 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.173 ± 2.777  ops/ms
ClientGrpc.existUser                       thrpt       3  10.638 ± 2.681  ops/ms
ClientGrpc.getUser                         thrpt       3  10.340 ± 3.922  ops/ms
ClientGrpc.listUser                        thrpt       3   7.928 ± 3.048  ops/ms
ClientGrpc.createUser                       avgt       3   3.135 ± 1.519   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 0.946   ms/op
ClientGrpc.getUser                          avgt       3   3.112 ± 0.380   ms/op
ClientGrpc.listUser                         avgt       3   4.085 ± 1.370   ms/op
ClientGrpc.createUser                     sample  309598   3.098 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.407           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.932           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.197           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.075           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.613           ms/op
ClientGrpc.existUser                      sample  318948   3.010 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.863           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.193           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  301385   3.186 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.674           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.286           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.888           ms/op
ClientGrpc.listUser                       sample  231100   4.154 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.920           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.029           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.527           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.935           ms/op
