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
# Warmup Iteration   1: 2.878 ops/ms
# Warmup Iteration   2: 8.052 ops/ms
# Warmup Iteration   3: 9.883 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.260 ops/ms
Iteration   3: 10.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.308 ±(99.9%) 0.774 ops/ms [Average]
  (min, avg, max) = (10.260, 10.308, 10.341), stdev = 0.042
  CI (99.9%): [9.534, 11.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.004 ops/ms
# Warmup Iteration   2: 10.599 ops/ms
# Warmup Iteration   3: 10.910 ops/ms
Iteration   1: 10.911 ops/ms
Iteration   2: 11.037 ops/ms
Iteration   3: 10.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.947 ±(99.9%) 1.425 ops/ms [Average]
  (min, avg, max) = (10.894, 10.947, 11.037), stdev = 0.078
  CI (99.9%): [9.523, 12.372] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.933 ops/ms
# Warmup Iteration   2: 10.085 ops/ms
# Warmup Iteration   3: 10.463 ops/ms
Iteration   1: 10.369 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.437 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (10.369, 10.437, 10.532), stdev = 0.085
  CI (99.9%): [8.895, 11.980] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.168 ops/ms
# Warmup Iteration   2: 7.528 ops/ms
# Warmup Iteration   3: 7.763 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.961 ±(99.9%) 1.636 ops/ms [Average]
  (min, avg, max) = (7.861, 7.961, 8.035), stdev = 0.090
  CI (99.9%): [6.325, 9.597] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.002 ms/op
Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (3.019, 3.048, 3.089), stdev = 0.037
  CI (99.9%): [2.381, 3.715] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.133 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.002 ms/op
Iteration   3: 2.926 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.926, 2.950, 2.963), stdev = 0.021
  CI (99.9%): [2.563, 3.337] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.434 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.004 ms/op
Iteration   1: 3.060 ±(99.9%) 0.003 ms/op
Iteration   2: 3.071 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (3.060, 3.066, 3.071), stdev = 0.006
  CI (99.9%): [2.965, 3.167] (assumes normal distribution)


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.011 ms/op
Iteration   1: 4.093 ±(99.9%) 0.021 ms/op
Iteration   2: 4.027 ±(99.9%) 0.012 ms/op
Iteration   3: 3.995 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.995, 4.038, 4.093), stdev = 0.050
  CI (99.9%): [3.127, 4.950] (assumes normal distribution)


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
# Warmup Iteration   1: 4.524 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  12.141 ms/op
                 createUser·p0.9999: 13.281 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.064 ms/op
                 createUser·p0.9999: 14.916 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   3: 3.082 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.612 ms/op
                 createUser·p0.999:  12.589 ms/op
                 createUser·p0.9999: 18.600 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313304
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 627 
    [ 1.250,  2.500) = 15640 
    [ 2.500,  3.750) = 281956 
    [ 3.750,  5.000) = 13195 
    [ 5.000,  6.250) = 1027 
    [ 6.250,  7.500) = 272 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 175 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     18.837 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.867 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  6.532 ms/op
                 existUser·p0.9999: 13.118 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  8.333 ms/op
                 existUser·p0.9999: 16.945 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  11.738 ms/op
                 existUser·p0.9999: 18.702 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327869
  mean =      2.927 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1800 
    [ 1.250,  2.500) = 32032 
    [ 2.500,  3.750) = 284344 
    [ 3.750,  5.000) = 8700 
    [ 5.000,  6.250) = 393 
    [ 6.250,  7.500) = 226 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.205 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     18.832 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.332 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 15.811 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   2: 3.083 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.196 ms/op
                 getUser·p0.9999: 14.926 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.779 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312234
  mean =      3.073 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 679 
    [ 1.250,  2.500) = 17323 
    [ 2.500,  3.750) = 273128 
    [ 3.750,  5.000) = 19372 
    [ 5.000,  6.250) = 1123 
    [ 6.250,  7.500) = 291 
    [ 7.500,  8.750) = 97 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.551 ms/op
     p(99.9900) =     16.564 ms/op
     p(99.9990) =     17.527 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 5.781 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.011 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.254 ms/op
                 listUser·p0.999:  13.844 ms/op
                 listUser·p0.9999: 17.537 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.902 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.042 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  16.914 ms/op
                 listUser·p0.9999: 30.968 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237786
  mean =      4.038 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2408 
    [ 2.500,  5.000) = 211161 
    [ 5.000,  7.500) = 22556 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 210 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     15.011 ms/op
     p(99.9900) =     29.997 ms/op
     p(99.9990) =     31.408 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.308 ± 0.774  ops/ms
ClientGrpc.existUser                       thrpt       3  10.947 ± 1.425  ops/ms
ClientGrpc.getUser                         thrpt       3  10.437 ± 1.543  ops/ms
ClientGrpc.listUser                        thrpt       3   7.961 ± 1.636  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.667   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.387   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.101   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 0.911   ms/op
ClientGrpc.createUser                     sample  313304   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.510           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.091           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.005           ms/op
ClientGrpc.existUser                      sample  327869   2.927 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.205           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  312234   3.073 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.498           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.551           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.564           ms/op
ClientGrpc.listUser                       sample  237786   4.038 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.120           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.011           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.997           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
