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
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 6.335 ops/ms
# Warmup Iteration   3: 9.271 ops/ms
Iteration   1: 9.964 ops/ms
Iteration   2: 9.811 ops/ms
Iteration   3: 9.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.825 ±(99.9%) 2.420 ops/ms [Average]
  (min, avg, max) = (9.700, 9.825, 9.964), stdev = 0.133
  CI (99.9%): [7.405, 12.245] (assumes normal distribution)


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
# Warmup Iteration   1: 3.334 ops/ms
# Warmup Iteration   2: 9.100 ops/ms
# Warmup Iteration   3: 10.217 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.436 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (10.362, 10.436, 10.525), stdev = 0.082
  CI (99.9%): [8.935, 11.937] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 9.192 ops/ms
# Warmup Iteration   3: 9.727 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.722 ops/ms
Iteration   3: 10.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.796 ±(99.9%) 5.505 ops/ms [Average]
  (min, avg, max) = (9.538, 9.796, 10.128), stdev = 0.302
  CI (99.9%): [4.292, 15.301] (assumes normal distribution)


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
# Warmup Iteration   1: 3.263 ops/ms
# Warmup Iteration   2: 7.851 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 8.390 ops/ms
Iteration   3: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.488 ±(99.9%) 2.009 ops/ms [Average]
  (min, avg, max) = (8.390, 8.488, 8.607), stdev = 0.110
  CI (99.9%): [6.480, 10.497] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.761 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.005 ms/op
Iteration   1: 3.098 ±(99.9%) 0.007 ms/op
Iteration   2: 3.130 ±(99.9%) 0.004 ms/op
Iteration   3: 3.273 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.167 ±(99.9%) 1.704 ms/op [Average]
  (min, avg, max) = (3.098, 3.167, 3.273), stdev = 0.093
  CI (99.9%): [1.463, 4.871] (assumes normal distribution)


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
# Warmup Iteration   1: 8.293 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.041 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
Iteration   3: 3.186 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 1.643 ms/op [Average]
  (min, avg, max) = (3.021, 3.082, 3.186), stdev = 0.090
  CI (99.9%): [1.440, 4.725] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.951 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.004 ms/op
Iteration   1: 3.256 ±(99.9%) 0.003 ms/op
Iteration   2: 3.284 ±(99.9%) 0.006 ms/op
Iteration   3: 3.141 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.141, 3.227, 3.284), stdev = 0.076
  CI (99.9%): [1.845, 4.608] (assumes normal distribution)


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
# Warmup Iteration   1: 8.639 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.007 ms/op
Iteration   1: 3.795 ±(99.9%) 0.011 ms/op
Iteration   2: 3.750 ±(99.9%) 0.012 ms/op
Iteration   3: 3.737 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.737, 3.761, 3.795), stdev = 0.030
  CI (99.9%): [3.209, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 7.639 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.630 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.010 ms/op
Iteration   1: 3.275 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  10.563 ms/op
                 createUser·p0.9999: 21.307 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.252 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  21.487 ms/op
                 createUser·p0.9999: 28.350 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  15.138 ms/op
                 createUser·p0.9999: 20.200 ms/op
                 createUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296986
  mean =      3.231 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17349 
    [ 2.500,  5.000) = 273709 
    [ 5.000,  7.500) = 4891 
    [ 7.500, 10.000) = 644 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     16.532 ms/op
     p(99.9900) =     27.437 ms/op
     p(99.9990) =     28.995 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 7.197 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  11.508 ms/op
                 existUser·p0.9999: 19.025 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 19.821 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.711 ms/op
                 existUser·p0.9999: 21.311 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306011
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26034 
    [ 2.500,  5.000) = 274430 
    [ 5.000,  7.500) = 4686 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     19.969 ms/op
     p(99.9990) =     21.820 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 7.822 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
Iteration   1: 3.231 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  14.090 ms/op
                 getUser·p0.9999: 29.924 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 27.952 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  8.315 ms/op
                 getUser·p0.9999: 24.447 ms/op
                 getUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298377
  mean =      3.216 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5339 
    [ 2.500,  5.000) = 287972 
    [ 5.000,  7.500) = 4225 
    [ 7.500, 10.000) = 444 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     14.019 ms/op
     p(99.9900) =     28.939 ms/op
     p(99.9990) =     30.672 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 9.055 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.012 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.149 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  16.077 ms/op
                 listUser·p0.9999: 25.633 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   2: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  18.350 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   3: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.647 ms/op
                 listUser·p0.9999: 14.935 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252995
  mean =      3.792 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 245822 
    [ 5.000,  7.500) = 5800 
    [ 7.500, 10.000) = 721 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     23.311 ms/op
     p(99.9990) =     26.328 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.825 ± 2.420  ops/ms
ClientPb.existUser                       thrpt       3  10.436 ± 1.501  ops/ms
ClientPb.getUser                         thrpt       3   9.796 ± 5.505  ops/ms
ClientPb.listUser                        thrpt       3   8.488 ± 2.009  ops/ms
ClientPb.createUser                       avgt       3   3.167 ± 1.704   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 1.643   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 1.382   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 0.552   ms/op
ClientPb.createUser                     sample  296986   3.231 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.532           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.437           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.950           ms/op
ClientPb.existUser                      sample  306011   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.141           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.207           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.969           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.282           ms/op
ClientPb.getUser                        sample  298377   3.216 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.106           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.685           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.019           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.939           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  252995   3.792 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.311           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.378           ms/op
