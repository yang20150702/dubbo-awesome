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
# Warmup Iteration   1: 4.759 ops/ms
# Warmup Iteration   2: 11.863 ops/ms
# Warmup Iteration   3: 12.062 ops/ms
Iteration   1: 12.293 ops/ms
Iteration   2: 12.434 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.408 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (12.293, 12.408, 12.498), stdev = 0.105
  CI (99.9%): [10.496, 14.321] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.464 ops/ms
# Warmup Iteration   2: 12.724 ops/ms
# Warmup Iteration   3: 13.136 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.063 ops/ms
Iteration   3: 13.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.043 ±(99.9%) 0.460 ops/ms [Average]
  (min, avg, max) = (13.015, 13.043, 13.063), stdev = 0.025
  CI (99.9%): [12.584, 13.503] (assumes normal distribution)


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
# Warmup Iteration   1: 7.456 ops/ms
# Warmup Iteration   2: 12.247 ops/ms
# Warmup Iteration   3: 12.499 ops/ms
Iteration   1: 12.774 ops/ms
Iteration   2: 12.514 ops/ms
Iteration   3: 12.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.605 ±(99.9%) 2.674 ops/ms [Average]
  (min, avg, max) = (12.514, 12.605, 12.774), stdev = 0.147
  CI (99.9%): [9.931, 15.279] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ops/ms
# Warmup Iteration   2: 10.318 ops/ms
# Warmup Iteration   3: 10.285 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.429 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (10.379, 10.429, 10.517), stdev = 0.076
  CI (99.9%): [9.045, 11.813] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.003 ms/op
Iteration   1: 2.568 ±(99.9%) 0.004 ms/op
Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
Iteration   3: 2.570 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.573 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (2.568, 2.573, 2.582), stdev = 0.007
  CI (99.9%): [2.438, 2.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.462, 2.474, 2.492), stdev = 0.016
  CI (99.9%): [2.187, 2.761] (assumes normal distribution)


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.004 ms/op
Iteration   1: 2.529 ±(99.9%) 0.005 ms/op
Iteration   2: 2.513 ±(99.9%) 0.003 ms/op
Iteration   3: 2.530 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.524 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (2.513, 2.524, 2.530), stdev = 0.009
  CI (99.9%): [2.354, 2.694] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.912 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.033 ms/op [Average]
  (min, avg, max) = (3.031, 3.033, 3.034), stdev = 0.002
  CI (99.9%): [3.000, 3.066] (assumes normal distribution)


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.726 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.006 ms/op
Iteration   1: 2.590 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   3.924 ms/op
                 createUser·p0.999:  11.688 ms/op
                 createUser·p0.9999: 13.904 ms/op
                 createUser·p1.00:   14.402 ms/op

Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.804 ms/op
                 createUser·p0.999:  10.296 ms/op
                 createUser·p0.9999: 12.878 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   3: 2.593 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  9.056 ms/op
                 createUser·p0.9999: 10.912 ms/op
                 createUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371216
  mean =      2.583 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 176815 
    [ 2.500,  3.750) = 189423 
    [ 3.750,  5.000) = 3876 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      9.155 ms/op
     p(99.9900) =     13.548 ms/op
     p(99.9990) =     14.020 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 14.041 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  7.297 ms/op
                 existUser·p0.9999: 14.778 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.863 ms/op
                 existUser·p0.999:  8.588 ms/op
                 existUser·p0.9999: 12.262 ms/op
                 existUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385652
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188332 
    [ 2.500,  3.750) = 193194 
    [ 3.750,  5.000) = 3035 
    [ 5.000,  6.250) = 604 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      6.680 ms/op
     p(99.9900) =     13.999 ms/op
     p(99.9990) =     14.891 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.059 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  12.108 ms/op
                 getUser·p0.9999: 14.572 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   2.546 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  9.471 ms/op
                 getUser·p0.9999: 13.736 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.994 ms/op
                 getUser·p0.9999: 12.265 ms/op
                 getUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376510
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 183515 
    [ 2.500,  3.750) = 187345 
    [ 3.750,  5.000) = 3941 
    [ 5.000,  6.250) = 1062 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     14.897 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 4.857 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.779 ms/op
                 listUser·p0.9999: 11.324 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   2: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 10.997 ms/op
                 listUser·p1.00:   11.452 ms/op

Iteration   3: 3.081 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  10.289 ms/op
                 listUser·p0.9999: 11.780 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311982
  mean =      3.074 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 81231 
    [ 2.500,  3.750) = 187601 
    [ 3.750,  5.000) = 34707 
    [ 5.000,  6.250) = 6629 
    [ 6.250,  7.500) = 964 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 201 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     11.544 ms/op
     p(99.9990) =     12.715 ms/op
     p(99.9999) =     12.812 ms/op
    p(100.0000) =     12.812 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.408 ± 1.912  ops/ms
ClientPb.existUser                       thrpt       3  13.043 ± 0.460  ops/ms
ClientPb.getUser                         thrpt       3  12.605 ± 2.674  ops/ms
ClientPb.listUser                        thrpt       3  10.429 ± 1.384  ops/ms
ClientPb.createUser                       avgt       3   2.573 ± 0.135   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.287   ms/op
ClientPb.getUser                          avgt       3   2.524 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.033   ms/op
ClientPb.createUser                     sample  371216   2.583 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.792           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.548           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.402           ms/op
ClientPb.existUser                      sample  385652   2.487 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.795           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.680           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.999           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.057           ms/op
ClientPb.getUser                        sample  376510   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.546           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.454           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.385           ms/op
ClientPb.listUser                       sample  311982   3.074 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.011           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.544           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.812           ms/op
