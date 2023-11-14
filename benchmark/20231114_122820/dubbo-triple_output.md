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
# Warmup Iteration   1: 5.011 ops/ms
# Warmup Iteration   2: 12.363 ops/ms
# Warmup Iteration   3: 12.330 ops/ms
Iteration   1: 12.759 ops/ms
Iteration   2: 12.679 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.781 ±(99.9%) 2.075 ops/ms [Average]
  (min, avg, max) = (12.679, 12.781, 12.904), stdev = 0.114
  CI (99.9%): [10.705, 14.856] (assumes normal distribution)


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
# Warmup Iteration   1: 8.340 ops/ms
# Warmup Iteration   2: 13.027 ops/ms
# Warmup Iteration   3: 13.077 ops/ms
Iteration   1: 13.194 ops/ms
Iteration   2: 13.214 ops/ms
Iteration   3: 13.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.165 ±(99.9%) 1.239 ops/ms [Average]
  (min, avg, max) = (13.088, 13.165, 13.214), stdev = 0.068
  CI (99.9%): [11.927, 14.404] (assumes normal distribution)


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
# Warmup Iteration   1: 7.809 ops/ms
# Warmup Iteration   2: 12.584 ops/ms
# Warmup Iteration   3: 12.733 ops/ms
Iteration   1: 12.925 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 12.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.903 ±(99.9%) 0.734 ops/ms [Average]
  (min, avg, max) = (12.857, 12.903, 12.927), stdev = 0.040
  CI (99.9%): [12.169, 13.637] (assumes normal distribution)


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
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 10.578 ops/ms
# Warmup Iteration   3: 10.782 ops/ms
Iteration   1: 10.712 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.720 ±(99.9%) 0.119 ops/ms [Average]
  (min, avg, max) = (10.712, 10.720, 10.724), stdev = 0.007
  CI (99.9%): [10.601, 10.839] (assumes normal distribution)


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.004 ms/op
Iteration   1: 2.495 ±(99.9%) 0.004 ms/op
Iteration   2: 2.501 ±(99.9%) 0.003 ms/op
Iteration   3: 2.525 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.507 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.495, 2.507, 2.525), stdev = 0.016
  CI (99.9%): [2.216, 2.798] (assumes normal distribution)


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.421 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.003 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (2.430, 2.441, 2.458), stdev = 0.015
  CI (99.9%): [2.171, 2.710] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (2.469, 2.493, 2.507), stdev = 0.021
  CI (99.9%): [2.118, 2.869] (assumes normal distribution)


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 2.955 ±(99.9%) 0.006 ms/op
Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
Iteration   3: 2.972 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.161 ms/op [Average]
  (min, avg, max) = (2.955, 2.965, 2.972), stdev = 0.009
  CI (99.9%): [2.804, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 3.965 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.903 ms/op
                 createUser·p0.999:  11.370 ms/op
                 createUser·p0.9999: 13.486 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  9.192 ms/op
                 createUser·p0.9999: 12.196 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.703 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384472
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 187272 
    [ 2.500,  3.750) = 193010 
    [ 3.750,  5.000) = 3125 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     12.772 ms/op
     p(99.9990) =     13.814 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.698 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.402 ms/op
                 existUser·p0.50:   2.650 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  10.329 ms/op
                 existUser·p0.9999: 23.167 ms/op
                 existUser·p1.00:   25.166 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.927 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.042 ms/op
                 existUser·p0.9999: 15.005 ms/op
                 existUser·p1.00:   15.778 ms/op

Iteration   3: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  7.646 ms/op
                 existUser·p0.9999: 20.380 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 379993
  mean =      2.525 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185333 
    [ 2.500,  5.000) = 188831 
    [ 5.000,  7.500) = 5005 
    [ 7.500, 10.000) = 489 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     24.668 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.007 ms/op
Iteration   1: 2.492 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   2.413 ms/op
                 getUser·p0.90:   3.265 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  12.612 ms/op
                 getUser·p0.9999: 15.139 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   2: 2.432 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.372 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.453 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.873 ms/op
                 getUser·p0.9999: 14.238 ms/op
                 getUser·p1.00:   15.122 ms/op

Iteration   3: 2.441 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.367 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.498 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  9.143 ms/op
                 getUser·p0.9999: 13.582 ms/op
                 getUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390704
  mean =      2.455 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 467 
    [ 1.250,  2.500) = 220009 
    [ 2.500,  3.750) = 156961 
    [ 3.750,  5.000) = 11538 
    [ 5.000,  6.250) = 1090 
    [ 6.250,  7.500) = 173 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 104 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.384 ms/op
     p(90.0000) =      3.178 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.370 ms/op
     p(99.9900) =     14.597 ms/op
     p(99.9990) =     15.514 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.009 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.878 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.945 ms/op
                 listUser·p0.9999: 12.780 ms/op
                 listUser·p1.00:   14.008 ms/op

Iteration   2: 2.965 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  10.525 ms/op
                 listUser·p0.9999: 12.394 ms/op
                 listUser·p1.00:   13.189 ms/op

Iteration   3: 2.935 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.325 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.390 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324204
  mean =      2.958 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 105816 
    [ 2.500,  3.750) = 178614 
    [ 3.750,  5.000) = 33178 
    [ 5.000,  6.250) = 4954 
    [ 6.250,  7.500) = 562 
    [ 7.500,  8.750) = 267 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 200 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     12.561 ms/op
     p(99.9990) =     13.521 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.781 ± 2.075  ops/ms
ClientPb.existUser                       thrpt       3  13.165 ± 1.239  ops/ms
ClientPb.getUser                         thrpt       3  12.903 ± 0.734  ops/ms
ClientPb.listUser                        thrpt       3  10.720 ± 0.119  ops/ms
ClientPb.createUser                       avgt       3   2.507 ± 0.291   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.269   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.376   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.161   ms/op
ClientPb.createUser                     sample  384472   2.494 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.779           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.772           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  379993   2.525 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.402           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.372           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.166           ms/op
ClientPb.getUser                        sample  390704   2.455 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.613           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.384           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.370           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.597           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.138           ms/op
ClientPb.listUser                       sample  324204   2.958 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.043           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.008           ms/op
