# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.944 ops/ms
# Warmup Iteration   2: 5.426 ops/ms
# Warmup Iteration   3: 8.351 ops/ms
Iteration   1: 9.123 ops/ms
Iteration   2: 9.247 ops/ms
Iteration   3: 8.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.114 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (8.973, 9.114, 9.247), stdev = 0.137
  CI (99.9%): [6.612, 11.616] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.461 ops/ms
# Warmup Iteration   3: 9.513 ops/ms
Iteration   1: 9.546 ops/ms
Iteration   2: 9.534 ops/ms
Iteration   3: 9.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.537 ±(99.9%) 0.144 ops/ms [Average]
  (min, avg, max) = (9.531, 9.537, 9.546), stdev = 0.008
  CI (99.9%): [9.392, 9.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.835 ops/ms
# Warmup Iteration   2: 8.404 ops/ms
# Warmup Iteration   3: 9.028 ops/ms
Iteration   1: 9.179 ops/ms
Iteration   2: 8.808 ops/ms
Iteration   3: 9.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.015 ±(99.9%) 3.459 ops/ms [Average]
  (min, avg, max) = (8.808, 9.015, 9.179), stdev = 0.190
  CI (99.9%): [5.557, 12.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 6.848 ops/ms
# Warmup Iteration   3: 7.714 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 8.088 ops/ms
Iteration   3: 7.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.976 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (7.878, 7.976, 8.088), stdev = 0.106
  CI (99.9%): [6.044, 9.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.799 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.603 ±(99.9%) 0.004 ms/op
Iteration   1: 3.524 ±(99.9%) 0.005 ms/op
Iteration   2: 3.526 ±(99.9%) 0.003 ms/op
Iteration   3: 3.483 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.511 ±(99.9%) 0.438 ms/op [Average]
  (min, avg, max) = (3.483, 3.511, 3.526), stdev = 0.024
  CI (99.9%): [3.073, 3.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.555 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.004 ms/op
Iteration   1: 3.471 ±(99.9%) 0.005 ms/op
Iteration   2: 3.250 ±(99.9%) 0.009 ms/op
Iteration   3: 3.441 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.387 ±(99.9%) 2.183 ms/op [Average]
  (min, avg, max) = (3.250, 3.387, 3.471), stdev = 0.120
  CI (99.9%): [1.204, 5.570] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.866 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.763 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.006 ms/op
Iteration   1: 3.494 ±(99.9%) 0.007 ms/op
Iteration   2: 3.350 ±(99.9%) 0.007 ms/op
Iteration   3: 3.504 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.449 ±(99.9%) 1.567 ms/op [Average]
  (min, avg, max) = (3.350, 3.449, 3.504), stdev = 0.086
  CI (99.9%): [1.882, 5.017] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.091 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 4.203 ±(99.9%) 0.005 ms/op
Iteration   2: 3.981 ±(99.9%) 0.009 ms/op
Iteration   3: 3.942 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.042 ±(99.9%) 2.575 ms/op [Average]
  (min, avg, max) = (3.942, 4.042, 4.203), stdev = 0.141
  CI (99.9%): [1.467, 6.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.830 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.009 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  21.170 ms/op
                 createUser·p0.9999: 23.334 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.614 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  21.271 ms/op
                 createUser·p0.9999: 24.148 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  19.956 ms/op
                 createUser·p0.9999: 27.256 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279427
  mean =      3.433 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12343 
    [ 2.500,  5.000) = 258256 
    [ 5.000,  7.500) = 7803 
    [ 7.500, 10.000) = 613 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     20.550 ms/op
     p(99.9900) =     24.483 ms/op
     p(99.9990) =     28.489 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.582 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.780 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 21.971 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.377 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  19.080 ms/op
                 existUser·p0.9999: 22.612 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 3.482 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.157 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  11.844 ms/op
                 existUser·p0.9999: 36.492 ms/op
                 existUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284054
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8824 
    [ 2.500,  5.000) = 268467 
    [ 5.000,  7.500) = 5982 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     11.810 ms/op
     p(99.9900) =     35.717 ms/op
     p(99.9990) =     38.113 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.351 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.010 ms/op
Iteration   1: 3.544 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.602 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.760 ms/op
                 getUser·p0.999:  21.028 ms/op
                 getUser·p0.9999: 26.771 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.422 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 25.023 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.523 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  23.672 ms/op
                 getUser·p0.9999: 41.021 ms/op
                 getUser·p1.00:   42.074 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274476
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267130 
    [ 5.000, 10.000) = 6981 
    [10.000, 15.000) = 108 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 145 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     39.882 ms/op
     p(99.9990) =     41.501 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.173 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.013 ms/op
Iteration   1: 4.156 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.694 ms/op
                 listUser·p0.999:  21.093 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.051 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  15.699 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.247 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  15.575 ms/op
                 listUser·p0.9999: 21.430 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231355
  mean =      4.150 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 220705 
    [ 5.000,  7.500) = 7846 
    [ 7.500, 10.000) = 2024 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     16.667 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     24.873 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.114 ± 2.502  ops/ms
ClientPb.existUser                       thrpt       3   9.537 ± 0.144  ops/ms
ClientPb.getUser                         thrpt       3   9.015 ± 3.459  ops/ms
ClientPb.listUser                        thrpt       3   7.976 ± 1.932  ops/ms
ClientPb.createUser                       avgt       3   3.511 ± 0.438   ms/op
ClientPb.existUser                        avgt       3   3.387 ± 2.183   ms/op
ClientPb.getUser                          avgt       3   3.449 ± 1.567   ms/op
ClientPb.listUser                         avgt       3   4.042 ± 2.575   ms/op
ClientPb.createUser                     sample  279427   3.433 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.550           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.483           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.967           ms/op
ClientPb.existUser                      sample  284054   3.378 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.157           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.810           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.717           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.191           ms/op
ClientPb.getUser                        sample  274476   3.495 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.030           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.108           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.074           ms/op
ClientPb.listUser                       sample  231355   4.150 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.366           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.231           ms/op
