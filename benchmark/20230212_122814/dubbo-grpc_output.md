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
# Warmup Iteration   1: 4.734 ops/ms
# Warmup Iteration   2: 8.978 ops/ms
# Warmup Iteration   3: 10.045 ops/ms
Iteration   1: 10.616 ops/ms
Iteration   2: 10.116 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.380 ±(99.9%) 4.582 ops/ms [Average]
  (min, avg, max) = (10.116, 10.380, 10.616), stdev = 0.251
  CI (99.9%): [5.798, 14.962] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.794 ops/ms
# Warmup Iteration   2: 10.348 ops/ms
# Warmup Iteration   3: 10.554 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.673 ±(99.9%) 0.439 ops/ms [Average]
  (min, avg, max) = (10.645, 10.673, 10.688), stdev = 0.024
  CI (99.9%): [10.234, 11.111] (assumes normal distribution)


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
# Warmup Iteration   1: 6.872 ops/ms
# Warmup Iteration   2: 9.962 ops/ms
# Warmup Iteration   3: 9.877 ops/ms
Iteration   1: 10.236 ops/ms
Iteration   2: 10.073 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.105 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (10.006, 10.105, 10.236), stdev = 0.118
  CI (99.9%): [7.947, 12.263] (assumes normal distribution)


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
# Warmup Iteration   1: 5.764 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 7.749 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.774 ops/ms
Iteration   3: 7.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.858 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (7.774, 7.858, 7.936), stdev = 0.081
  CI (99.9%): [6.371, 9.344] (assumes normal distribution)


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
# Warmup Iteration   1: 4.487 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.003 ms/op
Iteration   2: 3.213 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.168 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.141, 3.168, 3.213), stdev = 0.039
  CI (99.9%): [2.452, 3.884] (assumes normal distribution)


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
# Warmup Iteration   1: 3.988 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.906 ±(99.9%) 0.003 ms/op
Iteration   3: 2.891 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (2.891, 2.929, 2.991), stdev = 0.054
  CI (99.9%): [1.945, 3.913] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.180 ±(99.9%) 0.002 ms/op
Iteration   2: 3.213 ±(99.9%) 0.004 ms/op
Iteration   3: 3.149 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.181 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (3.149, 3.181, 3.213), stdev = 0.032
  CI (99.9%): [2.600, 3.761] (assumes normal distribution)


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.029 ms/op
Iteration   1: 4.094 ±(99.9%) 0.015 ms/op
Iteration   2: 4.060 ±(99.9%) 0.026 ms/op
Iteration   3: 4.113 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.089 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (4.060, 4.089, 4.113), stdev = 0.027
  CI (99.9%): [3.604, 4.574] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.221 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.271 ms/op
                 createUser·p0.9999: 18.446 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.758 ms/op
                 createUser·p0.9999: 21.560 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.164 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  6.585 ms/op
                 createUser·p0.9999: 22.995 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301949
  mean =      3.180 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23402 
    [ 2.500,  5.000) = 277472 
    [ 5.000,  7.500) = 675 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.127 ms/op
     p(99.9900) =     21.640 ms/op
     p(99.9990) =     23.428 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.035 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.484 ms/op
                 existUser·p0.9999: 19.905 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 3.035 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.759 ms/op
                 existUser·p0.9999: 13.836 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  8.913 ms/op
                 existUser·p0.9999: 19.908 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315248
  mean =      3.045 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42039 
    [ 2.500,  5.000) = 272332 
    [ 5.000,  7.500) = 505 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.051 ms/op
     p(99.9900) =     19.742 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.239 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.653 ms/op
                 getUser·p0.9999: 12.965 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  10.668 ms/op
                 getUser·p0.9999: 14.944 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.888 ms/op
                 getUser·p0.9999: 14.704 ms/op
                 getUser·p1.00:   16.613 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302984
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 493 
    [ 1.250,  2.500) = 16718 
    [ 2.500,  3.750) = 248632 
    [ 3.750,  5.000) = 36035 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     14.659 ms/op
     p(99.9990) =     16.366 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 4.005 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.992 ms/op
                 listUser·p0.9999: 16.368 ms/op
                 listUser·p1.00:   16.843 ms/op

Iteration   2: 4.018 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.496 ms/op
                 listUser·p0.9999: 27.656 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 4.063 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.785 ms/op
                 listUser·p0.9999: 25.764 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238302
  mean =      4.029 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2480 
    [ 2.500,  5.000) = 211403 
    [ 5.000,  7.500) = 23055 
    [ 7.500, 10.000) = 840 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     26.711 ms/op
     p(99.9990) =     27.888 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.380 ± 4.582  ops/ms
ClientGrpc.existUser                       thrpt       3  10.673 ± 0.439  ops/ms
ClientGrpc.getUser                         thrpt       3  10.105 ± 2.158  ops/ms
ClientGrpc.listUser                        thrpt       3   7.858 ± 1.486  ops/ms
ClientGrpc.createUser                       avgt       3   3.168 ± 0.716   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.984   ms/op
ClientGrpc.getUser                          avgt       3   3.181 ± 0.580   ms/op
ClientGrpc.listUser                         avgt       3   4.089 ± 0.485   ms/op
ClientGrpc.createUser                     sample  301949   3.180 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.782           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.127           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.640           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  315248   3.045 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.899           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.051           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.742           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.955           ms/op
ClientGrpc.getUser                        sample  302984   3.171 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.762           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.659           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.613           ms/op
ClientGrpc.listUser                       sample  238302   4.029 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.980           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.483           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.711           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.082           ms/op
