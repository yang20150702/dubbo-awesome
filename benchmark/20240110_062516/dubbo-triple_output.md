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
# Warmup Iteration   1: 5.103 ops/ms
# Warmup Iteration   2: 12.280 ops/ms
# Warmup Iteration   3: 12.465 ops/ms
Iteration   1: 12.632 ops/ms
Iteration   2: 12.736 ops/ms
Iteration   3: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.685 ±(99.9%) 0.952 ops/ms [Average]
  (min, avg, max) = (12.632, 12.685, 12.736), stdev = 0.052
  CI (99.9%): [11.733, 13.637] (assumes normal distribution)


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
# Warmup Iteration   1: 8.150 ops/ms
# Warmup Iteration   2: 13.257 ops/ms
# Warmup Iteration   3: 13.314 ops/ms
Iteration   1: 13.287 ops/ms
Iteration   2: 13.399 ops/ms
Iteration   3: 13.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.354 ±(99.9%) 1.086 ops/ms [Average]
  (min, avg, max) = (13.287, 13.354, 13.399), stdev = 0.060
  CI (99.9%): [12.269, 14.440] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ops/ms
# Warmup Iteration   2: 12.670 ops/ms
# Warmup Iteration   3: 12.895 ops/ms
Iteration   1: 12.847 ops/ms
Iteration   2: 12.874 ops/ms
Iteration   3: 12.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.781 ±(99.9%) 2.525 ops/ms [Average]
  (min, avg, max) = (12.622, 12.781, 12.874), stdev = 0.138
  CI (99.9%): [10.256, 15.306] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.637 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.570 ops/ms
Iteration   1: 10.520 ops/ms
Iteration   2: 10.507 ops/ms
Iteration   3: 10.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.505 ±(99.9%) 0.292 ops/ms [Average]
  (min, avg, max) = (10.488, 10.505, 10.520), stdev = 0.016
  CI (99.9%): [10.214, 10.797] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.960 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.003 ms/op
Iteration   3: 2.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.498 ±(99.9%) 0.387 ms/op [Average]
  (min, avg, max) = (2.478, 2.498, 2.521), stdev = 0.021
  CI (99.9%): [2.111, 2.885] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.004 ms/op
Iteration   1: 2.440 ±(99.9%) 0.003 ms/op
Iteration   2: 2.464 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.236 ms/op [Average]
  (min, avg, max) = (2.440, 2.449, 2.464), stdev = 0.013
  CI (99.9%): [2.213, 2.685] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.533 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.467, 2.487, 2.497), stdev = 0.017
  CI (99.9%): [2.173, 2.801] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.005 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.016, 3.023, 3.030), stdev = 0.007
  CI (99.9%): [2.896, 3.151] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.007 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.516 ms/op
                 createUser·p0.50:   2.462 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.498 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  11.184 ms/op
                 createUser·p0.9999: 15.307 ms/op
                 createUser·p1.00:   15.581 ms/op

Iteration   2: 2.494 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   2.458 ms/op
                 createUser·p0.90:   3.203 ms/op
                 createUser·p0.95:   3.523 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  11.711 ms/op
                 createUser·p0.9999: 15.358 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   3: 2.436 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.384 ms/op
                 createUser·p0.90:   3.158 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.006 ms/op
                 createUser·p0.9999: 11.878 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388145
  mean =      2.472 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 520 
    [ 1.250,  2.500) = 206496 
    [ 2.500,  3.750) = 169729 
    [ 3.750,  5.000) = 9865 
    [ 5.000,  6.250) = 893 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     14.787 ms/op
     p(99.9990) =     18.165 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.006 ms/op
Iteration   1: 2.398 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.351 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.542 ms/op
                 existUser·p0.9999: 15.445 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   2: 2.380 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.367 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  8.197 ms/op
                 existUser·p0.9999: 16.288 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.374 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.417 ms/op
                 existUser·p0.50:   2.318 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.342 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  8.463 ms/op
                 existUser·p0.9999: 13.377 ms/op
                 existUser·p1.00:   14.483 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402307
  mean =      2.384 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 235133 
    [ 2.500,  3.750) = 157802 
    [ 3.750,  5.000) = 7866 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.417 ms/op
     p(50.0000) =      2.343 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.801 ms/op
     p(99.9900) =     15.685 ms/op
     p(99.9990) =     17.301 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.897 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 15.480 ms/op
                 getUser·p1.00:   15.745 ms/op

Iteration   2: 2.557 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  9.926 ms/op
                 getUser·p0.9999: 16.122 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.640 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  8.724 ms/op
                 getUser·p0.9999: 12.216 ms/op
                 getUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379403
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 188004 
    [ 2.500,  3.750) = 183945 
    [ 3.750,  5.000) = 6048 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      8.945 ms/op
     p(99.9900) =     14.732 ms/op
     p(99.9990) =     16.509 ms/op
     p(99.9999) =     16.613 ms/op
    p(100.0000) =     16.613 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.767 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 10.924 ms/op
                 listUser·p1.00:   14.549 ms/op

Iteration   2: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.949 ms/op
                 listUser·p0.9999: 11.118 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 11.762 ms/op
                 listUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319724
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 95645 
    [ 2.500,  3.750) = 184816 
    [ 3.750,  5.000) = 31948 
    [ 5.000,  6.250) = 5894 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     11.355 ms/op
     p(99.9990) =     12.528 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.685 ± 0.952  ops/ms
ClientPb.existUser                       thrpt       3  13.354 ± 1.086  ops/ms
ClientPb.getUser                         thrpt       3  12.781 ± 2.525  ops/ms
ClientPb.listUser                        thrpt       3  10.505 ± 0.292  ops/ms
ClientPb.createUser                       avgt       3   2.498 ± 0.387   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.236   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.314   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.127   ms/op
ClientPb.createUser                     sample  388145   2.472 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.516           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.433           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.699           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.787           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.333           ms/op
ClientPb.existUser                      sample  402307   2.384 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.343           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.801           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.685           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.498           ms/op
ClientPb.getUser                        sample  379403   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.636           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.945           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.732           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.613           ms/op
ClientPb.listUser                       sample  319724   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.421           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.355           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.549           ms/op
