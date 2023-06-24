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
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 9.150 ops/ms
# Warmup Iteration   3: 9.990 ops/ms
Iteration   1: 10.473 ops/ms
Iteration   2: 10.886 ops/ms
Iteration   3: 10.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.599 ±(99.9%) 4.542 ops/ms [Average]
  (min, avg, max) = (10.438, 10.599, 10.886), stdev = 0.249
  CI (99.9%): [6.057, 15.142] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.602 ops/ms
# Warmup Iteration   2: 10.515 ops/ms
# Warmup Iteration   3: 11.062 ops/ms
Iteration   1: 10.873 ops/ms
Iteration   2: 11.203 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.049 ±(99.9%) 3.031 ops/ms [Average]
  (min, avg, max) = (10.873, 11.049, 11.203), stdev = 0.166
  CI (99.9%): [8.018, 14.079] (assumes normal distribution)


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
# Warmup Iteration   1: 6.709 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.488 ops/ms
Iteration   1: 10.639 ops/ms
Iteration   2: 10.450 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.565 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (10.450, 10.565, 10.639), stdev = 0.101
  CI (99.9%): [8.722, 12.407] (assumes normal distribution)


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
# Warmup Iteration   1: 5.482 ops/ms
# Warmup Iteration   2: 7.658 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 7.905 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.007 ±(99.9%) 1.989 ops/ms [Average]
  (min, avg, max) = (7.905, 8.007, 8.122), stdev = 0.109
  CI (99.9%): [6.019, 9.996] (assumes normal distribution)


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.004 ms/op
Iteration   1: 3.062 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
Iteration   3: 2.997 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (2.997, 3.021, 3.062), stdev = 0.036
  CI (99.9%): [2.373, 3.669] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.920 ±(99.9%) 0.002 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.829 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (2.829, 2.894, 2.933), stdev = 0.056
  CI (99.9%): [1.864, 3.925] (assumes normal distribution)


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
# Warmup Iteration   1: 4.188 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (2.988, 3.019, 3.045), stdev = 0.029
  CI (99.9%): [2.497, 3.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.772 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 4.010 ±(99.9%) 0.008 ms/op
Iteration   2: 3.974 ±(99.9%) 0.019 ms/op
Iteration   3: 4.026 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.003 ±(99.9%) 0.483 ms/op [Average]
  (min, avg, max) = (3.974, 4.003, 4.026), stdev = 0.026
  CI (99.9%): [3.520, 4.487] (assumes normal distribution)


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  10.183 ms/op
                 createUser·p0.9999: 13.887 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  13.439 ms/op
                 createUser·p0.9999: 18.475 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.323 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   5.637 ms/op
                 createUser·p0.999:  9.487 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310849
  mean =      3.087 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 20682 
    [ 2.500,  3.750) = 265403 
    [ 3.750,  5.000) = 21308 
    [ 5.000,  6.250) = 1613 
    [ 6.250,  7.500) = 675 
    [ 7.500,  8.750) = 392 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     10.387 ms/op
     p(99.9900) =     17.725 ms/op
     p(99.9990) =     19.308 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.287 ms/op
                 existUser·p0.999:  7.241 ms/op
                 existUser·p0.9999: 13.501 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.860 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.269 ms/op
                 existUser·p0.9999: 17.558 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 2.863 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.780 ms/op
                 existUser·p0.9999: 23.932 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332858
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45319 
    [ 2.500,  5.000) = 286152 
    [ 5.000,  7.500) = 1007 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     18.280 ms/op
     p(99.9990) =     24.139 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 4.477 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.175 ms/op
                 getUser·p0.9999: 17.277 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  8.039 ms/op
                 getUser·p0.9999: 17.735 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  10.090 ms/op
                 getUser·p0.9999: 21.045 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319209
  mean =      3.008 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25246 
    [ 2.500,  5.000) = 291957 
    [ 5.000,  7.500) = 1505 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =      8.847 ms/op
     p(99.9900) =     20.417 ms/op
     p(99.9990) =     21.713 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.405 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.012 ms/op
Iteration   1: 3.985 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.366 ms/op
                 listUser·p0.999:  16.433 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 4.039 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.559 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  16.527 ms/op
                 listUser·p0.9999: 22.134 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 3.964 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.842 ms/op
                 listUser·p0.9999: 22.476 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240414
  mean =      3.996 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2301 
    [ 2.500,  5.000) = 212771 
    [ 5.000,  7.500) = 23763 
    [ 7.500, 10.000) = 1151 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     16.698 ms/op
     p(99.9900) =     22.281 ms/op
     p(99.9990) =     22.780 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.599 ± 4.542  ops/ms
ClientGrpc.existUser                       thrpt       3  11.049 ± 3.031  ops/ms
ClientGrpc.getUser                         thrpt       3  10.565 ± 1.842  ops/ms
ClientGrpc.listUser                        thrpt       3   8.007 ± 1.989  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.648   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 1.031   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 0.521   ms/op
ClientGrpc.listUser                         avgt       3   4.003 ± 0.483   ms/op
ClientGrpc.createUser                     sample  310849   3.087 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.323           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.928           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.989           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.387           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.725           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  332858   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.741           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.280           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.051           ms/op
ClientGrpc.getUser                        sample  319209   3.008 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.640           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.417           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  240414   3.996 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.559           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.698           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.281           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
