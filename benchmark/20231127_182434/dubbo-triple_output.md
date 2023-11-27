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
# Warmup Iteration   1: 3.888 ops/ms
# Warmup Iteration   2: 11.318 ops/ms
# Warmup Iteration   3: 11.525 ops/ms
Iteration   1: 12.003 ops/ms
Iteration   2: 12.027 ops/ms
Iteration   3: 12.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.023 ±(99.9%) 0.331 ops/ms [Average]
  (min, avg, max) = (12.003, 12.023, 12.039), stdev = 0.018
  CI (99.9%): [11.692, 12.354] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 12.411 ops/ms
# Warmup Iteration   3: 12.429 ops/ms
Iteration   1: 12.406 ops/ms
Iteration   2: 12.455 ops/ms
Iteration   3: 12.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.453 ±(99.9%) 0.839 ops/ms [Average]
  (min, avg, max) = (12.406, 12.453, 12.498), stdev = 0.046
  CI (99.9%): [11.614, 13.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.057 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.348 ops/ms
Iteration   1: 12.402 ops/ms
Iteration   2: 12.145 ops/ms
Iteration   3: 12.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.251 ±(99.9%) 2.458 ops/ms [Average]
  (min, avg, max) = (12.145, 12.251, 12.402), stdev = 0.135
  CI (99.9%): [9.792, 14.709] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.654 ops/ms
# Warmup Iteration   2: 9.867 ops/ms
# Warmup Iteration   3: 10.000 ops/ms
Iteration   1: 10.091 ops/ms
Iteration   2: 10.033 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.016 ±(99.9%) 1.544 ops/ms [Average]
  (min, avg, max) = (9.924, 10.016, 10.091), stdev = 0.085
  CI (99.9%): [8.472, 11.560] (assumes normal distribution)


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.748 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.654 ±(99.9%) 0.004 ms/op
Iteration   1: 2.629 ±(99.9%) 0.004 ms/op
Iteration   2: 2.707 ±(99.9%) 0.004 ms/op
Iteration   3: 2.592 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.643 ±(99.9%) 1.067 ms/op [Average]
  (min, avg, max) = (2.592, 2.643, 2.707), stdev = 0.059
  CI (99.9%): [1.575, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.004 ms/op
Iteration   1: 2.568 ±(99.9%) 0.003 ms/op
Iteration   2: 2.574 ±(99.9%) 0.004 ms/op
Iteration   3: 2.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.566 ±(99.9%) 0.155 ms/op [Average]
  (min, avg, max) = (2.557, 2.566, 2.574), stdev = 0.008
  CI (99.9%): [2.412, 2.721] (assumes normal distribution)


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.699 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.602 ±(99.9%) 0.004 ms/op
Iteration   1: 2.612 ±(99.9%) 0.003 ms/op
Iteration   2: 2.611 ±(99.9%) 0.004 ms/op
Iteration   3: 2.636 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.620 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.611, 2.620, 2.636), stdev = 0.014
  CI (99.9%): [2.365, 2.874] (assumes normal distribution)


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
# Warmup Iteration   1: 5.231 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
Iteration   1: 3.186 ±(99.9%) 0.006 ms/op
Iteration   2: 3.170 ±(99.9%) 0.005 ms/op
Iteration   3: 3.143 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.166 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.143, 3.166, 3.186), stdev = 0.022
  CI (99.9%): [2.764, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 4.502 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.789 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.619 ±(99.9%) 0.006 ms/op
Iteration   1: 2.598 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.289 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  12.762 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.583 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.977 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   3: 2.606 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.166 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.043 ms/op
                 createUser·p0.999:  9.224 ms/op
                 createUser·p0.9999: 11.423 ms/op
                 createUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369517
  mean =      2.595 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 173980 
    [ 2.500,  3.750) = 189840 
    [ 3.750,  5.000) = 4478 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 131 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =      9.494 ms/op
     p(99.9900) =     13.911 ms/op
     p(99.9990) =     14.551 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.590 ±(99.9%) 0.006 ms/op
Iteration   1: 2.577 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.133 ms/op
                 existUser·p0.95:   3.252 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  12.597 ms/op
                 existUser·p0.9999: 14.382 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.203 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.086 ms/op
                 existUser·p0.9999: 14.136 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.658 ms/op
                 existUser·p0.90:   3.105 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  9.350 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 374744
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 179713 
    [ 2.500,  3.750) = 190284 
    [ 3.750,  5.000) = 3676 
    [ 5.000,  6.250) = 595 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 152 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      6.990 ms/op
     p(99.9900) =     14.050 ms/op
     p(99.9990) =     15.061 ms/op
     p(99.9999) =     15.417 ms/op
    p(100.0000) =     15.417 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.753 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.629 ±(99.9%) 0.006 ms/op
Iteration   1: 2.631 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   3.215 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  12.436 ms/op
                 getUser·p0.9999: 15.005 ms/op
                 getUser·p1.00:   15.483 ms/op

Iteration   2: 2.637 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.215 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 15.286 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   3: 2.620 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.642 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.136 ms/op
                 getUser·p0.9999: 11.105 ms/op
                 getUser·p1.00:   11.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 364762
  mean =      2.630 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 171155 
    [ 2.500,  3.750) = 186198 
    [ 3.750,  5.000) = 6025 
    [ 5.000,  6.250) = 855 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 72 
    [13.750, 15.000) = 70 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.842 ms/op
     p(99.9900) =     15.057 ms/op
     p(99.9990) =     15.702 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 5.192 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.009 ms/op
Iteration   1: 3.151 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.072 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.413 ms/op
                 listUser·p0.9999: 11.745 ms/op
                 listUser·p1.00:   12.239 ms/op

Iteration   2: 3.162 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.092 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  10.256 ms/op
                 listUser·p0.9999: 12.170 ms/op
                 listUser·p1.00:   13.484 ms/op

Iteration   3: 3.148 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.965 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.988 ms/op
                 listUser·p0.999:  10.262 ms/op
                 listUser·p0.9999: 11.728 ms/op
                 listUser·p1.00:   11.862 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 304135
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 68042 
    [ 2.500,  3.750) = 185321 
    [ 3.750,  5.000) = 41210 
    [ 5.000,  6.250) = 7516 
    [ 6.250,  7.500) = 1207 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 189 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =      9.861 ms/op
     p(99.9900) =     11.832 ms/op
     p(99.9990) =     13.416 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.023 ± 0.331  ops/ms
ClientPb.existUser                       thrpt       3  12.453 ± 0.839  ops/ms
ClientPb.getUser                         thrpt       3  12.251 ± 2.458  ops/ms
ClientPb.listUser                        thrpt       3  10.016 ± 1.544  ops/ms
ClientPb.createUser                       avgt       3   2.643 ± 1.067   ms/op
ClientPb.existUser                        avgt       3   2.566 ± 0.155   ms/op
ClientPb.getUser                          avgt       3   2.620 ± 0.254   ms/op
ClientPb.listUser                         avgt       3   3.166 ± 0.402   ms/op
ClientPb.createUser                     sample  369517   2.595 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.658           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  374744   2.559 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.938           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.617           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.990           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.050           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.417           ms/op
ClientPb.getUser                        sample  364762   2.630 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.798           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.642           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.842           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.057           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.761           ms/op
ClientPb.listUser                       sample  304135   3.154 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.963           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.096           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.832           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
