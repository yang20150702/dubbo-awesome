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
# Warmup Iteration   1: 5.108 ops/ms
# Warmup Iteration   2: 11.882 ops/ms
# Warmup Iteration   3: 12.086 ops/ms
Iteration   1: 12.185 ops/ms
Iteration   2: 12.296 ops/ms
Iteration   3: 12.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.263 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (12.185, 12.263, 12.310), stdev = 0.069
  CI (99.9%): [11.013, 13.514] (assumes normal distribution)


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
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 12.642 ops/ms
# Warmup Iteration   3: 12.911 ops/ms
Iteration   1: 12.887 ops/ms
Iteration   2: 12.951 ops/ms
Iteration   3: 12.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.905 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (12.878, 12.905, 12.951), stdev = 0.040
  CI (99.9%): [12.175, 13.636] (assumes normal distribution)


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
# Warmup Iteration   1: 7.843 ops/ms
# Warmup Iteration   2: 12.361 ops/ms
# Warmup Iteration   3: 12.713 ops/ms
Iteration   1: 12.669 ops/ms
Iteration   2: 12.786 ops/ms
Iteration   3: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.768 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (12.669, 12.768, 12.850), stdev = 0.092
  CI (99.9%): [11.090, 14.446] (assumes normal distribution)


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
# Warmup Iteration   1: 6.498 ops/ms
# Warmup Iteration   2: 10.333 ops/ms
# Warmup Iteration   3: 10.371 ops/ms
Iteration   1: 10.371 ops/ms
Iteration   2: 10.405 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.375 ±(99.9%) 0.521 ops/ms [Average]
  (min, avg, max) = (10.348, 10.375, 10.405), stdev = 0.029
  CI (99.9%): [9.854, 10.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.004 ms/op
Iteration   1: 2.592 ±(99.9%) 0.003 ms/op
Iteration   2: 2.632 ±(99.9%) 0.004 ms/op
Iteration   3: 2.577 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.600 ±(99.9%) 0.526 ms/op [Average]
  (min, avg, max) = (2.577, 2.600, 2.632), stdev = 0.029
  CI (99.9%): [2.075, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.775 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.003 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
Iteration   3: 2.508 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.504 ±(99.9%) 0.073 ms/op [Average]
  (min, avg, max) = (2.501, 2.504, 2.508), stdev = 0.004
  CI (99.9%): [2.431, 2.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.003 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.533 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.516, 2.533, 2.549), stdev = 0.016
  CI (99.9%): [2.235, 2.831] (assumes normal distribution)


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
Iteration   2: 3.026 ±(99.9%) 0.006 ms/op
Iteration   3: 3.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.032 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.026, 3.032, 3.042), stdev = 0.009
  CI (99.9%): [2.874, 3.190] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.755 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.934 ms/op
                 createUser·p0.999:  11.109 ms/op
                 createUser·p0.9999: 25.743 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 2.604 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.030 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.297 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  10.145 ms/op
                 createUser·p0.9999: 13.454 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 11.960 ms/op
                 createUser·p1.00:   12.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 371594
  mean =      2.581 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 174339 
    [ 2.500,  5.000) = 195893 
    [ 5.000,  7.500) = 959 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      9.493 ms/op
     p(99.9900) =     14.661 ms/op
     p(99.9990) =     26.209 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.281 ms/op
                 existUser·p0.9999: 13.372 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  8.928 ms/op
                 existUser·p0.9999: 13.766 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.781 ms/op
                 existUser·p0.999:  8.262 ms/op
                 existUser·p0.9999: 12.684 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384623
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 187421 
    [ 2.500,  3.750) = 193912 
    [ 3.750,  5.000) = 2372 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 128 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.629 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     13.313 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.085 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 13.636 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 13.527 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.113 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 12.000 ms/op
                 getUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379575
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 185597 
    [ 2.500,  3.750) = 189046 
    [ 3.750,  5.000) = 3889 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.625 ms/op
     p(99.9900) =     13.322 ms/op
     p(99.9990) =     14.081 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.009 ms/op
Iteration   1: 3.092 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.857 ms/op
                 listUser·p0.999:  9.332 ms/op
                 listUser·p0.9999: 14.133 ms/op
                 listUser·p1.00:   14.516 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.331 ms/op
                 listUser·p0.9999: 10.840 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.904 ms/op
                 listUser·p0.9999: 11.386 ms/op
                 listUser·p1.00:   11.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310398
  mean =      3.090 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 79706 
    [ 2.500,  3.750) = 185809 
    [ 3.750,  5.000) = 36131 
    [ 5.000,  6.250) = 7136 
    [ 6.250,  7.500) = 903 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 149 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.253 ms/op
     p(99.9990) =     14.427 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.263 ± 1.251  ops/ms
ClientPb.existUser                       thrpt       3  12.905 ± 0.730  ops/ms
ClientPb.getUser                         thrpt       3  12.768 ± 1.678  ops/ms
ClientPb.listUser                        thrpt       3  10.375 ± 0.521  ops/ms
ClientPb.createUser                       avgt       3   2.600 ± 0.526   ms/op
ClientPb.existUser                        avgt       3   2.504 ± 0.073   ms/op
ClientPb.getUser                          avgt       3   2.533 ± 0.298   ms/op
ClientPb.listUser                         avgt       3   3.032 ± 0.158   ms/op
ClientPb.createUser                     sample  371594   2.581 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.847           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.493           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.661           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.296           ms/op
ClientPb.existUser                      sample  384623   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.985           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.799           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.303           ms/op
ClientPb.getUser                        sample  379575   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.802           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.625           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.322           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.680           ms/op
ClientPb.listUser                       sample  310398   3.090 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.027           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.486           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.253           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.516           ms/op
