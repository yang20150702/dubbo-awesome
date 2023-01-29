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
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 6.335 ops/ms
# Warmup Iteration   3: 9.138 ops/ms
Iteration   1: 9.922 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.960 ±(99.9%) 4.260 ops/ms [Average]
  (min, avg, max) = (9.748, 9.960, 10.211), stdev = 0.234
  CI (99.9%): [5.700, 14.221] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ops/ms
# Warmup Iteration   2: 9.630 ops/ms
# Warmup Iteration   3: 10.548 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.224 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.426 ±(99.9%) 4.359 ops/ms [Average]
  (min, avg, max) = (10.224, 10.426, 10.690), stdev = 0.239
  CI (99.9%): [6.068, 14.785] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.795 ops/ms
# Warmup Iteration   2: 9.794 ops/ms
# Warmup Iteration   3: 9.467 ops/ms
Iteration   1: 9.773 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.123 ±(99.9%) 6.093 ops/ms [Average]
  (min, avg, max) = (9.773, 10.123, 10.438), stdev = 0.334
  CI (99.9%): [4.031, 16.216] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.481 ops/ms
Iteration   1: 8.692 ops/ms
Iteration   2: 8.393 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.599 ±(99.9%) 3.252 ops/ms [Average]
  (min, avg, max) = (8.393, 8.599, 8.711), stdev = 0.178
  CI (99.9%): [5.347, 11.850] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.133 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.004 ms/op
Iteration   1: 3.091 ±(99.9%) 0.005 ms/op
Iteration   2: 3.201 ±(99.9%) 0.004 ms/op
Iteration   3: 3.109 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.134 ±(99.9%) 1.070 ms/op [Average]
  (min, avg, max) = (3.091, 3.134, 3.201), stdev = 0.059
  CI (99.9%): [2.063, 4.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
Iteration   3: 2.987 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.036 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (2.987, 3.036, 3.061), stdev = 0.043
  CI (99.9%): [2.252, 3.821] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.073 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.486 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.001 ms/op
Iteration   1: 3.208 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.107 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.131 ±(99.9%) 1.238 ms/op [Average]
  (min, avg, max) = (3.079, 3.131, 3.208), stdev = 0.068
  CI (99.9%): [1.893, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 9.207 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.005 ms/op
Iteration   1: 3.711 ±(99.9%) 0.008 ms/op
Iteration   2: 3.712 ±(99.9%) 0.008 ms/op
Iteration   3: 3.700 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.708 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.700, 3.708, 3.712), stdev = 0.006
  CI (99.9%): [3.590, 3.826] (assumes normal distribution)


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
# Warmup Iteration   1: 6.990 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.622 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
Iteration   1: 3.296 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  13.991 ms/op
                 createUser·p0.9999: 23.308 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.098 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.236 ms/op
                 createUser·p0.95:   3.318 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 22.490 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   3: 3.138 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.557 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  16.581 ms/op
                 createUser·p0.9999: 29.279 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301831
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24201 
    [ 2.500,  5.000) = 273005 
    [ 5.000,  7.500) = 4035 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     17.733 ms/op
     p(99.9900) =     26.721 ms/op
     p(99.9990) =     30.178 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 7.208 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.419 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 21.510 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  8.794 ms/op
                 existUser·p0.9999: 21.883 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.280 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 21.318 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308538
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18639 
    [ 2.500,  5.000) = 284293 
    [ 5.000,  7.500) = 5069 
    [ 7.500, 10.000) = 242 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.247 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 8.679 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.009 ms/op
Iteration   1: 3.226 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.226 ms/op
                 getUser·p0.999:  19.038 ms/op
                 getUser·p0.9999: 29.609 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   2: 3.154 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302646
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24346 
    [ 2.500,  5.000) = 270973 
    [ 5.000,  7.500) = 6482 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     16.373 ms/op
     p(99.9900) =     27.385 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.922 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.756 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.350 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.032 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.762 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 14.279 ms/op
                 listUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254891
  mean =      3.767 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 246816 
    [ 5.000,  7.500) = 6074 
    [ 7.500, 10.000) = 1284 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.892 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.960 ± 4.260  ops/ms
ClientPb.existUser                       thrpt       3  10.426 ± 4.359  ops/ms
ClientPb.getUser                         thrpt       3  10.123 ± 6.093  ops/ms
ClientPb.listUser                        thrpt       3   8.599 ± 3.252  ops/ms
ClientPb.createUser                       avgt       3   3.134 ± 1.070   ms/op
ClientPb.existUser                        avgt       3   3.036 ± 0.785   ms/op
ClientPb.getUser                          avgt       3   3.131 ± 1.238   ms/op
ClientPb.listUser                         avgt       3   3.708 ± 0.118   ms/op
ClientPb.createUser                     sample  301831   3.175 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.721           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  308538   3.112 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.470           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.774           ms/op
ClientPb.getUser                        sample  302646   3.169 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.385           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  254891   3.767 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.892           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.628           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.578           ms/op
