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
# Warmup Iteration   1: 3.861 ops/ms
# Warmup Iteration   2: 8.422 ops/ms
# Warmup Iteration   3: 9.347 ops/ms
Iteration   1: 9.730 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 10.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.931 ±(99.9%) 3.189 ops/ms [Average]
  (min, avg, max) = (9.730, 9.931, 10.040), stdev = 0.175
  CI (99.9%): [6.742, 13.120] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.292 ops/ms
# Warmup Iteration   2: 10.369 ops/ms
# Warmup Iteration   3: 11.080 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.489 ops/ms
Iteration   3: 10.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.680 ±(99.9%) 3.929 ops/ms [Average]
  (min, avg, max) = (10.489, 10.680, 10.913), stdev = 0.215
  CI (99.9%): [6.751, 14.609] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 9.879 ops/ms
# Warmup Iteration   3: 10.423 ops/ms
Iteration   1: 10.372 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.341 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (10.274, 10.341, 10.377), stdev = 0.058
  CI (99.9%): [9.286, 11.396] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.059 ops/ms
# Warmup Iteration   2: 7.835 ops/ms
# Warmup Iteration   3: 7.815 ops/ms
Iteration   1: 7.904 ops/ms
Iteration   2: 8.032 ops/ms
Iteration   3: 8.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.000 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (7.904, 8.000, 8.066), stdev = 0.085
  CI (99.9%): [6.444, 9.557] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.305 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 3.063 ±(99.9%) 0.003 ms/op
Iteration   3: 3.070 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.064 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (3.059, 3.064, 3.070), stdev = 0.006
  CI (99.9%): [2.962, 3.167] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.954, 2.957, 2.963), stdev = 0.005
  CI (99.9%): [2.859, 3.055] (assumes normal distribution)


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.003 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.096 ±(99.9%) 0.440 ms/op [Average]
  (min, avg, max) = (3.076, 3.096, 3.122), stdev = 0.024
  CI (99.9%): [2.655, 3.536] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.689 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.305 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.006 ms/op
Iteration   1: 3.905 ±(99.9%) 0.021 ms/op
Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
Iteration   3: 4.023 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.976 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.905, 3.976, 4.023), stdev = 0.062
  CI (99.9%): [2.838, 5.114] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  9.696 ms/op
                 createUser·p0.9999: 11.603 ms/op
                 createUser·p1.00:   12.091 ms/op

Iteration   2: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  6.627 ms/op
                 createUser·p0.9999: 14.514 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.438 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315694
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18812 
    [ 2.500,  5.000) = 295380 
    [ 5.000,  7.500) = 1091 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     21.782 ms/op
     p(99.9990) =     22.867 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.826 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.007 ms/op
Iteration   1: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.354 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 2.878 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.500 ms/op
                 existUser·p0.999:  5.571 ms/op
                 existUser·p0.9999: 14.090 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  9.301 ms/op
                 existUser·p0.9999: 15.014 ms/op
                 existUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329581
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2318 
    [ 1.250,  2.500) = 40188 
    [ 2.500,  3.750) = 276184 
    [ 3.750,  5.000) = 9860 
    [ 5.000,  6.250) = 566 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     17.731 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.376 ms/op
                 getUser·p0.999:  6.539 ms/op
                 getUser·p0.9999: 11.510 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 19.854 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 18.078 ms/op
                 getUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307725
  mean =      3.119 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14081 
    [ 2.500,  5.000) = 292008 
    [ 5.000,  7.500) = 1250 
    [ 7.500, 10.000) = 228 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.006 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.246 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 5.725 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.010 ms/op
Iteration   1: 3.883 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   7.016 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 19.056 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 3.931 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  14.010 ms/op
                 listUser·p0.9999: 21.782 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.337 ms/op
                 listUser·p0.9999: 16.564 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245001
  mean =      3.919 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4449 
    [ 2.500,  5.000) = 218708 
    [ 5.000,  7.500) = 20642 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     20.857 ms/op
     p(99.9990) =     22.038 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.931 ± 3.189  ops/ms
ClientGrpc.existUser                       thrpt       3  10.680 ± 3.929  ops/ms
ClientGrpc.getUser                         thrpt       3  10.341 ± 1.055  ops/ms
ClientGrpc.listUser                        thrpt       3   8.000 ± 1.556  ops/ms
ClientGrpc.createUser                       avgt       3   3.064 ± 0.103   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.098   ms/op
ClientGrpc.getUser                          avgt       3   3.096 ± 0.440   ms/op
ClientGrpc.listUser                         avgt       3   3.976 ± 1.138   ms/op
ClientGrpc.createUser                     sample  315694   3.044 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.306           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.782           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.003           ms/op
ClientGrpc.existUser                      sample  329581   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.520           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.876           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  307725   3.119 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.633           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.006           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.235           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.644           ms/op
ClientGrpc.listUser                       sample  245001   3.919 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.013           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.222           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.857           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.151           ms/op
