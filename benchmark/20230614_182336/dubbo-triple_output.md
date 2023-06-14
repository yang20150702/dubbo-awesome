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
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 5.321 ops/ms
# Warmup Iteration   3: 8.866 ops/ms
Iteration   1: 9.037 ops/ms
Iteration   2: 9.358 ops/ms
Iteration   3: 9.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.254 ±(99.9%) 3.431 ops/ms [Average]
  (min, avg, max) = (9.037, 9.254, 9.367), stdev = 0.188
  CI (99.9%): [5.823, 12.685] (assumes normal distribution)


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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 9.787 ops/ms
Iteration   1: 9.765 ops/ms
Iteration   2: 9.964 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.862 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (9.765, 9.862, 9.964), stdev = 0.100
  CI (99.9%): [8.044, 11.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 8.934 ops/ms
Iteration   1: 9.271 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 9.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.245 ±(99.9%) 0.877 ops/ms [Average]
  (min, avg, max) = (9.190, 9.245, 9.275), stdev = 0.048
  CI (99.9%): [8.368, 10.122] (assumes normal distribution)


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
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 7.299 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 8.064 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.115 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (8.064, 8.115, 8.157), stdev = 0.047
  CI (99.9%): [7.261, 8.969] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.116 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.005 ms/op
Iteration   1: 3.426 ±(99.9%) 0.004 ms/op
Iteration   2: 3.428 ±(99.9%) 0.008 ms/op
Iteration   3: 3.366 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.407 ±(99.9%) 0.636 ms/op [Average]
  (min, avg, max) = (3.366, 3.407, 3.428), stdev = 0.035
  CI (99.9%): [2.771, 4.042] (assumes normal distribution)


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
# Warmup Iteration   1: 8.852 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.003 ms/op
Iteration   1: 3.273 ±(99.9%) 0.003 ms/op
Iteration   2: 3.245 ±(99.9%) 0.004 ms/op
Iteration   3: 3.217 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.245 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.217, 3.245, 3.273), stdev = 0.028
  CI (99.9%): [2.732, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 9.953 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.864 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.007 ms/op
Iteration   1: 3.441 ±(99.9%) 0.009 ms/op
Iteration   2: 3.431 ±(99.9%) 0.009 ms/op
Iteration   3: 3.472 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.431, 3.448, 3.472), stdev = 0.021
  CI (99.9%): [3.061, 3.836] (assumes normal distribution)


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
# Warmup Iteration   1: 11.231 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
Iteration   1: 3.889 ±(99.9%) 0.011 ms/op
Iteration   2: 4.078 ±(99.9%) 0.005 ms/op
Iteration   3: 3.821 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.929 ±(99.9%) 2.423 ms/op [Average]
  (min, avg, max) = (3.821, 3.929, 4.078), stdev = 0.133
  CI (99.9%): [1.507, 6.352] (assumes normal distribution)


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
# Warmup Iteration   1: 9.597 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.693 ±(99.9%) 0.012 ms/op
Iteration   1: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.234 ms/op
                 createUser·p0.999:  18.829 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  20.523 ms/op
                 createUser·p0.9999: 24.576 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  21.548 ms/op
                 createUser·p0.9999: 24.740 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280895
  mean =      3.415 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11622 
    [ 2.500,  5.000) = 261534 
    [ 5.000,  7.500) = 6490 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     19.861 ms/op
     p(99.9900) =     24.475 ms/op
     p(99.9990) =     26.180 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 8.315 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
Iteration   1: 3.353 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  18.297 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 25.482 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.063 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.001 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 26.027 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291120
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3364 
    [ 2.500,  5.000) = 281564 
    [ 5.000,  7.500) = 5416 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     25.457 ms/op
     p(99.9990) =     26.548 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 11.136 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.010 ms/op
Iteration   1: 3.491 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.714 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  19.790 ms/op
                 getUser·p0.9999: 23.456 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.483 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.669 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  21.122 ms/op
                 getUser·p0.9999: 29.453 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   3: 3.479 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  17.142 ms/op
                 getUser·p0.9999: 25.665 ms/op
                 getUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275305
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4019 
    [ 2.500,  5.000) = 263929 
    [ 5.000,  7.500) = 5538 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     29.212 ms/op
     p(99.9990) =     30.367 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 11.035 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
Iteration   1: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  17.810 ms/op
                 listUser·p0.9999: 23.411 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 4.037 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   3: 4.166 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.223 ms/op
                 listUser·p0.99:   7.987 ms/op
                 listUser·p0.999:  17.793 ms/op
                 listUser·p0.9999: 25.208 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234454
  mean =      4.093 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 221594 
    [ 5.000,  7.500) = 10460 
    [ 7.500, 10.000) = 1529 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.508 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     23.141 ms/op
     p(99.9990) =     26.374 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.254 ± 3.431  ops/ms
ClientPb.existUser                       thrpt       3   9.862 ± 1.817  ops/ms
ClientPb.getUser                         thrpt       3   9.245 ± 0.877  ops/ms
ClientPb.listUser                        thrpt       3   8.115 ± 0.854  ops/ms
ClientPb.createUser                       avgt       3   3.407 ± 0.636   ms/op
ClientPb.existUser                        avgt       3   3.245 ± 0.513   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 0.388   ms/op
ClientPb.listUser                         avgt       3   3.929 ± 2.423   ms/op
ClientPb.createUser                     sample  280895   3.415 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.378           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.861           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.475           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.345           ms/op
ClientPb.existUser                      sample  291120   3.297 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.063           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.640           ms/op
ClientPb.getUser                        sample  275305   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.669           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.678           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  234454   4.093 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.354           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.508           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.141           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
