# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.930 ops/ms
# Warmup Iteration   2: 4.493 ops/ms
# Warmup Iteration   3: 8.366 ops/ms
Iteration   1: 8.594 ops/ms
Iteration   2: 9.403 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.152 ±(99.9%) 8.835 ops/ms [Average]
  (min, avg, max) = (8.594, 9.152, 9.459), stdev = 0.484
  CI (99.9%): [0.317, 17.986] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.654 ops/ms
# Warmup Iteration   2: 7.542 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 9.659 ops/ms
Iteration   2: 9.186 ops/ms
Iteration   3: 9.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.472 ±(99.9%) 4.585 ops/ms [Average]
  (min, avg, max) = (9.186, 9.472, 9.659), stdev = 0.251
  CI (99.9%): [4.887, 14.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 7.522 ops/ms
# Warmup Iteration   3: 8.698 ops/ms
Iteration   1: 8.606 ops/ms
Iteration   2: 9.035 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.883 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (8.606, 8.883, 9.035), stdev = 0.240
  CI (99.9%): [4.505, 13.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 6.555 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 7.672 ops/ms
Iteration   2: 7.611 ops/ms
Iteration   3: 7.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.601 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (7.520, 7.601, 7.672), stdev = 0.077
  CI (99.9%): [6.200, 9.002] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.880 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.004 ms/op
Iteration   1: 3.649 ±(99.9%) 0.004 ms/op
Iteration   2: 3.548 ±(99.9%) 0.004 ms/op
Iteration   3: 3.585 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.594 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.548, 3.594, 3.649), stdev = 0.051
  CI (99.9%): [2.663, 4.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.973 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.004 ms/op
Iteration   1: 3.339 ±(99.9%) 0.004 ms/op
Iteration   2: 3.327 ±(99.9%) 0.005 ms/op
Iteration   3: 3.468 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.378 ±(99.9%) 1.432 ms/op [Average]
  (min, avg, max) = (3.327, 3.378, 3.468), stdev = 0.078
  CI (99.9%): [1.946, 4.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.345 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.003 ms/op
Iteration   1: 3.692 ±(99.9%) 0.006 ms/op
Iteration   2: 3.682 ±(99.9%) 0.002 ms/op
Iteration   3: 3.527 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.634 ±(99.9%) 1.689 ms/op [Average]
  (min, avg, max) = (3.527, 3.634, 3.692), stdev = 0.093
  CI (99.9%): [1.945, 5.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.040 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.590 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.332 ±(99.9%) 0.006 ms/op
Iteration   1: 4.268 ±(99.9%) 0.005 ms/op
Iteration   2: 4.143 ±(99.9%) 0.008 ms/op
Iteration   3: 4.071 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.161 ±(99.9%) 1.821 ms/op [Average]
  (min, avg, max) = (4.071, 4.161, 4.268), stdev = 0.100
  CI (99.9%): [2.340, 5.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 11.190 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.015 ms/op
Iteration   1: 3.517 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   7.149 ms/op
                 createUser·p0.999:  22.988 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  23.780 ms/op
                 createUser·p0.9999: 29.411 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 3.457 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275427
  mean =      3.481 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5913 
    [ 2.500,  5.000) = 261335 
    [ 5.000,  7.500) = 6360 
    [ 7.500, 10.000) = 1103 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.447 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.386 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.897 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.010 ms/op
Iteration   1: 3.442 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.875 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  21.305 ms/op
                 existUser·p0.9999: 24.740 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   2: 3.490 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.657 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  11.836 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.487 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.053 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  22.818 ms/op
                 existUser·p0.9999: 39.901 ms/op
                 existUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276155
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266408 
    [ 5.000, 10.000) = 9050 
    [10.000, 15.000) = 407 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 165 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 31 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     15.390 ms/op
     p(99.9900) =     33.370 ms/op
     p(99.9990) =     40.205 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.615 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.011 ms/op
Iteration   1: 3.683 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   9.023 ms/op
                 getUser·p0.999:  20.649 ms/op
                 getUser·p0.9999: 23.865 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   2: 3.607 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.958 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.275 ms/op
                 getUser·p0.999:  11.603 ms/op
                 getUser·p0.9999: 32.630 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.491 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.884 ms/op
                 getUser·p0.999:  23.451 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 267180
  mean =      3.592 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1598 
    [ 2.500,  5.000) = 252905 
    [ 5.000,  7.500) = 9623 
    [ 7.500, 10.000) = 2063 
    [10.000, 12.500) = 527 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     31.949 ms/op
     p(99.9990) =     33.334 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.123 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.015 ms/op
Iteration   1: 4.243 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.880 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  23.335 ms/op
                 listUser·p0.9999: 27.427 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 4.109 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  16.521 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.043 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  19.119 ms/op
                 listUser·p0.9999: 21.794 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232345
  mean =      4.130 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 219278 
    [ 5.000,  7.500) = 9450 
    [ 7.500, 10.000) = 2261 
    [10.000, 12.500) = 523 
    [12.500, 15.000) = 325 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.749 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.364 ms/op
     p(99.9000) =     18.655 ms/op
     p(99.9900) =     26.076 ms/op
     p(99.9990) =     27.864 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.152 ± 8.835  ops/ms
ClientPb.existUser                       thrpt       3   9.472 ± 4.585  ops/ms
ClientPb.getUser                         thrpt       3   8.883 ± 4.378  ops/ms
ClientPb.listUser                        thrpt       3   7.601 ± 1.401  ops/ms
ClientPb.createUser                       avgt       3   3.594 ± 0.931   ms/op
ClientPb.existUser                        avgt       3   3.378 ± 1.432   ms/op
ClientPb.getUser                          avgt       3   3.634 ± 1.689   ms/op
ClientPb.listUser                         avgt       3   4.161 ± 1.821   ms/op
ClientPb.createUser                     sample  275427   3.481 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.065           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.293           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.933           ms/op
ClientPb.existUser                      sample  276155   3.473 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.053           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.010           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.390           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.370           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.436           ms/op
ClientPb.getUser                        sample  267180   3.592 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.710           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.684           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.949           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  232345   4.130 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.749           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.364           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.655           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.917           ms/op
