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
# Warmup Iteration   1: 2.344 ops/ms
# Warmup Iteration   2: 6.057 ops/ms
# Warmup Iteration   3: 8.803 ops/ms
Iteration   1: 9.365 ops/ms
Iteration   2: 9.890 ops/ms
Iteration   3: 9.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.717 ±(99.9%) 5.559 ops/ms [Average]
  (min, avg, max) = (9.365, 9.717, 9.896), stdev = 0.305
  CI (99.9%): [4.159, 15.276] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 9.676 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.136 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.315 ±(99.9%) 3.297 ops/ms [Average]
  (min, avg, max) = (10.136, 10.315, 10.498), stdev = 0.181
  CI (99.9%): [7.018, 13.613] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.260 ops/ms
# Warmup Iteration   2: 9.355 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 10.157 ops/ms
Iteration   2: 10.134 ops/ms
Iteration   3: 10.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.099 ±(99.9%) 1.488 ops/ms [Average]
  (min, avg, max) = (10.006, 10.099, 10.157), stdev = 0.082
  CI (99.9%): [8.611, 11.587] (assumes normal distribution)


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
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 7.075 ops/ms
# Warmup Iteration   3: 8.208 ops/ms
Iteration   1: 8.555 ops/ms
Iteration   2: 8.412 ops/ms
Iteration   3: 8.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.430 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (8.323, 8.430, 8.555), stdev = 0.117
  CI (99.9%): [6.293, 10.567] (assumes normal distribution)


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
# Warmup Iteration   1: 8.803 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.006 ms/op
Iteration   1: 3.287 ±(99.9%) 0.004 ms/op
Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
Iteration   3: 3.126 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.173 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (3.105, 3.173, 3.287), stdev = 0.100
  CI (99.9%): [1.350, 4.995] (assumes normal distribution)


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
# Warmup Iteration   1: 8.258 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.006 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
Iteration   3: 3.157 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.093 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.051, 3.093, 3.157), stdev = 0.057
  CI (99.9%): [2.060, 4.125] (assumes normal distribution)


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
# Warmup Iteration   1: 7.646 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.006 ms/op
Iteration   1: 3.194 ±(99.9%) 0.004 ms/op
Iteration   2: 3.152 ±(99.9%) 0.003 ms/op
Iteration   3: 3.167 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.171 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (3.152, 3.171, 3.194), stdev = 0.021
  CI (99.9%): [2.783, 3.558] (assumes normal distribution)


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
# Warmup Iteration   1: 8.709 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.004 ms/op
Iteration   1: 3.836 ±(99.9%) 0.006 ms/op
Iteration   2: 3.739 ±(99.9%) 0.008 ms/op
Iteration   3: 3.901 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.739, 3.825, 3.901), stdev = 0.082
  CI (99.9%): [2.337, 5.314] (assumes normal distribution)


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
# Warmup Iteration   1: 8.585 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.820 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.011 ms/op
Iteration   1: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.602 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  11.364 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.384 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.315 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  19.127 ms/op
                 createUser·p0.9999: 23.429 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.210 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  18.661 ms/op
                 createUser·p0.9999: 30.745 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295270
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13666 
    [ 2.500,  5.000) = 275076 
    [ 5.000,  7.500) = 5652 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     26.916 ms/op
     p(99.9990) =     31.590 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 7.984 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
Iteration   1: 3.115 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.359 ms/op
                 existUser·p0.999:  9.999 ms/op
                 existUser·p0.9999: 18.787 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  9.825 ms/op
                 existUser·p0.9999: 21.485 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.231 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  15.539 ms/op
                 existUser·p0.9999: 21.297 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309505
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16029 
    [ 2.500,  5.000) = 288711 
    [ 5.000,  7.500) = 4049 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     10.240 ms/op
     p(99.9900) =     21.039 ms/op
     p(99.9990) =     22.410 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


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
# Warmup Iteration   1: 8.326 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.010 ms/op
Iteration   1: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  16.099 ms/op
                 getUser·p0.9999: 23.838 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  9.764 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 3.174 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.587 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298264
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20528 
    [ 2.500,  5.000) = 271681 
    [ 5.000,  7.500) = 4951 
    [ 7.500, 10.000) = 660 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     12.697 ms/op
     p(99.9900) =     24.614 ms/op
     p(99.9990) =     26.416 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 10.411 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.013 ms/op
Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 24.572 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 3.825 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.778 ms/op
                 listUser·p0.9999: 20.993 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.774 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.468 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  13.751 ms/op
                 listUser·p0.9999: 15.336 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249288
  mean =      3.846 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 239883 
    [ 5.000,  7.500) = 7160 
    [ 7.500, 10.000) = 1518 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.468 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.307 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     23.694 ms/op
     p(99.9990) =     25.085 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.717 ± 5.559  ops/ms
ClientPb.existUser                       thrpt       3  10.315 ± 3.297  ops/ms
ClientPb.getUser                         thrpt       3  10.099 ± 1.488  ops/ms
ClientPb.listUser                        thrpt       3   8.430 ± 2.137  ops/ms
ClientPb.createUser                       avgt       3   3.173 ± 1.823   ms/op
ClientPb.existUser                        avgt       3   3.093 ± 1.033   ms/op
ClientPb.getUser                          avgt       3   3.171 ± 0.387   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 1.489   ms/op
ClientPb.createUser                     sample  295270   3.251 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.219           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.916           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.719           ms/op
ClientPb.existUser                      sample  309505   3.101 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.231           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.240           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.741           ms/op
ClientPb.getUser                        sample  298264   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.461           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.693           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.697           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.614           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  249288   3.846 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.468           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.178           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.694           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
