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
# Warmup Iteration   1: 4.252 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.089 ops/ms
Iteration   1: 10.589 ops/ms
Iteration   2: 10.523 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.577 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (10.523, 10.577, 10.618), stdev = 0.049
  CI (99.9%): [9.683, 11.470] (assumes normal distribution)


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
# Warmup Iteration   1: 7.490 ops/ms
# Warmup Iteration   2: 10.625 ops/ms
# Warmup Iteration   3: 11.101 ops/ms
Iteration   1: 10.982 ops/ms
Iteration   2: 11.316 ops/ms
Iteration   3: 11.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.159 ±(99.9%) 3.060 ops/ms [Average]
  (min, avg, max) = (10.982, 11.159, 11.316), stdev = 0.168
  CI (99.9%): [8.098, 14.219] (assumes normal distribution)


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
# Warmup Iteration   1: 7.455 ops/ms
# Warmup Iteration   2: 10.359 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.685 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.690 ±(99.9%) 0.245 ops/ms [Average]
  (min, avg, max) = (10.680, 10.690, 10.705), stdev = 0.013
  CI (99.9%): [10.445, 10.935] (assumes normal distribution)


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
# Warmup Iteration   1: 5.588 ops/ms
# Warmup Iteration   2: 8.035 ops/ms
# Warmup Iteration   3: 8.079 ops/ms
Iteration   1: 8.141 ops/ms
Iteration   2: 8.445 ops/ms
Iteration   3: 8.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.278 ±(99.9%) 2.810 ops/ms [Average]
  (min, avg, max) = (8.141, 8.278, 8.445), stdev = 0.154
  CI (99.9%): [5.467, 11.088] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
Iteration   3: 3.064 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.014, 3.036, 3.064), stdev = 0.025
  CI (99.9%): [2.572, 3.500] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.004 ms/op
Iteration   2: 2.875 ±(99.9%) 0.004 ms/op
Iteration   3: 2.842 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.876 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (2.842, 2.876, 2.912), stdev = 0.035
  CI (99.9%): [2.240, 3.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.058 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.009 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 3.017 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (3.015, 3.020, 3.027), stdev = 0.007
  CI (99.9%): [2.900, 3.139] (assumes normal distribution)


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
# Warmup Iteration   1: 4.932 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.793 ±(99.9%) 0.021 ms/op
Iteration   1: 3.848 ±(99.9%) 0.012 ms/op
Iteration   2: 3.874 ±(99.9%) 0.009 ms/op
Iteration   3: 3.860 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.861 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.848, 3.861, 3.874), stdev = 0.013
  CI (99.9%): [3.623, 4.098] (assumes normal distribution)


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
# Warmup Iteration   1: 4.062 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.960 ms/op
                 createUser·p0.9999: 17.662 ms/op
                 createUser·p1.00:   18.055 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.997 ms/op
                 createUser·p0.9999: 16.045 ms/op
                 createUser·p1.00:   16.499 ms/op

Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.786 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  9.096 ms/op
                 createUser·p0.9999: 15.999 ms/op
                 createUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318653
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1172 
    [ 1.250,  2.500) = 28128 
    [ 2.500,  3.750) = 273030 
    [ 3.750,  5.000) = 14961 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 344 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.787 ms/op
     p(99.9900) =     16.110 ms/op
     p(99.9990) =     17.951 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.007 ms/op
Iteration   1: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.428 ms/op
                 existUser·p0.9999: 11.599 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.675 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.060 ms/op
                 existUser·p0.9999: 14.186 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.871 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.324 ms/op
                 existUser·p0.9999: 14.839 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332276
  mean =      2.887 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2411 
    [ 1.250,  2.500) = 43103 
    [ 2.500,  3.750) = 274925 
    [ 3.750,  5.000) = 10732 
    [ 5.000,  6.250) = 551 
    [ 6.250,  7.500) = 248 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.225 ms/op
     p(99.9900) =     14.431 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.028 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.071 ms/op
                 getUser·p0.9999: 14.247 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.977 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.126 ms/op
                 getUser·p0.9999: 14.127 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.999 ms/op
                 getUser·p0.9999: 15.745 ms/op
                 getUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321385
  mean =      2.986 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1637 
    [ 1.250,  2.500) = 25926 
    [ 2.500,  3.750) = 280806 
    [ 3.750,  5.000) = 11769 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 284 
    [ 7.500,  8.750) = 117 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.727 ms/op
     p(99.9900) =     15.462 ms/op
     p(99.9990) =     16.124 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.011 ms/op
Iteration   1: 3.842 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.364 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.611 ms/op
                 listUser·p0.9999: 18.077 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   2: 3.804 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 23.599 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  16.970 ms/op
                 listUser·p0.9999: 27.865 ms/op
                 listUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249482
  mean =      3.847 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5548 
    [ 2.500,  5.000) = 223054 
    [ 5.000,  7.500) = 19681 
    [ 7.500, 10.000) = 691 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     26.577 ms/op
     p(99.9990) =     28.230 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.577 ± 0.893  ops/ms
ClientGrpc.existUser                       thrpt       3  11.159 ± 3.060  ops/ms
ClientGrpc.getUser                         thrpt       3  10.690 ± 0.245  ops/ms
ClientGrpc.listUser                        thrpt       3   8.278 ± 2.810  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.464   ms/op
ClientGrpc.existUser                        avgt       3   2.876 ± 0.636   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.120   ms/op
ClientGrpc.listUser                         avgt       3   3.861 ± 0.238   ms/op
ClientGrpc.createUser                     sample  318653   3.014 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.787           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.110           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  332276   2.887 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.625           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.225           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  321385   2.986 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.651           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.727           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.462           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.269           ms/op
ClientGrpc.listUser                       sample  249482   3.847 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.748           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.577           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.377           ms/op
