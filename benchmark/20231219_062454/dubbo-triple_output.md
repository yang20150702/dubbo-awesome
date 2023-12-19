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
# Warmup Iteration   1: 5.012 ops/ms
# Warmup Iteration   2: 11.842 ops/ms
# Warmup Iteration   3: 12.126 ops/ms
Iteration   1: 12.333 ops/ms
Iteration   2: 12.513 ops/ms
Iteration   3: 12.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.436 ±(99.9%) 1.697 ops/ms [Average]
  (min, avg, max) = (12.333, 12.436, 12.513), stdev = 0.093
  CI (99.9%): [10.739, 14.133] (assumes normal distribution)


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
# Warmup Iteration   1: 8.295 ops/ms
# Warmup Iteration   2: 13.023 ops/ms
# Warmup Iteration   3: 13.081 ops/ms
Iteration   1: 13.221 ops/ms
Iteration   2: 13.278 ops/ms
Iteration   3: 13.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.201 ±(99.9%) 1.620 ops/ms [Average]
  (min, avg, max) = (13.104, 13.201, 13.278), stdev = 0.089
  CI (99.9%): [11.581, 14.821] (assumes normal distribution)


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
# Warmup Iteration   1: 7.755 ops/ms
# Warmup Iteration   2: 12.272 ops/ms
# Warmup Iteration   3: 12.498 ops/ms
Iteration   1: 12.592 ops/ms
Iteration   2: 12.630 ops/ms
Iteration   3: 12.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.603 ±(99.9%) 0.423 ops/ms [Average]
  (min, avg, max) = (12.588, 12.603, 12.630), stdev = 0.023
  CI (99.9%): [12.181, 13.026] (assumes normal distribution)


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
# Warmup Iteration   1: 6.392 ops/ms
# Warmup Iteration   2: 10.092 ops/ms
# Warmup Iteration   3: 10.483 ops/ms
Iteration   1: 10.410 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.383 ±(99.9%) 0.598 ops/ms [Average]
  (min, avg, max) = (10.346, 10.383, 10.410), stdev = 0.033
  CI (99.9%): [9.785, 10.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.558 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.547, 2.558, 2.571), stdev = 0.012
  CI (99.9%): [2.339, 2.776] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.773 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
Iteration   3: 2.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.463, 2.476, 2.498), stdev = 0.019
  CI (99.9%): [2.122, 2.830] (assumes normal distribution)


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
# Warmup Iteration   1: 4.041 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.475, 2.489, 2.500), stdev = 0.013
  CI (99.9%): [2.252, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.005 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.998, 3.011, 3.026), stdev = 0.014
  CI (99.9%): [2.752, 3.271] (assumes normal distribution)


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  11.155 ms/op
                 createUser·p0.9999: 13.788 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 12.499 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.990 ms/op
                 createUser·p0.999:  8.943 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375409
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 179124 
    [ 2.500,  3.750) = 191816 
    [ 3.750,  5.000) = 3485 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     13.498 ms/op
     p(99.9990) =     14.176 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  10.655 ms/op
                 existUser·p0.9999: 14.197 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  6.198 ms/op
                 existUser·p0.9999: 13.325 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  9.138 ms/op
                 existUser·p0.9999: 11.986 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382477
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 28 
    [ 1.250,  2.500) = 186450 
    [ 2.500,  3.750) = 192306 
    [ 3.750,  5.000) = 2820 
    [ 5.000,  6.250) = 442 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     13.660 ms/op
     p(99.9990) =     14.897 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  11.385 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   13.959 ms/op

Iteration   2: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.783 ms/op
                 getUser·p0.999:  9.590 ms/op
                 getUser·p0.9999: 12.700 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  7.675 ms/op
                 getUser·p0.9999: 11.207 ms/op
                 getUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381990
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 80 
    [ 1.250,  2.500) = 188567 
    [ 2.500,  3.750) = 188917 
    [ 3.750,  5.000) = 3734 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.290 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.791 ms/op
     p(99.9999) =     13.959 ms/op
    p(100.0000) =     13.959 ms/op


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
# Warmup Iteration   1: 4.678 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.009 ms/op
Iteration   1: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.230 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.852 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.732 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 11.263 ms/op
                 listUser·p1.00:   11.829 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.618 ms/op
                 listUser·p0.9999: 11.885 ms/op
                 listUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317220
  mean =      3.023 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 92570 
    [ 2.500,  3.750) = 184741 
    [ 3.750,  5.000) = 32064 
    [ 5.000,  6.250) = 6327 
    [ 6.250,  7.500) = 693 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.663 ms/op
     p(99.9900) =     11.469 ms/op
     p(99.9990) =     12.105 ms/op
     p(99.9999) =     13.795 ms/op
    p(100.0000) =     13.795 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.436 ± 1.697  ops/ms
ClientPb.existUser                       thrpt       3  13.201 ± 1.620  ops/ms
ClientPb.getUser                         thrpt       3  12.603 ± 0.423  ops/ms
ClientPb.listUser                        thrpt       3  10.383 ± 0.598  ops/ms
ClientPb.createUser                       avgt       3   2.558 ± 0.218   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.354   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.237   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.260   ms/op
ClientPb.createUser                     sample  375409   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.969           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.498           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.221           ms/op
ClientPb.existUser                      sample  382477   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.152           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.660           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.122           ms/op
ClientPb.getUser                        sample  381990   2.511 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.664           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.290           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.009           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.959           ms/op
ClientPb.listUser                       sample  317220   3.023 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.852           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.469           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.795           ms/op
