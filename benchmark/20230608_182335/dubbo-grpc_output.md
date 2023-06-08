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
# Warmup Iteration   1: 4.876 ops/ms
# Warmup Iteration   2: 9.267 ops/ms
# Warmup Iteration   3: 10.193 ops/ms
Iteration   1: 10.452 ops/ms
Iteration   2: 10.712 ops/ms
Iteration   3: 10.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.616 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (10.452, 10.616, 10.712), stdev = 0.143
  CI (99.9%): [8.009, 13.222] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ops/ms
# Warmup Iteration   2: 11.019 ops/ms
# Warmup Iteration   3: 11.209 ops/ms
Iteration   1: 11.187 ops/ms
Iteration   2: 11.685 ops/ms
Iteration   3: 11.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.428 ±(99.9%) 4.547 ops/ms [Average]
  (min, avg, max) = (11.187, 11.428, 11.685), stdev = 0.249
  CI (99.9%): [6.881, 15.975] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.326 ops/ms
# Warmup Iteration   2: 10.488 ops/ms
# Warmup Iteration   3: 10.837 ops/ms
Iteration   1: 10.964 ops/ms
Iteration   2: 10.861 ops/ms
Iteration   3: 11.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.947 ±(99.9%) 1.444 ops/ms [Average]
  (min, avg, max) = (10.861, 10.947, 11.017), stdev = 0.079
  CI (99.9%): [9.503, 12.392] (assumes normal distribution)


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
# Warmup Iteration   1: 5.976 ops/ms
# Warmup Iteration   2: 7.619 ops/ms
# Warmup Iteration   3: 7.974 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 8.180 ops/ms
Iteration   3: 8.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.096 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (8.014, 8.096, 8.180), stdev = 0.083
  CI (99.9%): [6.577, 9.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (2.985, 3.019, 3.063), stdev = 0.040
  CI (99.9%): [2.290, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.004 ms/op
Iteration   1: 2.825 ±(99.9%) 0.003 ms/op
Iteration   2: 2.795 ±(99.9%) 0.003 ms/op
Iteration   3: 2.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.829 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (2.795, 2.829, 2.868), stdev = 0.037
  CI (99.9%): [2.160, 3.499] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.868 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.024 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.002 ms/op
Iteration   1: 2.977 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.971 ±(99.9%) 0.338 ms/op [Average]
  (min, avg, max) = (2.951, 2.971, 2.986), stdev = 0.019
  CI (99.9%): [2.634, 3.309] (assumes normal distribution)


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
# Warmup Iteration   1: 4.888 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.025 ms/op
Iteration   1: 3.894 ±(99.9%) 0.017 ms/op
Iteration   2: 3.927 ±(99.9%) 0.015 ms/op
Iteration   3: 3.955 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.925 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.894, 3.925, 3.955), stdev = 0.030
  CI (99.9%): [3.371, 4.479] (assumes normal distribution)


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
# Warmup Iteration   1: 3.995 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.919 ±(99.9%) 0.005 ms/op
Iteration   1: 2.935 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.301 ms/op
                 createUser·p0.95:   3.445 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.292 ms/op
                 createUser·p0.9999: 16.977 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.722 ms/op
                 createUser·p0.9999: 15.518 ms/op
                 createUser·p1.00:   17.957 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.819 ms/op
                 createUser·p0.9999: 23.405 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325464
  mean =      2.948 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29210 
    [ 2.500,  5.000) = 295072 
    [ 5.000,  7.500) = 674 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     19.591 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 3.735 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.006 ms/op
Iteration   1: 2.876 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.305 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 12.400 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.880 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.591 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  9.879 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 2.833 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.521 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 14.937 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335378
  mean =      2.863 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4861 
    [ 1.250,  2.500) = 42610 
    [ 2.500,  3.750) = 277429 
    [ 3.750,  5.000) = 9285 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     15.497 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.994 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.257 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.283 ms/op
                 getUser·p0.9999: 11.988 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.775 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.614 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.832 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318994
  mean =      3.009 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26333 
    [ 2.500,  5.000) = 291336 
    [ 5.000,  7.500) = 1046 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.103 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     20.205 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 4.216 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.002 ms/op
                 listUser·p0.9999: 17.694 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 25.227 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.699 ms/op
                 listUser·p0.999:  16.002 ms/op
                 listUser·p0.9999: 27.902 ms/op
                 listUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242204
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4105 
    [ 2.500,  5.000) = 217060 
    [ 5.000,  7.500) = 19812 
    [ 7.500, 10.000) = 740 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     15.283 ms/op
     p(99.9900) =     23.913 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.616 ± 2.607  ops/ms
ClientGrpc.existUser                       thrpt       3  11.428 ± 4.547  ops/ms
ClientGrpc.getUser                         thrpt       3  10.947 ± 1.444  ops/ms
ClientGrpc.listUser                        thrpt       3   8.096 ± 1.520  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 0.728   ms/op
ClientGrpc.existUser                        avgt       3   2.829 ± 0.669   ms/op
ClientGrpc.getUser                          avgt       3   2.971 ± 0.338   ms/op
ClientGrpc.listUser                         avgt       3   3.925 ± 0.554   ms/op
ClientGrpc.createUser                     sample  325464   2.948 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.977           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.591           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.691           ms/op
ClientGrpc.existUser                      sample  335378   2.863 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.208           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.497           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.269           ms/op
ClientGrpc.getUser                        sample  318994   3.009 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.257           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.103           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.088           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  242204   3.963 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.923           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.283           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.913           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
