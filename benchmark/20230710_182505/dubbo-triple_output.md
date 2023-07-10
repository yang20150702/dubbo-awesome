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
# Warmup Iteration   1: 2.437 ops/ms
# Warmup Iteration   2: 5.983 ops/ms
# Warmup Iteration   3: 9.296 ops/ms
Iteration   1: 9.713 ops/ms
Iteration   2: 9.493 ops/ms
Iteration   3: 9.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.554 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (9.457, 9.554, 9.713), stdev = 0.139
  CI (99.9%): [7.024, 12.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.150 ops/ms
# Warmup Iteration   2: 8.843 ops/ms
# Warmup Iteration   3: 10.237 ops/ms
Iteration   1: 10.216 ops/ms
Iteration   2: 9.965 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.275 ±(99.9%) 6.286 ops/ms [Average]
  (min, avg, max) = (9.965, 10.275, 10.646), stdev = 0.345
  CI (99.9%): [3.989, 16.561] (assumes normal distribution)


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
# Warmup Iteration   1: 3.439 ops/ms
# Warmup Iteration   2: 9.078 ops/ms
# Warmup Iteration   3: 9.802 ops/ms
Iteration   1: 9.653 ops/ms
Iteration   2: 9.670 ops/ms
Iteration   3: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.812 ±(99.9%) 4.739 ops/ms [Average]
  (min, avg, max) = (9.653, 9.812, 10.112), stdev = 0.260
  CI (99.9%): [5.073, 14.551] (assumes normal distribution)


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
# Warmup Iteration   1: 3.513 ops/ms
# Warmup Iteration   2: 7.736 ops/ms
# Warmup Iteration   3: 8.385 ops/ms
Iteration   1: 8.540 ops/ms
Iteration   2: 8.446 ops/ms
Iteration   3: 8.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.467 ±(99.9%) 1.198 ops/ms [Average]
  (min, avg, max) = (8.414, 8.467, 8.540), stdev = 0.066
  CI (99.9%): [7.269, 9.664] (assumes normal distribution)


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
# Warmup Iteration   1: 8.261 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.008 ms/op
Iteration   1: 3.293 ±(99.9%) 0.005 ms/op
Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
Iteration   3: 3.164 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.275 ±(99.9%) 1.879 ms/op [Average]
  (min, avg, max) = (3.164, 3.275, 3.367), stdev = 0.103
  CI (99.9%): [1.395, 5.154] (assumes normal distribution)


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
# Warmup Iteration   1: 8.396 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.004 ms/op
Iteration   1: 3.192 ±(99.9%) 0.008 ms/op
Iteration   2: 3.145 ±(99.9%) 0.003 ms/op
Iteration   3: 3.118 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.152 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.118, 3.152, 3.192), stdev = 0.037
  CI (99.9%): [2.473, 3.830] (assumes normal distribution)


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
# Warmup Iteration   1: 8.579 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.004 ms/op
Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
Iteration   3: 3.162 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.162 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (3.147, 3.162, 3.177), stdev = 0.015
  CI (99.9%): [2.890, 3.434] (assumes normal distribution)


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
# Warmup Iteration   1: 10.160 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.005 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
Iteration   2: 3.728 ±(99.9%) 0.010 ms/op
Iteration   3: 3.781 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (3.728, 3.773, 3.810), stdev = 0.042
  CI (99.9%): [3.008, 4.537] (assumes normal distribution)


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
# Warmup Iteration   1: 8.328 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.008 ms/op
Iteration   1: 3.318 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  16.872 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  11.999 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   3: 3.265 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.464 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  10.665 ms/op
                 createUser·p0.9999: 27.015 ms/op
                 createUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294736
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24487 
    [ 2.500,  5.000) = 262982 
    [ 5.000,  7.500) = 6330 
    [ 7.500, 10.000) = 593 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     12.833 ms/op
     p(99.9900) =     25.957 ms/op
     p(99.9990) =     28.008 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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
# Warmup Iteration   1: 8.618 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.669 ms/op
                 existUser·p0.9999: 22.644 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.346 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  19.580 ms/op
                 existUser·p0.9999: 26.870 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 26.051 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298274
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21090 
    [ 2.500,  5.000) = 271661 
    [ 5.000,  7.500) = 4703 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.241 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.198 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 8.036 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.559 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.391 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.348 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.978 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.348 ms/op
                 getUser·p0.999:  18.055 ms/op
                 getUser·p0.9999: 20.484 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  8.930 ms/op
                 getUser·p0.9999: 22.781 ms/op
                 getUser·p1.00:   23.724 ms/op

Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  14.636 ms/op
                 getUser·p0.9999: 21.563 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295779
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11254 
    [ 2.500,  5.000) = 276120 
    [ 5.000,  7.500) = 7373 
    [ 7.500, 10.000) = 518 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.119 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 9.850 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.014 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.751 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.728 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.123 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255112
  mean =      3.762 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 246700 
    [ 5.000,  7.500) = 6560 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.027 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.554 ± 2.529  ops/ms
ClientPb.existUser                       thrpt       3  10.275 ± 6.286  ops/ms
ClientPb.getUser                         thrpt       3   9.812 ± 4.739  ops/ms
ClientPb.listUser                        thrpt       3   8.467 ± 1.198  ops/ms
ClientPb.createUser                       avgt       3   3.275 ± 1.879   ms/op
ClientPb.existUser                        avgt       3   3.152 ± 0.678   ms/op
ClientPb.getUser                          avgt       3   3.162 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.764   ms/op
ClientPb.createUser                     sample  294736   3.253 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.464           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          12.833           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.957           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.639           ms/op
ClientPb.existUser                      sample  298274   3.217 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.026           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.173           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.754           ms/op
ClientPb.getUser                        sample  295779   3.245 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.899           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.625           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.119           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.724           ms/op
ClientPb.listUser                       sample  255112   3.762 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.839           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
