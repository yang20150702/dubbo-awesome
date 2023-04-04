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
# Warmup Iteration   1: 2.464 ops/ms
# Warmup Iteration   2: 5.360 ops/ms
# Warmup Iteration   3: 9.148 ops/ms
Iteration   1: 9.724 ops/ms
Iteration   2: 10.003 ops/ms
Iteration   3: 9.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.907 ±(99.9%) 2.902 ops/ms [Average]
  (min, avg, max) = (9.724, 9.907, 10.003), stdev = 0.159
  CI (99.9%): [7.005, 12.809] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 9.617 ops/ms
# Warmup Iteration   3: 9.736 ops/ms
Iteration   1: 10.076 ops/ms
Iteration   2: 10.506 ops/ms
Iteration   3: 10.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.311 ±(99.9%) 3.978 ops/ms [Average]
  (min, avg, max) = (10.076, 10.311, 10.506), stdev = 0.218
  CI (99.9%): [6.333, 14.290] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.501 ops/ms
# Warmup Iteration   2: 9.012 ops/ms
# Warmup Iteration   3: 10.027 ops/ms
Iteration   1: 9.830 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.060 ±(99.9%) 4.219 ops/ms [Average]
  (min, avg, max) = (9.830, 10.060, 10.292), stdev = 0.231
  CI (99.9%): [5.840, 14.279] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.858 ops/ms
# Warmup Iteration   2: 7.497 ops/ms
# Warmup Iteration   3: 8.272 ops/ms
Iteration   1: 8.396 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.373 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (8.332, 8.373, 8.396), stdev = 0.035
  CI (99.9%): [7.735, 9.011] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.781 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.007 ms/op
Iteration   1: 3.315 ±(99.9%) 0.004 ms/op
Iteration   2: 3.257 ±(99.9%) 0.010 ms/op
Iteration   3: 3.173 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.248 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (3.173, 3.248, 3.315), stdev = 0.071
  CI (99.9%): [1.945, 4.552] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.875 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.127 ±(99.9%) 0.006 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.064 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.030, 3.064, 3.127), stdev = 0.055
  CI (99.9%): [2.056, 4.071] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.651 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.006 ms/op
Iteration   2: 3.218 ±(99.9%) 0.004 ms/op
Iteration   3: 3.262 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.236 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.218, 3.236, 3.262), stdev = 0.023
  CI (99.9%): [2.808, 3.664] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.275 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.008 ms/op
Iteration   1: 3.747 ±(99.9%) 0.008 ms/op
Iteration   2: 3.811 ±(99.9%) 0.006 ms/op
Iteration   3: 3.767 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.747, 3.775, 3.811), stdev = 0.033
  CI (99.9%): [3.171, 4.379] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.143 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
Iteration   1: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.185 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.713 ms/op
                 createUser·p0.9999: 26.226 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 3.246 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  15.188 ms/op
                 createUser·p0.9999: 26.815 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 3.333 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  14.416 ms/op
                 createUser·p0.9999: 21.706 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292509
  mean =      3.279 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20601 
    [ 2.500,  5.000) = 265970 
    [ 5.000,  7.500) = 4993 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     26.403 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.007 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.132 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  14.267 ms/op
                 existUser·p0.9999: 18.893 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 22.476 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.171 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 29.259 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304019
  mean =      3.158 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22711 
    [ 2.500,  5.000) = 275470 
    [ 5.000,  7.500) = 4889 
    [ 7.500, 10.000) = 522 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     28.082 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 8.212 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.012 ms/op
Iteration   1: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.792 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 21.995 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.792 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  13.091 ms/op
                 getUser·p0.9999: 22.755 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  15.041 ms/op
                 getUser·p0.9999: 22.018 ms/op
                 getUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298260
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14820 
    [ 2.500,  5.000) = 275962 
    [ 5.000,  7.500) = 6692 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.016 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.922 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.314 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.015 ms/op
Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.182 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.208 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   23.265 ms/op

Iteration   2: 3.777 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  14.325 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.841 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.421 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 17.116 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255245
  mean =      3.759 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 248138 
    [ 5.000,  7.500) = 5267 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     20.642 ms/op
     p(99.9990) =     22.808 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.907 ± 2.902  ops/ms
ClientPb.existUser                       thrpt       3  10.311 ± 3.978  ops/ms
ClientPb.getUser                         thrpt       3  10.060 ± 4.219  ops/ms
ClientPb.listUser                        thrpt       3   8.373 ± 0.638  ops/ms
ClientPb.createUser                       avgt       3   3.248 ± 1.303   ms/op
ClientPb.existUser                        avgt       3   3.064 ± 1.007   ms/op
ClientPb.getUser                          avgt       3   3.236 ± 0.428   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 0.604   ms/op
ClientPb.createUser                     sample  292509   3.279 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.092           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.122           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.403           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.213           ms/op
ClientPb.existUser                      sample  304019   3.158 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.082           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.293           ms/op
ClientPb.getUser                        sample  298260   3.216 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.016           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.512           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.183           ms/op
ClientPb.listUser                       sample  255245   3.759 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.642           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.265           ms/op
