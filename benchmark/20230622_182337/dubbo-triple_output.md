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
# Warmup Iteration   1: 1.600 ops/ms
# Warmup Iteration   2: 3.811 ops/ms
# Warmup Iteration   3: 7.068 ops/ms
Iteration   1: 7.082 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 7.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.570 ±(99.9%) 7.719 ops/ms [Average]
  (min, avg, max) = (7.082, 7.570, 7.829), stdev = 0.423
  CI (99.9%): [≈ 0, 15.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.222 ops/ms
# Warmup Iteration   2: 6.342 ops/ms
# Warmup Iteration   3: 7.534 ops/ms
Iteration   1: 8.125 ops/ms
Iteration   2: 7.849 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.988 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (7.849, 7.988, 8.125), stdev = 0.138
  CI (99.9%): [5.466, 10.510] (assumes normal distribution)


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
# Warmup Iteration   1: 2.487 ops/ms
# Warmup Iteration   2: 6.173 ops/ms
# Warmup Iteration   3: 7.593 ops/ms
Iteration   1: 7.562 ops/ms
Iteration   2: 8.075 ops/ms
Iteration   3: 7.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.854 ±(99.9%) 4.810 ops/ms [Average]
  (min, avg, max) = (7.562, 7.854, 8.075), stdev = 0.264
  CI (99.9%): [3.044, 12.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.993 ops/ms
# Warmup Iteration   2: 4.944 ops/ms
# Warmup Iteration   3: 6.285 ops/ms
Iteration   1: 6.524 ops/ms
Iteration   2: 6.316 ops/ms
Iteration   3: 6.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.463 ±(99.9%) 2.340 ops/ms [Average]
  (min, avg, max) = (6.316, 6.463, 6.550), stdev = 0.128
  CI (99.9%): [4.124, 8.803] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.260 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.055 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.004 ms/op
Iteration   1: 4.230 ±(99.9%) 0.008 ms/op
Iteration   2: 4.139 ±(99.9%) 0.012 ms/op
Iteration   3: 4.255 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.208 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (4.139, 4.208, 4.255), stdev = 0.061
  CI (99.9%): [3.095, 5.322] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.050 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.981 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.010 ms/op
Iteration   1: 4.113 ±(99.9%) 0.002 ms/op
Iteration   2: 3.953 ±(99.9%) 0.012 ms/op
Iteration   3: 4.007 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.025 ±(99.9%) 1.487 ms/op [Average]
  (min, avg, max) = (3.953, 4.025, 4.113), stdev = 0.082
  CI (99.9%): [2.538, 5.512] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.357 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.781 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.005 ms/op
Iteration   1: 4.248 ±(99.9%) 0.010 ms/op
Iteration   2: 4.089 ±(99.9%) 0.009 ms/op
Iteration   3: 4.202 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.180 ±(99.9%) 1.493 ms/op [Average]
  (min, avg, max) = (4.089, 4.180, 4.248), stdev = 0.082
  CI (99.9%): [2.687, 5.672] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.471 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.818 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.893 ±(99.9%) 0.011 ms/op
Iteration   1: 4.914 ±(99.9%) 0.015 ms/op
Iteration   2: 4.890 ±(99.9%) 0.014 ms/op
Iteration   3: 4.874 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.893 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (4.874, 4.893, 4.914), stdev = 0.020
  CI (99.9%): [4.525, 5.260] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.734 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 5.511 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.017 ms/op
Iteration   1: 4.107 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 22.250 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 4.141 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.503 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  17.225 ms/op
                 createUser·p0.9999: 23.897 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 4.197 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 26.161 ms/op
                 createUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231611
  mean =      4.148 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 153 
    [ 2.500,  5.000) = 212820 
    [ 5.000,  7.500) = 16866 
    [ 7.500, 10.000) = 1162 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     25.309 ms/op
     p(99.9990) =     26.545 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 13.008 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  11.977 ms/op
                 existUser·p0.9999: 25.920 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 4.070 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.235 ms/op
                 existUser·p0.99:   7.661 ms/op
                 existUser·p0.999:  25.704 ms/op
                 existUser·p0.9999: 29.660 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  13.551 ms/op
                 existUser·p0.9999: 34.934 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237952
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 134 
    [ 2.500,  5.000) = 227607 
    [ 5.000,  7.500) = 8080 
    [ 7.500, 10.000) = 1484 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.334 ms/op
     p(99.9900) =     33.214 ms/op
     p(99.9990) =     35.405 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 12.081 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.759 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.353 ±(99.9%) 0.013 ms/op
Iteration   1: 4.167 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.946 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  10.920 ms/op
                 getUser·p0.9999: 28.158 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   2: 4.229 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 51.737 ms/op
                 getUser·p1.00:   53.805 ms/op

Iteration   3: 4.264 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.040 ms/op
                 getUser·p0.50:   4.190 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  11.419 ms/op
                 getUser·p0.9999: 36.635 ms/op
                 getUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 227400
  mean =      4.220 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 216030 
    [ 5.000, 10.000) = 10697 
    [10.000, 15.000) = 442 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 112 
    [30.000, 35.000) = 39 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.665 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     19.352 ms/op
     p(99.9900) =     51.053 ms/op
     p(99.9990) =     53.674 ms/op
     p(99.9999) =     53.805 ms/op
    p(100.0000) =     53.805 ms/op


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
# Warmup Iteration   1: 14.197 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.705 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.196 ±(99.9%) 0.018 ms/op
Iteration   1: 4.937 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   9.690 ms/op
                 listUser·p0.999:  23.696 ms/op
                 listUser·p0.9999: 28.984 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 4.867 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  20.926 ms/op
                 listUser·p0.9999: 25.966 ms/op
                 listUser·p1.00:   27.132 ms/op

Iteration   3: 4.761 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.522 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197679
  mean =      4.854 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 162639 
    [ 5.000,  7.500) = 30474 
    [ 7.500, 10.000) = 3203 
    [10.000, 12.500) = 606 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      1.839 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     20.490 ms/op
     p(99.9900) =     27.276 ms/op
     p(99.9990) =     29.202 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.570 ± 7.719  ops/ms
ClientPb.existUser                       thrpt       3   7.988 ± 2.522  ops/ms
ClientPb.getUser                         thrpt       3   7.854 ± 4.810  ops/ms
ClientPb.listUser                        thrpt       3   6.463 ± 2.340  ops/ms
ClientPb.createUser                       avgt       3   4.208 ± 1.113   ms/op
ClientPb.existUser                        avgt       3   4.025 ± 1.487   ms/op
ClientPb.getUser                          avgt       3   4.180 ± 1.493   ms/op
ClientPb.listUser                         avgt       3   4.893 ± 0.368   ms/op
ClientPb.createUser                     sample  231611   4.148 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.088           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.279           ms/op
ClientPb.existUser                      sample  237952   4.032 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.171           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.266           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.334           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  227400   4.220 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.665           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.352           ms/op
ClientPb.getUser:getUser·p0.9999        sample          51.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          53.805           ms/op
ClientPb.listUser                       sample  197679   4.854 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.839           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.490           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.276           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.458           ms/op
