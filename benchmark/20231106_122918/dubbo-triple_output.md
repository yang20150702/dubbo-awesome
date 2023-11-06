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
# Warmup Iteration   1: 4.946 ops/ms
# Warmup Iteration   2: 11.992 ops/ms
# Warmup Iteration   3: 12.338 ops/ms
Iteration   1: 12.569 ops/ms
Iteration   2: 12.719 ops/ms
Iteration   3: 12.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.683 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (12.569, 12.683, 12.761), stdev = 0.101
  CI (99.9%): [10.844, 14.523] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.195 ops/ms
# Warmup Iteration   2: 13.078 ops/ms
# Warmup Iteration   3: 13.053 ops/ms
Iteration   1: 13.291 ops/ms
Iteration   2: 13.180 ops/ms
Iteration   3: 13.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.200 ±(99.9%) 1.504 ops/ms [Average]
  (min, avg, max) = (13.130, 13.200, 13.291), stdev = 0.082
  CI (99.9%): [11.696, 14.704] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.552 ops/ms
# Warmup Iteration   2: 12.523 ops/ms
# Warmup Iteration   3: 12.840 ops/ms
Iteration   1: 12.901 ops/ms
Iteration   2: 12.912 ops/ms
Iteration   3: 13.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.953 ±(99.9%) 1.475 ops/ms [Average]
  (min, avg, max) = (12.901, 12.953, 13.046), stdev = 0.081
  CI (99.9%): [11.478, 14.428] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.548 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 10.581 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.802 ops/ms
Iteration   3: 10.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.664 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (10.595, 10.664, 10.802), stdev = 0.119
  CI (99.9%): [8.488, 12.841] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.515 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
Iteration   3: 2.506 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.506, 2.528, 2.562), stdev = 0.030
  CI (99.9%): [1.978, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
Iteration   2: 2.423 ±(99.9%) 0.003 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.442 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.423, 2.442, 2.458), stdev = 0.017
  CI (99.9%): [2.127, 2.756] (assumes normal distribution)


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.495 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.487, 2.495, 2.502), stdev = 0.008
  CI (99.9%): [2.354, 2.636] (assumes normal distribution)


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 3.001 ±(99.9%) 0.007 ms/op
Iteration   2: 2.989 ±(99.9%) 0.004 ms/op
Iteration   3: 2.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.992 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.987, 2.992, 3.001), stdev = 0.007
  CI (99.9%): [2.859, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 4.135 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.705 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.103 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  12.038 ms/op
                 createUser·p0.9999: 15.884 ms/op
                 createUser·p1.00:   16.286 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.805 ms/op
                 createUser·p0.999:  9.496 ms/op
                 createUser·p0.9999: 14.311 ms/op
                 createUser·p1.00:   15.401 ms/op

Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.954 ms/op
                 createUser·p0.999:  9.511 ms/op
                 createUser·p0.9999: 13.737 ms/op
                 createUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375837
  mean =      2.552 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180436 
    [ 2.500,  3.750) = 190633 
    [ 3.750,  5.000) = 3873 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     14.848 ms/op
     p(99.9990) =     16.011 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  5.570 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   13.763 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  7.811 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  8.724 ms/op
                 existUser·p0.9999: 11.994 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387633
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 190952 
    [ 2.500,  3.750) = 193111 
    [ 3.750,  5.000) = 2551 
    [ 5.000,  6.250) = 536 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      7.564 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.752 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  12.071 ms/op
                 getUser·p0.9999: 13.718 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.638 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  9.159 ms/op
                 getUser·p0.9999: 14.159 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.429 ms/op
                 getUser·p0.9999: 16.581 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383204
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 188870 
    [ 2.500,  3.750) = 189285 
    [ 3.750,  5.000) = 3703 
    [ 5.000,  6.250) = 870 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 141 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      8.444 ms/op
     p(99.9900) =     14.584 ms/op
     p(99.9990) =     18.073 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.009 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.325 ms/op
                 listUser·p0.9999: 12.867 ms/op
                 listUser·p1.00:   13.418 ms/op

Iteration   2: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  8.907 ms/op
                 listUser·p0.9999: 10.224 ms/op
                 listUser·p1.00:   10.617 ms/op

Iteration   3: 3.026 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 11.514 ms/op
                 listUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319606
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 98095 
    [ 2.500,  3.750) = 182702 
    [ 3.750,  5.000) = 30761 
    [ 5.000,  6.250) = 6569 
    [ 6.250,  7.500) = 727 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 272 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     11.633 ms/op
     p(99.9990) =     13.232 ms/op
     p(99.9999) =     13.418 ms/op
    p(100.0000) =     13.418 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.683 ± 1.839  ops/ms
ClientPb.existUser                       thrpt       3  13.200 ± 1.504  ops/ms
ClientPb.getUser                         thrpt       3  12.953 ± 1.475  ops/ms
ClientPb.listUser                        thrpt       3  10.664 ± 2.177  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   2.442 ± 0.314   ms/op
ClientPb.getUser                          avgt       3   2.495 ± 0.141   ms/op
ClientPb.listUser                         avgt       3   2.992 ± 0.134   ms/op
ClientPb.createUser                     sample  375837   2.552 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.535           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.848           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.286           ms/op
ClientPb.existUser                      sample  387633   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.909           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.564           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.763           ms/op
ClientPb.getUser                        sample  383204   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.444           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.584           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.005           ms/op
ClientPb.listUser                       sample  319606   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.779           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.633           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.418           ms/op
