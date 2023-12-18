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
# Warmup Iteration   1: 4.375 ops/ms
# Warmup Iteration   2: 12.060 ops/ms
# Warmup Iteration   3: 12.164 ops/ms
Iteration   1: 12.395 ops/ms
Iteration   2: 12.270 ops/ms
Iteration   3: 12.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.336 ±(99.9%) 1.155 ops/ms [Average]
  (min, avg, max) = (12.270, 12.336, 12.395), stdev = 0.063
  CI (99.9%): [11.181, 13.491] (assumes normal distribution)


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
# Warmup Iteration   1: 7.983 ops/ms
# Warmup Iteration   2: 12.853 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 12.920 ops/ms
Iteration   2: 13.002 ops/ms
Iteration   3: 12.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 1.914 ops/ms [Average]
  (min, avg, max) = (12.794, 12.905, 13.002), stdev = 0.105
  CI (99.9%): [10.991, 14.820] (assumes normal distribution)


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
# Warmup Iteration   1: 7.045 ops/ms
# Warmup Iteration   2: 12.384 ops/ms
# Warmup Iteration   3: 12.612 ops/ms
Iteration   1: 12.621 ops/ms
Iteration   2: 12.512 ops/ms
Iteration   3: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.600 ±(99.9%) 1.461 ops/ms [Average]
  (min, avg, max) = (12.512, 12.600, 12.668), stdev = 0.080
  CI (99.9%): [11.140, 14.061] (assumes normal distribution)


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
# Warmup Iteration   1: 6.322 ops/ms
# Warmup Iteration   2: 10.112 ops/ms
# Warmup Iteration   3: 10.310 ops/ms
Iteration   1: 10.358 ops/ms
Iteration   2: 10.466 ops/ms
Iteration   3: 10.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.366 ±(99.9%) 1.767 ops/ms [Average]
  (min, avg, max) = (10.273, 10.366, 10.466), stdev = 0.097
  CI (99.9%): [8.599, 12.133] (assumes normal distribution)


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.568 ±(99.9%) 0.003 ms/op
Iteration   1: 2.531 ±(99.9%) 0.005 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.566 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.530, 2.542, 2.566), stdev = 0.021
  CI (99.9%): [2.163, 2.921] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.496 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.483, 2.496, 2.507), stdev = 0.012
  CI (99.9%): [2.273, 2.718] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.004 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.004 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.569 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.560, 2.569, 2.583), stdev = 0.012
  CI (99.9%): [2.343, 2.795] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
Iteration   1: 3.044 ±(99.9%) 0.004 ms/op
Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.019, 3.033, 3.044), stdev = 0.013
  CI (99.9%): [2.798, 3.268] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.735 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  10.932 ms/op
                 createUser·p0.9999: 13.556 ms/op
                 createUser·p1.00:   14.467 ms/op

Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 12.423 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  8.135 ms/op
                 createUser·p0.9999: 11.197 ms/op
                 createUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377665
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 181118 
    [ 2.500,  3.750) = 193126 
    [ 3.750,  5.000) = 2690 
    [ 5.000,  6.250) = 243 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.699 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     13.049 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.677 ms/op

Iteration   2: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  6.802 ms/op
                 existUser·p0.9999: 12.333 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.688 ms/op
                 existUser·p0.999:  8.547 ms/op
                 existUser·p0.9999: 11.950 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396923
  mean =      2.416 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 201173 
    [ 2.500,  5.000) = 195122 
    [ 5.000,  7.500) = 207 
    [ 7.500, 10.000) = 150 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.539 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     13.882 ms/op
     p(99.9990) =     19.818 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.617 ms/op
                 getUser·p0.999:  10.928 ms/op
                 getUser·p0.9999: 13.487 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  8.721 ms/op
                 getUser·p0.9999: 16.083 ms/op
                 getUser·p1.00:   16.679 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  9.254 ms/op
                 getUser·p0.9999: 11.894 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379045
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 185742 
    [ 2.500,  3.750) = 189330 
    [ 3.750,  5.000) = 3045 
    [ 5.000,  6.250) = 423 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     13.813 ms/op
     p(99.9990) =     16.613 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.856 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 10.996 ms/op
                 listUser·p1.00:   11.928 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.006 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.874 ms/op
                 listUser·p0.999:  9.741 ms/op
                 listUser·p0.9999: 11.649 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   3: 3.048 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.896 ms/op
                 listUser·p0.9999: 11.993 ms/op
                 listUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 313798
  mean =      3.056 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 84450 
    [ 2.500,  3.750) = 186998 
    [ 3.750,  5.000) = 34279 
    [ 5.000,  6.250) = 6324 
    [ 6.250,  7.500) = 938 
    [ 7.500,  8.750) = 234 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     12.237 ms/op
     p(99.9999) =     12.468 ms/op
    p(100.0000) =     12.468 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.336 ± 1.155  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 1.914  ops/ms
ClientPb.getUser                         thrpt       3  12.600 ± 1.461  ops/ms
ClientPb.listUser                        thrpt       3  10.366 ± 1.767  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.379   ms/op
ClientPb.existUser                        avgt       3   2.496 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.569 ± 0.226   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.235   ms/op
ClientPb.createUser                     sample  377665   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.825           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.699           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.467           ms/op
ClientPb.existUser                      sample  396923   2.416 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.454           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.882           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.677           ms/op
ClientPb.getUser                        sample  379045   2.530 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.735           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.813           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.679           ms/op
ClientPb.listUser                       sample  313798   3.056 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.829           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.468           ms/op
