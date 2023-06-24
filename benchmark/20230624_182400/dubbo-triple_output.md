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
# Warmup Iteration   1: 2.651 ops/ms
# Warmup Iteration   2: 6.525 ops/ms
# Warmup Iteration   3: 9.259 ops/ms
Iteration   1: 9.732 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 10.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.805 ±(99.9%) 3.119 ops/ms [Average]
  (min, avg, max) = (9.682, 9.805, 10.000), stdev = 0.171
  CI (99.9%): [6.685, 12.924] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 9.230 ops/ms
# Warmup Iteration   3: 9.243 ops/ms
Iteration   1: 10.236 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 10.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.100 ±(99.9%) 3.641 ops/ms [Average]
  (min, avg, max) = (9.871, 10.100, 10.236), stdev = 0.200
  CI (99.9%): [6.459, 13.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.639 ops/ms
# Warmup Iteration   2: 9.342 ops/ms
# Warmup Iteration   3: 9.519 ops/ms
Iteration   1: 9.822 ops/ms
Iteration   2: 9.730 ops/ms
Iteration   3: 10.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.970 ±(99.9%) 6.185 ops/ms [Average]
  (min, avg, max) = (9.730, 9.970, 10.358), stdev = 0.339
  CI (99.9%): [3.784, 16.155] (assumes normal distribution)


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
# Warmup Iteration   1: 3.261 ops/ms
# Warmup Iteration   2: 7.734 ops/ms
# Warmup Iteration   3: 8.376 ops/ms
Iteration   1: 8.367 ops/ms
Iteration   2: 8.577 ops/ms
Iteration   3: 8.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.413 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (8.293, 8.413, 8.577), stdev = 0.147
  CI (99.9%): [5.723, 11.102] (assumes normal distribution)


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
# Warmup Iteration   1: 9.008 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.008 ms/op
Iteration   1: 3.284 ±(99.9%) 0.003 ms/op
Iteration   2: 3.365 ±(99.9%) 0.007 ms/op
Iteration   3: 3.297 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.315 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.284, 3.315, 3.365), stdev = 0.043
  CI (99.9%): [2.527, 4.104] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.267 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
Iteration   3: 3.183 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.129 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.064, 3.129, 3.183), stdev = 0.060
  CI (99.9%): [2.031, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 7.398 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.003 ms/op
Iteration   1: 3.282 ±(99.9%) 0.005 ms/op
Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
Iteration   3: 3.242 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.246 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.214, 3.246, 3.282), stdev = 0.034
  CI (99.9%): [2.624, 3.868] (assumes normal distribution)


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
# Warmup Iteration   1: 9.025 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.161 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.006 ms/op
Iteration   1: 3.753 ±(99.9%) 0.007 ms/op
Iteration   2: 3.743 ±(99.9%) 0.009 ms/op
Iteration   3: 3.753 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.750 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (3.743, 3.750, 3.753), stdev = 0.006
  CI (99.9%): [3.640, 3.859] (assumes normal distribution)


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
# Warmup Iteration   1: 7.820 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   5.317 ms/op
                 createUser·p0.999:  19.386 ms/op
                 createUser·p0.9999: 21.393 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   2: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  16.637 ms/op
                 createUser·p0.9999: 22.120 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.215 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  10.091 ms/op
                 createUser·p0.9999: 18.882 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299768
  mean =      3.202 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22287 
    [ 2.500,  5.000) = 272217 
    [ 5.000,  7.500) = 4479 
    [ 7.500, 10.000) = 359 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.491 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     21.430 ms/op
     p(99.9990) =     22.544 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 6.975 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
Iteration   1: 3.139 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  9.094 ms/op
                 existUser·p0.9999: 20.441 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.110 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 22.934 ms/op
                 existUser·p1.00:   24.216 ms/op

Iteration   3: 3.207 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  12.654 ms/op
                 existUser·p0.9999: 27.100 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304617
  mean =      3.151 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16643 
    [ 2.500,  5.000) = 282169 
    [ 5.000,  7.500) = 4979 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.196 ms/op
     p(99.9900) =     25.872 ms/op
     p(99.9990) =     27.293 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 7.290 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.008 ms/op
Iteration   1: 3.361 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.718 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  18.350 ms/op
                 getUser·p0.9999: 21.381 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  10.078 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   23.790 ms/op

Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.748 ms/op
                 getUser·p0.999:  10.986 ms/op
                 getUser·p0.9999: 29.111 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290977
  mean =      3.297 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11634 
    [ 2.500,  5.000) = 269323 
    [ 5.000,  7.500) = 8734 
    [ 7.500, 10.000) = 765 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     16.647 ms/op
     p(99.9900) =     26.863 ms/op
     p(99.9990) =     29.661 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 9.636 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.013 ms/op
Iteration   1: 3.768 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  18.153 ms/op
                 listUser·p0.9999: 29.705 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.607 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.087 ms/op

Iteration   3: 3.720 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 13.648 ms/op
                 listUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256488
  mean =      3.740 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 250730 
    [ 5.000,  7.500) = 3962 
    [ 7.500, 10.000) = 1080 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.222 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     30.236 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.805 ± 3.119  ops/ms
ClientPb.existUser                       thrpt       3  10.100 ± 3.641  ops/ms
ClientPb.getUser                         thrpt       3   9.970 ± 6.185  ops/ms
ClientPb.listUser                        thrpt       3   8.413 ± 2.690  ops/ms
ClientPb.createUser                       avgt       3   3.315 ± 0.789   ms/op
ClientPb.existUser                        avgt       3   3.129 ± 1.097   ms/op
ClientPb.getUser                          avgt       3   3.246 ± 0.622   ms/op
ClientPb.listUser                         avgt       3   3.750 ± 0.109   ms/op
ClientPb.createUser                     sample  299768   3.202 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.015           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.491           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.991           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.430           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.003           ms/op
ClientPb.existUser                      sample  304617   3.151 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.196           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.460           ms/op
ClientPb.getUser                        sample  290977   3.297 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.679           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.703           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.647           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.863           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081           ms/op
ClientPb.listUser                       sample  256488   3.740 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.607           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.849           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.222           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.003           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.178           ms/op
