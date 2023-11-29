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
# Warmup Iteration   1: 5.111 ops/ms
# Warmup Iteration   2: 12.258 ops/ms
# Warmup Iteration   3: 12.433 ops/ms
Iteration   1: 12.526 ops/ms
Iteration   2: 12.825 ops/ms
Iteration   3: 12.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.698 ±(99.9%) 2.821 ops/ms [Average]
  (min, avg, max) = (12.526, 12.698, 12.825), stdev = 0.155
  CI (99.9%): [9.877, 15.519] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ops/ms
# Warmup Iteration   2: 13.251 ops/ms
# Warmup Iteration   3: 13.142 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 13.081 ops/ms
Iteration   3: 13.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.054 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (13.026, 13.054, 13.081), stdev = 0.028
  CI (99.9%): [12.550, 13.559] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.335 ops/ms
# Warmup Iteration   2: 12.650 ops/ms
# Warmup Iteration   3: 12.653 ops/ms
Iteration   1: 12.863 ops/ms
Iteration   2: 12.642 ops/ms
Iteration   3: 12.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.766 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (12.642, 12.766, 12.863), stdev = 0.113
  CI (99.9%): [10.699, 14.833] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.736 ops/ms
# Warmup Iteration   2: 10.201 ops/ms
# Warmup Iteration   3: 10.503 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.493 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.475 ±(99.9%) 0.530 ops/ms [Average]
  (min, avg, max) = (10.441, 10.475, 10.493), stdev = 0.029
  CI (99.9%): [9.944, 11.005] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.003 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.502, 2.505, 2.509), stdev = 0.004
  CI (99.9%): [2.435, 2.576] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.681 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.469 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.005 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.436 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.423, 2.436, 2.449), stdev = 0.013
  CI (99.9%): [2.202, 2.670] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.800 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
Iteration   1: 2.517 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.488, 2.502, 2.517), stdev = 0.014
  CI (99.9%): [2.238, 2.765] (assumes normal distribution)


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.005 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.003 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.992, 3.003, 3.013), stdev = 0.010
  CI (99.9%): [2.813, 3.194] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  10.195 ms/op
                 createUser·p0.9999: 13.693 ms/op
                 createUser·p1.00:   13.943 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.229 ms/op
                 createUser·p0.9999: 12.323 ms/op
                 createUser·p1.00:   13.222 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  9.000 ms/op
                 createUser·p0.9999: 11.454 ms/op
                 createUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384270
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 185160 
    [ 2.500,  3.750) = 194794 
    [ 3.750,  5.000) = 3461 
    [ 5.000,  6.250) = 340 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.981 ms/op
     p(99.9900) =     13.222 ms/op
     p(99.9990) =     13.863 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.680 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  5.523 ms/op
                 existUser·p0.9999: 13.795 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.100 ms/op
                 existUser·p0.9999: 14.239 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  6.758 ms/op
                 existUser·p0.9999: 12.061 ms/op
                 existUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389188
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 187258 
    [ 2.500,  3.750) = 198470 
    [ 3.750,  5.000) = 2680 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 117 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      6.765 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     14.371 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.920 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  11.490 ms/op
                 getUser·p0.9999: 14.102 ms/op
                 getUser·p1.00:   14.549 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  9.266 ms/op
                 getUser·p0.9999: 14.208 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.369 ms/op
                 getUser·p0.9999: 12.076 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382376
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 188783 
    [ 2.500,  3.750) = 188011 
    [ 3.750,  5.000) = 4137 
    [ 5.000,  6.250) = 878 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.010 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     13.968 ms/op
     p(99.9990) =     14.850 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.059 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   5.980 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.256 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.903 ms/op
                 listUser·p0.9999: 12.243 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.469 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315967
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 91195 
    [ 2.500,  3.750) = 182954 
    [ 3.750,  5.000) = 32673 
    [ 5.000,  6.250) = 7165 
    [ 6.250,  7.500) = 1018 
    [ 7.500,  8.750) = 295 
    [ 8.750, 10.000) = 295 
    [10.000, 11.250) = 172 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     11.715 ms/op
     p(99.9990) =     14.201 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.698 ± 2.821  ops/ms
ClientPb.existUser                       thrpt       3  13.054 ± 0.505  ops/ms
ClientPb.getUser                         thrpt       3  12.766 ± 2.067  ops/ms
ClientPb.listUser                        thrpt       3  10.475 ± 0.530  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.071   ms/op
ClientPb.existUser                        avgt       3   2.436 ± 0.234   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.263   ms/op
ClientPb.listUser                         avgt       3   3.003 ± 0.191   ms/op
ClientPb.createUser                     sample  384270   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.916           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.031           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.981           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.222           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.943           ms/op
ClientPb.existUser                      sample  389188   2.464 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.842           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.585           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.765           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.549           ms/op
ClientPb.getUser                        sample  382376   2.508 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.830           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.380           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.968           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.909           ms/op
ClientPb.listUser                       sample  315967   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.764           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.041           ms/op
