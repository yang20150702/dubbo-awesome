# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.758 ops/ms
# Warmup Iteration   2: 12.175 ops/ms
# Warmup Iteration   3: 12.357 ops/ms
Iteration   1: 12.636 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.617 ±(99.9%) 0.468 ops/ms [Average]
  (min, avg, max) = (12.588, 12.617, 12.636), stdev = 0.026
  CI (99.9%): [12.149, 13.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.359 ops/ms
# Warmup Iteration   2: 13.026 ops/ms
# Warmup Iteration   3: 13.125 ops/ms
Iteration   1: 12.906 ops/ms
Iteration   2: 13.100 ops/ms
Iteration   3: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.982 ±(99.9%) 1.885 ops/ms [Average]
  (min, avg, max) = (12.906, 12.982, 13.100), stdev = 0.103
  CI (99.9%): [11.097, 14.867] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.917 ops/ms
# Warmup Iteration   2: 12.450 ops/ms
# Warmup Iteration   3: 12.671 ops/ms
Iteration   1: 12.866 ops/ms
Iteration   2: 12.704 ops/ms
Iteration   3: 12.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.795 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (12.704, 12.795, 12.866), stdev = 0.083
  CI (99.9%): [11.288, 14.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.491 ops/ms
# Warmup Iteration   2: 10.689 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.808 ops/ms
Iteration   2: 10.668 ops/ms
Iteration   3: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.748 ±(99.9%) 1.319 ops/ms [Average]
  (min, avg, max) = (10.668, 10.748, 10.808), stdev = 0.072
  CI (99.9%): [9.430, 12.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.374 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.527, 2.541, 2.549), stdev = 0.012
  CI (99.9%): [2.322, 2.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.003 ms/op
Iteration   3: 2.428 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.412, 2.421, 2.428), stdev = 0.009
  CI (99.9%): [2.263, 2.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
Iteration   3: 2.491 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.467, 2.482, 2.491), stdev = 0.013
  CI (99.9%): [2.238, 2.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.937 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.004 ms/op
Iteration   1: 3.007 ±(99.9%) 0.003 ms/op
Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
Iteration   3: 3.018 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (3.007, 3.012, 3.018), stdev = 0.006
  CI (99.9%): [2.903, 3.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.048 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  11.206 ms/op
                 createUser·p0.9999: 13.452 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  9.556 ms/op
                 createUser·p0.9999: 12.440 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 11.292 ms/op
                 createUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382899
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 184580 
    [ 2.500,  3.750) = 194638 
    [ 3.750,  5.000) = 3000 
    [ 5.000,  6.250) = 236 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.882 ms/op
     p(99.9900) =     12.681 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  8.027 ms/op
                 existUser·p0.9999: 14.281 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.669 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  7.594 ms/op
                 existUser·p0.9999: 10.630 ms/op
                 existUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393244
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 196870 
    [ 2.500,  3.750) = 192434 
    [ 3.750,  5.000) = 2855 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      7.848 ms/op
     p(99.9900) =     13.403 ms/op
     p(99.9990) =     14.534 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.976 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  11.475 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  10.076 ms/op
                 getUser·p0.9999: 13.771 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.771 ms/op
                 getUser·p0.999:  9.322 ms/op
                 getUser·p0.9999: 11.344 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378668
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 185797 
    [ 2.500,  3.750) = 188302 
    [ 3.750,  5.000) = 3488 
    [ 5.000,  6.250) = 613 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.393 ms/op
     p(99.9900) =     13.765 ms/op
     p(99.9990) =     14.303 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.826 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.705 ms/op
                 listUser·p1.00:   13.124 ms/op

Iteration   2: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.687 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 11.794 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.605 ms/op
                 listUser·p0.9999: 11.023 ms/op
                 listUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316733
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 141 
    [ 1.250,  2.500) = 88346 
    [ 2.500,  3.750) = 187736 
    [ 3.750,  5.000) = 32936 
    [ 5.000,  6.250) = 6199 
    [ 6.250,  7.500) = 695 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 244 
    [10.000, 11.250) = 198 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.687 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     12.318 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.617 ± 0.468  ops/ms
ClientPb.existUser                       thrpt       3  12.982 ± 1.885  ops/ms
ClientPb.getUser                         thrpt       3  12.795 ± 1.507  ops/ms
ClientPb.listUser                        thrpt       3  10.748 ± 1.319  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.218   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.158   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.109   ms/op
ClientPb.createUser                     sample  382899   2.506 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.814           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.882           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  393244   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.853           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.403           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  378668   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.393           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.765           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.451           ms/op
ClientPb.listUser                       sample  316733   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.687           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.687           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.452           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.124           ms/op
