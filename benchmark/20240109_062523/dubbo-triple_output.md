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
# Warmup Iteration   1: 5.217 ops/ms
# Warmup Iteration   2: 12.496 ops/ms
# Warmup Iteration   3: 12.547 ops/ms
Iteration   1: 12.881 ops/ms
Iteration   2: 12.911 ops/ms
Iteration   3: 12.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.930 ±(99.9%) 1.093 ops/ms [Average]
  (min, avg, max) = (12.881, 12.930, 12.996), stdev = 0.060
  CI (99.9%): [11.837, 14.022] (assumes normal distribution)


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
# Warmup Iteration   1: 8.751 ops/ms
# Warmup Iteration   2: 13.454 ops/ms
# Warmup Iteration   3: 13.425 ops/ms
Iteration   1: 13.380 ops/ms
Iteration   2: 13.529 ops/ms
Iteration   3: 13.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.444 ±(99.9%) 1.395 ops/ms [Average]
  (min, avg, max) = (13.380, 13.444, 13.529), stdev = 0.076
  CI (99.9%): [12.049, 14.839] (assumes normal distribution)


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
# Warmup Iteration   1: 8.043 ops/ms
# Warmup Iteration   2: 12.804 ops/ms
# Warmup Iteration   3: 12.755 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.743 ±(99.9%) 0.417 ops/ms [Average]
  (min, avg, max) = (12.717, 12.743, 12.757), stdev = 0.023
  CI (99.9%): [12.326, 13.159] (assumes normal distribution)


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
# Warmup Iteration   1: 6.850 ops/ms
# Warmup Iteration   2: 10.275 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.461 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (10.394, 10.461, 10.516), stdev = 0.062
  CI (99.9%): [9.332, 11.591] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.004 ms/op
Iteration   1: 2.530 ±(99.9%) 0.003 ms/op
Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
Iteration   3: 2.456 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (2.456, 2.509, 2.541), stdev = 0.046
  CI (99.9%): [1.665, 3.354] (assumes normal distribution)


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
# Warmup Iteration   1: 3.602 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.417, 2.426, 2.437), stdev = 0.010
  CI (99.9%): [2.238, 2.615] (assumes normal distribution)


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.443 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.434, 2.443, 2.451), stdev = 0.008
  CI (99.9%): [2.291, 2.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.973 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.004 ms/op
Iteration   3: 2.949 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.958 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.949, 2.958, 2.973), stdev = 0.013
  CI (99.9%): [2.726, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 13.489 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.005 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  6.651 ms/op
                 createUser·p0.9999: 12.027 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.763 ms/op
                 createUser·p0.999:  8.479 ms/op
                 createUser·p0.9999: 10.061 ms/op
                 createUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386059
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 187317 
    [ 2.500,  3.750) = 195254 
    [ 3.750,  5.000) = 2676 
    [ 5.000,  6.250) = 257 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 140 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.994 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     14.006 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 12.829 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.321 ms/op
                 existUser·p0.9999: 13.417 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  8.186 ms/op
                 existUser·p0.9999: 11.894 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392449
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 192367 
    [ 2.500,  3.750) = 196749 
    [ 3.750,  5.000) = 2576 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.132 ms/op
     p(99.9900) =     12.825 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  6.559 ms/op
                 getUser·p0.9999: 13.664 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.846 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  8.014 ms/op
                 getUser·p0.9999: 13.672 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  5.925 ms/op
                 getUser·p0.9999: 11.562 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389036
  mean =      2.466 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 195486 
    [ 2.500,  3.750) = 188169 
    [ 3.750,  5.000) = 4108 
    [ 5.000,  6.250) = 773 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      6.554 ms/op
     p(99.9900) =     13.600 ms/op
     p(99.9990) =     13.950 ms/op
     p(99.9999) =     14.090 ms/op
    p(100.0000) =     14.090 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
Iteration   1: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.289 ms/op
                 listUser·p1.00:   11.633 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.898 ms/op
                 listUser·p1.00:   13.025 ms/op

Iteration   3: 3.030 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.511 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 11.531 ms/op
                 listUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316098
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 86876 
    [ 2.500,  3.750) = 188523 
    [ 3.750,  5.000) = 33241 
    [ 5.000,  6.250) = 6015 
    [ 6.250,  7.500) = 639 
    [ 7.500,  8.750) = 287 
    [ 8.750, 10.000) = 206 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.600 ms/op
     p(99.9990) =     12.460 ms/op
     p(99.9999) =     13.025 ms/op
    p(100.0000) =     13.025 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.930 ± 1.093  ops/ms
ClientPb.existUser                       thrpt       3  13.444 ± 1.395  ops/ms
ClientPb.getUser                         thrpt       3  12.743 ± 0.417  ops/ms
ClientPb.listUser                        thrpt       3  10.461 ± 1.129  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.844   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.188   ms/op
ClientPb.getUser                          avgt       3   2.443 ± 0.152   ms/op
ClientPb.listUser                         avgt       3   2.958 ± 0.232   ms/op
ClientPb.createUser                     sample  386059   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.994           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.058           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.352           ms/op
ClientPb.existUser                      sample  392449   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.754           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.132           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.825           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  389036   2.466 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.846           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.554           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.600           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.090           ms/op
ClientPb.listUser                       sample  316098   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.025           ms/op
