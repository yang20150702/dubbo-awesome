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
# Warmup Iteration   1: 4.995 ops/ms
# Warmup Iteration   2: 12.100 ops/ms
# Warmup Iteration   3: 12.600 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.751 ops/ms
Iteration   3: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.797 ±(99.9%) 3.093 ops/ms [Average]
  (min, avg, max) = (12.654, 12.797, 12.984), stdev = 0.170
  CI (99.9%): [9.704, 15.889] (assumes normal distribution)


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
# Warmup Iteration   1: 8.171 ops/ms
# Warmup Iteration   2: 12.939 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 12.809 ops/ms
Iteration   2: 12.973 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.897 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (12.809, 12.897, 12.973), stdev = 0.082
  CI (99.9%): [11.392, 14.401] (assumes normal distribution)


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
# Warmup Iteration   1: 7.203 ops/ms
# Warmup Iteration   2: 12.374 ops/ms
# Warmup Iteration   3: 12.566 ops/ms
Iteration   1: 12.717 ops/ms
Iteration   2: 12.871 ops/ms
Iteration   3: 12.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.738 ±(99.9%) 2.254 ops/ms [Average]
  (min, avg, max) = (12.626, 12.738, 12.871), stdev = 0.124
  CI (99.9%): [10.484, 14.992] (assumes normal distribution)


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
# Warmup Iteration   1: 6.541 ops/ms
# Warmup Iteration   2: 10.387 ops/ms
# Warmup Iteration   3: 10.576 ops/ms
Iteration   1: 10.594 ops/ms
Iteration   2: 10.422 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.491 ±(99.9%) 1.653 ops/ms [Average]
  (min, avg, max) = (10.422, 10.491, 10.594), stdev = 0.091
  CI (99.9%): [8.839, 12.144] (assumes normal distribution)


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.511 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.511, 2.534, 2.556), stdev = 0.023
  CI (99.9%): [2.122, 2.946] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.498 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.489, 2.498, 2.503), stdev = 0.008
  CI (99.9%): [2.357, 2.639] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.003 ms/op
Iteration   1: 2.524 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
Iteration   3: 2.506 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.516 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.506, 2.516, 2.524), stdev = 0.009
  CI (99.9%): [2.357, 2.675] (assumes normal distribution)


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
# Warmup Iteration   1: 4.929 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
Iteration   3: 3.025 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.018 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.005, 3.018, 3.025), stdev = 0.011
  CI (99.9%): [2.820, 3.215] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.549 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  12.707 ms/op
                 createUser·p0.9999: 17.144 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  11.127 ms/op
                 createUser·p0.9999: 16.586 ms/op
                 createUser·p1.00:   17.170 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  8.539 ms/op
                 createUser·p0.9999: 10.256 ms/op
                 createUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379600
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 182899 
    [ 2.500,  5.000) = 195272 
    [ 5.000,  7.500) = 849 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =     10.197 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     18.509 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  6.496 ms/op
                 existUser·p0.9999: 14.021 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   2: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.365 ms/op
                 existUser·p0.9999: 12.891 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  6.653 ms/op
                 existUser·p0.9999: 12.580 ms/op
                 existUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394686
  mean =      2.431 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195810 
    [ 2.500,  3.750) = 195319 
    [ 3.750,  5.000) = 2654 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 131 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      6.458 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 19.720 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  9.203 ms/op
                 getUser·p0.9999: 13.821 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.640 ms/op
                 getUser·p0.9999: 11.188 ms/op
                 getUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380046
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 186579 
    [ 2.500,  3.750) = 186962 
    [ 3.750,  5.000) = 4543 
    [ 5.000,  6.250) = 1404 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.142 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 5.239 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.753 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 11.485 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.570 ms/op
                 listUser·p0.9999: 11.297 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.598 ms/op
                 listUser·p0.9999: 13.428 ms/op
                 listUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320601
  mean =      2.991 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 97386 
    [ 2.500,  3.750) = 185121 
    [ 3.750,  5.000) = 30982 
    [ 5.000,  6.250) = 5536 
    [ 6.250,  7.500) = 781 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 202 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     13.107 ms/op
     p(99.9990) =     13.726 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.797 ± 3.093  ops/ms
ClientPb.existUser                       thrpt       3  12.897 ± 1.505  ops/ms
ClientPb.getUser                         thrpt       3  12.738 ± 2.254  ops/ms
ClientPb.listUser                        thrpt       3  10.491 ± 1.653  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.412   ms/op
ClientPb.existUser                        avgt       3   2.498 ± 0.141   ms/op
ClientPb.getUser                          avgt       3   2.516 ± 0.159   ms/op
ClientPb.listUser                         avgt       3   3.018 ± 0.198   ms/op
ClientPb.createUser                     sample  379600   2.526 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.197           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.024           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.922           ms/op
ClientPb.existUser                      sample  394686   2.431 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.982           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.458           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.385           ms/op
ClientPb.getUser                        sample  380046   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.767           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.142           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.451           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.988           ms/op
ClientPb.listUser                       sample  320601   2.991 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.107           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.894           ms/op
