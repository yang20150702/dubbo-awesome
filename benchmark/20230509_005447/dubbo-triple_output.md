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
# Warmup Iteration   1: 1.903 ops/ms
# Warmup Iteration   2: 3.692 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.074 ops/ms
Iteration   3: 7.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.063 ±(99.9%) 3.786 ops/ms [Average]
  (min, avg, max) = (7.850, 8.063, 8.265), stdev = 0.208
  CI (99.9%): [4.277, 11.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.373 ops/ms
# Warmup Iteration   2: 7.010 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.130 ops/ms
Iteration   2: 8.507 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.389 ±(99.9%) 4.088 ops/ms [Average]
  (min, avg, max) = (8.130, 8.389, 8.529), stdev = 0.224
  CI (99.9%): [4.301, 12.477] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.278 ops/ms
# Warmup Iteration   2: 7.157 ops/ms
# Warmup Iteration   3: 8.168 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.311 ops/ms
Iteration   3: 8.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.191 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (8.058, 8.191, 8.311), stdev = 0.127
  CI (99.9%): [5.874, 10.508] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.429 ops/ms
# Warmup Iteration   2: 6.654 ops/ms
# Warmup Iteration   3: 7.478 ops/ms
Iteration   1: 7.434 ops/ms
Iteration   2: 7.389 ops/ms
Iteration   3: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.238 ±(99.9%) 5.491 ops/ms [Average]
  (min, avg, max) = (6.892, 7.238, 7.434), stdev = 0.301
  CI (99.9%): [1.747, 12.729] (assumes normal distribution)


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
# Warmup Iteration   1: 12.485 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.007 ms/op
Iteration   1: 3.831 ±(99.9%) 0.008 ms/op
Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
Iteration   3: 4.042 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.902 ±(99.9%) 2.207 ms/op [Average]
  (min, avg, max) = (3.831, 3.902, 4.042), stdev = 0.121
  CI (99.9%): [1.695, 6.109] (assumes normal distribution)


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
# Warmup Iteration   1: 10.805 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.008 ms/op
Iteration   1: 3.649 ±(99.9%) 0.007 ms/op
Iteration   2: 3.754 ±(99.9%) 0.012 ms/op
Iteration   3: 3.575 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.660 ±(99.9%) 1.641 ms/op [Average]
  (min, avg, max) = (3.575, 3.660, 3.754), stdev = 0.090
  CI (99.9%): [2.019, 5.300] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.704 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.004 ms/op
Iteration   1: 3.958 ±(99.9%) 0.011 ms/op
Iteration   2: 3.687 ±(99.9%) 0.018 ms/op
Iteration   3: 3.696 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.780 ±(99.9%) 2.807 ms/op [Average]
  (min, avg, max) = (3.687, 3.780, 3.958), stdev = 0.154
  CI (99.9%): [0.973, 6.587] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.594 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.027 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.718 ±(99.9%) 0.007 ms/op
Iteration   1: 4.394 ±(99.9%) 0.014 ms/op
Iteration   2: 4.285 ±(99.9%) 0.013 ms/op
Iteration   3: 4.337 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.339 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (4.285, 4.339, 4.394), stdev = 0.055
  CI (99.9%): [3.337, 5.340] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.393 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.947 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.978 ±(99.9%) 0.014 ms/op
Iteration   1: 3.613 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  20.558 ms/op
                 createUser·p0.9999: 24.974 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.642 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  11.272 ms/op
                 createUser·p0.9999: 28.286 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 3.844 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  27.677 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 259567
  mean =      3.697 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1735 
    [ 2.500,  5.000) = 250552 
    [ 5.000,  7.500) = 6112 
    [ 7.500, 10.000) = 694 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     21.281 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     35.979 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.405 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.766 ±(99.9%) 0.012 ms/op
Iteration   1: 3.673 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.759 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  11.141 ms/op
                 existUser·p0.9999: 28.330 ms/op
                 existUser·p1.00:   30.081 ms/op

Iteration   2: 3.856 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  24.347 ms/op
                 existUser·p0.9999: 30.366 ms/op
                 existUser·p1.00:   31.785 ms/op

Iteration   3: 3.747 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  14.288 ms/op
                 existUser·p0.9999: 31.374 ms/op
                 existUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 255493
  mean =      3.757 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 782 
    [ 2.500,  5.000) = 245162 
    [ 5.000,  7.500) = 8031 
    [ 7.500, 10.000) = 1007 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     12.872 ms/op
     p(99.9900) =     30.423 ms/op
     p(99.9990) =     32.626 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 11.205 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.015 ms/op
Iteration   1: 3.682 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   7.094 ms/op
                 getUser·p0.999:  19.731 ms/op
                 getUser·p0.9999: 22.653 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.677 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  10.617 ms/op
                 getUser·p0.9999: 24.127 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.893 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  25.843 ms/op
                 getUser·p0.9999: 37.945 ms/op
                 getUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 255812
  mean =      3.748 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 391 
    [ 2.500,  5.000) = 246823 
    [ 5.000,  7.500) = 6892 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     19.372 ms/op
     p(99.9900) =     37.317 ms/op
     p(99.9990) =     38.142 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.089 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.017 ms/op
Iteration   1: 4.477 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.687 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  24.951 ms/op
                 listUser·p0.9999: 27.843 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   2: 4.578 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   8.336 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 22.709 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 4.590 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 21.071 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211183
  mean =      4.547 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 185316 
    [ 5.000,  7.500) = 20544 
    [ 7.500, 10.000) = 4382 
    [10.000, 12.500) = 428 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      4.325 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     19.675 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.063 ± 3.786  ops/ms
ClientPb.existUser                       thrpt       3   8.389 ± 4.088  ops/ms
ClientPb.getUser                         thrpt       3   8.191 ± 2.317  ops/ms
ClientPb.listUser                        thrpt       3   7.238 ± 5.491  ops/ms
ClientPb.createUser                       avgt       3   3.902 ± 2.207   ms/op
ClientPb.existUser                        avgt       3   3.660 ± 1.641   ms/op
ClientPb.getUser                          avgt       3   3.780 ± 2.807   ms/op
ClientPb.listUser                         avgt       3   4.339 ± 1.002   ms/op
ClientPb.createUser                     sample  259567   3.697 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.283           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.281           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.406           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.979           ms/op
ClientPb.existUser                      sample  255493   3.757 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.884           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.872           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.423           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.932           ms/op
ClientPb.getUser                        sample  255812   3.748 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.313           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.186           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.750           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.372           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.317           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.339           ms/op
ClientPb.listUser                       sample  211183   4.547 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.599           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.675           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.967           ms/op
