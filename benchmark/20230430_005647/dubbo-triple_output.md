# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.803 ops/ms
# Warmup Iteration   2: 4.648 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.517 ops/ms
Iteration   2: 8.917 ops/ms
Iteration   3: 8.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.690 ±(99.9%) 3.746 ops/ms [Average]
  (min, avg, max) = (8.517, 8.690, 8.917), stdev = 0.205
  CI (99.9%): [4.944, 12.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.773 ops/ms
# Warmup Iteration   2: 8.112 ops/ms
# Warmup Iteration   3: 8.566 ops/ms
Iteration   1: 8.961 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.232 ±(99.9%) 4.298 ops/ms [Average]
  (min, avg, max) = (8.961, 9.232, 9.387), stdev = 0.236
  CI (99.9%): [4.935, 13.530] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.602 ops/ms
# Warmup Iteration   2: 7.304 ops/ms
# Warmup Iteration   3: 8.550 ops/ms
Iteration   1: 8.901 ops/ms
Iteration   2: 8.425 ops/ms
Iteration   3: 8.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.733 ±(99.9%) 4.880 ops/ms [Average]
  (min, avg, max) = (8.425, 8.733, 8.901), stdev = 0.267
  CI (99.9%): [3.853, 13.614] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.460 ops/ms
# Warmup Iteration   2: 6.587 ops/ms
# Warmup Iteration   3: 7.528 ops/ms
Iteration   1: 7.492 ops/ms
Iteration   2: 7.145 ops/ms
Iteration   3: 7.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.242 ±(99.9%) 3.990 ops/ms [Average]
  (min, avg, max) = (7.088, 7.242, 7.492), stdev = 0.219
  CI (99.9%): [3.251, 11.232] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.162 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.841 ±(99.9%) 0.008 ms/op
Iteration   2: 3.552 ±(99.9%) 0.010 ms/op
Iteration   3: 3.719 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.704 ±(99.9%) 2.639 ms/op [Average]
  (min, avg, max) = (3.552, 3.704, 3.841), stdev = 0.145
  CI (99.9%): [1.065, 6.343] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.646 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.760 ±(99.9%) 0.005 ms/op
Iteration   1: 3.426 ±(99.9%) 0.011 ms/op
Iteration   2: 3.463 ±(99.9%) 0.008 ms/op
Iteration   3: 3.376 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.421 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.376, 3.421, 3.463), stdev = 0.044
  CI (99.9%): [2.624, 4.219] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.255 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.790 ±(99.9%) 0.002 ms/op
Iteration   1: 3.613 ±(99.9%) 0.006 ms/op
Iteration   2: 3.701 ±(99.9%) 0.006 ms/op
Iteration   3: 3.637 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.650 ±(99.9%) 0.836 ms/op [Average]
  (min, avg, max) = (3.613, 3.650, 3.701), stdev = 0.046
  CI (99.9%): [2.814, 4.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.726 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.926 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.415 ±(99.9%) 0.011 ms/op
Iteration   1: 4.326 ±(99.9%) 0.009 ms/op
Iteration   2: 4.222 ±(99.9%) 0.012 ms/op
Iteration   3: 4.189 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.246 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (4.189, 4.246, 4.326), stdev = 0.072
  CI (99.9%): [2.937, 5.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.348 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.017 ms/op
Iteration   1: 3.767 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 24.265 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   2: 3.736 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   8.067 ms/op
                 createUser·p0.999:  15.419 ms/op
                 createUser·p0.9999: 28.475 ms/op
                 createUser·p1.00:   28.934 ms/op

Iteration   3: 3.729 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.769 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  24.674 ms/op
                 createUser·p0.9999: 31.326 ms/op
                 createUser·p1.00:   31.982 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 256479
  mean =      3.744 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2084 
    [ 2.500,  5.000) = 244292 
    [ 5.000,  7.500) = 7348 
    [ 7.500, 10.000) = 2021 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.427 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     21.611 ms/op
     p(99.9900) =     30.682 ms/op
     p(99.9990) =     31.846 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 10.543 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.634 ±(99.9%) 0.012 ms/op
Iteration   1: 3.440 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  19.164 ms/op
                 existUser·p0.9999: 23.495 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.434 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  12.009 ms/op
                 existUser·p0.9999: 24.959 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.740 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.486 ms/op
                 existUser·p0.999:  25.673 ms/op
                 existUser·p0.9999: 30.129 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 271797
  mean =      3.532 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3593 
    [ 2.500,  5.000) = 261790 
    [ 5.000,  7.500) = 5167 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     13.786 ms/op
     p(99.9900) =     29.196 ms/op
     p(99.9990) =     31.059 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.986 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.455 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.012 ms/op
Iteration   1: 3.688 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.968 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  16.000 ms/op
                 getUser·p0.9999: 25.275 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   2: 3.620 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.778 ms/op
                 getUser·p0.50:   3.523 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.636 ms/op
                 getUser·p0.999:  24.248 ms/op
                 getUser·p0.9999: 26.739 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   3: 3.719 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  26.379 ms/op
                 getUser·p0.9999: 30.566 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 261043
  mean =      3.675 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5542 
    [ 2.500,  5.000) = 243695 
    [ 5.000,  7.500) = 10231 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 115 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     18.218 ms/op
     p(99.9900) =     29.786 ms/op
     p(99.9990) =     30.749 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.872 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 5.116 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.016 ms/op
Iteration   1: 4.394 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  24.945 ms/op
                 listUser·p0.9999: 27.670 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 4.238 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.946 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 19.905 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.298 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.219 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   7.733 ms/op
                 listUser·p0.999:  18.928 ms/op
                 listUser·p0.9999: 24.169 ms/op
                 listUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222669
  mean =      4.309 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 207600 
    [ 5.000,  7.500) = 11853 
    [ 7.500, 10.000) = 2312 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      4.211 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     26.712 ms/op
     p(99.9990) =     27.965 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.690 ± 3.746  ops/ms
ClientPb.existUser                       thrpt       3   9.232 ± 4.298  ops/ms
ClientPb.getUser                         thrpt       3   8.733 ± 4.880  ops/ms
ClientPb.listUser                        thrpt       3   7.242 ± 3.990  ops/ms
ClientPb.createUser                       avgt       3   3.704 ± 2.639   ms/op
ClientPb.existUser                        avgt       3   3.421 ± 0.798   ms/op
ClientPb.getUser                          avgt       3   3.650 ± 0.836   ms/op
ClientPb.listUser                         avgt       3   4.246 ± 1.309   ms/op
ClientPb.createUser                     sample  256479   3.744 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.427           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.627           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.611           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.682           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  271797   3.532 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.313           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.786           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.196           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.228           ms/op
ClientPb.getUser                        sample  261043   3.675 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.218           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  222669   4.309 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.562           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.712           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672           ms/op
