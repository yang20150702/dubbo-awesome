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
# Warmup Iteration   1: 2.627 ops/ms
# Warmup Iteration   2: 6.873 ops/ms
# Warmup Iteration   3: 9.344 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.678 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.958 ±(99.9%) 4.565 ops/ms [Average]
  (min, avg, max) = (9.678, 9.958, 10.161), stdev = 0.250
  CI (99.9%): [5.392, 14.523] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.867 ops/ms
# Warmup Iteration   2: 9.256 ops/ms
# Warmup Iteration   3: 9.645 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.521 ±(99.9%) 4.669 ops/ms [Average]
  (min, avg, max) = (10.227, 10.521, 10.692), stdev = 0.256
  CI (99.9%): [5.852, 15.191] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 9.146 ops/ms
# Warmup Iteration   3: 9.347 ops/ms
Iteration   1: 9.762 ops/ms
Iteration   2: 10.105 ops/ms
Iteration   3: 10.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.981 ±(99.9%) 3.469 ops/ms [Average]
  (min, avg, max) = (9.762, 9.981, 10.105), stdev = 0.190
  CI (99.9%): [6.511, 13.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.435 ops/ms
# Warmup Iteration   2: 7.819 ops/ms
# Warmup Iteration   3: 8.113 ops/ms
Iteration   1: 8.250 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.389 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (8.250, 8.389, 8.493), stdev = 0.125
  CI (99.9%): [6.111, 10.667] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.509 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.005 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
Iteration   2: 3.183 ±(99.9%) 0.007 ms/op
Iteration   3: 3.208 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 0.243 ms/op [Average]
  (min, avg, max) = (3.183, 3.193, 3.208), stdev = 0.013
  CI (99.9%): [2.950, 3.436] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.034 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.004 ms/op
Iteration   1: 3.153 ±(99.9%) 0.003 ms/op
Iteration   2: 3.179 ±(99.9%) 0.004 ms/op
Iteration   3: 3.101 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.144 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.101, 3.144, 3.179), stdev = 0.040
  CI (99.9%): [2.417, 3.871] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.308 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.005 ms/op
Iteration   1: 3.289 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.006 ms/op
Iteration   3: 3.205 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 1.428 ms/op [Average]
  (min, avg, max) = (3.132, 3.208, 3.289), stdev = 0.078
  CI (99.9%): [1.780, 4.637] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.941 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.005 ms/op
Iteration   1: 3.830 ±(99.9%) 0.005 ms/op
Iteration   2: 3.765 ±(99.9%) 0.008 ms/op
Iteration   3: 3.821 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.805 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.765, 3.805, 3.830), stdev = 0.036
  CI (99.9%): [3.156, 4.455] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.833 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.142 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   2: 3.156 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.276 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  10.606 ms/op
                 createUser·p0.9999: 28.196 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   3: 3.259 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  17.756 ms/op
                 createUser·p0.9999: 58.327 ms/op
                 createUser·p1.00:   59.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301209
  mean =      3.185 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 294483 
    [ 5.000, 10.000) = 6382 
    [10.000, 15.000) = 24 
    [15.000, 20.000) = 181 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 58 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.276 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     16.640 ms/op
     p(99.9900) =     50.250 ms/op
     p(99.9990) =     58.915 ms/op
     p(99.9999) =     59.245 ms/op
    p(100.0000) =     59.245 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  9.634 ms/op
                 existUser·p0.9999: 27.256 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.632 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  13.681 ms/op
                 existUser·p0.9999: 25.278 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.101 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  9.060 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308130
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29046 
    [ 2.500,  5.000) = 274867 
    [ 5.000,  7.500) = 3414 
    [ 7.500, 10.000) = 412 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     13.381 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.817 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.667 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.010 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 24.974 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  15.643 ms/op
                 getUser·p0.9999: 23.894 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   3: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  9.144 ms/op
                 getUser·p0.9999: 22.638 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297219
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14879 
    [ 2.500,  5.000) = 274845 
    [ 5.000,  7.500) = 6624 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     15.594 ms/op
     p(99.9900) =     24.052 ms/op
     p(99.9990) =     25.658 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 8.760 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
Iteration   1: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 3.769 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.190 ms/op
                 listUser·p0.9999: 17.810 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 3.825 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 15.362 ms/op
                 listUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251408
  mean =      3.818 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 244286 
    [ 5.000,  7.500) = 5234 
    [ 7.500, 10.000) = 1213 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.730 ms/op
     p(99.9900) =     22.470 ms/op
     p(99.9990) =     25.574 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.958 ± 4.565  ops/ms
ClientPb.existUser                       thrpt       3  10.521 ± 4.669  ops/ms
ClientPb.getUser                         thrpt       3   9.981 ± 3.469  ops/ms
ClientPb.listUser                        thrpt       3   8.389 ± 2.278  ops/ms
ClientPb.createUser                       avgt       3   3.193 ± 0.243   ms/op
ClientPb.existUser                        avgt       3   3.144 ± 0.727   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 1.428   ms/op
ClientPb.listUser                         avgt       3   3.805 ± 0.650   ms/op
ClientPb.createUser                     sample  301209   3.185 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.276           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.518           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.640           ms/op
ClientPb.createUser:createUser·p0.9999  sample          50.250           ms/op
ClientPb.createUser:createUser·p1.00    sample          59.245           ms/op
ClientPb.existUser                      sample  308130   3.112 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.381           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.526           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  297219   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.031           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.100           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.594           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.052           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  251408   3.818 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.327           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.730           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.470           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
