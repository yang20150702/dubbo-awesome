# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 6.033 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 9.248 ops/ms
Iteration   2: 9.913 ops/ms
Iteration   3: 9.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.531 ±(99.9%) 6.270 ops/ms [Average]
  (min, avg, max) = (9.248, 9.531, 9.913), stdev = 0.344
  CI (99.9%): [3.261, 15.801] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.451 ops/ms
# Warmup Iteration   2: 9.433 ops/ms
# Warmup Iteration   3: 9.779 ops/ms
Iteration   1: 10.683 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.229 ±(99.9%) 7.369 ops/ms [Average]
  (min, avg, max) = (9.909, 10.229, 10.683), stdev = 0.404
  CI (99.9%): [2.860, 17.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.318 ops/ms
# Warmup Iteration   2: 9.248 ops/ms
# Warmup Iteration   3: 9.805 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.937 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.052 ±(99.9%) 6.906 ops/ms [Average]
  (min, avg, max) = (9.744, 10.052, 10.474), stdev = 0.379
  CI (99.9%): [3.145, 16.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ops/ms
# Warmup Iteration   2: 7.617 ops/ms
# Warmup Iteration   3: 8.343 ops/ms
Iteration   1: 8.496 ops/ms
Iteration   2: 8.739 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.591 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (8.496, 8.591, 8.739), stdev = 0.130
  CI (99.9%): [6.226, 10.956] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.191 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.007 ms/op
Iteration   1: 3.231 ±(99.9%) 0.003 ms/op
Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
Iteration   3: 3.138 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.161 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.113, 3.161, 3.231), stdev = 0.062
  CI (99.9%): [2.025, 4.296] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.055 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
Iteration   2: 3.178 ±(99.9%) 0.004 ms/op
Iteration   3: 2.983 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.048 ±(99.9%) 2.048 ms/op [Average]
  (min, avg, max) = (2.983, 3.048, 3.178), stdev = 0.112
  CI (99.9%): [1.001, 5.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.896 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.281 ±(99.9%) 0.002 ms/op
Iteration   1: 3.221 ±(99.9%) 0.003 ms/op
Iteration   2: 3.179 ±(99.9%) 0.002 ms/op
Iteration   3: 3.254 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.179, 3.218, 3.254), stdev = 0.038
  CI (99.9%): [2.529, 3.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.913 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.005 ms/op
Iteration   1: 3.743 ±(99.9%) 0.008 ms/op
Iteration   2: 3.783 ±(99.9%) 0.005 ms/op
Iteration   3: 3.737 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.754 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.737, 3.754, 3.783), stdev = 0.025
  CI (99.9%): [3.295, 4.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.095 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.008 ms/op
Iteration   1: 3.176 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  14.352 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.227 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.169 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  15.338 ms/op
                 createUser·p0.9999: 30.308 ms/op
                 createUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300596
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16567 
    [ 2.500,  5.000) = 278699 
    [ 5.000,  7.500) = 4552 
    [ 7.500, 10.000) = 384 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     14.952 ms/op
     p(99.9900) =     28.537 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.240 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.466 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   5.327 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 19.967 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  11.724 ms/op
                 existUser·p0.9999: 22.350 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  9.630 ms/op
                 existUser·p0.9999: 22.567 ms/op
                 existUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306115
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36270 
    [ 2.500,  5.000) = 264845 
    [ 5.000,  7.500) = 4376 
    [ 7.500, 10.000) = 247 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.973 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     23.261 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.303 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.367 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
Iteration   1: 3.107 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  16.549 ms/op
                 getUser·p0.9999: 18.219 ms/op
                 getUser·p1.00:   19.137 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  10.469 ms/op
                 getUser·p0.9999: 24.019 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.196 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  13.475 ms/op
                 getUser·p0.9999: 19.688 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 306038
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7847 
    [ 2.500,  5.000) = 293694 
    [ 5.000,  7.500) = 3576 
    [ 7.500, 10.000) = 513 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     22.721 ms/op
     p(99.9990) =     24.599 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.366 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.011 ms/op
Iteration   1: 3.775 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 27.594 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 3.811 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.174 ms/op
                 listUser·p0.999:  14.172 ms/op
                 listUser·p0.9999: 15.191 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   3: 3.804 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252992
  mean =      3.797 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 245087 
    [ 5.000,  7.500) = 5950 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     25.028 ms/op
     p(99.9990) =     28.491 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.531 ± 6.270  ops/ms
ClientPb.existUser                       thrpt       3  10.229 ± 7.369  ops/ms
ClientPb.getUser                         thrpt       3  10.052 ± 6.906  ops/ms
ClientPb.listUser                        thrpt       3   8.591 ± 2.365  ops/ms
ClientPb.createUser                       avgt       3   3.161 ± 1.136   ms/op
ClientPb.existUser                        avgt       3   3.048 ± 2.048   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 0.689   ms/op
ClientPb.listUser                         avgt       3   3.754 ± 0.459   ms/op
ClientPb.createUser                     sample  300596   3.190 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.143           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.999           ms/op
ClientPb.existUser                      sample  306115   3.136 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.814           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.973           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.495           ms/op
ClientPb.getUser                        sample  306038   3.135 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.196           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.456           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.763           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.721           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.674           ms/op
ClientPb.listUser                       sample  252992   3.797 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.078           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.028           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
