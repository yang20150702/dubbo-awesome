# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.030 ops/ms
# Warmup Iteration   2: 12.158 ops/ms
# Warmup Iteration   3: 12.139 ops/ms
Iteration   1: 12.417 ops/ms
Iteration   2: 12.494 ops/ms
Iteration   3: 12.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.457 ±(99.9%) 0.703 ops/ms [Average]
  (min, avg, max) = (12.417, 12.457, 12.494), stdev = 0.039
  CI (99.9%): [11.754, 13.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.835 ops/ms
# Warmup Iteration   2: 12.677 ops/ms
# Warmup Iteration   3: 12.874 ops/ms
Iteration   1: 12.992 ops/ms
Iteration   2: 13.153 ops/ms
Iteration   3: 12.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.037 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (12.967, 13.037, 13.153), stdev = 0.100
  CI (99.9%): [11.205, 14.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.580 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.738 ops/ms
Iteration   1: 12.737 ops/ms
Iteration   2: 12.609 ops/ms
Iteration   3: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.669 ±(99.9%) 1.170 ops/ms [Average]
  (min, avg, max) = (12.609, 12.669, 12.737), stdev = 0.064
  CI (99.9%): [11.499, 13.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.600 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.473 ±(99.9%) 0.197 ops/ms [Average]
  (min, avg, max) = (10.461, 10.473, 10.481), stdev = 0.011
  CI (99.9%): [10.276, 10.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.040 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.003 ms/op
Iteration   1: 2.574 ±(99.9%) 0.005 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.556 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.534, 2.556, 2.574), stdev = 0.020
  CI (99.9%): [2.185, 2.928] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.455 ±(99.9%) 0.004 ms/op
Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.452 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (2.442, 2.452, 2.459), stdev = 0.009
  CI (99.9%): [2.293, 2.610] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.003 ms/op
Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.510, 2.529, 2.546), stdev = 0.018
  CI (99.9%): [2.201, 2.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.051 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (3.040, 3.051, 3.065), stdev = 0.013
  CI (99.9%): [2.821, 3.281] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.699 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.581 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.536 ms/op
                 createUser·p0.9999: 14.123 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.310 ms/op
                 createUser·p0.99:   4.086 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 12.383 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 11.112 ms/op
                 createUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370825
  mean =      2.586 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176843 
    [ 2.500,  5.000) = 193016 
    [ 5.000,  7.500) = 556 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     13.778 ms/op
     p(99.9990) =     14.640 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.914 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.912 ms/op
                 existUser·p0.999:  11.481 ms/op
                 existUser·p0.9999: 14.883 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   2.601 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.512 ms/op
                 existUser·p0.999:  5.613 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.035 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  8.636 ms/op
                 existUser·p0.9999: 12.573 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384030
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 189046 
    [ 2.500,  3.750) = 191152 
    [ 3.750,  5.000) = 2863 
    [ 5.000,  6.250) = 474 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      7.265 ms/op
     p(99.9900) =     13.969 ms/op
     p(99.9990) =     15.076 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.005 ms/op
Iteration   1: 2.594 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.346 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  11.825 ms/op
                 getUser·p0.9999: 14.216 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.572 ms/op
                 getUser·p0.999:  9.727 ms/op
                 getUser·p0.9999: 14.303 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.917 ms/op
                 getUser·p0.999:  8.646 ms/op
                 getUser·p0.9999: 11.370 ms/op
                 getUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375182
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 181884 
    [ 2.500,  3.750) = 187013 
    [ 3.750,  5.000) = 4879 
    [ 5.000,  6.250) = 874 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 112 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     15.024 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.867 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.429 ms/op
                 listUser·p1.00:   10.715 ms/op

Iteration   2: 3.066 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 10.547 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 10.715 ms/op
                 listUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314625
  mean =      3.048 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 84487 
    [ 2.500,  3.750) = 188952 
    [ 3.750,  5.000) = 33571 
    [ 5.000,  6.250) = 6201 
    [ 6.250,  7.500) = 642 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 293 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.593 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     10.545 ms/op
     p(99.9990) =     11.860 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.457 ± 0.703  ops/ms
ClientPb.existUser                       thrpt       3  13.037 ± 1.833  ops/ms
ClientPb.getUser                         thrpt       3  12.669 ± 1.170  ops/ms
ClientPb.listUser                        thrpt       3  10.473 ± 0.197  ops/ms
ClientPb.createUser                       avgt       3   2.556 ± 0.371   ms/op
ClientPb.existUser                        avgt       3   2.452 ± 0.158   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.328   ms/op
ClientPb.listUser                         avgt       3   3.051 ± 0.230   ms/op
ClientPb.createUser                     sample  370825   2.586 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.864           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.110           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.778           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.808           ms/op
ClientPb.existUser                      sample  384030   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.745           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.265           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.969           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.237           ms/op
ClientPb.getUser                        sample  375182   2.556 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.568           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  314625   3.048 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.754           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.593           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.545           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.075           ms/op
