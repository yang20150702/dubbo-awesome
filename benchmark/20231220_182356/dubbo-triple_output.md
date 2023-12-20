# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.567 ops/ms
# Warmup Iteration   2: 12.057 ops/ms
# Warmup Iteration   3: 12.392 ops/ms
Iteration   1: 12.449 ops/ms
Iteration   2: 12.563 ops/ms
Iteration   3: 12.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.547 ±(99.9%) 1.668 ops/ms [Average]
  (min, avg, max) = (12.449, 12.547, 12.630), stdev = 0.091
  CI (99.9%): [10.879, 14.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.255 ops/ms
# Warmup Iteration   2: 12.953 ops/ms
# Warmup Iteration   3: 12.858 ops/ms
Iteration   1: 12.756 ops/ms
Iteration   2: 12.790 ops/ms
Iteration   3: 12.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.711 ±(99.9%) 1.997 ops/ms [Average]
  (min, avg, max) = (12.586, 12.711, 12.790), stdev = 0.109
  CI (99.9%): [10.714, 14.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.662 ops/ms
# Warmup Iteration   2: 12.183 ops/ms
# Warmup Iteration   3: 12.515 ops/ms
Iteration   1: 12.702 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.734 ±(99.9%) 0.671 ops/ms [Average]
  (min, avg, max) = (12.702, 12.734, 12.774), stdev = 0.037
  CI (99.9%): [12.063, 13.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.760 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.353 ops/ms
Iteration   1: 10.480 ops/ms
Iteration   2: 10.572 ops/ms
Iteration   3: 10.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.540 ±(99.9%) 0.944 ops/ms [Average]
  (min, avg, max) = (10.480, 10.540, 10.572), stdev = 0.052
  CI (99.9%): [9.596, 11.484] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.561 ±(99.9%) 0.275 ms/op [Average]
  (min, avg, max) = (2.547, 2.561, 2.577), stdev = 0.015
  CI (99.9%): [2.286, 2.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.491 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.489 ±(99.9%) 0.041 ms/op [Average]
  (min, avg, max) = (2.487, 2.489, 2.491), stdev = 0.002
  CI (99.9%): [2.448, 2.531] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.494 ±(99.9%) 0.206 ms/op [Average]
  (min, avg, max) = (2.484, 2.494, 2.507), stdev = 0.011
  CI (99.9%): [2.289, 2.700] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.761 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
Iteration   3: 3.015 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.995, 3.018, 3.046), stdev = 0.026
  CI (99.9%): [2.548, 3.488] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.210 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.564 ±(99.9%) 0.006 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.939 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  11.944 ms/op
                 createUser·p0.9999: 13.989 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  9.775 ms/op
                 createUser·p0.9999: 14.287 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.260 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  9.487 ms/op
                 createUser·p0.9999: 11.233 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374602
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 178269 
    [ 2.500,  3.750) = 191513 
    [ 3.750,  5.000) = 3700 
    [ 5.000,  6.250) = 606 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.886 ms/op
     p(99.9990) =     14.549 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  6.193 ms/op
                 existUser·p0.9999: 14.135 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   2: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  5.640 ms/op
                 existUser·p0.9999: 14.528 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  6.235 ms/op
                 existUser·p0.9999: 11.985 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394932
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 198667 
    [ 2.500,  3.750) = 193027 
    [ 3.750,  5.000) = 2509 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      5.849 ms/op
     p(99.9900) =     14.091 ms/op
     p(99.9990) =     15.205 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  7.070 ms/op
                 getUser·p0.9999: 16.235 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.045 ms/op
                 getUser·p0.999:  5.868 ms/op
                 getUser·p0.9999: 18.973 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.805 ms/op
                 getUser·p0.9999: 12.004 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380413
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 186078 
    [ 2.500,  5.000) = 192857 
    [ 5.000,  7.500) = 1130 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      7.091 ms/op
     p(99.9900) =     16.415 ms/op
     p(99.9990) =     19.390 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.718 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.008 ms/op
Iteration   1: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.533 ms/op
                 listUser·p0.999:  8.725 ms/op
                 listUser·p0.9999: 11.333 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  10.018 ms/op
                 listUser·p0.9999: 14.638 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.605 ms/op
                 listUser·p0.9999: 13.561 ms/op
                 listUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317710
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 92157 
    [ 2.500,  3.750) = 185624 
    [ 3.750,  5.000) = 32450 
    [ 5.000,  6.250) = 5973 
    [ 6.250,  7.500) = 708 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.594 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     13.794 ms/op
     p(99.9990) =     14.939 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.547 ± 1.668  ops/ms
ClientPb.existUser                       thrpt       3  12.711 ± 1.997  ops/ms
ClientPb.getUser                         thrpt       3  12.734 ± 0.671  ops/ms
ClientPb.listUser                        thrpt       3  10.540 ± 0.944  ops/ms
ClientPb.createUser                       avgt       3   2.561 ± 0.275   ms/op
ClientPb.existUser                        avgt       3   2.489 ± 0.041   ms/op
ClientPb.getUser                          avgt       3   2.494 ± 0.206   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.470   ms/op
ClientPb.createUser                     sample  374602   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.601           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.886           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.237           ms/op
ClientPb.existUser                      sample  394932   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.785           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.849           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.335           ms/op
ClientPb.getUser                        sample  380413   2.521 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.762           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.236           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.091           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          20.021           ms/op
ClientPb.listUser                       sample  317710   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.878           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.594           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.794           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.302           ms/op
