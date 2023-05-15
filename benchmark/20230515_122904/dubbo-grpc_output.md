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
# Warmup Iteration   1: 4.016 ops/ms
# Warmup Iteration   2: 8.831 ops/ms
# Warmup Iteration   3: 10.352 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.566 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.600 ±(99.9%) 0.601 ops/ms [Average]
  (min, avg, max) = (10.566, 10.600, 10.632), stdev = 0.033
  CI (99.9%): [9.999, 11.201] (assumes normal distribution)


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
# Warmup Iteration   1: 7.310 ops/ms
# Warmup Iteration   2: 10.860 ops/ms
# Warmup Iteration   3: 11.029 ops/ms
Iteration   1: 11.043 ops/ms
Iteration   2: 11.561 ops/ms
Iteration   3: 11.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.274 ±(99.9%) 4.803 ops/ms [Average]
  (min, avg, max) = (11.043, 11.274, 11.561), stdev = 0.263
  CI (99.9%): [6.472, 16.077] (assumes normal distribution)


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
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 10.257 ops/ms
# Warmup Iteration   3: 10.780 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.774 ops/ms
Iteration   3: 10.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.661 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (10.576, 10.661, 10.774), stdev = 0.102
  CI (99.9%): [8.799, 12.524] (assumes normal distribution)


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
# Warmup Iteration   1: 5.462 ops/ms
# Warmup Iteration   2: 7.760 ops/ms
# Warmup Iteration   3: 7.778 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.007 ±(99.9%) 1.345 ops/ms [Average]
  (min, avg, max) = (7.941, 8.007, 8.086), stdev = 0.074
  CI (99.9%): [6.662, 9.352] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.014 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.994, 3.014, 3.025), stdev = 0.017
  CI (99.9%): [2.698, 3.330] (assumes normal distribution)


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.001 ms/op
Iteration   1: 2.856 ±(99.9%) 0.003 ms/op
Iteration   2: 2.906 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (2.856, 2.894, 2.919), stdev = 0.033
  CI (99.9%): [2.287, 3.501] (assumes normal distribution)


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 2.986 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.016 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (2.986, 3.016, 3.049), stdev = 0.032
  CI (99.9%): [2.435, 3.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.185 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.022 ms/op
Iteration   1: 3.963 ±(99.9%) 0.017 ms/op
Iteration   2: 3.922 ±(99.9%) 0.019 ms/op
Iteration   3: 3.938 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.941 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.922, 3.941, 3.963), stdev = 0.021
  CI (99.9%): [3.559, 4.323] (assumes normal distribution)


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
# Warmup Iteration   1: 4.287 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 3.068 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.037 ms/op
                 createUser·p0.9999: 12.733 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.689 ms/op
                 createUser·p0.9999: 16.035 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.287 ms/op
                 createUser·p0.999:  8.454 ms/op
                 createUser·p0.9999: 19.104 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317551
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 668 
    [ 1.250,  2.500) = 22685 
    [ 2.500,  3.750) = 278374 
    [ 3.750,  5.000) = 14156 
    [ 5.000,  6.250) = 899 
    [ 6.250,  7.500) = 329 
    [ 7.500,  8.750) = 179 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 78 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.006 ms/op
Iteration   1: 2.835 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  6.603 ms/op
                 existUser·p0.9999: 13.971 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.897 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 14.074 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.602 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.173 ms/op
                 existUser·p0.999:  8.647 ms/op
                 existUser·p0.9999: 15.993 ms/op
                 existUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332818
  mean =      2.882 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 53215 
    [ 2.500,  3.750) = 271931 
    [ 3.750,  5.000) = 6193 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     14.372 ms/op
     p(99.9990) =     16.215 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.107 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.045 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.069 ms/op
                 getUser·p0.9999: 12.583 ms/op
                 getUser·p1.00:   12.812 ms/op

Iteration   2: 2.974 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  7.360 ms/op
                 getUser·p0.9999: 14.344 ms/op
                 getUser·p1.00:   15.188 ms/op

Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.778 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.530 ms/op
                 getUser·p0.99:   4.088 ms/op
                 getUser·p0.999:  6.521 ms/op
                 getUser·p0.9999: 18.359 ms/op
                 getUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321682
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1552 
    [ 1.250,  2.500) = 28585 
    [ 2.500,  3.750) = 276733 
    [ 3.750,  5.000) = 13249 
    [ 5.000,  6.250) = 914 
    [ 6.250,  7.500) = 353 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     16.627 ms/op
     p(99.9990) =     18.689 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 5.505 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.020 ±(99.9%) 0.011 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.944 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 18.480 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.696 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.263 ms/op
                 listUser·p0.9999: 20.750 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240656
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3889 
    [ 2.500,  5.000) = 209459 
    [ 5.000,  7.500) = 25878 
    [ 7.500, 10.000) = 1030 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     20.080 ms/op
     p(99.9990) =     21.515 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.600 ± 0.601  ops/ms
ClientGrpc.existUser                       thrpt       3  11.274 ± 4.803  ops/ms
ClientGrpc.getUser                         thrpt       3  10.661 ± 1.862  ops/ms
ClientGrpc.listUser                        thrpt       3   8.007 ± 1.345  ops/ms
ClientGrpc.createUser                       avgt       3   3.014 ± 0.316   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.607   ms/op
ClientGrpc.getUser                          avgt       3   3.016 ± 0.581   ms/op
ClientGrpc.listUser                         avgt       3   3.941 ± 0.382   ms/op
ClientGrpc.createUser                     sample  317551   3.021 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.728           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.448           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  332818   2.882 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.602           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.372           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.237           ms/op
ClientGrpc.getUser                        sample  321682   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.356           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.809           ms/op
ClientGrpc.listUser                       sample  240656   3.988 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.080           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.627           ms/op
