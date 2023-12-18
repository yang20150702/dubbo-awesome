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
# Warmup Iteration   1: 4.554 ops/ms
# Warmup Iteration   2: 12.011 ops/ms
# Warmup Iteration   3: 12.200 ops/ms
Iteration   1: 12.644 ops/ms
Iteration   2: 12.654 ops/ms
Iteration   3: 12.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.599 ±(99.9%) 1.573 ops/ms [Average]
  (min, avg, max) = (12.500, 12.599, 12.654), stdev = 0.086
  CI (99.9%): [11.026, 14.172] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ops/ms
# Warmup Iteration   2: 13.183 ops/ms
# Warmup Iteration   3: 13.023 ops/ms
Iteration   1: 13.168 ops/ms
Iteration   2: 13.102 ops/ms
Iteration   3: 13.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.136 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (13.102, 13.136, 13.168), stdev = 0.033
  CI (99.9%): [12.533, 13.740] (assumes normal distribution)


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
# Warmup Iteration   1: 7.942 ops/ms
# Warmup Iteration   2: 12.602 ops/ms
# Warmup Iteration   3: 12.790 ops/ms
Iteration   1: 12.837 ops/ms
Iteration   2: 12.964 ops/ms
Iteration   3: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.914 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (12.837, 12.914, 12.964), stdev = 0.067
  CI (99.9%): [11.687, 14.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.665 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.757 ops/ms
Iteration   2: 10.817 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.757 ±(99.9%) 1.099 ops/ms [Average]
  (min, avg, max) = (10.697, 10.757, 10.817), stdev = 0.060
  CI (99.9%): [9.658, 11.857] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.989 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.482 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (2.464, 2.482, 2.499), stdev = 0.018
  CI (99.9%): [2.160, 2.803] (assumes normal distribution)


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.474 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.468 ±(99.9%) 0.096 ms/op [Average]
  (min, avg, max) = (2.464, 2.468, 2.474), stdev = 0.005
  CI (99.9%): [2.373, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.478, 2.493, 2.502), stdev = 0.013
  CI (99.9%): [2.259, 2.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 2.962 ±(99.9%) 0.006 ms/op
Iteration   2: 2.968 ±(99.9%) 0.004 ms/op
Iteration   3: 2.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.054 ms/op [Average]
  (min, avg, max) = (2.962, 2.965, 2.968), stdev = 0.003
  CI (99.9%): [2.910, 3.019] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  7.200 ms/op
                 createUser·p0.9999: 13.879 ms/op
                 createUser·p1.00:   14.598 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.297 ms/op
                 createUser·p0.9999: 14.913 ms/op
                 createUser·p1.00:   15.630 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.366 ms/op
                 createUser·p0.9999: 10.750 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385468
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 187708 
    [ 2.500,  3.750) = 193785 
    [ 3.750,  5.000) = 3098 
    [ 5.000,  6.250) = 402 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      8.329 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     15.245 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.450 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  5.986 ms/op
                 existUser·p0.9999: 13.515 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.383 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 12.940 ms/op
                 existUser·p1.00:   13.402 ms/op

Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.404 ms/op
                 existUser·p0.999:  9.208 ms/op
                 existUser·p0.9999: 11.597 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394079
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 194906 
    [ 2.500,  3.750) = 196737 
    [ 3.750,  5.000) = 1714 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.453 ms/op
     p(99.9000) =      8.271 ms/op
     p(99.9900) =     13.140 ms/op
     p(99.9990) =     13.864 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  12.203 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.510 ms/op
                 getUser·p0.999:  8.589 ms/op
                 getUser·p0.9999: 14.643 ms/op
                 getUser·p1.00:   15.679 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  8.139 ms/op
                 getUser·p0.9999: 10.005 ms/op
                 getUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382716
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 189735 
    [ 2.500,  5.000) = 192044 
    [ 5.000,  7.500) = 553 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.785 ms/op
     p(99.9000) =      8.139 ms/op
     p(99.9900) =     15.265 ms/op
     p(99.9990) =     22.490 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.008 ms/op
Iteration   1: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.371 ms/op
                 listUser·p1.00:   11.731 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.444 ms/op
                 listUser·p0.9999: 11.644 ms/op
                 listUser·p1.00:   11.960 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.470 ms/op
                 listUser·p0.9999: 10.961 ms/op
                 listUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319752
  mean =      3.000 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 94839 
    [ 2.500,  3.750) = 186025 
    [ 3.750,  5.000) = 31647 
    [ 5.000,  6.250) = 5713 
    [ 6.250,  7.500) = 750 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 196 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      8.868 ms/op
     p(99.9900) =     11.011 ms/op
     p(99.9990) =     11.895 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.599 ± 1.573  ops/ms
ClientPb.existUser                       thrpt       3  13.136 ± 0.603  ops/ms
ClientPb.getUser                         thrpt       3  12.914 ± 1.227  ops/ms
ClientPb.listUser                        thrpt       3  10.757 ± 1.099  ops/ms
ClientPb.createUser                       avgt       3   2.482 ± 0.322   ms/op
ClientPb.existUser                        avgt       3   2.468 ± 0.096   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.233   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.054   ms/op
ClientPb.createUser                     sample  385468   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.743           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.329           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.910           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.630           ms/op
ClientPb.existUser                      sample  394079   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.453           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.271           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.140           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  382716   2.506 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.139           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.265           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.577           ms/op
ClientPb.listUser                       sample  319752   3.000 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.868           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.011           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.960           ms/op
