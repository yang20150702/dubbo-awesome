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
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 8.947 ops/ms
# Warmup Iteration   3: 10.028 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.322 ops/ms
Iteration   3: 10.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.354 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (10.265, 10.354, 10.475), stdev = 0.109
  CI (99.9%): [8.369, 12.340] (assumes normal distribution)


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
# Warmup Iteration   1: 7.692 ops/ms
# Warmup Iteration   2: 10.697 ops/ms
# Warmup Iteration   3: 10.990 ops/ms
Iteration   1: 10.941 ops/ms
Iteration   2: 11.228 ops/ms
Iteration   3: 11.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.159 ±(99.9%) 3.522 ops/ms [Average]
  (min, avg, max) = (10.941, 11.159, 11.307), stdev = 0.193
  CI (99.9%): [7.637, 14.680] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.822 ops/ms
# Warmup Iteration   2: 10.232 ops/ms
# Warmup Iteration   3: 10.577 ops/ms
Iteration   1: 10.634 ops/ms
Iteration   2: 10.391 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.524 ±(99.9%) 2.248 ops/ms [Average]
  (min, avg, max) = (10.391, 10.524, 10.634), stdev = 0.123
  CI (99.9%): [8.276, 12.772] (assumes normal distribution)


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
# Warmup Iteration   1: 5.457 ops/ms
# Warmup Iteration   2: 7.954 ops/ms
# Warmup Iteration   3: 7.948 ops/ms
Iteration   1: 8.152 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.127 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (8.061, 8.127, 8.166), stdev = 0.057
  CI (99.9%): [7.085, 9.168] (assumes normal distribution)


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
# Warmup Iteration   1: 4.051 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.004 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.015 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (2.995, 3.015, 3.054), stdev = 0.034
  CI (99.9%): [2.399, 3.631] (assumes normal distribution)


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.004 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.896 ±(99.9%) 0.004 ms/op
Iteration   3: 2.830 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (2.830, 2.891, 2.948), stdev = 0.059
  CI (99.9%): [1.815, 3.968] (assumes normal distribution)


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
# Warmup Iteration   1: 4.089 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.003 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.023, 3.029, 3.038), stdev = 0.008
  CI (99.9%): [2.883, 3.176] (assumes normal distribution)


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.010 ms/op
Iteration   1: 3.972 ±(99.9%) 0.008 ms/op
Iteration   2: 3.994 ±(99.9%) 0.025 ms/op
Iteration   3: 3.925 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.964 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.925, 3.964, 3.994), stdev = 0.035
  CI (99.9%): [3.325, 4.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
Iteration   1: 2.992 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.519 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 24.945 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   2: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.381 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.282 ms/op
                 createUser·p0.9999: 24.518 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.359 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.600 ms/op
                 createUser·p0.999:  6.933 ms/op
                 createUser·p0.9999: 24.531 ms/op
                 createUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321502
  mean =      2.987 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25628 
    [ 2.500,  5.000) = 294081 
    [ 5.000,  7.500) = 1513 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      7.201 ms/op
     p(99.9900) =     24.768 ms/op
     p(99.9990) =     27.455 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  8.831 ms/op
                 existUser·p0.9999: 13.205 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.869 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.128 ms/op
                 existUser·p0.9999: 16.180 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.617 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.072 ms/op
                 existUser·p0.9999: 18.354 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330413
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3341 
    [ 1.250,  2.500) = 40084 
    [ 2.500,  3.750) = 274395 
    [ 3.750,  5.000) = 11560 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 199 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.993 ms/op
     p(99.9900) =     17.349 ms/op
     p(99.9990) =     19.258 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.677 ms/op
                 getUser·p0.9999: 14.156 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  8.741 ms/op
                 getUser·p0.9999: 20.071 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.300 ms/op
                 getUser·p0.9999: 14.861 ms/op
                 getUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314314
  mean =      3.054 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20903 
    [ 2.500,  5.000) = 292233 
    [ 5.000,  7.500) = 886 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.272 ms/op
     p(99.9900) =     19.305 ms/op
     p(99.9990) =     20.344 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.031 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.009 ms/op
Iteration   1: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  11.712 ms/op
                 listUser·p0.9999: 18.576 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   2: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.435 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.053 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   3: 3.941 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.895 ms/op
                 listUser·p0.9999: 22.536 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243011
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4122 
    [ 2.500,  5.000) = 217525 
    [ 5.000,  7.500) = 20119 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     21.869 ms/op
     p(99.9990) =     23.040 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.354 ± 1.985  ops/ms
ClientGrpc.existUser                       thrpt       3  11.159 ± 3.522  ops/ms
ClientGrpc.getUser                         thrpt       3  10.524 ± 2.248  ops/ms
ClientGrpc.listUser                        thrpt       3   8.127 ± 1.042  ops/ms
ClientGrpc.createUser                       avgt       3   3.015 ± 0.616   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 1.077   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.147   ms/op
ClientGrpc.listUser                         avgt       3   3.964 ± 0.639   ms/op
ClientGrpc.createUser                     sample  321502   2.987 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.359           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.201           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.768           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.886           ms/op
ClientGrpc.existUser                      sample  330413   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.564           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.993           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.349           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  314314   3.054 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.683           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.272           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.305           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  243011   3.955 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.435           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.861           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.869           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.101           ms/op
