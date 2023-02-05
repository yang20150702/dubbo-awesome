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
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 6.401 ops/ms
# Warmup Iteration   3: 8.942 ops/ms
Iteration   1: 9.603 ops/ms
Iteration   2: 9.508 ops/ms
Iteration   3: 9.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.537 ±(99.9%) 1.052 ops/ms [Average]
  (min, avg, max) = (9.499, 9.537, 9.603), stdev = 0.058
  CI (99.9%): [8.485, 10.589] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ops/ms
# Warmup Iteration   2: 9.386 ops/ms
# Warmup Iteration   3: 10.055 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.232 ±(99.9%) 5.986 ops/ms [Average]
  (min, avg, max) = (9.930, 10.232, 10.581), stdev = 0.328
  CI (99.9%): [4.246, 16.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.532 ops/ms
# Warmup Iteration   2: 9.290 ops/ms
# Warmup Iteration   3: 9.491 ops/ms
Iteration   1: 10.120 ops/ms
Iteration   2: 10.126 ops/ms
Iteration   3: 10.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.128 ±(99.9%) 0.162 ops/ms [Average]
  (min, avg, max) = (10.120, 10.128, 10.137), stdev = 0.009
  CI (99.9%): [9.966, 10.290] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.084 ops/ms
# Warmup Iteration   2: 7.510 ops/ms
# Warmup Iteration   3: 8.355 ops/ms
Iteration   1: 8.631 ops/ms
Iteration   2: 8.607 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.575 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (8.487, 8.575, 8.631), stdev = 0.077
  CI (99.9%): [7.164, 9.986] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.003 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.435 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.006 ms/op
Iteration   1: 3.173 ±(99.9%) 0.006 ms/op
Iteration   2: 3.310 ±(99.9%) 0.009 ms/op
Iteration   3: 3.218 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.234 ±(99.9%) 1.268 ms/op [Average]
  (min, avg, max) = (3.173, 3.234, 3.310), stdev = 0.070
  CI (99.9%): [1.966, 4.502] (assumes normal distribution)


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
# Warmup Iteration   1: 7.329 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.009 ms/op
Iteration   3: 3.044 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.028 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.015, 3.028, 3.044), stdev = 0.015
  CI (99.9%): [2.755, 3.301] (assumes normal distribution)


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
# Warmup Iteration   1: 6.878 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.003 ms/op
Iteration   1: 3.153 ±(99.9%) 0.003 ms/op
Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
Iteration   3: 3.303 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.245 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (3.153, 3.245, 3.303), stdev = 0.081
  CI (99.9%): [1.766, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 8.558 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.009 ms/op
Iteration   1: 3.848 ±(99.9%) 0.007 ms/op
Iteration   2: 3.803 ±(99.9%) 0.006 ms/op
Iteration   3: 3.700 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.784 ±(99.9%) 1.387 ms/op [Average]
  (min, avg, max) = (3.700, 3.784, 3.848), stdev = 0.076
  CI (99.9%): [2.397, 5.171] (assumes normal distribution)


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
# Warmup Iteration   1: 8.015 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.137 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.489 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  10.471 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  8.659 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.160 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 27.125 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302549
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19545 
    [ 2.500,  5.000) = 278572 
    [ 5.000,  7.500) = 3778 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     17.709 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     27.261 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 7.445 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.358 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  12.993 ms/op
                 existUser·p0.9999: 21.819 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   2: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.546 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.915 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 27.606 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 23.858 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305575
  mean =      3.140 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19936 
    [ 2.500,  5.000) = 279236 
    [ 5.000,  7.500) = 5574 
    [ 7.500, 10.000) = 377 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     25.274 ms/op
     p(99.9990) =     28.197 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 8.690 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.278 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  18.027 ms/op
                 getUser·p0.9999: 23.960 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  11.662 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  9.754 ms/op
                 getUser·p0.9999: 21.191 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296025
  mean =      3.243 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17348 
    [ 2.500,  5.000) = 269591 
    [ 5.000,  7.500) = 7981 
    [ 7.500, 10.000) = 716 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     23.213 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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
# Warmup Iteration   1: 7.590 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.012 ms/op
Iteration   1: 3.774 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.929 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  18.192 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.794 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 22.807 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.851 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.416 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.221 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252159
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 243038 
    [ 5.000,  7.500) = 6972 
    [ 7.500, 10.000) = 1359 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     16.737 ms/op
     p(99.9900) =     22.505 ms/op
     p(99.9990) =     23.395 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.537 ± 1.052  ops/ms
ClientPb.existUser                       thrpt       3  10.232 ± 5.986  ops/ms
ClientPb.getUser                         thrpt       3  10.128 ± 0.162  ops/ms
ClientPb.listUser                        thrpt       3   8.575 ± 1.411  ops/ms
ClientPb.createUser                       avgt       3   3.234 ± 1.268   ms/op
ClientPb.existUser                        avgt       3   3.028 ± 0.273   ms/op
ClientPb.getUser                          avgt       3   3.245 ± 1.479   ms/op
ClientPb.listUser                         avgt       3   3.784 ± 1.387   ms/op
ClientPb.createUser                     sample  302549   3.170 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.728           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.709           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.887           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.164           ms/op
ClientPb.existUser                      sample  305575   3.140 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.372           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.387           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.620           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.274           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  296025   3.243 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.011           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.650           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.434           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.213           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.019           ms/op
ClientPb.listUser                       sample  252159   3.806 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.416           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.737           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.505           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
