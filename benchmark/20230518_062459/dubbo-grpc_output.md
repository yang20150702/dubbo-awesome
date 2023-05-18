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
# Warmup Iteration   1: 3.664 ops/ms
# Warmup Iteration   2: 8.361 ops/ms
# Warmup Iteration   3: 9.939 ops/ms
Iteration   1: 10.464 ops/ms
Iteration   2: 10.551 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.531 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (10.464, 10.531, 10.579), stdev = 0.060
  CI (99.9%): [9.439, 11.624] (assumes normal distribution)


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
# Warmup Iteration   1: 7.044 ops/ms
# Warmup Iteration   2: 10.418 ops/ms
# Warmup Iteration   3: 11.002 ops/ms
Iteration   1: 11.119 ops/ms
Iteration   2: 11.147 ops/ms
Iteration   3: 11.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.116 ±(99.9%) 0.588 ops/ms [Average]
  (min, avg, max) = (11.082, 11.116, 11.147), stdev = 0.032
  CI (99.9%): [10.528, 11.704] (assumes normal distribution)


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
# Warmup Iteration   1: 6.431 ops/ms
# Warmup Iteration   2: 9.950 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.499 ±(99.9%) 1.632 ops/ms [Average]
  (min, avg, max) = (10.424, 10.499, 10.598), stdev = 0.089
  CI (99.9%): [8.867, 12.131] (assumes normal distribution)


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
# Warmup Iteration   1: 5.332 ops/ms
# Warmup Iteration   2: 7.788 ops/ms
# Warmup Iteration   3: 7.824 ops/ms
Iteration   1: 7.754 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 7.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.844 ±(99.9%) 1.436 ops/ms [Average]
  (min, avg, max) = (7.754, 7.844, 7.898), stdev = 0.079
  CI (99.9%): [6.409, 9.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.001 ms/op
Iteration   2: 3.057 ±(99.9%) 0.002 ms/op
Iteration   3: 3.061 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (3.057, 3.068, 3.086), stdev = 0.015
  CI (99.9%): [2.787, 3.349] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.002 ms/op
Iteration   1: 2.975 ±(99.9%) 0.001 ms/op
Iteration   2: 2.899 ±(99.9%) 0.003 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.938 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (2.899, 2.938, 2.975), stdev = 0.038
  CI (99.9%): [2.241, 3.634] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.323 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.166 ±(99.9%) 0.010 ms/op
Iteration   1: 3.102 ±(99.9%) 0.003 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.072, 3.104, 3.137), stdev = 0.032
  CI (99.9%): [2.514, 3.694] (assumes normal distribution)


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
# Warmup Iteration   1: 6.033 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.056 ms/op
Iteration   1: 4.081 ±(99.9%) 0.008 ms/op
Iteration   2: 4.005 ±(99.9%) 0.020 ms/op
Iteration   3: 4.002 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.029 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (4.002, 4.029, 4.081), stdev = 0.045
  CI (99.9%): [3.214, 4.845] (assumes normal distribution)


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.092 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.891 ms/op
                 createUser·p0.999:  9.175 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   2: 3.088 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  11.508 ms/op
                 createUser·p0.9999: 33.728 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  11.824 ms/op
                 createUser·p0.9999: 26.559 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311822
  mean =      3.077 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22899 
    [ 2.500,  5.000) = 285819 
    [ 5.000,  7.500) = 2302 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     32.139 ms/op
     p(99.9990) =     33.882 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.911 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.411 ms/op
                 existUser·p0.999:  7.087 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 2.898 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 14.450 ms/op
                 existUser·p1.00:   18.121 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   7.004 ms/op
                 existUser·p0.999:  9.372 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327449
  mean =      2.931 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1116 
    [ 1.250,  2.500) = 37704 
    [ 2.500,  3.750) = 275515 
    [ 3.750,  5.000) = 9591 
    [ 5.000,  6.250) = 1305 
    [ 6.250,  7.500) = 1300 
    [ 7.500,  8.750) = 488 
    [ 8.750, 10.000) = 150 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =      9.643 ms/op
     p(99.9900) =     17.310 ms/op
     p(99.9990) =     17.915 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.463 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.868 ms/op
                 getUser·p0.9999: 28.889 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.728 ms/op
                 getUser·p0.9999: 17.490 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  9.044 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315781
  mean =      3.040 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21324 
    [ 2.500,  5.000) = 292720 
    [ 5.000,  7.500) = 1320 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.308 ms/op
     p(99.9900) =     27.872 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 5.116 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
Iteration   1: 4.003 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.027 ms/op
                 listUser·p0.999:  14.041 ms/op
                 listUser·p0.9999: 22.381 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   2: 3.807 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  16.155 ms/op
                 listUser·p0.9999: 21.522 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.389 ms/op
                 listUser·p0.9999: 26.864 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245589
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4319 
    [ 2.500,  5.000) = 215796 
    [ 5.000,  7.500) = 23705 
    [ 7.500, 10.000) = 1370 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.677 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.531 ± 1.093  ops/ms
ClientGrpc.existUser                       thrpt       3  11.116 ± 0.588  ops/ms
ClientGrpc.getUser                         thrpt       3  10.499 ± 1.632  ops/ms
ClientGrpc.listUser                        thrpt       3   7.844 ± 1.436  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 0.281   ms/op
ClientGrpc.existUser                        avgt       3   2.938 ± 0.696   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.590   ms/op
ClientGrpc.listUser                         avgt       3   4.029 ± 0.815   ms/op
ClientGrpc.createUser                     sample  311822   3.077 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.756           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.420           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.139           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.948           ms/op
ClientGrpc.existUser                      sample  327449   2.931 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.643           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.310           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.121           ms/op
ClientGrpc.getUser                        sample  315781   3.040 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.700           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.308           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.872           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.360           ms/op
ClientGrpc.listUser                       sample  245589   3.908 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.853           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.925           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.280           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
