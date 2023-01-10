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
# Warmup Iteration   1: 3.102 ops/ms
# Warmup Iteration   2: 6.211 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 8.176 ops/ms
Iteration   3: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.129 ±(99.9%) 3.331 ops/ms [Average]
  (min, avg, max) = (7.928, 8.129, 8.284), stdev = 0.183
  CI (99.9%): [4.798, 11.460] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.044 ops/ms
# Warmup Iteration   2: 7.643 ops/ms
# Warmup Iteration   3: 8.037 ops/ms
Iteration   1: 8.131 ops/ms
Iteration   2: 8.711 ops/ms
Iteration   3: 8.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.449 ±(99.9%) 5.364 ops/ms [Average]
  (min, avg, max) = (8.131, 8.449, 8.711), stdev = 0.294
  CI (99.9%): [3.085, 13.812] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.152 ±(99.9%) 0.938 ops/ms [Average]
  (min, avg, max) = (8.094, 8.152, 8.192), stdev = 0.051
  CI (99.9%): [7.214, 9.090] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ops/ms
# Warmup Iteration   2: 5.975 ops/ms
# Warmup Iteration   3: 6.543 ops/ms
Iteration   1: 6.301 ops/ms
Iteration   2: 6.334 ops/ms
Iteration   3: 6.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.312 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (6.301, 6.312, 6.334), stdev = 0.019
  CI (99.9%): [5.968, 6.657] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.719 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.007 ms/op
Iteration   1: 3.962 ±(99.9%) 0.005 ms/op
Iteration   2: 3.982 ±(99.9%) 0.003 ms/op
Iteration   3: 3.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.960 ±(99.9%) 0.415 ms/op [Average]
  (min, avg, max) = (3.937, 3.960, 3.982), stdev = 0.023
  CI (99.9%): [3.545, 4.376] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.855 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.004 ms/op
Iteration   1: 3.729 ±(99.9%) 0.003 ms/op
Iteration   2: 3.845 ±(99.9%) 0.003 ms/op
Iteration   3: 3.820 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.798 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (3.729, 3.798, 3.845), stdev = 0.061
  CI (99.9%): [2.685, 4.912] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.004 ms/op
Iteration   1: 3.985 ±(99.9%) 0.005 ms/op
Iteration   2: 3.950 ±(99.9%) 0.004 ms/op
Iteration   3: 3.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.967 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.950, 3.967, 3.985), stdev = 0.018
  CI (99.9%): [3.645, 4.288] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.939 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.968 ±(99.9%) 0.010 ms/op
Iteration   1: 4.984 ±(99.9%) 0.010 ms/op
Iteration   2: 5.003 ±(99.9%) 0.016 ms/op
Iteration   3: 4.954 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.980 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (4.954, 4.980, 5.003), stdev = 0.025
  CI (99.9%): [4.532, 5.429] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.705 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.011 ms/op
Iteration   1: 3.920 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  16.627 ms/op
                 createUser·p0.9999: 20.147 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 3.865 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  12.177 ms/op
                 createUser·p0.9999: 20.995 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.856 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  13.484 ms/op
                 createUser·p0.9999: 24.626 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247367
  mean =      3.880 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7103 
    [ 2.500,  5.000) = 224527 
    [ 5.000,  7.500) = 13387 
    [ 7.500, 10.000) = 1650 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.375 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     23.286 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.391 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.011 ms/op
Iteration   1: 3.738 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.898 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.588 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.455 ms/op
                 existUser·p0.999:  11.722 ms/op
                 existUser·p0.9999: 16.825 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   2: 3.804 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 13.936 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 3.773 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 20.842 ms/op
                 existUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254270
  mean =      3.771 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10263 
    [ 2.500,  5.000) = 230791 
    [ 5.000,  7.500) = 11582 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     11.710 ms/op
     p(99.9900) =     17.943 ms/op
     p(99.9990) =     21.165 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.229 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.011 ms/op
Iteration   1: 3.915 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 16.253 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 34.400 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  13.047 ms/op
                 getUser·p0.9999: 21.657 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 246314
  mean =      3.897 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7280 
    [ 2.500,  5.000) = 221749 
    [ 5.000,  7.500) = 15355 
    [ 7.500, 10.000) = 1459 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     32.780 ms/op
     p(99.9990) =     35.700 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 7.110 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.080 ±(99.9%) 0.018 ms/op
Iteration   1: 4.955 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.291 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  16.924 ms/op
                 listUser·p0.9999: 21.827 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 4.906 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.349 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 23.558 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.957 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.431 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  19.591 ms/op
                 listUser·p0.9999: 27.153 ms/op
                 listUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194371
  mean =      4.939 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 335 
    [ 2.500,  5.000) = 130605 
    [ 5.000,  7.500) = 55559 
    [ 7.500, 10.000) = 6589 
    [10.000, 12.500) = 777 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.382 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     18.731 ms/op
     p(99.9900) =     25.381 ms/op
     p(99.9990) =     29.886 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.129 ± 3.331  ops/ms
ClientGrpc.existUser                       thrpt       3   8.449 ± 5.364  ops/ms
ClientGrpc.getUser                         thrpt       3   8.152 ± 0.938  ops/ms
ClientGrpc.listUser                        thrpt       3   6.312 ± 0.345  ops/ms
ClientGrpc.createUser                       avgt       3   3.960 ± 0.415   ms/op
ClientGrpc.existUser                        avgt       3   3.798 ± 1.114   ms/op
ClientGrpc.getUser                          avgt       3   3.967 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   4.980 ± 0.448   ms/op
ClientGrpc.createUser                     sample  247367   3.880 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.802           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.336           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.707           ms/op
ClientGrpc.existUser                      sample  254270   3.771 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.724           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.710           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.943           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.266           ms/op
ClientGrpc.getUser                        sample  246314   3.897 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.793           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.784           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.226           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.996           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.206           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.780           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.290           ms/op
ClientGrpc.listUser                       sample  194371   4.939 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.270           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.678           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.382           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.290           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.731           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.381           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.917           ms/op
