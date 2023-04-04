# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.111 ops/ms
# Warmup Iteration   2: 4.815 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.656 ops/ms
Iteration   3: 9.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.549 ±(99.9%) 4.458 ops/ms [Average]
  (min, avg, max) = (9.269, 9.549, 9.721), stdev = 0.244
  CI (99.9%): [5.091, 14.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.747 ops/ms
# Warmup Iteration   2: 8.312 ops/ms
# Warmup Iteration   3: 9.143 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 9.825 ops/ms
Iteration   3: 9.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.842 ±(99.9%) 2.275 ops/ms [Average]
  (min, avg, max) = (9.728, 9.842, 9.975), stdev = 0.125
  CI (99.9%): [7.568, 12.117] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ops/ms
# Warmup Iteration   2: 8.569 ops/ms
# Warmup Iteration   3: 9.117 ops/ms
Iteration   1: 8.948 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.302 ±(99.9%) 5.705 ops/ms [Average]
  (min, avg, max) = (8.948, 9.302, 9.540), stdev = 0.313
  CI (99.9%): [3.597, 15.007] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 7.237 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.014 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 8.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.060 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (7.991, 8.060, 8.174), stdev = 0.100
  CI (99.9%): [6.236, 9.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.090 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.012 ms/op
Iteration   1: 3.429 ±(99.9%) 0.011 ms/op
Iteration   2: 3.373 ±(99.9%) 0.005 ms/op
Iteration   3: 3.393 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.398 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.373, 3.398, 3.429), stdev = 0.028
  CI (99.9%): [2.887, 3.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.162 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.004 ms/op
Iteration   1: 3.315 ±(99.9%) 0.004 ms/op
Iteration   2: 3.300 ±(99.9%) 0.003 ms/op
Iteration   3: 3.307 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.308 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.300, 3.308, 3.315), stdev = 0.008
  CI (99.9%): [3.170, 3.446] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.297 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.008 ms/op
Iteration   1: 3.514 ±(99.9%) 0.004 ms/op
Iteration   2: 3.300 ±(99.9%) 0.009 ms/op
Iteration   3: 3.471 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 2.060 ms/op [Average]
  (min, avg, max) = (3.300, 3.428, 3.514), stdev = 0.113
  CI (99.9%): [1.368, 5.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.155 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.010 ms/op
Iteration   1: 4.245 ±(99.9%) 0.006 ms/op
Iteration   2: 3.964 ±(99.9%) 0.004 ms/op
Iteration   3: 4.121 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.110 ±(99.9%) 2.574 ms/op [Average]
  (min, avg, max) = (3.964, 4.110, 4.245), stdev = 0.141
  CI (99.9%): [1.536, 6.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.251 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.011 ms/op
Iteration   1: 3.744 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.937 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  17.367 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.418 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  24.672 ms/op
                 createUser·p0.9999: 29.829 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.376 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  24.728 ms/op
                 createUser·p0.9999: 32.244 ms/op
                 createUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273648
  mean =      3.506 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18358 
    [ 2.500,  5.000) = 244135 
    [ 5.000,  7.500) = 9053 
    [ 7.500, 10.000) = 1511 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     30.176 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.742 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.010 ms/op
Iteration   1: 3.285 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  18.687 ms/op
                 existUser·p0.9999: 27.001 ms/op
                 existUser·p1.00:   28.246 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  16.439 ms/op
                 existUser·p0.9999: 24.084 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.346 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 33.194 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291151
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12723 
    [ 2.500,  5.000) = 272761 
    [ 5.000,  7.500) = 4723 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     32.043 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.010 ms/op
Iteration   1: 3.486 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  19.891 ms/op
                 getUser·p0.9999: 23.455 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  22.708 ms/op
                 getUser·p0.9999: 25.351 ms/op
                 getUser·p1.00:   26.345 ms/op

Iteration   3: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 28.115 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279296
  mean =      3.438 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3097 
    [ 2.500,  5.000) = 268997 
    [ 5.000,  7.500) = 6158 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     27.036 ms/op
     p(99.9990) =     28.602 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.419 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.015 ms/op
Iteration   1: 4.083 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  21.549 ms/op
                 listUser·p0.9999: 24.314 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 4.092 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 18.389 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   3: 3.919 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.008 ms/op
                 listUser·p0.9999: 17.656 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238205
  mean =      4.030 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 230046 
    [ 5.000,  7.500) = 5584 
    [ 7.500, 10.000) = 1606 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     16.495 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.644 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.549 ± 4.458  ops/ms
ClientPb.existUser                       thrpt       3   9.842 ± 2.275  ops/ms
ClientPb.getUser                         thrpt       3   9.302 ± 5.705  ops/ms
ClientPb.listUser                        thrpt       3   8.060 ± 1.824  ops/ms
ClientPb.createUser                       avgt       3   3.398 ± 0.511   ms/op
ClientPb.existUser                        avgt       3   3.308 ± 0.138   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 2.060   ms/op
ClientPb.listUser                         avgt       3   4.110 ± 2.574   ms/op
ClientPb.createUser                     sample  273648   3.506 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.332           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.367           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.176           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.899           ms/op
ClientPb.existUser                      sample  291151   3.296 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.262           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.793           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.043           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  279296   3.438 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.307           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.349           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.036           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  238205   4.030 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.495           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.199           ms/op
